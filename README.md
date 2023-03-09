# Raspberry Pi Pico W with e-paper
Driving e-paper screen using CircuitPython

## Concept
Device should download weather data from online server once every 30 minutes, display it on the e-paper screen and go to deep sleep to save power.

## Hardware
* Raspberry Pi Pico W

* MH-ET Live 1.54 inch e-paper display

## Connections
| e-paper | Raspberry Pi |
| :-----: | :----------: |
| SCLK    | GP18         |
| SDI     | GP19         |
| CS      | GP17         |
| DC      | GP20         |
| Reset   | GP21         |
| Busy    | GP22         |

## Links

[Adafruit 1.54" eInk display breakouts](https://learn.adafruit.com/adafruit-1-54-eink-display-breakouts/overview)

[Quickstart using Adafruit eInk/ePaper displays with CircuitPython](https://learn.adafruit.com/quickstart-using-adafruit-eink-epaper-displays-with-circuitpython/overview)