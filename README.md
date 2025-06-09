# 🧠 Focus Track: Dynamic Task Scheduler

**Focus Track** is a powerful console-based C++ application designed to manage tasks dynamically with advanced scheduling capabilities. It helps users organize their workflow with features like subtasks, dependencies, priorities, recurring tasks, reward points, reminders, and more—making it an ideal productivity booster for individuals and students.

## ✨ Features

- ✅ **Task Creation** with title, description, category, deadline, and priority
- 🧩 **Subtasks** and 🔗 **Dependencies**
- 🔁 **Recurring Tasks** (Daily/Weekly)
- ⏰ **Reminders** for tasks due within 24 hours or 1 hour
- 🎯 **Reward Points** system for gamified productivity
- 📝 **Edit**, ❌ **Delete**, and 🕹️ **Undo** actions
- 🔍 **Search** and 🗂️ **Filter** tasks
- 📊 **Progress Summary** and motivational feedback
- 🤖 **Smart Task Suggestions** (earliest, easiest, quick win)
- 🔐 **Login/Signup** with user-specific saved task data

## 🛠 Technologies Used
- C++ STL: Vectors, Stacks, Queues, Maps
- File I/O for user-based persistent storage
- Windows API for popup reminders
- Console color coding using Windows.h

## 📁 File Structure

- `Dynamic Task Scheduler.cpp` – Main application file  
- `users.txt` – Stores user credentials  
- `tasks_<username>.txt` – Auto-generated files to store tasks per user  

## 🚀 Future Improvements

- GUI-based interface (Qt or Electron)  
- Calendar view for tasks  
- Export to CSV/PDF  
- Email and push notifications  
- Export tasks to CSV or PDF
