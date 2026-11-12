MIND GAMES — SUPABASE EDITION

Your Supabase Project URL and publishable key are already filled in config.js.

FILES:
- index.html: home page
- host.html: create and control quiz
- player.html: join and answer
- config.js: Supabase connection (already configured)
- style.css: design
- schema.sql: database setup

SETUP:
1. In Supabase, open SQL Editor > New query.
2. Open schema.sql, copy all its contents, paste into SQL Editor, and tap Run.
3. Upload index.html, host.html, player.html, config.js, and style.css to the ROOT of your GitHub Pages repository (same folder as index.html).
4. Open your GitHub Pages website URL.

HOW TO PLAY:
- Host opens host.html, adds questions and creates a game PIN.
- Players open player.html, enter their nickname and PIN.
- Host starts the quiz and advances questions.
- Correct answers earn 100 points; leaderboard updates automatically.

SECURITY NOTE:
- The browser uses only the Supabase publishable key, not a secret/service_role key.
- This starter setup has public anonymous database policies for a small private/classroom demo. Anyone who can access the website may be able to read or modify game data. Do not store private information. Tighten the database policies before using it publicly.
