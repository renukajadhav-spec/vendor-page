# Vendor page (Day 5)

A single web page that shows my practice vendors from a Supabase table. Overdue vendors (due date before today, balance above 0) are shown in red, and a form adds a new vendor. All data is fake.

**Key used:** only the Supabase **publishable** key. This key is meant to be public. It can do only what the table's Row Level Security rules allow: read vendors and add a vendor. It cannot edit or delete. The secret key is never used and never pushed.

**How to open:** open `index.html` in a browser. Nothing needs to be installed.
