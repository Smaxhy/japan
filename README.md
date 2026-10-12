# Azumabashi Base

A Tokyo trip companion for Dec 15–31, 2026, built around a home base at Azumabashi, Sumida.

**Live site:** https://smaxhy.github.io/japan/

- **Discover:** full-screen photo cards from a library of about 240 hand-picked places (must-sees, culture, nights out, rural day trips, food and local gems), each with what to expect, time needed, cost and best time. Tap for a photo gallery of the actual place, nearby picks and, with keys added, Google ratings, English and Japanese reviews and a Claude-written guide. With a Google key the deck also pulls unlimited top-rated places (4.2★+) around you or any of 70 areas.
- **Explore:** every place in one searchable list with category filters, sorted by distance from the hotel or from you.
- **Plan:** day-by-day planner with morning/afternoon/evening/night slots, two-tap adding from any card, walking times between stops, a day route in Google Maps and ideas from your notebook that fit the day.
- **Ride / Day trips:** bike loops from the hotel and day-trip guides.
- **Cash:** a yen budget for the trip's cash, with a daily allowance and spending log.
- **Live:** links to live weather, train status and events.

It's a single `index.html` with no build step. It installs to the home screen (manifest + offline service worker), and every push to `main` stamps a new version that the app picks up by itself (More → Update automatically). Plans and spending are saved in your browser; use **Live → Your data** to back them up or move them to another phone.
