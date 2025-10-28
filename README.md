# Log Analysis with Malicious Pattern Detection

## Overview
This project is a browser-based log analysis tool designed to detect malicious activity and security incidents in system logs using unsupervised machine learning (ML) and TF-IDF-based feature extraction. It runs completely client-side with no backend, ensuring data privacy and offline capability.

---

<img width="1910" height="886" alt="Screenshot 2025-10-28 183256" src="https://github.com/user-attachments/assets/f862ce91-b2d7-434d-92a0-49c169e67462" />
<img width="1895" height="903" alt="Screenshot 2025-10-28 183431" src="https://github.com/user-attachments/assets/8c1a2db7-7109-4415-8bf7-37dcbda1cce6" />
<img width="1894" height="890" alt="Screenshot 2025-10-28 183605" src="https://github.com/user-attachments/assets/7c74779e-edac-4552-9262-923a069d635f" />
<img width="1919" height="881" alt="Screenshot 2025-10-28 183629" src="https://github.com/user-attachments/assets/7fb67f2e-3a76-4724-af6c-99bcfb185b66" />
<img width="1911" height="885" alt="Screenshot 2025-10-28 183642" src="https://github.com/user-attachments/assets/d971611f-3b52-4f33-a573-676cfeba9f91" />
<img width="1910" height="891" alt="Screenshot 2025-10-28 183653" src="https://github.com/user-attachments/assets/448184cc-6fe0-4aeb-ab20-e01d922a0481" />

---

## Features
- Upload and parse `.log` or `.txt` files directly in the browser.
- Embedded demo datasets for quick testing and evaluation:
  - Normal system log entries
  - Malicious logs with SQL injection, brute force, XSS, and other attacks
- TF-IDF feature extraction using TensorFlow.js (CDN-hosted).
- Unsupervised anomaly detection via KMeans or DBSCAN clustering in-browser.
- Visual, color-coded log viewer with severity and anomaly confidence highlights.
- Dashboard with attack frequency charts, cluster visualization, and top TF-IDF keywords.
- Export analysis results as CSV, PDF, or text files.
- Completely offline-capable, secure, and privacy-first design.



Explore advanced log analysis with this  powerful client-only tool for cybersecurity practitioners, developers, and analysts.
