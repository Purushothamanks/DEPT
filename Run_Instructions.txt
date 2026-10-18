# RPSIT Department Portal (DEPT) - Run Instructions

## 🌐 Active Live URL (Firebase Hosting)
- **Primary Live URL**: https://department-rpsit.web.app
- **Alternate Live URL**: https://department-rpsit.firebaseapp.com
- **Firebase Project ID**: `department-rpsit`

---

## Project Overview
**RPSIT Department Portal** is a modern, single-page web portal application supporting multiple engineering departments (CSE, ECE, MECH, EEE). It features role-based access control, dark/light themes, announcement streams, student/faculty directories, event calendars, and resource sharing.

---

## Local Run Instructions

### Method 1: Python Built-in Server (Recommended & No Installation Required)
1. Open your terminal and navigate to the project directory:
   ```bash
   cd /home/purushothaman/Videos/Projects/DEPT/Project_file
   ```
2. Start the local server:
   ```bash
   python3 -m http.server 3000
   ```
3. Open your browser and navigate to:
   ```
   http://localhost:3000/public/
   ```
   *(or `http://localhost:3000/`)*

---

### Method 2: Node.js `serve` / `npx`
1. Navigate to the project directory:
   ```bash
   cd /home/purushothaman/Videos/Projects/DEPT/Project_file
   ```
2. Start using `npx`:
   ```bash
   npx serve public
   ```
3. Open the URL shown in the terminal (typically `http://localhost:3000`).

---

### Method 3: Direct Browser Open
Simply double-click or open `Project_file/public/index.html` (or `Project_file/index.html`) in any modern browser (Chrome, Firefox, Edge, Safari).

---

### Method 4: Firebase Hosting Deployment
1. Install Firebase CLI:
   ```bash
   npm install -g firebase-tools
   ```
2. In the `Project_file` directory, deploy:
   ```bash
   firebase login
   firebase deploy
   ```
