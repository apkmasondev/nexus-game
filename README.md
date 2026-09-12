# The Cipher Office — NEXUS

A first-person mystery that runs in the browser. Follow Mara's handover through the NEXUS office,
the Continuity Exchange and The Last Light, take the lift home to your apartment, and return the
next morning to the Oversight Division, where an independent review can stop a release that would
erase everyone's personal boundary.

**Play:** https://apkmason.dev/nexus-game/

Needs a desktop browser with WebGL 2 and a mouse and keyboard. Nothing is installed, no account is
required, and no data leaves the machine: progress lives only in the current visit.

| Input | Action |
| --- | --- |
| W A S D | Walk |
| Mouse | Look — click the room to capture the pointer; drag or use the arrow keys if capture is unavailable |
| E | Inspect whatever the reticle is on |
| J | Field notes and optional hints |
| Escape | Close a document, or open the session menu |

## What is in this repository

The published build only: the page, its compressed 3D assets, the Draco decoder and the audio. The
editable Blender sources, the generators, the puzzle tests and the working notes are kept outside it.

Three.js is redistributed under the MIT licence and Google's Draco decoder under Apache 2.0; both
notices are in [`THIRD-PARTY-NOTICES.md`](THIRD-PARTY-NOTICES.md), with the licence text in
`licenses/`. Everything else — the geometry, textures, writing, puzzle design and audio — belongs to
the project owner and carries no licence: all rights reserved.
