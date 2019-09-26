# # Pokedex Haskell Project
Pokedex website made using haskell's web framework yesod for the functional programming classes at FATEC Rubens Lara for the System's Development and Analysis' degree.
Professor Alexandre Garcia.

# Pokedex

The Pokédex (ポケモン図鑑 Pokemon Zukan) is an electronic device designed to catalogue and provide information regarding the various species of Pokémon featured in the Pokémon video game, anime and manga series.

# Yesod

Yesod is a Haskell web framework for productive development of type-safe, RESTful, high performance web applications.

## Installation

Follow the FP Complete get started guide to get the Stack build tool on the link: https://tech.fpcomplete.com/haskell/get-started.

Clone this project.

Install the yesod command line tool: 
```bash
stack install yesod-bin --install-ghc
```

Build libraries:
```bash
 stack build
 stack build yesod-bin
```
## Serving

Launch devel server: 
```bash
stack exec -- yesod devel
```
View your Yesod site at http://localhost:3000/

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
