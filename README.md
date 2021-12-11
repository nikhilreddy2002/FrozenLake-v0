# # FrozenLake-v0

**Frozen Lake Problem from Open AI Gym**
<br>
The agent controls the movement of a character in a grid world. Some tiles of the grid are walkable, and others lead to the agent falling into the water. Additionally, the movement direction of the agent is uncertain and only partially depends on the chosen direction. The agent is rewarded for finding a walkable path to a goal tile.
<br>
<br>
**The surface is described using a grid like the following:**
<br>
`SFFF` (S: starting point, safe)<br>
`FHFH` (F: frozen surface, safe)<br>
`FFFH` (H: hole, fall to your doom) <br>
`HFFG` (G: goal, where the frisbee is located)<br>
