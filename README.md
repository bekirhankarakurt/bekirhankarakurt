# İsmet Bekirhan Karakurt

**Embedded & real-time systems engineer — avionics links, sensor fusion, radar/vision, UAV software**

I work at a robotics company on Jetson, ESP32 and Raspberry Pi platforms with lidar and sonar sensors, and build open-source embedded and real-time software in my own time. I am targeting defense and aerospace software roles.

### What I build

- **Avionics and UAV software:** MAVLink ground control, mission planning, ADS-B decoding, flight data recording, attitude estimation.
- **Sensor processing:** radar signal processing, visual target tracking, CAN bus analysis.
- **Embedded firmware:** STM32 + FreeRTOS and ESP32 nodes with bootloaders, drivers and host-side tests.
- **Real-time systems and networking:** lock-free data structures, DDS-style middleware, reliable UDP, latency benchmarking.

## Tech stack

![C++17](https://img.shields.io/badge/C%2B%2B-17-00599C?logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-4C9A2A)
![STM32](https://img.shields.io/badge/STM32-03234B?logo=stmicroelectronics&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?logo=espressif&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

## Featured projects

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

## Engineering practices across all projects

- Warnings-as-errors builds on every CI run
- Sanitizers (ASan/UBSan, TSan for concurrent code)
- CodeQL static analysis and Dependabot updates
- Code coverage reporting and published API docs
- Reproducible releases with SHA256SUMS
- Simulation and replay modes, so everything runs without hardware

## GitHub stats

<p>
  <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=bekirhankarakurt&show_icons=true&hide_border=true&theme=default&count_private=false" />
  <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bekirhankarakurt&layout=compact&hide_border=true&theme=default" />
</p>

## Currently working on

Avionics data buses, MISB KLV metadata and 6-DOF flight simulation.

---

[github.com/bekirhankarakurt](https://github.com/bekirhankarakurt)
