Here’s a polished README.md you can ship with your notebook and slides. It ties your talk, walkthrough, and Enkrypt AI resources together:

# 🚀 A Developer’s Guide to AI Safety & Security

Welcome to the official walkthrough for **A Developer’s Guide to AI Safety & Security**, a live session hosted by Tanay Baswa in collaboration with G2i.  

This repository contains the **Jupyter notebook** and **supporting materials** used in the talk, demonstrating how to red team and secure AI applications.

---

## 🎯 About This Walkthrough
In this session, we explored:
- **Baseline AI apps with no defenses** → showing how easily they can be exploited
- **Hardened system prompts** → building stronger role instructions
- **Guardrails detectors** → catching unsafe inputs and outputs
- **Policy-based Guardrails** → enforcing compliance and business rules
- **End-to-end secure flows** → combining all strategies for production-ready resilience

👉 Security is **not an afterthought**. It’s the foundation for responsible AI development.

---

## 🧑‍💻 Getting Started

### 1. Clone or open the notebook
This repo includes the Jupyter notebook used in the live demo.  

### 2. Install dependencies
```bash
pip install enkryptai-sdk openai python-dotenv tabulate pandas requests
```

3. Set environment variables

You’ll need both an OpenAI API key and an Enkrypt AI API key.

Create a .env file:

OPENAI_API_KEY=your-openai-key
ENKRYPTAI_API_KEY=your-enkryptai-key
ENKRYPTAI_BASE_URL=https://api.enkryptai.com

4. Run the notebook

Launch Jupyter Lab or Jupyter Notebook and step through the cells.

⸻

🌐 Useful Links
	•	Main Website: enkryptai.com
	•	App Dashboard (get your API key): app.enkryptai.com
	•	Documentation: docs.enkryptai.com
	•	Secure Chatbot Demo: securechatbot.vercel.app

⸻

📌 Key Takeaways
	•	Developers are on the frontlines of AI security — your design choices define whether apps are safe or exploitable.
	•	Defense-in-depth works best: System prompts + Guardrails + Policies together create strong protection.
	•	AI security is a career advantage — mastering it now puts you ahead as enterprises race to deploy AI.

⸻

👤 About the Speaker

Tanay Baswa
Founding AI Researcher & Engineer, Director of Solutions at Enkrypt AI
	•	UC Berkeley Computer Science
	•	Published at NeurIPS 2024 on AI Safety & Security
	•	2+ years building AI security solutions for enterprise customers

⸻

📄 License

This material is provided for educational and demonstration purposes.
© 2025 Enkrypt AI. All rights reserved.