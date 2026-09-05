# Frequently Asked Questions

**What PLCs are supported?**
Allen-Bradley controllers over EtherNet/IP. Support for additional protocols is being evaluated
for future releases — see the [Roadmap](roadmap.md).

**Is an internet connection required?**
TRACE connects directly to PLC-connected equipment over the local industrial network, so no
internet connection or cloud account is needed.

**Can recordings be replayed?**
That's what the [Replay](replay.md) module is for: loading and analyzing previously recorded
sessions, complete with time cursors for precise event measurement.

**Can I export data?**
Recorded sessions can be exported to CSV for reporting or further analysis in spreadsheets or
other tools.

**Is TRACE open source?**
It isn't. TRACE is closed-source commercial software; this repository is the public
documentation and product overview, and the source code is maintained privately.

**Can I monitor multiple signals at once?**
[Live Monitoring](monitor.md) supports multiple synchronized graphs, each capable of tracking
several digital and analog signals simultaneously.

**Who is this software for?**
Maintenance technicians, automation engineers, controls engineers, commissioning engineers,
industrial electricians, and manufacturing engineers: anyone responsible for keeping
PLC-connected equipment running. It's also used by students and trainees learning to read and
troubleshoot PLC signals, before or alongside working with real equipment.

**Does TRACE require a live PLC to try?**
No — a built-in simulation mode generates realistic signal and network data, so the tool can be
evaluated, demonstrated, or used for training without a live connection. Students and trainees
can practice the same workflows on simulated data first, then move to a real PLC without
learning a different tool.

**Where can I ask a question that isn't answered here?**
Open an [Issue](https://github.com/wramirezrg/trace/issues) using the Question template, or email
[info@siganor.com](mailto:info@siganor.com).

---

[← Back to Overview](overview.md)
