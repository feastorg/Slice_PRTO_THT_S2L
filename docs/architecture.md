---
title: "Architecture Overview"
description: "High-level architecture: electrical, firmware, and mechanical design notes."
---

Overview of the electrical, firmware, and mechanical design of this Slice.

## 🧠 Purpose

<!-- Briefly describe the function of the Slice -->

This Slice is designed as a template for creating new Slice modules, with variants supporting different mechanical and electrical configurations. It is intended to standardize layout and encourage reuse.

## 🔌 Interfaces

| Signal | Connector | Direction | Voltage | Notes |
| ------ | --------- | --------- | ------- | ----- |
| ...    | ...       | ...       | ...     | ...   |

## 🪛 MCU Pin Mapping

| MCU Pin | Function | Net | Notes |
| ------- | -------- | --- | ----- |
| ...     | ...      | ... | ...   |

### DUMP

- Supported MCU Dev Boards:
  - Arduino Nano Original (ATMega328P)
  - Arduino Nano Every (ATMega4809)
  - STM32 Nucleo-32 series (e.g. L432KC, F303K8)
  - Other Nano-format boards also supported:
    - Any MCU board using the standard Arduino Nano pinout and 0.1" dual-row 15x2 header format
    - Nano ESP32 and ESP32-S2 variants with Nano footprint (e.g. Nano ESP32 by Arduino, or 3rd party clones)
    - RP2040 Nano-form boards (e.g. Nano RP2040 Connect, Seeed Studio RP2040 Nano)
    - CH32V203 or CH32V003 Nano-format RISC-V dev boards

## 🔋 Power Domains

- Logic power: ...
- High-current domain: ...

## 🧩 Mechanical

- Mounting pattern: ...
- Dimensions: ...
- Notes: ...

---

<!-- Optional: Add block diagrams or images under docs/assets/ -->
