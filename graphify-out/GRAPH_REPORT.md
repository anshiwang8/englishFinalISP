# Graph Report - .  (2026-06-06)

## Corpus Check
- Corpus is ~13,997 words - fits in a single context window. You may not need a graph.

## Summary
- 39 nodes · 69 edges · 9 communities (8 shown, 1 thin omitted)
- Extraction: 87% EXTRACTED · 13% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.77)
- Token cost: 106,235 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_WebGL Earth Rendering|WebGL Earth Rendering]]
- [[_COMMUNITY_Lens & Prism Optics Scenes|Lens & Prism Optics Scenes]]
- [[_COMMUNITY_Argumentation Auditorium|Argumentation Auditorium]]
- [[_COMMUNITY_Central Thesis & Conclusion|Central Thesis & Conclusion]]
- [[_COMMUNITY_Cosmic Intro Background|Cosmic Intro Background]]
- [[_COMMUNITY_Literary Criticism & Navigation|Literary Criticism & Navigation]]
- [[_COMMUNITY_Argumentation Theme & Echoes|Argumentation Theme & Echoes]]
- [[_COMMUNITY_Drama Investigation Room|Drama Investigation Room]]
- [[_COMMUNITY_Custom Cursor|Custom Cursor]]

## God Nodes (most connected - your core abstractions)
1. `Unit Echo Nodes / Glyphs (CONC_NODES)` - 9 edges
2. `Canvas Main Render Loop (frame)` - 8 edges
3. `ENG4U Independent Study Project (Presentation)` - 7 edges
4. `Look Beyond the Surface (Central Thesis)` - 7 edges
5. `Navigation / Page-Switching System` - 7 edges
6. `Intro Scene (Cosmic Starfield Hero)` - 7 edges
7. `Argumentation Scene (Cinematic Auditorium)` - 6 edges
8. `Literary Criticism Scene (Lens-Space)` - 6 edges
9. `Book Club Scene (Prism of Interpretation)` - 6 edges
10. `Drama / Hamilton Scene (Investigation Room)` - 6 edges

## Surprising Connections (you probably didn't know these)
- `Prism / Spectrum Dispersion (drawPrism)` --conceptually_related_to--> `Critical Lenses (Marxist / Feminist / Psychoanalytic)`  [INFERRED]
  index.html → index.html  _Bridges community 5 → community 1_
- `Unit Echo Nodes / Glyphs (CONC_NODES)` --semantically_similar_to--> `Floating Persuasion Words (drawArgFragments)`  [INFERRED] [semantically similar]
  index.html → index.html  _Bridges community 2 → community 6_
- `Unit Echo Nodes / Glyphs (CONC_NODES)` --semantically_similar_to--> `Glass Lens Cards (drawLensCard)`  [INFERRED] [semantically similar]
  index.html → index.html  _Bridges community 1 → community 6_
- `Unit Echo Nodes / Glyphs (CONC_NODES)` --semantically_similar_to--> `Red String Connections (drawRedStrings)`  [INFERRED] [semantically similar]
  index.html → index.html  _Bridges community 7 → community 6_
- `ENG4U Independent Study Project (Presentation)` --references--> `Argumentation Scene (Cinematic Auditorium)`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 6_

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **WebGL Earth Rendering Pipeline** — englsihisp_index_rotating_earth, englsihisp_index_earthgen, englsihisp_index_daynight_shader, englsihisp_index_atmosphere_glow, englsihisp_index_cloud_layer, englsihisp_index_perlin_noise [EXTRACTED 1.00]
- **Five Unit Scenes Embodying the Central Thesis** — englsihisp_index_argumentation_scene, englsihisp_index_literary_scene, englsihisp_index_bookclub_scene, englsihisp_index_drama_scene, englsihisp_index_conclusion_scene, englsihisp_index_central_thesis [EXTRACTED 1.00]
- **Conclusion Converges the Four Unit Echoes** — englsihisp_index_conc_lens, englsihisp_index_conc_nodes, englsihisp_index_argumentation_scene, englsihisp_index_literary_scene, englsihisp_index_bookclub_scene, englsihisp_index_drama_scene [EXTRACTED 1.00]

## Communities (9 total, 1 thin omitted)

