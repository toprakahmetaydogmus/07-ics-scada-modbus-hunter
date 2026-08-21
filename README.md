# 🏭 OT / ICS / SCADA Modbus Telemetry & Snort Threat Hunter

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/toprakahmetaydogmus/07-ics-scada-modbus-hunter?color=blue&label=Release)](https://github.com/toprakahmetaydogmus/07-ics-scada-modbus-hunter/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Developer: **Toprak Ahmet Aydoğmuş**

---

## 🎯 1. Overview
Operational Technology (OT) and SCADA threat hunting engine. Parses Modbus/TCP APU/PDU frames, detects unauthorized coil writes, function code anomalies (e.g. Force Single Coil / Multiple Registers), and generates Snort ICS inspection rules.

---

## 🚀 2. Quick Start

```bash
git clone https://github.com/toprakahmetaydogmus/07-ics-scada-modbus-hunter.git
cd 07-ics-scada-modbus-hunter
python -m unittest discover tests/
```

---

## 📜 3. License
Licensed under the [MIT License](LICENSE).  
Developer: **Toprak Ahmet Aydoğmuş**.
