# 📘 LEARN.md

Welcome to **Contribution Flower**! 🌸  
This document is designed to help you **learn** from the project — not just use it.  
Here you’ll find explanations of the core concepts, technologies, and useful resources.

---

## 🌱 What You’ll Learn

- How to use the **GitHub GraphQL API** to fetch contribution data  
- How to store sensitive data safely with **localStorage**  
- How to style web apps efficiently with **Tailwind CSS**  
- How to create simple animations in **JavaScript**  
- How to build a small but complete web application  

---

## 🔗 GitHub GraphQL API Basics

This app uses **GitHub GraphQL API v4** to fetch contributions.

### Key Points:
- Requires a **Personal Access Token (PAT)** with `read:user` scope  
- Query contributions by username  
- More info: [GitHub GraphQL API Docs](https://docs.github.com/en/graphql)

---

## 💾 Local Storage

We store the PAT in the browser using `localStorage`.  

- `localStorage.setItem("key", value)` → Save data  
- `localStorage.getItem("key")` → Retrieve data  
- `localStorage.removeItem("key")` → Delete data  

⚠️ **Important**: Data saved here is only available on your browser, not on a server.

---

## 🎨 Tailwind CSS

Tailwind is used for fast and responsive styling.  

Example:
```html
<button class="bg-blue-500 text-white px-4 py-2 rounded-lg">
  Grow Flower
</button>
