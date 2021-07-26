# Keypress Simulator/ Presentation Controller Using Hand Tracking

I made a project where I track and count the fingers of the hand and based on the data I simulated keypress. 

My objective:

* Control Presentation using gesture.
* Gesture Control Input Method

Some Info:

* 4 or 5 Fingers = Key Down
* 3 Fingers = Key Up

You can change this easily.

I get about 50 fps. So, I had to use delay(time.sleep) to halt the code execution for 1 second every time I simulate kew press so that it does not change multiple pages in the slide at a single time. 
