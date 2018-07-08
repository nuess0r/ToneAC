# ToneAC
[![Build Status](https://travis-ci.org/RoboticsBrno/ToneAC.svg?branch=master)](https://travis-ci.org/RoboticsBrno/ToneAC)

Replacement to the standard Arduino tone library with many advantages

Advantages over the standard tone library:
- Nearly twice the volume (because it uses two out of phase pins in push/pull fashion)
- Higher quality (less clicking)
- Capability of producing higher frequencies (even if running at a lower clock speed)
- Nearly 1.5k smaller compiled code
- Bug fixes (standard tone library can generate some odd and unpredictable results)
- Can set not only the frequency but also the sound volume
- Less stress on the speaker so it will last longer and sound better

[Source](http://forum.arduino.cc/index.php?topic=142097.0)
