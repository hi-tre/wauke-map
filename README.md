# Wauke · Nā Wahi Ulu
### Kapa Practitioner Map — Living Map of Hawaiʻi

**[→ Open live map](https://hi-tre.github.io/wauke-map/)**

An interactive mapping dashboard tracing where wauke (paper mulberry / *Broussonetia papyrifera*) is currently cultivated across the Hawaiian Islands, visualizing ecological conditions and potential outputs of expanded propagation — design as a tool for cultural restoration.

---

## Project Overview

**Purpose:** Built for kapa practitioners, students, and ecologists. Maps wauke cultivation sites, bamboo (ʻohe) sources, and ecological conditions across Oʻahu, Maui, Hawaiʻi, Kauaʻi, and Molokaʻi by moku district.

**Portfolio context:** ECU MFA in Critical Ecological Practices · Tre Zamora  
**Throughline:** *Restoration of relationship — to land, to culture, to self — through making.*

---

## Features

1. **Map View** — Interactive Leaflet.js map with real moku district boundaries
2. **Environmental Compare** — Side-by-side ecological scoring by moku
3. **Wauke Varieties** — Documented cultivars: Pōʻaha, Laulima, Kūloli
4. **Kapa + Wauke** — Cultural context, the kapa-making process, bamboo's role

### Layers
- Wauke cultivation sites (active / potential / study)
- Bamboo (ʻohe) sites for ʻohe kapala sourcing
- Moku district boundaries
- Wet / dry rainfall zones (toggle on/off)

### Islands covered
Oʻahu · Maui · Hawaiʻi · Kauaʻi · Molokaʻi

---

## File Structure

```
wauke-project/
├── index.html        ← Single-file app (HTML + CSS + JS)
└── README.md         ← This file
```

All dependencies load via CDN:
- **Leaflet.js 1.9.4** — interactive mapping
- **Google Fonts** — Fraunces (display) + DM Mono (body)
- **Basemap** — Stadia Alidade Smooth Dark + ESRI World Hillshade overlay

---

## Running Locally

Just open `index.html` in any modern browser — no build step, no server required.

For live reload during development, use VS Code's **Live Server** extension:
1. Install "Live Server" by Ritwick Dey
2. Right-click `index.html` → **Open with Live Server**

---

## Data Notes

All cultivation sites are based on documented public sources:
- Mānoa Heritage Center, Pūkoʻa Studios, Bishop Museum (Oʻahu)
- Maui Nui Botanical Gardens (Maui)
- Puʻuhonua o Hōnaunau NHP (Hawaiʻi)
- Hanalei Valley (Kauaʻi), Hālawa Valley (Molokaʻi)

Moku boundary polygons sourced from the State of Hawaiʻi Office of Planning GIS dataset (`geodata.hawaii.gov`), Douglas-Peucker simplified for web performance. All 30 moku across 5 islands use surveyed official boundaries.

Wauke variety information sourced from:
- Maui Nui Botanical Gardens ethnobotany records
- Bishop Museum ethnobotany database
- Ulukau Hawaiian language resources
- CanoePlants.com

---

## Next Development Steps

- [x] Replace approximate moku polygons with official State GIS GeoJSON
- [ ] Connect to live cultivation data via API
- [ ] Add propagation model (interactive acreage calculator)
- [ ] Add more plant layers (māmaki, ʻolonā, other kapa-adjacent species)
- [ ] Mobile responsive layout

---

*Brief generated: May 2026 · ECU MFA Critical Ecological Practices*  
*Tre Zamora · Fall 2027 application*
