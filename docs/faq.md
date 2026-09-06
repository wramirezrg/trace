# Frequently Asked Questions

**What PLCs are supported?**
Allen-Bradley controllers over EtherNet/IP. Support for additional protocols is being evaluated
for future releases. See the [Roadmap](roadmap.md) for details.

**Is an internet connection required?**
TRACE connects directly to PLC-connected equipment over the local industrial network, so no
internet connection or cloud account is needed.

**Can recordings be replayed?**
That's what the [Replay](replay.md) module is for: loading and analyzing previously recorded
sessions, complete with time cursors for precise event measurement.

**Can I export data?**
Recorded sessions can be exported to CSV for reporting or further analysis in spreadsheets or
other tools.

**Is TRACE free?**
Yes. TRACE is free to use, with all current features included: no trial, no paid tier.

**Is TRACE open source?**
It isn't. TRACE is free to use, but its source code is not public; this repository is the public
documentation and product overview.

**Can I monitor multiple signals at once?**
[Live Monitoring](monitor.md) supports multiple synchronized graphs, each capable of tracking
several digital and analog signals simultaneously.

**Who is this software for?**
Maintenance technicians, automation engineers, controls engineers, commissioning engineers,
industrial electricians, and manufacturing engineers: anyone responsible for keeping
PLC-connected equipment running. It's also used by students and trainees learning to read and
troubleshoot PLC signals, before or alongside working with real equipment.

**Does TRACE require a live PLC to try?**
No. [Simulation Mode](simulation.md) lets you configure digital and analog signals, load prepared
scenarios, and introduce manual events without connecting to physical PLC hardware. Students and
trainees can practice the same workflows on simulated data first, then move to a real PLC without
learning a different tool.

**Can I use TRACE for teaching or practice?**
Yes. Prepared scenarios and configurable signals provide a way to demonstrate signal behavior and
practice using TRACE in a classroom, personal lab, or technician training session.

**Can I simulate intermittent signal problems?**
Yes. Digital patterns include contact bounce and intermittent dropouts. Manual controls also let
you force or freeze simulated values, apply temporary analog spikes or dips, and interrupt
simulated communication for a panel. See [Simulation Mode](simulation.md).

**Where can I ask a question that isn't answered here?**
Open an [Issue](https://github.com/wramirezrg/trace/issues) using the Question template, or email
[info@siganor.com](mailto:info@siganor.com).

---

[← Back to Overview](overview.md)
