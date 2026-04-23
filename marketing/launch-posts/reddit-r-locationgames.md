# r/locationgames — Kulay launch post

**Subreddit:** r/locationgames (small but exactly on-target — Ingress, PoGo,
Wizards Unite, Geocaching, Turf, Zombies Run audience)
**Flair:** New Game / Discussion (check current rules)
**Best post window:** weekend mornings — this sub is small enough that there's
no strong daily peak; aim for when the OP can be present
**Author voice:** peer, not pitchman — these people know the genre cold
**CTA:** waitlist signup at kulay.co

---

## Title (pick one)

- A: New iOS location game in dev — claim territory by closing walking loops (think flood-fill, not gym battles)
- B: Kulay: closing a walking loop floods the enclosed area with your colour. Looking for genre veterans to break it.
- C: Building a location game where the *path shape* is the play, not the points-of-interest

> **Recommended:** B — concrete mechanic up front, signals you respect the
> sub's expertise.

---

## Body

Hey r/locationgames —

Solo iOS dev, long-time PoGo / Ingress lurker, building a thing called
**Kulay** and posting here first because if anyone's going to find the
holes in the design it's this sub.

**The premise:**

Your walk is the controller. Open the app, start a session, and your
path draws on the map in your colour. The mechanic is simple:

- Walk → trail
- Close the loop → the enclosed area floods with your colour
- Other players' colours show on the same map; loops can overlap and
  reclaim each other

**What this is *not*:**

- Not Ingress. No portals, no factions, no XM. The map data is just OSM.
- Not Pokémon GO. No spawns, no battles, no PvE encounters.
- Not Turf / Munzee. No POI checkpoints. The grid is implicit (it's
  geometry of your path), not pre-placed.
- Not Strava with paint. No pace, no segments, no fitness framing.

**Genre veterans — here's what I want your eyes on:**

1. **The cheat surface.** Spoofers ruined every game in this genre.
   Plan: server-side path validation (stride cadence, location/altitude
   delta sanity, no-teleport rules) plus per-region rate limits. Will
   never be perfect; aim is "annoying enough to not be worth it for
   coloured pixels." Better ideas welcome.
2. **The endgame.** What stops a city from being painted within a
   month? Current thinking: territory has a half-life — colour fades
   if no one re-walks it. Walks aren't permanent claims, they're a
   pulse.
3. **Sparse-area parity.** A rural player and a Manhattan player
   should both have a viable game. Currently leaning on per-cell
   normalisation (your "score" is your % of cells in your reachable
   radius, not absolute area). Open question.
4. **Multiplayer pressure.** Should overlap *replace* the prior
   colour, *blend* with it, or *layer* it (last-walked-wins, but the
   history is visible)? I'm leaning layer. Curious what you'd want.

iOS first (TestFlight, then App Store). Android is a maybe for v2 once
the loop is proven. Free at launch, no ads, eventual cosmetic unlocks.

Waitlist is at **https://kulay.co** — TestFlight invites go out in waves.

Tell me what's broken. I'd much rather hear it now.

— Dean

---

## Comment-monitoring notes

- **Treat this sub as a design panel.** They will ask hard questions
  about spoofing, cell normalisation, fairness. Engage substantively.
- **If asked "why not Android first":** "Solo, tight scope, iOS is what
  I can ship to a polish bar I'd accept. Android once the loop is
  validated."
- **If a comparison comes up to a defunct game** (e.g. Wizards Unite,
  the old "Turf" Swedish game), acknowledge it directly — these people
  remember everything.
- **Don't over-promise on anti-spoof.** The community has been burned
  by every dev who claimed "we've solved it." Be honest: it's a
  cost/annoyance game, not a cryptographic one.
