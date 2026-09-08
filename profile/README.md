# Viora

Peer-to-peer video calling. Audio and video go straight between devices over
WebRTC — a small relay only helps two people find each other.

| Repo | |
| --- | --- |
| [viora-android](https://github.com/SVUI-Labs/viora-android) | Android app — Kotlin / Compose |
| [viora-web](https://github.com/SVUI-Labs/viora-web) | Browser client — plain ES modules, no build |
| [signaling-server](https://github.com/SVUI-Labs/signaling-server) | The relay — Rust |
| [docs](https://github.com/SVUI-Labs/docs) | Architecture and deployment notes |

## Where it's going

- **Group calls** — 3–5 people over a mesh, no SFU.
- **Managed rooms** — a named room with a link, QR, PIN, and a host waiting room.
- **Same model everywhere** — Android and web share one call protocol.
- **Resilient calls** — data-saver mode, codec pinning, recovery when the network moves.
