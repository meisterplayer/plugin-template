GoogleIma
=========

This plugin allows advertisements to be played with Google IMA.

This plugin is usually used in conjuction with the [AdItem plugin for Meister](https://github.com/meisterplayer/parser-aditem). Ads specified in that plugin will be played with this plugin. For more details on how to do this please refer to its [README](https://github.com/meisterplayer/parser-aditem).

Config options
---------

Options are required unless marked as [optional].

* **scriptUrl** :: *String*  
    The location of the Google IMA SDK.

Example:

``` JavaScript
var meisterPlayer = new Meister('#player', {
    GoogleIma: {
        scriptUrl: 'https://imasdk.googleapis.com/js/sdkloader/ima3.js',
    }
});
```

