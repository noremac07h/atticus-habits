# Habit Tracker

The Habit Tracker page, hosted on GitHub Pages. Data lives in a private
Supabase project behind a login (row-level security: each account sees only
its own rows); the key in the page is Supabase's public "publishable" key,
which grants nothing without signing in. Atticus (the Mac assistant) reads
and ticks habits through the same table.
