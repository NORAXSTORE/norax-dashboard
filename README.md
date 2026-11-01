# NORAX Hub dashboard

Static page only. It contains no data and no keys: on first open it asks for the Supabase
Project URL and Publishable key, which stay in that browser. The database only lets that key
read dashboard views (row-level security), never write.

Source of truth: `dashboard/index.html` in the private `norax-hub` repo (copied here by its workflow).
