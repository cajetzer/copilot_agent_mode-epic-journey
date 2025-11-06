---
mode: agent
description: Analyze the repository and create modular instruction files for GitHub Copilot
tools: ['search/codebase', 'edit/editFiles', 'search', 'github-remote/*']
---

# Create Modular Copilot Instructions

Analyze this repository and create a modular `.github/instructions/` directory with separate, focused instruction files for GitHub Copilot based on the codebase characteristics.

Determine which instruction files are necessary based on the codebase characteristics of this repository (e.g backend development, frontend development, database, etc.). Each file should be concise, actionable, and focused on its specific domain. Use [this repo](https://github.com/cajetzer/copilot_agent_mode-crispy-carnival/) as a model for structuring the instructions.

Update `.github/copilot-instructions.md` to be minimal with only essential repo metadata and high-level guidance needed in every session to reduce repeated analysis. Do NOT reference all instruction files in it. The modular files should be attached as context on-demand when needed for specific tasks.
