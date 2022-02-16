# Settings

## App
#### Download Data over WiFi only (mobile)
This will load api data only if you are on wlan to save on data volume. This setting is available within mobile apps only.
#### Suppress Data Update Notifications
This toggles notifications appearing on the bottom of the app when new data was loaded.

## User Interface
#### Light Map Theme
Toggle dark/light theme.
#### Mono Background
Will disable displaying background graphics and replace with a near-black blue or white background.
#### User Interface scale
Use + and - to scale the entire UI. In browsers you can use its native zoom aswell.
#### Color Hue and Saturation
Use + and - to set UI colors.
#### Connection Line Width
Use + and - to change the line width of the connections on the map. Also important for exporting the map to PNG.

## Map
<!-- #### Hexagonal Map Layout -->
#### Extended Map Layout
This will extend maps with routes via different regions connecting back to the current map. This gets rendered via an arc with describing text on it.
Additionally this will display how many systems are connected to a system of another region.
#### Show Unknown Connections
A connection to that unknown system will get created when pasting cosmic signatures containing an [unknown wormhole](https://eveeye.readthedocs.io/en/latest/map/chain-mapping/). Using this option you can turn off displaying those. This can be triggered by <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/q.png" width="24" height="24" > in the left map menu aswell.

## Track
#### Autostart Location Tracking
If you got a character [authenticated](https://eveeye.readthedocs.io/en/latest/sync/client-synchronisation) this will instantly display your location on the map at app start.
#### Use Animated Location Marker

#### Center on Current System
This will tween the system your character is currently in to the center of the screen. This can be triggered by <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/center.png" width="24" height="24" > in the left map menu aswell.
#### Show Current Constellation Outline
Draws an orange outline around all systems of the constellation you are in currently.
#### Display Trail
Trails will help you to see which system you visited recently.
They do not get drawn on wormhole connections, wormhole systems or on chain maps.
Trails will fade over time and be hardly visible after 20h.  
This can be triggered by <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/t.png" width="24" height="24" > in the left map menu aswell.
#### Clear Trail
Using this you can clear your current trail.
#### Clear all Jumpbridges or Wormhole Connections
Sometimes you would want to clear them all at once.

## Route
#### Display Route
Will display your route on the map after you used "Set Destination/Waypoint" from solarsystem menu. This can be triggered by <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/r.png" width="24" height="24" > in the left map menu aswell.
#### Use Wormholes
Use your mapped wormholes to calculate a route including [Thera connections](https://eveeye.readthedocs.io/en/latest/map/map-options-misc/) if activated.
#### Use Jumpbridges 
Use your jumpbridges to calculate a route.
#### Shortest/Secure/Insecure Route
Set your preferred travel security. This should match your ingame setting.
#### Avoid Edencom/Triglavian Systems
Set this to <!--try to--> avoid routing via Edencom and/or Triglavian solarsystems. <!--This works differently than ingame though. If you use those settings ingame the EVE client will not find a route if you cannot get somewhere without crossing Edencom or Triglavian systems. Eveeye will try to find a route where you cross them least.-->
#### Avoid Systems
Avoid systems you set avoided by clicking it and choosing "Avoid System" in the solarsystem menu shown (that option is only there while [Client Sync](https://eveeye.readthedocs.io/en/latest/sync/client-synchronisation/) is activated). This should match your ingame setting since setting a system avoided in Eveeye does not set it avoided ingame and vice versa. 
#### Avoidance List
Systems you set avoided are listed here. Clicking the system will let you remove it from the list.

!!! attention
    You should match ingame and eveeye settings to get the same routes ingame and within eveeye. Still routes displayed may not match 100% every time.

## Jump
#### Display Jumprange
Enables/Disables displaying jumpranges on the map. This can be triggered by <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/j.png" width="24" height="24" > in the left map menu aswell.
#### Skill and Fitting Settings
Match your skills and fit for the app to calc your range and isotopes correctly.

## Marks
You can set names for your [Custom Marks](https://eveeye.readthedocs.io/en/latest/sharing/custom-marks/) which will display in the map's legend if applicable.

<!--stackedit_data:
eyJoaXN0b3J5IjpbNzU5MDgyNjg5LC0xNDI2MDA1ODA2LC04MD
U5MDYwNDgsMTMyMjY4NjEyMiwyMDgzMDUxMDg2LC0yNzM2OTY2
MCwtMzc0MDE4MTQ0LDY0NDQzNDUwMyw0Njg3ODY5NzMsLTIwNT
AzMjYyMTYsMTIxOTM4MzUxNiwtODQ2OTUzNzYyLC02MDE4NzQ5
NTYsODAwNDQ2Nzg1LDE5OTAxNjE4MjksMjg3OTQxMjM5LDEzMz
QzODc1MDYsLTEzOTc1MjczMzQsMTIyMjg3NjI1NSwtMzMzODc1
MTk5XX0=
-->