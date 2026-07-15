# Crew Status — public config

Fetched by the iOS app at:

`https://raw.githubusercontent.com/alexnjafari/flightAttendantSchedule-config/main/app.json`

## Fields

| Field | Description |
| --- | --- |
| `appStoreId` | Numeric App Store ID (used as `https://apps.apple.com/app/id{appStoreId}`). Leave `""` until the listing is live. |
| `latestVersion` | Latest App Store marketing version (e.g. `"1.0.1"`). |
| `minimumVersion` | Optional minimum supported version for future force-update checks. |

Update this file and push to `main` whenever you ship or get an App Store ID — no app update required for the share link / version check.
