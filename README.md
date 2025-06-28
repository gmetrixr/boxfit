# 🧩 BoxFit – Collaborative Packing Game

Welcome to **BoxFit**, a real-time collaborative grid-based game inspired by inventory packing and warehouse logistics.

This assignment is designed to test your skills in **React**, **CSS**, **algorithms**, and **real-time collaboration** using technologies like **Yjs** or **WebSockets**.

---

## 🎯 Objective

Build a multiplayer game where players work together to fit items of different shapes into a shared box grid. The game should be collaborative, visually intuitive, and follow basic placement rules.

---

## 🧱 Core Features

### ✅ Required

- **Shared Grid**  
  A fixed-size 2D grid (e.g., 10×10) representing the box container.

- **Item Placement**  
  Players receive items of various shapes and must drag and drop them into the grid.

- **Drag-and-Drop Interface**  
  Use mouse or touch to place and rotate items on the grid.

- **Collision Detection**  
  Prevent overlaps and enforce grid boundaries.

- **Real-Time Sync**  
  All players should see grid updates live using **Yjs**, **socket.io**, or equivalent.

- **Scoring**  
  Award points for valid fits, and optionally deduct for overlaps or wasted space.

---

## ✨ Bonus Features (Optional)

- Support **rotation** or **flipping** of item shapes.
- Show ghost cursors or presence indicators for other players.
- Timer per round or next-item queue.
- Undo/redo using **CRDT version history**.
- Add a simple **chat box**.
- Persist game history or scores using a database.

---

## 💡 Example Item JSON

```json
{
  "id": "item-1",
  "shape": [[1, 1], [1, 0]],
  "color": "blue"
}
```

## 🧠 Tech Expectations
You are free to choose your stack, but here are recommended technologies:

### Layer	Recommended Stack
* Frontend	React + TypeScript + Vite
* Styling	Tailwind CSS / CSS Modules
* Sync	Yjs (preferred) or socket.io
* Backend (for rooms/scores)
* DevOps	Docker + Docker Compose

## 🚀 Getting Started
🐳 Run via Docker, expose all relevant ports and services
`docker-compose up `

## 🧪 Evaluation Criteria
* React Structure	Hooks, component design, reusability
* CSS/UI	Drag/drop experience, responsive layout
* Logic	Collision detection, placement validation
* Real-Time Sync	Accuracy, latency, collaborative consistency
* Code Quality	Modularity, clarity, TypeScript usage

## 📬 Submission
* Share the GitHub repo with instructions in the README.md
* Optional: Live deployment (e.g., Vercel, Netlify, Render)

## 🙌 Have Fun!
We’re not only assessing correctness, but also creativity, collaboration UX, and how well you can translate real-world logic into a fun interactive game.

Good luck!

## PS, Feel free to use your favourite AI to help you get this going.
