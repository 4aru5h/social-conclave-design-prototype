# Social Conclave — Interactive UI/UX Design Prototype

<p align="left">
  <a href="https://4aru5h.github.io/social-conclave-design-prototype/"><img src="https://img.shields.io/badge/Live_Demo-View_Interactive_Prototype-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo" /></a>
  <img src="https://img.shields.io/badge/HTML5-Semantic-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-Custom_Tokens-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/Design-Responsive_Scales-76E9FF?style=for-the-badge&logo=figma&logoColor=black" alt="Design" />
  <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" alt="License" />
</p>

An interactive, responsive single-page conference web prototype designed for the **Social Conclave** event at Mukesh Patel School of Technology Management & Engineering (MPSTME), NMIMS. 

Engineered entirely in pure semantic HTML5, modern CSS3 custom properties (design tokens), fluid typography scales (`clamp()`), and multi-layer SVG vector artwork without external UI framework dependencies.

- **🌐 Live Production Preview:** [4aru5h.github.io/social-conclave-design-prototype](https://4aru5h.github.io/social-conclave-design-prototype/)

---

## Design System & Architecture

### 1. Palette & Design Tokens
The color architecture reflects a deep navy base accented by iridescent and electric blue highlights:

```css
:root {
  --ink:         #020F33;   /* Deepest background shadow */
  --navy:        #031B50;   /* Deep conference navy base */
  --royal:       #0753C7;   /* Primary accent */
  --electric:    #1675FF;   /* High-emphasis buttons & active states */
  --cyan:        #76E9FF;   /* Luminous glow & interactive focus */
  --white:       #F7FAFF;   /* Primary typography */
  --mist:        #BFD3F5;   /* Secondary subtitles */
  --iridescent:  linear-gradient(90deg, #76E9FF, #1675FF 35%, #A58CFF 65%, #F2A2DB);
}
```

### 2. Fluid Typography Scales
All headline and paragraph typography smoothly adapts across mobile, tablet, and desktop viewports using CSS `clamp()` without relying on jarring media query jumps:
- **Hero Display:** `clamp(4.1rem, 0.6rem + 9vw, 9.6rem)`
- **Section Headings (`H2`):** `clamp(2.9rem, 0.5rem + 5.8vw, 6.0rem)`
- **Body & Subtitles:** `clamp(1.06rem, 0.92rem + 0.45vw, 1.2rem)`

### 3. Key Components & Interactions
- **Floating Glass Navigation:** Semi-transparent frosted backdrop with active scroll position awareness and accessible mobile hamburger modal.
- **Procedural SVG Ribbon Curves:** Integrated SVG wave vectors with smooth gradient strokes.
- **Accessible Presentation Script:** Lightweight vanilla JavaScript handling keyboard escape, mobile drawer state, and smooth scroll offsets.

---

## Local Development & Usage

Clone the repository and open `index.html` directly in any modern browser:

```bash
git clone https://github.com/4aru5h/social-conclave-design-prototype.git
cd social-conclave-design-prototype
# Open directly in browser
start index.html
```

---

## License

Distributed under the [MIT License](LICENSE).
