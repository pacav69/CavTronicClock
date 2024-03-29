[![cavtronics logo](https://cldup.com/BhJv2ZU0rj.jpg)](http://www.cavtronics.com "cavtronics")

# CavTronicClock

This clock is based on 
[Mick Make's Project-mmClock ](https://github.com/MickMake/Project-mmClock)


The mmClock
Source code for my talking alarm clock. This alarm clock will:
- [x] Sync time from an NTP server.
- [x] Sync events from Google calendar.
- [x] Speak the time/date in many formats.
- [x] Annoy you with the alarm of your choice.

Features I'll be adding:
- [ ] Better security, (currently it's open).
- [ ] Select clock display style from Google calendar.
- [ ] Select MP3 alarm file to play from Google calendar.
- [ ] Select alarm volume level from Google calendar.
- [ ] Multiple calendar syncing.
- [ ] MQTT connectivity.
- [ ] Better web interface.

Check out [my tutorial video](https://www.youtube.com/watch?v=IoX6t03ULnc) on how I made it.
Also check out [my website](https://www.mickmake.com/archives/3375) for further details. 


## Support :+1:
If you want to support me, then head on over to [my Patreon page](http://patreon.com/MickMake).


## License
This source code is covered under the GPL!


## Source code - Clock/
Source code is under the [Clock/](Clock/) directory.
All the important defines are in the [common.h](Clock/common.h) file.
Make sure you update these to the correct settings.

## MP3 files - SDcard/
Copy all the files under [SDcard/](SDcard/) to an SD card. You can create your own, but make sure that you keep the same order as define in [ClockMP3defs.h](Clock/ClockMP3defs.h).

## Other libraries
To use: Download the [FireBeetle Covers-24X8 LED Matrix files](https://github.com/Chocho2017/FireBeetleLEDMatrix), unzip the file and copy the two files:

	DFRobot_HT1632C.cpp
	DFRobot_HT1632C.h

to the [Clock/](Clock/) directory.



## IT Development:

p.s:
I **LOVE** coffee! Buy me a coffee at:   

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XWQDNV85QA9RC&source=url)



## Support

<img src="https://vangogh.teespring.com/v3/image/SugZ-DRGZXUTuSzfrFtaOU3TAUQ/800/800.jpg" width="100px"  height="100px">

[Help support by buying some merchandise](https://cavtronics-3.creator-spring.com/)





