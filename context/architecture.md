# Architecture — zolai-ai.github.io

## Structure
- `index.html` — animated landing page (brand theme, entrance/hover effects, `prefers-reduced-motion`)
- `logo.png` — original brand logo (byte-identical to website)
- `_config.yml` — Jekyll minimal theme config
- `README.md` — source/build notes

## Invariants
- `logo.png` MUST be byte-identical to website logo
- Design tokens via CSS custom properties
- No `.venv`, no `node_modules`, no build output checked in
