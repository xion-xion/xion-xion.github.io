# AI Agent Guide (AGENTSV2.md)

This is the personal Jekyll-based portfolio of **Muhammad Khairi bin Samsudin**, hosted at [xion-xion.github.io](https://xion-xion.github.io/).

---

## 1. Context & Purpose (WHY & WHAT)
*   **Target Profile:** System Integration \u0026 IIoT Specialist.
*   **Core Theme:** "Bridging physical \u0026 digital silos to deliver real ROI."
*   **Tech Stack:** Jekyll (Kramdown engine), Vanilla HTML5/CSS3, ES6 JS.
*   **Constraint:** Do **NOT** use CSS frameworks (e.g., Tailwind, Bootstrap).

---

## 2. Dev Environment (HOW)
*   **Run Jekyll Local:** `bundle exec jekyll serve` or `jekyll serve`.
*   **Fallback Local Server:** `python3 -m http.server 8000`.

---

## 3. Reference Pointers
*   **Source of Truth (Read-Only):** [info/Khairi_Information.md](file:///home/xion/xion-xion.github.io/info/Khairi_Information.md). Do not hallucinate or invent info/metrics.
*   **Task List (Writable):** [PORTFOLIO_UPGRADE_PLAN.md](file:///home/xion/xion-xion.github.io/PORTFOLIO_UPGRADE_PLAN.md). Update task status as completed.
*   **Style Sheet (Writable):** [assets/css/style.css](file:///home/xion/xion-xion.github.io/assets/css/style.css). Contains typography, dark mode variables, and animations.
*   **Pages (Writable):** [index.html](file:///home/xion/xion-xion.github.io/index.html) and files under [projects/](file:///home/xion/xion-xion.github.io/projects/).

---

## 4. Key Rules
*   **Relative Paths:** Use Liquid relative URL filter for internal assets/links:
    *   `{{ '/path' | relative_url }}`.
*   **Front Matter:** Every new page requires Jekyll front matter (specifying `layout: default` and `title`).
*   **Aesthetics:** Align styles with the premium dark theme in [assets/css/style.css](file:///home/xion/xion-xion.github.io/assets/css/style.css). Do not use dummy image placeholders (prefer SVGs).
