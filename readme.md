# 📰 News App

A responsive **News Application** built using **HTML, CSS, and Vanilla JavaScript** that fetches real-time news using NewsAPI and displays it in a clean card-based UI.

---

## 🚀 Features

- 🔎 Search news by keyword  
- 📌 Category-based filtering (IPL, Finance, Politics)
- 🖼 Dynamic news cards with images  
- 🌍 Real-time news fetching using NewsAPI  
- 📱 Fully responsive layout 

---

## 🛠 Tech Stack

- HTML5  
- CSS3 (Flexbox, Custom Properties)  
- JavaScript (ES6+)  
- Fetch API  
- REST API Integration  

---

## 📂 Project Structure

```
newsApp/
│
├── index.html
├── style.css
├── script.js
└── assets/
    └── logo.png
```

---

## ⚙️ How It Works

1. On page load, default news for **India** is fetched.
2. Clicking a navigation category triggers:

```javascript
fetchNews("categoryName")
```

3. News data is fetched from API
5. Clicking a card opens the full article in a new tab.

---

## 🔑 API Used

This project uses **NewsAPI**.

To run this project:

1. Create an account at https://newsapi.org  
2. Generate your API key  
3. Replace the API key in `script.js`:

```javascript
const API_KEY = "YOUR_API_KEY";
```

---

## 📸 UI Highlights

- Fixed navigation bar  
- Clean card layout  
- Hover animations 

---

## 🧠 Concepts Practiced

- Async/Await  
- Fetch API  
- DOM Manipulation  
- Event Handling  
- Template Cloning  
- Conditional Rendering  
- Responsive Design  

---

## 🏃 How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/newsApp.git
```

2. Navigate into project:

```bash
cd newsApp
```

3. Open `index.html` in your browser.

---

## 🔮 Future Improvements

- Add loading spinner 
- Implement pagination  
- Add dark mode
- Improve error handling UI   

---

## 👨‍💻 Author

Dharmendra Gupta

---

## 📄 License

This project is for learning purposes.
