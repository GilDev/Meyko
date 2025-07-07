# ESPHome Configuration for Meyko

Meyko is an abandonned smart device from a French startup. It runs an ESP32, which can be programmed with ESPHome using this config to give it a new life.

It’s like a Nabaztag, but less cool (sorry Meyko).

![Meyko](meyko.jpg)

*Happy Meyko rocking his new software!*

## Usage

Using manually installed ESPHome: `esphome run meyko.yaml`
Using Docker Compose: `docker-compose run esphome run meyko.yaml`

## TODO

* Add support for the CR95HF NFC transceiver (not in ESPHome yet)
* Set LEDs as PWM to adjust their brightness and make fading animations
* Find a better way to declare faces. I don’t need external access to every LED, just presets
