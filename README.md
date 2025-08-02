# 🌟 Fanar | Smart Architectural Review Platform

**Fanar** is an intelligent platform that redefines the architectural design ecosystem by creating a unified interface connecting design studios, consulting offices, and regulatory entities through AI and IoT technologies.

---

## 🎯 The Idea

Fanar addresses four major challenges in the architectural design process:

1. Inconsistent expertise among consulting offices leading to variable design quality.  
2. Lack of digital coordination between parties, resulting in repetitive revisions and delays.  
3. Difficulty in aligning with municipal and environmental regulations for governance compliance.  
4. Absence of real-time environmental sustainability monitoring during project execution.  

---

## 🧠 The Solution

An intelligent web platform powered by **AI**, **NLP**, **LangChain**, **AR**, and **IoT** that:

- Analyzes building regulations and urban codes.  
- Provides smart design review suggestions.  
- Monitors surrounding environmental factors live using smart sensors.  

---

## ⚙️ Technologies Used

| Domain           | Technologies                                                                 |
|------------------|------------------------------------------------------------------------------|
| Frontend         | React.js, Tailwind CSS                                                       |
| Backend          | FastAPI                                                                      |
| NLP & AI         | OpenAI GPT-4, LangChain, spaCy                                               |
| Database         | PostgreSQL                                                                   |
| Authentication   | Firebase Auth                                                                |
| File Management  | Cloudinary                                                                   |
| IoT & AR         | IoT Sensors, AR Integration (e.g., WebXR / AR.js)                           |

---

## 📈 Expected Impact

✅ Improve design quality by over **40%**  
⏱ Reduce review time by up to **60%**  
✏️ Decrease repetitive revisions by **50%**  
🌍 Enhance compliance with environmental and governance standards  
🏛 Promote **Aseer’s architectural identity** through scalable modern technology  

---

## 🚀 How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/username/fanar-platform.git
cd fanar-platform

# 2. Run the frontend
cd frontend
npm install
npm run dev

# 3. Run the backend
cd ../backend
pip install -r requirements.txt
uvicorn main:app --reload
