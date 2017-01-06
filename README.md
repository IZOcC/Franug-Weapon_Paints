### Tips
* Use https://gitlab.com/Franc1sco/PRIVATE-WeaponPaints/issues if you found bugs, you have questions, or you want a new feature.
* Don't sell or give this to others or publish this private version or you will be out from the next updates.

### Installation:
* Install required plugin: https://www.dropbox.com/s/dygllegwqy6e0rr/franug%20givenameditem%203.0.0.zip?dl=0
* Disable "FollowCSGOServerGuidelines" option. In addons/sourcemod/configs/core.cfg write this line in the end ```FollowCSGOServerGuidelines "no"```
* Dont use your own tokens. Use this website https://csgo.tokenstash.com
* Unzip file in addons/sourcemod/
* Add a entry called "weaponpaints" to addons/sourcemod/configs/databases.cfg
* You dont need to upload the .sp file
* If you already use a old version. Remove your database content and start since 0
* A example of a basic databases.cfg is http://pastebin.com/XqsEjPhS
* If you want a !knife plugin you need to use the private knife version, if you still dont have it, then buy it from me (Franc1sco franug)


##### Cvars (put in server.cfg)
```
sm_weaponpaints_c4 "1" // Enable or disable that people can apply paints to the C4. 1 = enabled, 0 = disabled
sm_weaponpaints_saytimer "10" // Time in seconds for block that show the plugin commands in chat when someone type a command. -1 = never show the commands in chat
sm_weaponpaints_roundtimer "-1.0" // Time in seconds roundstart for can use the commands for change the paints. -1.0 = always can use the command
sm_weaponpaints_rmenu "1" // Re-open the menu when you select a option. 1 = enabled, 0 = disabled.
sm_weaponpaints_onlyadmin "0" // This feature is only for admins. 1 = enabled, 0 = disabled. (Use the value 1 and try to keep this plugin secret for the normal users because they can report it)
sm_weaponpaints_zombiesv "1" // Enable this for prevent crashes in zombie and 1v1 servers for knifes. 1 = enabled, 0 = disabled. (Use the value 1 if you use my knife plugin)
```