# Overview

TRACE is an industrial troubleshooting and diagnostics platform for PLC-connected equipment.
It's built for the people who are physically at the machine when something goes wrong, or who
need to understand exactly what happened after the fact.

## The problem

When a machine faults, the person diagnosing it usually has two options: watch the control panel
and hope to catch the fault as it happens, or open a proprietary engineering tool that's
expensive, tied to a single vendor's hardware, and often too generic to answer a specific field
question quickly. Neither option is built for speed.

## The approach

TRACE puts four capabilities in one application, all aimed at shortening the time between
noticing a problem and understanding what caused it:

- **[Live Monitoring](monitor.md)** — see signal behavior as it happens
- **[Replay](replay.md)** — go back and analyze what already happened
- **[Chain Map](chain-map.md)** — see the network the equipment depends on
- **[Pinout Library](pinouts.md)** — reference connector standards without leaving the tool

## Who it's for

- Maintenance Technicians
- Automation Engineers
- Controls Engineers
- Commissioning Engineers
- Industrial Electricians
- Manufacturing Engineers

## Design principles

- **Speed over ceremony.** Skip the project setup; connect and see live data in seconds.
- **Works offline.** A built-in simulation mode means the tool is useful even without a live PLC
  connection, for training, demos, or preparing a layout in advance.
- **Local by default.** TRACE runs on the technician's own machine and doesn't depend on
  outside infrastructure to do its job.

## Learn more

- [Live Monitoring](monitor.md)
- [Replay](replay.md)
- [Chain Map](chain-map.md)
- [Pinout Library](pinouts.md)
- [Screenshots](screenshots.md)
- [Roadmap](roadmap.md)
- [FAQ](faq.md)
