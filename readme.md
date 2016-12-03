# PumpkinPie Project

This is a hacked together halloween project for creating a creepy pumpkin using a Raspberry Pi and a Blinkt!

The goal was to have the raspberry pi inside a plastic pumpkin while simulating a candle burning. While the candle is burning, creepy sounds play. I used a small powered loud speaker.

I downloaded some free audio clips and used Audacity to hack together a creepy sound file that loops while the simulated candle burns inside the pumpkin.

This was my first attempt at using the Python multi-processing library. I am sure the multi-processing code is not proper and needs some work. But, this was functional enough to creep out some people. So, it was a success for me. :)

## Hardware Requirments:

* I used a Raspberry Pi 3 but it should work on a pi zero as well
* Blinkt! super-bright RGB LED indicator module
* Speaker to attach to your Raspberry Pi for the creepy audio
* Plastic pumpkin like the one kids use to collect candy

## Software Requirements

* Python 3.5
* NumPy Python Library
* Blinkt! Python library
* omxplayer - This is already installed if you use Raspbian and is a great media tool to hack with

## Setup

You will need a few Python libraries installed. These are related to simulating a candle with the blinkt! module.

* Install the blinkt! library: see https://github.com/pimoroni/blinkt
* Candle flicker adapted from blinkt! examples: This script requires the numpy module\nInstall with: sudo pip install numpy
* run the pumpkin.py script and the blinkt! module should look similar to a flickering candle inside the pumpkin and the creepy audio will play.

### NOTE: keep the volume low until you listen all the way through. It's intentionally soft at the beginning then loud audio toward the end. This is for effect.

## Resources
https://shop.pimoroni.com/products/blinkt  
http://www.numpy.org/  
https://docs.python.org/2/library/multiprocessing.html   
https://github.com/pimoroni/blinkt/blob/master/examples/candle.py   
http://www.raspberry-projects.com/pi/software_utilities/media-players/omxplayer  

## Happy Hacking!

### WARNING:  * * * I have been told the audio is scary. Please pre-screen before letting children and others listen to it. Some people have a hard time listening to it. Listen at your own risk. * * *
