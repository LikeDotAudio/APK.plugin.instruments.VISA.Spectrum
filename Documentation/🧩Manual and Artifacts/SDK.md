# SDK — INSTRUMENT.Spectrum

Every Spectrum model this library drives, and how to drive it. Each model answers the same five verbs over HTTP (its own port), WebSocket, a Unix socket and the bus; one page per model below lists its routes and every command.

← [Manual and Artifacts](INDEX.md)

| Verb | What it does |
|---|---|
| `get` | reads one value |
| `set` | writes one value |
| `nab` | reads more than one thing (observation, telemetry) |
| `rig` | configures several arguments at once |
| `do` | executes an action; takes no value |

| Model | Maker | get | set | nab | rig | do | Port |
|---|---|---:|---:|---:|---:|---:|---:|
| [8560A](SDK/8560A.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15000 |
| [8560E](SDK/8560E.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15001 |
| [8561E](SDK/8561E.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15002 |
| [8562E](SDK/8562E.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15003 |
| [8563E](SDK/8563E.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15004 |
| [8564E](SDK/8564E.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15005 |
| [8565E](SDK/8565E.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15006 |
| [8566B](SDK/8566B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15007 |
| [8568B](SDK/8568B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15008 |
| [8590 Series](SDK/8590%20Series.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15009 |
| [DSA815-TG](SDK/DSA815-TG.md) | Rigol | 87 | 142 | 101 | 3 | 53 | 15010 |
| [DSA832](SDK/DSA832.md) | Rigol | 87 | 142 | 101 | 3 | 53 | 15011 |
| [E4401B](SDK/E4401B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15012 |
| [E4407B](SDK/E4407B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15013 |
| [FPC1000](SDK/FPC1000.md) | Rohde & Schwarz | 87 | 142 | 101 | 3 | 53 | 15014 |
| [FPC1500](SDK/FPC1500.md) | Rohde & Schwarz | 87 | 142 | 101 | 3 | 53 | 15015 |
| [FSH4](SDK/FSH4.md) | Rohde & Schwarz | 87 | 142 | 101 | 3 | 53 | 15016 |
| [FSV3000](SDK/FSV3000.md) | Rohde & Schwarz | 87 | 142 | 101 | 3 | 53 | 15017 |
| [HPE4411A](SDK/HPE4411A.md) | HP / Agilent / Keysight | 4 | 9 | 8 | 3 | 8 | 15018 |
| [N9000B](SDK/N9000B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15019 |
| [N9010B](SDK/N9010B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15020 |
| [N9020B](SDK/N9020B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15021 |
| [N9030B](SDK/N9030B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15022 |
| [N9040B](SDK/N9040B.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15023 |
| [N9340B](SDK/N9340B.md) | HP / Agilent / Keysight | 101 | 145 | 115 | 3 | 53 | 15024 |
| [N9342CN](SDK/N9342CN.md) | HP / Agilent / Keysight | 4 | 9 | 8 | 3 | 8 | 15025 |
| [N9912A](SDK/N9912A.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15026 |
| [N9918A](SDK/N9918A.md) | HP / Agilent / Keysight | 87 | 142 | 101 | 3 | 53 | 15027 |
