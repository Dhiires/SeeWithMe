# SeeWithMe
Attempting to create an eye-guided camera to keep my hands free when traveling.

## Camera Movement
Initial movement expected to be in 2 axis (yaw, pitch). 3rd axis (roll) could later be added for stabilization purposes. 
- First development step will be with joystick to the pan tilt base of the camera.

## Eye tracking
Currently deciding if it should be done with bought AR glasses (because of integrated eye tracking) or with made glasses with a webcam attached to them. 

# Development steps
- Yaw, pitch angles with MPU attached to glasses for head movement tracking instead of eye tracking. Later this data could be complementary to eye tracking.
- Getting the cartesian position of the user's sight.

## Focus Point Estimation
With the tracked position of the eye and the relative position between eye and camera is expected to estimate the user's focus point. With this estimation camera movement will be actioned.