---
title: GeoPunch Privacy Policy
permalink: /privacy/
---

<!-- Copy of docs/privacy-policy.md in the app repository. Edit that file and copy it here. -->

# GeoPunch Privacy Policy

_Last updated: October 23, 2026_

GeoPunch ("the app") is an Android app, developed by Aleksey Sokolov, that punches you in and out of your employer's OrangeHRM 5 server based on where you are. This policy explains what data the app handles, where it goes and how you control it.

GeoPunch is an independent third-party tool and is not affiliated with, endorsed by, sponsored by, or associated with OrangeHRM Inc. in any manner.

## Summary

- There is no GeoPunch account, no GeoPunch server and no cloud service. The developer receives none of your data, except an email you choose to send.
- Your attendance data goes only to the OrangeHRM server **you** enter in the app, which is run by your employer (or by you).
- Your location is used on your device to tell whether you are at a work site. Your position is never sent to your OrangeHRM server or to the developer. The only exception is the Work Sites screen: map and address services can learn your approximate location there (see below).
- No ads, no analytics, no crash-reporting or tracking SDKs.

## Data stored on your device

| Data | Why |
|---|---|
| Server address, username and password | To sign in to your OrangeHRM server. Encrypted with a key held in the Android Keystore. |
| Work sites (name, address, coordinates, radius, optional office Wi-Fi name) | To detect when you arrive at or leave a site. |
| Punch history (time, note, sync status and the position where each punch happened) | To show your attendance and retry punches that could not be sent. |
| Your profile (name, photo), company logo, holidays and leave days, cached from your server | To show them in the app and to skip automatic punches on days off. |
| App settings | To remember your preferences. |

This data stays in the app's private storage. Android backups are disabled for the app, so it isn't copied to your Google account backup.

## Data sent off your device

**To your OrangeHRM server** (the address you enter; HTTPS only):
- Your username and password, to sign in.
- Each punch: date, time, time zone and a note. Automatic punches include a note naming the work site, for example "Automated Geofence Entry at Main Office". You can edit the note before confirming.
- Leave requests and cancellations you submit.
- Requests to read your profile, attendance, leave balances, holidays and the company logo.

Your employer controls that server and the data on it, under its own privacy policy.

**To map and address services** (only when you use the Work Sites screen):
- **Map tiles from OpenStreetMap** (tile.openstreetmap.org): the map area you are viewing and your IP address, as with any web map. If you tap "use my location", the map shows the area around you, so OpenStreetMap receives your approximate location. See the [OSM Foundation privacy policy](https://osmfoundation.org/wiki/Privacy_Policy).
- **Address search** uses Android's built-in Geocoder (provided by Google on most devices) and, if that finds nothing, OpenStreetMap Nominatim (nominatim.openstreetmap.org). The address text you type is sent to look it up. When you pick a point on the map or tap "use my location", that point is sent to the device's Geocoder (not to Nominatim) to show its street address.
- You can avoid both by typing the address of your work site instead of using your location.

**By email** (only when you tap "Report a problem" or "Suggest a feature" in Settings → About & Legal):
- Your email app opens with a message to alkaes@gmail.com. "Report a problem" fills in the app version, phone model and Android version. Nothing is sent until you send it yourself, and you can edit or remove those details first. The developer receives that email and your email address and uses them only to reply to you.

**Location services:** the app uses Android's location services (Google Play services fused location) to read your position on the device.

Nothing else is sent anywhere.

## Location

GeoPunch needs the location permission to notice when you arrive at or leave a work site.
- Location is used only while the app is open or while its monitoring notification is showing.
- The app does not request background location access.
- Positions are compared with your work sites on the device. The app doesn't keep a location history; only the position at the moment of each punch is saved with that punch record, on the device. These positions are never transmitted; only the Work Sites map and address lookups described above can reveal an approximate location.
- You can stop monitoring in Settings → Attendance rules, or revoke the permission in Android settings at any time.

## Notifications

Notifications are used to confirm, adjust or cancel each punch, to show that monitoring is running, and to remind you about a forgotten punch-out.

## Sharing and selling

The developer does not collect, share or sell your data; emails you send are used only to reply to you. Data reaches third parties only as described above (your employer's server, OpenStreetMap and your device's geocoding provider), and only to provide the app's functions.

## Retention and deletion

- **Sign out** (Settings → Server connection) deletes the server address, credentials, cached profile, photo and logo from the device.
- **Uninstalling** the app deletes all of its data from the device.
- Attendance and leave records on your OrangeHRM server are kept and deleted by your employer. Ask your HR administrator.

## Security

All traffic to your server must use HTTPS; plain HTTP is refused. Credentials are encrypted on the device. Log output never includes credentials, cookies or employee details.

## Children

GeoPunch is a workplace tool and is not directed at children under 13.

## Changes

If this policy changes, the updated version will be published at the same address with a new "Last updated" date.

## Contact

Questions about this policy: alkaes@gmail.com
