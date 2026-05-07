<p align="center">
  <img src="assets/icon.png" width="80" alt="Zyruz Booster">
</p>

<h1 align="center">Zyruz Booster</h1>

<p align="center">PC optimizer built for competitive gaming. No fluff, no bloat — just results.</p>

---

Most "optimizer" tools clear your temp folder and slap a before/after graph on it. Zyruz actually goes deeper — kernel scheduling, registry overhead, USB latency, driver stack, network tuning. The stuff that matters when you're playing at a competitive level.

Built on [Tauri](https://tauri.app/) (Rust + web frontend), runs as a standalone `.exe`, no installer needed.

---

## What it does

**Performance**
- Unpark CPU cores to eliminate micro-stutters under load
- Enable Hardware Accelerated GPU Scheduling (HAGS)
- Lock the Windows kernel in RAM — no disk paging under pressure
- Unlock power states that OEMs artificially cap

**Input**
- Raw 1:1 mouse input — no acceleration, no smoothing, no filtering
- Disable USB selective suspend (kills latency spikes mid-game)
- HID stack tuning for sub-millisecond response consistency
- Force true exclusive fullscreen for games that fake it

**Network**
- Disable Nagle's Algorithm for immediate packet dispatch
- Auto-detect and lock in your fastest DNS servers
- TCP flow stabilization to flatten ping variance
- Per-ISP network profile support

**Cleanup**
- Strip Windows telemetry and background services that eat CPU
- Smart RAM management — frees memory without killing app state
- Debloat without breaking system functionality

---

## Free vs PRO

| | Free | PRO |
|---|:---:|:---:|
| Core FPS optimizations | ✅ | ✅ |
| RAM & memory cleaner | ✅ | ✅ |
| Windows debloater | ✅ | ✅ |
| Advanced input lag suite | — | ✅ |
| Premium network optimizer | — | ✅ |
| GPU driver deep-clean | — | ✅ |
| Display latency tweaks | — | ✅ |
| Audio buffer optimization | — | ✅ |

---

## Getting started

Download the latest `.exe` from [Releases](https://github.com/Chaingod/zyruzoptimizer/releases). Run it as Administrator — it needs elevated rights to touch the system settings it actually changes.

A restore point is created automatically before any optimizations are applied. You can also trigger one manually from the dashboard.

Questions, issues, or looking to go PRO — [join the Discord](https://discord.gg/MxU4TNrzSt).

---

## Changelog

**v1.9.4**
- Fixed dashboard layout breakage (overlapping/misaligned UI elements)
- Fixed CEO/Premium accounts being shown as Free Plan due to case-sensitive role check
- Added HPET, MTU, Extreme Debloat, and CPU Unpark to the script whitelist
- Fixed clickable buttons in the draggable titlebar region
- Restored sidebar/content layout stability
- Fixed search and stats display in the admin panel
- RAM cleaner manual clear improvements

**v1.9.3**
- Admin panel expanded with live user search and stats summary
- Fixed long decimal display in before/after optimization stats
- Fixed activity log clearing on each run
- App now stays in tray on close/minimize
- RAM cleaner backend improvements

---

## Disclaimer

Zyruz Booster modifies registry entries, Windows services, and low-level system settings. A restore point is created before any changes are made, but you should back up your system regardless. Use at your own risk — we're not responsible for issues caused by misuse or hardware/software incompatibilities.

---

<p align="center">Made by the Zyruz Team</p>
