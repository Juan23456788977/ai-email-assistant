<div align="center">

# 🤖 AI Email Assistant

### Sistema de Respuesta Automática de Correos con IA
*AI-Powered Email Auto-Response & Classification System*

**🌐 English** | [🇪🇸 Español](#-español)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=10B981&center=true&vCenter=true&width=700&lines=OpenAI+GPT+Email+Auto-Response;ML+Importance+Classifier+(scikit-learn);FastAPI+Backend+%2B+Docker;Full-stack+AI+Customer+Support" alt="Typing SVG" />
</p>

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](#)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](#)

> ⚠️ **Showcase only — Source code is private.**

</div>

---

## 🎯 What is AI Email Assistant?

**AI Email Assistant** is a full-stack system that automatically reads incoming customer emails, classifies them by importance using a trained ML model, and generates intelligent responses using the OpenAI API — eliminating manual email triaging for customer support teams.

Built as a practical AI automation tool during internship at **Akdemia**.

---

## 🏗️ Architecture

```
ai-email-assistant/
├── backend/
│   ├── api/            ← FastAPI REST endpoints
│   ├── services/
│   │   ├── classifier.py   ← ML importance classifier (scikit-learn)
│   │   └── llm_response.py ← OpenAI GPT response generation
│   ├── models/         ← Data models
│   ├── db/             ← Database layer
│   ├── scripts/
│   │   └── train_classifier.py ← Model training script
│   └── utils/
├── frontend/           ← Dashboard UI
├── data/               ← Training datasets
└── docker-compose.yml
```

---

## ⚡ Core Features

### 🧠 AI / ML Engine
- **OpenAI GPT** — Generates context-aware email responses automatically
- **scikit-learn Classifier** — Trained ML model that classifies emails by importance (High / Medium / Low)
- **Custom training pipeline** — `train_classifier.py` trains on your own email dataset

### 📧 Email Processing
- Reads incoming emails automatically
- Classifies priority before routing
- Generates and sends AI responses
- Keeps human agents focused on high-priority cases only

### 🐳 Infrastructure
- **Docker Compose** — Full stack runs with one command
- **FastAPI** — High-performance async REST API
- Modular service architecture (classifier + LLM are independent services)

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **AI/ML** | OpenAI GPT API, scikit-learn |
| **Backend** | FastAPI, Python |
| **Infrastructure** | Docker, Docker Compose |
| **Data** | Custom training dataset |

---

<details>
<summary>🇪🇸 Español</summary>

## 🎯 ¿Qué es AI Email Assistant?

**AI Email Assistant** es un sistema full-stack que lee automáticamente los correos entrantes de clientes, los clasifica por importancia usando un modelo de ML entrenado, y genera respuestas inteligentes usando la API de OpenAI — eliminando el triaje manual de correos para equipos de soporte.

Desarrollado como herramienta de automatización con IA durante la pasantía en **Akdemia**.

## ⚡ Características Principales

- 🧠 **OpenAI GPT** — Genera respuestas de correo contextuales de forma automática
- 📊 **Clasificador ML** — Modelo entrenado con scikit-learn que clasifica emails por importancia
- 🔄 **Pipeline de entrenamiento** — Script para entrenar el modelo con datos propios
- 🐳 **Docker Compose** — Stack completo con un solo comando
- ⚡ **FastAPI async** — API REST de alto rendimiento

</details>

---

<div align="center">
  <b>Juan Alberto Cortez Urrea</b> — 18 años, Caracas, Venezuela 🇻🇪<br/>
  <a href="https://github.com/Juan23456788977">GitHub</a> ·
  <a href="mailto:cortezurreajuanalberto@gmail.com">Email</a> ·
  <a href="https://github.com/Juan23456788977/cortan-showcase">Ver Cortan v2.0</a>
</div>
