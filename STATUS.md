#### Branch `walkthrough`
##### Commit #3
##### Issues:
 - Cold Start - Breaking Accelration
 - Collision - Still hitting the car in front of us.


##### Commit #4
 - Added STATUS.md


##### Commit #5
 - Sensor Fusion - Simulator is reporting this kind of list of all other cars on the road. All other cars have some `s`, `d`, `x`, `y`, `vx` and `vy`.
 - Stopped collisions (rear-ending)

##### Issues:
 - Cold Start


 ##### Commit #6
 - Resolving Cold Start by using boolean and increasing/decreasing speed based on bool.
 - Resolved issue around `lane` and `ref_vel` declared outside of `h.onMessage`