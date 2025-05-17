---
layout: page
title: Development
---

# Development

c:geo is an open-source application, distributed under [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

## Source Code

Our source code is hosted on [GitHub](https://github.com/cgeo/cgeo). If you want to participate in the development, just check the [Readme](https://github.com/cgeo/cgeo/blob/master/README.md) and our [Wiki](https://github.com/cgeo/cgeo/wiki).

## Our website

Like our application also this website is [open source](https://github.com/cgeo/cgeo.github.io). If you want to fix a typo or otherwise improve it, you are welcome to contribute as described in the [readme file](https://github.com/cgeo/cgeo.github.io/blob/master/README.md).

## Our user guide

We do also have a [user guide](https://manual.cgeo.org) with a detailed description of all parts of the app. It is already available in some languages. We however need help to update translations and add translations into even more language. Learn here how to [help translating the user guide](https://manual.cgeo.org/en/translation).

## Beta Testing

You can also help us by becoming a beta tester for the release candidate versions of c:geo.

Becoming beta tester is just one click away: [c:geo Google Play Beta Testing](https://play.google.com/apps/testing/cgeo.geocaching)

After you enabled the beta testing mode you will receive beta versions (release candidates of c:geo) via Google Play update on the same way you receive the normal c:geo updates (it might take a few hours after enabling the beta testing mode). Additionally you can send us your feedback and problem reports via a dedicated Google Play feedback form.

Please be aware that beta releases might be unstable or not all functions are working as expected. However before we bring a version into beta testing we do our very best to make sure, that all basic functions are working properly.
You will not receive any possibly unstable alpha versions or nightly builds (see next chapter) via this beta channel.

If you wish to discontinue beta testing just use the link above and deselect the beta testing mode.
Afterwards you might need to uninstall the beta version from your device and reinstall the normal version from Google Play.

## Nightly Builds

You can use our nightly builds to test new features of upcoming versions. They are **not for normal usage**, as they contain code that is not well tested yet. Only install these versions if you know what you're doing.

Nightly builds can cause all kinds of crashes and malfunction. Please report such bugs, but don't expect us to deliver a fix right afterwards. If you need stable functionality, use the normal build.

The version without JIT is necessary for some devices with a MediaTek CPU. If you observe strange behavior in the live map or jumping distances, try the build without JIT.

Please be aware:

Direct downgrading from a nightly version to a production (or beta) version is not possible due to Android versioning restrictions. You need to manually deinstall the nightly and afterwards install the production (or beta) version.

Furthermore also a data backup you made in a nightly version might not be compatible to be restored into the production (or beta) version as the underlying database might have been changed in the meantime.

Please consider this, when using our nightly builds.

### Download Nightly Builds

[c:geo application](https://download.cgeo.org/cgeo-nightly.apk)\\
[c:geo application (without JIT)](https://download.cgeo.org/cgeo-nightly-nojit.apk)

## F-Droid repository

As an alternative to Google Play, c:geo can be downloaded from our private [F-Droid](https://f-droid.org/) repository.

We provide two channels, for stable and nightly builds.

### Repository channels

* [Mainline](fdroidrepos://fdroid.cgeo.org/fdroid/repo?fingerprint=370BB4D550C391D5DCCB6C81FD82FDA4892964764E085A09B7E075E9BAD5ED98)
* [Nightly](fdroidrepos://fdroid.cgeo.org/nightly/fdroid/repo?fingerprint=58AC102C3D6F16D0F4386415D75BC0EB64468C3817410EA0A4DA28912E826F08)

> ##### NIGHTLY REPO KEY CHANGE
>
> The Nightly repository has changed its signing key on 2025-05-17. Please import it again if you use it.
{: .block-warning }


### Instructions

1. Install the [F-Droid](https://f-droid.org/) client app.
1. Click on one of the c:geo repository link above to add the repository.
1. Refresh your F-Droid client app under the Categories tab.
1. Install c:geo from the F-Droid client app listing.

## Translation of c:geo

If you want to contribute translations, you need a free account at [Crowdin](https://crowdin.com/). Then start contributing new translations to or vote for existing translation proposals in the [c:geo translation project](https://crowdin.com/project/cgeo). If you would like to include a new language please contact us via Crowdin.

Localization statistics: [![Crowdin](https://badges.crowdin.net/cgeo/localized.svg)](https://crowdin.com/project/cgeo)

## Current status and usage statistics

While c:geo is in use it checks every 30 minutes for new notifications (these are shown on the homescreen of c:geo). Together with the IP of the device only the version of c:geo and the user's language are transferred to our server. This data is kept only temporarily and deleted after 30 minutes.

Our [status page](/status) shows a snapshot of the current usage of c:geo, split by version numbers. Additionally it shows the warnings of our user notification system (if there any).

We use GeoIP to estimate the user's location from the IP address (which usually points to the next big city or county). With this information it is possible to create a [heatmap of people currently using c:geo](/heatmap). It is neither possible to track individual users, nor do we ever track your individual GPS-position.
