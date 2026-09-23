# BAKELY · Product Operating System (BPOS)

Internal bakery operations app: products, versioned recipes, ingredients and price history, suppliers, packaging, costing (₹ INR), production planning, batch sheets, quality control, photos, reports and full version history.

**Live site:** `https://<your-username>.github.io/bakely-bpos/`

## Publish on GitHub Pages
1. Create a new repository named `bakely-bpos` (Public).
2. **Add file → Upload files** → drag in `index.html`, `README.md` and `.nojekyll` → **Commit changes**.
3. **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → **Save**.
4. After 1–2 minutes the site is live at the address above.

To update later, upload a new `index.html` over the old one.

## First use
Open the site → **Load demo data** → sign in. Demo password for every account: `bakely`

| Email | Role |
|---|---|
| owner@bakely.demo | Owner / Admin |
| production@bakely.demo | Production Manager |
| omar@bakely.demo, lina@bakely.demo | Baker |
| finance@bakely.demo | Finance |
| viewer@bakely.demo | Viewer |

Add your real team and change passwords in **Settings → Users**.

## Where data is stored
GitHub Pages only hosts the app file. All data is saved **in each visitor's own browser** (local storage):
- Nobody else can see your data, even though the site address is public.
- Each computer / browser has its own separate copy — data is **not** shared between staff devices.
- Clearing browser data deletes it. Back up often: **Settings → Data → Download backup**, and use **Restore from backup** to move data between devices.
- Browser storage holds about 5 MB, so keep photos few and small.

## Notes
- Currency: Indian rupees with Indian digit grouping (₹1,00,000); changeable in Settings → Business.
- Sign-in and roles organise a trusted team; they are not strong security.
- No build step, no server, no dependencies — a single self-contained `index.html` (web fonts load from Google Fonts when online).
