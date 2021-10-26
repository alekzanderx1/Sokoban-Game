# Sokoban Environment - NYU Artificial Intelligence
---
## Prerequisites
Requires python3 to run
##### Install libraries
`$ pip install -r requirements.txt`
## Run the Game

##### Solve as a human
`$ python3 game.py --play`
`$ python3 game.py --agent Human`
##### Solve with an agent
`$ python3 game.py --agent [AGENT-NAME-HERE]`

`$ python3 game.py --agent BFS #run game with BFS agent`

`$ python3 game.py --agent AStar --no_render #run game with AStar agent without rendering`

## Parameters
`--play` - run the game as a human player

`--no_render` - run the AI solver without showing the game screen 

`--agent [NAME]`  - the type of agent to use [Human, DoNothing, Random, BFS, DFS, AStar, HillClimber, Genetic, MCTS]

`--level [#]` - which level to test (0-99) or 'random' for a randomly selected level that an agent can solve in at most 2000 iterations. These levels can be found in the 'assets/gen_levels/' folder (default=0)

`--iterations [#]` - how many iterations to allow the agent to search for (default=3000)

`--solve_speed [#]` - how fast (in ms) to show each step of the solution being executed on the game screen 

