# WellGate Privacy Policy

**Last updated:** July 2026  
**Contact:** wellgate.support@lumeniad.com

## Overview

WellGate is a browser extension that helps you stay intentional on supported social sites. This policy describes how we handle data in **BlackBox** and **Explorer** modes, and how **Stripe** processes billing-related information.

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

If you **switch from Explorer to BlackBox** (in the extension or via Stripe when changing plan), new Explorer analytics are not sent after the change. Previously ingested anonymous summaries remain subject to the retention period unless you request deletion.

## Data stored locally

- Profile and settings
- Daily usage aggregates
- License token
- Trial dates and onboarding choices

## Third-party services

### Stripe (payments and subscription management)

We use [Stripe](https://stripe.com) for checkout, recurring billing, and the **Stripe Customer Portal** (manage subscription, switch between Explorer and BlackBox, update card, cancel).

Depending on your actions, Stripe may process:

- Name, email, and payment method details (we do not store full card numbers on our servers)
- Subscription plan, invoices, and billing history
- **Cancellation reasons** if you cancel through the Customer Portal (collected by Stripe according to your portal settings)

Stripe’s use of this data is governed by the [Stripe Privacy Policy](https://stripe.com/privacy). When you use the Customer Portal, you interact directly with Stripe-hosted pages for payment and subscription changes.

### AWS (Lambda, DynamoDB)

Our API stores license status, beta redemption metadata, and (for Explorer only) anonymous analytics ingest. We store Stripe customer and subscription identifiers linked to your license where needed to validate access — not your full payment details.

## Your rights

- Request **deletion of Explorer analytics** tied to your `installId` by emailing wellgate.support@lumeniad.com.
- **Cancel or change plan** via the Stripe Customer Portal (see Terms of Service). Cancellation takes effect at the **end of the current billing period** unless Stripe shows a different date at confirm time.
- Switch privacy mode in WellGate settings; paid plan and billing are managed in Stripe and must stay consistent with your subscription.

## Children

WellGate is not directed at children under 16.
