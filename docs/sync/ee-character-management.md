# Character Management
Logging in characters via Discord is not necessary to use this app but unlocks the following features:

 - Synchronize your Database Sets across devices
 - Share Database sets with people on a Discord Server

## Discord Login 
This app uses the [Discord oauth login](https://support.eveonline.com/hc/en-us/articles/205381192-Single-Sign-On-SSO-) to authenticate characters. 

!!! success "Security"
    A complementary key is stored on eveeye server. It alone cannot be used to authenticate a character or use any EVE Online [ESI](https://esi.evetech.net/) APIs.<br><br>If you got security concerns consider using two factor authentication. It can be enabled in EVE account management: <a href="https://secure.eveonline.com/authenticator/" target="_blank" style="text-decoration: none;">https://secure.eveonline.com/authenticator/</a>

To revoke access for Eveeye goto [https://community.eveonline.com/support/third-party-applications/](https://community.eveonline.com/support/third-party-applications/)

## Login process
To add characters tap <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/User-100_26_100_off.png" width="24" height="24" > or your character's portrait in the menu. After selecting to add a character you will get redirected to a new native browser window to log into EVE Online and then back to Eveeye with the character added. 

To remove a character tap <img src="https://raw.githubusercontent.com/Risingson/eedocs/master/docs/images/Minus-100_b.png" width="24" height="24" > in the menu. This will remove any tokens available to login the character but will keep other data like for example custom names stored to not loose that data by accident. To fully remove custom data un-install the app or clear browser cache.

When using the cloud storage feature your user including the token stored to identify your char gets removed from cloud immediately. Your custom data will get deleted from cloud 30 days after char removal.

## Re-authing
If you updated your character image you can update it by just authorizing the char again. Also if a new version of Eveeye was installed sometimes it would need you to authorize your characters again to use new features.

## Revoking access
To remove a character's API permissions please do so at [https://community.eveonline.com/support/third-party-applications/](https://community.eveonline.com/support/third-party-applications/).

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTIxNDkzMzY5N119
-->