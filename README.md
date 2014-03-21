TestCode2
=========

Reverted some stuff back that didn't work or didn't work better.
The Sphere Algo isn't used anymore for Gyro and Acc Calculation because no real benefit.
Tackled GPS circeling on several stages:
- Reduced Filtering on GPS/ACC Fusion part.
- Reduced Imax (maximal 1/4 of max gps tiltangle)
- Improved Heading calculation with mwii2.3 Algo. (slightly modified)

Rest -> see readme.
GPS Tailcontrol needs further attention - next version :)

Cheers

Rob
