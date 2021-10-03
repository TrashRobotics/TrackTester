<h1 align="center">
  <a href="ссылка на видео"><img src="https://github.com/TrashRobotics/TrackTester/blob/main/img/ttest.jpg" alt="Track Tester" width="800"></a>
  <br>
  Track Tester
  <br>
</h1>

<p align="center">
  <a href="https://github.com/TrashRobotics/TrackTester/blob/main/README.md">Русский(Russian)</a> •
  <a href="https://github.com/TrashRobotics/TrackTester/blob/main/README-en.md">English</a> 
</p>

# Description
Track platform testing programs

# Main parts
* arduino Nano v3;
* bluetooth module HC-06;
* motor driver MX1508;
* yellow arduino TT geared motors;
* 2x 18650 accumulators and battery compartment for them;
* toggle switch;
* board or piece of plywood 190x80 mm;
* [wheels, fasteners, etc](ссылка на детали)

### Fasteners
* Bearing 623 2RS (180023) 3dx10Dx4H x2;
* Self-tapping screw DIN7982 3.5x16 x10;
* Self-tapping screw DIN7982 2.2x9.5 x2; 
* Screw DIN7985 M3x35 x6;
* Screw DIN7985 M3x30 x8;
* Screw DIN7985 M3x12 x12;
* Nut DIN934 M3x0.5 x30;

# Programs
Arduino Nano sketch: **track_test/track_test.ino**  
          
**tracktester.py** - python script to control a platform from a PC.           
To run the script, you need to install the ** punput ** package.              
The platform is controlled by arrows.