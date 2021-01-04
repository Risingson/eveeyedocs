# Settings

## General
#### User Interface scale
Use + and - to scale the entire UI. In browsers you can use its native zoom aswell.
#### Download Data over WiFi only
This will load api data only if you are on wlan to save on data volume. This setting is available within mobile apps only.
#### Suppress Data Update Notifications
This toggles notifications appearing on the bottom of the app when new data was loaded.
#### Doubleclick/tap Mode
With this mode enabled clicking ot tapping a solarsystem will not show the menu. To show the menu you would have to doubleclick/tap it. On connection lines a single click/tap is sufficient to show its menu still.

## Map
#### Extended Map Layout
This will extend maps with routes via different regions connecting back to the current map. This gets rendered via an arc with describing text on it.
Additionally this will display how many systems are connected to a system of another region.
#### Mono Background
Will disable displaying background graphics and replace with a near-black blue background.
#### Center on Current System
This will tween the system your character is currently in to the center of the screen.
#### Show Current Constellation Outline
Draws an orange outline around all systems of the constellation you are in currently.
#### Display Trail
Trails will help you to see which system you visited recently.
They do not get drawn on wormhole connections, wormhole systems or on chain maps.
Trails will fade over time and be hardly visible after 20h. 
#### Clear Trail
Using this you can clear your current trail.

## Route
#### Display Route
Will display your route on the map after you used "Set Destination/Waypoint" from solarsystem menu.
#### Use Wormholes
Use your mapped wormholes to calculate a route including [Thera connections](https://eveeye.readthedocs.io/en/latest/map/map-options-misc/) if activated.
#### Use Jumpbridges 
Use your jumpbridges to calculate a route.
#### Shortest/Secure/Insecure Route
Set your preferred travel security. This should match your ingame setting.
#### Avoid Edencom / Triglavian Systems
Set this to try to avoid routing via Triglavian or Edencom solarsystems. This works differently than ingame. The EVE client will not find a route if you cannot get somewherew without crossing Trig
#### Avoid Systems
Avoid systems you set avoided by clicking it and choosing "Avoid System" in the solarsystem menu shown (that option is only there while [Client Sync](https://eveeye.readthedocs.io/en/latest/sync/client-synchronisation/) is activated). This should match your ingame setting since setting a system avoided in Eveeye does not set it avoided ingame and vice versa.
#### Avoidance List
Systems you set avoided are listed here. Clicking the system will let you remove it from the list.

!!! attention
    You should match ingame and eveeye settings to get the same routes ingame and within eveeye. Still routes displayed may not match 100% every time.

## Jump
#### Display Jumprange
Enables/Disables displaying jumpranges on the map.
#### Skill and Fitting Settings
Match your skills and fit for the app to calc your range and isotopes correctly.

!!! info
    While you are in <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Marker-100_on.png" width="18" height="18"> Client Sync the app will choose your current ship. If you like to choose another ship to check its range you would have to temporarily disable <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Marker-100_off.png" width="18" height="18"> Client Sync.

## Names
You can set names for your [Custom Marks](https://eveeye.readthedocs.io/en/latest/sharing/custom-marks/) which will display in the map's legend if applicable.

<!--stackedit_data:
eyJoaXN0b3J5IjpbNDAzNzMxOTU0LDgwMDQ0Njc4NSwxOTkwMT
YxODI5LDI4Nzk0MTIzOSwxMzM0Mzg3NTA2LC0xMzk3NTI3MzM0
LDEyMjI4NzYyNTUsLTMzMzg3NTE5OSwxMzU5OTk5NjQ1LDE3OT
kxODUxOTYsMTMxMTc0MjQ4NCwxODMyMTU2Mjg2XX0=
-->