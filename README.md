# 🌱 PestiSafe

**PestiSafe** is a smart crop-health and agricultural decision-support web application designed to help farmers identify crop problems, understand crop health, choose safer treatment approaches, and make better irrigation and prevention decisions.

The application provides an interactive farmer-friendly dashboard with crop analysis, recovery tracking, environmental intelligence, risk alerts, prevention guidance, and a voice-enabled agricultural assistant.

> ⚠️ **Prototype Notice:** PestiSafe is currently a functional prototype. Crop analysis, weather information, water guidance, and assistant responses use simulated/mock data. The project architecture is designed so real AI and external APIs can be integrated later.

---

## ✨ Features

### 🔍 Crop Analysis

* Upload a crop or leaf image.
* Use the device camera to capture an image.
* Drag and drop JPG/PNG images.
* Enter crop information and symptoms.
* Performs a simulated image-quality assessment.
* Provides a simulated crop-health analysis.
* Displays analysis results and recommended actions.

### 📊 Farmer Dashboard

* Overview of tracked crops.
* Crop health scores.
* Active crop problems.
* Recovery progress.
* Crop health comparison charts.
* Risk alerts.
* Recent analysis information.

### 🌿 Treatment Engine

* Provides treatment recommendations.
* Prioritizes lower-risk approaches.
* Supports biological and cultural control recommendations.
* Designed for future integration with real agricultural/AI recommendation systems.

### 💧 Smart Water Guidance

* Provides irrigation guidance using prototype data.
* Designed to consider crop and environmental conditions.
* Can later be connected to a real weather service and agricultural data.

### 🌦️ Environmental Intelligence

* Weather information.
* Rain and environmental conditions.
* Helps determine whether conditions are suitable for treatment.
* Currently uses simulated weather data.

### 🗺️ Crop Risk Map

* Displays crop/environmental risk information.
* Designed to help identify areas requiring attention.

### 🔄 Recovery Tracking

* Compare crop condition before and after treatment.
* Includes a prototype recovery comparison flow.

### 🤖 Agricultural Assistant

* Conversational agricultural assistant.
* Provides rule-based responses about crop problems, watering, weather, and treatment.
* Includes suggested starter questions.
* Supports browser speech recognition where available.
* Supports text-to-speech using the browser's Web Speech API.
* Can later be connected to a real AI/LLM API.

### 🌱 Prevention

* Provides preventative agricultural guidance.
* Helps users understand practices that can reduce future crop problems.

### 🌐 Language Support

* Includes a language selector.
* Translation/content structure is maintained in the application's translation data.

### ⚙️ Settings

* Application settings and preferences.

---

# 🛠️ Technology Stack

## Frontend

* **React 18**
* **Vite 5**
* **React Router DOM**
* **Tailwind CSS**
* **Recharts**
* **Lucide React**
* **JavaScript / JSX**

## Browser APIs

The application also uses browser capabilities for:

* Speech recognition
* Text-to-speech
* Camera/image capture
* File uploads

---

# 📁 Project Structure

```text
pestisafe/
│
├── public/
│   ├── hero-crop.png
│   ├── tomato-leaf-blight.png
│   ├── tomato-leaf-recovered.png
│   ├── leaf.svg
│   └── ...
│
├── src/
│   ├── components/
│   │
```
