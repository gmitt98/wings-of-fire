# Engineering Scaffold — Project Rules

This project follows the Engineering Scaffold standard.

## Compliance Level

1

<!-- Detected: kid-built game, single HTML, low stakes, no external deps. Level 1. -->

## Project Overview

**Wings of Fire — Dragon Battle** — a turn-based dragon combat game based on the
Wings of Fire book series by Tui T. Sutherland.

Players pick one of seven dragon tribes (SkyWing, NightWing, SeaWing, MudWing,
SandWing, IceWing, RainWing), each with unique stats and a special ability.
Then they battle a randomly chosen enemy dragon turn by turn.

## Visual Standard

3D dragons built from Three.js primitive geometry (boxes, spheres, cylinders,
cones, ShapeGeometry for wings). No external sprite files. Procedural only.
Reference: granger-quadruplets-game for the quality bar — chunky, expressive,
animated, self-contained.

## Tech

- Single `index.html`
- Three.js r128 from CDN (no build step)
- Open the file in a browser to play

## Rules (Always On — from Engineering Scaffold)

R1 do not resolve ambiguity silently · R2 spec is authority ·
R3 one thing per unit (~60 line functions) · R4 validate at boundaries ·
R5 errors are part of the contract · R6 make state visible ·
R7 code communicates to humans · R8 do not patch forward from a wrong model
