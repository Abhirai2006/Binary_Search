# Binary Search Visualizer (Pro Edition)

A high-performance, modern, and aesthetic web-based visualizer for the Binary Search algorithm. Built for developers and students to understand the "Divide and Conquer" strategy through interactive logic tracking and sensory feedback.

[![Live Demo](https://img.shields.io/badge/demo-live_site-success?style=for-the-badge&logo=netlify)](https://binarysearch-abhirai.netlify.app/)

---

## 🔗 Live Application
Access the tool here:  
👉 **[https://binarysearch-abhirai.netlify.app/](https://binarysearch-abhirai.netlify.app/)**

---

## ✨ Features

- **💎 Glassmorphism Design:** A premium dark-themed UI with frosted-glass effects and neon accents.
- **🕹️ Interactive 3D Parallax:** A mouse-tracking glow and 3D tilt effect on panels for an immersive experience.
- **🔊 Audio Feedback:** Custom synthesized "Cyber" tones using the Web Audio API (Chimes for success, low tones for search steps).
- **💻 Live Code Monitor:** High-performance code snippet window that highlights the current logic path (`if`, `else if`, `else`).
- **📊 Efficiency Analytics:** Real-time $O(\log n)$ tracking and a "Search Space Remaining" gauge that shows data elimination.
- **🎯 Dynamic Pointers:** Fully responsive "LOW", "MID", and "HIGH" tags that adjust dynamically without overlapping.

---

## 🧠 The Logic Behind the Tool

Binary Search is an efficient algorithm for finding an item from a sorted list of items. It works by repeatedly dividing in half the portion of the list that could contain the item, until you've narrowed down the possible locations to just one.



[Image of binary search algorithm flow chart]


This visualizer helps bridge the gap between abstract code and visual intuition:
1.  **Divide:** Picking the `MID` element.
2.  **Conquer:** Comparing the `MID` to the `TARGET`.
3.  **Combine:** Moving the `LOW` or `HIGH` boundaries to eliminate 50% of the remaining data.

---

## 🛠️ Tech Stack

* **Language:** Vanilla JavaScript (ES6+)
* **Styling:** CSS3 (Grid, Flexbox, Glassmorphism, Animations)
* **Audio:** Web Audio API
* **Deployment:** Netlify
* **Version Control:** GitHub

---

## 📖 Usage

1.  **Enter Data:** Provide a sorted comma-separated array (e.g., `10, 20, 30, 40`).
2.  **Input Target:** Enter the number you want to find.
3.  **Prepare:** Click **Prepare** to initialize the system and logic pointers.
4.  **Visualize:** Use the **Next Step** button to walk through the algorithm manually.

---

## 👤 Credits

Developed with ❤️ by **Abhirai2006**.  
*Feel free to star the repo if you found this useful!*

---
