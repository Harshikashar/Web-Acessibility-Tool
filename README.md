# Web-Acessibility-Tool
# A11y AI Inspector 🚀

An intelligent Chrome Extension to detect and suggest fixes for web accessibility issues using AI.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Version](https://img.shields.io/badge/version-1.0.0-informational.svg)

---

## 📖 About The Project

Web accessibility (a11y) is crucial for creating inclusive web experiences, but identifying and fixing issues can be complex and time-consuming. **A11y AI Inspector** is a browser extension designed to help developers, testers, and designers automatically scan web pages for accessibility violations.

Unlike traditional rule-based checkers, this tool leverages AI and machine learning to provide intelligent, context-aware suggestions for fixes, such as generating descriptive alt-text for images.

---

## ✨ Key Features

* **Rule-based Scanning:** Detects common WCAG violations like missing `alt` attributes, incorrect heading structures, and missing `aria-labels`.
* **AI-Powered Suggestions:** Uses a backend ML model to suggest meaningful `alt` text for images and recommend color contrast improvements.
* **Accessibility Score:** Provides a quantifiable score (out of 100) to quickly assess a page's overall accessibility health.
* **One-Click Auto-Fixes (In-DOM):** Apply suggested fixes directly in the browser to preview changes instantly.
* **Highlight Issues on Page:** Visually pinpoints the exact elements on the page that have accessibility issues.
* **Exportable Reports:** Generate detailed accessibility audit reports in PDF or CSV format for documentation and team collaboration.

---

## 🛠️ Tech Stack

* **Frontend / Extension:**
    * HTML5 & CSS3
    * JavaScript (ES6+)
    * WebExtension APIs (Chrome MV3)
    * jsPDF for report generation

* **Backend / AI:**
    * Python
    * Flask / FastAPI
    * TensorFlow / Scikit-learn

---

## ⚙️ Getting Started: Installation & Setup

To get a local copy up and running, follow these simple steps.

### Prerequisites

* Google Chrome or any Chromium-based browser.
* Node.js and npm (optional, for development).

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/your-username/a11y-ai-inspector.git](https://github.com/your-username/a11y-ai-inspector.git)
    ```

2.  **Load the extension in Chrome:**
    * Open Chrome and navigate to `chrome://extensions`.
    * Enable **Developer mode** by toggling the switch in the top-right corner.
    * Click on the **"Load unpacked"** button.
    * Select the directory where you cloned the repository.
    * The **A11y AI Inspector** icon should now appear in your browser's toolbar!

---

## 👨‍💻 How to Use

1.  Navigate to any website you want to test.
2.  Click on the **A11y AI Inspector** icon in your browser toolbar.
3.  Click the **"Scan Page"** button in the popup.
4.  View the detected issues, accessibility score, and AI suggestions directly in the popup UI.
5.  Click on an issue to highlight the problematic element on the page.

---

## 🗺️ Project Roadmap

This project is planned in multiple phases:

* **Phase 1: Basic Working Version (MVP)**
    * Functional extension with a UI, DOM scanner, and basic rule-based checks.
* **Phase 2: AI Suggestions + Backend Integration**
    * Integrate a Python backend to provide AI-generated suggestions for alt-text and color contrast.
* **Phase 3: Smart Fixes, Score, & Reporting**
    * Implement an accessibility score, one-click "auto-fix" functionality, and PDF/CSV report exports.
* **Phase 4: Pro-Level Features (Future Scope)**
    * Add advanced features like voice assistance, issue heatmaps, and LLM integration for smarter suggestions.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

Please see the `CONTRIBUTING.md` file for our code of conduct and the process for submitting pull requests.

---

## 👥 Authors

* **Manya**
* **Harshika**
* **Anshu**

---

## 📜 License

This project is licensed under the MIT License - see the `LICENSE` file for details.
