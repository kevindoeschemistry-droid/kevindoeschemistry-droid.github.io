# Stick Arena — Single Player & Online

> Also in this repo: **[Spellstorm](spellstorm.html)** — an original turn-based
> wizard-artillery game (destructible terrain, 4 spellbooks, bots, hotseat
> multiplayer). Play it at `spellstorm.html` on the same site.

A fan remake of XGen Studios' *Stick Arena*: top-down stick-figure deathmatch.
Play solo against AI bots, or host an online match for your friends — no
servers to run, ever.

## Play

Just open `index.html` in any modern browser. Single player works fully
offline; online play only needs a normal internet connection.

## Play with friends

1. Give your friends a copy of this same `index.html` (or host it anywhere,
   e.g. GitHub Pages / itch.io, and share the link).
2. One player clicks **Host Online Game** and reads out the 4-letter room code.
3. Everyone else types the code and clicks **Join**.
4. The host picks map/bots/length and hits **Start Match**. Friends can also
   join mid-match.

Networking is peer-to-peer (WebRTC via PeerJS's free broker) — the host's
browser runs the match, so the host should keep their tab open. Up to 8 humans;
bots fill out the rest of the arena.

## Arsenal

**Classic:** Fists, Baseball Bat, Katana, Sledgehammer, Glock, Shotgun, AK-47.

**Ballistick lab weapons:** Chainsaw (rapid shredding), Tazer (stuns the
victim), Chain Gun (bullet hose), Flamethrower (short-range cone of fire),
Rail Gun (piercing beam that hits everything in a line).

## Other features

- **Chat**: press Enter to talk — messages show in the log and as speech
  bubbles. Bots talk trash on their own.
- **Lava**: the Meltdown, Runoff and Foundry maps have molten hazard tiles.
  Crossing is survivable in a sprint; standing still is not. Knock enemies in.
- **Melee lunge**: every swing hops you forward, like the original.
- Six maps, permanent blood decals, corpse animations, and death by lava
  ("X melted in the lava") in the kill feed.

## Controls

| Input | Action |
|---|---|
| WASD / arrows | Move |
| Mouse | Aim |
| Left click / hold | Attack / fire |
| Tab (hold) | Scoreboard |
| Esc | Pause |

Walk over the blue spinners to grab weapons — Glock, Shotgun, AK-47, Katana,
Sledgehammer, Baseball Bat. Guns have limited ammo; when you run dry you're back
to fists. Highest kill count when the clock hits zero wins.

## Options

- **3 maps** — The Yard, Warehouse, Killbox
- **3 / 5 / 7 bots** with Easy / Medium / Hard AI (aim error, reaction time, aggression)
- **3 / 5 / 10 minute** matches
