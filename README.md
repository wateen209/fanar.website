#  Fanar | Smart Architectural Review Platform

**Fanar** is an intelligent platform that redefines the architectural design ecosystem by creating a unified interface connecting design studios, consulting offices, and regulatory entities through AI and IoT technologies.

---

##  The Idea

Fanar addresses four major challenges in the architectural design process:

1. Inconsistent expertise among consulting offices leading to variable design quality.  
2. Lack of digital coordination between parties, resulting in repetitive revisions and delays.  
3. Difficulty in aligning with municipal and environmental regulations for governance compliance.  
4. Absence of real-time environmental sustainability monitoring during project execution.  

---

##  The Solution

An intelligent web platform powered by **AI**, **NLP**, **LangChain**, **AR**, and **IoT** that:

- Analyzes building regulations and urban codes.  
- Provides smart design review suggestions.  
- Monitors surrounding environmental factors live using smart sensors.  

---

##  Technologies Used

| Field                            | Technology / Tool       | Usage Description                                                                              | Algorithms / Mechanisms                                                                                                                    |
| -------------------------------- | ----------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Artificial Intelligence (AI)** | OpenAI GPT-4 API        | Automatically analyzes project regulatory requirements and generates smart design suggestions. | 🔹 *Natural Language Processing (NLP)*<br>🔹 *Text Embedding* for understanding regulations<br>🔹 *Prompt Engineering* for precise outputs |
| **Extended Reality (AR/XR)**     | A-Frame + Three.js      | Displays architectural models in a 3D interactive web environment.                             | 🔹 *WebXR Device API* for immersive interaction<br>🔹 *Scene Graph Rendering* via Three.js                                                 |
|                                  | Blender                 | Designs and models 3D elements.                                                                | 🔹 *Mesh Modeling*<br>🔹 *UV Mapping* for visual optimization                                                                              |
|                                  | AR.js / Adobe Aero      | Allows real-world AR model previews via camera.                                                | 🔹 *Marker-based* or *Markerless AR* to bind models to real locations                                                                      |
| **Internet of Things (IoT)**     | MQTT + Firebase         | Simulates environmental data (e.g., air quality, energy) and visualizes it.                    | 🔹 *Publish/Subscribe Pattern* in MQTT<br>🔹 *Real-time Sync* via Firebase Realtime Database                                               |
| **Front-End**                    | React.js + Tailwind CSS | Builds a fast and responsive user interface.                                                   | 🔹 *Component-Based Architecture*<br>🔹 *Responsive Design* using Tailwind                                                                 |
|                                  | WebXR Integration       | Integrates XR scenes directly into the browser.                                                | 🔹 *WebGL Rendering*<br>🔹 *Device Orientation & Input Mapping*                                                                            |
| **Back-End**                     | FastAPI                 | Handles integration between AI, IoT data, and 3D visualizations.                               | 🔹 *RESTful API Endpoints*<br>🔹 *Asynchronous Processing* with Python and Uvicorn                                                         |
| **Storage & Hosting**            | Firebase + Vercel       | Stores data and models, manages sessions, and hosts the frontend.                              | 🔹 *Cloud Firestore* for storing design data<br>🔹 *CI/CD Deployment* via Vercel                                                           |


---

##  Expected Impact

Improve design quality by over **40%**  
Reduce review time by up to **60%**  
 Decrease repetitive revisions by **50%**  
 Enhance compliance with environmental and governance standards  
 Promote **Aseer’s architectural identity** through scalable modern technology  

---

## How to Run Locally

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
