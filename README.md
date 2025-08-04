# 🧳 Travel Planner AI Agent

Welcome to the **Travel Planner AI Agent**! 🌍✈️  
This project simulates an intelligent assistant that helps users plan their trips efficiently through a structured JSON message format.

#  IBM Hackathon Project 🤖

An **AI-powered assistant** designed to help users plan trips efficiently and intelligently. Built using **🧠 IBM Granite Foundation Model** and hosted on ☁️ **IBM Cloud Lite**, this smart agent suggests destinations, builds personalized itineraries, recommends transport and accommodation, and gives real-time travel alerts using weather and map APIs.

---

## 🧩 Problem Statement

🎯 Design and develop an AI-powered Travel Planner Agent that:
- 📍 Plans trips based on user preferences  
- 🗺️ Suggests destinations and builds itineraries  
- 🚄 Recommends transport and accommodation  
- 🌦️ Uses real-time data (weather, maps, events)  
- 🔔 Manages bookings and alerts  
- 🔄 Optimizes schedules dynamically

### 💡 Proposed Solution

To address this, we built a **Travel Planner AI Agent** using IBM Cloud Lite and Granite. The conversational interface understands user needs through natural language and generates smart, real-time, and personalized travel plans using APIs and LLM-based reasoning.

---

## ⚙️ Technologies Used

- ☁️ IBM Cloud Lite – Hosting & serverless backend  
- 🧠 IBM Granite LLM – Smart response generation  
- 💬 NLP – Understands natural user queries  
- 🔗 IBM App Connect – API integrations (weather, maps, etc.)

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio  
- IBM Granite Model (via Watsonx.ai)  
- IBM Cloud Functions  
- IBM Cloud Object Storage  
- IBM IAM & AI Tools  
- Optional: Watson Assistant (for chatbot interface)

---

## 🌟 WOW Factors

✨ **Real-Time Itinerary Updates** – Based on live weather/travel data  
🧠 **AI Personalization** – Tailored plans using user inputs  
🧭 **Smart Destination & Route Suggestions** – Budget and duration optimized  
🔗 **Integrated APIs** – Maps, weather, bookings, events  
💬 **Conversational UI** – Natural interaction powered by Watson Assistant  
⚙️ **Serverless Efficiency** – Using IBM Cloud Functions

---

## 👥 Target End Users

- 🧍 Solo travelers  
- 👨‍👩‍👧 Families or groups  
- ✈️ Travel bloggers  
- 🏢 Business executives  
- 🎓 Student or academic travelers  
- 🏕️ NGOs planning awareness trips

---

## 🛠️ Setup & Run

1. 🔐 Sign up at [IBM Cloud Lite](https://cloud.ibm.com)
2. 🧠 Launch Watsonx.ai Studio & create a new project
3. 🔗 Integrate APIs (Maps, Weather, Bookings - real or mock)
4. ⚙️ Configure Cloud Functions for backend logic
5. 💬 Build prompts with IBM Granite or Watson Assistant
6. 🌐 Deploy via Streamlit, HTML, or custom UI

---

## 🔍 Sample User Questions

- “Plan a 3-day trip to the beach under ₹10,000”  
- “Suggest a monsoon destination in August”  
- “Help me plan a week-long North India trip”  
- “Show me low-budget hill station options”

---

## 🧪 Tools Used & Testing

🧪 IBM Granite Model – For natural responses  
🔗 IBM App Connect – To call APIs  
🧪 Postman – For API testing  
🌐 Streamlit – UI demo and preview

---

## 🚀 Deployment & Preview

✅ Deployed on IBM Cloud Lite  
✅ Serverless logic using IBM Cloud Functions  
✅ Dynamic AI reasoning via Granite  
✅ Optional chatbot preview with Watson Assistant

---

## 📊 Results

📌 Personalized plans for various inputs  
📌 Adapted to weather & user constraints  
📌 Optimized suggestions for travel, stay, and activities  
📌 Hosted with full scalability using serverless backend

---

## 🔮 Future Scope

📱 Voice Assistant Integration (Alexa, Siri)  
🌐 Multilingual Support with Watson Translator  
🎟️ IRCTC/Goibibo/Booking APIs  
📤 Offline Itinerary PDF Export  
📍 Local travel warnings & seasonal data

---

## 🏅 IBM Certifications

✅ IBM AI Engineering  
✅ IBM Cloud Essentials  
✅ Watsonx Foundation Model Practitioner  
✅ IBM Cloud Functions & App Connect

---
## 🔗 Useful Links

- [🌐 IBM Cloud Lite – Sign Up](https://cloud.ibm.com/registration)  
- [🧠 IBM Watsonx.ai – Granite Foundation Models](https://www.ibm.com/products/watsonx-ai)  
- [🎓 IBM SkillsBuild – Free Courses & Certifications](https://skillsbuild.org/)

## 📜 License

This project is licensed under the **MIT License**.



## 🔤 JSON Format

This project uses a message format compatible with OpenAI's chat APIs:

```json
{
  "messages": [
    {
      "role": "assistant",
      "content": "Hi, I am your Travel Planner AI agent. Where would you like to go today?"
    }
  ]
}
