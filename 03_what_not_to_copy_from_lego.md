# What NOT to Copy from LEGO Spike Prime

## Purpose
Identify LEGO design decisions that should **not** be replicated, as they conflict with engineering education goals.

---

## 1. Over-Abstraction of Hardware

LEGO hides:
- PWM
- ADC resolution
- Protocol errors
- Power constraints

Impact:
- Students cannot debug
- No understanding of failures

Decision:
- Expose hardware behavior gradually

---

## 2. Proprietary Lock-In

LEGO:
- Enforces certified devices
- Prevents third-party sensors

Impact:
- Limits experimentation
- Increases cost
- Reduces innovation

Decision:
- Support open standards and devices

---

## 3. Fixed Port Semantics

LEGO ports:
- Are pre-defined (motor/sensor)

Impact:
- No concept of multiplexing or reuse

Decision:
- Allow any port to become any interface

---

## 4. No Failure Visibility

LEGO hides:
- Bus collisions
- Timeout errors
- Electrical faults

Impact:
- Students assume systems “just work”

Decision:
- Surface errors in a controlled, teachable way

---

## 5. Terminal Learning Path

LEGO:
- Has no exit to professional tools

Decision:
- Design explicit transition to embedded systems

---

## Summary

Avoid copying LEGO’s **constraints**, not its polish.
