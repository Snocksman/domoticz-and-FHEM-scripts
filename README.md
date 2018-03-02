# Scripts for Domoticz & FHEM
Virtual switch for Milight v6 for use in Domoticz & FHEM

- Full color support ( hex, RGB and HSV )
- Full brightness support ( 0 - 100 )
- Full saturation support ( 0 - 100 )
- Full device and zone support

 Usage:
  milight-home.py [DEVICE (0,1,7,8)] [ZONE (0,1,2,3,4)] [COMMAND ...]

 Commands are:
-  ON
-  OFF
-  DIMUP                        Only for Device type 1
-  DIMDOWN                      Only for Device type 1
-  NIGHT                        Nightlight for Device type 1 & 8
-  DISCO[1-9]
-  DISCOFASTER
-  DISCOSLOWER
-  WHITE                        for Device type 0 & 8
-  TEMP (0-100)                 White-Temperature for Device type 8
-  HUE (0-255)
-  SATUR (0-100)
-  BRIGHT (0-100)
-  SPECTRUM                     Animates lamps through full color spectrum
-  COLOR "(hex color)"          ie. "#ff0000" for red, "#0000ff" for blue ('#' char not needed)
-  COLOR (red) (green) (blue)   ie. 255 0 0 for red, 0 0 255 for blue
