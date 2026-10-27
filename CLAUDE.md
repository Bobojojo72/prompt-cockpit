# Prompt Engineering Cockpit: single-page app on GitHub Pages
- Everything is in index.html: 513KB, ~7,400 lines. NEVER read it whole.
  Grep for what you need, then read only those lines.
- Data lives in named arrays; grep the name to find it:
  SKILLS_DATA, BEST_PROMPTS_DATA, INTERACTION_TEMPLATES, CCM_WORKFLOWS, PT_GROUPS, TP_GROUPS
- Tabs switch via switchTab('<name>'); grep data-tab="<name>" for a tab's markup.
- Don't rename localStorage keys (see BACKUP_KEYS): Jo's saved prompts and settings would vanish.
- No build step, no tests. Check changes by loading the page in Playwright.
- Answer directly. Don't restate your reasoning in the reply.
- Read TASKS.md at the start of a session and keep it current (rule inside).
