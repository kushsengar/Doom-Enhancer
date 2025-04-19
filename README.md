# Doom-Enhancer
# 🧠 Mood Enhancer App (Broodl)

A full-stack mood tracking and enhancement application built with **Next.js**, **TailwindCSS**, and **Firebase**. It allows users to log moods, get personalized insights, receive motivational quotes based on mood, and track emotional patterns over time.

## 🚀 Tech Stack

- **Frontend:** Next.js 14 (App Router), React
- **Styling:** TailwindCSS
- **Backend & DB:** Firebase Firestore
- **Charts:** Chart.js
- **Authentication:** Firebase Auth

---

## ✨ Features

### ✅ Core Features

- **Mood Logging**  
  Log your daily mood with emojis or keywords (e.g., happy, sad, anxious, unmotivated).

- **Firebase Authentication**  
  Secure login and user-specific mood storage.

- **Mood Dashboard**  
  See a visual overview of your mood entries.

---

### 🆕 Added Features

#### 📈 Mood Pattern Analysis by Time of Day

Understand when your moods tend to be better or worse across the day:

- Aggregates mood scores by hour (0–23).
- Visualizes average mood using a line chart.
- Helps identify times when you're most positive or low.

#### 🧾 Mood Notes

Add context to your mood entries with optional notes, e.g., “Had a bad meeting” or “Great lunch with friends.”

#### 💬 Personalized Quotes Based on Mood

- Suggests motivational or comforting quotes based on your logged mood.
- Quotes are tagged by mood types (e.g., unmotivated, anxious, calm).
- After seeing a quote, you can mark it as “Helpful.”
- The app keeps track of which quotes helped you most.

#### ⭐ Helpful Quote Feedback System

- Quotes have a `helpfulCount` that increases when a user marks them as helpful.
- Enables personalized recommendations based on community and personal history.

---

## 📊 Mood Chart Example

Powered by Chart.js, you get a time-of-day breakdown like:

