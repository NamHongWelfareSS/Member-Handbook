# NHWSS Committee Handbook 南凤福利协会委员手册

Mobile handbook for the Management Committee. One permanent link, no server, no login, no maintenance beyond editing one Excel file.

## What's in this folder
| File | Purpose | Touch it? |
|---|---|---|
| `index.html` | The webpage (all 4 tabs) | No |
| `xlsx.full.min.js` | Excel-reading library, bundled locally so the site has zero external dependencies | No |
| `data.xlsx` | **All content lives here** — the only file you maintain | Yes |
| `photos/` | Member photos, filenames referenced in data.xlsx | Yes |

## One-time setup (approx. 10 minutes)
1. Create a GitHub account **for the organisation** (e.g. `namhongwelfare`), not a personal account — so the link survives any change of personnel. Use a shared/office email.
2. Create a new **public** repository. Use a neutral name, e.g. `handbook`.
3. Upload everything in this folder (drag-and-drop on the repo page → *Add file → Upload files* → Commit).
4. Repo **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
5. After ~1 minute the permanent link is live: `https://<accountname>.github.io/handbook/`
6. Share that link once with the 25 members (they can *Add to Home Screen* for an app-like icon).

## Routine updates
1. Edit `data.xlsx` on your computer (sheets: `1_Committee`, `2_OfficeBearers`, `3_SubCommittees`, `4_Events`, `Info`). Rules are on the `Instructions` sheet inside the file.
2. On the repo page: *Add file → Upload files* → drop the edited `data.xlsx` (and any new photos into `photos/`) → Commit.
3. Done. The page updates within about a minute; the link never changes. Git automatically keeps every prior version of `data.xlsx` in the commit history, so nothing is ever lost.

## Photos
- Filenames lowercase, no spaces (e.g. `stanley_lim.jpg`), square crop preferred, keep under ~200 KB each.
- Missing or unnamed photo → the page shows the member's initials instead (never broken images).

## Notes
- **Public visibility**: GitHub Pages is public. The page carries a `noindex` tag so search engines are told not to list it, but anyone holding the link can open it. Keep content to name / title / photo / event level only — no NRIC, contact numbers or addresses.
- **Continuity**: because the repo sits under the organisation's own account, the site keeps running unchanged regardless of who administers it. Handover = passing on the account credentials.
