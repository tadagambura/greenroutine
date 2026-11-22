# GreenRoutine: Spec

**Small swaps, less waste, visible impact** · #19 of 33 · Wave 2: Recurring keepers · Used: Daily/weekly · Medium · Revenue potential: Low–medium · Home & Household · Source: Perplexity

## One-liner

Track reusable habits (bottle, cup, bags), log food waste, get 'use it up' reminders, work through eco-swaps room by room, and never miss a recycling collection. Monthly impact summary.

## Problem / audience

- **Who it's for:** Eco-conscious households, zero-waste beginners, parents cutting plastic and food waste.
- **The problem it solves:** Good intentions fade without small, visible progress.
- **Example:** A household logs its reusable cups, gets nudged to use leftover veg, and sees its monthly waste fall.

## MVP features (ship with only these)

1. Reusable-item tracker
2. Food-waste log and 'use it up' reminders
3. Eco-swap checklist by room
4. Recycling and collection-day reminders
5. Monthly impact summary

## Not in MVP

- Household sharing
- Challenge packs (e.g. Plastic Free July)
- Impact report cards

## Monetisation

| Model | Detail |
|---|---|
| Free | Tracking and swaps, with ads |
| Premium | £2.99/month: unlimited tracking, sharing, reports, packs |
| Affiliate | Eco products, carefully chosen and labelled |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Collection-day and 'use it up' reminders |
| Tiny win | Log a reuse or swap |
| Progress | Monthly impact |
| Share | Impact cards |
| Next step | Monthly challenge |
| Cadence | Daily/weekly |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Reuse logged: the reusable cup high-fives the stickman
- Food saved: a caped stickman rescues a wilting carrot
- Collection day: the bin rolls itself to the kerb
- Monthly impact: the little planet smiles bigger
- Challenge done: a seed sprouts into a tree

**Line we don't cross:** No eco-guilt animations.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Easy eco swaps; Food waste; Plastic-free challenges
- **Shareable output:** Impact cards

## Risks

Must never feel preachy. Impact numbers must be honest estimates with sources (no greenwashing). Collection days differ by council.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
