# MacOS Monterey on the Framework Laptop

##### What doesn't work
- Integrated Graphics / IGPU
- Graphics Acceleration / IGPU
- Backlight control / IGPU
- Sound, speaker, microphone / IDT 92HD95
- Integrated Thunderbolt 4
- Goodix Fingerprint scanner
- ALS
- Intel Neural Accelerator

Failed trying to get the AppleIntelICLGraphics driver to load by spoofing as IceLake device-id and AAPL,ig-platform-id.
Failed trying to get audio to work by spoofing TigerLake Intel Smart Sound Controller as Ice Lake Intel Smart Sound Controller.

Framework community forums: https://community.frame.work/t/macos-on-framework-laptop/2957/39

# https://dortania.github.io/OpenCore-Install-Guide/
