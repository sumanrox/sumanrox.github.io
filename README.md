# 🧠 Nmap XML Visualizer — IBM Carbon Dark Edition

> **A professional-grade, single-page Nmap XML visualization tool built with IBM Carbon Design System.**

![Static Badge](https://img.shields.io/badge/status-active-success)
![Static Badge](https://img.shields.io/badge/license-MIT-blue)
![Static Badge](https://img.shields.io/badge/theme-IBM%20Carbon%20Dark-161616)
![Static Badge](https://img.shields.io/badge/built_with-Vanilla%20JS-orange)
![Static Badge](https://img.shields.io/badge/deployment-GitHub%20Pages-lightgrey)

---

## 🪄 Overview

**Nmap XML Visualizer** is a lightweight, standalone web app that converts and visualizes Nmap scan results into a structured, interactive dashboard.  
Designed with IBM’s **Carbon Design System**, it delivers a **sleek enterprise-grade UI** while remaining **completely portable** — no npm, no build steps, and no dependencies.

Ideal for **VDP researchers, penetration testers, and network analysts**, this tool provides quick insights into hosts, open ports, and running services through an elegant interface.

---

## ✨ Features

- 🎨 **IBM Carbon Dark Theme** — elegant, enterprise-inspired interface.  
- 📊 **Interactive Dashboard** — structured summaries for IPs, ports, and services.  
- 🧩 **Accordion-Based Inventory** — explore each IP’s open ports, services, and versions.  
- ⚙️ **Client-Side XML Parsing** — process Nmap scan data directly in your browser.  
- 📂 **Import / Export Support** — load XML, view results, export JSON.  
- 📱 **Responsive Layout** — optimized for desktops and tablets.  
- ⚡ **Zero Setup Required** — just open `index.html` and start using.  

---

## 🧰 Tech Stack

| Layer | Technology |
|--------|-------------|
| **UI Framework** | IBM Carbon Design System (via CDN) |
| **Frontend** | Vanilla JavaScript (no React or build tools) |
| **Styling** | Pure CSS (Carbon colors + custom dark theme) |
| **Data Format** | Nmap XML → JSON |
| **Hosting** | Static (GitHub Pages / Netlify / Any Web Server) |

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/sumanrox/sumanrox.github.io
cd sumanrox.github.io
```

### 2️⃣ Launch Locally with any browser
```bash
open index.html
```

## 🧭 Usage

Follow these simple steps to get started with the Nmap Data Viewer:

1.  **View Sample Data:** Click the "**Load Example**" button to immediately see a demonstration of how your scan results will be displayed.
2.  **Upload Your Data:** Click "**Choose File**" to select and upload your own Nmap XML output file.
3.  **Explore Results:** Navigate the parsed IP addresses using the **accordion view**. Each section expands to show port, service, and protocol details for that host.
4.  **Quick Access:** Use the "**Copy IP**" button for quick clipboard access or "**View Raw**" to see the original XML snippet for that host.
5.  **Save Data:** Click "**Export JSON**" to download the entire parsed inventory as a JSON file.

---

## 🧠 Roadmap

Always looking to improve! Future plans for the tool include if the community asks:

* 🔍 **Search & Filter:** Implement robust filtering by IP address, Port, or Service name.
* ✅ **XML Validation:** Add checks to ensure the uploaded file is valid Nmap XML before parsing.
* 💾 **Local Storage:** Use browser local storage to save previously loaded inventories.
* 🌓 **Theme Toggle:** Introduce a Light/Dark theme switch for better viewing in different environments.
* 📈 **Data Visualization:** Integrate graphs and charts for a visual overview of scan results (e.g., common ports, OS distribution).
