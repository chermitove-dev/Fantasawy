# Fantasawy — Flutter MVP

A cross-platform Fantasy Premier League companion app prototype.

## Included in this first build
- Home dashboard with gameweek and season overview
- Live Points leaderboard with demo live-event feed
- Premier League fixtures and match details
- Squad pitch view with captain / vice-captain markers
- Player points breakdown
- Settings screen with language/theme controls (UI prototype)

## Run locally
1. Install Flutter (stable channel) and Android Studio or Xcode.
2. From this directory run:
   ```bash
   flutter pub get
   flutter run
   ```

## Important data note
This build uses clearly labelled local demo data. It does not connect to the official Fantasy Premier League service and does not claim real-time accuracy.
Before production, integrate an authorized/licensed data provider, verify its terms, and implement a backend that securely handles synchronization, scoring, caching, and notifications.

## Suggested next milestones
1. Add a NestJS backend and PostgreSQL schema.
2. Implement a replaceable authorized FPL data-provider adapter.
3. Add team lookup and private-league membership.
4. Implement server-side scoring reconciliation and WebSocket updates.
5. Add Firebase push notifications and production tests.
