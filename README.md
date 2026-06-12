# Tasmota experiments
Some settings and etc. 

## Settings for Current transformers

### CL-CT08CL5 2000/1 - ESP8266 - Wemos D1 modul

![https://docs.openenergymonitor.org/_images/ct-sensors-circuit1.png](https://docs.openenergymonitor.org/_images/ct-sensors-circuit1.png)

The voltage divider was powered from 3.3V, not 5V. Middle point should be 1.65V 
Burden = 100 ohm

Configuration for analog input - ADC CT Power

```
AdcParam 17, 0, 2022, 0.23
```
