# 📊 DataSheet Analytics

### Transforming Spreadsheet Data into Interactive Visual Insights

🌐 Live Demo:  https://datasheeet.netlify.app/

---

## 🚀 Overview

DataSheet Analytics is a modern React-based spreadsheet analysis platform that enables users to upload CSV and Excel files, explore data, generate visualizations, and extract meaningful insights directly in the browser.

The application focuses on simplicity and accessibility by performing data processing on the client side, allowing users to analyze datasets without requiring complex setup or dedicated analytics tools.

---

## ✨ Features

### 📂 Spreadsheet Upload

Supports:

* CSV (.csv)
* Excel (.xlsx)
* Excel (.xls)

Users can upload files and instantly preview their contents.

---

### 📄 Sheet Selection

For Excel workbooks containing multiple sheets:

* Detect available sheets
* Select specific worksheets
* Analyze only relevant data

---

### 🔢 Custom Range Selection

Analyze specific portions of uploaded spreadsheets.

Examples:

```text
A1:D100
B2:F200
C5:H500
```

This allows users to focus on the exact data they need.

---

### 🏷 Dynamic Header Row Selection

Different spreadsheets have different structures.

Users can:

* Choose which row contains column headers
* Handle non-standard datasets
* Improve analysis accuracy

---

### 📊 Interactive Visualizations

Generate graphical insights using Chart.js.

Supported charts:

* Bar Charts
* Line Charts
* Pie Charts
* Doughnut Charts
* Area Charts

Features:

* Dynamic chart rendering
* Responsive visualizations
* Real-time chart updates

---

### 📈 Data Exploration Dashboard

Explore uploaded datasets through:

* Data previews
* Column summaries
* Graphical representations
* Interactive filtering

---

### 🔐 Firebase Authentication

Secure user authentication powered by Firebase.

Features include:

* User Registration
* Login
* Authentication Persistence
* Protected Routes

---

## 🎯 Purpose

Many users work with spreadsheets but lack simple tools for quickly visualizing and understanding their data.

DataSheet Analytics bridges this gap by providing a lightweight, browser-based analytics experience that transforms raw spreadsheet data into meaningful visual insights.

---

## 🛠 Technology Stack

### Frontend

* React.js
* JavaScript (ES6+)
* HTML5
* CSS3

### Authentication

* Firebase Authentication

### Data Processing

* XLSX Library
* CSV Parsing

### Visualization

* Chart.js
* React Chart.js 2

### Deployment

* Vercel / Netlify

---

## 📂 Project Structure

```text
DataSheet-Analytics/
│
├── public/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── charts/
│   ├── firebase/
│   ├── utils/
│   └── assets/
│
├── package.json
└── README.md
```

---

## 🌟 Highlights

✅ React-Based Architecture

✅ Firebase Authentication

✅ CSV/XLS/XLSX Support

✅ Dynamic Sheet Selection

✅ Custom Range Processing

✅ Interactive Charts

✅ Client-Side Data Analysis

✅ Responsive Dashboard Design

✅ Fully Deployed Application

---

## 📸 Screenshots

Add screenshots of:

* Dashboard
* Upload Interface
* Data Preview
* Chart Generation
* Analytics View

---

## 🔮 Future Improvements

* AI-Powered Insights
* Dataset Exporting
* Advanced Filtering
* Statistical Analysis
* Custom Dashboard Creation
* Shareable Reports
* Dark Mode Enhancements

---

## ⚙️ Installation

Clone Repository

```bash
git clone https://github.com/yourusername/datasheet-analytics.git
```

Install Dependencies

```bash
npm install
```

Run Development Server

```bash
npm start
```

Build for Production

```bash
npm run build
```

---

## 👨‍💻 Developer

Built to simplify spreadsheet exploration and data visualization through a clean, modern, and interactive user experience.

### 📊 Upload • Analyze • Visualize • Discover
