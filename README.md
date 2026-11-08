# THE CLASS LEAGUE — Ultimate Hybrid Demo

A responsive, animated multi-page league frontend with a black, gold and purple esports-inspired design.

## Pages
- `index.html` — command center
- `standings.html` — searchable demo leaderboard
- `schedule.html` — filterable fixtures
- `rules.html` — scoring and fair-play charter
- `roster.html` — searchable player directory
- `hall-of-fame.html` — champions and awards
- `community.html` — local demo posts and likes
- `profile.html` — sample player profile and achievements
- `challenges.html` — demo challenges
- `tournaments.html` — sample tournament bracket
- `notifications.html` — sample alert center
- `admin.html` — simulated admin dashboard (not secure / not real admin controls)

## Run locally
Open `index.html` in a browser. The project uses no build tools and no backend. Google Fonts are optional; a system font fallback is included.

## GitHub Pages deployment
1. Create a GitHub repository.
2. Upload all files and folders while preserving their structure.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for the Pages URL to appear. The homepage is `index.html`.

## Demo data and Firebase later
- Leaderboard, roster and fixtures are sample data in `js/demo-data.js`.
- Community posts and likes use this browser's `localStorage` only. They are not shared between visitors and may be cleared by the browser.
- Demo buttons show preview messages; they do not create real accounts, submit verified scores, send notifications or grant admin permissions.
- The admin page is intentionally only a visual preview. Do not use it for real moderation or player management.
- Before launch, connect Firebase Authentication and Firestore, add Firestore security rules, validate all submissions server-side where needed, and replace demo actions with authenticated database operations.
