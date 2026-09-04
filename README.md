# GM-Copilot Studios
*Deterministic TTRPG Ingestion Architecture*  
*Live Storefront:* [GM-Copilot Studios](https://cmccombs01.github.io/GM-Copilot-Studios.github.io/)

## Executive Summary
GM-Copilot Studios provides a B2B, zero-hallucination ingestion pipeline designed to eliminate manual data entry for Tabletop Roleplaying Game (TTRPG) publishers. We convert legacy and print PDF rulebooks into verified JSON architectures and ready-to-play module bundles for Virtual Tabletop (VTT) platforms like Foundry VTT and Roll20.

## Core Architecture
Unlike generative AI wrappers that hallucinate stats, our pipeline operates deterministically:
* **Spatial Invariant Isolation (OpenCV):** Isolates bounding boxes, multi-column document flows, maps, and tables to eliminate text-wrap and layout bugs.
* **Formal Verification (Lean 4 & Pydantic):** Mathematical logic gates enforce strict structural invariants, verifying action economies, modifiers, and stat blocks before compilation.
* **Stateless FinOps Infrastructure:** Runs on an isolated Azure environment with zero-cost Redis caching. PDF payloads are processed in-memory and purged immediately for complete IP isolation.

## Volume Conversion Tiers

| Package | Scope | Turnaround | Key Deliverables |
| :--- | :--- | :--- | :--- |
| **Free 1-Page Audit** | 1 Page ($0) | 10 Minutes | Spatial audit + sample Foundry VTT JSON |
| **Starter Adventure** | Up to 15 Pages ($49) | 24 Hours | One-shots, monster rosters, Foundry & Roll20 JSON |
| **Indie Zine Pack** | Up to 30 Pages ($79) | 24 Hours | Stat block & item verification, full exports |
| **Core Rulebook** | Up to 150 Pages ($229) | 48 Hours | Custom actor schema mapping, action economies, tables |
| **Campaign Studio** | Up to 400 Pages ($499) | Priority Queue | Multi-PDF support, complete .zip module packaging |
| **Enterprise Vault** | Up to 1,000 Pages ($999) | Custom SLA | Catalog backlist ingestion, dedicated Azure pipeline |

## Deliverables
Every completed project delivers:
* **Foundry VTT Module (`.zip`):** Ready to drop into active instances with registered Actor, Item, and Journal packs.
* **Roll20 & Schema-Validated JSON:** Clean structured payloads matching target character sheets.
* **Extracted Visual Handouts:** Spatially cropped maps, handouts, and illustrations linked to journals.
* **Formal Verification Manifest:** SHA-256 signed audit report verifying mathematical invariants.

---
© 2026 GM-Copilot Studios. All rights reserved. | Federal UEI: FPADLBNEN6G1
