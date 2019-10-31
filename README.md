# Zeus Icon Set for Home Assistant

This is a free sample of the [Zeus Icon Set](https://xus.badia.me/zeus) for [Home Assistant](https://www.home-assistant.io).

![Zeus for Home Assistant](/docs/zeus-ha-main.png "Zeus for Home Assistant")

## Instructions
To add these icons to your Home Assistant, you just need to follow these simple steps:

1) Copy the www folder inside your Home Assistant.

2) Add this code to your configuration.yaml file:

```
frontend:
  extra_html_url:
    - /local/hass-zeus-icons.html
```

That's it! To use the icons, just write 'zeus:icon_name'. (the 'icon_name' is the same as the SVG files inside the SVG folder).

Here's a cheatsheet for a complete list of icon names:
```
baggage
crown
megaphone
treehouse
settingscogs
homeassistant
homeassistantmini
lightstringleft
floorlamptop
lightstringcenter
floorlampmiddle
lightstringright
floorlampbottom
dooropen
doorclosed
door
ceilinglamp
lightstring
floorlamp
floorplan
floorplandoors
motionsensor
friendsneutralcircle
coffeealt
power
running
piggybank
volumemutealt
sofa
airconditioner
airconditionerfan
vacuumcleaner
fanoff
dog
smokedetector
classicwalllight
chandelier
drop
```


================================

For a complete list of Zeus icons, please visit: https://xus.badia.me/zeus

And a complete cheatsheet, please visit: https://xus.badia.me/zeus/cheatsheet

================================

## Example

![Lights](/docs/lights_screenshot.png "Lights")
