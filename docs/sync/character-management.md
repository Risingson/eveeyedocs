# Character Management
Logging in characters is not necessary to use this app but unlocks the following features:

 - Track your ingame location
 - Interact with the EVE client like setting waypoints etc.
 - Sync your data across devices
 - Share your data with other pilots
<!-- - Display relayed ingame intel channel data -->

## EVE Online Single-Sign-On (SSO) 
This app uses the [EVE Online Single Sign On (SSO)](https://support.eveonline.com/hc/en-us/articles/205381192-Single-Sign-On-SSO-) to authenticate characters. <!--Since the ingame browser has been removed it is not possible to track your ingame location without a SSO login hence using an API KEY is not an option anymore.-->

!!! success "Security"
    Unless you enable the [Cloud](https://eveeye.readthedocs.io/en/latest/sharing/cloud/) services no data gets stored on Eveeye server. If cloud sync is enabled only a complementary key is stored on the server. It alone cannot be used to authenticate a character or use any EVE Online [ESI](https://esi.evetech.net/) APIs.<br><br>If you got security concerns consider using two factor authentication. It can be enabled in EVE account management: <a href="https://secure.eveonline.com/authenticator/" target="_blank" style="text-decoration: none;">https://secure.eveonline.com/authenticator/</a>

To revoke access for Eveeye goto [https://community.eveonline.com/support/third-party-applications/](https://community.eveonline.com/support/third-party-applications/)

## Login process
To add characters tap <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/User-100_26_100_off.png" width="24" height="24" > or your character's portrait in the menu. After selecting to add a character you will get redirected to a new native browser window to log into EVE Online and then back to Eveeye with the character added. 

To remove a character tap <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Minus-100_b.png" width="24" height="24" > in the menu. This will remove any tokens available to login the character but will keep other data like for example custom names stored to not loose that data by accident. To fully remove custom data un-install and re-install the app or clear browser cache.

When using the cloud storage feature your user including the token stored to identify your char gets removed from cloud immediately. Your custom data will get deleted from cloud 30 days after char removal.

## Re-authing
If you updated your character image you can update it by just authorizing the char again. Also if a new version of Eveeye was installed sometimes it would need you to authorize your characters again to use new features.

## Revoking access
To remove a character's API permissions please do so at [https://community.eveonline.com/support/third-party-applications/](https://community.eveonline.com/support/third-party-applications/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbNTIxMjg4NjgwLC0xNzg0MjgyMzgzLDIxMz
Y2MjA0ODksLTE1MTQyODQyOCw3NTA2NTUxNzgsLTgzODc2Nzkx
OCwxNDc3MzE4NDc0LC0zNDYyNjYyMDcsLTE1MzExNTY0OTAsLT
U1NzUwMzUzMSwtODc0NzU5Mzk5LC0xNTIzMTgyMjc2LDEwNjM2
NTEwMTEsLTEzOTEwMjE0MTcsMTgzNTYzNDU2MSwtMzgwNDk4MD
IwLDEyODY5MTk3ODcsMTIyNjk5NzcyOCwxNjc5NjY4MDkzXX0=

-->