# 📦 o-wails-erp-free - Open Source Offline-First ERP

### 🚀 Business Management Without the Internet.
A lightweight, free, and open-source Enterprise Resource Planning (ERP) application designed for speed, privacy, and reliability in environments with intermittent connectivity.

---

## 🌟 Why o-wails-erp-free?
In many regions, a stable internet connection isn't always guaranteed. Most modern ERPs require expensive cloud subscriptions and constant connectivity. 

This project is built for the "local business owner" who needs their data to be **local, fast, and always accessible.**

* **Offline-First:** All data stays on your machine in a local SQLite database. No cloud, no lag.
* **Privacy-Centric:** Your business secrets are yours. No third-party tracking or data mining.
* **Native Performance:** A lightweight desktop experience powered by Wails (Go) and Angular.
* **Zero Cost:** Free to use, modify, and distribute under the GPLv3 license.

## 🛠️ Tech Stack
* **Frontend:** [Angular](https://angular.io/) (Enterprise-grade UI)
* **Backend/Desktop Wrapper:** [Wails](https://wails.io/) (Go-based native application)
* **Database:** [SQLite](https://www.sqlite.org/) (High-performance local relational database)
<!--
## 📥 Installation

### For Users (Windows)
We provide a simple Installation Wizard for non-developers:
1. Go to the [**Releases**](https://github.com/O-rensa/o-wails-erp-free/releases) page on the right.
2. Download the latest `o-wails-erp-free_Setup.exe`.
3. Run the installer and follow the wizard instructions.
-->
### For Developers
If you want to build from source:
1. **Prerequisites:** Install [Go](https://go.dev/), [Node.js](https://nodejs.org/), and the [Wails CLI](https://wails.io/docs/gettingstarted/installation).
2. **Clone:** `git clone https://github.com/O-rensa/o-wails-erp-free.git`
3. **Install Dependencies:** `cd frontend && npm install`
4. **Run Dev Mode:** `wails dev`
5. **Build Production:** `wails build -nsis` (Generates the Windows Wizard)

## 📈 Roadmap
- [ ] **Core Inventory:** Product tracking and stock alerts.
- [ ] **Sales & Invoicing:** Generate PDF receipts locally.
- [ ] **Expense Management:** Track business overhead.
- [ ] **Data Portability:** Export/Import SQLite data for backups.

## ⚖️ License & Open Source
This project is licensed under the **GNU General Public License v3.0 (GPLv3)**. 
This means:
* You are free to use and modify this software.
* If you distribute a modified version, **it must also be open-source under GPLv3.**
* This ensures the project remains a free resource for the community forever.

## ⚠️ Disclaimer
**Use at your own risk.** This software is provided "as is" without warranty of any kind. As this is an offline-first application, the developer is not responsible for any data loss, hardware failure, or financial discrepancies resulting from the use of this software. Users are strongly encouraged to perform regular manual backups of their local SQLite database.
<!--
## ☕ Support the Developer
Building an ERP as a busy developer takes a lot of late nights! If this tool helps your business save money or stay independent, consider supporting the project:

* **[Insert Donation/PayPal/BuyMeACoffee Link Here]**
* **Star this repository** to help other business owners find it!
-->
---
Developed by O-rensa and Rara Studio.
