# Airsim Drone Keyboard Controller
This is a dead simple drone controller meant to work with your keyboard. 
This is intended for you to be able to test things such as your computer vision models on the go without needing a remote controller or pixhawk. 
This IS NOT a replacement for a real remote controller. However I have found it useful as a way to focus just on things like ML and test them in low-fidelity before moving on to more rigorous evaluations. 

##### Controls
w, a, s, d -> front, left, back and right
q, e -> yaw left, yaw right
z, x -> altitude up/down

As of now, there aren't controls for throttle but that can be adjusted as the `step` parameter in `on_press()`

Perhaps you may find it useful! :)


