This code is based off of an ESP32 tutorial I found online when contemplating this project

The main changes I made to the code was of course modifying the webpage to upload a constant stream of camera data (it was initially quite low speed), adding functionality for a button that allows the user to "fire" the spray bottle which would launch
water towards the center of the camera feed, spraying anything in front of the device.

An additional major change was the addition of a function that reduces the speed at which the servos turn, the original application of the code was for a very light and small device to turn very small increments. The additional weight
range of movement caused the turret to move unexpectedly when turning at full speed.

PLEASE feel free to view pictures of the working turret as well as the STLS on my linkedin: www.linkedin.com/in/aubrey-scott-8289b1166
