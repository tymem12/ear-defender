# 🎧 EarDefender

A Next-Generation Web Platform for Detecting Audio DeepFakes

## 🚀 Overview

EarDefender is a modular web application designed to automatically search selected social media platforms (e.g., YouTube), extract audio/video materials, analyze them for potential audio DeepFakes using advanced AI models, and generate a comprehensive verification report.

The system presents the entire pipeline:

**web scraping** → **audio extraction** → **DeepFake detection** → **detailed reporting**

Users can also choose their preferred detection approach, making the analysis adaptable to different use-cases and accuracy requirements.

## 🧩 Architecture Summary

EarDefender is built as a multi-service system, each module handling a distinct part of the workflow:

**Frontend** – user-facing web interface

**Connector** – orchestrates service communication

**Scraper** – searches the internet and downloads A/V content

**Detector** – performs DeepFake audio analysis (e.g., SSL-wav2vec, MesoNet)


All modules are containerized and can be deployed together using Docker Compose.

## 🔗 Submodules

To learn more about the implementation or explore each part individually, visit the dedicated repositories:

### Frontend – UI
https://github.com/tymem12/ear-defender-frontend

### Connector – module integration
https://github.com/tymem12/ear-defender-connector

### Scraper – content discovery & downloading
https://github.com/tymem12/ear-defender-scraper

### Detector – DeepFake prediction models
https://github.com/tymem12/ear-defender-model


## 🧠 Research & Article

A detailed description of the methodology, datasets, model evaluation (including EER, accuracy, and cross-dataset performance), and implementation can be found in our research paper:

👉 https://openreview.net/forum?id=Wr9bnLMcLQ


## ⚙️ Getting Started

To run the full system locally:

1. Clone the repository:

`git clone https://github.com/tymem12/ear-defender.git`


2. Navigate into the project root and start all services:

`docker-compose up --build`


3. Open the app in your browser:

`http://localhost:8080`



## 👥 Authors

- **Łukasz Jałocha**

- **Łukasz Janiak**

- **Tymoteusz Zapała**


If you’d like to collaborate or discuss DeepFake detection, ML research, or microservice architectures — feel free to reach out.

## 📌 Roadmap

- More advanced and adversarial-resistant detection models

- Support for additional social media platforms

- Cloud-native production deployment with monitoring & API

- Publication of extended experimental results
