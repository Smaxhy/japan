# Azumabashi Base

A Tokyo trip companion for Dec 15–31, 2026, built around a home base at Azumabashi, Sumida.

**Live site:** https://smaxhy.github.io/japan/

- **Discover:** full-screen swipe cards. 150+ hand-picked spots (including 45 rural and unusual day trips), then an endless feed of real places: Google Places (ratings, English and Japanese reviews) when a key is added in More → Power-ups, otherwise Wikipedia. Filter by type and by where: anywhere, near me (GPS), near the hotel, Tokyo, countryside or one of 78 named areas. Tap a card for what you'll find there, written by Claude from the reviews when an Anthropic key is added.
- **Eat / Do / Ride / Day trips:** local-favorite food, December events, bike loops from the hotel, and day trips, with photos and one-tap Google Maps directions from the hotel.
- **Calendar:** Dec 15–31 planner with city events marked.
- **Cash:** a yen budget for the trip's cash, with a daily allowance and spending log.
- **Live:** links to live weather, train status and events.

It's a single `index.html` with no build step. It installs to the home screen (manifest + offline service worker), and every push to `main` stamps a new version that the app picks up by itself (More → Update automatically). Plans and spending are saved in your browser; use **Live → Your data** to back them up or move them to another phone.
