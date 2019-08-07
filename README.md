# AGSOL-Gyro-Tactor
Prototype of a general purpose module to use gyroscope measurements for playing different vibration effects.


KNOWN ISSUES:
  1. This device will only work for movement in one direction in its current state.
  2. Acceleration in the Y direction seems to have smaller magnitudes than on the other two axis. More testing is needed to determine why      this is.
  3. The tactor does not seem to like taking the output values in its current state.
   
TO DO:
  1. Fix accelerometer and gyro gain using the format of x-accel
  2. Implement tactor
  3. Consider how the minimum expected value fits into this model
  4. Consider how to implement the max.
  5. Values for max are hardcoded for now. Create a program that gets the maximum acceleration and updates automatically.
  6. Currently values are only calibrated for the acceleromter. This should be done for the gyroscope as well.
