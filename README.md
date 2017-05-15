# moore_constellation
A cluster of small telescopes, doing autonomous science work
Project named to the honor of Sir Patrick Moore

## Description
Using a collection of cheap and autonomous telescopes to do task such as

- Variable star astrometry
- Exoplanet confirmation
- Moon meteorite monitoring
- Astrophotography

## Parts of the project
1. Autonomous mini-observatories: Consists of a motorized telescope with a camera, with a motorized dome and climate sensors
2. INDI compatible software for controlling each mini-observatory
3. Kstars for controlling the mini-observatories and assign tasks to them
4. Normalization software that will aggregate results from several observatories to add to the power of the telescopes as well as to add scientific value to the observations

## TODO
- [x] Cloud sensors using 90° IR Thermometer. The dome should close then clouds are detected
- [x] 3d part for connecting a DSLR camera to the focuser of the telescope. (It is probable an NoIR-Pi cam will be used)
- [x] 3d part to hold focuser, it has the contour of the telescope and screw holes with secondary mirror space
- [ ] 3d part for the focuser, with mini-stepper motor and rail. I'm currently trying with a motorized linear rail potenciometer, but later with mini-stepper with included rails
- [ ] Webcams as well as Pi-cams are being evaluated
- [ ] Integration with focus software
- [ ] Stratum-1 NTP Server with GPS synchronization
