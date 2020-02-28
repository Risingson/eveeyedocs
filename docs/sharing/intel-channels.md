# Intel Channels
This feature allows the desktop app to read your clients chatlogs and display intel channel info on the maps. 

To enable chat channel parsing you need to download and install the [desktop app](https://www.dropbox.com/s/feo1z1055a7jmpd/Eveeye_v001.exe?dl=0).

To add channels hit the <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Share-100_off.png" width="24" height="24" > Sharing Icon and add intel channels. You can turn them on and off by clicking the added channels.

!!! warning "Feature in development"
    ## Development, current issues
    This is an alpha test. This means means the feature ist still in development and will have issues. Known issues are as follows:<br><br>
     - The display of the Intel list is getting a rework. I know the actual intel lines are a pain to read at the moment.<br>
     - If a system was cleared via `clr` or `clear` subsequent intel in that system does not draw the red marker.<br>
     - `+[Number]` only works with one space before it at the moment.<br>
    <br> 
    [Please help with feedback, report problems or bugs or anything making the feature better](https://feedback.userreport.com/7ab42bbb-8bf8-4955-9573-c0b1213b1ba7/#submit/bug)<br><br> 
    Fixed:<br>
    - Systems behind jump bridges reported too close<br>

## Syntax
What the system can parse names of:

 - `character`
 - `solarsystem`
 - `ships`

All of the above need to be separated by 2 spaces.

Additionally you can use the following at the end of an intel line:

`solarsystem` &#9251; &#9251; `clr` or `clear`: Sets a system empty
`character` &#9251; &#9251; `solarsystem` &#9251; &#9251; `+5`: Will add +5 or any other number behind the plus.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3NTY1NDA2NDcsLTE1MjI2ODM2ODEsMT
g2MjYwMzA3MCwtMjA2NTE2MzA4LDE5OTAyNjc0MzksLTE0MDM0
ODkxMDEsLTIxNDE4ODc4MjgsMTk4NTAyNzUxMSwxMDE2NDUzMj
gzLDExMzkwMTk2MDYsLTE0MTUwMDI3ODcsODkxNjUyMTQ5XX0=

-->