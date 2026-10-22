# DayCasion Legacy Executor viewer

Static page served by GitHub Pages at https://legacy.daycasion.com.

It holds no secrets and no data. An executor opens it from the private link in their DayCasion email
(`https://legacy.daycasion.com#t=<token>`); the token stays in the address fragment (never sent to this host)
and every request is checked by the Supabase `legacy-access` function against the owner's recorded permissions.

Files: `index.html` (the viewer), `CNAME` (custom domain), `.nojekyll` (serve files as-is), `robots.txt` (no indexing).
