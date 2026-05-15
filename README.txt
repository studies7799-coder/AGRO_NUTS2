═══════════════════════════════════════════════════════════
  AGRO NUTS 2026 — v2 Full System (with Login + Database)
═══════════════════════════════════════════════════════════

DEFAULT LOGINS
──────────────
  Admin:   admin   / admin123    (full access)
  Viewer:  viewer  / viewer123   (read-only)

  ⚠️ Change passwords after first login in Users tab!

RUN LOCALLY
───────────
  1. Install Python: https://www.python.org
  2. pip install flask openpyxl
  3. python app.py
  4. Open: http://127.0.0.1:5000

FEATURES
────────
  ✅ Login system (Admin & Viewer roles)
  ✅ Dashboard with live budget & truck summary
  ✅ WH Entry — add deliveries with SOLD OUTSIDE flag
  ✅ All Deliveries — filter by supplier, sold/kept, search
  ✅ Sold Tracker — full breakdown of sold vs kept per supplier
  ✅ Suppliers — add, edit budgets, view individual records
  ✅ User Management — create/remove users (admin only)
  ✅ Export: CSV, Excel (.xlsx), JSON
  ✅ SQLite database — data never lost

ROLE PERMISSIONS
────────────────
  Action                    Admin   Viewer
  View all data              ✅      ✅
  Export CSV/Excel/JSON      ✅      ✅
  Add delivery entries       ✅      ❌
  Mark as Sold Outside       ✅      ❌
  Add/edit suppliers         ✅      ❌
  Edit budgets               ✅      ❌
  Manage users               ✅      ❌

DEPLOY ONLINE FREE (Render.com)
────────────────────────────────
  1. Upload folder to GitHub
  2. Create account at render.com
  3. New Web Service → connect GitHub repo
  4. Build: pip install -r requirements.txt
  5. Start: gunicorn app:app
  6. Get free URL instantly!

DATABASE
────────
  File: agro_nuts_v2.db (SQLite)
  Backup: Use Export → JSON anytime

═══════════════════════════════════════════════════════════
