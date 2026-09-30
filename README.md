# Ladder Timer

A simple, browser-based focus timer. It is a single HTML file with no setup required: just open the file.

## How It Works

The timer splits a 60-minute session into 6 work blocks of increasing length, followed by a 5-minute break:

**2 → 4 → 6 → 8 → 15 → 20 minutes (work) → 5 minutes (break)**

Each block is shown as a column that fills from bottom to top as time passes, so both the current block and the overall progress of the session are visible at a glance.

## Usage

- **Start / Pause**: Starts or pauses the timer
- **Skip block**: Skips the current block and moves to the next one
- **Reset**: Restarts the session from the beginning
- **Space bar**: Shortcut for Start / Pause
- Click any column to jump directly to that block

The tab title is updated with the remaining time, so the timer can be followed even when the tab is in the background.

## Technical Notes

- No external dependencies, a single `.html` file
- Can be published statically with GitHub Pages
- Aileron typeface, dark theme
