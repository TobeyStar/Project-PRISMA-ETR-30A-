# 🌈 PROJECT PRISMA

[![License: CC BY-SA 4.0](https://img.shields.org/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Hardware: Open-Source](https://img.shields.org/badge/Hardware-Open--Source-blue.svg)](#)
[![Status: Experimental](https://img.shields.org/badge/Status-Experimental--Hypothesis-orange.svg)](#)

**Project PRISMA** (*Precision Refractive Interface for Solid-State Vacuum Manifestation Architecture*) is an open-source hardware specification based on theoretical physics and material science synthesis of zero-point energy (ZPE) harvesting systems.

---

## 💎 The PRISMA Principle: Quantum Vacuum Refraction

In classical optics, a pure glass prism receives **unformed white light**—a chaotic blend of all frequencies—and refracts it into a structured, coherent spectrum of visible light.

Project PRISMA applies this mechanism to quantum vacuum electrodynamics:

The zero-point energy (ZPE) field represents an unformed baseline of ultra-high frequency vacuum fluctuations (Terahertz to Planck scales). Positioned at the geometric vortex center of an asymmetric toroidal winding is an anisotropic **pure synthetic $\alpha$-quartz crystal** ($\alpha\text{-SiO}_2$). 

This core acts as a **Harmonic Step-Down Transformer**: through non-linear phononic interactions and inverse piezoelectric coupling, it intercepts chaotic, high-frequency ZPE modes and refracts them down into lower, coherent, and usable electromagnetic oscillations.

---

## 📐 Core Architecture & System Topology

+-----------------------------------+
|      Toroidal Core Substrate      |
+-----------------------------------+
|
+-----------------------+-----------------------+
|                                               |
v                                               v
+-------------------+                           +-------------------+
| Bimetallic Wire   |                           | Bimetallic Wire   |
| (Cu Bulk Core /   |                           | (Cu Bulk Core /   |
|  Ag Cladding)     |                           |  Ag Cladding)     |
| 30° Vector Angle  |                           | 30° Vector Angle  |
+-------------------+                           +-------------------+
\                                               /
--> [ Geometric Field Asymmetry: B ≈ 0 ] <--/
|
v
+---------------------------------+
|    THE QUANTUM PRISMA CORE      |
| Anisotropic Pure α-Quartz Core  |
| (Optical c-axis aligned)        |
+---------------------------------+
|
[ Inverse Piezoelectric Lock ]
|
[ Coherent Energy Harvest ]

---

## 🗝️ Key Technical Foundations (From Research)

1. **Anisotropic Alpha-Quartz Core ($\alpha\text{-SiO}_2$):**  
   Positioned at the geometric vortex center with its optical/electrical c-axis aligned with the toroidal vortex vector. Functions as a high-Q piezoelectric frequency stabilizer and non-linear phononic step-down resonator.

2. **$30^\circ$ Vortex Vector Windings:**  
   Coil conductors are wrapped through the central aperture at an angle $30^\circ$ short of a direct radial cross-section. This forces electrons along the path of minimum reluctance, minimizing back-EMF and collapsing radiated magnetic fields ($B \approx 0$) to form an **anapole state** with a non-zero magnetic vector potential ($\mathbf{A}$).

3. **Cu-Ag Bimetallic Skin-Effect Optimization:**  
   Pairs a high-conductivity copper core ($401\text{ W/m}\cdot\text{K}$) for thermal dissipation and magnetic grounding with an ultra-pure silver surface cladding ($1\text{--}10\ \mu\text{m}$). High-frequency currents route through the silver skin layer, eliminating $I^2R$ ohmic heating losses.

4. **Dynamic High-Voltage Pulse Drive:**  
   Utilizes high-voltage AC pulse excitation ($10\text{ kV} - 30\text{ kV}$) swept across resonance frequencies ($10\text{ kHz} - 1\text{ MHz}$) to induce localized vacuum polarization and harvest net power.

---

## 🗂️ Repository Structure

* 📄 **[`docs/01_THEORY.md`](docs/01_THEORY.md)** – Quantum Vacuum Refraction, Anapole States, Topological Insulators, and Non-Hertzian Waves.
* 📄 **[`docs/02_HARDWARE_BOM.md`](docs/02_HARDWARE_BOM.md)** – Material Specifications (Cu-Ag Bimetallic, Alpha-Quartz, Toroidal Cores).
* 📄 **[`docs/03_CIRCUITRY.md`](docs/03_CIRCUITRY.md)** – High-Voltage Pulse Generator, Frequency Sweep Controllers, and Harvesting Diodes.
* 📄 **[`docs/04_TEST_PROTOCOL.md`](docs/04_TEST_PROTOCOL.md)** – Laboratory Setup, Vector Potential Measurement, and Faraday Cage Validation.

---

## ⚡ Core Technical Parameters

| Parameter | Specification | Source Grounding |
| :--- | :--- | :--- |
| **Project Codename** | **PRISMA** | Open-source concept |
| **Core Material** | Pure Synthetic $\alpha$-Quartz ($\alpha\text{-SiO}_2$) | Aligned along optical c-axis |
| **Winding Geometry** | Counter-rotating $30^\circ$ helical windings | Minimizes back-EMF & reluctance |
| **Conductor Composition** | Bimetallic Copper Core + Silver Cladding | $1\text{--}10\ \mu\text{m}$ Ag skin layer |
| **Field Dynamics** | Anapole State ($B \approx 0$, $\mathbf{A} \neq 0$) | Aharonov-Bohm active potential |
| **Excitation Range** | $10\text{ kHz} - 1\text{ MHz}$ (Swept) / $10\text{--}30\text{ kV}$ | High-voltage AC pulse drive |
| **Harvesting Yield** | Scalable ($20\text{ mW} - 2.5\text{ W}$ baseline test) | Diode bridge to capacitors |

---

## 📜 License

This work is licensed under a **[Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**.
