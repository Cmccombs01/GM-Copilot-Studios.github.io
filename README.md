# GM-Copilot Studios: Deterministic TTRPG Ingestion Architecture
**Live Storefront:** [https://cmccombs01.github.io/GM-Copilot-Studios.github.io/](https://cmccombs01.github.io/GM-Copilot-Studios.github.io/)

## Executive Summary
GM-Copilot Studios provides a B2B, zero-hallucination ingestion pipeline designed to eliminate manual data entry for Tabletop Roleplaying Game (TTRPG) publishers. We specialize in converting legacy PDF rulebooks into verified JSON architectures for Virtual Tabletop (VTT) platforms like **Foundry VTT** and **Roll20**.

## Core Architecture
Unlike generative AI wrappers that hallucinate stat blocks, the Masterwork Engine utilizes a strictly deterministic approach:
* **Spatial Mapping (OpenCV):** Isolates bounding boxes, multi-column document flows, and grid topologies to prevent layout distortion and text-wrap bugs.
* **Formal Verification (Lean 4 & Pydantic):** Mathematical logic gates enforce strict structural invariants, verifying action economies, hit points, and trait tags before VTT export.
* **Stateless FinOps Infrastructure:** Built on a secure Azure VNet with zero-cost Upstash Redis caching. All PDF payloads are processed in-memory and purged immediately, ensuring absolute IP security.

## Services Offered
We provide high-volume conversion services, starting with our **$99 Pilot Extraction Structural Audit**, mapping a 5-page PDF sample into a mathematically verified VTT layout in under 3 minutes.
