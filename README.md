# The System

A Solo Leveling-style daily quest tracker. Installable web app (PWA), data in Supabase with row-level security, so only the signed-in owner can read or write their rows.

- `index.html`: the whole app
- `config.js`: Supabase project URL + publishable key (safe to be public; RLS guards the data)
- `sw.js`: offline shell
