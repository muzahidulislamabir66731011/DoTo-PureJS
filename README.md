# 🎯 DoTo
A **zero-dependency** To-Do app that just works.  
Add, tick, delete—data survives reloads via localStorage.  
Perfect for your portfolio, phone home-screen or a quick class demo.

![DoTo screenshot](docs/todo-preview.png)

## ✨ Features
- Pure HTML + CSS + Vanilla JS (no frameworks, no build step)  
- Glass-morphism gradient UI  
- Add task ⏎ | click to mark done ✅ | click × to delete 🗑️  
- Auto-saves to localStorage (list survives refresh)  
- Responsive out of the box (320 px → 4 K)

## ⚡ Quick start
1. Clone or download this repo  
2. Double-click `index.html` … that’s it!  
3. *(Optional)* Drop your own `icon.png`, `unchecked.png`, `checked.png` to re-theme.

## File map
```
DoTo-PureJS/
├── index.html      – semantic markup
├── style.css       – glass-morphism styles
├── script.js       – localStorage logic
├── icon.png        – header icon
├── unchecked.png   – empty circle
├── checked.png     – green check-circle
└── docs/
    └── todo-preview.png  – readme eye-candy
```

## Customise in 30 s
| What | Where |
|------|-------|
| Gradient colours | `style.css` line 9 `background: linear-gradient(...)` |
| Font | replace `"sans-serif"` in `*` block |
| Check icons | swap `checked.png` / `unchecked.png` images |

## Deploy anywhere
Static hosting friendly—drag the folder to Netlify, Vercel, GitHub Pages or even your Android `/sdcard` and open with [Kiwi Browser](https://kiwibrowser.com).

## License
MIT – fork, brand, sell, whatever. Just keep the tiny ⚡ emoji happy.

### LIVE DEMO
[![Live Demo](https://img.shields.io/badge/Live%20Demo-DoTo--PureJS-blue?style=for-the-badge&logo=github)](https://muzahidulislamabir66731011.github.io/DoTo-PureJS/)

