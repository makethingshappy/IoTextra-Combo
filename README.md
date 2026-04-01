# Combo I/O modules (analog and digital) for IoT/IIoT/Smart Home. Integrate with Raspberry, Arduino, etc. Accelerate development via Node-RED & IoTflow

## Overview

[**IoTextra-Combo**](https://makethingshappy.io/collections/Combo-iotextra) The IoTextra Combo series provides high-precision ADC and Digital I/O solutions for the **makethingshappy** platform. All modules follow the **47x56 mm** form factor.

IoTextra modules integrate cleanly with IoTbase carrier boards and IoTsmart MCU boards and can be used with MQTT and Node-RED workflows (e.g., via the IoTflow automation framework).

---

## Hardware Specifications

Each IoTextra-Combo module has its own electrical and mechanical specifications, documented inside its versioned folder.

Module folders:

- **[Combo/v.3.03](./Combo/v.3.03/)**  
- **Combo2** ( Coming Soon )  

Refer to each module’s documentation for exact technical data.

---

## Module Comparison

- **IoTextra Combo**: Based on **ADS1115** (16-bit), optimized for 4-20mA and 0-10V signals. Two SPDT relays.
- **IoTextra Analog2**: Based on **MCP3421** (18-bit), provides 2 differential channels for high-resolution tasks. Two SPDT relays and two digital output channels.

---

## Measurement Ranges

The **IoTextra Combo** (ADS1115) model supports:
- Voltage: ±0.5V to ±10V.
- Current: 0-20mA, 4-20mA, and up to 40mA.

---

## Connectivity

- **Primary Interface**: HOST12 connector providing Power, 10 GPIOs, and I2C.
- **Expansion**: 2x Qwiic connectors on Lite and Pro versions for daisy-chaining.


See the diagrams located in:

- **[Combo/v.3.03](./Combo/v.3.03/)**  

---

## Software Support

IoTextra-Combo is a **hardware-only** series, but integrates cleanly into automation stacks.

Typical usage includes:

- Connecting module inputs/outputs to IoTsmart or Raspberry Pi PICO boards  
- Triggering MQTT events or Node-RED flows  
- Following IoTflow’s MQTT topic conventions for automation

---

### Node-RED Automation Examples (IoTflow)

👉 **IoTflow Node-RED Examples**  
https://github.com/makethingshappy/IoTflow/tree/main/Node-RED%20Examples

---

## Ordering Information

### 📦 SKU Information  
The complete list of SKUs is provided in the following PDF located in the repository root:

- **SKU Combo IoTextra.pdf**

---

### 🛒 Purchase Links  

Order directly from the official store:

* [**IoTextra Combo Module**](https://makethingshappy.io/collections/combo-iotextra/products/iotextra-combo)

---

## Licensing

This repository uses separate licenses for each category of assets:

- **Code:** [`LICENSE_CODE.md`](./LICENSE_CODE.md) — MIT License  
- **Schematics & Documentation:** [`LICENSE_HARDWARE.md`](./LICENSE_HARDWARE.md) — CC BY-SA 4.0  
- **Documentation:** [`LICENSE_DOCS.md`](./LICENSE_DOCS.md)  
- **Media:** [`LICENSE_MEDIA.md`](
