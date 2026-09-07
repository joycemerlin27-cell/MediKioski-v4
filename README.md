# 🏥 MediKiosk — AI-Powered OPD Patient Case-Taking System

> **MediKiosk** is a smart digital OPD patient case-taking and queue management platform designed to reduce the workload on doctors by collecting and organizing patient information before consultation.

🌐 **Live Demo:** https://medikioski-v4.onrender.com

---

## 📌 Overview

In busy hospital OPDs, doctors have to manage a large number of patients within limited consultation time. A significant portion of this time is spent collecting basic patient history and organizing information.

**MediKiosk** addresses this problem by providing a digital patient intake workflow where patients can enter their information before meeting the doctor.

The collected information can then be used to create a structured patient case summary and support a faster, more organized consultation.

---

## 🎯 Problem Statement

Traditional OPD workflows can involve:

* Long patient queues
* Limited doctor consultation time
* Repeated history-taking
* Unorganized patient information
* Difficulty managing large numbers of patients
* Manual collection of basic medical history

These problems can reduce the amount of time doctors can spend on examination, clinical reasoning and patient counselling.

---

## 💡 Our Solution

MediKiosk provides a **patient-facing digital OPD interface** that helps collect patient information in a structured manner.

### Basic workflow

```text
Patient
   ↓
MediKiosk
   ↓
Patient Information
   ↓
Medical History / Case Details
   ↓
Structured Patient Record
   ↓
OPD Queue
   ↓
Doctor Consultation
```

The goal is to move routine information collection **before the doctor consultation**.

---

## ✨ Key Features

### 👤 Patient Registration

Patients can enter their basic information before consultation.

### 📋 Digital Case Taking

Instead of depending completely on manual history-taking, MediKiosk provides a structured digital workflow for collecting patient information.

### 🏥 OPD Queue Management

Patients can be organized within the OPD workflow, helping staff manage the consultation queue more efficiently.

### 📊 Structured Patient Information

Collected information can be presented in an organized format so that healthcare professionals can review it more easily.

### 🖥️ Patient-Friendly Interface

The interface is designed for simple interaction and can be adapted for touchscreen/kiosk environments.

### 🤖 AI Integration

The MediKiosk architecture is designed to support AI-assisted clinical history processing and structured case summaries.

---

## 🧠 Future AI Capabilities

The project can be extended with AI modules for:

* 🗣️ Voice-based patient history
* 🌐 Multilingual interaction
* 🤖 Adaptive medical questioning
* 📄 Medical document OCR
* 📝 AI-generated clinical summaries
* 🚨 Red-flag symptom detection
* 🩺 Doctor-side case review
* 🔗 ABDM/ABHA integration

These features are intended to make the system more useful in high-volume OPD environments.

---

## 🔄 Proposed Patient Journey

### 1. Identify

The patient enters their basic details and starts the OPD process.

### 2. Case Taking

The patient provides their medical information through the MediKiosk interface.

### 3. Organize

The system structures the collected information.

### 4. Queue

The patient is placed into the appropriate OPD workflow.

### 5. Consultation

The doctor reviews the available information and proceeds with the consultation.

---

## 🏗️ System Architecture

```text
                 ┌──────────────────┐
                 │      Patient     │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │    MediKiosk     │
                 │   Patient UI     │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │  Case Collection │
                 │  & Validation    │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │ Structured Case  │
                 │     Data         │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │   OPD Queue      │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │ Doctor / Clinician│
                 │    Consultation  │
                 └──────────────────┘
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have:

* Node.js
* npm
* Git

### Clone the repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd <YOUR_PROJECT_FOLDER>
```

### Install dependencies

```bash
npm install
```

### Configure environment variables

Create a `.env` file if your project requires environment variables.

For example:

```env
GEMINI_API_KEY=your_api_key_here
```

> **Never commit your API keys or `.env` file to GitHub.**

### Run locally

```bash
npm run dev
```

Open the local development URL shown in your terminal.

---

## 🌐 Live Deployment

The current V4 deployment is available at:

**https://medikioski-v4.onrender.com**

---

## 🛠️ Technology Stack

The project uses a modern web-based architecture and can be extended with:

| Technology        | Purpose                |
| ----------------- | ---------------------- |
| HTML / CSS        | User interface         |
| JavaScript        | Frontend functionality |
| Node.js           | Backend/runtime        |
| AI APIs           | Intelligent processing |
| Google Gemini API | AI capabilities        |
| Render            | Cloud deployment       |
| GitHub            | Version control        |

> Update this table with the exact technologies used in your repository if your implementation differs.

---

## 🔐 Security Considerations

MediKiosk is intended to handle sensitive healthcare information.

Important security practices include:

* Do not expose API keys in frontend code.
* Store secrets using environment variables.
* Avoid committing `.env` files.
* Validate user input.
* Use secure communication.
* Obtain appropriate patient consent before processing health information.
* Minimize unnecessary storage of patient data.

---

## 📈 Impact

MediKiosk aims to:

* ⏱️ Reduce time spent on routine history-taking
* 👨‍⚕️ Allow doctors to focus more on patients
* 🏥 Improve OPD workflow
* 📋 Reduce repetitive manual data collection
* 📊 Organize patient information
* 🚶 Help manage high patient volumes
* 💻 Introduce digital-first patient intake

---

## 🔮 Future Scope

### Phase 1 — Digital Intake

* Structured patient forms
* OPD queue management
* Patient case records

### Phase 2 — AI Assistance

* Gemini-powered case processing
* Adaptive questioning
* Automatic clinical summarization

### Phase 3 — Multimodal Interaction

* Voice input
* Text input
* Touch-based interaction
* Multilingual support

### Phase 4 — Medical Document Intelligence

* Prescription scanning
* OCR
* Lab report extraction
* Medical timeline generation

### Phase 5 — Healthcare Integration

* ABHA integration
* ABDM interoperability
* Hospital information system integration
* Doctor dashboard

---

## 👥 Team

**Project:** MediKiosk

**Domain:** Healthcare Technology / Artificial Intelligence

**Use Case:** OPD Patient Case Taking & Queue Management

---

## ⚠️ Disclaimer

MediKiosk is a software prototype intended to assist with patient information collection and healthcare workflow management.

It is **not a replacement for a qualified medical professional** and should not be used as an autonomous diagnostic system.

---

## 📄 License

This project is currently developed as an academic/prototype project.

Add your preferred license here if the project is intended for public distribution.


