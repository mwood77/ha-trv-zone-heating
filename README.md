# Home Assistant Automated TRV Zone Heating

Welcome 👋

Here you'll find a collection of automations that'll allow you to _precisely_ control the heating within your home on a room-by-room basis, using [Zigbee](https://en.wikipedia.org/wiki/Zigbee) based TRVs and temperature sensors.

### Why Use This

> Fine-tunable, fully automated, and remote-controlled heating. 

This is a cost efficient system which converts traditional hot water radiator heating systems into a zone-controlled heating system; each room with an installation has the capability to self-regulate its own temperature.

This project's goal is to be as comprehensive as possible, providing a local-controlled alternative to closed source automated heating systems like that offered by [Tado](https://www.tado.com/nl-nl?srsltid=AfmBOorJe498UwW5kq8HAElu1WR35V_Gj9q3CalYz6Kc3KUPyQKnGuGW), [Drayton's Wiser](https://www.draytoncontrols.co.uk/products/smart-heating/wiser), and [Resieo's Evohome](https://www.resideo.com/nl/nl/oplossingen/comfort/evohome/).


### What's a TRV (Thermostatic Radiator Valve)
> [Wikipedia](https://en.wikipedia.org/wiki/Thermostatic_radiator_valve)

A TRV (Thermostatic Radiator Valve) is a device which is connected to hot water radiator heating systems, at each radiator. These allow you to set a rough temperature per room by adjusting the water in-flow into each radiator. These offer better temperature regulation than conventional flow based radiator valves, but still require the the main heating system to be pumping in order to heat the room or area.

## How This Works
**@todo**

# Getting Started

## Design Considerations and Safety Precautions
**@todo**

## Prerequisites
> [!IMPORTANT]
> You must have a decent level of familiarity with [Home Assistant](https://www.home-assistant.io/); the open source home automation platform.

1. A central heating hot water system that uses radiators and a "CV ketel" or "CV boiler"
    - For best results, your CV needs to be **OpenTherm compatible**. This standard is nearly 30 years old, so it's likely yours is, but there are some caveats:
        - Some (Nefit) Bosch units may require an additional addon to convert their CVs from Bosch's proprietary communication standard. The (Nefit) Bosh part number is `7746901847`.
        - [You can reference known OpenTherm compatible systems here](https://www.opentherm.eu/products/)
1. An established and functional Home Assistant installation
1. A Zigbee coordinator
1. An established and configured [Zigbee2MQTT installation within Home Assistant](https://github.com/zigbee2mqtt/hassio-zigbee2mqtt?tab=readme-ov-file#installation)

