# WellGate Privacy Policy

**Last updated:** July 2026  
**Contact:** wellgate.support@lumeniad.com

## Overview

WellGate is a browser extension that helps you stay intentional on supported social sites. This policy describes how we handle data in **BlackBox** and **Explorer** modes.

## BlackBox mode

- All stats and settings stay **on your device** only.
- We do **not** receive behavioral analytics from BlackBox users.
- License validation sends only your license token to our API.

## Explorer mode

With your explicit consent at onboarding, Explorer sends **anonymous session summaries** to improve WellGate:

- Extension UI interactions (intention choices, shield actions, drift nudge responses)
- Coarse timing (session duration, idle bands)
- Scroll speed **bands** (low / medium / high — not raw streams)
- Supported platform name (e.g. `instagram`) — **not** URLs, posts, messages, or identities

We do **not** collect page content, usernames, search queries, or cross-site browsing outside supported platforms.

Explorer payloads use a rotating anonymous `installId`. Data is retained up to **90 days**, then deleted via TTL.

## Data stored locally

- Profile and settings
- Daily usage aggregates
- License token
- Trial dates and onboarding choices

## Third-party services

- **Stripe** — payment processing (subject to [Stripe Privacy Policy](https://stripe.com/privacy))
- **AWS** (Lambda, DynamoDB) — license validation, beta codes, anonymous Explorer ingest

## Your rights

You may request deletion of Explorer analytics tied to your `installId` by emailing wellgate.support@lumeniad.com. You can switch to BlackBox in settings at any time (billing may differ).

## Children

WellGate is not directed at children under 16.
