# Generic 6-DOF Flight Sandbox

A self-contained, browser-based six-degree-of-freedom rigid-body flight simulation. Open the deployed GitHub Pages site on a desktop or phone; no installation is required.

## What it models

- Three translational degrees of freedom: world position and body-axis velocity
- Three rotational degrees of freedom: quaternion attitude and body angular rates
- Gravity, thrust, quadratic drag, simplified lift and side force
- Control moments and angular-rate damping
- Velocity and altitude hold commands
- A mission-distance stop at the selected range

## Controls

- Sliders: commanded velocity, altitude, and mission range
- Start, pause, reset, and three camera modes
- Desktop manual trim: W/S pitch, A/D roll, Q/E yaw, R/F throttle

## Scope and limitations

This is a deliberately abstract, non-weaponized educational flight model. Coefficients and dimensions are toy values and are not calibrated to any real vehicle. It does not include targeting, seeker logic, interception, terminal guidance, payload behavior, or real-world performance validation.
