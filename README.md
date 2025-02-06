
# Fitness Tracker - Project Breakdown

## Objective
The **Fitness Tracker** is a full-stack web application designed to help users log, track, and monitor their fitness activities. It allows users to record workouts, set goals, track progress over time, and visualize their fitness journey through graphs and reports.

## Project Workflow

1️⃣ **User Authentication & Profile Management**  
   - Users can **Sign Up/Login** with authentication.  
   - Profile includes basic details like **name, age, weight, and fitness goals**.  

2️⃣ **Workout Logging (CRUD Operations)**  
   - Users can **Add, Edit, Delete, and View** their workouts.  
   - Workouts include:  
     - **Exercise type** (Cardio, Strength, Yoga, etc.)  
     - **Duration** and **Calories burned**  
     - **Date of workout**  

3️⃣ **Goal Setting & Progress Tracking**  
   - Users can set **weekly/monthly fitness goals**.  
   - Visual progress indicators to track completed workouts.  

4️⃣ **Dashboard & Analytics**  
   - A **Dashboard page** with charts and stats.  
   - Users can view **progress over time** (calories burned, workout frequency, etc.).  

5️⃣ **Workout History & Search**  
   - Users can **filter workouts** by type, date, or duration.  
   - A **search function** to find specific workouts.  

## Pages & Navigation

📌 **1. Home Page**  
   - Landing page with app overview and login/signup options.

📌 **2. Authentication Pages**  
   - **Login Page**: Users enter credentials to access their fitness data.  
   - **Signup Page**: New users register and create a profile.  

📌 **3. Dashboard Page**  
   - Displays user’s **workout stats**, **goal progress**, and **charts**.  

📌 **4. Workout Log Page**  
   - Users **add/edit/delete** their workout details.  
   - Shows workout history in a table or card format.  

📌 **5. Goal Tracking Page**  
   - Users can set and update their **fitness goals**.  
   - Progress visualization using **graphs/charts**.  

📌 **6. Profile Page**  
   - Users can update **personal details** like weight, age, fitness goal.  

📌 **7. Settings Page (Optional)**  
   - **Dark mode toggle**, **notification preferences**, etc.  

## Tech Stack

### Frontend (React.js)
- **React.js**: Main UI framework  
- **React Router**: Handles navigation  
- **Axios**: API requests  
- **Recharts / Chart.js**: Display workout progress  
- **Tailwind CSS / Bootstrap**: Styling  

### Backend (Node.js & Express.js)
- **Node.js**: Backend runtime  
- **Express.js**: API handling  
- **Mongoose**: MongoDB object modeling  

### Database (MongoDB)
- **MongoDB Atlas**: Stores user workouts & goals  

### Authentication
- **JWT (JSON Web Token)**: Secure login system  


## Thank You