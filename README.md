# JEIR — Type 3 Diabetes AI Assistant (Public Showcase)

> Navigate health education with **JEIR** 🥕 — an AI assistant that explains the science linking insulin resistance, metabolic health, and cognitive decline often described as “Type 3 diabetes.” Built by **Mindful Diabetes Inc.** for learning and empowerment.

[▶ Open JEIR](https://www.mindfuldiabetes.ai/) · [Alt Domain](https://jeir.ai) · [Privacy & Safety](#privacy--safety) · [Contact](#contact)

---

<p align="center">
  <img src="assets/jeir-home.png" alt="JEIR landing page with Quickstart, GitHub, YouTube, Join, and GoFundMe cards" width="900">
</p>

## What JEIR Does
- **Clear answers with sources** — Ask about insulin resistance in the brain, diet & exercise basics, the AD–T2D connection, and more.
- **Actionable suggestions** — e.g., “Can you make me a 21-day walking routine?”
- **Friendly guardrails** — Educational tone, plain-language summaries, and reminders to consult clinicians for personal care.

> **Scope:** JEIR is an **educational assistant**. It does **not** diagnose, treat, or provide medical advice.

## Quickstart
1. **Open:** https://www.mindfuldiabetes.ai/ (or https://jeir.ai)  
2. **Sign in:** Email or **Continue with Google** (Kinde Authentication).
3. **Ask a question:** Use the suggested prompts or type your own.
4. **Review sources:** Where applicable, JEIR includes citations/sourcing to help you learn more.

<p align="center">
  <img src="assets/jeir-login.png" alt="Kinde login screen for JEIR by Mindful Diabetes Inc." width="520">
</p>

## Example
**You:** *What is the connection between Alzheimer’s Disease & Type 2 Diabetes?*  
**JEIR:** Explains evidence around insulin resistance, chronic inflammation, vascular health, amyloid burden, and shared lifestyle risk factors — with plain-language takeaways and references.

<p align="center">
  <img src="assets/jeir-chat.png" alt="JEIR chat UI with suggested question chips and input box" width="900">
</p>

<p align="center">
  <img src="assets/jeir-answer.png" alt="JEIR answer card explaining AD-T2D links in sections" width="900">
</p>

## How It Works (High-Level)
- **Web app UI** for chat + suggested prompts
- **Auth via Kinde** (email/Google) to protect usage and settings
- **Retrieval-augmented generation** over a **curated knowledge base** (Mindful Diabetes content and reputable sources)
- **Citations/links** surfaced where available
- **Guardrails** to keep responses educational and safety-aware

*Production code is private. This repository is a public, docs-only showcase.*

## Privacy & Safety
- **No PHI required** to explore the assistant.
- **Server-side keys only;** credentials are never exposed client-side.
- Educational content only; **not medical advice.** Always talk to a licensed healthcare professional for diagnosis or treatment.

(Optional) **Analytics/Status:** If you expose a public dashboard, link it here.  
`[Live Analytics](https://your-analytics-url.example)` <!-- replace or remove -->

## Screenshots
- `assets/jeir-home.png` — Landing
- `assets/jeir-login.png` — Login (Kinde)
- `assets/jeir-chat.png` — Chat UI
- `assets/jeir-answer.png` — Example answer

> Drop your images into `/assets/` with the names above, or update the paths here.

## Roadmap (Selected)
- Multilingual responses (ES/EN)
- More lifestyle templates (e.g., walking plans, grocery lists)
- Expanded source surfacing & bibliographies
- Classroom mode for workshops

## Credits
- **Lead:** Joseph-Michael Schulz (Mindful Diabetes Inc.)
- **Mission:** Make metabolic & cognitive health knowledge accessible, practical, and hopeful.

## License
Documentation in this repository is released under the **MIT License**.  
The production application source code is private.

## Contact
Questions, partnerships, or media?  
**Mindful Diabetes Inc.** · jmschulz@mindfuldiabetes.org

---

**Open JEIR:** https://www.mindfuldiabetes.ai/ (alt: https://jeir.ai)
