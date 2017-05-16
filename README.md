# Python Speedtest app for Raspberry Pi
## This is Deprecated! Go use [this](https://github.com/BadgerOps/resin-speedtest) instead!
## Parts

I'm using an OG raspberry pi, and the aforementioned [Adafruit RGB LCD+Keypad kit](https://www.adafruit.com/product/1109)

### Resin.io Setup & Deployment

1. If you haven't got a resin.io account, visit [resin.io](http://resin.io) and sign up.
1. start a new applicaton on resin.io, name it what you want, download the .zip file and extract it to your SD card.
1. Insert the SD card into the Raspberry pi, connect the ethernet cable and power it up.
1. After about 10 -15 minutes your device should show up on the resin.io applications dashboard.


Once your resin.io account is set up, you should be able to:

`$ git clone https://github.com/Badger32d/rpi-speedtest.git`

then add the resin remote: (replacing <myUserName> and <myApplicationName> with yours from the resin.io dashboard)

`$ git remote add resin git@git.staging.resin.io:<myUserName>/<myApplicationName>.git`

and finally push the code to your raspberry pi:

`$ git push resin master`
