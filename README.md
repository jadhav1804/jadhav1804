# create a local folder and add the README
mkdir jadhav1804-profile
cd jadhav1804-profile

# create README.md (use your editor or the echo below to start)
cat > README.md <<'EOF'
# 👋 Hi, I'm Riddhi Jadhav

💡 AI & Web Developer | 🚀 Building smart apps with Python, Streamlit & ML | 🌱 Lifelong Learner

---

## 🔧 Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-009688?style=for-the-badge&logo=tensorflow&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## 📊 GitHub Stats
![GitHub stats](https://github-readme-stats.vercel.app/api?username=jadhav1804&show_icons=true&theme=radical)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jadhav1804&layout=compact&theme=radical)  

---

## 🌱 Currently
- 🛠️ Working on **AI-based web apps**
- 📖 Exploring **Machine Learning & Cloud**

---

## 📫 Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/riddhi-jadhav-7b6259378?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jadhavriddhi104@gmail.com)  

---

![Profile Views](https://komarev.com/ghpvc/?username=jadhav1804&label=Profile%20Views&color=blue&style=for-the-badge)
![Followers](https://img.shields.io/github/followers/jadhav1804?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/jadhav1804?style=for-the-badge)

---

⚡ *“Code. Learn. Innovate. Repeat.”*
EOF

# initialize git and push
git init
git add README.md
git commit -m "Add profile README"
git branch -M main
git remote add origin https://github.com/jadhav1804/jadhav1804.git
git push -u origin main
