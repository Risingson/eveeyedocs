# Chain Mapping

## Mechanics
#### Automatic connection creation
 - While syncing your ingame location jumps via wormholes or jump-bridges will get mapped automatically.
 - A connection will get created when jumping a cyno. Stop sync before jumping or remove the connection created manually.
 
#### Manual connection creation
 - You can add connections manually via the menu entry `Add Connection`
 
#### Connection creation via Signature pasting
 - When pasting wormhole signatures connections to "Unknown Systems" will get created
 - Click the created connection to set its destination
 <img src="https://raw.githubusercontent.com/Risingson/eveeyedocs/master/docs/images/mapper/incoming_unknown_menu.png">
 - Either enter the wormhole code or at unknown incomings the destination security or class. "T" stands for Thera and "P" for Pochven.

#### Merging automatically created and pasted connections
   <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="//youtu.be/g7bN3VgXrrY" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

#### Wormhole removal
 - Wormhole connections get removed after 48h latest. 
 - If you have set the wormhole code the removal will adopt that wormhole's expiration.
 - If you set a wormhole "End of Life" the timer will be set to 4 hours left.
 - You can always remove connections manually by clicking the connection line and selecting `Remove Connection` from the solarsystem menu.

 - When pasting wormhole signatures connections to "Unknown Systems" will get created


<!--
#### Viewable Information 
 - For wormhole systems there is no api data available for recent jumps or NPC kills.
 - Phenomenons are stated as an extra sub-label. To view its effects click the wormhole and select `Show Info` from the menu and switch to the `WH` tab.
   -->

## Display Styles
Solarsystem oultines are solid or dashed. 
Connection lines are colored and solid or dashed.

|Type| Meaning |
|--|--|
| Dashed system outline | Shattered wormhole |
| Blue lines | Not end of life |
| Red lines | End of life |
| Solid lines | Stability not reduced |
| Dashed line | Stability reduced|
| Large gap dashed line| Stability critical |
| Dotted line| Frigate sized |

## Add data to connections
To add data to connections you can right-click wormhole connection lines or click wormholes in the solarsystem info pane within the "SIG" tab.
You can edit:<br>

 - Signature codes on both sides<br>
 -  Wormhole code<br>
 - K162 side<br>
 - Label<br>

In solarsystem info pane's `SIG` tab you can merge "Unknown System" connections via dragging and dropping onto wormhole connections created by jumping them.

## Name wormholes
Clicking wormhole systems will show a `Set Wormhole Name` option in solarsystem menu.

## Routing
Wormhole connections can be used for plotting [routes](https://eveeye.readthedocs.io/en/latest/sync/waypoints/).
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0NzMzNjgwNywyMDg1NjYzODE0LDE5MT
I5MzExMjEsNjQ0Njg3OTU1LC0xNjQxMzk0MzcxLDEzMTk4NDM2
MzAsLTE3MDIyMzY0NDYsLTk3NDg3NTY0NiwtODQxNjUzNzkzLD
ExMzczMjUzNzEsNjIzOTgxMDU1LC00NTQyNDAzNjksLTE5NDM5
NTU5NzksMTYzNzE4NDkwLDY3MDcxOTU1MSwtNDU3NzgxMzEsLT
MzMjQ0NzI5N119
-->