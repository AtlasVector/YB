## Introduction
While this is not my first home server, it is my first lab built with a clear focus on security operations. As a hobby, I have previously run a small personal home lab for **home automation and self-hosted services,** which helped me build a solid foundation in Linux, networking, and troubleshooting.

I later built my first dedicated cybersecurity lab using VMware Fusion on a Windows host. That environment was essential for turning theory into practice, but as the lab grew I began to hit hardware limitations, particularly around RAM usage and scalability.

To remove those constraints and enable further experimentation, I decided to rebuild the lab on **Proxmox VE**. Rather than migrating the existing environment, I chose to start over, using the opportunity to apply what I had learned and intentionally face new technical challenges.

## Lab Goals
The primary goal of this lab is to create a learning environment where encountering problems is expected and encouraged. Instead of avoiding complexity, the lab is designed to introduce new challenges that require investigation, experimentation, and hands-on problem solving.

The lab emphasizes:
- Learning through troubleshooting and experimentation  
- Facing unfamiliar technical challenges  
- Validating ideas and assumptions by testing and observation  

This approach creates continuous opportunities to build understanding and confidence by solving real problems rather than following predefined paths.

---

## Environment Overview
The lab is hosted on a single Proxmox VE node and is composed of multiple virtual machines with clearly defined responsibilities. Services are intentionally separated to support troubleshooting, safe experimentation, and easier understanding of system behavior.
#### The environment includes:
- Network routing and control
- Segmented internal networks
- Traffic monitoring and inspection
- Centralized logging and analysis
- Windows-based infrastructure
- A testing/attacker host for experimentation

<img src="/Personal%20Projects/resources/Lab-Environment.png" />


## Infrastructure & Virtualization

The lab is hosted on a single Proxmox VE node, chosen to provide better resource management and flexibility compared to previous setups. Running the environment  allows efficient use of system resources while making it easier to add, remove, or rebuild virtual machines as the lab evolves.

This setup supports learning by:
- Allowing rapid creation and rollback of virtual machines using snapshots.
- Encouraging experimentation without long term impact.
- Making infrastructure changes visible and reversible to open new learning opportunities.  

<img src="/Personal%20Projects/resources/PVE-node.png" />

