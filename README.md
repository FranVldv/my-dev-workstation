# My Development Workstation & Hardware Architecture

This repository documents the technical specifications of my custom-built workstation, designed to handle intensive workflows in **Full Stack Development (NestJS/TypeScript)** and the **execution/training of local AI models**.

## 🛠️ Build Specifications
I personally assembled and optimized this rig, achieving a balance between multi-threaded processing power, massive memory capacity, and efficient thermal management.

### Core Components:
* **Processor (CPU):** **AMD Ryzen 7 5700G** (8 Cores / 16 Threads). 
    * *Rationale:* Ideal for parallelizing tasks, running multiple microservices, and Docker containers simultaneously without performance degradation.
* **RAM:** **48GB DDR4**.
    * *Rationale:* Extended capacity for complex development environments requiring multiple VS Code instances, memory-heavy browsers, and demanding local databases.
* **Graphics (GPU):** **Sapphire AMD Radeon RX 6700 XT (12GB VRAM)**.
    * *Rationale:* The 12GB of VRAM allows for loading and testing Large Language Models (LLMs) and Stable Diffusion locally for rapid prototyping.
* **Storage (3-Tier Architecture):**
    1.  **NVMe M.2 (1TB):** Main drive for OS and active projects (maximum read/write speeds).
    2.  **SSD SATA (1TB):** High-speed storage for libraries and dependencies (node_modules, docker images).
    3.  **HDD (512GB):** Local backup and static assets.
* **Cooling:** Air cooling system + optimized airflow with a **6-fan setup** and unified control system.
    * *Rationale:* Guaranteed thermal stability under 100% workloads (massive compilation or rendering).

## 🖥️ Demonstrated Hardware Skills
- **Full Assembly:** High-end hardware assembly and cable management.
- **Thermal Optimization:** Fan curve configuration and positive pressure airflow management.
- **Maintenance:** Hardware diagnostics, BIOS updates, and periodic preventive maintenance.

## 💡 Technical Philosophy
Understanding hardware architecture (such as NVMe latency or Ryzen 7 thread management) allows me to write more efficient code, optimizing resource usage and improving the overall quality of the software I develop.
