# Product Hunt — Upcoming page copy

**Channel:** Product Hunt — *Upcoming page* (not the full launch)
**URL pattern:** producthunt.com/upcoming/kulay (claim slug early)
**CTA:** "Notify me" → adds to Product Hunt's waitlist *and* drives to
kulay.co for a deeper signup
**When to publish:** as soon as the slug is available. Full launch comes
after TestFlight is stable enough to handle a few-thousand-visit spike.

All character limits below are Product Hunt's current Upcoming-page caps as
of the last review — re-verify before publishing.

---

## Product name

```
Kulay
```

(Pronunciation aid for the page footer / FAQ: *koo-lai* — Filipino for
"colour".)

---

## Tagline (≤ 60 chars)

**Primary:**
```
Claim territory by walking. Colour your city.
```
(46 chars)

**Backup options:**
```
A game where your walks paint the map.
```
(38 chars)
```
Walk a loop. Flood the area with your colour.
```
(45 chars)

> **Recommended:** primary. Verbs first ("claim"), benefit second ("colour
> your city"). The backups are softer if PH staff push back on "claim
> territory" sounding aggressive.

---

## Short description (≤ 260 chars)

```
Kulay is an iOS game where your real walks are the controller. Walk
any path — your trail draws on the map. Close the loop and the area
inside floods with your colour. No combat, no leaderboards, no step
counter. Just colour on a shared map.
```
(255 chars)

---

## Long description (the body of the Upcoming page)

```
Kulay (Filipino for "colour") is an iOS game played with your feet.

The loop is four verbs:

  1. Walk — start a session, put your phone away, and just go.
     Your phone tracks your path on a map.
  2. Splat — your trail draws itself on the map in your colour
     as you walk.
  3. Circuit — close the loop. Walk back to where your trail
     started.
  4. Flood — the area inside the loop floods with your colour.
     That patch of the city is yours.

Other players' colours show up on the same shared map. Loops can
overlap, reclaim, and layer. The neighbourhood is the board, and
the board is shared with everyone walking it.

What Kulay deliberately does not have:
  - No step counter, no daily goal, no streaks.
  - No leaderboards, no follower counts, no social feed.
  - No combat, no creatures, no PvE encounters.

iOS first. TestFlight invites are going out in waves to the
waitlist at kulay.co. Free at launch, no ads, eventual cosmetic
unlocks (extra colours, trail styles). No pay-to-win — there's
nothing to win against.

Made by a solo dev who walks too much.
```

---

## Topics / categories (pick 3)

1. **Games** (primary)
2. **iOS**
3. **Health & Fitness** *or* **Maps** — pick whichever PH suggests has
   higher engagement at the time of publishing. Lean Maps if Health &
   Fitness slot is crowded with launch-day competition.

---

## Gallery (Upcoming page allows up to 5 stills + 1 video)

Order the gallery as a story:

1. **Hero still** — phone screen with a single closed coral loop on a
   neutral map, area filled. No UI chrome. (This is the image that
   appears in the Upcoming card preview.)
2. **GIF / short video** — full 4-verb loop in 6 seconds: walk → splat
   → circuit → flood. Loop seamlessly. Same coral as the hero.
3. **Multi-colour map** — a city block with 4–5 overlapping colour
   patches from different players. Shows the multiplayer surface
   without a single word of UI.
4. **Phone in pocket / lock-screen** — a real-life shot of someone
   walking with the phone away, lock-screen showing "Kulay session
   active." This is the "you don't stare at the screen" promise made
   visual.
5. **Tagline card** — "Colour your city" in the Kulay coral on the
   `#FAFAFA` site palette. Clean type-only. Use as gallery closer.

> All assets live in `assets/marketing/` once produced — currently
> wireframes only (real captures pending iOS Simulator runtime).

---

## Maker comment (post as the first comment on the Upcoming page)

```
Hey 👋 — solo dev here. Kulay started as a thing I built for myself
because I walk a lot and got tired of step-counter apps making it
feel like homework.

The mechanic is the whole game: walk a path, close the loop, flood
the area with your colour. The map fills up over time as more people
walk. Nothing to grind, nothing to win, nothing to miss if you skip
a day.

Two things I'd love feedback on while we're still pre-launch:

  1. Battery. Walking games live or die on this. Background
     tracking is opt-in per session, not always-on. Working on
     keeping a 30-min walk under 3% battery.
  2. Sparse-area parity. A rural player and a Manhattan player
     should both have a viable game. Currently using per-cell
     normalisation in your reachable radius. Open to better ideas.

Hit "Notify me" if a game made of walks sounds like a thing you'd
try, and full waitlist (TestFlight invites) is at kulay.co.
```

(Emoji intentionally restrained — one wave only, per PH culture.)

---

## FAQ block (if PH page supports it; otherwise post as second maker comment)

```
Q: When is launch?
A: TestFlight is rolling out to the waitlist now. Full App Store
   launch follows once the build is stable across the wave invites.

Q: Android?
A: iOS only at launch. Android is a maybe for v2 once the loop is
   proven. No timeline.

Q: How much will it cost?
A: Free at launch. No ads. Eventual cosmetic unlocks (more colours,
   trail styles). No pay-to-win.

Q: How does it stop GPS spoofers?
A: Server-side path validation: stride cadence, location/altitude
   delta sanity, no-teleport rules, per-region rate limits. Will
   never be perfect — the goal is "annoying enough to not be worth
   it for coloured pixels."

Q: Do I need an account?
A: No. You can start walking and claiming territory anonymously.
   Account is optional, only needed if you want to keep your colour
   on a new device.

Q: Battery impact?
A: Background tracking is per-session, not always-on. Aiming for
   under 3% battery on a 30-minute walk on a 2-year-old iPhone.
```

---

## Notes for the publisher

- **Claim the slug ASAP** — "kulay" is short, may be contested.
  Reserve it on the Upcoming page even if the assets aren't final.
- **Hero image must work as a 200px square thumbnail.** Test the
  hero still cropped to centre — the closed loop + flood needs to
  read at thumb size or the card gets ignored in the Upcoming feed.
- **Do not enable the full launch from the Upcoming page** until
  TestFlight is sturdy. PH launches drive an unforgiving traffic
  spike on launch day; do not run that test against an unstable
  build.
- **Cross-link the kulay.co waitlist** in both the description and
  the maker comment. Some PH users skim past the description.
