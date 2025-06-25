# 🩺 HEALTH TRACKER – Web Application

## 📄 Software Requirements Specification (SRS)

### 1. Introduction

#### 1.1 Purpose
The **Group Health Tracker** web application aims to help users monitor their fitness, nutrition, and overall health in a simple and user-friendly way. It allows tracking of steps, sleep, nutrition, workouts, and water intake to support users in achieving their health goals.

#### 1.2 Scope
- 🟢 User-friendly interface for tracking daily activities (steps, sleep, food intake, workouts).
- 🟢 Personalized goal setting and progress tracking.
- 🟢 Secure user authentication and profile management.
- 🟢 Dashboard with real-time insights on health metrics.
- 🟢 Basic reports and summaries for user performance.

#### 1.3 Intended Users
- 👤 Individuals tracking personal fitness.
- 👥 Small fitness groups monitoring shared progress.

---

### 2. Functional Requirements

- ✅ **User Registration & Login**  
   - Email & password authentication  
   - Google/Apple Sign-In (OAuth)

- ✅ **Profile Management**  
   - Update personal information (name, age, height, weight)  
   - Password reset

- ✅ **Health Tracking Modules**
   - **Steps Tracking**: Daily step count with goal comparison
   - **Sleep Tracking**: Bedtime, wake time, and sleep quality logs
   - **Nutrition Tracking**: Tracks calories, proteins, carbs, and fats
   - **Workout Tracking**: Logs exercises completed per week

- ✅ **Dashboard Overview**  
   - Health score  
   - Daily & weekly summaries of all metrics

- ✅ **Settings & Security**  
   - Two-factor authentication  
   - Secure password management

---

### 3. Non-Functional Requirements

- 💡 Simple & beginner-friendly user interface (UI)
- 🔐 Secure user authentication and data storage
- ⚡ Basic performance optimization for smoother UX

---

### 4. Technology Stack

| Layer     | Technology                     |
|-----------|--------------------------------|
| Frontend  | HTML, CSS, JavaScript (React)  |
| Backend   | Node.js with Express.js        |
| Database  | MongoDB                        |

---

### 5. Application Flowchart

```text
+------------------------+
|        Start           |
+------------------------+
           |
           v
+------------------------+
| User Login / Register |
+------------------------+
           |
           v
+-----------------------------+
| Dashboard with Health Stats|
| (steps, sleep, nutrition)  |
+-----------------------------+
           |
           v
+-----------------------------+
| Health Tracking Features   |
| ├─ Track Steps             |
| ├─ Track Sleep             |
| ├─ Track Nutrition         |
| └─ Track Workouts          |
+-----------------------------+
           |
           v
+-----------------------------+
| View Reports & Progress    |
| (weekly/monthly summaries) |
+-----------------------------+
           |
           v
+-----------------------------+
| Settings & Security        |
| (profile, 2FA, password)   |
+-----------------------------+
           |
           v
+------------------------+
|         End           |
+------------------------+
