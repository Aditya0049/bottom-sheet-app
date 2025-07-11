# 🚀 Bottom Sheet App – React Frontend Assignment

This project is a fully functional **Bottom Sheet UI component** built in **React** as part of the Flam Frontend Internship Assignment.

The component mimics the behavior of mobile bottom sheets with **multiple snap points** and **manual spring animations** — built **without using libraries like `framer-motion` or `react-spring-bottom-sheet`**, as per the challenge requirement.

---

## 📦 Features Implemented

✅ **Three Snap Points**
- Closed (hidden)
- Half-open (midway)
- Fully open (100%)

✅ **Spring Motion Animations**
- Custom implementation using `requestAnimationFrame` and spring physics (no third-party animation libs)

✅ **User Interaction**
- 🔼 `ArrowUp` key opens to full
- 🔽 `ArrowDown` key closes it
- ⏸️ `Space` opens to half snap
- ✋ Drag and release support with snap-to-nearest point

✅ **Mobile Responsive Design**
- Touch-friendly UI
- Adaptive layout for all screen sizes

✅ **Clean, Modular Codebase**
- `App.js`: Entry point with hook setup
- `BottomSheet.js`: Core component logic
- `springUtils.js`: Reusable spring animation engine
- `styles.css`: Fully responsive and modern styling

✅ **Keyboard Accessibility**
- Fully operable using keyboard keys

✅ **Optional Bonus**:
- Reusable, modular animation logic
- Can be easily converted to a package

---

## 🧠 Tech Stack

- **React** (CRA)
- **JavaScript** (ES6+)
- **CSS3**
- **Vercel** for deployment

---

## 🔧 Setup Instructions

1. **Clone the Repo**

```bash
git clone https://github.com/Aditya0049/bottom-sheet-app.git
cd bottom-sheet-app
