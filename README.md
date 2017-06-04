# Snake Game built on elm
[![StackShare](https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/MikeSaprykin/elm-stack)
## Project overview
This is a simple snake game built purely on elm.
Game includes:
* Movement by the Arrow Presses
* Game pausing by hitting space
* Game over if you run into yourself or in the wall of the field
* Grow, if you got the fruit

> You can play the game on [github.pages](https://mikesaprykin.github.io/elm-snake-game/)

## Project structure

```
.
├── README.md                           # Project Readme
├── docs                                # Github.pages deployment page
│   └── index.html                      # Compiled elm file
├── elm-package.json                    # Main elm-package.json file
├── index.html                          # Compiled elm-live file
├── package.json                        # Project npm package.json
├── src                                 # Source files folder
│   └── main.elm                        # Main elm module
└── tests                               # Tests folder
    ├── Main.elm                        # Main tests elm module
    ├── Tests.elm                       # Elm Tests file 
    └── elm-package.json                # Elm Tests elm-package.json
```

## Project todos:

* [ ] Split the game code by files and modules
* [ ] Add unit tests with elm-test package
* [ ] Add menu with game configurations
* [ ] Add menu with game statistics
* [ ] Add server support
* [ ] Write server with node.js 
* [ ] Close all enhancements in github.repo

> The initial version of this project was made,
watching [this cool tutorial](https://www.youtube.com/watch?v=okt6-T0IiNI)
