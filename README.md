# OpenTX GPS LUA TELEMETRY screens - GPS last known quad postions v2.2

Copyright (C) by mosch   
License GPLv2: http://www.gnu.org/licenses/gpl-2.0.html       
GITHUB: https://github.com/moschotto?tab=repositories 

## make sure that your radio is a least on OpenTX version 2.3!

### Radios with 480x272 pixel displays (e.g. Jumper T16)
- /T16/GPS
- /T16/GPSviewerT16.lua

### Radios with 212x64 pixel displays (e.g. x9d/x9+/x9E)
- /x9/GPSx9.lua
- /x9/GPSviewerX9.lua
- /x9/GPSviewerX9e.lua (use this if your radio has a scroll wheel)

### Radios with 128x64 pixel displays (e.g. x7 / x9 lite)
- /x7_x9lite/GPSx9L.lua
- /x7_x9lite/GPSviewerX9L.lua

 
### Description:
How to find your model in case of a crash, power loss etc? Right, check the last 
GPS coordinates and type it into to your mobile phone...

- Shows and logs GPS related information. log file will be generated in
/LOGS/GPSpositions.txt

- GPS logfile can be viewed with the GPSviewer.lua" on the radio itself

- in case that the telemetry stops, the last coordinates will remain on the screen

- distance to your home position - how far you need to walk ;)

- Reset telemetry data (home positon and distance):

   [TARANIS] Reset via "long press enter"

   [T16 etc] Reset via "long press enter" -> statistics -> "long press enter" to reset statistics and exit menu in under 10 seconds	


### Install Taranis models:
- copy GPSxxx.lua to /SCRIPTS/TELEMETRY

- copy GPSviewerxxx.lua to /SCRIPTS/TOOLS

- copy the ICON folder to /SCRIPTS/TELEMETRY/BMP

- Setup a "screen (DIsplay 13/13)" and select GPSxxx.lua

### Install Jumper/HOROUS models:

- copy the GPS folder (inculding subfolders) to /WIDGETS/GPS
- copy GPSviewerT16.lua to /SCRIPTS/TOOLS

- Setup "1/2" widget screen and select "GPS"


##################################################



### x7 / x9 lite Screens:

![Alt text](https://github.com/moschotto/Taranis_GPS_Telemetry/blob/main/media/x9L_GPS_screen.PNG)
![Alt text](https://github.com/moschotto/Taranis_GPS_Telemetry/blob/main/media/x9L_GPSviewer.PNG)

### x9d/x9+/x9E Screens:

![Alt text](https://github.com/moschotto/Taranis_GPS_Telemetry/blob/main/media/x9_GPS_screen.PNG)
![Alt text](https://github.com/moschotto/Taranis_GPS_Telemetry/blob/main/media/x9_GPSviewer.PNG)

### JUMPER T16 / HOROUS etc WIDGET screen:
![Alt text](https://github.com/moschotto/Taranis_GPS_Telemetry/blob/main/media/T16_GPS_screen.png)
![Alt text](https://github.com/moschotto/Taranis_GPS_Telemetry/blob/main/media/T16_GPSViewer.png)


### Demo Video

<a href="http://www.youtube.com/watch?feature=player_embedded&v=9Jt2rRiSq0U" target="_blank"><img src="http://img.youtube.com/vi/9Jt2rRiSq0U/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmoschotto%2FOpenTX_GPS_Telemetry&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

