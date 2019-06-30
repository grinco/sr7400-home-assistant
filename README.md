# Marantz sr7400 media player component for home-assistant

Tested on hass.io  0.95.4 

To install - just copy [custom_components](https://github.com/grinco/sr7400-home-assistant/tree/master/custom_components) and [deps](https://github.com/grinco/sr7400-home-assistant/tree/master/deps) directories under your home assistant root configuration directory and add the following to your config:
```
  - platform: marantz  
    serial_port: /dev/ttyUSB0  
    name: Marantz Receiver  
    min_volume: -71  
    max_volume: -1  
    sources:  
      'A': 'DSS'  
      'B': 'TV'  
      'D': 'DVD'  
      'E': 'VCR1'  
      'G': 'AUX1'  
      'H': 'AUX2'  
      'J': 'CD'  
      'K': 'TAPE'  
      'L': 'CD-R'  
      'N': 'FM'  
      'O': 'AM/MW'  
      'Q': 'TUNER'  
    soundmode:  
      '0': 'Auto'  
      'd': 'Stereo'  
      'X': 'S-DIRECT'  
      'c': 'VIRTUAL'  
      'P': 'NEO6 MUSIC'  
      'O': 'NEO6 CINEMA'  
```
