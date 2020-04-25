# Developers

## Mac and Linux Desktop App
I got no installer available for those platforms. You can download the browser at [https://nwjs.io/downloads/](https://nwjs.io/downloads/). 
A reference on how to package for that platforms can be found [here](http://docs.nwjs.io/en/latest/For%20Users/Package%20and%20Distribute/#platform-specific-steps).

Extra files: [package.json](https://www.dropbox.com/s/0knpy9bi84dp7ay/package.json?dl=0), [logo.png](https://www.dropbox.com/s/b9adylfp2x1fmw6/logo.png?dl=0), [nw.icns](https://www.dropbox.com/s/0u6pfn6qkm33u5t/nw.icns?dl=0)

!!! help "Help needed"
    If you can do a working package for one of those platforms i would be happy if you could provide it via github and let me know.
    
## Eveeye custom-url-scheme
You can call Eveeye on iOS or Android from app version 3.00.0 via the custom-url-scheme `eveautheveeye` with parameters <br>
`m` for mapname<br>
`s` for solarsystemname<br>
`t` for info tab opened <br>
`o` for options<br>
`j` for radar map level <br>
Check browser version urls for reference.<br><br>

#### Custom url scheme on mobile
For example `eveautheveeye://?m=Delve&s=G-TT5V` will load Delve map with G-TTV5 centered. 

If a check on if eveeye is installed fails you could redirect to<br>
iOS: `itms-apps://itunes.apple.com/us/app/eveeye/id1163904317`<br>
Android: `market://details?id=com.eveeye`

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1MTA3Nzc1MCwyNzczOTc0NjYsLTEzMj
Q2MTY0Myw2MTAyOTg4ODYsMjA1MzUyNDkwMCw0MzA3NDA2NzAs
LTI2MTExMDc5NF19
-->