# PokeShop

Hey all. This is an assignment repository for people to have a stab at in their own PD time. The idea is quite simple, we have some pokemon in our store and we want a basket of the pokemon that we wish to purchase. A basket is made up of any number of pokemons, and we can multiple of the same pokemon. It's best to approach each stage in order, and commit as you go. You can fork or branch - whatever your poison.

Figma designs for all parts are available here: https://www.figma.com/file/g4wXl7qfVaA60nS0z1QPrU/Dev-Challenge?node-id=0%3A1

## Part 1: Listings

First things first, we need to get a list of our pokemon for people to browser. In the repository you should find `data/pokemon.json` with an array full of pokemon objects. You need to turn this into a listing view on the page for people to browse.

## Part 1a: Listing Scroll Behaviour

It's important that our header that contains the basket is always at the top of the screen. So the expectation is that the header remains static at the top of the page as the contents of the store scrolls underneath.

## Part 2: Item Adding

When a user clicks the 'add to basket' icon on an item in the store it should update a badge on the basket in the top right of the screen. This number should reflect the 'total number of pokemons' and allow any number to be added.

## Part 3: Out of Stock

If a user adds all of the available stock for a particular item we need to show that item as out of stock, and not allow any more to be added

## Part 4: Basket Overlay

If a user clicks the basket icon in the top right of the screen, we want to show the current basket state with a line for each type of pokemon, it's number of items and cost. There should also be a running total. If no items are in the basket we should not allow them to open this overlay.
