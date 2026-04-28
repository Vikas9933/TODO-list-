# Taskly — Python To-Do List App
 
A beautiful, responsive todo list web app built with Python (Flask).
Access it from your laptop, phone, or any device on your network.
 
---
 
## 🚀 Setup & Run
 
### 1. Install Flask
```bash
pip install flask
```
 
### 2. Start the App
```bash
cd todo_app
python app.py
```
 
You'll see:
```
 * Running on http://0.0.0.0:5000
 * Running on http://YOUR_LOCAL_IP:5000
```
 
---
 
## 📱 Access from Any Device
 
| Device     | URL to open in browser        |
|------------|-------------------------------|
| Laptop     | http://localhost:5000          |
| Phone/Tablet | http://YOUR_LAPTOP_IP:5000  |
| Any device on same WiFi | http://YOUR_LAPTOP_IP:5000 |
 
**To find your laptop IP:**
- **Mac**: `ifconfig | grep "inet "` → look for 192.168.x.x
- **Windows**: `ipconfig` → look for IPv4 Address
- **Linux**: `hostname -I`
Example: If your laptop IP is `192.168.1.42`, open `http://192.168.1.42:5000` on your phone.
 
---
 
## ✨ Features
 
- ✅ Add tasks with categories (Work, Personal, Shopping, Health, Finance)
- 🔴🟡🟢 Priority levels (High, Medium, Low)
- 🔍 Search tasks instantly
- 📊 Progress bar showing completion %
- 🗂️ Filter by All / Active / Completed / High Priority
- 🗑️ Clear all completed tasks at once
- 💾 Tasks saved to `todos.json` (persist between restarts)
- 📱 Fully responsive — works great on mobile
---
 
## 📁 File Structure
 
```
todo_app/
├── app.py              ← Flask server (run this)
├── todos.json          ← Your tasks (auto-created)
├── templates/
│   └── index.html      ← The UI
└── README.md
```
