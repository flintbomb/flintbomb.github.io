# flintbomb.github.io

Website for Jason Petrovffsky's Android apps, served by GitHub Pages at <https://flintbomb.github.io/>.

- `nmea-bluetooth-access/` — NMEA Bluetooth Access home page
- `nmea-bluetooth-access/privacy/` — its privacy policy, linked from Google Play, the app and the Gmail OAuth consent screen
- `armesh/` — ARmesh home page
- `armesh/privacy/` — its privacy policy, linked from Google Play and from the app's config screen

Play requires the policy both on the store listing and inside the app for any
app that asks for a sensitive permission, which both of these do. Keep the
effective date at the top of a policy honest: edit it when the substance
changes, not on every typo fix.

Plain HTML and CSS with no build step. `.nojekyll` makes GitHub Pages serve the files as they are.
