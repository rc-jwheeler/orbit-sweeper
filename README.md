# Orbit Sweeper

A relaxing, one-thumb space-junk cleaner. Fly a little neon ship through the junkyard of old orbits, break up dead satellites, spent boosters, UFO wrecks, telescopes and station chunks, and pull the scrap home to upgrade your ship.

**Play:** https://rc-jwheeler.github.io/orbit-sweeper/

## How to play

- **Drag anywhere** to fly. The ship follows your thumb's movement, so your thumb never has to cover it.
- **While your thumb is down** the ship fires automatically. Ammo is unlimited.
- **Lift your thumb** and the **tractor beam** switches on, pulling nearby scrap ✦ toward you.
- **Satellite trains:** a soft chime and a glowing pink dotted line warn you a couple of seconds before a train of little satellites crosses. Slide out of the line.
- **Space life:** the glowing jellyfish-like drifters are friendly and **can't be hurt** — your shots pass right through them. Hover near one with your beam on and it leaves you a gift. The wobbly green munchers eat loose scrap — shoot them to get it back.
- **Shields** soak up bumps and recharge on their own. If they run out you don't lose: your carried scrap scatters and you can scoop it back up while the shields reboot.
- Each **sector lasts 3 minutes**. From Sector 3 on, a huge **derelict hulk** drifts in near the end — break it for a big scrap haul.
- The view is zoomed out so you can see more of the junkyard.

## Hangar

Spend banked scrap on shields, recharge, fire rate, laser power, tractor beam, thrusters and:

- **Weapon pattern** — 10 patterns to unlock in order: Single, Twin, Trident, Wide fan, Side cannons, Fore & aft, Wave, Spiral sweep, Homing darts, Ring burst. Pick any unlocked pattern from the chips under the upgrades.
- **Orbital drone** — a little drone circles your ship with its own tractor beam. Level 2 gives it a shield that blocks a hit every 9 seconds; level 3 adds a second drone.
- **Mode** — Normal, or **Zen** (no trains, no munchers, no damage; ×0.7 scrap).

## Jump to a new orbit (prestige)

Once you reach **Sector 9** or max every upgrade, the hangar offers **Jump to a new orbit**. You trade all upgrades and scrap for one **permanent reward** plus a lasting **+15% scrap bonus** per jump, and start again at Sector 1. Rewards:

| Reward | What it does |
|---|---|
| 🛸 Bigger ship | Larger hull, +40 shield, wider scoop |
| 💎 New gem | Broken junk sometimes drops sky-gems worth 8 |
| ⭐ Star junk | Golden junk appears, dropping gold scrap worth 5 |
| ✈️ Extra ship | A wingman flies beside you and fires too |
| 🐱 Pet companion | Comet the space cat zooms around fetching scrap |
| 🔆 New shooting pattern | Prism lance — a piercing triple beam (pattern 11) |
| 🛩️ Ship designs | Manta and Saucer hulls |
| 🎨 Ship colors | Rose, Lime, Gold and Violet paint |

Progress (including v1 saves) is kept on your device.

- **Pause** with the ❚❚ button (the game also pauses if you switch apps). ♪ toggles the calm ambient soundtrack.

On desktop, click and drag with the mouse. Esc or P pauses.

## Add to your home screen

- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** ⋮ menu → Add to Home screen / Install app.

## Tech

A single `index.html` with an HTML5 canvas and Web Audio, no build step and no dependencies. Everything is drawn procedurally.
