# Final Project Progress Update #2

The crafting of the machine, the physical building of the plywood and the attachment of the motors was probably the easiest portion of this entire project. I used some leftover wood from another project, as this was more of a prototype/first rendition than a finished product.

The hardest? The metal cubes that held the rag onto it. I tried three different designs/ideas and none of them worked as well as I had hoped. Eventually, I settled on making more threaded holes in the face of the cube to attach the cloth directly connected to bolts.

The first thought I had was to just weld a sheet of metal on top of the cube to squeeze the rag between two pieces of metal. As the cube is aluminum, apparently our lab doesn't have the aargon gas in order to weld aluminum.

I decided that more threaded holes was the way to go. Oringinally I planned to have eight, one in each corner. This quickly changed as I began and realized that threading holes is physically difficult and time consuming. So, I only fully threaded four holes (two on each motor) instead of the original eight.

Then I decided to make a metal sheet with holes cut into it that alligned with the threaded holes I was making for extra security.

The bolts found in the sculpture lab are located in old orange juice and milk cartons, so finding eight bolts was a challenge. They were far too long as well, so I had to them cut them down to size. I watched a youtube video on how to do this, and surprisingly it worked. In the process I lost around 3 bolts, so I decided on only having two on each motor placed diagonally across from eachother.

_____

Originally once I got home from class and rewired the motors to the motor driver, it was working right and I could tell based on how the motors were acting that it was a power supply issue. (Thanks to my midterm project and its power supply issue.)

Turns out I had not attached the GND of my arduino to anything, so once I attached that it at leaste the motors were able to turn.

_____

I spent hours trying to figure out the code for the highest current. Why didn't I just email Rob? Good question, that I have no answer to. I was convinced it couldn't be that different from the code he already put together.

The current kept jumping, every time I would change the threshold for the highest current. Like it would show a range from 30-60, I'd make the threshold 60 and then it would be in the 300-400 range?

The float numbers didn't work in order to map the current in amps.

Eventually I got so confused, I had to stop because I couldn't even make the motors turn at one point. At that, I deleted everythign and started over with my original code. I quite literally had three different windows open with three sets of code. One was for just turning the motors in one direction. One was with the motors turning back and forth based on time and monitoring the current. The final one was for testing out code in order to find the highest current.

I was also struggling to get the rag to make a large enough shift in the current without being ripped from the bolts. Obviosuly a design flaw that I had to work with.

Eventually I settled on using the timing for the critique day in class.

I didn't realize that the motor driver could change the speed of the motors as well, I overlooked the fact that I could use an analog read from the pwm pins and tell it how fast to turn. That was super useful!

I'm not entirely happy with how it turned out, but based on what I've done, I can definitely see how I can change/adapt this to make the project I want. I just have to now narrow down my concept.
