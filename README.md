<link rel="me" href="https://mastodon.gamedev.place/@GMCopilot">

# GM-Copilot Studios
**Deterministic TTRPG Ingestion Architecture**

**Live Storefront:** [GM-Copilot Studios](https://cmccombs01.github.io/GM-Copilot-Studios.github.io/)

---

## Executive Summary
GM-Copilot Studios provides a B2B, zero-hallucination ingestion pipeline designed to eliminate manual data entry for Tabletop Roleplaying Game (TTRPG) publishers. We specialize in converting legacy PDF rulebooks into verified JSON architectures for Virtual Tabletop (VTT) platforms like Foundry VTT and Roll20.

## Core Architecture
Unlike generative AI wrappers that hallucinate stat blocks, the **Masterwork Engine** utilizes a strictly deterministic approach:

* **Spatial Mapping (OpenCV):** Isolates bounding boxes, multi-column document flows, and grid topologies to prevent layout distortion and text-wrap bugs.
* **Formal Verification (Lean 4 & Pydantic):** Mathematical logic gates enforce strict structural invariants, verifying action economies, hit points, and trait tags before VTT export.
* **Stateless FinOps Infrastructure:** Built on a secure Azure VNet with zero-cost Upstash Redis caching. All PDF payloads are processed in-memory and purged immediately, ensuring absolute IP security.

---

## Services Offered & Pricing Architecture
We provide flexible, flat-rate conversion packages designed to fit publisher project budgets with zero risk upfront:

### 1. Free 1-Page Structural Audit ($0)
* **Scope:** Drop in 1–2 pages of your messiest multi-column layout or complex stat block. 
* **Deliverable:** We process a spatial audit and generate verified Foundry/Roll20 JSON in under 3 minutes—no credit card required.

### 2. Zine & Short Module Pack ($49 Flat)
* **Scope:** Complete conversion for zines, pamphlets, and adventure modules up to 25 pages. 
* **Deliverable:** Includes full VTT JSON exports and Pydantic validation.

### 3. Core Rulebook & Campaign Pack ($199 Flat)
* **Scope:** Comprehensive ingestion for full settings and core rulebooks up to 150 pages. 
* **Deliverable:** Complete mapping for actors, items, spell matrices, and grid coordinates.

### 4. Publisher Retainer Pass ($299/month)
* **Scope:** High-volume pipeline access for active studios (up to 250 pages/month). 
* **Deliverable:** Includes priority queue routing, custom schema mapping, and dedicated switchboard capacity.
