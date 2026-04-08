# #101 Sec to Clock

A minimalist, high-speed "Time Unpacker" that converts total seconds into a readable clock format (H:M:S) and vice versa. Part of the [Fridge Combo](https://afrorakda.github.io/) series.

## 1 Tool / 1 Action
- **Primary Action**: Convert total seconds into formatted time (HH:MM:SS) instantly.
- **Secondary Action**: Reverse convert hours, minutes, and seconds back into total seconds.

## Features
- **Bi-directional Sync**: Enter total seconds to see the clock, or edit the clock to see the total seconds.
- **Smart Validation**: Automatically caps minutes and seconds at 59 for logical time conversion.
- **One-Tap Copy**: Tap the result area to copy the formatted time instantly (with a visual "COPIED!" feedback).
- **Optimized for Mobile**: Features specialized numeric input modes and zero-latency UI.
- **Privacy First**: No login, no tracking, no ads. Browser-only execution.

## Design System
- **Background**: #fff
- **Main Color**: #333
- **Accent Color**: #eee (Input background: #fafafa)
- **Border Radius**: 15px (Mandatory for all elements)
- **UI Mantra**: Tool-like, high-contrast, and friction-free.

## Technical Details
- **Zero-Width Prevention**: Handles browser-specific auto-fill issues and Bfcache (back-button) consistency.
- **iOS Standard**: Includes `-webkit-appearance: none` and fixed opacity rules to prevent Safari text-fade issues.

## License
No login / No tracking / No ads / Browser only
Privacy Policy / afrorakda © 2026
