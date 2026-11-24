# How Students and Early-Career Professionals Discover, Choose, and Learn AI Tools

**CS5340 Human-Computer Interaction, Fall 2026, Project F26_4 (Group 4)**

> **Status: Phase 3: Prototype.** Phase 3 adds the research synthesis, ideation, and a clickable prototype of the chosen concept, Toolfit.

## Team Members

- Jawad Hassan Basra (hassan.jaw@northeastern.edu)
- Nicholas Kaplun (kaplun.n@northeastern.edu)
- Jikuan Wang (wang.jik@northeastern.edu)

## Project Description

New AI tools are released constantly, and students and early-career professionals hear about them from scattered sources: friends, instructors, social media, newsletters, and workplaces. This project studies how these groups discover AI tools, decide which ones are worth trying, and learn to use them. We do not yet know whether the main difficulty is finding tools, choosing between them, trusting recommendations, or learning to use them, or whether many people are satisfied with the tools they already use. Following the Design Thinking process, we will begin with user interviews before deciding what, if anything, to design.

## Prototype: Toolfit

Toolfit is a task-first AI tool finder. Instead of browsing a directory, the user describes the task their current AI tool just failed at, adds budget and setting, and gets three matches. Each match explains how it differs from the tool they already use, flags tools that run on the same underlying model, and shows evidence from people with a similar task. The user then tries a suggested test prompt on their own task and reports back whether it worked.

- **Live prototype:** https://claude.ai/artifact/XeR7ZQSwKqtoHiH4XvmG2E
- **Run locally:** open `prototype/index.html` in any browser. It is a single HTML file with plain JavaScript and no build step.
- **Screenshots:** `prototype/screens/`

The tool data, prices, and user reports in the prototype are illustrative sample data, not interview findings. Matching currently covers three example tasks drawn from our interviews.

## Repository Contents

- `docs/F26_4_Phase1_Research_and_Planning.docx`: Phase 1 report (background research, competitor analysis, stakeholder analysis, design thinking milestones, and technical planning)
- `docs/F26_4_Phase3_Report.docx`: Phase 3 report (research summary, problem and ideation, prototype, implementation, and UI/UX principles)
- `prototype/index.html`: Toolfit clickable prototype
- `prototype/screens/`: screenshots of each prototype screen, including error and dark mode states
