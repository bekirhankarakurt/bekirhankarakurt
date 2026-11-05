## Hi, I'm Bekirhan 👋

Embedded and real-time software developer. I build things that run close to the hardware:
firmware, Linux system services, networking stacks and signal-processing pipelines, mostly in
modern C++ (C++17), plus some C and Rust.

**Focus areas:** embedded Linux · RTOS firmware · UAV / avionics software · real-time networking ·
signal processing · performance and concurrency

### Featured projects

| Project | What it is |
|---|---|
| [radar-signal-processing-sim](https://github.com/bekirhankarakurt/radar-signal-processing-sim) | Pulse-Doppler radar simulator: LFM pulse compression, Doppler FFT and CA/OS-CFAR detection |
| [mavlink-ground-station](https://github.com/bekirhankarakurt/mavlink-ground-station) | Lightweight MAVLink ground control station: live telemetry, mission upload, tested against PX4 SITL |
| [stm32-freertos-sensor-node](https://github.com/bekirhankarakurt/stm32-freertos-sensor-node) | STM32 + FreeRTOS firmware with UART/I2C/SPI drivers and a CRC-checked A/B bootloader |
| [lockfree-containers](https://github.com/bekirhankarakurt/lockfree-containers) | Header-only lock-free SPSC/MPMC queues and ring buffers, benchmarked and TSan-verified |
| [flight-data-recorder](https://github.com/bekirhankarakurt/flight-data-recorder) | Power-loss tolerant black box with CRC-framed append-only storage and replay tooling |
| [can-bus-analyzer](https://github.com/bekirhankarakurt/can-bus-analyzer) | SocketCAN analyzer and traffic simulator with DBC decoding, recording and replay |

<details>
<summary><b>More projects</b></summary>

- **UAV & navigation:** [uav-mission-planner](https://github.com/bekirhankarakurt/uav-mission-planner) (A*, RRT*, terrain-aware) ·
  [vision-target-tracker](https://github.com/bekirhankarakurt/vision-target-tracker) (Kalman + PID gimbal tracking) ·
  [imu-kalman-attitude](https://github.com/bekirhankarakurt/imu-kalman-attitude) ·
  [nmea-gps-logger](https://github.com/bekirhankarakurt/nmea-gps-logger) ·
  [adsb-aircraft-tracker](https://github.com/bekirhankarakurt/adsb-aircraft-tracker)
- **Networking & middleware:** [lite-dds-pubsub](https://github.com/bekirhankarakurt/lite-dds-pubsub) ·
  [reliable-udp-transfer](https://github.com/bekirhankarakurt/reliable-udp-transfer) ·
  [embedded-http-server](https://github.com/bekirhankarakurt/embedded-http-server) ·
  [protocol-codegen](https://github.com/bekirhankarakurt/protocol-codegen) (C++ serializers + Wireshark dissectors)
- **Linux systems:** [embedded-telemetry-daemon](https://github.com/bekirhankarakurt/embedded-telemetry-daemon) ·
  [telemetry-tui-dashboard](https://github.com/bekirhankarakurt/telemetry-tui-dashboard) ·
  [process-watchdog](https://github.com/bekirhankarakurt/process-watchdog) ·
  [rt-latency-bench](https://github.com/bekirhankarakurt/rt-latency-bench)
- **Embedded & security:** [esp32-air-quality-station](https://github.com/bekirhankarakurt/esp32-air-quality-station) ·
  [home-network-ids](https://github.com/bekirhankarakurt/home-network-ids) (Rust)

</details>

### Tools

C++17 · C · Rust · CMake · FreeRTOS · STM32 · ESP32 · Linux (SocketCAN, real-time scheduling) ·
MAVLink / PX4 · GitHub Actions · clang-tidy · sanitizers
