# Coffee Can Radar

## Disclaimer
This is a work in progress! It may or (more likely) may not currently be in a functioning state. 

## Purpose

This project is inspired by the [MIT Coffee Can Radar](https://ocw.mit.edu/resources/res-ll-003-build-a-small-radar-system-capable-of-sensing-range-doppler-and-synthetic-aperture-radar-imaging-january-iap-2011/). The purpose of this project is to get some exposure to RF PCB design by adapting the MIT Coffee Can radar to make use of tools that are readily available and familiar to the open source community.

## New things for me!

I would like to move away from using Altium. It is a great tool, but I no longer have access to a license and I would like to be able to create designs that can be shared easily. For this project I will try out Kicad. I can always fall back to Circuit Maker if it doesnt work out. 

## Notes

I need to experiment with the baseband circuits. Some examples uses a gain stage followed by a low pass filter, another example just added another gain stage before the mixer input. I think I'll get a prototype board made of just the RF section and then play around with some baseband circuits.

## Useful Resources

1. [MIT Coffee Can Radar](https://ocw.mit.edu/resources/res-ll-003-build-a-small-radar-system-capable-of-sensing-range-doppler-and-synthetic-aperture-radar-imaging-january-iap-2011/)
2. [Henrik's Blog](https://hforsten.com/)
3. [SimpleFMCWRadar](https://github.com/lukeweston/SimpleFMCWRadar)
4. [DEFCON 19: Build your own Synthetic Aperture Radar](https://www.youtube.com/watch?v=MViVyocQhVw)
5. [OCW Coffee-Can Radar Optimized in AWR Software](https://www.awr.com/serve/v-rdr-cfcn)

