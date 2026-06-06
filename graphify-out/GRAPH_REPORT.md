# Graph Report - .  (2026-06-06)

## Corpus Check
- Corpus is ~11,305 words - fits in a single context window. You may not need a graph.

## Summary
- 25 nodes · 40 edges · 5 communities
- Extraction: 62% EXTRACTED · 38% INFERRED · 0% AMBIGUOUS · INFERRED: 15 edges (avg confidence: 0.85)
- Token cost: 49,595 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Lenses & Interpretation|Lenses & Interpretation]]
- [[_COMMUNITY_Converging Skills (Conclusion)|Converging Skills (Conclusion)]]
- [[_COMMUNITY_Argumentation & Persuasion|Argumentation & Persuasion]]
- [[_COMMUNITY_Site Shell & Bookends|Site Shell & Bookends]]
- [[_COMMUNITY_Drama & Motive|Drama & Motive]]

## God Nodes (most connected - your core abstractions)
1. `Thesis: Look Beyond the Surface` - 10 edges
2. `ENG4U English ISP Portfolio Site` - 7 edges
3. `Argumentation Page` - 6 edges
4. `Literary Criticism Page` - 6 edges
5. `Book Club Page` - 6 edges
6. `Drama / Hamilton Page` - 6 edges
7. `Conclusion Scene: Cosmic Convergence Lens` - 6 edges
8. `Conclusion Page` - 3 edges
9. `Perspective` - 3 edges
10. `Understanding` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Argumentation Page` --conceptually_related_to--> `Thesis: Look Beyond the Surface`  [INFERRED]
  index.html → index.html  _Bridges community 0 → community 2_
- `Drama / Hamilton Page` --conceptually_related_to--> `Thesis: Look Beyond the Surface`  [INFERRED]
  index.html → index.html  _Bridges community 0 → community 4_
- `Literary Criticism Scene: Floating Circular Glass Lenses` --semantically_similar_to--> `Conclusion Scene: Cosmic Convergence Lens`  [INFERRED] [semantically similar]
  index.html → index.html  _Bridges community 0 → community 1_
- `Argumentation Page` --references--> `ENG4U English ISP Portfolio Site`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 2_
- `Book Club Page` --references--> `ENG4U English ISP Portfolio Site`  [EXTRACTED]
  index.html → index.html  _Bridges community 3 → community 0_

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Four Unit Takeaways Forming the Thesis** — englsihisp_index_look_beyond_the_words, englsihisp_index_look_beyond_a_single_interpretation, englsihisp_index_look_beyond_my_first_understanding, englsihisp_index_look_beyond_actions_and_dialogue, englsihisp_index_look_beyond_the_surface [INFERRED 0.85]
- **Four Conclusion Keywords Converging on the Central Lens** — englsihisp_index_persuasion, englsihisp_index_perspective, englsihisp_index_understanding, englsihisp_index_motivation, englsihisp_index_scene_convergence_lens [EXTRACTED 0.95]

## Communities (5 total, 0 thin omitted)

### Community 0 - "Lenses & Interpretation"
Cohesion: 0.36
Nodes (8): Book Club Page, Critical Lenses (Marxist, Feminist, Psychoanalytic), Literary Criticism Page, Look Beyond a Single Interpretation, Look Beyond My First Understanding, Thesis: Look Beyond the Surface, Literary Criticism Scene: Floating Circular Glass Lenses, Book Club Scene: Prism Dispersing White Light into a Spectrum

### Community 1 - "Converging Skills (Conclusion)"
Cohesion: 0.50
Nodes (5): Motivation, Perspective, Persuasion, Conclusion Scene: Cosmic Convergence Lens, Understanding

### Community 2 - "Argumentation & Persuasion"
Cohesion: 0.50
Nodes (4): Argumentation Page, Look Beyond the Words, Persuasive Techniques (TED Talks, Rick Mercer Rants), Argumentation Scene: Cinematic Auditorium with Backlit Speaker and Ripples of Influence

### Community 3 - "Site Shell & Bookends"
Cohesion: 0.50
Nodes (4): Conclusion Page, Intro Page, Intro Scene: Rotating Earth in Space, ENG4U English ISP Portfolio Site

### Community 4 - "Drama & Motive"
Cohesion: 0.50
Nodes (4): Drama / Hamilton Page, Look Beyond Actions and Dialogue, Drama Scene: Cork Investigation Board with Red Strings, Subtext, Motive and Theatrical Devices

## Knowledge Gaps
- **6 isolated node(s):** `Persuasive Techniques (TED Talks, Rick Mercer Rants)`, `Subtext, Motive and Theatrical Devices`, `Intro Scene: Rotating Earth in Space`, `Argumentation Scene: Cinematic Auditorium with Backlit Speaker and Ripples of Influence`, `Book Club Scene: Prism Dispersing White Light into a Spectrum` (+1 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Thesis: Look Beyond the Surface` connect `Lenses & Interpretation` to `Argumentation & Persuasion`, `Site Shell & Bookends`, `Drama & Motive`?**
  _High betweenness centrality (0.340) - this node is a cross-community bridge._
- **Why does `ENG4U English ISP Portfolio Site` connect `Site Shell & Bookends` to `Lenses & Interpretation`, `Argumentation & Persuasion`, `Drama & Motive`?**
  _High betweenness centrality (0.279) - this node is a cross-community bridge._
- **Why does `Argumentation Page` connect `Argumentation & Persuasion` to `Lenses & Interpretation`, `Converging Skills (Conclusion)`, `Site Shell & Bookends`?**
  _High betweenness centrality (0.215) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `Thesis: Look Beyond the Surface` (e.g. with `Argumentation Page` and `Book Club Page`) actually correct?**
  _`Thesis: Look Beyond the Surface` has 8 INFERRED edges - model-reasoned connections that need verification._
- **Are the 2 inferred relationships involving `Book Club Page` (e.g. with `Thesis: Look Beyond the Surface` and `Critical Lenses (Marxist, Feminist, Psychoanalytic)`) actually correct?**
  _`Book Club Page` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Persuasive Techniques (TED Talks, Rick Mercer Rants)`, `Subtext, Motive and Theatrical Devices`, `Intro Scene: Rotating Earth in Space` to the rest of the system?**
  _6 weakly-connected nodes found - possible documentation gaps or missing edges._