# OrbitQTH

One HTML file that tracks every amateur radio satellite. No server, no
account, no install: download index.html, open it, work the birds.

![OrbitQTH](screenshot.png)

**Live:** https://hamsat.aganet.gr/

## What it does

- Live world map of all amateur satellites, with day/night terminator and
  coverage footprints
- Pass predictions for your QTH: AOS, LOS, max elevation and duration
- Azimuth, elevation, range and live Doppler with the exact RX frequency
- Uplink, downlink, CTCSS tones and beacons for the workable satellites
- Polar sky view of each pass and a six-hour timeline across all birds
- Works offline: "fetch TLEs" pulls fresh elements over the internet,
  "load TLE" reads a file you downloaded yourself, and "offline copy"
  saves a field-ready page with current elements baked in

## Keeping elements fresh

Positions are computed from orbital element sets (TLEs) that age. The map
shows their age in its bottom-right corner; a set a few days old still points
an antenna fine, weeks old does not.

- On the live site, elements refresh automatically.
- On a downloaded copy, press **fetch TLEs** to pull current elements from
  CelesTrak (needs internet once).
- With no internet at all: download the amateur set yourself from
  [CelesTrak](https://celestrak.org/NORAD/elements/gp.php?GROUP=amateur&FORMAT=tle)
  or [AMSAT](https://www.amsat.org/tle/current/nasabare.txt) on any machine,
  carry the file over, and press **load TLE**. The page remembers it.

## Quick start

1. Open the live site, or download index.html and open it in any browser.
2. Set your QTH: locator, coordinates, or just click the map.
3. Pick a satellite. The list is sorted by next pass.

MIT license. George Anestopoulos, SV1DOD / HB9ISH.
