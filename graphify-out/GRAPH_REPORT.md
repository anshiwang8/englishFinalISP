# Graph Report - .  (2026-06-05)

## Corpus Check
- Corpus is ~8,901 words - fits in a single context window. You may not need a graph.

## Summary
- 67 nodes · 89 edges · 7 communities
- Extraction: 85% EXTRACTED · 15% INFERRED · 0% AMBIGUOUS · INFERRED: 13 edges (avg confidence: 0.83)
- Token cost: 88,656 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Site Shell, Pages & Themes|Site Shell, Pages & Themes]]
- [[_COMMUNITY_Book Club Prism Scene|Book Club Prism Scene]]
- [[_COMMUNITY_Drama Room Environment|Drama Room Environment]]
- [[_COMMUNITY_Intro Cosmic Scene & Render Loop|Intro Cosmic Scene & Render Loop]]
- [[_COMMUNITY_Literary Lens-Space|Literary Lens-Space]]
- [[_COMMUNITY_Argumentation Auditorium|Argumentation Auditorium]]
- [[_COMMUNITY_Drama Clue Cards|Drama Clue Cards]]

## God Nodes (most connected - your core abstractions)
1. `frame Shared Canvas Render Loop` - 12 edges
2. `drawBookSpace` - 10 edges
3. `drawDramaRoom` - 10 edges
4. `drawAuditorium` - 9 edges
5. `INTRO Cosmic Scene` - 8 edges
6. `drawLensSpace` - 8 edges
7. `switchPage Page-Switch with Fade Transition` - 7 edges
8. `Thesis: ENG4U Taught Me to Look Beyond the Surface` - 6 edges
9. `drawClue (Clue Card Dispatcher)` - 6 edges
10. `ENG4U Independent Study Project Website` - 5 edges

## Surprising Connections (you probably didn't know these)
- `INTRO Cosmic Scene` --references--> `Thesis: ENG4U Taught Me to Look Beyond the Surface`  [INFERRED]
  index.html → index.html  _Bridges community 0 → community 3_
- `LIT_CARDS Lens Definitions` --semantically_similar_to--> `BOOK_SPECTRUM Color/Lens Data`  [INFERRED] [semantically similar]
  index.html → index.html  _Bridges community 4 → community 1_
- `frame Shared Canvas Render Loop` --calls--> `drawAuditorium`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 5_
- `frame Shared Canvas Render Loop` --calls--> `drawBookSpace`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 1_
- `frame Shared Canvas Render Loop` --calls--> `drawDramaRoom`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 2_

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **frame Render Loop Dispatches Unit Scenes by currentPage** — englsihisp_index_frame_loop, englsihisp_index_intro_scene, englsihisp_index_argumentation_scene, englsihisp_index_literary_scene, englsihisp_index_bookclub_scene, englsihisp_index_drama_room [EXTRACTED 1.00]
- **All Unit Themes Embody the Look-Beyond-the-Surface Thesis** — englsihisp_index_theme_beyond_surface, englsihisp_index_theme_argumentation, englsihisp_index_theme_multiple_meanings, englsihisp_index_theme_revisiting, englsihisp_index_theme_motives_subtext [INFERRED 0.85]
- **Marxist/Feminist/Psychoanalytic Lenses Shared Across Lit Crit and Book Club** — englsihisp_index_three_lens_motif, englsihisp_index_lit_cards, englsihisp_index_book_spectrum [INFERRED 0.85]

## Communities (7 total, 0 thin omitted)

### Community 0 - "Site Shell, Pages & Themes"
Cohesion: 0.21
Nodes (15): ARGUMENTATION Auditorium Scene (Unit 1), BOOK CLUB Prism of Interpretation Scene (Unit 3), Custom Cursor (cur-ring / cur-dot), DRAMA / HAMILTON Investigation Room Scene (Unit 4), Hero Overlay + Staggered Reveal Pattern, ENG4U Independent Study Project Website, LITERARY CRITICISM Lens-Space Scene (Unit 2), Navigation Tab System (nav-tabs / data-page) (+7 more)

### Community 1 - "Book Club Prism Scene"
Cohesion: 0.24
Nodes (10): BOOK_SPECTRUM Color/Lens Data, drawBeamLabels, drawBookBackground, drawBookFog, drawBookParticles, drawBookSpace, drawBookStars, drawPrism (The Text) (+2 more)

### Community 2 - "Drama Room Environment"
Cohesion: 0.20
Nodes (10): buildDramaCork Cork Texture, DRAMA_LINKS Red-String Connections, drawBackSilhouettes, drawCorkBoard, drawCurtains, drawDeskLamp, drawDramaDust, drawDramaRoom (+2 more)

### Community 3 - "Intro Cosmic Scene & Render Loop"
Cohesion: 0.31
Nodes (10): buildEarthTex Earth Texture, CITIES City-Lights Data, CONCLUSION Page (Placeholder), drawConstellations, drawEarth, drawLens Cursor Lens, drawNebulae, drawStars (+2 more)

### Community 4 - "Literary Lens-Space"
Cohesion: 0.25
Nodes (8): Brooks Advertisement Reference, drawLensCard (Glass Lens Card), drawLensSpace, drawLitBackground, drawLitParticles, drawNeuralLines, drawRefractedOrb, LIT_CARDS Lens Definitions

### Community 5 - "Argumentation Auditorium"
Cohesion: 0.25
Nodes (8): buildAudienceTex Audience Texture, drawAuditorium, drawBalconies, drawSpeaker (Speaker + Mic), drawSpotlights, drawStage, updateAndDrawDust, updateAndDrawWords Word Particles

### Community 6 - "Drama Clue Cards"
Cohesion: 0.33
Nodes (6): DRAMA_CLUES Clue Card Data, drawClue (Clue Card Dispatcher), drawHubCard (MOTIVE Hub), drawNoteCard, drawPhotoCard (Character Polaroid), drawTagCard

## Knowledge Gaps
- **33 isolated node(s):** `Custom Cursor (cur-ring / cur-dot)`, `buildEarthTex Earth Texture`, `CITIES City-Lights Data`, `drawSpotlights`, `drawStage` (+28 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `frame Shared Canvas Render Loop` connect `Intro Cosmic Scene & Render Loop` to `Site Shell, Pages & Themes`, `Book Club Prism Scene`, `Drama Room Environment`, `Literary Lens-Space`, `Argumentation Auditorium`?**
  _High betweenness centrality (0.638) - this node is a cross-community bridge._
- **Why does `drawDramaRoom` connect `Drama Room Environment` to `Site Shell, Pages & Themes`, `Intro Cosmic Scene & Render Loop`, `Drama Clue Cards`?**
  _High betweenness centrality (0.409) - this node is a cross-community bridge._
- **Why does `drawBookSpace` connect `Book Club Prism Scene` to `Site Shell, Pages & Themes`, `Intro Cosmic Scene & Render Loop`?**
  _High betweenness centrality (0.258) - this node is a cross-community bridge._
- **What connects `Custom Cursor (cur-ring / cur-dot)`, `buildEarthTex Earth Texture`, `CITIES City-Lights Data` to the rest of the system?**
  _33 weakly-connected nodes found - possible documentation gaps or missing edges._