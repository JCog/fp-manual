# 2.6 Camera

The free camera function provides full control of the game's camera. When enabled, the camera can be controlled with the joystick, C buttons, and Z trigger. These controls are disabled in-game when controlling the free camera. Press **lock** to disable the manual camera controls and restore the normal game controls. Note that changing the camera from its default will not affect how Mario controls. As far as the rest of the game knows, the camera is still where it normally would be.

The **behavior** setting decides how the camera moves and how the controls work:

* **manual:** The camera does not move by itself. Use the joystick to look around, and the C buttons to move. Hold Z to move with the joystick, look with C-left and right, and move vertically with C-up and down. The **distance min** and **distance max** settings do nothing.
* **birdseye follow:** The camera automatically looks at Mario and moves forward and backward to stay within the specified _distance_. Controls are the same as for _manual_.
* **radial follow:** The camera follows Mario from a fixed viewing angle. It will move up, down, and sideways to keep Mario in focus, and forward and backward to stay within the specified _distance_. Use the joystick, C-left, and C-right to rotate the viewing angle, and C-up and down to move towards and away from the focus point. Hold Z to swap the function of C-up and down with the vertical joystick axis.

Use `distance min` and `distance max` control the min/max that the camera can be from Mario when not in `manual` mode. Use `move speed` and `pan speed` to adjust how fast the camera moves when moving adjusting it. Pressing `reset` will move the camera back to roughly where it would be with the free cam disabled.
