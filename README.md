# Hostel-Network-Infrastructure
Enterprise-grade ISP infrastructure utilizing a 16-core MikroTik CCR2116-12G-4S+ router along with WiFi 7 APs to deliver managed high-speed internet to 100+ concurrent clients, generating $9,500+ every year in contractual revenue via custom remote WinBox telemetry."
# Enterprise-Scale Residential ISP Deployment & Telemetry

A production-grade network engineering portfolio detailing the architecture, automated traffic management, and remote monitoring systems implemented to support an active multi-user infrastructure. 

This project operates as a fully commercialized deployment, providing reliable, high-speed internet to over 100 concurrent endpoints under structured Service Level Agreements (SLAs), generating over $9,500 (110,000+ GHS) in contractual revenue.

## 🛠️ Core Infrastructure & Hardware
* **Edge Routing Platform:** MikroTik CCR2116-12G-4S+ Cloud Core Router
  * *Specs Utilized:* 16-Core ARM CPU @ 2GHz, 16GB DDR4 RAM, Layer 3 Hardware Offloading via Marvell Prestera switch-chip.
* **Core Distribution:** High-throughput 10G SFP+ fiber uplinks paired with multi-floor managed Access Point matrices.
* **Power Architecture:** Dual-redundant hot-swappable power supplies integrated into a dedicated UPS/Inverter failover grid for 99.9% uptime.

## ⚙️ Key System Implementations

### 1. High-Density Traffic Engineering & QoS
Utilizing the 16-core processing power and Layer 3 Hardware Offloading of the CCR2116, the network processes heavy parallel connection tracking states without CPU degradation. 
* Implemented **Per Connection Queueing (PCQ)** and granular firewall mangle rules to eliminate bufferbloat and guarantee dynamic, equitable bandwidth distribution during peak saturation.
* Configured isolated VLANs and strict subnetting protocols to separate subscriber traffic and ensure bulletproof local network security.

### 2. Custom Web-Based Remote Management Telemetry
To maintain operational efficiency while managing full-time academic and software development schedules, I designed and deployed a custom remote accessibility pipeline.
* Built a secure, web-enabled remote gateway allowing real-time, encrypted access to the core router’s **WinBox API/Terminal**.
* Engineered remote telemetry monitoring for instant configuration adjustments, traffic analysis, and hot-swappable client management from any location worldwide.

## 💼 SLA & Business Operations Management
* **Contractual Execution:** Orchestrated and signed binding service agreements defining legal infrastructure access, tier-based billing rules, and guaranteed performance metrics.
* **Subscriber Lifecycle:** Integrated an automated captive portal authentication and voucher provisioning matrix to minimize operational overhead and handle user onboarding completely hands-free.