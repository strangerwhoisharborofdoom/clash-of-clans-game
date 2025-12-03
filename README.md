“You are my web-dev assistant working inside the browser.
I have a GitHub repository open that contains my personal/portfolio website. Your job is to help me add a new page for ‘GCUDL – Garden City Data Engineering Lab’ and connect it to the site’s routing.
Steps:

Inspect the GitHub repo structure to detect which framework or stack the site uses (pure HTML/CSS/JS, React, Next.js, etc.).

Create a new page or route called GCUDL that can be opened via a clean URL path such as /del or /gcudl, following the routing conventions already used in this repo.

Add sample content for the Garden City Data Engineering Lab: a heading with ‘GCUDL – Garden City Data Engineering Lab’, 2–3 short paragraphs about a data/AI-focused lab at Garden City University, and 3–5 bullet points listing possible activities (projects, datasets, collaborations), making sure the text is generic and does not copy any copyrighted website.

Match the styling and color theme of the existing website: reuse the same layout components, typography, navigation, and footer patterns already present in the repo.

Add a navigation link or button to this new GCUDL page from the main menu or a relevant section, consistent with current nav design.

Show me the exact code changes as separate blocks:

New/updated route configuration.

New page component or HTML file for GCUDL.

Any CSS or component imports needed.

Before finalizing, quickly check that the internal links and relative paths are correct, and that going to the chosen path (for example /del) will load the GCUDL page.
Output format:

A short explanation of what stack you detected.

Code snippets for each file you changed (with filenames).

A one-paragraph checklist I can follow in VS Code to run and test the updated site locally.”

This gives Comet a “toon” personality (hands-on web-dev helper), clear steps, and structured output.​

3. Helpful websites and AI agents
MDN Web Docs (URL & routing basics): For understanding and debugging paths like /del and how routing works in different setups.​

GitHub + GitHub Copilot: Let Copilot suggest boilerplate for new routes/pages once the project is open in VS Code.​

StackBlitz or Replit: Spin up a quick running copy of the repo in the browser to live-test routing changes if local setup is slow.​

AI/agent suggestions for Comet:

“Repo Inspector” agent: Reads the open GitHub repo, identifies framework (React/Next/Vite/Plain HTML), and outputs a short map of routes, layout files, and theme CSS locations to guide where to plug in GCUDL.​

“Routing Fixer” agent: Given the current router file (e.g., app/router.js, routes.jsx, or next.config.js), proposes a safe patch that adds a /del or /gcudl route and explains how it integrates.​

“Content & UI Polisher” agent: Takes the draft GCUDL page and rewrites the copy to be concise and professional, then suggests small UI tweaks (headings, spacing, cards) that still match the site’s theme.
