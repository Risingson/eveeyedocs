# Developers

## Mac and Linux Desktop App
I got no installer available for those platforms. You can download the browser at [https://nwjs.io/downloads/](https://nwjs.io/downloads/). 
A reference on how to package for that platforms can be found [here](http://docs.nwjs.io/en/latest/For%20Users/Package%20and%20Distribute/#platform-specific-steps).

Extra files: [package.json](https://www.dropbox.com/s/83yjmh3ktzatuny/package.json?dl=0), [logo.png](https://www.dropbox.com/s/b9adylfp2x1fmw6/logo.png?dl=0), [nw.icns](https://www.dropbox.com/s/0u6pfn6qkm33u5t/nw.icns?dl=0)

!!! help "Help needed"
    If you can do a working package for one of those platforms i would be happy if you could provide it via github and let me know.
    
## Eveeye custom-url-scheme
You can call Eveeye on iOS or Android via the custom-url-scheme `eveautheveeye` with parameters 
`m` for mapname
`s` for solarsystemname
`t` for info tab opened 
`o` for options
Check browser version urls for reference.

For example `eveautheveeye://?m=Delve&s=G-TT5V` will load Delve map with G-TTV5 centered. 

If a check on if eveeye is installed fails you can redirect the to
iOS: `itms-apps://itunes.apple.com/us/app/eveeye/id1163904317`
Android: `https://market.android.com/details?id=com.eveeye`

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI2MTExMDc5NF19
-->