# Context Fundamentals Workshop

**Tips**:
- Pay attention to which mode you are in: Ask Mode, Agent Mode, or Plan Mode.
- Keep context relevant by starting a new session when switching tasks.
- Try different models to see which works best for your use case, or use Auto to let Copilot choose. See [https://docs.github.com/en/copilot/reference/ai-models/model-comparison]https://docs.github.com/en/copilot/reference/ai-models/model-comparison

## 1. Clone the Repository

Clone [https://github.com/cajetzer/copilot_agent_mode-epic-journey/](https://github.com/cajetzer/copilot_agent_mode-epic-journey/)

---

## 2. Get to Know the Codebase or Ask if Your Workspace is Properly Set Up (Ask Mode)
- Try: `#codebase where is auth initialized?`
- Try: `is my @workspace properly configured for this project?`

---

## 3. Start the github-remote MCP Server
- Click the Tools icon in Copilot Chat
- Click the settings gear for the server
- Click **Start** for the server in the config file

---

## 4. Ask Copilot to Enhance `copilot-instructions.md` (Agent Mode)
- Try: `enhance #file:copilot-instructions.md using the instructions in this repo as a model: https://github.com/cajetzer/copilot_agent_mode-crispy-carnival`

---

## 5. Build Specialized Custom Instructions – Tailored Instructions Without Context Bloat (Agent Mode)
- Try the saved prompt: `/create-modular-instructions.prompt`

---

## 6. Plan the Implementation of a New Feature (Plan Mode)
- Review instructions in `.github/chatmodes/Plan.chatmode.md`
- Try: `/plan-qna implement a new welcome page; note questions asked to build better plan`

---

## 7. Use Plan Mode with Injected Requirements (Plan Mode)
- Try: `/plan-qna implement #file:cart-requirements.md`
- Try: (Agent Mode) save the plan as `cart-plan.md`

---

## 8. Start Incremental Implementation (Agent Mode)
- Try: Implement first increment of the `#file:cart-plan.md`
