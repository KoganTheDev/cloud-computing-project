# 🤖 **RoboDash - Real-Time Engineering Dashboard**

---

## 📝 **Overview**  
**RoboDash** is a real-time cloud dashboard built for monitoring sensor networks and managing engineering team productivity. It provides live insights into environmental data (indoor/outdoor), performance scores, and task completion status—all powered by **Firebase**, **Python**, and **Google Colab**.

It serves as a data-driven operational panel for engineering teams needing quick, interactive overviews of sensor activity, performance analytics, and daily assignments.

---

## 🎯 **Features**  

### 📡 **Sensor Monitoring**
- **Real-Time Sync** with Firebase for both indoor and outdoor sensor data.
- **Historical Visualization** of sensor values over time using `matplotlib`.
- **Dynamic Plotting** with automatic date parsing.

### 👷 **Engineer Performance**
- Tracks each engineer’s **points** and **completed improvements**.
- Displays engineer ranking and contributions.
- Supports gamification for increased motivation.

### 📝 **Task Management**
- Daily tasks with fields:  
  - Description  
  - Points  
  - Assigned Engineer  
  - Status (Pending / Completed)  
- Allows marking tasks as completed and tracks the date and engineer.

### 🧠 **Smart Backend**
- Uses custom data structures (`SensorData`, `EngineersPerformance`, etc.) for clean logic separation.
- Firebase database paths structured for easy access to sensor and user-related data.

### 🎨 **Styled UI Components**
- Built with `ipywidgets` for interactive elements (buttons, dropdowns, etc.).
- Consistent and visually appealing UI design using predefined constants (colors, shadows, padding).

---

## 🛠 **Architecture**
- **Frontend:** Interactive notebook-based UI (Google Colab).
- **Backend:** Firebase database with real-time read/write.
- **Data Layer:** Python dictionaries and type-safe structures.
- **Visualization:** `matplotlib` and `ipywidgets`.

---

## 💻 **Development Environment**
- Built using Google Colab notebooks.
- Dependencies:  
  `numpy`, `pandas`, `ipywidgets`, `matplotlib`, `firebase`, `nltk`, `datetime`, `zoneinfo`

---

## 🧪 **Demo Preview**  
![image](https://github.com/user-attachments/assets/67b4913d-5960-481e-8659-72be891237c7)
![image](https://github.com/user-attachments/assets/9b1b8956-4f07-4974-ade5-a557e35426ff)
![image](https://github.com/user-attachments/assets/94ec66e4-5367-419c-803e-bcb936810b73)

---

## 👥 **Authors**  
This project is developed by:

* **Yuval Kogan**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/yuval-kogan) [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/KoganTheDev)  

* **Daniel Lachmakov**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/daniel-lachmakov-94761b288/) [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/Danielon05423)  

* **Almog Raz**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/almog-raz/) [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/almograz1)  

* **Ron Salama**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/ron-salama-3860a0107/) [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/RS-OG)  

* **Lior Dagash**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/lior-dagash-53130333a/) [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/iMianite)  

* **Yaniv Bodaga**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/yaniv-bodaga/) [![GitHub](https://img.shields.io/badge/GitHub-Profile-black?style=flat-square&logo=github)](https://github.com/yaniv99)  
