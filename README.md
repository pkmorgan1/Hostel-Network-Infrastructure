# Hostel-Network-Infrastructure
Enterprise-grade ISP infrastructure utilizing a 16-core MikroTik CCR2116-12G-4S+ router along with WiFi 7 APs to deliver managed high-speed internet to 100+ concurrent clients, generating $9,500+ every year in contractual revenue via custom remote WinBox telemetry."
# Enterprise-Scale Residential ISP Deployment & Remote SaaS Telemetry

A production-grade network engineering portfolio detailing the architecture, automated billing lifecycle, and remote telemetry systems implemented to support an active multi-user residential infrastructure. 

This infrastructure operates as a fully commercialized deployment, providing reliable, high-speed internet to over 100 concurrent endpoints under structured Service Level Agreements (SLAs), generating over $9,500 (110,000+ GHS) in contractual revenue.

## 🛠️ Core Infrastructure & Cloud Architecture
* **Edge Routing Platform:** MikroTik CCR2116-12G-4S+ Cloud Core Router
  * *Specs Utilized:* 16-Core ARM CPU @ 2GHz, 16GB DDR4 RAM, Layer 3 Hardware Offloading via Marvell Prestera switch-chip.
* **Remote Management & Automation Engine:** Integrated via [NettPortal](https://nettportal.com/)
* **Core Distribution:** High-throughput 10G SFP+ fiber uplinks paired with multi-floor managed Access Point matrices.
* **Power Architecture:** Dual-redundant hot-swappable power supplies integrated into a dedicated UPS/Inverter failover grid for 99.9% uptime.

## ⚙️ Key System Implementations

### 1. Cloud-Based Remote Telemetry & MicroTik Management
To maintain flawless operations while balancing full-time academic schedules, I engineered a cloud-to-hardware pipeline using the NettPortal platform. 
* **Global Router Monitoring:** Established a secure, encrypted cloud gateway allowing remote configuration, live bandwidth tracking, and instantaneous RouterOS adjustments from any location worldwide.
* **Hands-Free Subscriber Lifecycle:** Automated the entire user creation process. When users request access, account credentials and dynamic rate limits are automatically injected into the MikroTik router via API.

### 2. High-Density Traffic Engineering & QoS
Utilizing the 16-core processing power and Layer 3 Hardware Offloading of the CCR2116, the core engine processes heavy parallel connection tracking states without CPU degradation. 
* Implemented **Per Connection Queueing (PCQ)** and granular firewall mangle rules to eliminate bufferbloat and guarantee dynamic, equitable bandwidth distribution during peak saturation.
* Configured isolated VLANs and strict subnetting protocols to separate subscriber traffic and ensure bulletproof local network security.

### 3. Automated Captive Portal & Billing Matrix
* **Automated Voucher Engine:** Configured custom captive portal templates and automated voucher generation streams, completely removing manual entry or human error from the billing loop.
* **Contractual Execution:** Orchestrated and signed binding service agreements defining legal infrastructure access, tier-based billing rules, and guaranteed performance metrics.
