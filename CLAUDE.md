# Dorian's Blast Off to 4 — Birthday Party Landing Page

## Project
A single-file HTML birthday party landing page for Dorian's 4th birthday.
File: `dorians-blast-off-to-4.html`

## Event Details
- **Name:** Dorian's Blast Off to 4!
- **Date:** Sunday, May 17th
- **Venue:** Launch Clubhouse, 1st Floor
- **Address:** 1777 Clement Ave, Alameda, CA 94501
- **RSVP Deadline:** Monday, May 11

## Design
- Space/astronaut theme
- Dark color palette (deep navy/black background)
- Accent colors: mustard yellow, cream
- Monospace font for labels (JetBrains Mono)
- Animated stars and floating planets in the background
- Countdown banner showing days until the party

## Features
- Countdown timer to party date
- Mission-style detail cards (date, time, location, navigation, parking)
- Embedded Google Maps iframe (Maps Embed API)
  - Google API Key: AIzaSyBouTUsIhH4ShrL9Uincm7DfuwljhcLOFA
  - Maps Embed API must be enabled in Google Cloud Console
- "Open in Google Maps" link to 1777 Clement Ave, Alameda, CA 94501
- Parking directions:
  1. Drive toward the marina from Schiller St. and Clement Ave.
  2. Turn left
  3. Park in the parking lot, near the Launch community breezeway
- RSVP form (name, guest count, dietary notes)
- Add to Calendar button (generates .ics file)
- Food/snack section ("Fuel up on cake, cosmic snacks...")

## Coding Notes
- Everything is in a single HTML file (no separate CSS or JS files)
- No frameworks or external dependencies except Google Fonts and Google Maps
- CSS variables used for theming (colors, fonts)
- Fully responsive for mobile
