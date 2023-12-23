---
comments: true
description: My Python-learning journey for automating the finding of a Pokémon
---
# Automating rare Pokémon searching with Python
My journey of learning Python began hoping to automate searching for a very rare Pokémon.

### For the Pokémon-uninitiated
Pokémon is a game about collecting, befriending, training, and battling with hundreds of unique creatures. One that is especially hard to add to one's team is named Arceus. It can only be obtained through befriending all other Pokémon in Pokémon Legends Arceus (once per playthrough, per software), or through past promotional events, though adding to to one's team in Pokémon Legends Arceus also allows the player to add it to their team in Pokémon Brilliant Diamond and/or Pokémon Shining Pearl.

What's more rare than a rare Pokémon? Most Pokémon have a chance of being a different set of colors than normal! This type of Pokémon is referred to as 'shiny.' The usual chance of finding a shiny Pokémon is 1 in 4096 in the current main-series games. The chance can also be improved, guaranteed, or impossible, in different sets of circumstances.

### Shiny Arceus' Rarity
To get shiny Arceus, one must encounter it in Pokémon Brilliant Diamond/Shining Pearl after adding it to their team in Pokémon Legends Arceus. Arceus being shiny is impossible in Pokémon Legends Arceus, but this allows one to encounter it in Pokémon Brilliant Diamon/Shining Pearl, where its odds of being shiny are 1 in 4096.

But who wants to go to all that work only to keep re-encountering it until it happens to be shiny, and then be successful in adding it to their team? Not me! Every attempt takes over a minute, and if one is at odds, it would take over 3 days of constantly trying.

### My solution
I decided that automating the encounter process would allow me to take care of other things while I wait to find a shiny Arceus, and then put the device to sleep until I come back ready to catch it. I had little idea of how to write the automation software myself, so I looked online.

I found [Poketools on FDEKeers' GitHub](https://github.com/fdekeers/poketools), which did a lot of what I was imagining. It emulated a Nintendo Switch controller, and used an audio cable to listen for a shiny Pokémon's sound effect to detect success. However, it wasn't configured for encountering Arcues specifically, and was also missing some other features I wanted. This led me to learn enough Python to add these features myself.

### What did I contribute?
My list of commits can be found by looking for 'cdmckinley' [here](https://github.com/cdmckinley/poketools/commits/main), but here's a summary:

- Added argument for different types of encounters
- Added support for encountering Arceus
- Added argument to have the Nintendo Switch capture a screenshot or replay upon successfully finding a shiny Pokémon
- Added argument for using different audio inputs on the script's host device

![Shiny Arceus summary](../assets/images/shiny-arceus-summary.jpg)

*A screenshot of the result of the application's result, showing a shiny Arceus was encountered and caught on June 20th 2022.*