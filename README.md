# ⚙️ DSA Visualizer

> A real-time interactive tool to **visualize Sorting, Searching, and Pathfinding algorithms** with animations, built entirely using **p5.js**.

---

## 📌 Overview

DSA Visualizer is a clean, responsive, and educational visualization tool for algorithms like Bubble Sort, Merge Sort, Insertion Sort, Linear Search, and placeholders for BFS/DFS Grid.  
It is built with pure HTML, CSS (TailwindCSS), and **p5.js**, a JavaScript library that makes creative coding easy and visual.

This project is not just a technical demo  it is a **reflection of deep creative interest in p5.js**, built by a developer who dreams to **contribute to Processing Foundation** and push the power of visual code learning.

---

## 📸 Demo Preview

[Coming soon... *(or you can open the HTML file directly in browser)*](https://p5js-algoscope.netlify.app/)

---

## 🧠 Features

- ✅ Real-time sorting animations (Bubble, Selection, Insertion, Merge)
- ✅ Linear Search highlighting
- ✅ Speed control with slider
- ✅ Responsive UI (Mobile & Desktop)
- ✅ Pause / Resume functionality
- ✅ Theme toggle (light/dark)
- ✅ Interactive Info Panel (Status, Steps, Algorithm)
- ⚙️ Future-Ready: Pathfinding Grid (BFS/DFS) integration planned

---

## 🧰 Technologies Used

| Tech         | Description                           |
|--------------|---------------------------------------|
| `p5.js`      | Visual drawing + animation logic      |
| `TailwindCSS`| Lightweight styling framework         |
| `HTML`/`JS`  | DOM controls + logic                  |

---


---

## 🧩 Algorithm Support

| Algorithm       | Type      | Status     |
|-----------------|-----------|------------|
| Bubble Sort     | Sorting   | ✅ Complete |
| Selection Sort  | Sorting   | ✅ Complete |
| Insertion Sort  | Sorting   | ✅ Complete |
| Merge Sort      | Sorting   | ✅ Complete |
| Linear Search   | Searching | ✅ Complete |
| BFS Grid        | Pathfinding | ⏳ Coming Soon |
| DFS Grid        | Pathfinding | ⏳ Coming Soon |

---

## 🖥️ GUI Walkthrough

- **Dropdown:** Select algorithm (Bubble Sort, Merge Sort, etc.)
- **Input Field:** Enter custom array (like `5, 3, 1, 7`)
- **Speed Slider:** Control animation speed (10–200ms)
- **Start Button:** Begin selected algorithm
- **Reset Button:** Randomize array
- **Pause Button:** Pause/resume animation
- **Theme Toggle:** Switch between light/dark
- **Info Panel:** Displays current algorithm, step status

---

## 🛠️ Functions & Logic

### 🧪 `runSort()`
Main logic to call the selected algorithm and manage UI state.

### 🎲 `generateArray()`
Creates a new randomized array for sorting.

### 🔁 Sorting Functions:
- `bubbleSort()`
- `selectionSort()`
- `insertionSort()`
- `mergeSort()` + `merge()`

Each function uses:
- `await sleep(delayTime)` to simulate animation
- `redraw()` to re-render bars

### 🎯 Searching:
- `linearSearch()` uses simple loop + highlights found value

---

## 💡 Future Plans

- ✅ Add Merge Sort animation logic (Done)
- ⏳ BFS & DFS Grid with mouse-click based pathfinding
- 🔁 Step counters, swap counters
- 📈 Compare algorithms visually
- 💾 Save/load array state
- 🎨 Add sound feedback (swap click)

---

## 🧑‍💻 Author

### 👨‍💻 Yashodip More

- 🏫 B.Tech Electrical Engineering @ RCPIT
- 👨‍🔬 First-generation learner from rural India
- 🎨 Passionate about p5.js and creative code
- 💭 **Dream: To collaborate with the Processing Foundation one day**
- 💚 100% committed to the power of visual learning & algorithmic storytelling

---

## ❤️ Why p5.js?

> “I believe code is art. With p5.js, I don’t just solve problems — I bring ideas to life with animation, interaction, and pure creativity.  
My goal is to make complex computer science concepts feel like visual stories anyone can understand.”

This is not just a tech project — it is a bridge between **logic and creativity**.

---

## 🚀 Get Started

1. Clone the repo or download the `index.html`
2. Open it in your browser
3. Choose your algorithm
4. Click ▶️ Start
5. Watch the magic 💫

---

## 📬 Contact

Feel free to reach out or collaborate:

- Email: yashodipmore2004@gmail.com
- LinkedIn: [linkedin.com/in/yashodip-more](https://www.linkedin.com/in/yashodip-more)
- GitHub: [github.com/YashodipMore](https://github.com/YashodipMore)

---

> Made with ❤️ and p5.js  
> “Logic is the foundation. **Visualization is the revolution.**”

