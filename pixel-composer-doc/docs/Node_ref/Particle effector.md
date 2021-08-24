## Particle Effector

Particle effector takes in particle data, and manipulate them using different algorithm. Allowing you to modify particle after spawn.

| Inputs           | Type     | Description                                                  |
| ---------------- | -------- | ------------------------------------------------------------ |
| Particle data    | Particle | Particle to affect.                                          |
| Output dimension | Float    | Output size.                                                 |
| Area             | Float[5] | Area of effect.                                              |
| Falloff          | Curve    | How effect got weaker near the edge of the area.             |
| Falloff distance | Float    | Width of the falloff.                                        |
| Effect type      | Int      | Type of effect.<br />- Wind: push particle in area in one direction.<br />- Attract: pull all particle to center.<br />- Repel: push particle out of the center.<br />- Vortex: rotate the particle around center. |
| Strength         | Float[2] | Strength of the effect.                                      |
| Effect Vector    | Float[2] | Direction of the force.                                      |
| Effect rotation  | Float    | Rotate the affected particle.                                |
| Effect scale     | Float[2] | Scale the affected particle.                                 |

| Outputs       | Type     | Description    |
| ------------- | -------- | -------------- |
| Surface out   | Surface  | Image output.  |
| Particle data | Particle | Particle data. |

