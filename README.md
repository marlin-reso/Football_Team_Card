# ⚽ Football Team Card — JavaScript | HTML | CSS

<p align="center">
  <img src="https://media.giphy.com/media/l0HlNQ03J5JxX6lva/giphy.gif" width="620" />
</p>

A dynamic, responsive, and visually appealing **Football Team Card UI** built using **HTML**, **CSS**, and **JavaScript**. This project displays football player details with animations, hover effects, and interactive elements — perfect for portfolios and UI showcases.

---

## ⭐ Features

✔ Player photo, name, jersey number, and position card
✔ Smooth hover animations
✔ Flip-card or sliding reveal animation (based on your design)
✔ Responsive layout (mobile + desktop)
✔ Clean card UI with gradients and shadows
✔ Dynamic data loading using JavaScript
✔ Animated background inspired by football graphics

---

## 🛠 Tech Stack

| Technology     | Purpose                                        |
| -------------- | ---------------------------------------------- |
| **HTML5**      | Structure of player cards                      |
| **CSS3**       | Styling, animations, gradients, responsiveness |
| **JavaScript** | Dynamic card creation & interactivity          |

---

## 📁 Folder Structure

```
Football-Team-Card/
│
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── players/
│   └── icons/
└── README.md
```

---

## 🧩 Example Code Snippet

### 🎴 HTML Structure

```html
<div class="player-card">
  <img src="assets/players/player1.png" class="player-img" />
  <h2 class="player-name">Lionel Messi</h2>
  <p class="player-role">Forward</p>
  <span class="jersey-number">10</span>
</div>
```

### 🎨 CSS Animation Example

```css
.player-card {
  transition: transform 0.3s ease;
  border-radius: 15px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}

.player-card:hover {
  transform: scale(1.06);
}
```

### ⚡ JavaScript Dynamic Loading

```javascript
const player = {
  name: "Cristiano Ronaldo",
  role: "Forward",
  jersey: 7,
  img: "assets/players/ronaldo.png"
};

document.querySelector('.player-name').textContent = player.name;
```

---

## ▶ How to Run

1️⃣ Clone the project:

```
git clone https://github.com/your-username/football-team-card.git
cd football-team-card
```

2️⃣ Open the project in browser:

```
open index.html
```

(or double-click the file)

---

## 🎨 Optional Enhancements

✨ Add card flip animation
✨ Add player stats popup
✨ Add team switcher carousel
✨ Add background football stadium animation
✨ Add audio cheer sound on hover

---

<p align="center">
  <b>Football meets creativity — build stunning player cards! ⚽🔥</b>
</p>
