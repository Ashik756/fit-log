# 🏋️‍♂️ FitLog

A sleek, responsive workout tracking web application built with Next.js. Explore a curated exercise library, inspect step-by-step workout breakdowns, bookmark routines for future sessions, and organize a focused daily workout plan.

## Tech Stack

- **Framework:** Next.js & React
- **Styling:** Tailwind CSS
- **State Management:** Context API
- **UI & Notifications:** React Icons, React Toastify

## Core Highlights

- **Responsive Workout Library:** Seamlessly browse exercises and key metrics across mobile, tablet, and desktop viewports.
- **In-Depth Exercise Breakdowns:** Access essential details including required equipment, difficulty level, sets, reps, estimated calories, and form instructions.
- **Focused Daily Planning:** Build **Today's Plan** with up to 5 targeted exercises per session.
- **Bookmarking & Organization:** Save workouts for later and manage your active and saved routines from the dedicated **My Plan** dashboard.
- **Live Workout Metrics:** Automatically track total exercises, active minutes, and projected calorie burn in real time.
- **Smart Sorting:** Quickly filter and order workouts by duration, calorie output, or user rating.
- **Session Actions:** Mark completed exercises as done with instant feedback or remove items from any list effortlessly.

## Feature Breakdown

### 1. Sort & Discover Workouts
Users can organize the workout library by **Duration**, **Calories**, or **Rating**, making it fast and intuitive to find exercises that match their available time and fitness goals.

### 2. Build Today's Plan
Select and add preferred exercises to **Today's Plan** to structure a custom daily session. The plan caps at **5 workouts** to keep routines focused, automatically updating the exercise counter and live session metrics with every addition.

### 3. Bookmark for Later
Spot an interesting routine for another day? Users can save workouts with a single click. All bookmarked exercises are neatly stored under the **Saved** tab on the **My Plan** page for quick retrieval.

### 4. Complete & Track Progress
Once an exercise in the active plan is finished, users can mark it as **Done**. A confirmation toast notifies the user, and the completed workout is cleared from the active session queue.

### 5. Flexible List Management
Users retain full control over their routines and can remove any exercise from **Today's Plan** or the **Saved** list at any time. All counters and workout statistics recalculate instantaneously upon removal.