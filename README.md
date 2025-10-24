# Component 1 User Manual
This manual will explain how the component works and how it will be used in the final prototype

## Player
The player moves using the GetAxisRaw() function. This makes setting up the controls not to complex for the final prototype. The player's rigidbody has been set to kinematic and the rigidbody has been
constrained so that it won't rotate. This is so that if the player hits the wall, the force cant be applied to the rigidbody and push it past and around the walls.

## Walls
The walls have been set up with a simple collider and have been set to kinematic to keep them in the same place.

## Implementation
The movement of the player will be determined by the camera position. Being able to move on the X and Y axis when side-on, and on the X and Z axis when top-down. The player will also only be able to move a couple units in its "Forward" direction, as this is how many similar bullet hells/shoot-em ups are played.
