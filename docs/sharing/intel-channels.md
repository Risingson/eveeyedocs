# Intel Channels
This feature allows the desktop app to read your clients chatlogs and display intel channel info on the maps. 

To enable chat channel parsing you need to download and install the [desktop app](https://www.dropbox.com/s/feo1z1055a7jmpd/Eveeye_v001.exe?dl=0).

To add channels hit the <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Share-100_off.png" width="24" height="24" > Sharing Icon and add intel channels. You can turn them on and off by clicking the added channels.

!!! warning "Feature in development"
    Development, current issues
This is an alpha test. This means means the feature ist still in development and will have issues. Known issues are as follows:
 - The display of the Intel list is getting a rework. I know the actual intel lines are a pain to read at the moment.
 - If a system was cleared via `clr` or `clear` subsequent intel in that system does not draw the red marker.
 - `+[Number]` only works with one space before it at the moment. 
 
[Please give feedback, report problems or bugs or anything making the feature better](https://feedback.userreport.com/7ab42bbb-8bf8-4955-9573-c0b1213b1ba7/#submit/bug)


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
eyJoaXN0b3J5IjpbNDcxMjg2NywtMTQwMzQ4OTEwMSwtMjE0MT
g4NzgyOCwxOTg1MDI3NTExLDEwMTY0NTMyODMsMTEzOTAxOTYw
NiwtMTQxNTAwMjc4Nyw4OTE2NTIxNDldfQ==
-->