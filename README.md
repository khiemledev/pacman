# CS106.M11.KHCL Assignment 3 - Evaluation functions for Minimax/AlphaBeta/Expectimax

This is the sourcecode for implementing the evaluation functions for the Minimax, AlphaBeta, and Expectimax algorithms for playing pacman.

## Quick start

To run the game, be sure to install the following packages:
```bash
pip install pygame
```

To run the game controlled manually, run the following command:

```bash
python pacman.py
```

To change the map layout, run the following command:

```bash
python pacman.py -l <layout_name>
# All available layout_name are listed under layouts/
# For example
python pacman.py -l mediumClassic
```

To change the agent, run the following command:
```bash
python pacman.py -p <agent_name>
# All available agent_name:
# - ReflexAgent
# - MinimaxAgent
# - AlphaBetaAgent
# - ExpectimaxAgent
# For example
python pacman.py -p ReflexAgent
```

To change the depth of the search, run the following command:
```bash
python pacman.py -a depth=<depth>
# <depth> is integer, default is 2
# For example
python pacman.py -a depth=3
```

To change the evaluation function, run the following command:
```bash
python pacman.py -a evalFn=<evalFn>
# <evalFn> is string, default is 'betterEvaluationFunction'
# For example
python pacman.py -a evalFn=betterEvaluationFunction
```