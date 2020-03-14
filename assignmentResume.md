<p align="center">
<img width="150" height="150" src="https://www.productboard.com/wp-content/themes/productboard/public/images/logo-pb-small.svg">
</p>

# Agustín Silveira
# productboard frontend assignment answer



#### 📝 Do your own initial analysis 
I thought about the user experience and I used as an example both Productboard and Amazon search components. 
I believe the user should be able to receive the most visited search recommendation, that is why I added a field count in my example data file searchSuggestionData.json.
In this case, I didn't slice the array because a good practice would be sending a limited amount of suggestions filtered by most visited from the API.

## USER EXPERIENCE

- The user should be able to get suggestions by writing in the search board
- User should be able to select a suggestion and when it is selected it should replace the value of the search bar
- The user should be able to search for the product once it is selected or directly search with the search button.
- If there is no match with our result I follow Amazon example and don't show anything
- If the user decides to click the search button with a search param that didn't give him/her/them any suggestion it should make a search against the API and look over all the data and not only the most searched and then send him/her/them to the page with the result. 

- The suggestion should change color while hovered or focused
#### 🔍️ Do an effort estimate 

I divided the component in two, a search bar and the suggestion list. I would divide the component into smaller pieces if more functionalities were added. 
I also estimated the time it would take to build and style the component. 
## ESTIMATIONS
- 40 minutes to decide what modules to use and think about the component and how it should work. 
- 20 - 30 minutes to install modules and configure them. 
- 1 hour to build the search bar component and style it.
- 1 - 2 hours to build the suggestions list component and style it.
- 1 hour to write the specs and the readme with the explanations of the technical assignment.

- 30 min to review and fix bugs or improve code and style.


#### Tools 
 - React
 - Prettier
 - EsLint
 - Styled Components

#### What would I improve or implement
- I would implement a loading component. I would do this in case calls to an API are implemented.
- I would implement calls to an API
- I would implement an "erase all component" like in productboard so the user can erase the whole search by clicking it.
- I would improve the style and make it even more similar to the productboard style.
