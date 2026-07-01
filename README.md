# IoT-Based Smart Indoor Air Quality Monitoring and Alert System

An end-to-end cloud-integrated Internet of Things (IoT) solution designed to continuously monitor indoor air quality, provide real-time dashboards, and execute edge-to-cloud automated remediation via smart infrastructure. Developed as an academic term project at **King Mongkut's University of Technology Thonburi (KMUTT)**.

## 🚀 Project Overview

Indoor Air Quality (IAQ) directly impacts human health, comfort, and cognitive performance. This project establishes an automated, closed-loop telemetry and remediation ecosystem. By reading environmental markers (CO2 and PM2.5 particulate levels) at the edge, transmitting metrics securely via a lightweight publish-subscribe network protocol to a cloud virtual machine, and employing a flow-based orchestration engine, the system actively mitigates hazardous indoor environments without human intervention.

### Key Capabilities
* **Continuous Edge Telemetry:** Multi-sensor collection of carbon dioxide concentration and fine particulate matter without manual sampling.
* **Cloud-Native Infrastructure:** Remote data aggregation, broker processing, and hosting via Google Cloud Platform (GCP) Compute Engine.
* **Automated Closed-Loop Mitigation:** Intelligent threshold logic drives a smart actuator to control standard consumer appliances, skipping the constraints of closed proprietary APIs.
* **Real-Time Data Visualization:** Color-coded dashboards with historical trend tracking for data analysis and hazard reporting.

---

## 🏗️ System Architecture & Data Flow

The architecture operates on a linear telemetry and control loop split across the physical edge, a cloud middleware broker, and responsive smart infrastructure.
