# Fitness Tracker - Project Overview

## Objective
The **Fitness Tracker** is a full-stack web application that enables users to **log, track, and monitor** their fitness activities. It helps users **set fitness goals, track progress over time, and visualize data** through interactive charts.

## Features

### User Authentication & Profile Management
- **Sign Up/Login** using authentication (**JWT**).
- **Profile details**: name, age, weight, and fitness goals.

### Workout Logging (CRUD Operations)
- Users can **Add, Edit, Delete, and View** workouts.
- **Workout details** include:
  - **Exercise type** (Cardio, Strength, Yoga, etc.)
  - **Duration and Calories burned**
  - **Date of workout**

### Goal Setting & Progress Tracking
- Users can **set weekly/monthly fitness goals**.
- **Visual indicators** track completed workouts.

### Dashboard & Analytics
- Displays user’s **workout stats, goal progress, and visual analytics**.
- **Charts** for calories burned, workout frequency, and trends.

### Workout History & Search
- Users can **filter workouts** by **type, date, or duration**.
- **Search function** to find specific workouts.

### Profile & Settings
- **Update personal details** (weight, age, fitness goals).
- **Optional settings**: dark mode toggle, notifications.

## Tech Stack

### Frontend
- **React.js**, **React Router**, **Axios**
- **Recharts/Chart.js**, **Tailwind CSS/Bootstrap**

### Backend
- **Node.js**, **Express.js**, **Mongoose**

### Database
- **MongoDB Atlas**

### Authentication
- **JWT (JSON Web Token)**
