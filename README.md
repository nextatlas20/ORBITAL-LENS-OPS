# Orbital Lens Operations

This repository holds sealed observatory telemetry for the morning control-room handoff.

<!-- MORNING-QUEUE:BEGIN -->
## Morning intervention queue — 5 March 2088
Interventions: 6 | Escalate: 1 | Calibrate: 2 | Schedule: 2 | Watch: 1

| Position | Instrument | Site | Drift (arcsec) | Action | Basis |
| ---: | --- | --- | ---: | --- | --- |
| 1 | OBS-DS-03 | Desert Spur | 0.20 | ESCALATE | signal loss |
| 2 | OBS-CP-06 | Cape Point | 9.99 | CALIBRATE | drift above 1.50 |
| 3 | OBS-HV-02 | Harbor View | 1.70 | CALIBRATE | drift above 1.50 |
| 4 | OBS-AL-04 | Alpine Lab | 0.75 | SCHEDULE | maintenance window: cryostat check |
| 5 | OBS-NR-01 | North Ridge | 1.20 | SCHEDULE | maintenance window: mirror wash |
| 6 | OBS-RV-07 | River Vale | 1.500 | WATCH | drift 0.75-1.50 |
<!-- MORNING-QUEUE:END -->

## Handling

Telemetry records are immutable after the seal is issued.
