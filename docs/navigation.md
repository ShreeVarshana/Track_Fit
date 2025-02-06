# Navigation Structure & Flow of Work

## User Authentication Flow
- User visits the **Home Page (`/`)** and chooses to **login** or **signup**.
- If logging in, they are redirected to the **Dashboard (`/dashboard`)**.
- If signing up, they complete registration and are then redirected to the **Profile Page (`/profile`)** to set fitness details.

## Dashboard Flow
- After authentication, the user lands on the **Dashboard (`/dashboard`)**.
- Dashboard displays **key stats, progress tracking,** and **links to workouts and goals**.

## Workout Management Flow
- Users navigate to **Workout Log (`/workouts`)**.
- They can **add a new workout, edit an existing one, or delete a workout**.
- Workouts are listed in a **table or card format** with **filtering options**.

## Goal Setting & Tracking Flow
- Users visit the **Goal Tracking Page (`/goals`)**.
- They can **set new fitness goals** (e.g., run **10km/week**, burn **500 calories/day**).
- Goals are tracked via **visual progress indicators**.

## Profile & Personalization Flow
- Users navigate to the **Profile Page (`/profile`)**.
- They can **update personal details** like **weight, age, and fitness goals**.

## Settings Flow 
- Users visit **Settings (`/settings`)**.
- Options include **toggling dark mode** and **setting notification preferences**.

## Search & History Flow
- Users access their **workout history** via **Workout Log (`/workouts`)**.
- They can **search workouts** by **type, date, or duration**.

## Navigation Summary
1. **Home (`/`)** → **Login/Signup**
2. **Login (`/login`)** → **Redirect to Dashboard**
3. **Signup (`/signup`)** → **Redirect to Profile Setup**
4. **Dashboard (`/dashboard`)** → **Overview & Quick Actions**
5. **Workouts (`/workouts`)** → **CRUD Operations**
6. **Goals (`/goals`)** → **Goal Setting & Progress**
7. **Profile (`/profile`)** → **Update Personal Details**
8. **Settings (`/settings`)** → **Preferences & Theme**
