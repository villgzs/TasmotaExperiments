# Tasmota experiments
Some settings and etc. 

## Settings for Current transformers

### CL-CT08CL5 2000/1 - ESP8266 - Wemos D1 modul

![https://community-assets.home-assistant.io/original/3X/c/f/cfcfe10bb64bd13008dde199a72872d27c1fbf42.png](https://community-assets.home-assistant.io/original/3X/c/f/cfcfe10bb64bd13008dde199a72872d27c1fbf42.png)

The voltage divider was powered from 3.3V, not 5V. Middle point should be 1.65V.  
Burden = 100 ohm  

Configuration for analog input - ADC CT Power  

```
AdcParam 17, 0, 2022, 0.23
```