### Community 0 - "WebGL Earth Rendering"
Cohesion: 0.38
Nodes (7): Fresnel Atmosphere Glow, Static 2D Canvas Earth (drawEarth, deprecated), Cloud Shell Layer, Day/Night Earth Shader, Procedural Earth Texture Generator (EarthGen), Perlin Noise / fBm Generator, Rotating WebGL Earth

### Community 1 - "Lens & Prism Optics Scenes"
Cohesion: 0.33
Nodes (6): Prism-Space Renderer (drawBookSpace), Central Convergence Lens (drawConcLens), Glass Lens Cards (drawLensCard), Lens-Space Renderer (drawLensSpace), Prism / Spectrum Dispersion (drawPrism), Refracted Central Orb (drawRefractedOrb)

### Community 2 - "Argumentation Auditorium"
Cohesion: 0.40
Nodes (5): Rim-Lit Audience (drawArgAudience), Floating Persuasion Words (drawArgFragments), Ripples of Influence (drawArgRipples), Backlit Speaker Silhouette (drawArgSpeaker), Auditorium Renderer (drawAuditorium)

### Community 3 - "Central Thesis & Conclusion"
Cohesion: 0.60
Nodes (5): Look Beyond the Surface (Central Thesis), Conclusion Scene (Cosmic Convergence), Drama / Hamilton Scene (Investigation Room), ENG4U Independent Study Project (Presentation), Theatrical Devices (Drama Theme)

### Community 4 - "Cosmic Intro Background"
Cohesion: 0.60
Nodes (5): Constellations (drawConstellations), Intro Scene (Cosmic Starfield Hero), Nebulae Background (drawNebulae), Canvas Main Render Loop (frame), 2D Starfield (buildStars / drawStars)

### Community 5 - "Literary Criticism & Navigation"
Cohesion: 0.67
Nodes (4): Book Club Scene (Prism of Interpretation), Critical Lenses (Marxist / Feminist / Psychoanalytic), Literary Criticism Scene (Lens-Space), Navigation / Page-Switching System

### Community 6 - "Argumentation Theme & Echoes"
Cohesion: 0.67
Nodes (3): Argumentation Scene (Cinematic Auditorium), Unit Echo Nodes / Glyphs (CONC_NODES), Persuasive Techniques (Argumentation Theme)

### Community 7 - "Drama Investigation Room"
Cohesion: 0.67
Nodes (3): Cork Investigation Board (drawCorkBoard), Investigation Room Renderer (drawDramaRoom), Red String Connections (drawRedStrings)

## Knowledge Gaps
- **10 isolated node(s):** `Custom Cursor (ring + dot)`, `Persuasive Techniques (Argumentation Theme)`, `Theatrical Devices (Drama Theme)`, `Fresnel Atmosphere Glow`, `Perlin Noise / fBm Generator` (+5 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Intro Scene (Cosmic Starfield Hero)` connect `Cosmic Intro Background` to `WebGL Earth Rendering`, `Central Thesis & Conclusion`, `Literary Criticism & Navigation`?**
  _High betweenness centrality (0.339) - this node is a cross-community bridge._
- **Why does `Rotating WebGL Earth` connect `WebGL Earth Rendering` to `Cosmic Intro Background`?**
  _High betweenness centrality (0.278) - this node is a cross-community bridge._
- **Why does `Canvas Main Render Loop (frame)` connect `Cosmic Intro Background` to `Lens & Prism Optics Scenes`, `Argumentation Auditorium`, `Literary Criticism & Navigation`, `Drama Investigation Room`?**
  _High betweenness centrality (0.220) - this node is a cross-community bridge._
- **Are the 4 inferred relationships involving `Unit Echo Nodes / Glyphs (CONC_NODES)` (e.g. with `Floating Persuasion Words (drawArgFragments)` and `Glass Lens Cards (drawLensCard)`) actually correct?**
  _`Unit Echo Nodes / Glyphs (CONC_NODES)` has 4 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Custom Cursor (ring + dot)`, `Persuasive Techniques (Argumentation Theme)`, `Theatrical Devices (Drama Theme)` to the rest of the system?**
  _10 weakly-connected nodes found - possible documentation gaps or missing edges._