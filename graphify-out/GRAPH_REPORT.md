# Graph Report - .  (2026-06-03)

## Corpus Check
- Corpus is ~3,013 words - fits in a single context window. You may not need a graph.

## Summary
- 25 nodes · 40 edges · 5 communities (4 shown, 1 thin omitted)
- Extraction: 78% EXTRACTED · 22% INFERRED · 0% AMBIGUOUS · INFERRED: 9 edges (avg confidence: 0.84)
- Token cost: 37,952 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Cosmic Render Pipeline|Cosmic Render Pipeline]]
- [[_COMMUNITY_Earth, Paper and Meaning|Earth, Paper and Meaning]]
- [[_COMMUNITY_Hero Animation and Reveal|Hero Animation and Reveal]]
- [[_COMMUNITY_Page Structure and Identity|Page Structure and Identity]]
- [[_COMMUNITY_Interactive Cursor|Interactive Cursor]]

## God Nodes (most connected - your core abstractions)
1. `Main Animation Loop (frame)` - 11 edges
2. `Math Utility Functions (easeOut, lerp, clamp, inv)` - 7 edges
3. `drawEarth Function` - 5 edges
4. `ENG4U ISP Landing Page` - 4 edges
5. `Animation Timeline (TL)` - 4 edges
6. `drawPaper Function` - 4 edges
7. `DEPTH Constellation Spelling` - 4 edges
8. `ENG4U Independent Study Project` - 4 edges
9. `drawStars Function` - 3 edges
10. `drawConstellations Function` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Canvas Rendering Engine` --implements--> `Main Animation Loop (frame)`  [INFERRED]
  index.html → index.html  _Bridges community 3 → community 0_
- `Paper-to-Cosmos Dissolve Transition` --rationale_for--> `Ink Particles System`  [INFERRED]
  index.html → index.html  _Bridges community 2 → community 1_
- `Wittgenstein Quote on Language` --semantically_similar_to--> `DEPTH Constellation Spelling`  [INFERRED] [semantically similar]
  index.html → index.html  _Bridges community 0 → community 1_
- `Wittgenstein Quote on Language` --conceptually_related_to--> `ENG4U Independent Study Project`  [INFERRED]
  index.html → index.html  _Bridges community 1 → community 3_
- `ENG4U ISP Landing Page` --references--> `Hero Section (Title/Author Text)`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 2_

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Cosmic Reveal Sequence** — index_animation_timeline, index_paper_dissolve_transition, index_draw_earth [INFERRED 0.85]
- **Canvas Draw Pipeline** — index_main_loop, index_draw_nebulae, index_draw_stars, index_draw_constellations, index_draw_earth, index_draw_ink, index_draw_paper, index_draw_lens [EXTRACTED 1.00]
- **Depth Theme — Language, Stars, Earth** — index_wittgenstein_quote, index_constellations_depth, index_eng4u_isp [INFERRED 0.75]

## Communities (5 total, 1 thin omitted)

### Community 0 - "Cosmic Render Pipeline"
Cohesion: 0.43
Nodes (8): DEPTH Constellation Spelling, drawConstellations Function, drawInk Function, drawNebulae Function, drawStars Function, Main Animation Loop (frame), Math Utility Functions (easeOut, lerp, clamp, inv), Star Field with Glyphs

### Community 1 - "Earth, Paper and Meaning"
Cohesion: 0.33
Nodes (6): City Lights Array, drawEarth Function, drawPaper Function, Earth Texture Builder, Paper-to-Cosmos Dissolve Transition, Wittgenstein Quote on Language

### Community 2 - "Hero Animation and Reveal"
Cohesion: 0.40
Nodes (5): Animation Timeline (TL), Hero Section (Title/Author Text), Ink Particles System, revealHero Text Animation, Scroll Cue Indicator

### Community 3 - "Page Structure and Identity"
Cohesion: 0.67
Nodes (4): Canvas Rendering Engine, ENG4U Independent Study Project, ENG4U ISP Landing Page, Navigation Bar

## Knowledge Gaps
- **4 isolated node(s):** `Earth Texture Builder`, `Custom Cursor System`, `Scroll Cue Indicator`, `City Lights Array`
  These have ≤1 connection - possible missing edges or undocumented components.
- **1 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Main Animation Loop (frame)` connect `Cosmic Render Pipeline` to `Earth, Paper and Meaning`, `Hero Animation and Reveal`, `Page Structure and Identity`, `Interactive Cursor`?**
  _High betweenness centrality (0.552) - this node is a cross-community bridge._
- **Why does `drawEarth Function` connect `Earth, Paper and Meaning` to `Cosmic Render Pipeline`?**
  _High betweenness centrality (0.183) - this node is a cross-community bridge._
- **Why does `Animation Timeline (TL)` connect `Hero Animation and Reveal` to `Cosmic Render Pipeline`?**
  _High betweenness centrality (0.110) - this node is a cross-community bridge._
- **What connects `Earth Texture Builder`, `Custom Cursor System`, `Scroll Cue Indicator` to the rest of the system?**
  _4 weakly-connected nodes found - possible documentation gaps or missing edges._