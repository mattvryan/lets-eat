# Let's Eat 🍳

A custom, shared recipe web app designed just for the two of us to store, view, and import recipes without the clutter of traditional food blogs. Built as a Progressive Web App (PWA) hosted on AWS Lambda, it behaves like a native iPhone app without needing the App Store.

## 🚀 Project Vision & Stack

The goal is a lightweight, blazing-fast mobile experience tailored for our household. 

* **Frontend:** Responsive HTML / CSS / Vanilla JS (Mobile-first, but fully usable on tablets and laptops).
* **Backend:** Node.js running on **AWS Lambda**.
* **Database:** **Amazon DynamoDB** (Schemaless, cost-effective storage for recipe JSON).
* **App Type:** Progressive Web App (PWA) with a `manifest.json` for standalone "Add to Home Screen" usage on iOS.

---

## 🛠️ Core Features

- [ ] **Recipe Scraper:** Give the app a URL, and a Node.js scraper parses out the mess and grabs just the ingredients, steps, and images.
- [ ] **Shared Vault:** A clean, searchable index of all our saved recipes that we can both access and view simultaneously.
- [ ] **PWA Support:** Service worker caching and standalone display settings so it looks and feels like a native iOS app.

---

## 💡 Feature Ideas

Beyond the core functionality, here are the roadmap concepts to implement over time:

### Intelligence & Discovery
* **AI-Agent Helper:** An AI assistant to chat with when we can't figure out what we want to eat.
* **Smart Suggestions:** Automatically suggest highly-rated meals that we haven't cooked in a while.
* **Contextual Filtering:** Quickly select recipes based on situational factors:
  * *"This is what we have in the fridge"*
  * *"I need this to be ready to eat in 30 minutes"*
  * *"Something in the sous vide"*

### Personalization & Utility
* **User Accounts & Auth:** Personalization for both of us (ideally leveraging Face ID / Biometric web auth if possible).
* **Dynamic Scaling:** The ability to automatically scale ingredient amounts up or down for larger or smaller audiences.
* **Custom Edits:** The ability to make custom edits and tweaks to imported recipes (and customize them over time).
* **Meal Ratings:** A rating system with proactive prompts reminding us to rate a meal after we make it.

### Expansion
* **Grocery List:** A shared, automatic grocery list generator based on selected recipes.
* **Meal Planner:** A lightweight calendar interface to map out the week's dinners.

---

## 💻 Local Development & Deployment

*(Placeholders for future setup)*

### Prerequisites
* AWS CLI configured with appropriate credentials.
* Node.js (v20+) installed locally.

### Deployment Steps
1. Clone the repo.
2. Run `npm install`.
3. Deploy to AWS via [SAM / Serverless Framework / CDK].

