# TV Tracker

**Live demo:** https://liamgmcleod.github.io/watchlist/

I built this when the show-tracking app I relied on shut down. It's a single HTML file
that I use every day on my laptop and phone.

## What it does
- Searches for shows and pulls episode data from the TVMaze API
- Tracks where I am in each show, including rewatches and shows I've dropped
- Works out UK release times and moves a show forward automatically when a new season airs
- Shows what's coming up, with stats on episodes and hours watched
- Syncs between devices through a private GitHub gist, with export and import as a backup

## How I built it
I built it with Claude. My part was deciding what it should do, testing it against my
real list of 337 shows, and tracking down and fixing edge cases as they came up, such as
mid-season breaks, timezone differences on release dates and conflicts between devices.

## About the demo
The demo is a snapshot of my own list, so feel free to click around. Sync is switched off,
and any changes you make stay in your browser.
