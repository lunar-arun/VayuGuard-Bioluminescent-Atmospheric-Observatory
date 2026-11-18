# VayuGuard — Bioluminescent Atmospheric Observatory

**VayuGuard** is a GenAI-powered atmospheric intelligence web application designed to help families and urban communities navigate severe winter smog, temperature inversions, and high-PM2.5 episodes. It pairs real-time particle physics visualization with tailored low-emission routines, interactive indoor air quality hacks, and transparent impact quantification.

---

## Key Features

### 1. Full-Bleed Interactive Particle Physics Canvas (`#atmos-canvas`)
- **Dynamic Air-State Simulation:** Swirling crimson/amber PM2.5 hazard motes visibly transform into luminous emerald and cyan oxygen streams as you activate low-emission habits and indoor air hacks.
- **Cursor Atmospheric Ionizer:** Moving your mouse or touch pointer across the screen generates an ionizing wake that disperses smog particles into glowing cyan oxygen trails.

### 2. Breathable Biosphere Sanctuary & 24-Hour Ventilation Arc
- **Concentric Deflection Shield:** Visualizes outdoor toxic particulate matter bouncing off your household's clean-air boundary while tracking real-time **Indoor Purity %** and **Indoor vs. Outdoor AQI**.
- **24-Hour Radial Ventilation Clock:** Highlights the exact midday solar-lift window when thermal inversions break so families know when to safely cross-ventilate without letting peak morning/nocturnal smog inside.
- **Lung Burden Avoided:** Translates micrograms of blocked PM2.5 into relatable daily **cigarette-equivalents saved**.

### 3. Daily Low-Emission Matrix & Kinetic Impact Gauges
- Toggle everyday actions (*Metro/EV School & Office Run*, *Induction Cooking + Exhaust*, *HEPA Nighttime Bedroom Purge*, *Zero-Waste Leaf Mulching*) to watch three real-time gauges update:
  - **PM2.5 Avoided (`µg/m³`)** — Personal respiratory dose reduction.
  - **Soot & CO₂ Cut (`kg`)** — Direct neighborhood combustion emissions prevented.
  - **Clean Breath Gained (`hrs`)** — Equivalent WHO-safe breathing hours restored.

### 4. Interactive Indoor Air Hacks X-Ray Lab
- An interactive SVG architectural cutaway of a home living zone. Toggle four budget-friendly indoor defenses—**DIY MERV-13 Corsi-Rosenthal Cube**, **Wet-Mop Dust Trap**, **Snake/Spider Plant Bio-Wall**, and **Silicone Window & Door Seals**—to inspect clean airflow vectors and boost room **CADR (`CFM`)**.

### 5. AETHER Holographic GenAI Copilot
- Tailors advice to your selected **City/AQI** (*New Delhi*, *Chennai*, *Lahore*, *Beijing*, or a live *Custom AQI Simulator*) and **Household Profile** (*Family with Kids & Seniors*, *Metro/Daily Commuter*, *High-Rise Apartment*, or *Community Organizer*).
- Every response is structured into three scannable pillars:
  1. **Actionable Routine**
  2. **Why It Works** (atmospheric & respiratory science)
  3. **Direct Health & Emission Impact**

### 6. Community Smog Shield Pulse Radar
- Connects households to ward-level collective action pacts such as **School-Gate No-Idling Pacts**, **Ward Leaf-Composting Drives**, and **Construction Dust Mist Alerts**.

---

## Project Structure

```text
vayuguard/
├── vayuguard.html   # Complete self-contained application (HTML5 Canvas, SVG, Tailwind CSS, JS)
└── README.md        # Architecture, features, and setup guide
```

---

## Quick Start

1. **Zero-Build Local Launch:**
   Simply open `vayuguard.html` directly in any modern browser (Chrome, Edge, Safari, Firefox), or serve it via any static server:
   ```bash
   npx serve .
   ```
2. **Optional Live Gemini API Integration:**
   - By default, `vayuguard.html` includes a built-in deterministic atmospheric engine so every prompt and scenario works immediately offline or in sandboxed previews.
   - To connect live Gemini responses, open `vayuguard.html`, locate `const apiKey = "";` inside `handleUserChatSubmit()`, and insert your Google Gemini API key.

---

## Tech Stack
- **UI & Styling:** Tailwind CSS (CDN), Custom Glassmorphic Obsidian & Bioluminescent Aurora Theme
- **Typography:** Space Grotesk, Plus Jakarta Sans, JetBrains Mono
- **Graphics & Physics:** HTML5 2D Canvas Particle Engine + Animated Vector SVG Biosphere & X-Ray Blueprints
- **GenAI Synthesis:** Gemini REST API (`gemini-3-flash-preview`) with structured JSON schema output
