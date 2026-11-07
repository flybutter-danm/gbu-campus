# GBU Campus

**Instructor-produced teaching sample.** This project was produced by the course instructor as a sample for learning AI-assisted development. It is **not an official 3D tour of Great Bay University**, an official campus map, or a surveyed reconstruction. The night story is fictional.

- [Game source code](https://github.com/greenquark/gbu-campus)
- [Play the game](https://greenquark.github.io/world/)

Try **Take the guided visit** and **Explore on foot** by day; switch to **Haunted night** for **Begin the night** and **Watch demo**.

The 2026-10-05 crawling-limb revision added: articulated finger grips, uneven limb pulls, grounded contact, wet tissue, drag marks and staggered reattachment. [Play Haunted night](https://greenquark.github.io/world/night/) or [open the Day tour](https://greenquark.github.io/world/). Refresh an existing tab once. References, motion review and deployment checks: [crawling-limbs-evidence.md](artifacts/crawling-limbs-evidence.md). Earlier character provenance remains in [realistic-students-evidence.md](artifacts/realistic-students-evidence.md), and historical Railway publication evidence in [railway-model-evidence.md](artifacts/railway-model-evidence.md). These are historical QA records, not verification of the current Pages deployment.

One campus website with two modes: on GitHub Pages, **Day tour** opens at `/world/` and **Haunted night** at `/world/night/`. Local development uses `/` and `/night/` respectively. Use the shared header to switch in the same tab. Night pause and ending screens also offer **Return to day tour**. Switching modes ends the current visit or run and stops its audio.

The rebuilt campus follows the physical model: towers at one end, the crescent and garden in the middle, and sports buildings and dormitories at the other. Day tour offers six landmark stops and a guided campus walk. Haunted night adds four location-specific challenges: restore the water reflection, listen in the west teaching block, complete a timed blue-track lap, and replay the dormitory melody. It retains GBU-shirt zombie students, blood loss, kicks, slowly reassembling limbs and touch controls; the kick now uses a photographic running shoe and trousers. Select **Watch demo** from the night title screen.

Night audio shuts down completely on victory, defeat, quit or exit. Pause, mute and leaving the game window suspend its audio engine, including during demos. Continue or Retry restores sound only for active gameplay. See `artifacts/audio-shutdown-evidence.md` for the focused checks and rollout status. Refresh an already-open game tab after an update to load the latest version.
