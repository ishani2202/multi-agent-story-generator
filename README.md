# 🌙 Multi-Agent Bedtime Story Generator  
A safe, gentle, multi-agent storytelling system powered by GPT-3.5 Turbo.

This project generates bedtime stories for children ages 5–10 using a **multi-agent LLM pipeline** consisting of a **Storyteller**, **Judge**, **Reviser**, and **Moral Generator**. The system ensures stories remain emotionally safe, age-appropriate, and structurally coherent while offering user-controlled **tone** and **story length** options.

---

## ✨ Project Overview

This project demonstrates:

- Multi-agent prompting with well-defined roles  
- Safety-aware and child-centered content generation  
- Structured agent interaction and revision loops  
- Clean, modular Python design  
- Optional tone and length customization for storytelling  
- Extensibility toward multimodal and ML-driven improvements  

---

## 🚀 Features

### 📝 Storyteller Agent  
Creates the first draft of the bedtime story using:
- A gentle tone  
- Clear story arc (Beginning → Middle → End)  
- Age-appropriate vocabulary  
- Optional **tone** (cozy, magical, silly, sleepy, exciting…)  
- Optional **length** (short, medium, long)  

### 🧠 Judge Agent  
Evaluates the draft for:
- Emotional safety  
- Age suitability  
- Vocabulary simplicity  
- Coherence and clarity  
- Presence of a helpful lesson  

Responds with either:
- `"approved"`  
**or**  
- A concise set of revision instructions  

### 🔧 Reviser Agent  
If needed, rewrites the story according to the judge's feedback.

### 🌟 Moral Generator  
Produces a one-sentence moral aligned with the final story.

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/multi-agent-bedtime-story-generator.git
cd multi-agent-bedtime-story-generator
