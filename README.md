# myprotime-cli

MyProtime command-line client to clock in and out

This is a simple Python3 script based on Selenium that can be used to clock in and out from the command-line.

## Requirements

myprotime-cli was written with Linux in mind, but should work on other Unices. YMMV.

It requires:

- the selenium library and the chromium driver: `apt install chromium-driver python3-selenium`
- either a local Chrome browser or a Selenium Grid instance.

For the latter, these images help a lot:

- `docker.io/selenium/standalone-chrome`
- `docker.io/seleniarm/standalone-chromium`

## Installation

Copy myprotime and myprotime-wrapper wherever you see fit, typically `/usr/local/bin`.

## Configuration

Copy config.sample as `~/.config/myprotime` and customize it. 
