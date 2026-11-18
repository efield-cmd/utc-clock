# UTC to Local Time Dial

A lightweight, dedicated web app designed for converting game/event UTC times into a users local time with an interactive ruler dial.

## Features
- **Rule-Style Dial**: Smoothly drag or scroll left and right to dial in UTC hours and minutes.
- **Accurate User-based Time Conversion**:
  - Automatically handles Daylight Saving Time.
  - Displays day offset tags (`SAME DAY`, `PREVIOUS DAY`, `NEXT DAY`).
  - Can auto-detect your timezone or be chosen manually
- **Flexible Controls**:
  - Drag the dial left/right with mouse, touch, or trackpad to desired time.
  - Mouse wheel / trackpad scroll for fine adjustments.
  - Magnetic snapping to every hour (:00) and half-hour (:30) if released within 14 minutes.
  - Top Time Display shows what the UTC time translates to in your chosen time zone.
  - "Type Time" button or click on the dialed time to directly type 24h times (e.g. `16:00`, `9:30`, or `0400`).
  - "Set to Current UTC" button for instant synchronization with current game time.
  - Quick game reset presets (`00:00 UTC`, `04:00 UTC`, `12:00 UTC`, `16:00 UTC`, `20:00 UTC`).