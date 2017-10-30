### Reflection

The Project Walkthrough and Q & A helped me develop my model. Much of what David went over and implemented was presented in the lessons. The walkthrough was really helpful in understanding what the C++ code was doing and what was needed to be done.

After watching and understanding what was implemented, I added a variable (`too_close`) to measure how far a car needed to be for me to considered completing a lane change. Essentially, if a vehicle is not 30 meters of my vehicle, stay the course. Flip that situation, we have a few things to consider:

* Check what lane the vehicle is in
* Is the vehicle in front of me, if so, I set the `too_close` variable `true`.
* Is the vehicle to the left or right of me, I set the `too_close` variable to `false`.

With the additional logic, everything seemed to run very well. There was one time when there was a collision. Problem is that I was unable to replicate.
