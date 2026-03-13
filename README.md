---
title: "IoT Systems - Collaboration Guide"
description: "Contributing guide for IoT Systems course content"
tableOfContents: true
sidebar:
  order: 999
---

# IoT Systems

![Build](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors Welcome](https://img.shields.io/badge/contributors-welcome-orange)

A hands-on course covering IoT architecture from protocol selection through production monitoring. You will build secure MQTT pipelines, real-time dashboards, and a complete edge-to-cloud system.

## Lessons

| # | Title |
|---|-------|
| 1 | IoT Architecture and Protocol Comparison |
| 2 | MQTT Broker Setup and Secure Connections |
| 3 | MQTT Clients on ESP32 Pico and STM32 |
| 4 | Real-Time Dashboards and Data Visualization |
| 5 | REST APIs Webhooks and Device Integration |
| 6 | Alerts Automation and Rule Engines |
| 7 | Device Security TLS and Provisioning |
| 8 | Production IoT Monitoring System |

## File Structure

```
iot-systems/
├── lesson-0.mdx        # Course introduction
├── lesson-1.mdx        # IoT Architecture and Protocol Comparison
├── lesson-2.mdx        # MQTT Broker Setup and Secure Connections
├── lesson-3.mdx        # MQTT Clients on ESP32 Pico and STM32
├── lesson-4.mdx        # Real-Time Dashboards and Data Visualization
├── lesson-5.mdx        # REST APIs Webhooks and Device Integration
├── lesson-6.mdx        # Alerts Automation and Rule Engines
├── lesson-7.mdx        # Device Security TLS and Provisioning
├── lesson-8.mdx        # Production IoT Monitoring System
└── README.md
```

## How to Contribute

1. Fork the repository: [SiliconWit/iot-systems](https://github.com/SiliconWit/iot-systems)
2. Create a feature branch: `git checkout -b feature/your-topic`
3. Make your changes and commit with a clear message
4. Push to your fork and open a Pull Request against `main`
5. Describe what you changed and why in the PR description

## Content Standards

- All lesson files use `.mdx` format
- Do not use `<BionicText>` in this course
- Code blocks should include a title attribute:
  ````mdx
  ```python title="mqtt_client.py"
  import paho.mqtt.client as mqtt
  ```
  ````
- Use Starlight components (`<Tabs>`, `<TabItem>`, `<Steps>`, `<Card>`) where appropriate
- Keep paragraphs concise and focused on practical application
- Include working code examples that readers can run directly

## Local Development

Clone the main site repository and initialize submodules:

```bash
git clone --recurse-submodules <main-repo-url>
cd siliconwit-com
npm install
npm run dev
```

To test a production build:

```bash
npm run build
```

## License

This course content is released under the [MIT License](LICENSE).
