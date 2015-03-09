---
layout: page
title: Send2cgeo
---

# Send2cgeo

Send2cgeo is a script available for Mozilla Firefox or Google Chrome browser. It allows you to send geocaches directly from your browser to c:geo on your phone.

[How to install send2cgeo?](#howto)\\
[Get the script!](#script)\\
[Usage instructions for send2cgeo](#usage)\\
[FAQ for send2cgeo](/faq.html#faq.Whatissend)

## Disclaimer

No personal data (except your browser name, your device name and geocodes) will ever be stored on our servers. This service does not use any password and you will never be asked to enter any of your passwords for it.

This service comes without any warranty and might be unavailable sometimes (e.g. due to server maintenance).

While the import function in c:geo is activated, it transmits about 5kb of data over the internet per minute! Beware of this, if you are on 3G and don't have a flatrate.

## How to install send2cgeo?
<a name="howto"></a>

### Important Note:
The send2c:geo script supports Mozilla Firefox and Google Chrome. Microsoft Internet Explorer is not supported! You need to allow cookies to be stored in your browser in order for the script to work.

### Script installation with Firefox:

    Install the greasemonkey add-on: http://addons.mozilla.org/en-US/firefox/addon/greasemonkey/
    Open the send2c:geo script page: https://send2.cgeo.org/script.html
    Start installing the script by clicking on "Start"
    Greasemonkey will be triggered automatically, confirm the installation when prompted
    Continue with the registration as described below

### Script installation with Chrome:

    Install the Tampermonkey add-on
    Open the send2c:geo script page: https://send2.cgeo.org/script.html
    Start installing the script by clicking on "Start"
    Tampermonkey will be triggered automatically, confirm the installation when prompted
    Continue with the registration as described below

### Registering browser and device:

    After succesful installation of the script click "Register browser" on the right sidebar of the send2c:geo webpage https://send2.cgeo.org
    You can change the browser name by click on its name (optional step)
    Run c:geo on your android device and select Menu → Settings → Services → send2c:geo
    Specify a device name in the setting "Your device name" (optional step)
    Select "Request Registration". You will get an info window showing a five digit PIN
    Now click "Add a device" in your browser and enter this PIN
    The webpage should now show a registrated browser and device on the right sidebar

## How to use send2cgeo
<a name="usage"></a>

- On the geocaching.com website you should be able to see a "send to c:geo" button on the cache detail page as well as on the live map popup (Next to the existing "Send to my phone" button)
- Clicking this button will add the specific cache to the queue for downloading to c:geo
- Start c:geo on your device and go to a list of saved caches
- Select Menu → Import → Import from web
- The caches will automatically be downloaded from geocaching.com to the list of saved caches
- c:geo will continue to wait for more caches to be downloaded for 3 minutes.

## Get the script!
<a name="script"></a>

Make sure you have Greasemonkey/Tampermonkey installed and active in your browser before continuing.

The installation should start automatically in Greasemonkey/Tampermonkey if you click on the link below:\\
[Script installation](https://github.com/cgeo/cgeo/raw/master/send2cgeo/send2cgeo.user.js)


