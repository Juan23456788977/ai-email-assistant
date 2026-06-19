<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />

  <br />

  <h1 style="color: #10B981;">🤖 AI Email Assistant</h1>
  <p><b>ML Classifier & Auto-Responder / Clasificador ML y Auto-Respondedor</b></p>
  
  <p>
    <i>Bilingual Documentation (English & Español)</i>
  </p>
</div>

---

## 🌍 Overview / Descripción General

**(EN)** A decoupled background system that reads incoming emails, classifies them by priority using a **trained scikit-learn model**, and generates contextual responses via **OpenAI GPT**. The `classifier.py` and `llm_response.py` services are intentionally decoupled so the LLM provider can be swapped without touching the core classification logic.

**(ES)** Sistema en segundo plano que lee correos entrantes, los clasifica por prioridad con un **modelo entrenado en scikit-learn**, y genera respuestas con **OpenAI GPT**. Los servicios `classifier.py` y `llm_response.py` están desacoplados para poder cambiar el LLM sin afectar la lógica matemática de clasificación.

---

## 🛠 Tech Stack / Tecnologías

- `FastAPI` `Python 3` `OpenAI API` `scikit-learn` `Pandas` `Docker Compose`

<div align="center">
  <i>🔒 Private Source Code / Código Privado 🔒</i>
</div>
