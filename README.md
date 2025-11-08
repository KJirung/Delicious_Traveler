# 🍴 Delicious Traveler (맛있는 여행자)

> An AI-based mobile application that recognizes Korean foods from images and provides cultural and recipe information for foreign tourists.  
> 외국인 관광객을 위한 음식 인식·정보 제공 앱으로, 사용자가 촬영한 사진에서 한국 음식을 탐지하고 레시피 및 유래 정보를 제공합니다.

---

## 📌 Overview (개요)

- What is “Delicious Traveler”?  
- Project Motivation  
- Flow Chart  
- Tech Stack  
- Demo Video

---

## 🍱 What is “Delicious Traveler”? (맛있는 여행자란?)

- The app detects foods from user-captured images using on-device deep learning models.  
- When a user taps a detected food item, the system classifies it and provides brief information such as **recipes, origin, and cultural background**.  
- 외국인 관광객이 촬영한 음식 이미지를 분석하여 음식명을 인식하고, 해당 음식의 레시피 및 유래 정보를 제공합니다.

---

## 💡 Project Motivation (프로젝트 선정 배경)

- With the global popularity of **K-pop** and **K-drama**, the number of foreign tourists visiting Korea is increasing rapidly.  
- We aimed to create an AI-powered app to help tourists understand and enjoy Korean cuisine more easily.  
- 최근 K-콘텐츠 열풍으로 한국을 방문하는 외국인 관광객이 많아지면서, AI를 활용한 음식 정보 제공 앱을 제작하였습니다.

---

## 🔁 Flow Chart (프로그램 흐름도)

- Image detection: **YOLOv5m**  
- Image classification: **InceptionV3**  
- Both models run **on-device (offline)** within the Android app  
- Information retrieval: **RAG + LLM integration** to provide contextual food details  
- 앱 내 카메라 접근 → 음식 탐지(YOLOv5m) → 분류(InceptionV3) → RAG 기반 LLM을 통해 음식 정보 제공

![FlowChart](https://github.com/KJirung/A_Delicious_Traveler/assets/142071404/ee2c16d1-1203-4f09-891d-7e13ff798b91)

---

## 🧰 Tech Stack (사용 기술)

| Category | Tools / Frameworks |
|-----------|--------------------|
| **Languages** | Kotlin, Python |
| **Frameworks** | PyTorch, TensorFlow, Keras |
| **Dev Tools** | Android Studio, VS Code, Jupyter Notebook |

---

## 🎥 Demo Video (시연 영상)

![시연영상](https://github.com/KJirung/A_Delicious_Traveler/assets/142071404/e9935591-6bce-4cc5-ad6e-0ae44a678ae0)
