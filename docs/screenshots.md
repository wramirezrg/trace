# Screenshots

A closer look at each module. All images are captures of the actual application.

## Live Monitoring

![Live Monitoring](../media/monitor.png)

Multiple synchronized graphs tracking digital and analog signals in real time. Each graph window
is independent, so different machine sections can be watched side by side without one busy chart
becoming unreadable.

## Replay

![Replay](../media/replay.png)

A recorded session loaded for analysis, with dual time cursors placed around a sequence of
events. The time delta between the cursors gives an exact measurement of how long each step in
the sequence took.

## Chain Map

![Chain Map](../media/chain-map.png)

An industrial Ethernet daisy chain, mapped node by node with live latency figures. An unreachable
node is immediately visible, along with everything downstream of it that's affected.

## Pinouts

![Pinouts](../media/pinouts.png)

An industrial connector reference, covering pin numbering, signal assignment, and color coding,
kept inside the same tool used for monitoring and diagnostics.

## Simulation Mode

![Simulation Mode](../media/simulation.png)

The "Motor start sequence" scenario running with no PLC connected: `Motor_Running` follows
`Start_Command` with its own delay, and `Motor_Current` climbs with a realistic first-order
response as the motor starts.

---

[← Back to Overview](overview.md)
