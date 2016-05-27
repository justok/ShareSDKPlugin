ShareSDKPlugin
==============
##cordova plugin shareSDK

This is a plugin for ShareSDK(http://mob.com/#/index) in Apache Cordova/PhoneGap! 

![dd](http://demo.mob.com/wiki/wp-content/themes/twentyfourteen/images/u139_normal.jpg)
### Sample Code

```javascript
var message = {
                title: "我",
                content: "ah",
                url: "http://www.baidu.com",
                imagePath: "http://ac-p9y5fh0m.clouddn.com/c28cb93e9a0eae4b3b11.jpg"
            };
ShareSDK.share(message,null,null);
```
### Installation
1
```sh
cordova plugin add https://github.com/justok/ShareSDKPlugin --variable WECHATAPPID=YOUR_APPID --variable SHARESDKAPPID=YOUR_SHARESDKAPPID --variable WECHATAPPSECRET=YOUR_WECHATAPPSECRET --variable QQAPPID=YOUR_QQAPPID --variable QQAPPSECRET=YOUR_QQAPPSECRET
```
2
```sh
cordova build ios 
```
### Feature
Wechat share for iOS ,微信分享

###TO-DO
- Sina share
- QQ share
- More ShareSDK API
- for android


###License
----

MIT
