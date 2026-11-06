# Social Conclave - Conference Prototype

A responsive single-page web prototype designed for the Social Conclave conference at MPSTME, NMIMS.

Built with plain HTML5, CSS custom properties, and fluid typography scales (`clamp()`) without external UI frameworks.

- **Live Demo:** [4aru5h.github.io/social-conclave-design-prototype](https://4aru5h.github.io/social-conclave-design-prototype/)

---

## Design System & Tokens

The color architecture is built around a dark navy foundation with electric and iridescent blue accents:

```css
:root {
  --ink:         #020F33;   /* Background shadow */
  --navy:        #031B50;   /* Conference navy base */
  --royal:       #0753C7;   /* Primary accent */
  --electric:    #1675FF;   /* High-emphasis buttons and active states */
  --cyan:        #76E9FF;   /* Interactive focus glow */
  --white:       #F7FAFF;   /* Primary typography */
  --mist:        #BFD3F5;   /* Secondary typography */
  --iridescent:  linear-gradient(90deg, #76E9FF, #1675FF 35%, #A58CFF 65%, #F2A2DB);
}
```

Typography scales smoothly across viewport widths using CSS `clamp()`:

- **Hero Display:** `clamp(4.1rem, 0.6rem + 9vw, 9.6rem)`
- **Section Headings:** `clamp(2.9rem, 0.5rem + 5.8vw, 6.0rem)`
- **Body Text:** `clamp(1.06rem, 0.92rem + 0.45vw, 1.2rem)`

---

## Viewing Locally

Clone the repository and open `index.html` in any modern web browser:

```bash
git clone https://github.com/4aru5h/social-conclave-design-prototype.git
cd social-conclave-design-prototype
# Open directly in browser
start index.html
```

---

## License

Distributed under the [MIT License](LICENSE).
