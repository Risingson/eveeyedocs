# Client Sync

!!! attention
    This page is work in progress.

## Icons
<img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Marker-100_off.png" width="24" height="24" > Off<br>
<img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Marker-100_standby.png" width="24" height="24" > Connecting to EVE<br>
<img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Marker-100_on.png" width="24" height="24" > On<br>
<img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Marker-100_fail.png" width="24" height="24" > Failed<br>

<br><br>...<br><br>

## Setting Waypoints
With sync active you got the possibility to set destinations/waypoints from Eveeye to the EVE client. To do this tap/click a solarsystem. I the appearing menu hit *Set Waypoint* or *Set Destination*.

### Option Use Wormholes/Jumpbridges
When you got one or both of the options `Use Wormholes` or `Use Jumpbridges` enabled in [Routing Settings](https://eveeye.readthedocs.io/en/latest/ui/settings/#Route) calculating the route will consider those connections. If a route is found that includes wormholes or jumpbridges waypoints will be set accordingly.

#### Example
We like to go from `PR-8CA` to `Nasreri`.<br>
The shortest route from `PR-8CA` to `Nasreri` via k-space is 32 jumps.<br> 
![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/Wormhole_routing_00.png)

A 12-jump route including a detour via Thera was found:<br>![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/Wormhole_routing_0.png)

If you `Set Destination` to `Nasreri` via Eveeye the app will set a waypoint at `PUIG-F`. There you would have to find the entrance to Thera. The corresponding Signature Code is found in the solarsystem-tab SIG or on the line on the map. From Thera do the same for the exit -in this case- to `Vecamia`.<br>

Within the EVE Client your route would look like this though since the client does not plot routes via wormholes:<br>![enter image description here](https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/route/Wormhole_routing_03.png)
<!--stackedit_data:
eyJoaXN0b3J5IjpbODAzMzA0OTA5LDcyMDkwMzAyMywtMTc2OT
M5NDA4OCw4Mjc4MDY4MjcsMTg4MDAwMTgsMTg5MjkyNjA4LC00
MjE0NTUyOTgsMTA2NDExMzc5LC0xMjgzNTM1MDk3LC03NzA5Mz
Y4NDAsNjA3NTY0NDcsLTIxMDM3NzU4NjMsNDA0NDE0NjE5LC0y
MDgwNTA4NTQ3LDEyNTMxNDc2NTUsLTE0NjcwODg4OTQsMjAyOD
c3NjYyMSwtMTUxMDUyNjA5MSwtMTM0NTg1MzI3OV19
-->