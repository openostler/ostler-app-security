# Ostler Security app

Alarm, tracker, geofences (the Guardian product).

Part of [Ostler](https://github.com/openostler/ostler), an open, local-first,
smart-home-like ecosystem for your car. Ostler is built like a phone OS: the
platform repo is the bare system, and every feature is an app or pack in its
own repo, installed from the Store.

Status: empty. This project follows UX first: design, then UI against
recorded fixtures, then wiring. Nothing is built here until the app's design
brief is approved. The briefs live in
`openostler/ostler/references/design/2026-10/brief/`.

Licence: AGPL-3.0-or-later. Contributions are
accepted under the project CLA.

## What this repo holds

- **Owner in the brief:** `app:security`.
- **Contents:** the alarm, arming and disarming, events and clips, the tracker map, geofences, tow and theft mode, alert channels; widgets: alarm status, arm button (Parked only), last event, tracker mini-map. This app alone is the Ostler Guardian flavour.
- **Design brief:** [85-security-a-main](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/85-security-a-main.md), [85-security-b-events](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/85-security-b-events.md), [85-security-c-tracker](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/85-security-c-tracker.md), [85-security-d-setup-settings](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/85-security-d-setup-settings.md), [85-security-e-widgets](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/85-security-e-widgets.md), [85-security-f-companion-guardian](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/85-security-f-companion-guardian.md), [20-hardware-f-security-mesh-service](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/20-hardware-f-security-mesh-service.md) (index: [99-index](https://github.com/openostler/ostler/blob/main/references/design/2026-10/brief/99-index-a.md)).
- **Spec:** [gps-tracker-alarm](https://github.com/openostler/ostler/blob/main/specs/2026-10-02-gps-tracker-alarm-design.md).
- **Code that moves here later** ([ADR-0046](https://github.com/openostler/ostler/blob/main/decisions/adr-0046-empty-os-every-app-an-add-on.md)): `ui/src/destinations/Security.tsx`. It moves only after this app's designs are approved ([ADR-0045](https://github.com/openostler/ostler/blob/main/decisions/adr-0045-ux-first.md)).
