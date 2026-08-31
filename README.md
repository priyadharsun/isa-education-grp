# Children's Education Development Programme — Islandwide Map

An interactive map presentation of the **Children's Education Development Programme**
run by the **Ilankai Saivism Association**, Sooran Perumanar Education Board, across Sri Lanka.

**Live site:** https://priyadharsun.github.io/isa-education-grp/

## What it shows

- The real Sri Lankan district map, with every district ISA works in highlighted
- All 48 schools pinned at village level, colour-coded by status:
  - **Green** — programme already started
  - **Orange** — upcoming
  - **Red** — awaiting zonal approval
- A slide per district (Kalutara, Ratnapura, Nuwara Eliya, Mullaitivu, Colombo,
  Batticaloa, Mannar, Galle) with its schools listed and photographs from the classes
- The challenges the programme faces, and planned expansion into Trincomalee, Matale and Jaffna

## Presenting it

Open the site and press **F** for full screen, then move with the **← →** arrow keys,
the on-screen arrows, or the dots along the bottom. Click any district on the national
map to jump straight to it. Click a photograph to enlarge it.

## About the map data

District boundaries come from [geoBoundaries](https://www.geoboundaries.org/) (ADM2, Sri Lanka).
School positions are derived from Sri Lanka's official GN and DS division boundaries, so each
pin marks the school's village or town area rather than the exact building.

## Structure

The whole presentation is a single self-contained `index.html` — no build step, no
dependencies, no server needed. Photographs are embedded in the file, so it works offline
once loaded.
