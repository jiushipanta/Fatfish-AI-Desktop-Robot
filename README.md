# FatFish: AI Desktop Companion Robot

## Project Owner

**Name:** Rui Ma
**Virginia Tech Email:** ruim@vt.edu

## Project Overview

FatFish is an AI desktop companion robot with a 6-DOF head, two moving arms, and a rotating base. It uses voice and vision to interact with users. The goal is to build a working prototype in six weeks.

## What I Hope to Learn

Integrate mechanics, embedded firmware, networking, and cloud AI into one reliable robot.

## Design and Implementation

The ESP32-P4 handles sound direction, camera capture, and servo control. An ESP32-C6 provides Wi-Fi 6. Cloud services provide speech recognition (ASR), DeepSeek language processing (LLM), speech synthesis (TTS), and vision. The head is a six-degree-of-freedom Stewart platform driven by six SCS0009 servos. Two servos move the arms, and two rotate the base.

## Bill of Materials

Estimated component costs are planning estimates. PLA and a 3D printer are already owned.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Feetech SCS0009 serial servo | 10 | $80.00 | [Seeed Studio product page](https://www.seeedstudio.com/Feetech-SCS0009-Servo-p-6535.html) |
| DFRobot FireBeetle 2 ESP32-P4 | 1 | $16.50 | [DFRobot product page](https://www.dfrobot.com/product-2915.html) |
| MIPI CSI camera module | 1 | $12.90 | [Seeed Studio product page](https://www.seeedstudio.com/OV5647-160-FOV-IR-Camera-module-for-Raspberry-Pi-3B-4B-p-5485.html) |
| Multi-microphone array | 1 | $11.90 | [DFRobot product page](https://www.dfrobot.com/product-1976.html) |
| MAX98357A I²S amplifier | 1 | $4.90 | [DFRobot product page](https://www.dfrobot.com/product-2614.html) |
| Mini speaker | 1 | $5.00 | [Seeed Studio product page](https://www.seeedstudio.com/Mono-Enclosed-Speaker-4R-5W-p-5931.html) |
| Power components (DC-DC, LDO) | 1 | $20.00 | TBD |
| Servo interface | 1 | $12.00 | TBD |
| Bearings, rods, screws, hardware | 1 | $20.00 | TBD |
| Filament | 4 | $68.00 | [Amazon product page](https://www.amazon.com/dp/B0DLJKB98D) |

**Estimated total:** $251.20 hardware + $15.07 tax + $18.00 shipping + $15.00 reserve = **$299.27**. Verify compatibility, stock, tax, and shipping before purchase.

## Timeline and Milestones

| Milestone | Target Date | Status |
|---|---|---|
| CAD and linkage validation | Week 1 | Planned |
| Procurement and electronics | Week 2 | Planned |
| Cloud ASR, LLM, and TTS | Week 3 | Planned |
| Motion control and inverse kinematics | Week 4 | Planned |
| Sensor and AI integration | Week 5 | Planned |
| Debugging and final demo | Week 6 | Planned |

## Progress Log

- 2026-10-30 — Finished the project presentation.
- 2026-10-31 — Set up the GitHub repository.

## Project Files

- `README.md` — project overview, design, bill of materials, timeline, and progress log.
- `hero.png` — project cover image.

## Useful Links

- [FEETECH SCS0009 Specification Sheet](https://m5stack-doc.oss-cn-shenzhen.aliyuncs.com/1205/SCS0009.pdf)
- [Reachy Mini GitHub Repository](https://github.com/pollen-robotics/reachy_mini)
- [Stewart Platform Inverse Kinematics with Servo Motors](https://raw.org/research/inverse-kinematics-of-a-stewart-platform/)

## Project Image

The project cover image is `hero.png`. It is used on the AMP Lab website; keep this filename.
