# flux

Temperature waves from 10 world cities. Each city's temperature becomes a unique sine wave — hot cities oscillate fast with wide amplitude, cold cities slow and narrow.

**Visual Style:** Dark — Abyss (ocean cyan on deep navy, thin glowing strokes, gentle motion)

**Data Source:** Open-Meteo current weather API (10 cities from Dubai to Reykjavik)

**How it works:**
- Fetches real-time temperatures from Open-Meteo for 10 cities
- Each city is a sine wave — frequency and amplitude scale with temperature
- Three harmonic layers per wave for organic motion
- Tap anywhere to create a ripple disturbance
- Auto-refreshes every minute

**Live:** https://parthchandak02.github.io/flux/

**Tech:** Native Canvas 2D, single HTML file, zero dependencies.
