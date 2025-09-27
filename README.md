# Python Proxy Server with Real-Time IDS Dashboard

A multi-threaded HTTP/HTTPS proxy server built in Python that includes a signature-based Intrusion Detection System (IDS). All network traffic and security alerts are visualized on a live web dashboard built with Flask and Chart.js.

## ✨ Features

* **HTTP/HTTPS Proxying:** Functions as a standard proxy for web browsing.
* **Multi-Threaded:** Handles multiple client connections simultaneously.
* **Intrusion Detection System (IDS):** Inspects plaintext traffic for common web attack patterns like:
    * SQL Injection (SQLi)
    * Cross-Site Scripting (XSS)
    * Local File Inclusion (LFI)
    * Command Injection
* **Live Web Dashboard:** A real-time interface built with Flask that visualizes:
    * Total threats detected and blocked
    * Live alert feed with details of each threat
    * Attack distribution chart
    * Active proxy connections
* **Domain Blocking:** Blocks access to a custom list of domains (e.g., facebook.com).
* **Request Anonymization:** Basic modification of outgoing HTTP headers to mask the client's identity.

---

## 🔧 Tech Stack

* **Backend:** Python
    * **Sockets:** For low-level networking and proxy functionality.
    * **Threading:** To handle concurrent client connections.
    * **Flask:** To serve the web dashboard and its API.
* **Frontend:**
    * HTML5
    * CSS3
    * JavaScript
* **Charting Library:** [Chart.js](https://www.chartjs.org/) for data visualization.

---
