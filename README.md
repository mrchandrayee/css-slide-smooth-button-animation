# Slide Smooth Button Animation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/css-slide-smooth-button-animation/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

A runnable recreation of the five button hover animations visible in the uploaded 24.93-second screen recording.

## Included effects
1. **Left Fill** — a green fill grows from left to right.
2. **Center Fill** — a blue fill expands outward from the center.
3. **Diagonal** — an orange skewed panel wipes across the button.
4. **Dual Fill** — pink fills grow inward from both sides.
5. **Liquid Fill** — a cyan curved shape rises from below the button.

Each demo includes a CSS snippet panel based on the readable code shown in the recording. Buttons also respond to keyboard focus.

## Run locally
No dependencies or build step required.

```bash
python -m http.server 8000
```

Open http://localhost:8000.

## Files
- `index.html` — five button examples and their code excerpts
- `style.css` — transitions, pseudo-elements, fill animations and responsive styles

## Extraction note
The recording clearly shows the title **Slide smooth button animation** and the five labels: Left Fill, Center Fill, Diagonal, Dual Fill, and Liquid Fill. The visible snippets include `.btn1::before` width transitions, `.btn2::before` centered positioning with `translateX(-50%)`, `.btn3::before` with `skewX(-30deg)`, `.btn4` before/after width expansion to `50%`, and `.btn5::before` moving from `bottom: -100%` to `bottom: 0`. The project reconstructs complete working CSS and HTML around these visible details; it does not claim every source line was legible.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
