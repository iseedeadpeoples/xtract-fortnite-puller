# Xtract – Fortnite Account Manager / 2fa Bypasser

## 📌 Overview

**Xtract** is a lightweight Fortnite account manager designed to simplify account handling and streamline authentication workflows. It provides a clean interface for managing multiple accounts while implementing alternative authentication handling methods to improve reliability and usability.

> ⚠️ Disclaimer: This tool is intended for educational and personal use only. Misuse may violate Epic Games’ Terms of Service. Use at your own risk.

---

## ✨ Features

* 🔐 Multi-account management
* ⚡ Fast authentication handling
* 🧠 Session caching for quicker logins
* 🖥️ Simple and clean UI
* 📂 Local data storage (no external database required)
* 🔄 Auth workaround system for improved login consistency

---

## 🛠️ Installation

### Requirements

* Windows 10/11
* Python 3.9+ (if running source)
* Internet connection

### Steps

1. Download the latest release or clone the repository:

   ```bash
   git clone https://github.com/yourrepo/xtract.git
   cd xtract
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the program:

   ```bash
   python main.py
   ```

---

## 🚀 Usage

1. Launch Xtract
2. Add your Fortnite account credentials or auth data
3. Select an account from the list
4. Click **Login / Authenticate**
5. The system will handle session generation and storage

---

## 🔄 Authentication Workaround

Xtract uses an alternative authentication handling method that:

* Reduces failed login attempts
* Maintains active sessions longer
* Minimizes repeated credential entry

This is done by:

* Storing session tokens locally
* Refreshing auth when needed
* Avoiding unnecessary re-authentication requests

---

## 📁 File Structure

```
xtract/
│── main.py
│── ui/
│── auth/
│── data/
│── utils/
│── requirements.txt
```

---

## ⚠️ Security Notice

* Your account data is stored locally
* Do NOT share your auth files or tokens
* Use a secondary account if testing

---

## ❗ Known Issues

* Auth sessions may expire after extended inactivity
* UI scaling issues on some resolutions
* Occasional login delay depending on network

---

## 🔧 Future Updates

* Improved UI/UX
* Encrypted storage system
* Account grouping & tagging
* Auto-login system

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the MIT License.

---

## 💬 Support

If you encounter issues, open a GitHub issue or contact the developer.

---

## ⚠️ Final Note

This project is not affiliated with Epic Games or Fortnite.
Use responsibly.
