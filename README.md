# RPSIT Multi-Department Academic Portal (DEPT)

An enterprise-grade, responsive single-page academic and departmental management web portal for RPS Institute of Technology. Designed with modern aesthetics following the **60-30-10** color rule, **WCAG 2.1 AAA** contrast compliance, and omnichannel mobile-first responsiveness (320px to 4K displays).

---

## 🌐 Live Application
- **Live URL**: [https://department-rpsit.web.app](https://department-rpsit.web.app)
- **Alternate URL**: [https://department-rpsit.firebaseapp.com](https://department-rpsit.firebaseapp.com)
- **Firebase Project ID**: `department-rpsit`

---

## 🏛️ Supported Engineering Departments
1. **CSE** — Computer Science & Engineering
2. **ECE** — Electronics & Communication Engineering
3. **MECH** — Mechanical Engineering
4. **EEE** — Electrical & Electronics Engineering
5. **B.TECH-IT** — Information Technology
6. **AIDS** — Artificial Intelligence & Data Science
7. **CIVIL** — Civil Engineering
8. **CYBER SECURITY** — Cyber Security & Forensic Tech

Each department features isolated and persistent datasets for:
- 👥 **Student Directories**: Full CRUD, live real-time filtering, JSON export & import.
- 📚 **Curriculum Catalogs**: Semester-based course modules, credit allocations, and syllabi.
- 👨‍🏫 **Faculty Directories**: Distinguished professors, designations, research focus areas, and contact links.
- 📅 **Departmental Events**: Technical symposiums, hackathons, and guest seminars with instant RSVP.
- 📊 **Analytics Dashboard**: Real-time KPI counters, enrollment metrics, and year-wise student distributions.
- 🎓 **Student Profiles**: Individual student credentials, technical specializations, and password management.

---

## 🔐 Role-Based Access Control & Demo Logins
The portal includes a quick one-click demo login system directly in the hero banner for instant evaluation:
- 🛡️ **Administrator**: Full management privileges (Add/Edit/Delete students, courses, faculty, events).
  - *Default credentials*: `admin` / `admin123`
- 👨‍🏫 **Staff / Faculty**: Directory management (Add/Edit students, view all departmental resources).
  - *Default credentials*: `STAFF001` / `staff123`
- 🎓 **Enrolled Student**: Directory exploration, curriculum review, personalized profile and event registration.

---

## 🚀 Running Locally

### Method 1: Python HTTP Server (Zero Dependencies)
```bash
cd /home/purushothaman/Videos/Projects/DEPT/Project_file
python3 -m http.server 3000
```
Open [http://localhost:3000/public/](http://localhost:3000/public/) in your browser.

### Method 2: Node.js Serve
```bash
cd /home/purushothaman/Videos/Projects/DEPT/Project_file
npx serve public
```

---

## 🛠️ Deployment
To deploy updates to Firebase Hosting:
```bash
cd /home/purushothaman/Videos/Projects/DEPT/Project_file
firebase deploy --only hosting
```
