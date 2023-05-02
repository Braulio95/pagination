# Components

Try to not overload components, use your customHooks to work with businessLogic.
Tip: I would not consider Pagination as business logic but try to build a customHook around this logic.

# Design

I will grade this project as 80% Design/Markup/Styles implementation and 20% React/JS.

There's a lot of inspiration in the internet about a Pokedex and Pagination so there's no excuse about it.

Pagination with Pokemons

Follow up from this week's topic.

Note: Instructions are in the submission page.


# Rules

No external libraries (done)

You must use React + TS for this project (done)

App should be hosted somewhere (for ex. GH Pages/Netlify)

You must fork this repo: https://github.com/carmandomx/pagination (done)

You must read the README.md in the base repo. (done)

# Requirements

When the app loads or refreshes the first 9 Pokemons must show (done)

Each Pokemon Card, must containt the following information(done):
    Order (done)
    Name (done)
    Height (done)
    Weight (done)
    Generation when it was introduced (done)
    Types (done)
    Default Sprite (done)

The Types of the Pokemon must show a different background color based on it, you can take inspiration from images of the game. (done)

The app needs an Input element that acts as a search bar that can take numbers or strings and the Grid of Pokemons needs to change to reflect the results(done).

The app needs a dropdown element with all the types of pokemons as options and whenever a type is selected the Grid of Pokemons needs to change to reflect the results (done).

The Grid of Pokemons must include a Pagination component that will allow the user to sort throught all the possible results, the page size must be always 9.

Challenge: Create a toggle that will cycle through the default sprite and shiny sprite if available.

Deliverable:

Create a PR to the base repo and paste the link here.