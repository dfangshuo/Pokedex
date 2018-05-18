# Pokedex

*by Fang Shuo and Shubham*

Pokedex is an iOS app that allows users to search for Pokemon via a number of parameters (like attack points, defence, health etc

## Features
- **Search for Pokemon:** Specify search parameters and view a list of Pokemon that match the criterion
- **Discover Pokemon:** See a featured list of Pokemon, which is a randomly generated list of 20 Pokemon to discover Pokemon you never knew existed.
- **Go online:** Access the web in-app to find out more about a Pokemon you might be interested in.
- **Save your favorites:** Save your favorite Pokemon, so you can look at them again easily next time.


## Implementation

- **Languages:** Swift

Pokedex uses a local JSON data as the exhaustive list of all possible Pokemon. From this list, a narrow, more specific list is generated when the user enters search parameters. 

To save user favorites, data is stored in user defaults so this information can persist between sessions. 

The front-end was built using Swift 4, and the project featured extensive use of TableViews and CollectionViews to display Pokemon in different ways (depending on the user preference).

For this project, I implemented most of the front-end views while my partner (Shubham) handled a lot of the Pokemon Filtering.


