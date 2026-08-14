# Asset Reference — Alpha 3D README

## Included (already generated, ready to use)
```
assets/
├── hero-ai-core.svg          ← cinematic hero banner (done)
├── tech-stack.svg            ← AI tech pyramid diagram (done)
├── footer-ai.svg             ← footer banner (done)
└── gitfut-card.png           ← your existing profile photo card (reused, unchanged)
```
System Architecture and Agentic AI Network are rendered as **Mermaid diagrams** directly in the README (native GitHub rendering, zero image weight, always crisp in light/dark mode) rather than static SVGs — this was explicitly allowed by the brief and is more maintainable.

## Optional upgrades (image-gen prompts, if you want AI-generated art later)

**1. `assets/project-homework.svg`** — Multi-agent orchestration diagram
> Minimal dark-mode technical diagram, 800×450px, transparent/dark (#08090D) background. Four connected nodes labeled Orchestrator, Subject Expert, Explanation Adapter, Memory Logger, glowing cyan (#22D3EE) connection lines, gold (#D4AF37) node borders, flat vector style, no text clutter, GitHub-README-safe.

**2. `assets/project-agroguard.svg`** — Computer vision detection visualization
> Dark technical illustration, 800×450px, a leaf silhouette with a YOLO-style bounding-box grid overlay in cyan, subtle scan-line effect, gold accent corner markers, minimal flat vector style, dark background (#08090D).

**3. `assets/project-face-attendance.svg`** — Biometric pipeline diagram
> Dark technical diagram, 800×450px, simplified face-outline with facial landmark points connected by thin gold lines, a small database cylinder icon at the end of the pipeline, cyan glow accents, flat vector, dark background.

**4. `assets/project-defect-system.svg`** — Industrial vision pipeline
> Dark technical illustration, 800×450px, a conveyor-belt silhouette with a scanning beam (cyan) crossing a product icon, a red/crimson (#800020) flag marking a detected defect, flat vector, dark background.

**5. `assets/developer-command-card.svg`** (optional replacement for the photo card)
> 500×700px vertical card, dark glass panel (#111116) with 1.5px gold (#D4AF37) border and soft outer glow, layered depth via subtle drop shadows, holographic corner accent in violet (#8B5CF6), space reserved at top for a circular profile photo, clean sans-serif label areas below for name / role / links, minimal and uncluttered, GitHub-README-safe (static image, no CSS/JS dependencies).

## Notes
- All SVGs use inline gradients only (no external fonts/scripts) so they render identically on GitHub, mobile GitHub, and both light/dark themes.
- Keep total asset weight low — the three included SVGs are lightweight vector files (a few KB each), well under GitHub's practical README budget.
- If you generate the four project SVGs above, just drop them in `assets/` and add `<img src="assets/project-x.svg" width="100%"/>` above each project's table in the README.
