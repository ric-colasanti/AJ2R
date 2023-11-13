# AJ2R
Public health planning viewer

## Simulation model
### Cell
Attributes
- neighbors []
- occupants []
- x_pos
- y_pos

Methods
- add_neighbor
- random_neighbor

### Agent
Attributes
- home

Methods
- move

### Simulation
Attributes
- cells []
- agents []

Methods
- initialization
- set_neighbors
- add_agents
- iterate
- ... for each agent:
- ...... move 
