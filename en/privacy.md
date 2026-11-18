---
layout: page
lang: en
ref: privacy
permalink: /en/privacy/
title: Privacy policy
description: What data the Ávila Bus app handles, why, and how to exercise your rights.
updated: 2026-11-18
locale: en_GB
---

This policy explains what data the **Ávila Bus** app for Android (`dev.davidjuanes.avilabus`) handles, what it uses it for and what you can do about it. It applies to the app and to this website.

## Summary

- There are no accounts or sign-ups: the app doesn't know who you are.
- Your location, favourites and settings stay on your phone.
- The app sends crash reports to Google (Firebase Crashlytics), measures which screens, lines and stops are used with Google Analytics for Firebase (without your location) and shows Google AdMob ads, which use device identifiers. In the European Economic Area, the UK and Switzerland we ask for your consent before personalising ads and measuring usage.
- We don't sell personal data.

## Controller

David González Juanes, the app's developer, based in Spain. Contact: [{{ site.contact_email }}](mailto:{{ site.contact_email }}).

## What data is handled and why

### Location

If you grant location permission (approximate or precise), the app uses it to sort stops by distance, centre the maps and point the compass towards the stop. **Your location is processed only on your phone**: the app doesn't send it to any server or store it. The only thing that can give an approximate idea of where you are is which stop you open (see *Usage analytics*). The permission is optional: without it, the app uses Plaza de Santa Teresa as the starting point. You can revoke it at any time in Android settings.

### Favourites and settings

Your favourite stops, their names, their order and your preferences (arrival time format, theme and language) are stored on your phone. If Android backup is turned on, the system may include them in your Google backup, encrypted and under your account; we have no access to it.

### Arrival times

To show the next arrivals, the app asks the information service of Ávila's city buses (run by Avanza) for the times at the stop you're looking at. The request is encrypted and only carries the stop number. As with any internet connection, that server receives the IP address it comes from.

### Maps

The maps use the Google Maps SDK for Android. When they're shown, Google receives technical data such as the IP address, the device model and map usage, under [Google's privacy policy](https://policies.google.com/privacy).

### Crash reports (Firebase Crashlytics)

When the app crashes, it sends a report to Firebase Crashlytics (Google) so we can find and fix the bug. The report includes the stack trace, the device model and Android version, the app version and a Firebase installation ID, which doesn't identify you personally. It doesn't include your location or your favourites. Legal basis: our legitimate interest in the app working properly. Crashlytics keeps reports for 90 days.

### Usage analytics (Google Analytics for Firebase)

The app uses Google Analytics for Firebase to know how much it is used, which screens, lines and stops are looked at the most and on which devices, and so that AdMob and Firebase can measure ads better. It records which **screen** you see and which **line or stop** you open (only when you open its detail, not when it shows up in a list), plus what the SDK collects by itself: opening the app, the ads shown, the device model, the Android and app versions, a Firebase installation ID, the advertising ID and the approximate country and city, which come from the IP address. It **doesn't include** your GPS location, your favourites, your routes or what you search for. Note that, since stops are in a specific place, opening a nearby stop gives an approximate idea of where you are. This data is linked to the app's AdMob account and Google processes it as our provider.

- In the European Economic Area, the UK and Switzerland, analytics is off until you give your consent through Google's tool (UMP), the same one as for ads, and it stops collecting if you withdraw it from *More → Settings → Ad privacy options*. Outside those areas it is on when the app opens.
- You can reset or delete the advertising ID in Android's settings (*Privacy → Ads*).
- Google Analytics keeps the data for 14 months at most.

Legal basis: your consent in the European Economic Area, the UK and Switzerland, and our legitimate interest in knowing how the app is used elsewhere.

### Advertising (Google AdMob)

The app is free and funded by Google AdMob ads, which appear in some lists and at the bottom of some screens, never on the maps or full screen. To show and measure them and to prevent fraud, the Google Mobile Ads SDK collects and shares with Google:

- device identifiers: the advertising ID, the app set ID and, if any, identifiers of the accounts signed in on the device;
- the IP address, which may be used to estimate the device's approximate location (not your GPS location, which never leaves your phone);
- your interactions with the app and the ads, such as opening the app, taps and video views;
- diagnostic data about the app and the SDK, such as launch time, hangs and energy use.

- In the European Economic Area, the UK and Switzerland, the app asks for your consent through Google's consent tool (UMP) before showing personalised ads. If you don't give it, ads aren't personalised. You can change your choice at any time in the app's settings (*More → Settings → Ad privacy options*).
- You can reset or delete your advertising ID in Android settings (*Privacy → Ads*).
- Google handles this data as described in [how Google uses information from sites or apps that use its services](https://policies.google.com/technologies/partner-sites).

Legal basis: your consent for personalised ads and our legitimate interest for non-personalised ones.

### Feedback by email

If you write to us from *Send feedback*, the email includes the app and data versions, your phone model and Android version, to help with your request. We also receive your email address. We only use this data to reply and delete it once it's no longer needed.

### This website

This site is hosted on GitHub Pages and served through Cloudflare. Like any web server, they log technical data about visits (such as the IP address) for security and operation. The site uses no cookies, analytics, or third-party fonts or services.

## Who it's shared with

Only with the providers above, for the purposes described: Google (Firebase Crashlytics and Analytics, Google Maps and AdMob) and, to serve this site, GitHub and Cloudflare. Google may process data outside the European Economic Area under the EU-US Data Privacy Framework and the European Commission's standard contractual clauses.

## Your rights

You can ask for access to, rectification, erasure, restriction or portability of your data, and object to its processing, by writing to [{{ site.contact_email }}](mailto:{{ site.contact_email }}). As the app has no accounts, we may not be able to link any data to you. You can also lodge a complaint with the [Spanish Data Protection Agency (AEPD)](https://www.aepd.es).

To delete all of the app's data on your phone, uninstall it or clear its data in Android settings.

## Children

The app isn't specifically aimed at children and doesn't knowingly collect data from children under 14.

## Changes

If this policy changes, we'll publish the new version on this page with its update date.
