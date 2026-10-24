---
layout: default
title: Privacy Policy
permalink: /privacy-policy/
---

# Puffin' Privacy Policy

_Last updated: 24 October 2026_

Puffin' is a group fitness app. This policy explains exactly what it collects, why,
where it goes, and how to get rid of it.

## What we collect

**Your account.** When you sign in with Apple we receive an anonymous user
identifier, and — only if you choose to share it — your name and email address.
Apple's Hide My Email is fully supported. We store the identifier, plus the display
name and handle you pick during setup.

**Your workouts and activity, from Apple Health.** With your permission, Puffin'
reads workouts, walking/running/cycling/swimming distance, active energy, step
count and exercise time from Apple Health. For each workout we upload the activity
type, start and end time, duration, distance, active energy, and the name of the
app or device that recorded it. We also upload daily step and active-energy totals.

**What you post.** Group names, challenge titles, comments and emoji reactions.

**Reports and blocks.** If you report content we keep a copy of what you reported,
so we can act on it after the original is deleted.

**Anonymous usage counts.** Puffin' uses TelemetryDeck to count a few things people
do in the app, such as starting or joining a challenge, sharing or opening an
invite, or reacting to a workout. Each count carries only coarse details (for
example, whether it was somebody's first challenge), plus the app version, iOS
version, device model and language. A challenge is identified only by a one-way
hash. TelemetryDeck never receives your account, name, email, workouts, or anything
you write, and it sees you only as an anonymous hashed identifier that can't be
traced back to you.

## What we never collect

- **Your route.** GPS is used while you are recording a workout, to draw the map
  and measure distance. The route is written to Apple Health on your iPhone and is
  **never uploaded to our servers**. Nobody else can see where you ran.
- **Any health data beyond the list above.** No heart rate, no sleep, no weight
  history, no clinical records. Body mass is read on-device only, to estimate
  calories for a workout you record in the app, and is never transmitted.
- **Tracking data.** Puffin' contains no advertising SDKs and no third-party
  trackers. The anonymous usage counts above are only used to see which parts of
  the app work, never for advertising, and are never combined with data from
  other companies. We do not use the Advertising Identifier, and we never ask you
  to allow tracking, because there is none.

## Who can see your data

Only people who share a group with you, and only the workout summary — activity,
time, duration, distance, energy. Nobody outside your groups sees anything.
Blocking someone makes you mutually invisible, immediately and in both directions.

## Where it is stored

On Supabase (PostgreSQL), the app's hosting provider, which processes this data
solely on our instructions. Access is enforced at the database level by row-level
security, so the rule above is applied by the database itself rather than by the
app asking nicely. Data is encrypted in transit (TLS) and at rest.

The anonymous usage counts go to TelemetryDeck, which processes them only on our
behalf.

We do **not** store Health data in iCloud, and we do **not** sell, rent or share
your data with anyone, ever. We do not use Health data for advertising, marketing,
or any form of use-based data mining, as required by Apple's HealthKit terms.

## Deleting your data

Settings → Delete account removes your profile, workouts, daily totals, reactions
and comments permanently, and revokes Puffin's Sign in with Apple token. Deletion
is immediate and cannot be undone. Your Apple Health data is untouched — Health
remains the record of everything you have done, with or without this app.

You can also revoke Puffin's access to Apple Health at any time in the Health app
under Sharing → Apps, or turn off location in iOS Settings → Privacy & Security.

## Children

Puffin' is not directed at children under 13, and we do not knowingly collect data
from them.

## Changes

Material changes will be posted here with a new date at the top, and surfaced in
the app before they take effect.

## Contact

Questions, data requests, or anything else: **Luke@blueskylabs.io**.
