# Seconds From Midnight Calculator

A free, lightweight web tool that converts **seconds** or **milliseconds** from midnight into standard time formats, and vice versa — plus coordinate converters between LLA, ECEF and local NED (WGS84).

## Features

- **Seconds From Midnight tab**: seconds/milliseconds → 24-hour and 12-hour clock time, and back
- Convert **milliseconds from midnight** → time breakdown (hours, minutes, seconds, milliseconds)
- **Reverse conversion**: enter `HH:MM:SS` → get seconds and milliseconds from midnight
- One-click **copy** of 24-hour or 12-hour result to clipboard
- **Coordinate Calculators tab** (WGS84 ellipsoid):
  - **LLA ↔ ECEF**: geodetic latitude/longitude/altitude ↔ Earth-Centered, Earth-Fixed XYZ
  - **ECEF ↔ NED**: XYZ ↔ local North-East-Down meters relative to a reference point
  - **ECEF ↔ NWU**: XYZ ↔ local North-West-Up meters relative to a reference point
- Responsive layout — works on desktop and mobile
- Zero dependencies — pure HTML, CSS, and vanilla JavaScript

## Usage

1. Open `index.html` in any browser
2. Enter a value (e.g. `44049000`) and select **Milliseconds** or **Seconds**
3. The time is displayed instantly — no button needed
4. Use **Copy 24 Hour** or **Copy 12 Hour** to copy the result

### Examples

| Input | Result |
|---|---|
| 44049 seconds | 12:14:09 |
| 44049000 ms | 12:14:09 |
| 86399 seconds | 23:59:59 |
| 0 | 00:00:00 |

## Files

| File | Purpose |
|---|---|
| `index.html` | Main application |
| `favicon.svg` | Browser tab icon (blue clock) |
| `robots.txt` | Search engine crawler instructions |
| `sitemap.xml` | Site map for SEO |
| `readme.md` | This file |

## Why This Exists

Developers frequently encounter timestamps stored as seconds or milliseconds from midnight in logs, PLC systems, embedded devices, SQL databases, industrial automation, telemetry systems, and APIs. This tool makes converting those values quick and accurate.
