# 🚨📱 DIAL-AID

**DIAL-AID** is an iOS app designed to **prevent fall-related injuries in the elderly**. With real-time fall detection powered by advanced machine learning, DIAL-AID brings critical help when it's needed most—fast, accurate, and reliable.

---

## 🎥 Demo

### 🔐 Login & Register

<p float="left">
  <img src="./assets/dialaid_login.png" width="300" />
  <img src="./assets/dialaid_register.png" width="300" />
</p>

---

### 🧾 Add Emergency Contact Details

<p float="left">
  <img src="./assets/dialaid_emergency.png" width="300" />
</p>

---

### 🚨 Fall Triggered Alert

<p float="left">
  <img src="./assets/dialaid_fall_detected.png" width="300" />
</p>

---

### 🤖 ML Model Accuracy Overview

<p float="left">
  <img src="./assets/dialaid_ml_model.png" width="500" />
</p>

---

## 💡 Inspiration

Elderly falls are a major health concern, often leading to severe injuries and delayed medical response. **DIAL-AID** was created to offer a fast, intelligent solution that detects falls in real-time and alerts caregivers or emergency contacts—**potentially saving lives**.

---

## 🛠️ How It Works

- 🧠 **ML Fall Detection (95% Accuracy):** Built with an ensemble of **CatBoost**, **Random Forest**, and **XGBoost** trained on gyroscope and accelerometer data.
- ⚙️ **Optimized FFT Feature Extraction:** Uses **NumPy** and **Pandas** for real-time signal analysis, minimizing false positives.
- 📲 **Swift + CoreMotion + CoreML:** Leverages iOS's **CoreMotion API** for motion tracking with sub-50ms response time and **CoreML** to integrate ML model response
- ☁️ **Data Storage:** Logs fall data to **Firebase**, hosted on **Google Cloud Platform** (GCP), managing over **10,000+ fall records**.

---

## ⚙️ Tech Stack

- **Frontend:** SwiftUI (Xcode)
- **Motion Tracking:** CoreMotion API & CoreML
- **ML Stack:** CatBoost, Random Forest, XGBoost
- **Signal Processing:** NumPy, Pandas, Jupyter Notebook
- **Storage:** Firebase, hosted on GCP
- **Version Control:** Git

---

## 🏆 Key Highlights

- 🧪 Tested on **50+ simulated falls** with 95% model accuracy.
- ⚡ Real-time analysis and detection under **50ms latency**.
- 🔐 Customizable emergency contact options.
- 🗃️ Logs stored securely for long-term monitoring and pattern analysis.

---

## 🔮 What’s Next

- 📍 **Location Integration:** Add real-time GPS with fall alerts.
- 🧠 **On-Device Model Optimization:** Integrate CoreML for offline detection.
- 👥 **Caregiver Dashboard:** Web portal for remote monitoring.
- 🛡️ **Advanced Privacy:** Encrypt fall logs and user data.

---

## 🙌 Acknowledgments

- Smitha R 

---
