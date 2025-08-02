<!-- PROJECT LOGO -->
<br />
<div align="center">
    <img src="assets/resources/appIcon.png"  alt="App Icon" width="100" height="100">

  <h1 align="center">Intellicash - AI Personal Finance guide</h1>

  <p align="center">
    Intellicash is a next-gen personal finance platform powered by Google Cloud services including Firebase, Vertex AI, and Fi Money's MCP server, delivering enterprise-grade financial intelligence with consumer simplicity.
    <br />
    <a href="#about-the-project"><strong>Start exploring »</strong></a>
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
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
</details>

## About the project

### 📸 Screenshots

|                                                                                                                    |                                                                                                                    |                                                                                                                    |                                                                                                                    |
| :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| ![1](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva1.PNG) | ![2](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva2.PNG) | ![3](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva3.PNG) | ![4](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva4.PNG) |
| ![5](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva5.PNG) | ![6](https://github.com/enrique-lozano/Monekin/blob/main/app-marketplaces/screenshots/en/Mockups/Diapositiva6.PNG) |

### 🌟 Why Intellicash? 

- **Hybrid AI Intelligence**  
  Combines on-device processing with cloud AI through Fi Money's MCP server and Google Vertex AI.
- **Google Cloud Powered**  
  Enterprise-grade infrastructure with Firebase, Cloud Functions, and BigQuery analytics.
- **Smart Transaction Categorization**  
  Uses both local ML models and cloud AI for 98% accurate categorization.
- **Natural Language Processing**  
  Ask questions like "Show food spending last month" using Vertex AI's NLP.
- **Financial Forecasting**  
  Vertex AI time-series forecasting for budget predictions.
- **Unlimited Transactions**  
  Scales to millions of transactions via Firestore and Cloud SQL.
- **Multi-Device Sync**  
  Real-time data synchronization across devices with Firebase.
- **Advanced Security**  
  Google Cloud IAP, Secret Manager, and encryption at rest.
- **Open Source Core**  
  Fully transparent local-first architecture.

### 🚀 Core Google Cloud Integrations

1. **Firebase Platform**
   - Authentication with OAuth, biometrics, and 2FA
   - Firestore with offline persistence
   - Cloud Functions for transaction processing
   - Crashlytics for performance monitoring

2. **Vertex AI Services**
   - Custom financial classification models
   - AutoML Tables for cash flow forecasting
   - NLP for transaction memo analysis
   - Anomaly detection algorithms

3. **Google Cloud Infrastructure**
   - Cloud Run microservices
   - Pub/Sub event processing
   - Secret Manager for credentials
   - Cloud SQL for analytics

### 🔄 Hybrid AI Architecture

**Data Flow:**
[Device] → [Firebase] → [Cloud Functions] → [Vertex AI] → [BigQuery] ↑____________↓ ↑ [Local SQLite] [Fi Money MCP]


**Key Features:**
1. **On-Device Processing**
   - TensorFlow Lite models
   - Local SQLite database
   - Offline transaction recording

2. **Cloud Enhancements**
   - Vertex AI model serving
   - Firestore synchronization
   - MCP server integrations

3. **Security Model**
   - End-to-end encryption
   - IAM role-based access
   - Audit logging

### 🔧 Enhanced Technical Stack

**Frontend:**
- Flutter with Firebase plugins
- Google Maps Platform for location tagging
- Charts powered by Google Charts

**Backend Services:**
- Cloud Run containers
- Cloud Scheduler for batch jobs
- Memorystore for caching

**Data Pipeline:**
- Dataflow for ETL
- BigQuery analytics
- Looker Studio dashboards

**ML Operations:**
- Vertex AI Pipelines
- Model monitoring
- Continuous retraining


## Run the code locally 🚀🧑‍💻

IntelliCash is fully open-source, allowing you to run it locally on your device. Whether you’re curious about how the app works, planning to contribute, or simply exploring, this guide provides all the steps to get started.


### Prerequisites 🛠️

Before running IntelliCash, ensure you have the following tools installed:

1. **Flutter SDK**: Follow the [official installation guide](https://docs.flutter.dev/get-started/install) to set up Flutter on your system.
2. **Code Editor (Optional)**: Tools like [Visual Studio Code](https://code.visualstudio.com/) or Android Studio make managing Flutter projects easier.

### Getting the Project 📂

You can choose one of two ways to obtain the project:

### Option 1: Download as ZIP File (No Git Required)

1. Go to the [IntelliCash GitHub Repository](https://github.com/Sudoerz/IntelliCash).
2. Click the green **Code** button, then select **Download ZIP**.
3. Extract the ZIP file to a folder of your choice.

### Option 2: Clone the Repository (Recommended for Contributors)

1. Open a terminal in the folder where you want the project.
2. Run the following command:

   ```bash
   git clone https://github.com/Sudoerz/IntelliCash
   ```

### Installation📦

Once you’ve downloaded or cloned the project, navigate to the project directory and install the required dependencies using Flutter:

```bash
flutter pub get
```

### Running the App ▶️

With the setup complete, you can run the app on a connected device or an emulator:

```bash
flutter run
```

If everything is set up correctly, the app will launch, and you’ll be able to test its features locally.


## Contributing 🙋🏻

### How to get started

### 1. Fork the repo

To start, fork the project. If you are new to this, don't worry! We leave you a guide below, and if you still have problems, you can contact us whenever you wish.

**[How To Fork Guide - by GitHub.com](https://docs.github.com/en/get-started/quickstart/fork-a-repo)**

After that you should [run your app](https://github.com/Sudoerz/IntelliCash) to check that everything is correct.

### 2. Configure your developer workspace

Once you have the project up and running, you should prepare to develop in Monekin. To make changes to the project and develop on it, the use of **[Visual Studio Code](https://code.visualstudio.com/)** as a text editor is strongly recommended. You can use any other code editor, you can even program using Word, but Visual Studio Code is the most widespread editor for Front-End development, and using it guarantees you follow the same work methods as the administrators of this project.

### Visual Studio and Recommended extensions

To increase your productivity on this project, it is strongly recommended to install the recommended extensions. To do this, when you have the project open with Visual Studio Code, you can type `@recommended` in the extensions section, and install all the ones that appear in the list.

And that's it! You're are ready to start.


### Why to contribute 🙌

Contributing to IntelliCash is more than just writing code — it's an opportunity to:

- 💡 Learn and grow your skills with real-world Flutter development
- 🤝 Collaborate with a welcoming open-source community
- 🧠 Understand how a full-stack Flutter app is structured and maintained
- 📢 Build your GitHub profile with meaningful contributions
- 🔥 Help improve a finance app that helps users manage money better

Whether you’re a beginner exploring open source or an experienced developer, there’s always a way to add value — from fixing bugs and optimizing performance to improving documentation or adding new features.


**Note:** Intellicash is a fork of the original [Monekin](https://github.com/enrique-lozano/Monekin) project, enhanced with Google Cloud services and Fi Money MCP integration while maintaining its open-source core. The app offers a unique combination of local data privacy and cloud-powered intelligence.
