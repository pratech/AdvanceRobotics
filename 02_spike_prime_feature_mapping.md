# Spike Prime Feature Mapping → STM32 Robotics Hub

## Objective
Map LEGO Spike Prime capabilities to equivalent or superior implementations in the STM32 Robotics Hub.

---

## Port & Device Mapping

| Spike Prime Feature | STM32 Hub Equivalent |
|-------------------|----------------------|
| Powered motor port | PWM + H-bridge + encoder |
| LEGO sensor port | Generic ADC / I2C / UART |
| Auto-detection | Electrical + protocol detection |
| Fixed port role | Dynamic port role |

---

## Sensors

| Spike Sensor | STM32 Hub Approach |
|-------------|-------------------|
| Color sensor | Generic I2C color sensor |
| Distance sensor | Ultrasonic / ToF via I2C |
| Force sensor | Analog load cell |
| IMU | On-board IMU |

---

## Programming

| Capability | Spike Prime | STM32 Hub |
|----------|-------------|-----------|
| Scratch blocks | Static | Dynamic |
| Custom sensors | No | Yes |
| MicroPython access | Limited | Full |
| Register-level learning | No | Optional |

---

## Educational Upgrade

Spike Prime abstracts complexity.  
STM32 Hub exposes complexity **progressively**, enabling deeper learning without overwhelming beginners.

---

## Net Result

Everything Spike Prime can do:
- STM32 Hub can do equivalently

Many things STM32 Hub can do:
- Spike Prime intentionally cannot
