# CwC Bypass

Bypass browser level internet restrictions by using Coding with Chrome

# Deprecation Notice
Per [Google's support document](https://knowledge.workspace.google.com/kb/ending-support-for-chrome-apps-000008392), Chrome Apps will no longer be user installable starting July 2025. This method requires the use of the "Coding With Chrome" Chrome App. After this date, new installations will not be possible, with support for Chrome Apps being completely removed February 2028.

## Download

- [Bypass](https://github.com/lebestnoob/cwc-bypass/raw/main/bypass.html)

- [Simple](https://github.com/lebestnoob/cwc-bypass/raw/main/simple.html)

- [Iframe Bypass **(NOT SUPPORTED)**](https://github.com/lebestnoob/cwc-bypass/raw/main/bypass-iframe.html)

Right click and choose `Save link as...`

## How to use

1. Download the file from the top
2. ~~Add the [Coding with Chrome](https://chrome.google.com/webstore/detail/coding-with-chrome/becloognjehhioodmnimnehjcibkloed) app to your browser from the [Chrome Web Store](https://chrome.google.com/webstore)~~ The application has been delisted. You need to manually add it as an unpacked extension. A CRX file for the extension id `becloognjehhioodmnimnehjcibkloed` needs to found online.
3. Open Coding with Chrome
4. Click the hamburger menu on the top left corner of the app
5. Click on `Open file` and select the file you previously downloaded

## Limitations

- Browser full screen mode does not work
- User Agent is sent as `CWC sandbox`, with no feasable way to change it to a "standard" one
- Anything that requires permission or interaction from the user's browser does not work (Media, HID, Web Speech API, Alert Boxes, Notifications, etc.)
- Opening links in a New Tab will open it in the regular browser
- Downloading does not work
- No browser settings
- No history tracking
- URLs blocked by a chrome policy do not load
