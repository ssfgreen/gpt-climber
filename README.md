# GPT-Climber

## Playgrounds

### hold_playground.ipynb

- Generates 3 dimensional coordinates
- Adds the hold sets and compass (N, S, E, W etc) rotations for 2016, 2017 and 2019 moonboards
- Calculates the distances between holds and exports this file

### data_playground.ipynb

- imports the 2017 moonboard json from https://github.com/andrew-houghton/moon-board-climbing/tree/master/moon/utils
- Creates a histogram df of all the hold occurances at each grade
- Creates a crude popular/difficulty score for each hold
- Sorts the holds by coordinate A1...K1....A18...K18 etc
- Calcualtes the distances between pairs of holds in sequence
- Creates a crude, "hardest move" score -> hold difficulty of each hold \* distance between them
- Sorts this list by hardest move
