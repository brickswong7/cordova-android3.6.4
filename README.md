# cordova android 3.6.4 (below 4.0.0).
the cordova version (Do restore ancient ways).
Today, i want to do something about the cordova! 
Recently, there are some tools to package your application for android.
But now, i wanna restore the cordova version under 4.0 .0!
Now, i explain why i have to do that. 
the reason is smart TV. 
But， the part of smart TVs is handled by remotes，which have not touchingscreen function，and that means we have to apply the cordova version below 4.0

Steps:
一：cordova创建一个App（cordova create a App） 
cordova create App *****!


二：看一下 cordova platform 里面的可以应用的版本 (have a look Available platforms) 
cordova platform ls
cordova platform ls Available platforms: 
amazon-fireos ~3.6.3 (deprecated) 
android ~5.2.0 blackberry10 ~3.8.0 
browser ~4.1.0 firefoxos ~3.6.3 
webos ~3.7.0 
windows ~4.4.0 
wp8 ~3.8.2 (deprecated)


三：创建cordova android 3.6.4版本 （cordova android 3.6.4） 
cordova platform add android@3.6.4

四：结果 Result:
Project successfully created.
Using this version of Cordova with older version of cordova-android is being deprecated. Consider upgrading to cordova-android@5.0.0 or newer.

五:check check check! 
paltform cordova platform ls: 
result: Installed platforms: android 3.6.4 Available platforms: amazon-fireos ~3.6.3 (deprecated) blackberry10 ~3.8.0 browser ~4.1.0 firefoxos ~3.6.3 webos ~3.7.0 windows ~4.4.0 wp8 ~3.8.2 (deprecated)


六：恭喜你 。你需要的版本成功了！Congratulations！
