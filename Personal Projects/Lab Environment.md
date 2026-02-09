## 1. Purpose

This repository documents a personal cybersecurity lab designed to replicate the **technical and operational realities of a small enterprise environment**, with a specific focus on **SOC operations, detection engineering, and log-driven investigations**.

Rather than optimizing for tooling breadth, the lab prioritizes:
- End-to-end **telemetry visibility**
- Understanding **where data is lost or distorted**
- Solving **real operational failures**
- Making monitoring **persistent, debuggable, and explainable**

The lab is intentionally built and documented through **iteration, failure, and correction**, mirroring how production SOC environments actually evolve.

---

## 2. High-Level Architecture
<img src="/Personal%20Projects/resources/Lab-Environment.png" />


**Core components**
- Proxmox VE hypervisor
- pfSense firewall and inter-VLAN router
- Linux bridge networking (no OVS)
- Dedicated Suricata IDS sensor
- Windows Server & Workstation endpoints
- Elastic Stack for centralized logging
- Kali Linux for controlled attack simulation

  

---