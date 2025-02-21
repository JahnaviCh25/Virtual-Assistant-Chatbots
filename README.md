# **Virtual Assistant Avatars – README**  

This repository contains **interactive virtual assistant avatars** built using **HTML, JavaScript, and APIs** to provide a seamless conversational experience. The assistants are powered by different AI models, including **ChatGPT, Claude AI, and Hugging Face’s DialoGPT**, enabling **speech recognition, AI-generated responses, and text-to-speech functionalities**.  

## **Project Overview**  

The repository includes the following assistant implementations:  

1️⃣ **AvatarChatGPT.html** – A virtual assistant powered by OpenAI's **ChatGPT API**.  
2️⃣ **ClaudeAvatar.html** – An interactive assistant utilizing **Anthropic’s Claude API**.  
3️⃣ **HuggingFaceAvatar.html** & **HuggingFaceAvatar Copy.html** – AI chatbot using **Hugging Face’s DialoGPT**.  

Each assistant allows **speech-based** interactions, with **voice recognition, AI-generated responses, and text-to-speech (TTS) capabilities**.  

---

## **Features & Functionalities**  

✔ **Speech Recognition** – Uses Web Speech API for voice input processing.  
✔ **AI-Powered Responses** – Fetches responses from different AI models (ChatGPT, Claude, or Hugging Face).  
✔ **Text-to-Speech (TTS)** – Converts AI-generated responses into speech.  
✔ **Interactive Avatar Animation** – Simulates engagement when speaking.  
✔ **Real-time User Input Processing** – Users can talk to the assistant naturally.  

---

## **Assistant Breakdown**  

### **1️⃣ AvatarChatGPT.html (ChatGPT-Powered Assistant)**  
🔹 **Uses OpenAI’s GPT-3.5 API** to process voice queries.  
🔹 Fetches responses from **OpenAI’s ChatGPT API** using a POST request.  
🔹 Implements **Text-to-Speech (TTS)** to vocalize AI-generated answers.  
🔹 Avatar **animates while speaking**, creating a more interactive experience.  

🔧 **Tech Stack:**  
- OpenAI API  
- Web Speech API  
- JavaScript (fetch requests, event listeners)  
- HTML & CSS (for UI styling)  

---

### **2️⃣ ClaudeAvatar.html (Claude AI Assistant)**  
🔹 **Uses Claude API via a proxy server** to generate responses.  
🔹 Includes a **video-based avatar** that plays animations when active.  
🔹 Speech recognition enables **voice commands**.  
🔹 **Conversation history tracking** for improved contextual responses.  

🔧 **Tech Stack:**  
- Claude AI API  
- Web Speech API  
- JavaScript (API requests, async functions)  
- HTML5 Video (for animated avatar)  

---

### **3️⃣ HuggingFaceAvatar.html & HuggingFaceAvatar Copy.html (Hugging Face Assistant)**  
🔹 **Uses Hugging Face’s DialoGPT API** for chatbot-style interactions.  
🔹 Implements **real-time speech-to-text conversion**.  
🔹 Supports **multi-turn conversations** by maintaining a short chat history.  
🔹 **Text-to-Speech (TTS)** provides **audible** AI responses.  
🔹 Includes **loading animations** and **chat UI formatting**.  

🔧 **Tech Stack:**  
- Hugging Face API (DialoGPT)  
- Web Speech API  
- JavaScript (async functions, event listeners)  
- HTML & CSS (chat UI, buttons, styling)  

---

## **How to Use the Assistants**  

### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/your-repo-name.git
cd your-repo-name
```

### **2️⃣ Open the HTML Files**  
You can open any `.html` file in a web browser to start using the assistant.  

### **3️⃣ Enable Speech Recognition**  
Click the **"Start Talking"** button and speak to the assistant.  

### **4️⃣ Receive AI Responses**  
- The assistant **recognizes speech** and processes it using the AI model.  
- It then **generates a response** and **speaks it aloud**.  
- Avatar animations or **chat messages** enhance user experience.  

---

## **Customization & Configuration**  

🔹 **API Keys** – Replace placeholders with your actual API keys (OpenAI, Claude, Hugging Face).  
🔹 **Text-to-Speech (TTS)** – Modify speech synthesis settings (pitch, speed).  
🔹 **Avatar Customization** – Update image/video sources for a personalized assistant.  
🔹 **Backend Integration** – Connect with **Flask, Node.js, or other frameworks** for enhanced functionalities.  

---

## **Future Enhancements**  

🚀 **Multi-Language Support** – Expand speech recognition to different languages.  
🎤 **Real-Time Voice Training** – Improve response personalization based on user patterns.  
📊 **Analytics Dashboard** – Track and visualize user interaction data.  
💡 **Integration with IoT** – Connect virtual assistants with smart home devices.  

---

## **Conclusion**  

This project provides an **interactive AI-powered virtual assistant** experience, integrating **speech recognition, AI responses, and text-to-speech** to create **engaging chatbot avatars**. Whether using **ChatGPT, Claude, or Hugging Face’s DialoGPT**, users can **converse naturally** and receive **intelligent AI-driven responses**.  

📌 **Try it out and customize your AI assistant today!** 🚀  

---
