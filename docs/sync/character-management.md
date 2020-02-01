# Character Management
Logging in characters is not necessary to use this app but unlocks the following features:

 - Track your ingame location
 - Interact with the EVE client like setting waypoints etc.
 - Sync your data across devices
 - Share your data with other pilots
<!-- - Display relayed ingame intel channel data -->

## EVE Online Single-Sign-On (SSO) 
This app uses the [EVE Online Single Sign On (SSO)](https://support.eveonline.com/hc/en-us/articles/205381192-Single-Sign-On-SSO-) to authenticate characters. Since the ingame browser has been removed it is not possible to track your ingame location without a SSO login hence using an API KEY is not an option anymore.

!!! success "Security"
    Unless you enable the [Cloud](https://eveeye.readthedocs.io/en/latest/sharing/cloud/) services no data gets stored on Eveeye server. If cloud sync is enabled only a complementary key is stored on the server. It alone cannot be used to authenticate a character or use any EVE Online [ESI](https://esi.evetech.net/) APIs.<br><br>If you got security concerns consider using two factor authentication. It can be enabled in EVE account management: <a href="https://secure.eveonline.com/authenticator/" target="_blank" style="text-decoration: none;">https://secure.eveonline.com/authenticator/</a>

To revoke access for Eveeye goto [https://community.eveonline.com/support/third-party-applications/](https://community.eveonline.com/support/third-party-applications/)

## Login process
To add characters tap <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/User-100_26_100_off.png" width="24" height="24" > or your character's portrait in the menu.

To remove a character tap <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Minus-100_b.png" width="24" height="24" > in the menu. This will remove any tokens available to login the character but will keep other data like for example custom names stored to not loose that data by accident. To fully remove custom data un-install the app or clear browser cache.

When using the cloud storage feature your user including the token stored to identify your char gets removed from cloud immediately. Your custom data will get deleted from cloud 30 days after char removal.

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ3NzMxODQ3NCwtMzQ2MjY2MjA3LC0xNT
MxMTU2NDkwLC01NTc1MDM1MzEsLTg3NDc1OTM5OSwtMTUyMzE4
MjI3NiwxMDYzNjUxMDExLC0xMzkxMDIxNDE3LDE4MzU2MzQ1Nj
EsLTM4MDQ5ODAyMCwxMjg2OTE5Nzg3LDEyMjY5OTc3MjgsMTY3
OTY2ODA5M119
-->