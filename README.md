# Smart-Waste-Management-System

### ✅ `README.md` for Working Web App (QR + GIS System)

````markdown
# Smart Waste Management System Using QR Code and GIS 🗺️♻️

This project implements a smart and scalable waste management system using:
- ✅ **QR Code Scanning**
- 🗺️ **GIS Mapping with Leaflet.js**
- 👥 **Role-Based User System**
- 📊 **Admin Dashboard for Live Monitoring**

## 📌 Problem Statement

Urban areas often face challenges like:
- Missed or delayed waste collection
- Overflowing collection points
- Lack of real-time updates

This system solves the above by integrating technology into the waste monitoring process.

---

## 🔧 Technologies Used

| Layer           | Tools/Frameworks                                |
|----------------|--------------------------------------------------|
| Frontend        | HTML, CSS, JavaScript, Leaflet.js               |
| Backend         | Python (Flask) or Node.js (if used)             |
| Database        | SQLite or Firebase (based on implementation)    |
| QR Code Scanner | JavaScript QR Scanner (`html5-qrcode`)          |
| Mapping         | Leaflet.js + OpenStreetMap                      |
| GIS Layer       | Google Earth Pro → QGIS for shapefiles (SHP)    |

---

## 👥 User Roles & Workflow

### 🧹 First-Level User (Haritha Karma Sena)
- Scans QR code after depositing waste at MCF
- Map updates status from 🟢 (Empty) ➜ 🔴 (Full)

### 🚛 Second-Level User (Waste Collectors)
- Views red-marked (full) MCFs on map
- Scans QR code after collecting
- Map updates status from 🔴 ➜ 🟢

### 🧑‍💼 Admin
- Dashboard view of live MCF statuses
- Interactive GIS map with filters and logs

---

## 📲 Features

- 🎯 Real-time color-coded MCF status on map
- 📸 QR Code scanning using device webcam
- 🗺️ GIS map integration with zoom, pan, and markers
- 📍 Route optimization for workers
- 🔐 Role-based login system (Worker / Collector / Admin)

---

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/<ks-2004>/smart-waste-management.git
cd smart-waste-management
````

### 2. Install dependencies

If using Flask (Python):

```bash
pip install flask
```

If using Node.js:

```bash
npm install
```

### 3. Start the server

```bash
flask run
# or
npm start
```

---

## 🖼️ Screenshots

| Login Page                 | First-Level Interface                 |
| -------------------------- | ------------------------------------- |
| ![Login](https://github.com/ks-2004/Smart-Waste-Management-System/blob/main/login.png) | ![HKS](images/first-level_staff.jpeg) |

| Second-Level Collector                       | Admin Dashboard                 |
| -------------------------------------------- | ------------------------------- |
| ![Collector](images/second-level_staff.jpeg) | ![Admin](images/admin_page.png) |

---

## 🌍 GIS & Mapping Details

* Ward boundaries and MCFs marked using **Google Earth Pro**
* Exported to **QGIS** for converting to SHP format
* Integrated with **Leaflet.js** for map visualization

---

## 📈 Future Enhancements

* Mobile app for field workers
* Real-time GPS tracking of collector vehicles
* Push notifications for full MCFs
* Predictive analytics using AI

---

## 👩‍💻 Contributors

* Aadhil Zabeel M
* Akshay S
* Aniruddhan K A
* Joel Johnson
* Keerthana S
* Lekshmi R
* Sruthy Jayaraj
* Ujwal B Nehin

**Guided by:** Dr. Suja R

---

## 📜 License

This project is intended for academic and research purposes. You are free to use, modify, and adapt with appropriate credits.

---

## 🔗 Links

* 🌐 Live Demo (if hosted): `https://steamspace.in`
* 📝 Project Report (LaTeX): Available in `.pdf`
* 📦 GIS Layers & QR Examples: Available in `/assets/gis/` and `/qr_codes/`

