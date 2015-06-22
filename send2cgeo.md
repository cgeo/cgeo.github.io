---
layout: page
title: Send2cgeo
---

# Send2cgeo

Send2cgeo is a script available for Mozilla Firefox and Google Chrome browser. It allows you to send geocaches directly from your browser to c:geo on your phone.

[How to install send2cgeo](#how-to-install-send2cgeo)

[Register browser and/or device](#registering-browser-and-device)

[Usage instructions for send2cgeo](#how-to-use-send2cgeo)

[FAQ for send2cgeo](/faq.html#faq.Whatissend)

[Download the script](#download-the-script)

## Important Notes/Disclaimer

No personal data (except your browser name, your device name and geocodes) will ever be stored on our servers. This service does not use any password and you will never be asked to enter any of your passwords for it.

This service comes without any warranty and might be unavailable sometimes (e.g. due to server maintenance).

While the import function in c:geo is activated, it transmits about 5kb of data over the internet per minute! Beware of this, if you are on 3G and don't have a flatrate.

## How to install send2cgeo

### Prerequisites:
The send2cgeo script supports Mozilla Firefox and Google Chrome. Microsoft Internet Explorer is not supported! You need to allow cookies to be stored in your browser in order for the script to work.

### Script installation with Mozilla Firefox:

- Install the [Greasemonkey add-on](http://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) and make sure it is activated in your browser after installation
- Start installing the script by clicking [here](https://github.com/cgeo/cgeo/raw/master/send2cgeo/send2cgeo.user.js)
- Greasemonkey will be triggered automatically, confirm the installation when prompted
- Continue with the registration as described below

### Script installation with Google Chrome:

- Install the [Tampermonkey add-on](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) and make sure it is activated in your browser after installation
- Start installing the script by clicking [here](https://github.com/cgeo/cgeo/raw/master/send2cgeo/send2cgeo.user.js)
- Tampermonkey will be triggered automatically, confirm the installation when prompted
- Continue with the registration as described below

## Registering browser and device

- After succesful installation of the script click "Register browser" in the window shown below
- You can change the browser name by click on its name (optional step)
- Run c:geo on your android device and select Menu → Settings → Services → Send to c:geo
- Specify a device name in the setting "Your device name" (optional step)
- Select "Request Registration". You will get an info window showing a five digit PIN
- Now click "Add a device" in the window shown below and enter this PIN
- The window below should now show a registrated browser and device.

<iframe src="http://send2.cgeo.org/api/" width="100%" height="300px"></iframe>

## How to use send2cgeo

- On the geocaching.com website you should be able to see a "send to c:geo" button on the cache detail page as well as on the live map popup (Next to the existing "Send to my phone" button)
- Clicking this button will add the specific cache to the queue for downloading to c:geo
- Start c:geo on your device and go to a list of saved caches
- Select Menu → Import → Import from send2cgeo
- The caches will automatically be downloaded from geocaching.com to the list of saved caches
- c:geo will continue to wait for more caches to be downloaded for 3 minutes.

## Download the script

Make sure you have Greasemonkey/Tampermonkey **installed and active** in your browser before continuing.
Otherwise please read [How to install send2cgeo](#how-to-install-send2cgeo) first.

The installation should start automatically in Greasemonkey/Tampermonkey if you click on the link below:\\
[Script installation](https://github.com/cgeo/cgeo/raw/master/send2cgeo/send2cgeo.user.js)
