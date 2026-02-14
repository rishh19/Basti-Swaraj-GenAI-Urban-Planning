# Basti-Swaraj: Generative In-Situ Upgrading for Informal Settlements  
### ET GenAI Hackathon – Phase 1 Concept Submission

This repository contains our Phase 1 concept submission for the ET GenAI Hackathon.  
The project proposes a Generative AI system designed to help planners visualize micro-upgrades in dense informal settlements without resorting to demolition-based redevelopment.

---

## 🏙 Problem Statement

Rapid urbanization in India has led to the expansion of dense informal settlements where millions lack access to sanitation, clinics, and safe infrastructure.

Current redevelopment models often rely on demolishing entire settlements and relocating communities, which disrupts livelihoods and social networks. Urban planners lack tools to **visualize small-scale, in-situ improvements** that preserve the existing settlement structure while improving living conditions.

---

## 🎯 Concept Objective

Basti-Swaraj aims to build a Generative AI-assisted planning tool that allows:

- Visualization of infrastructure upgrades directly on satellite/drone imagery  
- Context-aware placement of facilities like toilets, clinics, or Anganwadi centers  
- Rapid generation of design alternatives for planners and NGOs  
- Feasibility feedback based on engineering and planning constraints  

The goal is to enable **community-friendly, non-destructive urban upgrading**.

---

## 🧠 Proposed Solution Approach

The proposed system combines multi-modal AI models in a structured pipeline:

### 1️⃣ Map Input & Segmentation
Satellite or drone imagery is uploaded.  
A segmentation model identifies rooftops, roads, and open land that can host interventions.

### 2️⃣ Generative Inpainting
A generative diffusion model fills selected zones with context-aware infrastructure designs based on prompts such as:

- “Community health clinic”
- “Bio-toilet complex”
- “Low-cost Anganwadi centre”

### 3️⃣ Feasibility Assessment
A vision-language model evaluates whether the generated layout blocks drainage paths, violates setbacks, or creates accessibility issues, producing a feasibility score.

---

## 🏗 Potential Users

- Municipal planners and Smart City teams  
- NGOs working in slum upgrading and advocacy  
- Community leaders proposing local improvements  
- Urban planning consultants and architecture firms  

---

## 🌍 Impact Focus

The project aligns with:

- **SDG 11 – Sustainable Cities & Communities**  
- **SDG 6 – Clean Water & Sanitation**

It demonstrates how Generative AI can support **inclusive urban planning** rather than purely digital applications.

---

## 📊 Data & Knowledge Sources (Proposed)

- OpenStreetMap / satellite imagery for base maps  
- SpaceNet dataset for building footprint learning  
- National Building Code of India for planning constraints  

---

## 🚀 Project Status

This repository currently contains:

- Phase 1 concept submission document  

Prototype development, architecture diagrams, and implementation experiments are planned in future phases.

---

## 🔮 Future Scope

Planned next steps include:

- Building a proof-of-concept pipeline using segmentation + diffusion models  
- Creating a simple web interface for planners  
- Testing on real settlement imagery  
- Incorporating engineering constraint checks  

---

## 👥 Team

**Team PEN**

---
## 💡 Vision

Basti-Swaraj explores how Generative AI can act as a *co-architect* for humanitarian urban design, helping cities upgrade settlements **with communities, not against them**.
