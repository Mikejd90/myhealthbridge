# MyHealthBridge 🩺🌉

MyHealthBridge is a lightweight, privacy-focused web application designed to help patients track daily health metrics at home and seamlessly share structured reports with their GP surgery or healthcare providers.

[Live Demo »](https://mikejd90.github.io/myhealthbridge/)

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
* **Deployment:** Zero-build static page (hosted on GitHub Pages)

---

## Version History

* **v1.3.0**
  * **PDF Export Optimization:**
    * Updated PDF generation logic to export text BP readings, summaries, and patient metadata without graph graphics.
    * Temporarily hides canvas chart wrappers during capture to ensure clean, clutter-free printable reports.
  * **UI & Quality of Life Improvements:**
    * Enhanced field validation and timestamp resets on form submissions.
    * Improved responsive rendering on mobile viewports for health data tables.
* **v1.2.0**
  * Added Export All Data (Combined CSV) feature allowing export of all logged health streams in one structured CSV file.
  * Streamlined patient details form auto-persisting to local storage.
  * Optimized page layout for standalone single-page deployment (`index.html`).
* **v1.1.0**
  * Added multi-tracker support:
    * Asthma Peak Flow tracking (PEFR in L/min).
    * Weight tracking (Kilograms with Stones/Pounds conversion).
  * Integrated multi-page PDF export via `html2pdf.js`.
  * Included dynamic Chart.js graphing for all tracking modes.
* **v1.0.0**
  * Initial release focusing on NHS NICE-compliant 7-day Blood Pressure logging.
  * Added plain text summary copy tool for eConsult/Accurx submissions.

---

## Disclaimer & Safety Notice

> **DEMO / NON-CLINICAL APPLICATION ONLY**
>
> * **Not a Medical Device:** MyHealthBridge is a non-clinical prototype tool built solely for demonstration, portfolio showcase, and personal tracking assistance. It is **not** a certified medical device and does **not** provide medical diagnosis, clinical evaluation, or official treatment advice.
> * **Emergency Situations:** In the event of a medical emergency, do not rely on this application. Contact emergency services immediately — **999** (UK), **911** (US), or **112** (EU).
> * **Consult a Healthcare Professional:** Always seek the advice of a GP, physician, or qualified healthcare provider regarding any health condition or treatment plan. Never disregard or delay seeking professional medical advice because of information logged or calculated within this application.

## Repository Policy & Contributions

This repository exists strictly as a **personal portfolio showcase**. 

* **No External Contributions:** Pull requests, issues, and feature requests from outside contributors are not currently accepted.
* **Ownership:** All maintenance, updates, and code pushes are managed exclusively by the author ([@mikejd90](https://github.com/mikejd90)).
* **Usage:** You are free to view, fork, or study the code under the terms of the MIT License below, but changes to this main repository remain strictly locked to the owner.

---

## License

This project is licensed under the **MIT License** — feel free to inspect or learn from the codebase for personal or educational purposes.

```text
MIT License

Copyright (c) 2026 MyHealthBridge

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
