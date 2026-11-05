<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=800&color=7AA2F7&center=true&vCenter=true&width=640&lines=Hi%2C+I'm+Bekirhan+%F0%9F%91%8B;Embedded+%26+Real-Time+Software;UAV+%C2%B7+Avionics+%C2%B7+Radar+%C2%B7+Vision" alt="Typing intro" />

**Embedded & real-time software developer** — I build things that run close to the hardware:<br/>
firmware, Linux system services, networking stacks and signal-processing pipelines.

[![Repos](https://img.shields.io/badge/public_repos-21-7aa2f7?style=flat-square)](https://github.com/bekirhankarakurt?tab=repositories)
[![All CI green](https://img.shields.io/badge/CI-all_green-9ece6a?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/bekirhankarakurt?tab=repositories)

<img src="https://skillicons.dev/icons?i=cpp,c,rust,python,cmake,linux,raspberrypi,githubactions,docker,git,vim&theme=dark" alt="Tech stack" />

</div>

---

### 🛰️ Focus areas

`embedded Linux` · `RTOS firmware` · `UAV / avionics software` · `radar & vision` · `real-time networking` · `performance & concurrency`

### ⭐ Featured projects

| Project | What it does | Release |
|---|---|---|
| 📡 **[radar-signal-processing-sim](https://github.com/bekirhankarakurt/radar-signal-processing-sim)** | Pulse-Doppler radar: LFM pulse compression, Doppler FFT, CFAR detection | ![release](https://img.shields.io/github/v/release/bekirhankarakurt/radar-signal-processing-sim?style=flat-square&color=7aa2f7&label=) |
| 🛩️ **[mavlink-ground-station](https://github.com/bekirhankarakurt/mavlink-ground-station)** | MAVLink v2 ground station: live telemetry, missions, PX4 SITL tested | ![release](https://img.shields.io/github/v/release/bekirhankarakurt/mavlink-ground-station?style=flat-square&color=7aa2f7&label=) |
| 🗺️ **[uav-mission-planner](https://github.com/bekirhankarakurt/uav-mission-planner)** | A* / Theta* / RRT* route planning over terrain and no-fly zones | ![release](https://img.shields.io/github/v/release/bekirhankarakurt/uav-mission-planner?style=flat-square&color=7aa2f7&label=) |
| 🎯 **[vision-target-tracker](https://github.com/bekirhankarakurt/vision-target-tracker)** | Correlation tracker + Kalman prediction + PID gimbal loop | ![release](https://img.shields.io/github/v/release/bekirhankarakurt/vision-target-tracker?style=flat-square&color=7aa2f7&label=) |
| 🗃️ **[flight-data-recorder](https://github.com/bekirhankarakurt/flight-data-recorder)** | Power-loss tolerant black box with crash recovery and replay | ![release](https://img.shields.io/github/v/release/bekirhankarakurt/flight-data-recorder?style=flat-square&color=7aa2f7&label=) |
| 📟 **[telemetry-tui-dashboard](https://github.com/bekirhankarakurt/telemetry-tui-dashboard)** | Rust terminal dashboard with live telemetry charts | ![release](https://img.shields.io/github/v/release/bekirhankarakurt/telemetry-tui-dashboard?style=flat-square&color=7aa2f7&label=) |

<details>
<summary><b>📂 All 21 projects (with live CI status)</b></summary>

### UAV & Avionics

| Project | What it does | Key tech | CI |
|---|---|---|---|
| [mavlink-ground-station](https://github.com/bekirhankarakurt/mavlink-ground-station) | MAVLink ground control station: live telemetry, mission upload, command link; tested against PX4 SITL | C++17, MAVLink | [![CI](https://github.com/bekirhankarakurt/mavlink-ground-station/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/mavlink-ground-station/actions/workflows/ci.yml) |
| [uav-mission-planner](https://github.com/bekirhankarakurt/uav-mission-planner) | A*, Theta* and RRT* planning over SRTM terrain and no-fly zones, exporting QGC missions | C++17, pybind11 | [![CI](https://github.com/bekirhankarakurt/uav-mission-planner/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/uav-mission-planner/actions/workflows/ci.yml) |
| [adsb-aircraft-tracker](https://github.com/bekirhankarakurt/adsb-aircraft-tracker) | ADS-B Mode S decoder and aircraft tracker for RTL-SDR captures with live map output | C++17, Mode S | [![CI](https://github.com/bekirhankarakurt/adsb-aircraft-tracker/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/adsb-aircraft-tracker/actions/workflows/ci.yml) |
| [flight-data-recorder](https://github.com/bekirhankarakurt/flight-data-recorder) | Power-loss tolerant black box with CRC-framed append-only storage and replay tooling | C++17, CRC | [![CI](https://github.com/bekirhankarakurt/flight-data-recorder/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/flight-data-recorder/actions/workflows/ci.yml) |
| [imu-kalman-attitude](https://github.com/bekirhankarakurt/imu-kalman-attitude) | Attitude estimation from IMU streams over UDP using Kalman and complementary filters, with live 3D view | C++17, Kalman filter | [![CI](https://github.com/bekirhankarakurt/imu-kalman-attitude/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/imu-kalman-attitude/actions/workflows/ci.yml) |
| [nmea-gps-logger](https://github.com/bekirhankarakurt/nmea-gps-logger) | NMEA 0183 parser, track logger and geofence monitor with GPX/GeoJSON export | C++17, NMEA 0183 | [![CI](https://github.com/bekirhankarakurt/nmea-gps-logger/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/nmea-gps-logger/actions/workflows/ci.yml) |

### Sensors, Radar & Vision

| Project | What it does | Key tech | CI |
|---|---|---|---|
| [radar-signal-processing-sim](https://github.com/bekirhankarakurt/radar-signal-processing-sim) | Pulse-Doppler radar simulator: LFM pulse compression, Doppler FFT, CA/OS-CFAR detection | C++17, DSP, FFT | [![CI](https://github.com/bekirhankarakurt/radar-signal-processing-sim/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/radar-signal-processing-sim/actions/workflows/ci.yml) |
| [vision-target-tracker](https://github.com/bekirhankarakurt/vision-target-tracker) | Real-time visual target tracker for gimbal control: correlation tracking, Kalman prediction, PID loop | C++17, Kalman, PID | [![CI](https://github.com/bekirhankarakurt/vision-target-tracker/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/vision-target-tracker/actions/workflows/ci.yml) |
| [can-bus-analyzer](https://github.com/bekirhankarakurt/can-bus-analyzer) | SocketCAN analyzer and traffic simulator with DBC decoding, filtering, recording and replay | C++17, SocketCAN | [![CI](https://github.com/bekirhankarakurt/can-bus-analyzer/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/can-bus-analyzer/actions/workflows/ci.yml) |

### Embedded Firmware

| Project | What it does | Key tech | CI |
|---|---|---|---|
| [stm32-freertos-sensor-node](https://github.com/bekirhankarakurt/stm32-freertos-sensor-node) | STM32 firmware with UART/I2C/SPI drivers, CRC-checked A/B bootloader and host-side tests | C, FreeRTOS, STM32 | [![CI](https://github.com/bekirhankarakurt/stm32-freertos-sensor-node/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/stm32-freertos-sensor-node/actions/workflows/ci.yml) |
| [esp32-air-quality-station](https://github.com/bekirhankarakurt/esp32-air-quality-station) | ESP32 temperature, humidity and CO2 station streaming CRC-protected UDP telemetry, with host simulator | C++17, ESP-IDF | [![CI](https://github.com/bekirhankarakurt/esp32-air-quality-station/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/esp32-air-quality-station/actions/workflows/ci.yml) |

### Real-time & Networking

| Project | What it does | Key tech | CI |
|---|---|---|---|
| [lite-dds-pubsub](https://github.com/bekirhankarakurt/lite-dds-pubsub) | Minimal DDS-style pub/sub middleware over UDP multicast with discovery and QoS | C++17, UDP multicast | [![CI](https://github.com/bekirhankarakurt/lite-dds-pubsub/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/lite-dds-pubsub/actions/workflows/ci.yml) |
| [reliable-udp-transfer](https://github.com/bekirhankarakurt/reliable-udp-transfer) | Reliable UDP file transfer with sliding window, selective ACK, congestion control and integrity checks | C++17, UDP | [![CI](https://github.com/bekirhankarakurt/reliable-udp-transfer/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/reliable-udp-transfer/actions/workflows/ci.yml) |
| [rt-latency-bench](https://github.com/bekirhankarakurt/rt-latency-bench) | Latency benchmark and scheduler lab for Linux: SCHED_FIFO, CPU pinning, histograms | C++17, Linux RT | [![CI](https://github.com/bekirhankarakurt/rt-latency-bench/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/rt-latency-bench/actions/workflows/ci.yml) |
| [lockfree-containers](https://github.com/bekirhankarakurt/lockfree-containers) | Header-only lock-free SPSC/MPMC queues and ring buffers, benchmarked and TSan-verified | C++17, atomics | [![CI](https://github.com/bekirhankarakurt/lockfree-containers/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/lockfree-containers/actions/workflows/ci.yml) |
| [embedded-telemetry-daemon](https://github.com/bekirhankarakurt/embedded-telemetry-daemon) | Linux telemetry daemon: /proc collectors, rolling log, live UDP downlink, no external dependencies | C++17, Linux | [![CI](https://github.com/bekirhankarakurt/embedded-telemetry-daemon/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/embedded-telemetry-daemon/actions/workflows/ci.yml) |
| [telemetry-tui-dashboard](https://github.com/bekirhankarakurt/telemetry-tui-dashboard) | Terminal dashboard with live charts from the telemetry daemon's UDP downlink | Rust, ratatui | [![CI](https://github.com/bekirhankarakurt/telemetry-tui-dashboard/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/telemetry-tui-dashboard/actions/workflows/ci.yml) |
| [embedded-http-server](https://github.com/bekirhankarakurt/embedded-http-server) | Zero-dependency HTTP/1.1 server for device configuration panels and REST APIs | C++17, sockets | [![CI](https://github.com/bekirhankarakurt/embedded-http-server/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/embedded-http-server/actions/workflows/ci.yml) |
| [process-watchdog](https://github.com/bekirhankarakurt/process-watchdog) | Process supervisor with heartbeats, restart policies and health reporting | C++17, Linux | [![CI](https://github.com/bekirhankarakurt/process-watchdog/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/process-watchdog/actions/workflows/ci.yml) |
| [home-network-ids](https://github.com/bekirhankarakurt/home-network-ids) | Intrusion detection: port-scan, ARP-spoofing and rogue-device detection from raw sockets or pcap | Rust | [![CI](https://github.com/bekirhankarakurt/home-network-ids/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/home-network-ids/actions/workflows/ci.yml) |
| [protocol-codegen](https://github.com/bekirhankarakurt/protocol-codegen) | Schema-to-code generator: C++ serializers with CRC framing and Wireshark Lua dissectors | C++17, Lua | [![CI](https://github.com/bekirhankarakurt/protocol-codegen/actions/workflows/ci.yml/badge.svg)](https://github.com/bekirhankarakurt/protocol-codegen/actions/workflows/ci.yml) |

</details>

### 🔧 How every project is built

| | |
|---|---|
| ✅ Warnings-as-errors builds, GCC + Clang | 🧪 ASan / UBSan / TSan in CI |
| 🔍 CodeQL, cppcheck, clang-tidy | 📊 Coverage reports + API docs on Pages |
| 📦 Versioned releases with SHA256SUMS | 🎮 Simulation & replay modes — runs without hardware |

### 📈 Stats

<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=bekirhankarakurt&theme=tokyonight" alt="Profile summary" />
</p>
<p align="center">
  <img height="170" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=bekirhankarakurt&theme=tokyonight" alt="Repos per language" />
  <img height="170" src="https://streak-stats.demolab.com?user=bekirhankarakurt&theme=tokyonight&hide_border=true" alt="Streak" />
</p>

### 🚧 Currently working on

MIL-STD-1553 & ARINC 429 avionics buses · MISB KLV video metadata · 6-DOF flight simulation

<div align="center"><sub>Bekirhan Karakurt · <a href="https://github.com/bekirhankarakurt">github.com/bekirhankarakurt</a></sub></div>
