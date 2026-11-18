# Ximena Macavilca — AI Career Portfolio

[Visit the website](https://ximena-ai-career-research.creamcedar20.chatgpt.site)

A personal career-research and project portfolio exploring AI forward-deployed engineering, AI solutions architecture, and AI business analysis. Built for Information Systems coursework and early-career planning at NJIT, with expected graduation in January 2029.

## Pages

| File | Purpose |
| --- | --- |
| `dist/index.html` | Career research, employer sources, skills roadmap, and background |
| `dist/projects.html` | Summaries of 14 public GitHub repositories and the Nest team project |
| `dist/personas.html` | Hypothetical Google and Accenture employer personas and Agile traceability |
| `dist/consulting-plan.html` | Consulting portfolio themes, epics, stories, tasks, priorities, and acceptance criteria |
| `dist/consulting-backlog.json` | Downloadable backlog with persona links |
| `dist/agile.html` | Retained educational login/registration/dashboard example; removed from navigation |

The personas are fictional planning tools informed by cited employer examples, not real employees or validated employer interviews. Backlog stories remain proposed unless supported by delivery evidence. Employer descriptions are dated research, not promises of future openings or personal eligibility. Project summaries distinguish exercises, unfinished work, and team contributions.

## Run locally

Requires Python 3. No package installation or build is required.

```sh
git clone https://github.com/XimenaMacavilca12/ai-career-portfolio.git
cd ai-career-portfolio
python3 -m http.server 3000 --directory dist
```

Open <http://localhost:3000>. Stop with **Ctrl+C**.

The site uses HTML, CSS, and browser JavaScript. Fonts load from Google Fonts with local fallbacks. Roadmap checkboxes use browser-local storage and do not sync between devices. No account system or backend is implemented.

## Editing and validation

Edit files in `dist/` directly. Keep persona references, story IDs, tasks, and acceptance criteria consistent between `consulting-plan.html`, `personas.html`, and `consulting-backlog.json`.

With Node.js available, check JavaScript syntax:

```sh
node --check dist/app.js
node --check dist/agile.js
node --check dist/consulting-plan.js
```

Review links, keyboard navigation, mobile layout, filters, and downloads in a browser. Earlier environment checks verified internal links and backlog consistency; they do not replace visual review.

## Hosting

This is a source snapshot of the existing Sites-hosted portfolio. Pushing here does **not** automatically update the live website. Publish through the existing Sites workflow or configure hosting separately. This repository contains no hosting credentials, uploaded résumé, or local browser data.

Snapshot exported November 18, 2026, from portfolio source commit `2c4b22b785b3fcb4df37028fda2db2d8fc53be10`.

## Feedback and attribution

Use GitHub Issues for feedback. Include the page, expected behavior, actual behavior, and relevant story ID when applicable.

Third-party projects and employer sources remain owned by their respective authors and are linked for reference. Team contributions and tool assistance should be credited accurately.
