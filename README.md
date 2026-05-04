# <p align="center">argb-ai Protocol Specification</p>

<p align="center">
  <strong>Defining the Language of Light for the AI Era.</strong>
</p>

---

## 📖 Overview

The **argb-ai specification** is a vendor-neutral, open standard for high-performance lighting control. It is designed to bridge the gap between **Large Language Models (LLMs)** and physical hardware, enabling **Intent-Driven** lighting orchestration.

Unlike traditional lighting protocols, `argb-ai` treats light as a dynamic data stream, capable of expressing both functional utility and emotional ambience.

## 🎯 Core Domains

To ensure optimal user experience and hardware performance, the protocol distinguishes between two primary operational domains:

### 1. Functional Domain (`functional`)
* **Focus:** Human-centric lighting, eye protection, and utility.
* **Parameters:** CCT (Correlated Color Temperature), Lux, Melatonin protection.
* **Priority:** Critical. Ensures safe and comfortable environments for tasks like coding, reading, or resting.

### 2. Ambient Domain (`ambient`)
* **Focus:** Immersion, emotional resonance, and "Vibe Coding."
* **Parameters:** ARGB Flow, Spatial Coordinates (XYZ), Real-time Synchronization.
* **Priority:** Adaptive. Synchronizes with screen content, music, or AI agent intentions.

## 🏗 Specification Structure

This repository is organized into versioned modules to ensure long-term stability and backward compatibility:

* **[`/v1/concepts.md`](./v1/concepts.md):** High-level philosophy and semantic definitions.
* **[`/v1/schema/`](./v1/schema/):** Standardized JSON models for MCP and API integration.
* **[`/v1/transport/`](./v1/transport/):** Physical layer definitions, including our custom Serial Protocol for hardware identification.
* **[`/v1/addressing.md`](./v1/addressing.md):** Pixel-level topology and spatial mapping standards.

## 🤖 AI-Native Integration

The protocol is built from the ground up to be **Agent-friendly**. By exposing lighting as a structured "Tool" via the **Model Context Protocol (MCP)**, AI agents can perceive and manipulate the physical environment with sub-millisecond precision.

---

## 🛠 Status: Draft v0.1.0

This specification is currently in the **Draft** phase. We welcome contributions from hardware manufacturers, software developers, and AI researchers.

<p align="center">
  Maintained by the <strong>Skydimo</strong> Engineering Team.<br>
  <em>Built with ❤️ for the future of ambient intelligence.</em>
</p>
