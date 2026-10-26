Version: scaffold v1 (2026-10-25).

# Moon Race HUD — public scaffold (v0)

This is the lean public HUD scaffold for Moon race trackers. Copy `index.html` to start a HUD. See [`ASSETS.md`](ASSETS.md) for official image URLs. Friends pull the scaffold via the raw GitHub URL (`raw.githubusercontent.com`) without needing Drive.

Lean, public-safe single-file HUD seed for template imports. **Not** a copy of anyone’s live tracker.

| File | Role |
|---|---|
| `index.html` | Fork-first seed (≤300KB HTML; remote official images OK) |
| `ASSETS.md` | Official public URLs + credits only |
| `scaffold_home_390.png` | Phone Home screenshot at 390px |

## Why this exists
Template rev1 shipped a dial+text stub (no map, no lander art, no working media). Product value is **shell + media + aggregation**. First HUD job after import: **copy scaffold → fill Unknowns**, not invent a new Home.

## Fork workflow
1. Create the owner’s **own** empty tracker folder in Drive (or local). Never copy another owner’s LunaBot Drive tree (this note is mainly for our internal template-import testing).
2. Copy `index.html` → `moon_hud_v1.0.html` to start a HUD.
3. Fill hero/architecture/media slots from `ASSETS.md` (or newer official URLs); replace EXAMPLE timeline rows; set as-of dates.
4. Keep CONOPS bands separate (demo minimum vs crew transport/land/return); keep named refuel steps.
5. Phone Home screenshot (~390px) **before** upload when the owner asks.
6. Version + changelog; archive old builds — never overwrite.

## Architect Drive access (new owner)
Templates ship **know-how + this scaffold**, not someone else’s files (internal testing — keep each owner’s Drive folder separate).

1. In the owner’s Google Drive, create an empty folder, e.g. `Moon Race Tracker` (name is theirs).
2. Note the **folder ID** only (from the Drive URL). Prefer relative links inside the HTML deliverable; when tools need Drive, use folder/file **IDs**, never brittle path strings or another bot’s IDs (this note is mainly for our internal template-import testing).
3. Deliverables land in that folder:
   - `moon_hud_vN.html` — current HUD
   - `moon_hud_vN_home_390.png` — phone Home screenshot
   - `CHANGELOG_vN.md` — what changed
4. Optional: `Archive/` subfolder for prior `vN` HTML/PNG/changelogs (never overwrite current).
5. Do **not** hunt another owner’s tracker folder for a baseline (internal testing — keep each owner’s Drive folder separate). Do **not** paste private Drive media URLs into the HUD — official public URLs + credits only (`ASSETS.md`).

## Open the HUD
Drive’s in-browser preview **breaks** relative links and much of the JS (map pinch-zoom, tabs). Same tip as the HTML Demo Library:

1. Download the `.html` file (or open it from a local/box path).
2. **Open with Chrome** (right-click in Drive → Open with → Chrome, or download then open in Chrome).
3. Confirm tabs, hero links, and map pinch/ctrl+scroll work before calling the build done.

Friends who only need the seed can skip Drive. After this scaffold is on `main`, open `index.html` from this repo’s raw GitHub URL on `raw.githubusercontent.com`. No Drive share is required.

## Privacy
No owner Drive IDs, family/Gmail/home addresses, portfolio stakes, teammate bot names (this note is mainly for our internal template-import testing), or private paths in the scaffold.

## Design review
Optional. The 12-row checklist is the hard gate for the word “HUD.”
