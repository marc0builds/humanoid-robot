# Humanoid H1

Part of [marc0builds](https://mmessa28.github.io/marc0builds/) · [Instagram](https://instagram.com/marc0builds) · [Support the build](https://buymeacoffee.com/marc0builds)

**Status: 🔵 planning · building the first actuator**

A child-sized (~1.0–1.2 m), two-legged humanoid robot that walks, talks and reacts. The same class as commercial humanoids like the Unitree R1, but built in a home workshop on a fraction of the budget.

> Working title: **H1**. The final name comes later.

## Goals

- Walk on two legs (slow, stable gait first)
- Talk, listen and react (voice/AI layer)
- Total material budget **under €1,500**
- Every part I design is released **open source** when it's done

## Architecture

| Part | Approach |
|---|---|
| **Leg joints** (hip, knee) | 3D-printed quasi-direct-drive actuators with cycloidal-planetary gearbox, based on [Caden Kraft's Ironless QDD Actuator](https://github.com/CKraft11/Ironless-QDD-Actuator) |
| **Ankles** | Smaller off-the-shelf gear motors (e.g. Steadywin GIM6010-8) |
| **Arms & head** | Standard high-torque hobby servos via PCA9685 |
| **Motor drivers** | ODrive-compatible (MKS XDrive Mini) |
| **Balance** | IMU (gyro + accelerometer) |
| **Brain** | Raspberry Pi for control & testing, upgrade later |
| **Walking** | Pre-programmed gait first, reinforcement learning in simulation later |
| **Shell** | Lightweight 3D-printed armour plates |

## Budget (target)

| Area | Estimate |
|---|---|
| Legs (actuators + drivers) | €500–700 |
| Arms & head (servos) | €150–200 |
| Battery + BMS | €100–150 |
| Electronics (compute, IMU, camera, audio) | €80–120 |
| Filament, bearings, screws, frame | €100–150 |
| **Total** | **~€1,000–1,400** |

## Roadmap

- [ ] **Phase 1:** one actuator, torque test ← **current step**
- [ ] **Phase 2:** one full test leg
- [ ] **Phase 3:** both legs + hip, standing and weight shifting
- [ ] **Phase 4:** first steps with IMU balance
- [ ] **Phase 5:** upper body (arms, head)
- [ ] **Phase 6:** voice/AI layer
- [ ] **Phase 7:** armour shell & design
- [ ] **Phase 8:** release all files

## Files

- [ACTUATOR.md](ACTUATOR.md): the joint motor (parts list, print notes, test log)

## Credits

| Project | Author | Used for | License |
|---|---|---|---|
| [Ironless QDD Actuator](https://github.com/CKraft11/Ironless-QDD-Actuator) | Caden Kraft | Joint actuator | MIT |
| [Berkeley Humanoid Lite](https://github.com/HybridRobotics/Berkeley-Humanoid-Lite) | Hybrid Robotics, UC Berkeley | Leg design and RL walking reference | See repo |
| [InMoov](https://inmoov.fr/) | Gaël Langevin | Arms, hands and head reference | CC BY-NC |

Third-party files are linked, not copied.

## License

My own designs and docs: [CC BY-NC 4.0](LICENSE). Build it, remix it, share it. Not for commercial use.

## Support

Help buy the next motor: **[buymeacoffee.com/marc0builds](https://buymeacoffee.com/marc0builds)** 🖤
