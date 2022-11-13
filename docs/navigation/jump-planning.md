# Jump Planning (work in progress)

### Enabling using a jump-drvie for route planning
Enable `Use Jumpdrive` in `ROUTE` settings.<br>
Set your jump-ship and skills in `JUMP` settings.<br>

#### Jump settings
|  |  |
|--|--|
| `Use Jumpdrive` | Toggles if the route-planner will plot a jump route. |
| `Prefer Less Midpoints/Isotopes` | Sometimes a route with more mids needs less fuel. |
| `Jump if more than X Gates` | This sets the planner to always use its jumpdrive or only plot a jump if the gate distance to the next mid is more than X gates. |
| `Leaving Highsec` | Sets if you want to travel highsec as far as possible and jump from there (`Gate afar`) or if you want to jump as soon as possible (`Jump asap`). |
| `Prefer Station Systems` | The planner will try to jump via systems that got an NPC-station. |
| `Include dockable structures` | This option appears if you chose to prefer station systems. The planner would try to plot jumps via systems that got an NPC-Station or an [added structure](https://eveeye.readthedocs.io/en/latest/sharing/structures/) set to `DOCK` or `BLUE`. |
<br>

### How to plot a route
#### Choosing the system to start the route from
Choose a System to start from. When tracking location that would be your current location system. If not tracking location you can set a system your current location by doubleclicking it or right-clicking it and choosing `Set Current System` from the menu.

#### Menu options
After right-clicking or doubletapping a system on mobile in addition to [general and gate route options](https://eveeye.readthedocs.io/en/latest/navigation/waypoints/#route-manipulation) you will get presented with the following navigation options where applicable.

##### Terminology
|  |  |
|--|--|
| `Waypoint` | A system you want to go through. It is like pinning systems in your route. |
| `Midpoint` or `mid` | Systems chosen by the planner to reach the next waypoint. |

##### Menu options
|  |  |
|--|--|
| `Set Jump Destination` | Will plot a jump-route to the system according to your settings. |
| `Append Jump Destination` | Will add a jumproute to an existing route. |
| `Alternate Midpoint` | If a midpoint using this option you will get presented with all systems that could be used as a mid instead of this one. This will also show a list of alternate mids in  <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/rou.png" width="24" height="24"> route pane. |
| `Alternate Exit System` | When planning a Jump-freighter route to highsec the planner will choose an Exit system for you. Use this option to use a different one.  |
| `Turn into Waypoint` | Will pin a system you want to go through. |
| `Remove Waypoint` | Will remove a waypoint within a route. |
| `Remove Destination` | Will remove the last waypoint. Clears the route if it is the only Waypoint. |


!!! attention "Color of menu entries"
    Options involving the jump-drive got an *orange* color instead of the standard *yellow* for navigational options.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI3MTEyNDA5OCw3NjQwMTkyMjYsLTYwMT
gyNjExLDE4MzU1NjM1NjAsLTE3MDA5NjUwODIsMTYyOTYyMzIz
MSwtMTk4NTUxNjE3NF19
-->