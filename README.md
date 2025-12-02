# DrinkSync

Check it out here: [DrinkSync](https://csci331vm.cs.montana.edu/~w62q346/finalproject/drink-sync/client/build)

## Overview

DrinkSync is a web app where users can be suggested random mixed drinks, look up recipes they're curious about, and save mixed drink recipes they enjoy!

## Features
Below is an overview of key features for each page in the web app.

### Main Drinks Page
Random Drink Suggestion: on the main page, users will immediately be given a random set of recipes until they enter a search query.

Infinite Scroll: the user will continuously be given new results as long as there are still results that match their query. If there is no query, the user will keep receiving random drinks from the CocktailDB API until the API itself runs out of recipes to serve.

Recipe Filtering: users can filter search results by "All Drinks", "Alcoholic", and "Non-alcoholic for their convenience.

### Drink Detail Page

A detailed display of the user's selected recipe.

This page is similar in structure to the drink card components that are displayed on the main Drinks page and the Saved Drinks page, but also includes the following:

* Preparation Instructions
* Buttons to save and remove the recipe from the user's Saved Drinks page.

### Saved Drinks Page

This page displays every drink recipe the user has chosen to save.

Much like the main drinks page, users can click the saved drink card and remove it from their Saved Drink page if desired.

### Persistent Navbar

Throughout the web app, a navigation bar is conveniently always at the top of the screen for the user's convenience and changes to fit the restrictions of the page it's currently rendered on.

### User Registration/Authentication

New users can register and later login to their own account so they can have their own unique Saved Drinks page.

### Guest View

If a new user doesn't want to register, they can choose to continue as a guest from the login page. The website will be functionally identical with the exception that guests are not able to save their own drinks.

## Setup (The Tech Stack)


## Group Members