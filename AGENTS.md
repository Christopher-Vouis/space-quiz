# Project rules

- Keep the quiz self-contained in `index.html`; do not add a server, build step, or external dependencies.
- Preserve the 10-question quiz, progress indicator, score, answer feedback, and results/restart flow.
- Keep the layout responsive and centered in a narrow column. Use the existing CSS variables for colors so light and dark themes stay consistent.
- Use semantic HTML, keyboard-accessible controls, visible focus states, and accessible status/progress announcements.
- Respect `prefers-reduced-motion` for animations and transitions.
- Keep JavaScript dependency-free and use safe DOM APIs for dynamic content.
- After UI changes, open `index.html` in the integrated browser and check the affected flow in both themes when practical.
