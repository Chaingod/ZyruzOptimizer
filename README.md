<p align="center">
  <img src="assets/icon.png" width="80" alt="Zyruz Booster">
</p>

**<h1 align="center">[Zyruz Booster](https://opti-zyruz.vercel.app/)</h1>**

<p align="center">PC optimizer built for competitive gaming. No fluff, no bloat — just results.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.9.4-blueviolet?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows" alt="Platform">
  <a href="https://discord.gg/MxU4TNrzSt"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>

---

Most "optimizer" tools clear your temp folder and slap a before/after graph on it. Zyruz actually goes deeper — kernel scheduling, registry overhead, USB latency, driver stack, network tuning. The stuff that matters when you're playing at a competitive level.


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


## Disclaimer

Zyruz Booster modifies registry entries, Windows services, and low-level system settings. A restore point is created before any changes are made, but you should back up your system regardless. Use at your own risk — we're not responsible for issues caused by misuse or hardware/software incompatibilities.

---

<p align="center">Made by the Zyruz Team</p>
