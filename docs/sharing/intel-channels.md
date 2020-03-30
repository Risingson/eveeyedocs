# Intel Channels
This feature allows the desktop app to read your client's chatlogs and display intel channel info on the maps. 

To enable chat channel parsing you need to download and install the [desktop app](https://www.dropbox.com/s/x2dgjwiof2frek3/Eveeye_v002.exe?dl=0).

To add channels hit the <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Share-100_off.png" width="24" height="24" > Sharing Icon and add intel channels. You can turn them on and off by clicking the added channels. Remove them by clicking the minus sign.

!!! warning "Feature in development"
    ## Development, current issues
    This is an alpha test. This means means the feature is still in development and has issues.<br>Known issues are as follows:<br><br>
     - The display of the intel list is getting a rework.<br>
     - Multiple channel intel line display needs changes.<br>
     - If a system was cleared via `clr` or `clear` subsequent intel in that system does not draw the red marker.<br>
     - `+[Number]` only works with one space before it at the moment.<br>
     - Some users report that the app does stop to update if not the active window or minimized. I cannot reproduce this and need more info on it.<br>
    <br> 
    [Please help with feedback, report problems or bugs or anything making the feature better](https://feedback.userreport.com/7ab42bbb-8bf8-4955-9573-c0b1213b1ba7/#submit/bug)<br><br> 
    Fixed:<br>
    - Systems behind jump bridges report 6+ jumps now.<br>
    - Parsing should not stop anymore after a lot of lines have been processed.<br>
    - System does now detect if new chat file was created (client restart).<br> 
    
## Syntax
The system can parse names of:

 - `character` 
 - `solarsystem`
 - `ship` 

All of the above need to be separated by 2 spaces.<br>Their order does not matter.<br> For example: `FWST-8` &#9251; &#9251; `Risingson` &#9251; &#9251; `Tengu`

Additionally you can use the following at the end of an intel line:<br>
`solarsystem` &#9251; &#9251; `clr` or `clear`: Sets a system empty<br>
`character` &#9251; &#9251; `solarsystem` &#9251; &#9251; `+5`: Will add +5 or any other number behind the plus.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU4ODA4ODE1LC01NjIxODIzNTIsMTk1OD
U0OTQxLC0xODkyMDk4ODUxLC0xOTE3MzgxNDU0LC05MDc3NTU1
MjYsMTI5MzE2MjcyMywxMjkzMTYyNzIzLDE5ODQyMTkwMSwtMT
EyNDIxNjM1Nyw2OTQ5MjUxMDEsMTg5MDYwMDkxNSwtMjQ5OTcy
NTYzLC0xMzE4MzQ4ODcwLDEwOTYxMTcxMzMsLTE1MjI2ODM2OD
EsMTg2MjYwMzA3MCwtMjA2NTE2MzA4LDE5OTAyNjc0MzksLTE0
MDM0ODkxMDFdfQ==
-->