## Welcome to Bl@ckList

Blacklist maintains lists of  of Androids apps (packages) to blacklist (or whitelist) for removal by the the App BlackApps.\
You can download latest version of BlackApps here --> [BlackApps.apk](https://github.com/blackappslist/blacklists/blob/master/BlackApps.apk?raw=true)\


###  mainlist.txt

[Mainlist.txt](https://github.com/blackappslist/blacklists/raw/master/mainlist.txt) is a sample file which contains apps which could be blacklisted for removal and removed using the Bl@ckApps Android App\\


### listre.txt
[listre.txt](https://github.com/blackappslist/blacklists/raw/master/mainlist.txt) is another sample file which contains apps which could be blacklisted/whitelisted (contains regex based matches for apps/app publisher) for version 1.5 of BlackApps App and newer.\ Allows you to remove over 700 undesirable apps.\\


Other lists of apps will be added in  time\
If you want any specific malicious of undesirable app to be added to these lists. Please use issues and to indicate such apps. or you can create your own list of apps and point use its URL in Bl@ack List App.\


### File Format :-
One package/RegExp per line as follows\

Java-style Package Name,       App Name,  <App Category (optional)> \
#RegExp to match package name, App Name,  <App Category (optional)> \

eg:\
com.facebook.katana, Facebook, Social Media\
com.facebook.lite,  Facebook Lite, Social Media\
#^com\.adobe\..* , All Adobe Apps
