# The basics of Conway's Game of Life
## What is it?
Conway's Game of Life is a cellular automaton designed by the British mathematician John Conway in 1970. The player creates an initial state for the game 'grid' and then provides no further input and watches how the cells 'evolve'. The model is an example of the concept of complexity derived from simplicity as the game holds an extremely simple set of rules that are then used to create more complex models and ideas.

##How can I try it out?
You can use my own [python implementation](https://github.com/game-of-life-in-X/GameOfLifeInPython) or the common cross-platform implementation [Golly](http://golly.sourceforge.net/). There are also online alternatives if you want to avoid installing a program and performing setup.

## The rules
The rules for Conway's Game of Life are extremely simple; Each cell is in a binary state of either dead or alive (usually with black representing a alive and white representing dead) and cells both alive and dead interact with neighbouring cells to produce an output, either changing state or remaining in the same previous state. Cells count as neighbouring if they are horizontally,  vertically or diagonally adjacent to the cell. The game moves in 'ticks', with each tick acting as  check in state for every cell on the grid. There are four rules that dictate what happens to a cell each tick:
1. Any cell with less than two neighbours will die. This is known as underpopulation or loneliness.
2. Any living cell with two to three neighbours survives to the next generation.
3. Any living cell with greater than three neighbours dies . This is known as overpopulation or overcrowdedness.
4. Any dead cell with three neighbours will become a live cell. This is known as reproduction.

## Basic patterns
The most common types of patterns come in three forms:
- Still lifes which are static cell groups that never change
- Oscillators which change through a set of looping forms in an infinite loop, with each change being known as a period 
- Spaceships or Gliders which are moving groups of cells that move forever unless disrupted. 

### The block
![A block model](https://i.imgur.com/dvgyIat.png)


The block is the simplest still life and is extremely easy to create. It is often left as the result of more complex models.

### The hive
![A basic hive model](https://i.imgur.com/LRLBgiE.png)


The hive is another simplistic Still Life model. It useful for the creation of some more complex models.

### The Blinker
![The blinker](https://i.imgur.com/sXiR5YM.gif)


The Blinker is a simple two period oscillator, it stays in place switching between the two periods forever.

### The Toad
![The toad](https://i.imgur.com/dR84RXf.gif)


The Toad is another two period oscillator. It's slightly more complex and has a further reach than that of the blinker.

### The Glider
![A basic glider](https://i.imgur.com/rnPoh7q.gif)


This is a classical glider, it moves infinitely in one direction and doesn't stop until it meets an external cell.

## Where to go next?
From here it's up to you to experiment and research to find more complex and interesting models and create new ideas. Youtube user [Alex Bellos](https://www.youtube.com/channel/UCjY-JWyBWiejeMoVSmYVTPA) has a playlist featuring many more complex models such as glider guns and basic logic gates using gliders that you can explore [here](https://www.youtube.com/watch?v=bTPN3spiq1I&list=PL_DEGJtvl7wtPc-ZyTq_jh0ptRjnYGaWZ).
