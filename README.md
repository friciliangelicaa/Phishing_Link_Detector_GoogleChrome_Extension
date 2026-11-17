# 🔍 Phishing Link Detector
A Google Chrome extension designed to help users detect and avoid phishing links using the XGBoost algorithm and DomainTrustScore. Provides real-time URL detection, user-friendly warnings, and easy-to-follow installation and usage instructions.

---

## 📌 About

**Phishing Link Detector** is a browser extension developed to help users identify potentially harmful phishing links while browsing the internet.

The extension uses the **XGBoost machine learning algorithm** and **DomainTrustScore** to analyze URLs and classify them into two categories: phishing and legitimate.

By automatically analyzing URLs during navigation, the extension helps users become more aware of potentially dangerous websites before accessing them.

## ✨ Features

| Feature                    | Description                                                                      |
| -------------------------- | -------------------------------------------------------------------------------- |
| 🔗 Automatic URL Detection | Automatically analyzes URLs when users navigate to a website.                    |
| 🤖 XGBoost Classification  | Uses a machine learning model with 27 features to classify URLs.                 |
| 🌐 DomainTrustScore        | Incorporates domain reputation scores into the detection process.                |
| ⚠️ Warning Page            | Redirects users to a warning page when a URL is detected as phishing.            |
| 🛡️ User Protection        | Helps users make informed decisions when encountering potentially harmful links. |

## 🚀 Installation Guide

Follow these steps to install the extension manually:

1. Download this repository by clicking **Code → Download ZIP**.

2. Extract the downloaded ZIP file.

3. Open **Google Chrome**.

4. Navigate to the following address:

   ```text
   chrome://extensions
   ```

5. Enable **Developer mode** in the top-right corner.

6. Click **Load unpacked**.

7. Locate and select the extracted **`dist`** folder.

8. The extension is now installed and ready to use!

## 💻 How to Use

1. Open Google Chrome after installing the extension.
2. Browse the internet as usual.
3. When navigating to a website, the extension automatically analyzes its URL.
4. If the URL is classified as phishing, a warning page will appear.
5. Review the warning information before deciding whether to leave the website or proceed.

## ⚙️ Technologies Used

| Technology                  | Purpose                                                           |
| --------------------------- | ----------------------------------------------------------------- |
| JavaScript                  | Core extension implementation.                                    |
| Google Chrome Extension API | Browser navigation monitoring and extension functionality.        |
| XGBoost                     | Machine learning algorithm for URL classification.                |
| DomainTrustScore            | Domain reputation assessment.                                     |
| IndexedDB                   | Local storage for the detection model and domain reputation data. |
| Supabase Storage            | Hosting the machine learning model and domain reputation data.    |

## 📋 Requirements

- Google Chrome browser.
- Active internet connection for downloading the detection model and domain reputation data when they are not available in the local cache.
- Developer mode enabled in Chrome for manual installation.

## ⚠️ Disclaimer

This extension is designed to assist users in identifying potentially harmful phishing URLs. Detection results do not guarantee that a website is completely safe or that every phishing link will be detected.

Users are encouraged to remain cautious when visiting unfamiliar websites.

## 🎓 Project Information

This project was developed as part of an undergraduate thesis research project on phishing link detection using the **XGBoost algorithm** and **DomainTrustScore**.

---

Developed for research and educational purposes.
