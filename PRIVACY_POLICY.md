---
title: Política de privacidad
permalink: /PRIVACY_POLICY/
---

# RRRadio — Privacy Policy

**Last updated:** 2026-07-13

RRRadio respects your privacy. This policy explains what data the app handles and how.

## 1. Personal data

RRRadio does **not** collect, store, or transmit any personal data. There is no login, no
account, no analytics, and no crash reporting built into the app.

## 2. Local data

The following data is stored **only on your device** and is never sent to any server:

- **Favorites:** stations you've marked as favorite.
- **Last played:** the station you last listened to (to restore the mini-player).
- **Traffic usage:** your data-consumption history (for the traffic meter feature).

This data remains on your device until you uninstall the app or clear its data.

## 3. Third-party services

RRRadio uses the **Radio Browser API** (`api.radio-browser.info`) to search for radio stations.
When you search or browse stations, your app sends a request to this public API. These requests
are anonymous (no user identifier is sent). Radio Browser's own privacy practices are governed by
their policy at `https://api.radio-browser.info/`.

## 4. Streaming

When you play a radio station, the app connects directly to the station's streaming server
(provided by the station, not by RRRadio). Your IP address is visible to that server, as with any
internet radio player.

## 5. Permissions

| Permission | Why |
|---|---|
| `INTERNET` | Stream radio audio and search for stations. |
| `FOREGROUND_SERVICE` + `FOREGROUND_SERVICE_MEDIA_PLAYBACK` | Keep audio playing in the background. |
| `POST_NOTIFICATIONS` | Show playback controls on the lock screen and notification bar (Android 13+). |
| `WAKE_LOCK` | Prevent the CPU from sleeping during playback (managed by Media3). |

## 6. Children's privacy

RRRadio is not directed at children under 13 and does not knowingly collect data from them.

## 7. Changes

If this policy changes, the updated version will be posted here with a new date.

## 8. Contact

For questions about this policy, open an issue on the project's GitHub repository.
