<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="assets/resources/appIcon.png"  alt="App Icon" width="100" height="100">

  <h1 align="center">Intellicash - AI Personal Finance Guide</h1>

  <p align="center">
    Intellicash is a next-gen personal finance platform powered by Google Cloud services like Firebase and Vertex AI, delivering enterprise-grade financial intelligence with consumer-level simplicity.
    <br />
    <a href="#about-the-project"><strong>Start exploring »</strong></a>
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->

  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#-why-intellicash">Why Intellicash?</a></li>
        <li><a href="#-core-google-cloud-integrations">Core Google Cloud Integrations</a></li>
        <li><a href="#-hybrid-ai-architecture">Hybrid AI Architecture</a></li>
        <li><a href="#-enhanced-technical-stack">Enhanced Technical Stack</a></li>
      </ul>
    </li>
    <li>
      <a href="#run-the-code-locally-">Run the code locally</a>
      <ul>
        <li><a href="#prerequisites-%EF%B8%8F">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#contributing-">Contributing</a>
      <ul>
        <li><a href="#how-to-get-started">How to get started</a></li>
        <li><a href="#why-to-contribute-">Why to contribute?</a></li>
      </ul>
    </li>
  </ol>

## About the project

### 📸 Screenshots

|                                                                                                                    |                                                                                                                    |                                                                                                                    |                                                                                                                    |
| :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| ![1](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva1.PNG) | ![2](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva2.PNG) | ![3](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva3.PNG) | ![4](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva4.PNG) |
| ![5](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva5.PNG) | ![6](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva6.PNG) |

### 🌟 Why Intellicash? 

- **Hybrid AI Intelligence**  
  Combines on-device ML processing with cloud-based AI models for smart financial analysis.
- **Google Cloud Powered**  
  Leverages Firebase, Cloud Functions, and BigQuery to deliver secure, scalable, real-time insights.
- **Smart Transaction Categorization**  
  Achieves 98% accuracy using a blend of local ML models and Vertex AI.
- **Natural Language Queries**  
  Ask questions like "Show food spending last month" using built-in NLP support.
- **Predictive Forecasting**  
  Uses Vertex AI to provide future budget estimates based on spending patterns.
- **Scalable Data Handling**  
  Handles millions of transactions using Firestore and Cloud SQL.
- **Cross-Device Sync**  
  Seamless real-time data synchronization across all your devices.
- **Advanced Security**  
  End-to-end encryption, IAM, and Google Cloud Secret Manager integration.
- **Open Source First**  
  Built with transparency and privacy in mind—local-first where possible.

### 🚀 Core Google Cloud Integrations

1. **Firebase Platform**
   - Secure authentication (OAuth, biometrics, 2FA)
   - Firestore with offline sync
   - Cloud Functions for backend automation
   - Crashlytics for bug and crash tracking

2. **Vertex AI Services**
   - Custom-trained classification models
   - AutoML Tables for time-series forecasting
   - Natural language understanding for finance
   - Anomaly detection for fraud and outliers

3. **Google Cloud Infrastructure**
   - Microservices with Cloud Run
   - Pub/Sub for real-time event streaming
   - Secret Manager for key management
   - Cloud SQL and BigQuery for data analytics

### 🔄 Hybrid AI Architecture

**Data Flow:**

`[Device] → [Firebase] → [Cloud Functions] → [Vertex AI] → [BigQuery] ↑____________↓ ↑ [Local SQLite]`

**Architecture Highlights:**

- **Local Intelligence**
  - Offline transaction tracking using SQLite
  - On-device models with TensorFlow Lite

- **Cloud Augmentation**
  - Cloud model inference via Vertex AI
  - Real-time sync through Firestore

- **Security-First Design**
  - IAM, encryption at rest, and audit logging

### 🔧 Enhanced Technical Stack

**Frontend:**
- Flutter with Firebase integration
- Google Maps for location tagging
- Interactive charts via Google Charts

**Backend Services:**
- Cloud Run containers
- Cloud Scheduler for automation
- Memorystore (Redis) for caching

**Data Pipeline:**
- Dataflow for ETL
- BigQuery for advanced analytics
- Looker Studio for dashboards

**ML Operations:**
- Vertex AI Pipelines for MLOps
- Model monitoring and auto-retraining

---

## Run the code locally 🚀🧑‍💻

Intellicash is fully open-source and easy to set up locally. Whether you're contributing, learning, or exploring—you're welcome here!

### Prerequisites 🛠️

1. **Flutter SDK** – Install from the [official guide](https://docs.flutter.dev/get-started/install)
2. **Code Editor (Optional)** – [VS Code](https://code.visualstudio.com/) or Android Studio recommended

### Getting the Project 📂

**Option 1: Download as ZIP**
- Go to the [IntelliCash GitHub Repo](https://github.com/Sudoerz/IntelliCash)
- Click **Code** > **Download ZIP**
- Extract to your desired folder

**Option 2: Clone the Repo**
```bash
git clone https://github.com/Sudoerz/IntelliCash
```

### Installation 📦

Navigate to the project folder and install dependencies:

```bash
flutter pub get
```

### Run the App ▶️

Run the app on an emulator or connected device:

```bash
flutter run
```

---

## Contributing 🙋🏻

### How to get started

1. **Fork the repo**

New to forking? Use [this GitHub guide](https://docs.github.com/en/get-started/quickstart/fork-a-repo) to fork and set up your copy.

2. **Set up your workspace**

Clone your fork locally, then open it using your preferred code editor.

We recommend **Visual Studio Code**, along with the Flutter extension pack. Type `@recommended` in the extensions tab to install all project-recommended tools.

---

### Why to contribute 🙌

Contributing to Intellicash gives you a chance to:

- 🚀 Learn practical Flutter + Firebase development
- 🌍 Work with an open-source community
- 🔧 Understand full-stack cloud-native architectures
- 💼 Build your GitHub portfolio with meaningful contributions
- 💡 Help people take control of their finances with AI

All skill levels are welcome — whether you're fixing typos, improving UI, writing docs, or building features.

---

**Credits:**  
- [Google Cloud](https://cloud.google.com/) – for cloud infrastructure and AI services.
- [Firebase](https://firebase.google.com/) – for authentication, database, and analytics.
- [Monekin](https://github.com/enrique-lozano/Monekin) – for financial tracking design and structure.
- [Vertex AI](https://cloud.google.com/vertex-ai) – for integrating generative AI capabilities.
- [Chroma DB](https://www.trychroma.com/) – for vector search and semantic memory.
- [MCP](https://mcp.sudomate.ai/) – for natural language SQL and fast API workflows.

