---
layout: archive
title: ""
permalink: /home-automation/
author_profile: true
---

## 🏡 Vision

My vision for home automation extends far beyond controlling lights and appliances. I aim to **create a home that understands not just your physical presence but your emotional state as well**. A home that can provide **psychological support**, adapt to your moods, and enhance your overall well-being through intelligent automation.

---

## 🎯 Mission

To **fully automate a smart home** that requires **no manual feedback or intervention**—a system that intuitively understands and responds to the resident’s needs, schedules, activities, and habits in real time using AI-powered predictive systems.

---

## 🌟 Benefits of Full Home Automation

- 💡 Energy Efficiency through intelligent control
- 🧠 Context-aware systems that adapt to routines and emotions
- 🏥 Assistive care for elderly or disabled individuals
- 📉 Reduction in manual tasks and mental load
- 🔐 Improved home security with smart monitoring
- 🌐 Seamless integration with IoT and AI systems

---

## 🔄 Project Phases

---

### 📐 Phase 1: Architectural Design

As a first step, I designed a **modular smart home architecture** that simplifies wiring complexity, supports both manual and smart control, and enhances overall system reliability and cost-efficiency.

- The proposed architecture is documented in my **research paper**:  
  📄 [Download Paper – Advanced Smart Home Architectures (PDF)](/files/Advanced_Smart_Home_Architectures__Enhancing_Efficiency__Reliability__and_Integration (7).pdf)

---

### 💻 Phase 2: Software & Automation Logic

In this phase, I’ve been developing **intelligent software agents** that react to sensor data and autonomously control home appliances.

- Designed early control signal initiation logic based on occupancy, time, and ambient environment data.
- Working on state-based scheduling models that adjust behaviors without explicit triggers.
- Focus on fault tolerance and responsive automation without requiring internet/cloud dependency.

> **Still under development and testing in simulated environments.**

---

### 🧠 Phase 3: Integration of AI & Machine Learning

To enable the system to **learn user behavior and adapt**, I’ve integrated AI models into the core logic. Below are two projects that form the backbone of this integration:

---

#### 🤖 Human Activity Recognition using ConvLSTM  
*Tools: Python, ConvLSTM2D, TimeDistributed, UCF101*  
[GitHub Repository](https://github.com/akashrana8755/Human_Activity_Recognition_using_ConvLSTM)

- Built a deep learning pipeline to classify human activities from video sequences.
- Achieved 92% accuracy using ConvLSTM-based architecture.
- Addressed class imbalance with augmentation and efficient network tuning.

---

#### 📍 Next Move Prediction using HMMs and DBNs  
*Tools: Python, HMM, DBN, Particle Filtering*  
[GitHub Repository](https://github.com/akashrana8755/Next_Move_Prediction_using_HMMs_and_Bayesian_Networks)

- Created a hybrid system that predicts the next likely location of a resident using sensor and time-based contextual data.
- Achieved 90% accuracy on CASAS Aruba dataset.
- Incorporated both sequential and contextual information to improve forecasting precision.

---

## 🔬 Ongoing Research

The system is still evolving, and I'm currently experimenting with:

- Real-time reinforcement learning loops for adaptive control
- Privacy-preserving architectures for on-device learning
- Expanding activity types beyond motion (e.g., emotion sensing, sleep patterns)

Stay tuned as the vision of a truly **intelligent, emotionally aware smart home** continues to take shape.