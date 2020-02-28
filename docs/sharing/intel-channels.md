# Intel Channels
This feature allows the desktop app to read your clients chatlogs and display intel channel info on the maps. 

To enable chat channel parsing you need to download and install the [desktop app](https://www.dropbox.com/s/feo1z1055a7jmpd/Eveeye_v001.exe?dl=0).

To add channels hit the <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Share-100_off.png" width="24" height="24" > Sharing Icon and add intel channels. You can turn them on and off by clicking the added channels.

## Development, current issues

 - If a system was cleared via `clr` or `clear` subsequent intel in that system does not draw the red marker
 - `+[Number]` only works with one space before it
 - UI

## Syntax
What the system can parse names of:

 - `character`
 - `solarsystem`
 - `ships`

All of the above need to be separated by 2 spaces.

Additionally you can use the following:

`solarsystem` &#9251; &#9251; `clr` or `clear`: Sets a system empty
`character` &#9251; &#9251; `solarsystem` &#9251; `+5`: Will add +5 or any other number behind the plus (CURRENTLY ONLY ONE SPACE BEFORE THE + PLEASE AND ONLY AT THE END OF THE LINE. will improve)

!!! warning "Feature in development"
    This feature is currently under development. You can test it by downloading the [desktop app](https://eveeye.readthedocs.io/en/latest/desktop-app/). [Feedback](https://eveeye.readthedocs.io/en/latest/#Feedback) more than welcome !!
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NTM3MTk1MDcsLTE0MDM0ODkxMDEsLT
IxNDE4ODc4MjgsMTk4NTAyNzUxMSwxMDE2NDUzMjgzLDExMzkw
MTk2MDYsLTE0MTUwMDI3ODcsODkxNjUyMTQ5XX0=
-->