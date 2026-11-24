# ProjectGO

Read this in [繁體中文](README.zh-TW.md).

Tsim Sha Tsui open-world 3D demo in Three.js — a playable web prototype built from real Hong Kong 3D map data.

Play it here: https://kttcat.github.io/ProjectGO/

## What it is

An open-world walk around Tsim Sha Tsui, Hong Kong, rendered in the browser. You spawn at the Star Ferry pier plaza and can walk, drive, ride and fly through 460 real buildings across a 750 × 1200 m map. This web demo is a prototype to validate the core interactions; the full game targets Unreal Engine 5.8 → 6.0.

## Features

- Walk / drive / fly, with a car and a motorbike
- Eat, sleep, and hang out — with a personal room, dress-up, NPCs and a pet dog
- Day and night with real sun position
- Three quality tiers for desktop and mobile: Full / Lite / uLite

## Controls

- WASD — move, Shift — run, Space — toggle fly
- F — get in / out of the car
- E — interact (sit, eat, talk)
- J — punch

## Map data

Building geometry comes from the Hong Kong Lands Department's Open3Dhk 3D map data, via the Common Spatial Data Infrastructure (CSDI) / Hong Kong Map Service 2.0 — free for commercial and non-commercial use with attribution to the Government of the Hong Kong Special Administrative Region.

## Tech

- Three.js r160, Blender (map patches), GitHub Pages

## License

MIT covers the code in this repo. It does not cover the 3D assets: the character model is a Mixamo asset (royalty-free use in projects, not for redistribution), and the map geometry is Open3Dhk data (see Map data above). 3D models are served from Cloudflare R2 for the demo and are not stored in this repo.

Based TPE, HKG
