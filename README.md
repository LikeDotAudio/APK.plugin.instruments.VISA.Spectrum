# INSTRUMENT.Spectrum

**Wiki:** [Documentation/README.md](Documentation/README.md) — principles, architecture, delivery, and the [SDK](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK.md).

The **Spectrum** instruments of the APK.audio bench, as one thing: 28 models, their command tables and the family's panel. Spectrum analysers: a trace on screen and markers on it.

| | |
|---|---|
| **Is** | **inputs** — takes signals in — its connectors are inputs a patch can land on<br>**metering** — measures — its readings are numbers with units<br>**monitoring** — shows — a trace, a waveform or a display you watch |
| **Inputs** | each model's BIM part: /api/bim/parts?full=1&id=<part> — ports where side is "input" and domain is not "power" |
| **Recipe** | none — data, not a container: read in place by the stacks that bake `INSTRUMENTS` |
| **Source** | this repository (https://github.com/LikeDotAudio/APK.plugin.instruments.VISA.Spectrum.git), a submodule of [APK.plugin.instruments.VISA](https://github.com/LikeDotAudio/APK.plugin.instruments.VISA) at `INSTRUMENT.Spectrum/` |
| **Family name** | `Spectrum` — the device type, the topic segment and the `manifest.json` key; the `INSTRUMENT.` prefix belongs to the folder only |

## Models

| Model | Maker | What | Commands | Table | API |
|---|---|---|---:|:---:|---|
| [8560A](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8560A.md) | HP / Agilent / Keysight | Portable 2.9 GHz (Legacy) | 239 |  | :15000 |
| [8560E](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8560E.md) | HP / Agilent / Keysight | Portable 2.9 GHz (Enhanced) | 239 |  | :15001 |
| [8561E](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8561E.md) | HP / Agilent / Keysight | Portable 6.5 GHz | 239 |  | :15002 |
| [8562E](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8562E.md) | HP / Agilent / Keysight | Portable 13.2 GHz | 239 |  | :15003 |
| [8563E](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8563E.md) | HP / Agilent / Keysight | Portable 26.5 GHz | 239 |  | :15004 |
| [8564E](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8564E.md) | HP / Agilent / Keysight | Portable 40 GHz | 239 |  | :15005 |
| [8565E](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8565E.md) | HP / Agilent / Keysight | Portable 50 GHz | 239 |  | :15006 |
| [8566B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8566B.md) | HP / Agilent / Keysight | High Perf 22 GHz (The 'Beast') | 239 |  | :15007 |
| [8568B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8568B.md) | HP / Agilent / Keysight | High Perf 1.5 GHz | 239 |  | :15008 |
| [8590 Series](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/8590%20Series.md) | HP / Agilent / Keysight | Low Cost Portable (Legacy) | 239 |  | :15009 |
| [DSA815-TG](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/DSA815-TG.md) | Rigol | 1.5 GHz Analyzer + Tracking Gen | 239 |  | :15010 |
| [DSA832](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/DSA832.md) | Rigol | 3.2 GHz Spectrum Analyzer | 239 |  | :15011 |
| [E4401B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/E4401B.md) | HP / Agilent / Keysight | ESA-E Series 1.5 GHz | 239 |  | :15012 |
| [E4407B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/E4407B.md) | HP / Agilent / Keysight | ESA-E Series 26.5 GHz | 239 |  | :15013 |
| [FPC1000](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/FPC1000.md) | Rohde & Schwarz | Entry Spectrum Analyzer (1-3 GHz) | 239 |  | :15014 |
| [FPC1500](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/FPC1500.md) | Rohde & Schwarz | Spectrum Analyzer + Vector Network | 239 |  | :15015 |
| [FSH4](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/FSH4.md) | Rohde & Schwarz | Handheld Spectrum Analyzer | 239 |  | :15016 |
| [FSV3000](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/FSV3000.md) | Rohde & Schwarz | Signal and Spectrum Analyzer | 239 |  | :15017 |
| [HPE4411A](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/HPE4411A.md) | HP / Agilent / Keysight | ESA-L Series 1.5 GHz | 28 | ✅ | :15018 |
| [N9000B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9000B.md) | HP / Agilent / Keysight | CXA Signal Analyzer | 239 |  | :15019 |
| [N9010B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9010B.md) | HP / Agilent / Keysight | EXA Signal Analyzer | 239 |  | :15020 |
| [N9020B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9020B.md) | HP / Agilent / Keysight | MXA Signal Analyzer | 239 |  | :15021 |
| [N9030B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9030B.md) | HP / Agilent / Keysight | PXA Signal Analyzer (High Performance) | 239 |  | :15022 |
| [N9040B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9040B.md) | HP / Agilent / Keysight | UXA Signal Analyzer (Ultra Performance) | 239 |  | :15023 |
| [N9340B](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9340B.md) | HP / Agilent / Keysight | Handheld (100 kHz - 3 GHz) | 256 | ✅ | :15024 |
| [N9342CN](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9342CN.md) | HP / Agilent / Keysight | Handheld (9 kHz - 7 GHz) | 28 | ✅ | :15025 |
| [N9912A](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9912A.md) | HP / Agilent / Keysight | FieldFox RF Analyzer (4 GHz) | 239 |  | :15026 |
| [N9918A](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SDK/N9918A.md) | HP / Agilent / Keysight | FieldFox RF Analyzer (26.5 GHz) | 239 |  | :15027 |

## Layout

```
INSTRUMENT.Spectrum/
  thing.json            what this thing is on the bench (authored)
  gui/                  the family panel, stamped once per discovered box
    Spectrum.cad.json
    Spectrum.dxf
    Spectrum.json
    Spectrum.probe.json
  <Model>/              <Model>.komand (the command table), <Model>.gui,
                        <Model>.api.json (generated), commands_tree.md, SOURCES.md
  Documentation/        the wiki; SDK/ is generated by _komand/family_sdk_docs.py
```

Generated by `_komand/family_sdk_docs.py` in the parent repository; edit `thing.json` or the
models, not this page.

<!-- wiki:smoke -->
**Smoke test** — ❌ FAIL 0/1 since 2026-11-04 20:50 EST — [results](Documentation/%F0%9F%A7%A9Manual%20and%20Artifacts/SMOKE.md)
<!-- /wiki:smoke -->
