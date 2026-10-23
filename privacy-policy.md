# Corduroy privacy policy

Last updated 23 October 2026.

Corduroy keeps your ski days on your phone. There are no accounts, no ads, no analytics and no tracking. The developer
runs no server that receives your data, and nothing you enter is sold or shared.

## What stays on your phone

- The passes you hold, what you paid for them and a walk-up ticket price if you enter them, your Ski Free voucher
  count and your units.
- Your home town and its map position, if you set one. It's used for distances to resorts.
- The days you log: date, resort, pass, how the day counted and your notes.
- Ski days you import from Slopes, GPX or KMZ files: the GPS track, its stats and the runs it matched.
- Ski days you record in the app: the GPS track (time, position and height every few seconds while recording), its
  stats and the runs and lifts it matched.
- Stored forecasts, and the resorts you told check-ins to skip.

All of this is deleted when you uninstall the app or clear its storage.

## Location

Location is used for two things, each off until you choose it: Day check-ins and recording a day.

**Day check-ins** are off until you turn them on in Settings.

- When the app is open, it asks the phone where it is, to see whether you're at a resort on your passes.
- If you also allow location all the time, Android watches the area around nearby resorts on your passes. After about
  90 minutes at one, the app shows a notification asking whether to log the day. Nothing is logged unless you tap Log it.

Check-ins don't store your location.

**Recording a day** starts only when you tap Start recording or Record a day. From then until it stops, the app notes
the phone's position every 2 seconds while you're moving and every 15 seconds while you're standing still, and shows a
notification the whole time with Pause and Stop. It stops when you tap Stop, or by itself once you've been well away from
the resort for 15 minutes. The track is kept on your phone. If you log the day, it's saved with the day; if you discard
it, it's deleted.

The app never sends your location anywhere. Your phone works out its position using Google Play services, under
Google's own privacy policy. You can turn check-ins off in Settings, stop a recording, or remove the permission in
Android's settings, at any time.

## What the app sends over the internet

The app downloads forecasts and alerts. Each request goes straight to the service named below and carries only
what's listed. As with any internet request, the service also sees your IP address.

- **Open-Meteo** (api.open-meteo.com): the map position and height of resorts on your passes, to get their forecasts.
  The list of resorts can show which passes you hold. Your own location is never sent. With powder alerts on, this
  also happens once a day in the background, for resorts on your passes within your alert distance.
- **US National Weather Service** (api.weather.gov): the map position of a US resort when you open its page, to check
  for storm alerts.
- **Google** (www.google.com), in test builds only: a resort's website address, to fetch its logo. The version on
  Google Play shows the resort's initials instead and never makes this request.
- **Your phone's address lookup**: the town or ZIP code you type for your home location. Android's built-in geocoder
  sends it to Google to find it on the map.
- **GitHub** (raw.githubusercontent.com): the list of resorts and pass rules, at most once a day, so changes reach
  you without an app update. Nothing about you is sent with it.

Buttons such as Website, Snow report and Directions open your browser or maps app. Those apps and sites have their own
privacy policies.

## Backups

- **Export visits** saves your logged days to a file in the place you choose. What happens to that file is up to you.
- If Android backup to your Google account is turned on, Android may include the app's data in that backup. You
  control this in Android's settings.

## Imported files

Files you share to Corduroy or pick in Settings are read on your phone. Their tracks are kept on your phone and are
not uploaded. The same goes for the days you record.

## Children

Corduroy isn't directed at children under 13 and doesn't knowingly collect anything from them.

## Changes

If this policy changes, the new version will be posted here with a new date.

## Contact

Questions about this policy: [CONTACT EMAIL]
