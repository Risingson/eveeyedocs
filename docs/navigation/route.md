# Route display

### Symbols
|  |  |
|--|--|
| ![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_start.png) | Current system|
|![disc](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_dot.png)|Fly thru system without npc station|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_thru.png)|Fly thru system with npc station|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_wp.png)|Waypoint solarsystem|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_sta.png)|Waypoint station|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_jb.png)|Waypoint jumpbridge|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_wh.png)|Waypoint wormhole|
|![line](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_jmp.png)|Midpoint (jumpdrive)|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_end.png)|Destination solarsystem|
|![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_end_sta.png)|Destination station|

### Information

|  |  |
|--|--|
| # | Number of system in route |
| N | NPC Kills within 1 hour (CCP API) |
| J | Jumps within 1 hour (CCP API) |
| K | Kills within 1 hour (CCP API) |
| Gatekills | Kills within 1 hour (zKill max ~5 min behind) |
| red number at jumpdrive jumps | Cooldown after jump in minutes |
| cyan number at jumpdrive jumps | Fatigue after jump in minutes |
| alliance/faction name | IHUB sovereignty or faction of the system |

### Gatekills
Kills are fetched from zKill every 5 minutes

|  |  |
|--|--|
| Red Background  | Kills on gates on route within 60 min |
| Blue background  | Kills in system or at a gate not on your route within 60 min |
| Blinking background  | Kills within 20 min |

### Example
<img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/jmprou2.png">

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc1NDc0OTgwOF19
-->