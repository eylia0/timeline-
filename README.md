# Road to the Powerhouse

SideKick's plan from the thesis to the Powerhouse presentation (1 Dec 2026) and after: deadlines, a timeline of workstreams, and checklists.

- Live at https://eylia0.github.io/timeline-/ . Hosted with GitHub Pages (Settings > Pages > Deploy from branch `main`, folder `/`).
- Data lives in Supabase (tables `phases` and `tasks`). Only the owner's signed-in account can read or change it (row level security).
- The key in `index.html` is Supabase's publishable key, which is meant to be public. Never put the service role key in this repo.
