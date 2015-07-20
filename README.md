# [mixpanel](https://mixpanel.com/)-js-shim

This is the mixpanel integration library packaged as a CommonJS.

Note: The MixPanel integration library requires that it  be attached to the window on `window.mixpanel` in addition to  being exported with `module.exports`.

## Usage:
```.js
var mixpanel = require('mixpanel-js-shim');
mixpanel.init('your_token');
```
