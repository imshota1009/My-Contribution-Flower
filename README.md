# 🌸 Contribution Flower 🌸  

<div align="center">

Turn your daily GitHub contributions ("grass")  
into the power to grow a beautiful flower 🌱🌼  

</div>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/GitHub_API-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub API">
</p>

---

## 🌼 About

Simply enter your **GitHub username** and **Personal Access Token (PAT)**,  
and watch all of your contributions (including private ones) turn into a growing flower in real time.  

👉 [Check out your flower here](https://imshota1009.github.io/My-Contribution-Flower/)

---

## 📸 Screenshot

![App Screenshot](./images/myflower_screenshot.png)

---

## ✨ Features

- **Accurate Data**  
  Uses the GitHub GraphQL API to fetch both public and private contributions.  

- **Growth Visualization**  
  Your "grass" contributions transform into a flower — from seed → sprout → leaf → full bloom — with smooth animations.  

- **Secure by Design**  
  Your PAT is stored **only in your browser’s `localStorage`** and never sent to any external server.  

---

## 🚀 How to Use

This app requires a **GitHub Personal Access Token (PAT)**.  

### 1. Create a PAT

1. Go to [this page](https://github.com/settings/tokens/new)  
2. **Note**: Use a descriptive name like `Contribution Flower Viewer`  
3. **Expiration**: For security, *90 days* is recommended  
4. **Scopes**: Check only `read:user`  
5. Scroll down and click **Generate token**  
6. Copy the token starting with `ghp_` (it will only be shown once!)  

---

### 2. Grow Your Flower

1. Open the app  
2. Enter your **GitHub username**  
3. Enter your **PAT**  
4. Click **"Grow Flower"**  
5. Your contributions will bloom beautifully on screen 🌸  

---

## ⚠️ Security Notes

- Treat your PAT like a password.  
  **Do not share it or commit it to public repositories.**  
- This app stores your PAT **only in your browser’s localStorage**.  
- Avoid using the app on public or shared computers.  

---

## 🛠️ Technologies Used

- **HTML5** – Structure  
- **Tailwind CSS** – Styling  
- **JavaScript (ES6+)** – App logic  
- **GitHub GraphQL API v4** – Fetching contribution data  
