Cordova DeviceIdentifier-Plugin
====================

A plugin to get device indetifier for Cordova 3.x.x

by Tamir Twina ([github.com/tamirtw](https://github.com/tamirtw))

## Supported Platforms
- **iOS**<br>  
            Reuires iOS 6.0+    

- **Android**  
            Coming soon

## Adding the Plugin to your project
Through the [Command-line Interface](http://cordova.apache.org/docs/en/3.0.0/guide_cli_index.md.html#The%20Command-line%20Interface):
```
cordova plugin add https://github.com/tamirtw/cordova-plugin-device-identifier.git
```

## Removing the Plugin from your project
Through the [Command-line Interface](http://cordova.apache.org/docs/en/3.0.0/guide_cli_index.md.html#The%20Command-line%20Interface):
```
cordova plugin rm com.tamirtw.cordova.plugin.device-identifier
```

## PhoneGap Build
Add the following xml to your config.xml to always use the latest version of this plugin:
```
<gap:plugin name="com.tamirtw.cordova.plugin.device-identifier" />
```
or to use this exact version:
```
<gap:plugin name="com.tamirtw.cordova.plugin.device-identifier" version="0.0.1" />
```
More informations can be found [here](https://build.phonegap.com/plugins/333).

## Release Notes

#### Version 0.0.1 (12.02.2014)
- Added iOS support<br>
  

## Using the plugin
The plugin creates the object ```window.plugin.deviceIdentifier``` with two methods:

### uniqueIdentifier()

```javascript
/*
 * Get device vendor identifier
 */
window.plugin.deviceIdentifier.uniqueIdentifier(
    function(Idfv) {
        alert(Idfv);
    }
);
```
This software is released under the [MIT License](http://opensource.org/licenses/MIT).
