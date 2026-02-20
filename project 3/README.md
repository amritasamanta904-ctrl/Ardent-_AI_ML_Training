# 🎓 Student Portfolio — AI & Python Projects

> A modern, animated personal portfolio website for a B.Sc (CSE) student showcasing AI/ML workshop projects, skills, and learning journey.

---

## 🖥️ Live Preview

> **Deploy to GitHub Pages** — push this repo and enable GitHub Pages under **Settings → Pages → Deploy from branch (`main`)**. Your site will be live at:
> `https://your-username.github.io/your-repo-name/`

---

## 📌 About This Project

This is a **single-file HTML portfolio** built to showcase beginner-level AI and Machine Learning projects completed during a hands-on workshop. It is designed to be:

- ✅ Recruiter-friendly and professional
- ✅ Fully responsive (mobile + desktop)
- ✅ Animated with a modern dark glassmorphism design
- ✅ Ready to deploy on GitHub Pages instantly

**Student:** B.Sc (CS) — 2nd Year, 4th Semester  
**Institution:** Haldia Institute of Management  
**Mentor:** SK Sahil (AI Developer & Tutor) — [@Code_ScholarEU](https://www.instagram.com/code_scholar_eu/)

---

## 🚀 Featured Projects

### 1. 📊 EDA Dashboard — Titanic Dataset
> Exploratory Data Analysis using real-world data

- Loaded and explored the Titanic dataset using **Pandas**
- Cleaned missing values using **mean** and **mode** imputation
- Created visualizations: survival count, gender vs survival, age distribution
- Summarized key insights ready for presentation

**Tech Stack:** `Python` `Pandas` `Matplotlib` `Google Colab`

---

### 2. 🏠 House Price Prediction — Linear Regression
> First supervised ML model using scikit-learn

- Performed **train-test split** to evaluate on unseen data
- Trained model using **scikit-learn's LinearRegression**
- Evaluated performance with **RMSE** and **R² score**
- Visualized Actual vs Predicted values and residual errors

**Tech Stack:** `Python` `scikit-learn` `Matplotlib` `Pandas` `Google Colab`

---

## 🛠️ Skills Showcased

| Category | Tools & Concepts |
|---|---|
| **Language** | Python (functions, loops, data structures) |
| **Data Handling** | Pandas, EDA, data cleaning |
| **Visualization** | Matplotlib (bar charts, histograms, scatter plots) |
| **Machine Learning** | scikit-learn, Linear Regression, RMSE, R² |
| **Dev Tools** | Google Colab, GitHub, Git |

---

## 🎓 Workshops & Learning

**Ardent — AI & Machine Learning Workshop** *(3 Days)*
Hands-on live coding in Google Colab covering ML foundations, EDA, and model building.

**Code_ScholarEU — AI Development Learning**
Ongoing mentored learning covering automation workflows, LLM use-cases, and real project building.

---

## ⚙️ How to Personalize

Open `index.html` and update the `LINKS` object at the bottom of the file:

```js
const LINKS = {
  githubProfile: "https://github.com/your-username",     // ← your GitHub
  linkedin:      "https://linkedin.com/in/your-profile", // ← your LinkedIn
  project1Repo:  "https://github.com/your-username/project-1",
  project2Repo:  "https://github.com/your-username/project-2",
  project1Notebook: "https://colab.research.google.com/...", // ← Colab link
  project2Notebook: "https://colab.research.google.com/...",
  email:         "your-email@example.com"
};
```

Also replace **"Student Name"** in the `<h1>` tag with your actual name.

---

## 📂 Project Structure

```
📁 your-portfolio/
├── index.html       # Complete portfolio (HTML + CSS + JS in one file)
└── README.md        # This file
```

> **No build tools required.** No npm, no webpack, no dependencies — just open `index.html` in a browser.

---

## ✨ Features

- 🌌 Animated particle canvas background
- 💎 Glassmorphism card UI with scroll-reveal animations
- ⌨️ Typing effect cycling through project types
- 📱 Fully responsive with mobile hamburger menu
- 📊 Scroll progress bar
- 🎨 Purple/cyan gradient accent theme

---

## 🚢 Deploy to GitHub Pages

```bash
# 1. Initialize git (if not already)
git init

# 2. Add all files
git add .

# 3. Commit
git commit -m "Initial portfolio commit"

# 4. Push to GitHub
git remote add origin https://github.com/your-username/your-repo-name.git
git branch -M main
git push -u origin main
```

Then go to your repo → **Settings → Pages** → set source to **main branch** → Save.

---

## 📬 Contact

- 📧 Email: `student@email.com` *(update in the LINKS object)*
- 💼 LinkedIn: *(update in the LINKS object)*
- 🐙 GitHub: *(update in the LINKS object)*
- 📸 Mentor/Community: [@code_scholar_eu](https://www.instagram.com/code_scholar_eu/)

---

## 📄 License

This project is open for personal and educational use. Feel free to fork and adapt it for your own portfolio.

---

*Built with ❤️ using HTML, CSS & JavaScript — no frameworks needed.*
