# 🌱🌱🌱 The Invisible Carbon Calculator 🌱🌱🌱

_Uncover the carbon footprint you can’t see—at home, on the road, and online._

---

## What is **Invisible Carbon**?

Most carbon calculators ignore your digital life, but **Invisible Carbon** reveals the impact of your everyday habits—including food, travel, household, and especially your digital activities (streaming, scrolling, gaming, and more).

---

## 🚀 **Next-Gen Calculator Covers:**
- 🍔 **Food:** Track your diet’s carbon impact
- 🚗 **Travel:** See emissions from your rides, flights, and commutes
- 💡 **Energy:** Household power, gas, water, and waste
- 📱 **Digital Life:** Streaming, social media, cloud, notifications, and gaming

---

## 🧭 **How It Works**

1. **Input your habits:** Answer a few quick questions about your lifestyle.
2. **Get instant, interactive charts:** See your carbon footprint in real time.
3. **AI-powered personalized tips:** Receive actionable suggestions based on your unique results.

---

## ✨ **Features**

- 📊 Live, adaptive visualizations (pie charts & global comparisons)
- 🤖 AI-powered personalized recommendations (using Google Gemini)
- 🚦 Digital + daily life footprint (the full story)
- 🛡️ Privacy-first (no data leaves your device unless you use Gemini API)

---

## 🌱 **Why Invisible Carbon?**
- 🌫️ Most tools ignore your digital world—**Invisible Carbon** doesn't.
- 🌱 Understand your full footprint and take real action.
- 🌍 Compare yourself to global averages.

---

## ⚡ **Make every click count. Act for the planet!**

---

## 🛠️ **Set-Up & Usage**

### **Requirements**

- Python 3.x
- Jupyter Notebook or Google Colab
- Packages: `numpy`, `matplotlib`, `requests`

### **(Optional) For AI-powered suggestions:**
- Google Gemini API key (set as `PATEL_GEMINI_KEY` in Colab `userdata`)

---

### **Quick Start (in Colab):**

1. **Clone or upload the notebook:**
    - Download `icc.ipynb` from this repo and open in [Google Colab](https://colab.research.google.com/) or Jupyter.

2. **Install requirements (if prompted):**
    ```python
    !pip install matplotlib numpy requests
    ```

3. **(Optional) Add your Gemini API key:**
    ```python
    from google.colab import userdata
    userdata.set('PATEL_GEMINI_KEY', 'YOUR_API_KEY')
    ```

4. **Run all cells and follow the prompts!**

---

## 📦 **How It Works – Overview**

- **Data Sources:** Emission factors are sourced from EPA, EEA, IEA, IPCC, ADEME, Shift Project, and Berkeley Lab.
- **Categories:** Food, Transport, Household, Digital Life.
- **Input:** User answers simple questions about their habits.
- **Calculations:** Annual carbon emissions are computed per category.
- **Visualization:** Interactive charts display your breakdown and compare to global averages.
- **AI Recommendations:** (If enabled) Gemini API analyzes your data and gives custom advice.

---

## 🔒 **Privacy**

- All calculations run locally in your browser or Colab session.
- AI-powered tips use Gemini only if you provide an API key.
- No data is stored or shared without your action.

---



Note:
ms-cc-hackathon-test
This is a repository for testing curriculum for the MS-CC Hackathon 2025. This event is Co-organized by [Black Codes](https://theblackcodes.org/) & [ESIIL](https://esiil.org/) as part of MS-CC's Annual Meeting. Read more about [MS-CC](https://ms-cc.org/) and their events [here](https://ms-cc.org/2025-ms-cc-annual-meeting/).
