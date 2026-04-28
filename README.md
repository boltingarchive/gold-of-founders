# 🛠️ Foundry: Pure Ideas

### [Visit the Live Site](https://your-username.github.io/your-repo-name/)

> **The "No-AI" Antidote to Startup Stall.** Born in the heat of Australia, **Foundry** is a minimalist, open-source business blueprint generator designed for builders who are tired of the "AI hype train." While everyone else is burning GPU credits asking a chatbot for a generic startup idea, Foundry uses structured, human-curated logic to spark genuine creative collisions.

---

## 🇦🇺 The Philosophy: "Keep it Simple, Mate."

In a world of bloated software and complex APIs, Foundry is a return to the basics. No trackers, no cookies, no LLM hallucinations. Just pure, deterministic randomness.

- **Zero Dependency:** No React, no Tailwind, no NPM. It’s a single `index.html` file.
- **Human-Curated:** The logic engine is built on hand-crafted arrays of industries, problems, and business models. 
- **Lightning Fast:** It loads before you can finish your first sip of a flat white.
- **Open Source:** If you don't like an idea, fork the repo and change the source code. It's your machine now.

## ⚙️ The Engine

The "Logic Engine" isn't a black box. It's a transparent JavaScript system that cross-references:
* **20+ Business Models** (Subscription, P2P, White-Label...)
* **20+ Underserved Industries** (Maritime, Rural Ag, Aged Care...)
* **20+ Real-World Pain Points** (Cash-flow gaps, Compliance burden, Knowledge capture...)

With over **8,000 unique permutations**, the goal isn't to give you a finished business plan—it's to force a "collision" in your brain that leads to a real solution.

## 🚀 Deployment (The 60-Second Set Up)

This project is built to be hosted on **GitHub Pages** for $0.

1.  **Fork** this repository.
2.  Head to **Settings > Pages**.
3.  Set the branch to `main` and the folder to `/ (root)`.
4.  Hit save. Your site is live.

## 🛠️ Modifying the "Brain"

Want to add your own niche industries or specific problems? Open `index.html`, scroll down to the `IDEA_DATABASE` constant, and start typing. 

```javascript
const IDEA_DATABASE = {
  BusinessModels: ['Your New Model', ...],
  Industries: ['Your Local Niche', ...],
  Problems: ['A Specific Headache', ...]
};
