# Airsim Drone Keyboard Controller
This is a dead simple drone controller meant to work with your keyboard. 
This is intended for you to be able to test things such as your computer vision models on the go without needing a remote controller or pixhawk. 
This IS NOT a replacement for a real remote controller. However I have found it useful as a way to focus just on things like ML and test them in low-fidelity before moving on to more rigorous evaluations. 
<br>
#### Controls
w, a, s, d -> front, left, back and right<br><br>
q, e -> yaw left, yaw right<br><br>
z, x -> altitude up/down<br><br>
<br>
As of now, there aren't controls for throttle but that can be adjusted as the `step` parameter in `on_press()`
<br>

#### To Use
Clone the repo
`git clone https://github.com/AydinGokce/Airsim_Drone_Keyboard_Controller.git`

cd into the repo
`cd Airsim_Drone_Keyboard_Controller`

Run `controller.py`
`python3 controller.py`

Perhaps you may find it useful! :)


