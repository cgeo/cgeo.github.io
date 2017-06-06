---
layout: page
title: Send2cgeo
redirect_from: /send2cgeo.html
---

# Send2cgeo

Send2cgeo is a script available for Mozilla Firefox and Google Chrome browser. It allows you to send geocaches directly from your desktop browser to c:geo on your phone.

[How to install send2cgeo](#how-to-install-send2cgeo)

[Register browser and/or device](#registering-browser-and-device)

[Usage instructions for send2cgeo](#how-to-use-send2cgeo)

[FAQ for send2cgeo](/faq#send2cgeo)

## Important Notes/Disclaimer

No personal data (except your browser name, your device name and geocodes) will ever be stored on our servers. This service does not use any password and you will never be asked to enter any of your passwords for it.

This service comes without any warranty and might be unavailable sometimes (e.g. due to server maintenance).

While the import function in c:geo is activated, it transmits about 5kb of data over the Internet per minute! Beware of this, if you are on 3G and don't have a flatrate.

## How to install send2cgeo

### Prerequisites:
The send2cgeo script supports Mozilla Firefox and Google Chrome. Microsoft Internet Explorer is not supported! You need to allow cookies to be stored in your browser in order for the script to work.

### Script installation:

- In Mozilla Firefox install the [Greasemonkey add-on](http://addons.mozilla.org/en-US/firefox/addon/greasemonkey/). In Google Chrome install the [Tampermonkey add-on](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) instead.
- Make sure GreaseMonkey or Tampermonkey is now activated in your browser after installation. There is a new icon in your browser toolbar.
- To start the installation, click on the script link below that fits your needs. You can install multiple scripts.
  - [geocaching.com send2cgeo script](https://github.com/cgeo/send2cgeo/raw/release/send2cgeo.user.js)
  - [opencaching.de send2cgeo script](https://github.com/cgeo/send2cgeo/raw/release/send2cgeoOc.user.js)
  - [opencaching.pl send2cgeo script](https://github.com/cgeo/send2cgeo/raw/release/send2cgeoOcPl.user.js)
- Greasemonkey/Tampermonkey will be triggered automatically, confirm the installation when prompted.
- When a new version of the script is released, your browser will automatically update it.
- Continue with the registration as described below.

## Registering browser and device

- After successful installation of the script click "Register browser" in the window shown below
- You can change the browser name by click on its name (optional step)
- Run c:geo on your android device and select Menu → Settings → Services → Send to c:geo
- Specify a device name in the setting "Your device name" (optional step)
- Select "Request Registration". You will get an info window showing a five digit PIN
- Now click "Add a device" in the window shown below and enter this PIN
- The window below should now show a registered browser and device.

<iframe src="http://send2.cgeo.org/api/" width="100%" height="300px"></iframe>

## How to use send2cgeo

- On the geocaching.com website you should be able to see a "send to c:geo" button on the cache detail page as well as on the live map popup (Next to the existing "Send to my phone" button)
- Clicking this button will add the specific cache to the queue for downloading to c:geo
- Start c:geo on your device and go to a list of saved caches
- Select Menu → Import → Import from send2cgeo
- The caches will automatically be downloaded from geocaching.com to the list of saved caches
- c:geo will continue to wait for more caches to be downloaded for 3 minutes.
