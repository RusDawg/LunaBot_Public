Version: scaffold v1 (2026-10-25). Thickened shells stay EXAMPLE / Unknown.

# Moon Race HUD — public scaffold (v0)

Chat-first HUD seed for Moon race trackers. No connectors required. Copy `index.html` to start a HUD. See [`ASSETS.md`](ASSETS.md) for official image URLs. Friends pull the file over raw HTTPS (`raw.githubusercontent.com`). A GitHub connector is not required, and an X connector is not used.

This is not a copy of anyone’s live tracker. Dates, marker positions, and counters ship as EXAMPLE or Unknown.

| File | Role |
|---|---|
| `index.html` | Single-file seed at the repo root (remote official images only) |
| `ASSETS.md` | Official public URLs and credits |
| `scaffold_home_390.png` | Phone Home preview at 390px |

## 1. Who this is for
A new Moon race tracker. The seed is the know-how and a blank HUD: mission control, both ways to the Moon, a south-pole map, per-path drill-downs, and an empty claims log. It is not a hand-off of someone else’s files.

## 2. Ask permission before fetching
Ask the owner’s permission before fetching this public repo. Raw HTTPS is enough to read `index.html`. No GitHub connector. No X connector.

## 3. Fork `index.html` and fill Unknowns
Copy `index.html` to start the HUD. Fill hero, architecture, and media slots from [`ASSETS.md`](ASSETS.md) or newer official URLs. Replace EXAMPLE timeline rows, map glue points, and drill-down shells, and set as-of dates. Leave the claims log empty until a row has a source.

Keep the demo CONOPS band separate from the crew transport / land / return band, and keep the named refuel steps. The demo N-of-M counter is an EXAMPLE. Do not paste a live tanker count.

## 4. Deliver in chat, then open with Chrome
Send the HTML and a phone Home PNG in chat. The owner downloads them and opens the HTML with Chrome. Confirm tabs, hero links, and map pinch or ctrl+scroll before calling the build done.

`scaffold_home_390.png` is the seed’s Home at 390px. A filled tracker gets its own screenshot at delivery.

## What the seed includes
Shells only. Replace them from sources.

- Mission control, race dial, and a “two ways to the Moon” preview
- South-pole map with EXAMPLE past-landing and next-target markers, a legend, and a site-card stub
- Architecture drill-downs for Starship, Blue Origin, SLS, New Glenn, and China (Steps · What’s next · Pieces to finish · Compare stub)
- Timeline drift chrome (○ → ●) and an EXAMPLE slip pill
- Separate demo and crew CONOPS bands, with named refuel steps and an EXAMPLE N-of-M
- How-it-works and full-details expanders
- Official media strip (remote images only)
- Claims log tab, empty until you fill it after import

## Open the HUD
1. Download the `.html` from chat (or from the raw GitHub URL).
2. **Open with Chrome.**
3. Confirm the tabs, the hero links, and map pinch / ctrl+scroll.

Drive’s in-browser preview breaks the map and the tabs. That only matters if a copy is stored in Drive later. Download the file and open it in Chrome either way.

## Drive (optional, later)
Drive is not the starting path. Use it only when the owner wants a folder and points at one they created. Do not copy another owner’s tracker Drive tree (internal testing — keep each owner’s Drive folder separate). Official public image URLs only — see `ASSETS.md`.

## Privacy
No owner Drive IDs, family/Gmail/home addresses, portfolio stakes, teammate bot names (this note is mainly for our internal template-import testing), or private paths in the scaffold.
