# Gulag Padel

Tiered-court padel nights: live courts, point slams, seeding, history and league manager tools.

- `index.html` is the whole app (one page). It stores data in Firebase (project `gulag-padel`) and signs refs and the league manager in with Firebase logins.
- `firestore.rules` holds the database security rules. Paste them into Firebase console → Firestore Database → Rules and tap Publish whenever they change.
- The site is published with GitHub Pages from the `main` branch, so every push goes live within a minute or two.

## Who can do what

| | Viewers | Refs | League manager |
|---|---|---|---|
| See seeding, live courts, history | ✓ | ✓ | ✓ |
| Set up and run a night, enter scores, fix earlier rounds | | ✓ | ✓ |
| LM Tools: players, merges, ratings, settings, seasons, refs, edit or delete saved nights | | | ✓ |

Refs are added by email in LM Tools → Refs. They then create an account on the site with that email and confirm it from their inbox.
