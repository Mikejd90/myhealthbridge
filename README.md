# MyHealthBridge

**MyHealthBridge** is a lightweight, privacy-focused web application designed to help patients track daily health metrics at home and seamlessly share structured reports with their GP surgery or healthcare providers.

[**Live Demo »**](https://mikejd90.github.io/myhealthbridge/)

Built using the official NHS.UK Frontend Framework, the app offers a clear, accessible, and intuitive interface that aligns with UK healthcare design standards.

---

## Key Features

* **Multi-Metric Tracking:**
  * **Blood Pressure Diary:** Tracks Systolic and Diastolic pressure (mmHg). Features auto-calculated NICE 7-day averages (automatically excluding Day 1 readings according to clinical standards).
  * **Asthma Peak Flow Diary:** Records daily Peak Expiratory Flow Rate (PEFR in L/min) and tracks personal bests.
  * **Weight Tracker:** Logs body weight in kilograms with real-time automatic conversion to Stones & Pounds.

* **Flexible Export Options for GP Practice Submission:**
  * **Customizable PDF Report Generation:** Downloads a clean, GP-ready PDF summary with patient metadata and chronological history logs. Optionally excludes visual charts for streamlined text-only reports.
  * **Active Mode CSV:** Export single-category readings directly to spreadsheet format.
  * **Combined CSV Export:** Downloads all historical logs across BP, Peak Flow, and Weight into a single unified report.
  * **Copy Plain Text:** One-click copy formatted text directly into online practice consultation portals (e.g., eConsult, Accurx, Patchs).

* **Privacy & Local Storage First:**
  * All data is stored purely inside the patient's browser local storage (`localStorage`).
  * No backend servers, databases, or third-party tracking involved.
  * Patient personal details (Name, DOB, NHS Number) remain entirely on the local device.

---

## Technical Stack

* **Frontend Framework:** NHS.UK Frontend (v9.2.0 CSS)
* **Visualization:** Chart.js (v4.x)
* **PDF Export Engine:** html2pdf.js / jsPDF
* **Storage:** Browser LocalStorage API
* **Deployment:** Zero-build static page (compatible with GitHub Pages, Netlify, Vercel)

---

## Version History

### **v1.3.0**
* **PDF Export Optimization:**
  * Updated PDF generation logic to export text BP readings, summaries, and patient metadata without graph graphics.
  * Temporarily hides canvas chart wrappers during capture to ensure clean, clutter-free printable reports.
* **UI & Quality of Life Improvements:**
  * Enhanced field validation and timestamp resets on form submissions.
  * Improved responsive rendering on mobile viewports for health data tables.

### **v1.2.0**
* Added **Export All Data (Combined CSV)** feature allowing export of all logged health streams in one structured CSV file.
* Streamlined patient details form auto-persisting to local storage.
* Optimized page layout for standalone single-page deployment (`index.html`).

### **v1.1.0**
* Added multi-tracker support:
  * Asthma Peak Flow tracking (PEFR in L/min).
  * Weight tracking (Kilograms with Stones/Pounds conversion).
* Integrated multi-page PDF export via `html2pdf.js`.
* Included dynamic Chart.js graphing for all tracking modes.

### **v1.0.0**
* Initial release focusing on NHS NICE-compliant 7-day Blood Pressure logging.
* Added plain text summary copy tool for eConsult/Accurx submissions.
