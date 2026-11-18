# UTC to Central Time Dial

A lightweight, dedicated desktop web app designed for converting game/event UTC times into local Central Time (Little Rock, Arkansas) with an Apple iOS timer-style interactive ruler dial.

## Features
- **Apple iOS Timer-Style Dial**: Smoothly drag or scroll left and right to dial in UTC hours and minutes.
- **Accurate Central Time (Little Rock) Conversion**:
  - Automatically handles Daylight Saving Time (**CST** `UTC-6` vs **CDT** `UTC-5`).
  - Displays day offset tags (`SAME DAY`, `PREVIOUS DAY`, `NEXT DAY`).
- **Flexible Controls**:
  - Drag the dial left/right with mouse, touch, or trackpad to desired time.
  - Mouse wheel / trackpad scroll for fine adjustments.
  - Magnetic snapping to every hour (:00) and half-hour (:30) if released within 14 minutes.
  - Top Time Display shows what the UTC time translates to in your chosen time zone.
  - "Type Time" button or click on the dialed time to directly type 24h times (e.g. `16:00`, `9:30`, or `0400`).
  - "Set to Current UTC" button for instant synchronization with current game time.
  - Quick game reset presets (`00:00 UTC`, `04:00 UTC`, `12:00 UTC`, `16:00 UTC`, `20:00 UTC`).

## How to Run

### Method 1: Open Directly in Any Browser
Double-click `index.html` or open it in your favorite browser:
```bash
open /Users/elias/.gemini/antigravity/scratch/utc-central-clock/index.html
```

### Method 2: Run via Local Server
```bash
cd /Users/elias/.gemini/antigravity/scratch/utc-central-clock
python3 -m http.server 4321
```
Then visit `http://localhost:4321`.
