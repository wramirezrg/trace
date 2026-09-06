<p align="center">
  <img src="media/trace-banner.png" alt="TRACE: Industrial Troubleshooting Platform" width="100%">
</p>

# TRACE

**An industrial troubleshooting and diagnostics platform for PLC-connected equipment.**

TRACE gives maintenance technicians, automation engineers, and controls engineers a fast,
direct view into what a PLC-connected machine is doing, in real time and after the fact, without
an expensive proprietary toolchain.

[**Visit www.siganor.com →**](https://www.siganor.com)

![TRACE Monitor: real-time PLC signal monitoring](media/monitor.png)

---

## What TRACE Does

Industrial troubleshooting usually means one of two things: staring at a control panel hoping
to catch a fault as it happens, or digging through vendor-specific tools that are expensive,
locked to a single hardware ecosystem, or too generic to answer field questions quickly.

TRACE is built around a simpler idea: give the people closest to the machine (technicians,
electricians, and engineers) a direct, real-time and historical view of signal behavior, plus the
network and connector context needed to find a problem fast.

## Feature Highlights

- **Real-time monitoring** of PLC signals with multiple synchronized graphs, in real
  engineering units
- **Digital and analog** signal visualization, side by side
- **Conditional recording** that starts and stops automatically on a signal condition
- **Session replay** with time cursors for post-incident analysis
- **Network topology mapping** for industrial Ethernet daisy chains
- **Connector pinout reference library** for common industrial standards
- **CSV export and recording** for reporting and further analysis
- **Configurable simulation mode**: signal patterns, ready-made scenarios, and manual events, no
  PLC required
- Installs and runs as a local desktop application, with no cloud dependency

## Screenshots

### Live Monitoring
![Live Monitoring](media/monitor.png)
Multiple signals, digital and analog, tracked live and side by side, so a fault is visible the
moment it happens instead of being pieced together afterward.

### Replay
![Replay](media/replay.png)
Load a recorded session and step through it with dual time cursors to measure exactly how long
each event took and how signals relate to one another.

### Chain Map
![Chain Map](media/chain-map.png)
A live view of an industrial Ethernet daisy chain, showing reachability and per-node latency to
help narrow down where a communication problem is.

### Pinouts
![Pinouts](media/pinouts.png)
An offline reference for industrial connector standards, covering pin numbering, signal
assignment, and color coding, without leaving the application.

### Simulation Mode
![Simulation Mode](media/simulation.png)
A ready-made scenario running with no PLC connected: a motor's Running signal delayed off
Start_Command, and its Current climbing with a realistic first-order response.

See [`docs/screenshots.md`](docs/screenshots.md) for the full gallery with extended
descriptions.

## Main Modules

| Module | Description | Learn more |
|---|---|---|
| **Live Monitoring** | Real-time graphing of digital and analog PLC signals, with conditional recording | [docs/monitor.md](docs/monitor.md) |
| **Replay** | Historical playback and event analysis of recorded sessions | [docs/replay.md](docs/replay.md) |
| **Chain Map** | Industrial Ethernet topology and reachability diagnostics | [docs/chain-map.md](docs/chain-map.md) |
| **Pinout Library** | Reference for industrial connector standards | [docs/pinouts.md](docs/pinouts.md) |
| **Simulation Mode** | Configurable signal patterns, scenarios, and manual events, no PLC needed | [docs/simulation.md](docs/simulation.md) |

## Why TRACE

- **Built for the field, not the lab.** Fast to open and fast to point at a PLC, with no project
  files or engineering workstation to set up first.
- **One tool, several jobs.** Live monitoring, historical replay, network diagnostics, a
  connector reference, and a simulation environment live in a single application instead of
  several.
- **Works without a live PLC.** Configurable simulation patterns and ready-made scenarios mean
  anyone can practice reading and troubleshooting signals with no real PLC hardware required, and
  the same views carry over once they're working on a real one.
- **Your data stays yours.** TRACE runs locally and does not transmit signal data, tags, or
  project information anywhere.

## Technology Overview

TRACE is a lightweight desktop application for Windows. It connects to PLC-connected equipment
over standard industrial Ethernet, runs entirely on the local machine, and stores its
configuration and recordings locally. There's no server component, no account requirement, and no
telemetry. This repository documents the product; the application itself is closed-source.

## Pricing

TRACE is free to use, with all current features included: no trial, no paid tier. See
[www.siganor.com/trace](https://www.siganor.com/trace) for the current feature list.

## Roadmap

TRACE is under active development; the full breakdown is in [`ROADMAP.md`](ROADMAP.md). In short:
Live Monitoring, Replay, Chain Map, the Pinout Library, and Simulation Mode are all shipped and in
daily use. Priorities being evaluated for future releases include support for additional
industrial protocols and continued refinement of the simulation toolset.

## Current Development Status

TRACE's core modules (Live Monitoring, Replay, Chain Map, Pinout Library, and Simulation Mode) are
functional and in daily use. Follow progress and get in touch through the channels below.

## FAQ

**What PLCs are supported?**
Allen-Bradley controllers over EtherNet/IP. Support for additional protocols is being evaluated
for future releases.

**Is an internet connection required?**
No. TRACE runs entirely on the local network segment where the PLC lives.

**Can recorded sessions be replayed later?**
Yes. The Replay module is built specifically for loading and analyzing past recording sessions.

**Can I export data?**
Yes, recordings can be exported to CSV for reporting or further analysis in other tools.

**Do I need a physical PLC to use TRACE?**
No. [Simulation Mode](docs/simulation.md) lets you configure digital and analog signals, load
prepared scenarios, and introduce manual events without connecting to physical PLC hardware.

**Is TRACE open source?**
TRACE is free to use, but its application source code is not public. This repository documents
the product publicly.

See the [full FAQ](docs/faq.md) for more.

## Contact

- Website: [www.siganor.com](https://www.siganor.com)
- Email: [info@siganor.com](mailto:info@siganor.com)

## License

This repository (documentation and media) is provided for informational purposes only. See
[`LICENSE.md`](LICENSE.md). It does not grant any license to the TRACE software itself; visit
[www.siganor.com](https://www.siganor.com) for product licensing information.
