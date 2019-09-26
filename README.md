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



## VSCode Shakespeare Extension

There is no Yesod or Shakespeare extension in VSCode yet which could support the hamlet file extension. Because of that, we can force vscode to read shakespeare syntax as HTML, CSS and JS files.

# Step 1

Open the settings screen.

# Step 2

In the Settings Screen you can see the override options of the default settings. You can apply settings changes for all of your personal projects (User Settings), for a whole Workspace (more specific) or even more fine grained to a folder. We will apply the changes to all of our projects.

We would like to make the following mapping:

Hamlet files (with the .hamlet file extension) should be syntax highlighted as HTML files
Julius files (with the .julius file extension) should be syntax highlighted as JavaScript files
Cassius files (with the .cassius file extension) should be syntax highlighted as CSS files

The settings are defined in JSON, a very common data structure which makes it pretty simple for any developer to adapt. Let's add the following entry:

settings.json
```bash

  "files.associations": {
        "*.hamlet": "html",
        "*.julius": "javascript",
        "*.cassius": "css",
        "*.lucius": "css",
      }
```

Congratulations! You managed to add Shakespeare Templates support to your VSCode installation. If you open one of the files with the mentioned file extension, your code should be syntax highlighted. (Even if hamlet structure does not require the closing tags, the syntax highlighting works surprisingly well. As well do the flow keywords.)



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
