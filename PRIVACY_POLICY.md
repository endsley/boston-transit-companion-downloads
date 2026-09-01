# Boston MBTA Routes Privacy Policy

**Effective date:** September 1, 2026

Boston MBTA Routes is a map-first companion for MBTA bus, subway, light-rail,
Silver Line, and Mattapan service. This policy explains how the Android app
handles information.

## Information the app uses

### Location

If you grant foreground location permission, the app reads your approximate or
precise current location while the map is visible. It uses the location on your
device to find nearby stops. To request nearby realtime predictions, it sends
the current latitude and longitude to the MBTA's public API over HTTPS. The app
does not keep a location history or operate a server that receives your
location.

You can use the map without granting location permission; it opens in central
Boston instead.

### Transit preferences and alarms

Favorite groups, saved stops, route-direction preferences, arrival alarms, and
notification choices are stored only in the app's local database on your
device. They are not automatically backed up to cloud or device-transfer
services.

When you choose to export a backup, Android's system file picker writes the
backup to the location you select. When you restore one, the app reads only the
file you explicitly select. Saved stop and route identifiers are sent to the
MBTA only when needed to obtain the realtime arrivals, alerts, or schedules you
asked the app to display.

### Notifications

If you grant notification permission and create an arrival alarm or enable
saved-route disruption notices, the app posts notifications on your device.
Arrival-alarm state remains local to the device.

## Network services

The app connects directly to these services over HTTPS:

- **MBTA APIs and GTFS download service** for schedules, predictions, vehicles,
  alerts, station information, and static transit data.
- **OpenFreeMap/OpenStreetMap map-tile service**, rendered through MapLibre.
- **Google Play** to deliver the app and its updates when installed from Google
  Play.

The app has no user accounts, advertising SDKs, analytics, telemetry, or
developer-operated backend servers.

## Retention and deletion

Remove individual saved items in the app, clear the app's storage, or uninstall
the app to delete the local information it stores. Backups you export are under
your control and must be deleted from the location you chose separately.

## Security

The app uses HTTPS for its network connections. No method of transmission or
storage is completely secure, but the app does not intentionally transmit local
preferences or alarm data except as described above.

## Changes and contact

We may update this policy when app behavior changes. The current version and
effective date are published at this URL. For privacy questions or a deletion
request, use the support contact shown on the Google Play store listing.
