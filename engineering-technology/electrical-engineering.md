---
domain: engineering-technology
subdomain: electrical-engineering
title: "Electrical Engineering"
description: "The engineering of electrical systems, electronics, and electromagnetism"
created: 2026-05-15
updated: 2026-05-15
tags: [circuits, electronics, signals, power, control systems, semiconductors, RF, embedded]
prerequisites: [physics, mathematics]
related: [engineering-technology/computer-science, natural-sciences/physics]
difficulty: introductory
completeness: comprehensive
---

# Electrical Engineering

## Overview

Electrical engineering is the branch of engineering that deals with the study, design, and application of equipment, devices, and systems that use electricity, electronics, and electromagnetism. It spans power systems, electronics, signal processing, control systems, and telecommunications.

## Core Concepts

### Circuit Theory
- **Ohm's Law**: V = IR; voltage, current, resistance
- **Kirchhoff's Laws**: KCL (current), KVL (voltage); nodal and mesh analysis
- **AC/DC Circuits**: Alternating vs direct current; RMS values; power (P = IV)
- **Impedance**: Resistance, capacitance, inductance in AC; phasors; complex impedance
- **Thevenin/Norton Equivalents**: Simplifying circuits
- **Resonance**: LC circuits; frequency response; bandwidth
- **Filters**: Low-pass, high-pass, band-pass, band-stop

### Electronics
- **Semiconductors**: Diodes, transistors (BJT, MOSFET); doping; PN junctions
- **Amplifiers**: Common emitter/source; gain, bandwidth, feedback
- **Operational Amplifiers**: Inverting, non-inverting, summing, integrator, differentiator
- **Digital Logic**: AND, OR, NOT, NAND, NOR, XOR; Boolean algebra; logic gates
- **Flip-Flops & Registers**: SR, JK, D flip-flops; shift registers; counters
- **Microprocessors/Microcontrollers**: CPU architecture; memory; I/O; embedded systems

### Signal Processing
- **Analog Signals**: Continuous-time; Fourier series; frequency spectrum
- **Digital Signals**: Sampling (Nyquist theorem); quantization; ADC/DAC
- **Fourier Transform**: Time domain → frequency domain; DFT, FFT
- **Filters (Digital)**: FIR, IIR; convolution; Z-transform
- **Signal-to-Noise Ratio**: SNR; noise sources; noise figure
- **Modulation**: AM, FM, PM; QAM; spread spectrum

### Power Systems
- **Generation**: Thermal, hydro, nuclear, wind, solar; generators
- **Transmission**: High-voltage AC/DC; transformers; power loss minimization
- **Distribution**: Grid architecture; substations; smart grids
- **Power Electronics**: Inverters, rectifiers, converters; switching power supplies
- **Renewable Energy**: Solar cells, wind turbines, energy storage (batteries, supercapacitors)
- **Power Quality**: Harmonics; power factor correction; voltage regulation

### Control Systems
- **Open-Loop vs Closed-Loop**: Feedback control
- **Transfer Functions**: Laplace domain; block diagrams; signal flow graphs
- **Stability**: Routh-Hurwitz; root locus; Bode plots; Nyquist criterion
- **PID Controllers**: Proportional-Integral-Derivative; tuning methods
- **State-Space Methods**: State variables; controllability; observability
- **Digital Control**: Discrete-time systems; z-transform

### Electromagnetics
- **Maxwell's Equations**: Foundation of electromagnetics
- **Wave Propagation**: EM waves; reflection, refraction, diffraction
- **Antennas**: Radiation patterns; gain; impedance matching; array antennas
- **Transmission Lines**: Impedance matching; standing waves; Smith chart
- **Microwave Engineering**: Waveguides, cavity resonators, radar

### Telecommunications
- **Communication Systems**: Transmitter, channel, receiver; Shannon limit
- **Digital Communications**: ASK, FSK, PSK, QAM; error detection/correction
- **Wireless**: Cellular (4G/5G), WiFi, Bluetooth, satellite, radio
- **Fiber Optics**: Total internal reflection; single-mode, multi-mode; WDM

## Key Theories

| Theory | Description |
|--------|-------------|
| Maxwell's Equations | Unify electricity, magnetism, and optics |
| Nyquist-Shannon Theorem | Minimum sampling rate = 2× highest frequency |
| Shannon-Hartley Theorem | Channel capacity = B × log₂(1 + S/N) |
| Fourier Analysis | Any signal can be decomposed into sinusoids |
| Control Theory | Feedback systems stability and performance analysis |

## Important Figures

- **Nikola Tesla**: AC power systems; induction motor
- **Thomas Edison**: DC power; phonograph; light bulb
- **James Clerk Maxwell**: Electromagnetic theory
- **Claude Shannon**: Information theory; digital circuit design
- **Heinrich Hertz**: Radio waves; confirmed Maxwell's theory
- **Jack Kilby / Robert Noyce**: Integrated circuit invention

## Frontiers

- **Beyond-CMOS Electronics**: Exploring tunnel FETs, spintronics, and 2D materials (MoS2, graphene transistors) as silicon scaling reaches physical limits
- **Wireless Power Transfer**: Efficient mid-range and long-range energy transmission for EVs, implants, and IoT devices
- **Terahertz Gap**: Bridging the frequency range between microwave and infrared for imaging, communications, and sensing applications
- **Ultra-Low-Power Design**: Harvesting ambient energy and designing circuits that operate at near-threshold voltages for billions of IoT nodes
- **6G and Beyond**: Sub-THz communication, intelligent reflecting surfaces, and integrated sensing-communication architectures

## Applications

- **Consumer Electronics**: Smartphones, computers, displays, audio systems
- **Power Industry**: Grid design, renewable energy integration, EV charging
- **Telecommunications**: 5G networks, satellite communications, fiber optic systems
- **Automotive**: Electric vehicles, ADAS, engine control units
- **Aerospace**: Avionics, radar, satellite systems, spacecraft electronics
- **Medical Devices**: MRI, EEG, pacemakers, ultrasound

## Classic Works

- **"The Art of Electronics"** by Horowitz & Hill — The gold standard for practical circuit design; teaches intuition for analog and digital electronics
- **"Signals and Systems"** by Oppenheim & Willsky — Foundational text on signal processing, Fourier analysis, and system theory
- **"Microelectronic Circuits"** by Sedra & Smith — Comprehensive treatment of semiconductor devices and amplifier design
- **"Power Electronics"** by Mohan, Undeland & Robbins — Essential reference for converters, inverters, and motor drives
- **"Control Systems Engineering"** by Nise — Accessible yet thorough introduction to feedback control, root locus, and state-space methods

## See Also

- [Computer Science](./computer-science.md) — Digital systems, embedded programming
- [Physics](../natural-sciences/physics.md) — Electromagnetism fundamentals
- [Aerospace Engineering](./aerospace-engineering.md) — Avionics, guidance systems
- [Biomedical Engineering](./biomedical-engineering.md) — Medical electronics
