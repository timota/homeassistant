This blueprint adds the ability to control home assistant covers (blinds) using an Ikea Tradfri button (E1743), connected via zigbee2mqtt.

This is a fork of Zigbee2mqtt - [IKEA on/off button (E1743) to control Covers (Blinds)](https://community.home-assistant.io/t/ikea-on-off-button-e1743-to-control-covers-blinds/286307)

The button actions are mapped to cover services as follows:
```
Short Press ON - (on) - Open Cover
Short Press OFF - (off) - Close Cover
Long Press ON - (brightness_move_up) - Move cover UP until button is released.
Long Press OFF - (brightness_move_down) - Move cover DOWN until button is released.
Release ON or OFF after Long Press - Stop Cover

Short Press ON/OFF when cover is running - Stop cover
```