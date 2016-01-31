# homebridge-mpd
Homebridge plugin to control MPD.

### Usage:

```json
"accessories": [
   {
       "accessory": "mpd",
       "name": "Stereo",
       "host": "localhost",
       "port": "6600"
   }
]
```

### Dependencies:
 * Homebridge: https://github.com/nfarina/homebridge
 * Mpd.js: https://github.com/andrewrk/mpd.js