# BRAKE-DISC-DEFECT-DETECTION
Brake Disc Defect Detection using CNN and FastAPI
# 🔧 Brake Disc Defect Detection using Machine Vision

A deep learning-based quality inspection system that automatically detects 
defects in brake discs using a custom CNN model, deployed as a REST API.

## 📌 Project Overview
This system captures brake disc images and classifies them into 7 categories
using a Convolutional Neural Network (CNN), helping automate quality control
in manufacturing industries.

## 🛠️ Tech Stack
- **Model:** Custom 4-layer CNN (TensorFlow/Keras)
- **API:** FastAPI
- **Deployment:** Railway Cloud
- **Camera:** Basler Industrial Camera (PyPylon)
- **Dataset:** ALL METAL DEFECTS Dataset (Roboflow) — 7 classes

## 🔍 Defect Classes Detected
- Undefective (Good)
- Crack
- Scratch
- Pit
- Inclusion
- Rolled-in Scale
- Patches

## 🚀 How It Works
1. Image is captured via Basler industrial camera
2. Sent to FastAPI backend for inference
3. CNN model predicts defect class with confidence score
4. Result displayed on Flask dashboard

## 📡 API Endpoints
| Endpoint | Method | Description |
|---|---|---|
| `/` | GET | API status |
| `/predict` | POST | Upload image for prediction |
| `/health` | GET | Model health check |

## 👩‍💻 Team
- Chithrani
- Natchathira S
- Sanjay K A

**Supervisor:** Mrs. N. Dheerthi

## 🏫 Institution
SREC — Final Year Engineering Project, 2026
