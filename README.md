<div align="center">

# 🇹🇳 Chachia Go

### *Explore Tunisia. Collect Memories. Earn Rewards.*

**A gamified AI travel companion for tourists discovering the magic of Tunisia**

[![Built with LangGraph](https://img.shields.io/badge/Built%20with-LangGraph-6c63ff?style=flat-square)](https://github.com/langchain-ai/langgraph)
[![RAG Powered](https://img.shields.io/badge/Powered%20by-RAG-ff6b6b?style=flat-square)](#)
[![React](https://img.shields.io/badge/Frontend-React%20%2B%20TypeScript-61dafb?style=flat-square)](https://react.dev)
[![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?style=flat-square)](https://fastapi.tiangolo.com)
[![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-4285f4?style=flat-square)](https://deepmind.google/technologies/gemini/)

</div>

---

## 🎮 Inspired by Pokémon GO — but for Culture & Discovery

Remember the first time you opened Pokémon GO and realized the world around you had transformed into a map full of hidden treasures waiting to be found? **Chachia Go** brings that same electric sense of discovery — but instead of catching Pokémon, you catch tunisian chachia's.

Just like Pokémon GO:
- 📍 **Real-world locations** become interactive destinations to visit and unlock
- 🏆 **XP points** are earned for every activity, quiz, and challenge completed
- 🎖️ **Leaderboards** pit explorers against each other in friendly competition
- 🎒 **Collections** fill up as you discover new places and cultural artifacts
- 🎁 **Rewards** are unlocked as your XP grows

But Chachia Go goes further — it pairs the game loop with a deeply **AI-powered travel assistant** that knows Tunisia inside and out, making every tourist feel like they have a local friend guiding them.

---

## ✨ What Is Chachia Go?

**Chachia Go** is a mobile-first travel companion app for tourists visiting Tunisia. It combines:

- A **personalized AI onboarding** that learns your travel style, interests, and preferences
- A **gamified exploration system** with XP, leaderboards, rewards, and collectable items
- A **full-trip AI chatbot** that answers any travel-related question about Tunisia in real time
- An **interactive map** of Tunisian destinations, activities, and hidden gems
- A **quiz game** to challenge and deepen your knowledge of the places you visit

Whether you are a solo adventurer heading to the Sahara, a couple looking for romantic Mediterranean beaches, or a history enthusiast exploring ancient Punic and Roman sites, Chachia Go crafts a journey tailored just for you.

---

## 🤖 How the AI Works — RAG + LangGraph

Chachia Go is not just a pretty map app. Under the hood, it runs a sophisticated multi-agent AI pipeline built on two powerful technologies:

### 🔍 RAG (Retrieval-Augmented Generation)

The app maintains a curated knowledge base of Tunisian destinations — each enriched with descriptions, vibes, top activities, insider tips, best seasons, and budget information. When a tourist begins their onboarding, the system **retrieves the most relevant destinations** based on their stated preferences (travel style, companions, budget, interests, trip duration) and injects that context directly into the AI's prompt.

This means the AI does not guess — it recommends based on **factual, structured, up-to-date place profiles**, making its suggestions genuinely useful and personalized rather than generic.

### 🔗 LangGraph — Orchestrating the Journey

The entire tourist interaction flows through a **LangGraph state machine** with clearly defined phases:

```
[ CHOUCHENE : Onboarding Agent ]
         ↓
  User picks a destination
         ↓
[ RAG Loader: Context Injection ]
         ↓
[ QUIZ AGENT: Destination Challenge ]
         ↓
[ SUMMARY: Score & Results ]
         ↓
[ CHOUCHENE: Open Q&A Mode — ask anything about Tunisia ]
```

Each node in the graph handles a distinct phase of the tourist experience, and the system seamlessly transitions between them while carrying the full conversation state. This architecture makes the app **robust, extensible, and easy to add new phases or features** without breaking existing flows.

### 💬 The AI Chatbot — Always There, Always Helpful

Once onboarding is complete, a **floating AI chatbot** (powered by the Q&A agent) is available on every screen of the app. Tourists can ask it anything:

- *"What should I eat in Sfax?"*
- *"Is it safe to travel to Tataouine?"*
- *"What's the best way to get from Tunis to Djerba?"*
- *"What does 'Yezzi' mean in Tunisian Arabic?"*
- *"What's the weather like in Hammamet in April?"*

The assistant answers warmly and accurately, staying focused on Tunisia. If a question falls outside its expertise, it politely redirects — it is your **Tunisia specialist**, not a generic search engine.

---

## 🗺️ Core Features

| Feature | Description |
|---|---|
| 🧭 **AI Onboarding** | Personalized chat with Chouchene, who learns your preferences and recommends destinations |
| 🗺️ **Interactive Map** | Explore Tunisian spots, unlock locations, and plan your route |
| 🎒 **Collection** | Gather digital Chachias and cultural badges as you explore |
| 🏆 **Leaderboard** | Compete with other tourists for the top explorer spot |
| 🎁 **Rewards** | Unlock real-world perks as your XP grows |
| 🧠 **Destination Quiz** | Test your knowledge about the places you visit |
| 💬 **AI Chatbot** | Ask any travel question about Tunisia at any moment |
| 🌿 **Sustainability Tags** | Activities are flagged for eco-friendly and sustainable travel |

---

## 🤝 Partner Program — Hotels & Restaurants

Chachia Go is designed with a **partnership ecosystem at its core**. The rewards system is not just a fun game mechanic — it is a **real value exchange** between tourists and local businesses.

### We Are Actively Seeking Partners

We are looking for **hotels, restaurants, riads, tour operators, hammams, artisan shops, and local experiences** across Tunisia to join the Chachia Go partner network.

**How it works:**

1. 🏨 A tourist earns XP by visiting destinations, completing quizzes, and finishing activities
2. 🎁 As their XP reaches reward thresholds, they unlock vouchers and perks
3. 🍽️ Those rewards are **sponsored and fulfilled by our partner businesses** — a free mint tea, a room upgrade, a discount at a local restaurant, a free guided tour
4. 📈 Partners gain **direct exposure** to tourists who are already engaged, motivated, and nearby

This creates a win-win ecosystem: tourists feel genuinely rewarded for their curiosity and exploration, and local businesses attract motivated customers who are pre-engaged with Tunisian culture.

> 📩 **Interested in becoming a Chachia Go partner?** We want to hear from you. Partnership integrations will appear directly inside the app, with your branding visible to every tourist who unlocks a reward in your city.

---

## 🚀 Future Features Roadmap

Chachia Go is just getting started. Here is what we are building next:

### 📸 AI Photo Challenges — Earn XP with Your Camera

One of our most exciting upcoming features is an **AI-powered photo verification system**. Tourists will receive location-specific photo challenges — *"Take a picture of a blue door in the Medina"* or *"Photograph the sunset from this exact viewpoint"* — and our AI will verify the submission using computer vision.

- Verified photos earn **bonus XP and exclusive badges**
- Creates a social layer of shared visual memories
- Encourages deeper engagement with the destination beyond just checking in

### 👥 Tourist Social Rooms — Meet Your Fellow Explorers

Travel is more fun when you share it. We are building **live group chat rooms** for tourists who are visiting the same destination at the same time.

- Rooms are **automatically created per destination** (e.g., a Sidi Bou Said room, a Douz room)
- Tourists can share tips, coordinate meetups, or simply make new friends during their journey
- Optional: themed rooms for solo travelers, families, or adventure seekers
- Moderated to stay safe, friendly, and travel-focused

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React + TypeScript + Tailwind CSS + Framer Motion |
| **Backend** | Python + FastAPI |
| **AI Orchestration** | LangGraph (multi-phase state machine) |
| **AI Model** | Google Gemini |
| **Knowledge Retrieval** | RAG (custom Tunisian destinations knowledge base) |
| **State Management** | React Context + TanStack Query |
| **Routing** | React Router v6 |

---

## 🌍 Our Vision

Tunisia is one of the most culturally rich, historically deep, and naturally diverse countries in the Mediterranean — yet it remains undiscovered by millions of travelers who walk past its wonders without context or connection.

**Chachia Go exists to change that.**

By blending the addictive exploration loop of mobile gaming with the warmth of a knowledgeable local guide, we want every tourist who lands in Tunisia to leave feeling like they truly *lived* it — not just visited it.

> *"From the blue-and-white charm of Sidi Bou Said, to the golden dunes of Douz, to the ancient magic of Carthage — Tunisia is small in size, but huge in experiences."*

---

<div align="center">

Made with ❤️ for Tunisia

**Chachia Go** — *Your journey, reimagined.*

</div>
