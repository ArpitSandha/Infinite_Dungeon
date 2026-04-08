# The Infinite Dungeon: Adaptive Gamified Learning Platform

[![Live Demo](https://img.shields.io/badge/Live_Demo-Play_Now-00d2ff?style=for-the-badge&logo=streamlit)](https://infinitedungeon-ztcq4ozwvmfbxbc2rnf4tl.streamlit.app/)
[![Python 3.9+](https://img.shields.io/badge/Python-3.9+-blue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Powered by Gemini](https://img.shields.io/badge/AI-Google_Gemini-orange.svg?style=flat&logo=google)](https://aistudio.google.com/)

---

## Author  
Arpit Singh Sandha

---

## Live Demo  
https://infinitedungeon-ztcq4ozwvmfbxbc2rnf4tl.streamlit.app/

---

## Overview

The Infinite Dungeon is an AI-powered gamified learning platform that transforms traditional education into an interactive role-playing experience. The system dynamically adapts question difficulty, pacing, and feedback based on real-time user performance using large language models.

The platform integrates algorithmic problem-solving and conceptual assessment into a unified game environment, improving engagement and long-term retention.

---

## System Architecture

### Dual-AI Engine Design

**1. Algorithmic Evaluation Engine**
- Built using the modern `google-genai` SDK  
- Executes user-submitted code in a sandbox environment  
- Generates hidden edge-case test cases  
- Evaluates correctness and time complexity (Big-O analysis)  

**2. Conceptual Assessment Engine**
- Built using `google-generativeai`  
- Generates structured multiple-choice questions in strict JSON format  
- Assigns difficulty tiers dynamically (Level 1–6)  
- Ensures stable and parseable outputs  

---

## Core Features

- Dynamic Difficulty Adjustment based on user performance  
- AI-based code evaluation with hidden test cases  
- Multiple-choice combat system for conceptual learning  
- Player progression system including levels, XP, and inventory  
- Integrated code editor with syntax highlighting (streamlit-ace)  
- Responsive UI with advanced styling and animations  
- Audio feedback for enhanced interaction  

---

## Technical Stack

- Frontend Framework: Streamlit  
- Code Editor: streamlit-ace  
- AI Infrastructure: Google Gemini 2.5 Flash  
- Environment Management: python-dotenv  

---

## Project Structure

```

Infinite_Dungeon/
│── assets/
│── app1.py
│── requirements.txt
│── README.md
│── .gitignore

````

---

## Installation and Setup

### 1. Clone the repository
```bash
git clone https://github.com/ArpitSandha/Infinite_Dungeon.git
cd Infinite_Dungeon
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure environment variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_api_key_here
```

### 4. Run the application

```bash
streamlit run app1.py
```

---

## Deployment

The application is deployed using Streamlit Community Cloud:

[https://infinitedungeon-ztcq4ozwvmfbxbc2rnf4tl.streamlit.app/](https://infinitedungeon-ztcq4ozwvmfbxbc2rnf4tl.streamlit.app/)

---

## Future Enhancements

* User authentication and profile management
* Global leaderboard system
* Multiplayer gameplay features
* Performance analytics dashboard
* Database integration (MongoDB or Firebase)

---

## License

This project is licensed under the MIT License.
