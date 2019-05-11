# A1
Flipotronics A1 hybrid modular digital/analog synthesizer based on Raspberry Model 3B+
and the Eurorack standard.

A1 combines digital oscillators with analog filters, based on Open Source projects and
Open Source Hardware.

This repo contains the Flipotronics A1 documentation

 Containerized projects:
- nodeJS REACT project to handle OSC, remote UI and the TFT display
- nodeJS project to manage online Sound Library and community functions
- Python project to manage VST plugins and Linux synthesizers
- Python project to handle GPIO for midi, encoders, push buttons and 7 segment display

High priority:
- C++ demon for Flipotronics sound routing and modulation

Cron based:
- GOLANG project OTA over the air updates managing Docker containers

projects communicate using Redis or Jack.


dependencies:

- Raspbian Stretch with PREEMPT kernel
- Alsa
- Jack
- Redis
- Docker
- pm2
- RPi.GPIO

- FluidSynth
- Hydrogen
- Dexed
- Guitarix
- Synth1
- Bristol
- setBfree
