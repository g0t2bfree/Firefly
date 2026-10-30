# GitHub game resource opportunities — Firefly — separate repository

_Recorded 2026-10-30. Documentation only; no packages installed or tested against the game._

## Existing project boundary
This is a separate, minimally documented repo from firefly-catcher. Do not assume they share the same code or overwrite either.

## Potential open-source components
| Repository | Top-level license indicator | Potential application |
|---|---|---|
| [ctkrug/murmur](https://github.com/ctkrug/murmur) | MIT | Optional gentle swarm motion if this turns out to be a browser firefly game. |
| [goldfire/howler.js](https://github.com/goldfire/howler.js) | MIT | Optional soft effects and capture cues for HTML5. |
| [pixijs/pixijs](https://github.com/pixijs/pixijs) | MIT | Optional glow and particles for browser graphics. |

## First practical task
Establish whether this repository is active before moving features from firefly-catcher; keep both independent.

Before importing code, verify current upstream licenses, dependencies, **separately licensed assets**, engine version, and the ability to build in isolation. This file does not authorize destructive changes or imply compatibility. Central catalog: [Figgy](https://github.com/g0t2bfree/forge-ai-local/blob/main/tools/game_resources.json).
