---
layout: page
title: Development
---

# Development

c:geo is an open source application, distributed under [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Source Code

Our source code is hosted on [GitHub](https://github.com/cgeo/cgeo). If you want to participate in the development, just check the [Readme](https://github.com/cgeo/cgeo/blob/master/README.md) and our [Wiki](https://github.com/cgeo/cgeo/wiki).

## Developer chat

If you want to contact the developers directly, join our IRC channel [#cgeo on freenode.net](https://webchat.freenode.net/?channels=%23cgeo). It might take some time until someone can respond to your question, most activity happens in the evening (European time zones).

## Our website

Like our application also this website is [open source](https://github.com/cgeo/cgeo.github.io). If you want to fix a typo or otherwise improve it, you are welcome to contribute as described in the [readme file](https://github.com/cgeo/cgeo.github.io/blob/master/README.md).

We are also looking for people willing to help writing a users manual for c:geo. Just contact us via GitHub if you are interested.

## Nightly Builds

You can use our nightly builds to test new features of upcoming versions. They are **not for normal usage**, as they contain code that is not well tested yet. Only install these versions if you know what you're doing.

Nightly builds can cause all kinds of crashes and malfunction. Please report such bugs, but don't expect us to deliver a fix right afterwards. If you need stable functionality, use the normal build.

The version without JIT is necessary for some devices with a MediaTek CPU. If you observe strange behavior in the live map or jumping distances, try the build without JIT.

### Download Nightly Builds

[c:geo application](http://download.cgeo.org/cgeo-nightly.apk)\\
[c:geo application (without JIT)](http://download.cgeo.org/cgeo-nightly-nojit.apk)\\
[calendar plugin](http://download.cgeo.org/cgeo-calendar-nightly.apk)\\
[contacts plugin](http://download.cgeo.org/cgeo-contacts-nightly.apk)

## F-Droid repository

As an alternative to Google Play, c:geo could be downloaded from our private [F-Droid](https://f-droid.org/) repository.

We provide two channels, for stable and nightly builds.

* https://fdroid.cgeo.org
* https://fdroid.cgeo.org/nightly

Our repository fingerprint is:

* 370BB4D550C391D5DCCB6C81FD82FDA4892964764E085A09B7E075E9BAD5ED98

## Translation of c:geo

If you want to contribute translations, you need a free account on [Crowdin](https://crowdin.com/). Then start contributing translations or vote for existing translation proposals to the [c:geo Crowdin project](https://crowdin.com/project/cgeo). If you would like to include a new language please contact us via Crowdin.

Localization statistics: [![Crowdin](https://d322cqt584bo4o.cloudfront.net/cgeo/localized.png)](https://crowdin.com/project/cgeo)

## Current status and usage statistics

While c:geo is in use it checks every 30 minutes for new notifications (these are shown on the homescreen of c:geo). Together with the IP of the device only the version of c:geo and the user's language are transferred to our server. This data is kept only temporarily and deleted after 30 minutes.

Our [status page](/status.html) shows a snapshot of the current usage of c:geo, split by version numbers. Additionally it shows the warnings of our user notification system (if there any).

We use GeoIP to estimate the user's location from the IP address (which usually points to the next big city or county). With this information it is possible to create a [heatmap of people currently using c:geo](heatmap.html). It is neither possible to track individual users, nor do we ever track your individual GPS-position.
