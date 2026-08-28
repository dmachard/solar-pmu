# solar-pmu

Solar power management unit designed for ultra-low power IoT

![Solar PMU Board](hardware/board_3d.png)

It features a dedicated Li-ion charger with dynamic power path management, an integrated 18650 cell holder, a regulated 3.3V output, and real-time I2C power monitoring.

## Features

* **PMIC / Charger**: BQ25185
* **Battery:** Onboard single 18650 Li-ion holder
* **Voltage Regulator:** ME6211
* **Power Monitoring**: INA226

## Pinout

| Connector | Type | Pin 1 | Pin 2 |
| :--- | :--- | :--- | :--- |
| **SOLAR1 / SOLAR2** | JST-PH 2.0 | `+` (V_IN) | `-` (GND) |
| **3.3V OUT** | JST-PH 2.0 | `-` (GND) | `+` (3.3V) |
| **I2C** | JST-PH 2.0 | SDA | SCL |