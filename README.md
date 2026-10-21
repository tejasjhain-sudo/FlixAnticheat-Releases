# Vigil / FlixAnticheat — Official Binary Distribution 🛡️
> **Enterprise Packet-Level Detection Engine for Modern Minecraft (1.20 – 1.21+)**  
> Engineered by **FlixStudios** (Tejas) • Folia-Ready & Netty Async

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20%20--%201.21+-brightgreen.svg)
![Netty Pipeline](https://img.shields.io/badge/Pipeline-Netty_Async-blue.svg)
![Overhead](https://img.shields.io/badge/Tick_Overhead-%3C0.02ms-brightgreen.svg)
![Folia Ready](https://img.shields.io/badge/Folia-Thread_Safe-purple.svg)

---

## ✨ Engine Overview

Vigil Anticheat is a high-performance packet analysis engine designed for enterprise networks. By decoupling packet processing entirely from the Minecraft tick loop, Vigil eliminates movement spoofing, reach, and combat anomalies without impacting server TPS.

* **⚡ Zero-Tick Performance (<0.02ms):** Fully off-tick execution via Netty channel handlers.
* **🎯 Sub-Millimeter Reach Detection:** 3D raycast collision analysis with strict box projection (3.001 block boundary precision).
* **🔄 Rotational Acceleration Heuristics:** Advanced trigonometric angle distribution checks detecting silent killaura and aim-assist locks.
* **🌐 Folia Multithreading Support:** Engineered with region-safe concurrency guarantees.

---

## 📦 Releases & Verification
Compiled enterprise builds and checksums are published in [GitHub Releases](https://github.com/tejasjhain-sudo/FlixAnticheat-Releases/releases).

---

## 🏢 Commercial Licensing
Vigil Anticheat is proprietary software licensed exclusively through **FlixStudios**.  
To request network licensing or private deployment, visit [flixstudios.in](https://flixstudios.in).

---
© 2026 FlixStudios. All rights reserved.
