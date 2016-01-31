# homebridge-mpd
Homebridge plugin to control MPD.
Includes volume control and play/stop control. Volume control uses the brightness Characteristic of the homekit protocol because a volume Characteristic is not available yet.

### Configuration:

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

#### Default values:
 * name: "MPD"
 * host: "localhost"
 * port: "6600"

### Dependencies:
 * Homebridge: https://github.com/nfarina/homebridge
 * Mpd.js: https://github.com/andrewrk/mpd.js

### Usage:
 - *Siri, turn Stereo on*
 - *Siri, turn Stereo off*
 - *Siri, change Stereo to 20%*
 - *Siri, is Stereo on?*