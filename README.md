USC PIV (Beta) - Particle Image Velocimetry codes

This repo contains some of the Particle Image Velocimetry(PIV) codes I have been developing over the last year. As it stands, this repo is a haphazard collection of seemingly random Matlab codes. Over the course of this year (between multiple projects and teaching commitments), I hope to turn it into something more useful. My goal is to eventually design a clean GUI that will call these codes through a nice, user-friendly interface. In the mean time, feel free to take a look at the various sub-routines (you migth even find some of them handy!), modify it for your own use (definitely encouraged!), and send me a pull request if you make any changes. 

Note:

[1] A good starting point would be xcorrPIV.m which performs the initial step of calculating displacement and velocity fields. 
[2] All of the codes are written in Matlab. Signal Processing Toolbox is required for cross-correlation.  
[3] The readimx4matlab libraries (32- and 64- bit versions) required to read image data acquired through DaVis are provided in this repo for your convenience. LaVision retains any and all rights to those libraries, and by using them you assume any liabilities that might arise. Thanks to LaVision ( http://www.lavision.de/en/ ) for making them available. Check them out for all of your PIV needs. 
[4] All codes (except LaVision's readimx4matlab) provided under the MIT license.  

-Prabu Sellappan
