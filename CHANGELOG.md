# Changelog

User-visible changes in each GeoPunch release. The version is shown in Settings → About & Legal.

## 1.2

First Google Play closed-test release.

### New
- **One record per day**: if you leave the site and come back the same day, GeoPunch keeps your first punch-in and moves the punch-out to when you finally leave (Settings → Attendance rules, on by default). Moving a punch-out needs *"Employee can edit/delete own attendance records"* on the server.
- Session editor: add or correct missed punches, with checks against overlapping or impossible times.
- Leave day totals in the Monthly view.

### Fixed
- Much lower battery use: the GPS no longer runs at full power for the whole workday while you're on site.
- On phones without network location, the location no longer goes stale far from a site.
- Adding a past day no longer shows a false "Still punched in?" reminder.
- The countdown in the punch confirmation dialog stays on one line.
- Status bar icons are readable when the in-app theme differs from the system theme.

## 1.1

- Onboarding card on Home: server, work site, location permission.
- Office Wi-Fi: being on a site's Wi-Fi counts as being on site.
- Home-screen widget, Quick Settings tile and launcher shortcuts.
- Daily target in the Monthly view.
- More reliable punch sync and geofence detection.

## 1.0

- Automatic punch in/out based on work sites drawn on a map, with an exit grace period and "Stay in today".
- Confirm, cancel or adjust the time before every automatic punch.
- Monthly attendance, leave balances and requests, profile.
- Work week and holidays, English, Hebrew and Russian.
