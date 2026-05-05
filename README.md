# 🎡 KineticSlide: Inertial Drag & Motion Orchestration

> **"A high-fidelity draggable slider component exploring input physics, pointer events, and hardware-accelerated CSS motion transitions."**

![Repo Size](https://img.shields.io/github/repo-size/emineugurlu/CARD-SLIDER?color=blue&style=flat-square)
![Language Count](https://img.shields.io/github/languages/count/emineugurlu/CARD-SLIDER?color=blue&style=flat-square)
![UX Type](https://img.shields.io/badge/Interaction-Draggable-orange?style=flat-square)

Static carousels are a thing of the past. This project is a technical exploration of **Interactive Surface Physics**, utilizing JavaScript to bridge the gap between user intent (dragging) and visual output (sliding). By calculating pointer velocity and offset coordinates, I implemented a slider that feels tactile and responsive, mimicking the inertial behavior of native mobile interfaces.

---

## 🚀 Engineering Mindset

This component focuses on **Dynamic Input Handling**:

*   **Pointer Event Orchestration:** Managing `mousedown`, `mousemove`, and `mouseup` (plus touch equivalents) to track displacement vectors in real-time.
*   **Inertial Animation Logic:** Utilizing CSS `transition` timing functions that adjust based on the drag distance to simulate realistic momentum.
*   **Stateful UI Mapping:** Ensuring the slider maintains its "active" state during interaction, preventing accidental clicks while the user is mid-drag.
*   **Performance Optimization:** Using `transform: translateX()` instead of `left` properties to ensure all animations are handled by the GPU, maintaining a stable 60fps experience.

## 🌟 Key Features

*   **Tactile Drag-and-Drop:** Intuitive mouse and touch interaction for navigating content.
*   **Fluid Spatial Transitions:** Smooth, physics-based movement between card states.
*   **Responsive Surface:** A modular architecture that recalculates drag boundaries based on the current viewport width.

## 🔧 Technical Stack

*   **HTML5:** Semantic structure for modular card elements.
*   **CSS3:** Advanced usage of `user-select: none`, `cursor: grabbing`, and hardware-accelerated transforms.
*   **JavaScript (ES6+):** Core logic for coordinate tracking, offset calculation, and event binding.

## 📸 Visual Showcase


![Drag View 1](https://github.com/user-attachments/assets/c5d42a0d-e54b-405b-a9fd-2bc68b139fbf)

![Drag View 2](https://github.com/user-attachments/assets/63c6ae76-4569-4a43-969e-bbcac7968a52)

![Mobile View](https://github.com/user-attachments/assets/145279e5-f321-45f0-8b1e-eeedd8e684a4)

---

## 🛠️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/emineugurlu/CARD-SLIDER.git](https://github.com/emineugurlu/CARD-SLIDER.git)

2. **Open the Project:**
    ````bash
    cd CARD-SLIDER
    open index.html

Developed by Emine Uğurlu with a focus on interaction physics and responsive UI components.
