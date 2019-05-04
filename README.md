# FF-Disable-ExtensionSigning

This modification disables the requirement for addon to be digitally signed.

Tested on FF 52.0.2 and 55.x

WARNING: This disables a security feature. FF will accept any potentially malicous addon. Be sure to remove this modification as soon as possible.

To install:
- copy the „mozilla.cfg“ into your FF installation path (usually „C:\Program Files\Mozilla Firefox“)
- copy the „autoconfig.js“ to the „.\defaults\pref\“ folder inside your FF installation path.
If one of the files already exists, append the lines at the end.
