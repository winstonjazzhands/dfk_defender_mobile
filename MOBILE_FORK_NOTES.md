# dfk_defender_mobile

Forked from DFK Defender v46.9.1.299 resume-limit build.

Mobile fork version: v46.9.1.305m

## What changed

- Created a separate frontend fork identity: `dfk_defender_mobile`.
- Changed the board from 14x6 landscape to 6x14 portrait.
- Moved the void breach/spawn lanes to the top row.
- Changed portal placement rules so the portal starts in the lower half of the board, away from the top void.
- Added portrait-first CSS overrides for a stacked mobile shell and a taller board.
- Updated title/copy/script version query strings for the mobile fork.

## Backend / Supabase

No Supabase function code was changed for this fork pass. No Supabase redeploy is required unless you decide this mobile fork should use separate backend functions, tables, or project config.

## v46.9.1.301m
- Fixed mobile flyout CSS so Treasury/leaderboard panels remain off-screen unless explicitly opened.
- Added iPhone-safe top positioning and sticky close header so Treasury can always be closed on small portrait screens.


## v46.9.1.304m
- Rebuilt the mobile fork CSS/JS activation to be portrait-first instead of landscape-first.
- Removed the portrait rotate-blocking behavior from layout flow.
- Resized the board as a 6x14 portrait grid and reserved bottom space for mobile action controls.
- Moved action controls to a bottom mobile dock and left-edge slide-out menus.
- Tightened intro modal sizing so the Let's play button stays reachable on iPhone XR-sized screens.


## v46.9.1.304m
- Tightened portrait mobile bottom controls and top status/summoner bar.
- Shifted the portrait board slightly left/up so it uses more of the iPhone viewport.
- Reworked FUNC flyout to prioritize wallet controls: Connect, Disconnect, Enable/Disable Run Tracking, Manage Queued Runs, Wallet Heroes, Dailies/Bounties, and Known Relics.


## v46.9.1.305m
- Removed the temporary multicolor mobile ability/art dock.
- Removed the live damage report panel from the mobile build.
- Kept the top summoner/loading status but compacted it.
- Increased usable portrait board space and tightened bottom action controls.
