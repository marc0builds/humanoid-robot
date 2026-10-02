# Actuator #1: 3D-printed QDD joint motor

The first part of the humanoid: a joint motor strong enough for knees and hips, printed in-house.

**Base design:** [Ironless QDD Actuator](https://github.com/CKraft11/Ironless-QDD-Actuator) by Caden Kraft (MIT license).
Print files: [MakerWorld](https://makerworld.com/en/models/2042262-caden-kraft-s-qdd-cycloidal-planetary-actuator).
Rated up to ~29 Nm holding torque, ~$70 including controller according to the author.

## Parts list (one actuator)

From the original BOM. Quantities per actuator.

| Part | Qty |
|---|---|
| Motor driver MKS XDrive Mini | 1 |
| Stator 10010 | 1 |
| Magnets N52 12×5×3 mm | 42 |
| Enamelled magnet wire 0.4 mm | ~60 g |
| Bearing 6805 (25×37×7) | 2 |
| Bearing 6710 (50×62×6) | 2 |
| Bearing 5×14×5 | 6 |
| Pin 5×12 mm | 3 |
| M2.5×12 countersunk | 20 |
| Heat-set inserts M2.5 / M3 / M4 | 7 / 14 / 15 |
| M4×25 shoulder bolt | 1 |
| Lock nuts M2 / M4 | 4 / 1 |
| M3×6 screws | 8 |
| M2×25 screws | 4 |

**Also needed:** PET-CF filament (no PLA: the rotor creeps under magnetic load), M3 tap, lithium grease, 24 V / ≥10 A bench supply.

## Print notes

- Rotor: 100% infill, stiff low-creep material (PET-CF / PA6-CF)
- Gears: engineering plastic, hardened nozzle
- Driver config for the MKS XDrive is in the [original repo](https://github.com/CKraft11/Ironless-QDD-Actuator)

## Test log

| Date | Test | Result |
|---|---|---|
| | Holding torque | |
| | Backlash | |
| | Temperature after 10 min | |
