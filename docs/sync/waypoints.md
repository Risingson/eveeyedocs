
# Waypoints
With sync active you got the possibility to set destinations/waypoints from Eveeye to the EVE client. 

## Interaction
To set waypoints tap/click a solarsystem. In the appearing menu hit `Set Waypoint` or `Set Destination`.<br>
In the same menu you can select to `Avoid System`. To manage your avoided systems goto the `ROUTE` tab in <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Settings-100_off.png" width="24" height="24" > [Settings](https://eveeye.readthedocs.io/en/latest/ui/settings/#Route).

!!! attention "Ingame vs Eveeye route"
    You should match ingame and eveeye settings to get the same routes ingame and within eveeye. Still routes displayed may not match 100% every time.
    
#### Route Display
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_start.png) Current system<br>
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_thru.png) Fly thru system<br>
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_wp.png) Waypoints<br>
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_jb.png) Jump a jumpbridge from this system<br>
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_wh.png) Jump a wormhole from this system<br>
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_sta.png) Station<br>
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/rou_end.png) Destination<br> 


#### Route Manipulation
Clicking the colored square or else in the route legend will trigger a menu with some options where applicable:

 
|  |  |
|--|--|
| Clear Route | Will clear your route ingame and in eveeye |
| Turn into Waypoint | Will stop your ship in this system if autopiloting |
| Remove Waypoint | Will not stop your ship in this system if autopiloting |
| Add again at end of route | Will add that system as a waypoint to the end of your route |
| Set sole destination | Will clear current route and set that system as destination |

## Wormholes/Jumpbridges
When you got one or both of the options `Use Wormholes` or `Use Jumpbridges` enabled in [Routing Settings](https://eveeye.readthedocs.io/en/latest/ui/settings/#Route) calculating the route will consider those connections. If a route is found that includes wormholes or jumpbridges waypoints will be set accordingly.

#### Example
We like to go from `PR-8CA` to `Nasreri`.<br>
The shortest route from `PR-8CA` to `Nasreri` via k-space is 32 jumps.<br> ![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/Wormhole_routing_00.png)

A 12-jump route using a detour via Thera was found:<br>![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/Wormhole_routing_0.png)

If you `Set Destination` to `Nasreri` via Eveeye the app will set a waypoint at `PUIG-F`. There you would have to find the entrance to Thera. The corresponding Signature Code is found in the solarsystem-tab `SIG` or on the line on the map. From Thera do the same for the exit -in this case- to `Vecamia`. After jumping back to k-space the client will show the last 4 jumps.<br>

Within the EVE Client your route would look like this since the client does not plot routes via wormholes:<br>![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/Wormhole_routing_03.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTMzOTc3NTg3OSw3NTI0MjczMTAsLTE3Mj
E0ODI3NTgsNjM4Nzk2NDc2LDEwMDIzOTY2NTUsLTg5MTcyMjQ0
OSwtNTI0NzEzODM4LC00NDE3MjI1MzYsLTE4MDU1ODY0NTVdfQ
==
-->