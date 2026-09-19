# MyHealthBridge

### Privacy-Focused Personal Health Tracking Prototype

MyHealthBridge is a lightweight web-based health-tracking prototype designed to explore how personal health information could be recorded, visualised and exported through a simple, accessible digital interface.

The project has been developed as a **portfolio demonstration of UX design, front-end development, data handling and digital health technology concepts**.

> **Portfolio Concept — Not an Official NHS Service**

---

## Project Overview

⚠️ DEMO / PORTFOLIO PROJECT ONLY

MyHealthBridge provides a simple interface for recording and reviewing selected health measurements, including:

* 🩸 Blood Pressure
* 🌬️ Asthma Peak Flow (PEFR)
* ⚖️ Weight
* 📊 Health-data visualisations
* 📄 PDF reports
* 📊 CSV data export
* 📝 Plain-text summaries

The prototype is designed around a privacy-first approach, with demonstration data stored locally within the user's browser rather than transmitted to a live healthcare system.

---

## Key Features

### Blood Pressure

* Record systolic and diastolic readings.
* Record pulse rate.
* Calculate a 7-day blood pressure average.
* Exclude Day 1 from the 7-day calculation where appropriate.
* Review recorded readings and summaries.

### Asthma Peak Flow

* Record Peak Expiratory Flow Rate (PEFR).
* Review historical readings.
* Visualise recorded measurements.

### Weight Tracking

* Record weight in kilograms.
* Convert weight to Stones/Pounds.
* Review historical measurements.

### Data Visualisation

* Chart.js used for graphical representation of supported health data.
* Designed to make changes and trends easier to review.

### Data Export

* Multi-page PDF report generation using `html2pdf.js`.
* Combined CSV export for health-tracking data.
* Plain-text summary export.
* PDF reports include relevant BP readings, summaries and demonstration metadata.
* PDF output is optimised for cleaner printing and sharing.

### Local Data Storage

* Uses browser LocalStorage for demonstration data.
* Patient/demo details can persist between sessions on the same browser.
* No live NHS database or clinical system connection.

### Responsive Design

* Designed for desktop, tablet and mobile screens.
* Responsive health-data tables and forms.
* Optimised as a standalone `index.html` deployment.

---

## Technology

| Technology   | Purpose                                    |
| ------------ | ------------------------------------------ |
| HTML5        | Application structure                      |
| CSS3         | Responsive interface and styling           |
| JavaScript   | Application functionality and calculations |
| Chart.js     | Data visualisation                         |
| html2pdf.js  | PDF report generation                      |
| LocalStorage | Local browser data persistence             |
| CSV          | Data export                                |
| GitHub Pages | Portfolio/demo deployment                  |

---

## Privacy & Data Handling

MyHealthBridge is designed as a **demonstration prototype** rather than a live healthcare service.

The current prototype:

* Uses LocalStorage for demonstration data.
* Does not connect to live NHS systems.
* Does not transmit patient data to a healthcare provider.
* Does not require a live NHS login.
* Does not use real patient information.

Only fictional or demonstration data should be entered.

---

## Health Information & Safety

MyHealthBridge includes example reference indicators to demonstrate how a future application could highlight measurements requiring attention.

These are presented as:

* **Reference flag**
* **Outside example range**

These indicators are **not clinical assessments or diagnoses**.

Health measurements should be interpreted by an appropriately qualified healthcare professional and in the context of the individual's circumstances.

---

## Portfolio Purpose

This project demonstrates practical application of:

* UX and responsive interface design
* Front-end web development
* Digital health concepts
* Local data management
* Data visualisation
* Reporting and document generation
* Accessibility and usability considerations
* Privacy-by-design principles
* Iterative product development

The project also provides an example of how a healthcare technology concept can be explored safely through a standalone prototype without connecting to live clinical systems.

---

## Version History

### v1.3.0 – PDF Export Optimisation

**PDF Export**

* Improved PDF generation for blood pressure readings, summaries and patient/demo metadata.
* Removed graph graphics from PDF output for cleaner reports.
* Improved printable report formatting.

**UI & Quality-of-Life Improvements**

* Enhanced form validation.
* Improved timestamp handling following submissions.
* Improved responsive rendering of health-data tables.

### v1.2.0 – Data Export & Deployment Improvements

* Added combined CSV export for all health-tracking data.
* Improved persistence of patient/demo details using LocalStorage.
* Optimised standalone `index.html` deployment.

### v1.1.0 – Expanded Health Tracking

* Added Asthma Peak Flow tracking.
* Added Weight tracking with Stones/Pounds conversion.
* Added multi-page PDF export using `html2pdf.js`.
* Added Chart.js visualisations for supported tracking modes.

### v1.0.0 – Initial Release

* Initial Blood Pressure tracking release.
* Added 7-day blood pressure calculation functionality.
* Added plain-text summary export to demonstrate potential online consultation workflows.

---

## Future Development

Potential future development could explore:

### Apple Watch

* Potential integration with supported Apple Watch health measurements.
* Watch-based data capture and review.
* Exploration of wearable-to-mobile health-data workflows.

### Apple iPhone

* Further optimisation for iPhone.
* Native-style mobile experience.
* Improved touch interaction and mobile data visualisation.

### iPhone Duo Concept

* Exploration of potential dual-screen/multi-device workflows.
* Extended dashboard and health-data interaction concepts.
* Investigation of how future Apple hardware concepts could support personal health tracking.

### Further Development

* Additional health measurements.
* Improved accessibility testing.
* User research and usability testing.
* More advanced data visualisation.
* Secure cloud synchronisation in a suitable future architecture.
* Potential interoperability concepts, subject to appropriate security, privacy and clinical governance requirements.
---

## Portfolio Purpose

**Demonstration & Portfolio Use Only**

## This project is presented as part of a personal technology and digital-health portfolio.

The prototype, interface and associated materials are intended for **demonstration, educational and portfolio purposes** and should not be deployed as a live healthcare service without appropriate technical, clinical, information-governance, security, accessibility and regulatory assessment.

© 2026 MyHealthBridge — Portfolio Demonstration

Portfolio Purpose
This project demonstrates practical application of:

IT Leadership • Digital Transformation • Operational Resilience • Clinical Systems • Governance • Clinical Safety • Service Improvement

Created as a portfolio prototype demo to demonstrate digital solution design and problem-solving within an NHS General Practice IT context.

## Disclaimer
FICTIONAL PORTFOLIO DEMONSTRATION ONLY

This application is not an NHS service, procurement system or clinical system.

It is not intended for live NHS use, real procurement decisions, clinical use or storage of real patient or confidential organisational information.

The scenarios, organisations, people, suppliers, costs and other information used within the demonstration are fictional.

The application should not be copied, adopted or used as a live procurement or business-case system without appropriate professional, organisational, legal, financial, procurement, information governance and security review.

Copyright © 2026 Mikejd90. All rights reserved. This project is for portfolio demonstration purposes only. No reuse, modification, or distribution is permitted."
