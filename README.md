GVGAI-MapElite
=====

This Project is forked from the mcts_agents branch from https://github.com/mcgreentn/GVGAI and the large portion of the implementation is taken from https://github.com/amidos2006/MarioExperiments


Taking inspiration from the example genetic generator, a basic layout for MapElite is implemented. The package is under `/src/tracks/levelGeneration/mapEliteLevelGenerator`

## TODOs

`Chromosome.java`

1. The `populateDimensions` method is a placeholder. This method is supposed to be able to interface with  Adelphi to obtain its dimension info.

2. The `calculateFitness` method works similarly as the Mario level generator code. Its implementation needs to be re-evaluated to fit GVGAI framework.

## CHANGELOG

This lays out all the changes in the codebase that deviates from mcts_agents
Any code in the mapEliteLevelGenerator is not included

`/src/core/game/game.java`
 - Commented out a block of code for testing at line 941, 948, 1316, 1342

`src/core/competition/CompetitionParameters.java`
 - Line 37: Changed `LEVEL_ACTION_TIME` to 200000
