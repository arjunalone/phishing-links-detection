# 🛡️ Phishing Shield — Real-Time Browser Protection Powered by AI

Hi there! 👋  
Welcome to **Phishing Shield** — a smart browser extension that helps you stay safe from phishing attacks while browsing the web.

It’s lightweight, modern, and powered by machine learning to give you instant alerts when a site looks suspicious. Just browse like normal — we’ll take care of the rest.

---

## 💡 What Is It?

Phishing Shield is a **Chrome extension** backed by a **Flask-based ML API** that:
- Automatically scans every site you visit
- Warns you instantly if a site seems like a phishing attempt
- Gives you a confidence score so *you* stay in control

It’s like a mini security analyst watching your back 👀

---

## 🔍 How It Works

Behind the scenes:

1. We use **XGBoost** and **TF-IDF** to understand and classify URLs.
2. If a site looks suspicious, we inject a clean warning screen.
3. You’ll see a **confidence level** and can choose to stay or leave.
4. Everything is handled smoothly in the background — no friction.

---

## ✨ Features You'll Love

✅ Instant scan of every URL you visit  
✅ Clean, mobile-friendly popup UI  
✅ Confidence scores + risk levels (LOW / MEDIUM / HIGH)  
✅ Real-time badge on the extension icon  
✅ Friendly overlay warnings for phishing pages  
✅ Stats like total scans, threats blocked, and safe sites  

---

## 🖼️ A Quick Peek

> (Add screenshots here)

- **Popup UI**: Shows if current site is safe, model status, and scan stats  
- **Phishing Overlay**: Warns users visually and lets them go back

---

## ⚙️ Tech Stack (No Buzzwords, Just Tools)

| Part         | What We Used                       |
|--------------|------------------------------------|
| Extension UI | HTML + CSS + JS                    |
| Backend API  | Flask (Python)                     |
| ML Engine    | XGBoost + Scikit-learn TF-IDF      |
| Storage      | SQLite + chrome.storage.local      |
| Communication| Fetch API (CORS enabled)           |

---

## 🛠️ Getting Started (Super Simple)

### 1. Clone this repo

git clone https://github.com/yourname/phishing-shield.git
cd phishing-shield
