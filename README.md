# nteasocial_satellite

welcome. a small repository for anything i know about or suggest. [more about me](https://www.nteasocial.com)

---

# Table of Contents
1. [Maths & Physics Glossary](#maths--physics-glossary)
2. [Browser & Frontend](#browser--frontend)
    - [More than just frameworks or libs](#more-than-just-frameworks-or-libs)
    - [Rendering Methods Explained Simply (SSR, CSR, SSG, ISR)](#rendering-methods-explained-simply)
3. [Softwares & System Design](#softwares--system-design)
    - [The Trombone Effect](#the-trombone-effect)
4. [Notes](#notes)

---

# Maths & Physics Glossary

### 🔖 snippets from the physics & mathematics world

#### Physics Glossary

- **Quantum**:  
  The discrete, indivisible unit of a physical quantity.  
  **Formula**: E=hν (energy of a quantum, where E is energy, h is Planck's constant, and ν is the frequency).

- **Entanglement**:  
  Particles become correlated so that the state of one instantly affects the state of another, regardless of distance.  
  **Formula**: |ψ⟩ = 1/√2 (|00⟩ + |11⟩)

- **Heisenberg Uncertainty Principle**:  
  One cannot simultaneously know the exact position and exact momentum of a particle.  
  **Formula**: Δx⋅Δp≥2ℏ (uncertainty relation, where Δx is the uncertainty in position, Δp is the uncertainty in momentum, and ℏ is the reduced Planck's constant).

- **Quantum Tunneling**:  
  A particle traverses a potential energy barrier that it classically could not surmount.  
  **Formula**: T≈e−2γa (transmission coefficient T for tunneling, where γ is a constant related to the barrier height and width a).

- **Superposition**:  
  A quantum system can exist simultaneously in multiple states until it is measured.  
  **Formula**: ∣ψ⟩=a∣0⟩+b∣1⟩ (quantum state ∣ψ⟩ is a combination of states ∣0⟩ and ∣1⟩, with probabilities a and b).

- **Wave-Particle Duality**:  
  Quantum entities exhibit both particle-like and wave-like properties.  
  **Formula**: λ=ph (de Broglie wavelength, where λ is the wavelength, h is Planck's constant, and p is momentum).

---

# Browser & Frontend

### & more than just frameworks or libs

A compilation of topics that can benefit any frontend developer with curiosity and a more in-depth understanding of *Browsers* and *JavaScript*.

1. Accessibility (a11y), Accessibility Testing Tools (e.g., Axe, Lighthouse), Algorithms, Async/Await, Browser Compatibility, Box Model
2. Closure, CORS, CSP, CSS, CI/CD, CDN, CLS, Cache-Control
3. DOM, DRY, Data Structures, Dependency Injection, Design Patterns
4. Event Loop, Event Bubbling, ES6, e2e Testing
5. FCP, Fetch, Flexbox
6. Grid (CSS), Gzip, Git Commands
7. Hoisting, HOC (for React), HTTP Headers
8. IIFE, Internationalization (i18n)
9. JavaScript quirks, KISS
10. Lazy Loading, LCP, localStorage vs sessionStorage vs IndexedDB
11. Memoization, Micro-frontends, MVC
12. Null vs Undefined, OOP, OAuth
13. Promise, Polyfill, Prototype, PWA, Prefetch
14. Query String, Responsive Design, RESTful API
15. SOLID, SSR, SSG, SPA, SEO
16. Throttle vs Debounce, TDD, `this` keyword
17. UX/UI Principles, Virtual DOM, VCS
18. Webp, Web APIs, WebSockets, Web Workers
19. XHR, XSS, Yarn vs npm vs pnpm
20. Z-index complexities
21. Middleware, Module Federation, State Management
22. Error Handling, Code Splitting, WebAssembly
23. Frontend Monitoring and Analytics
24. Web Browser Security Models
25. Browser Storage (Cookies, Local Storage, Session Storage)

---

# Rendering Methods Explained Simply

### 1. Server-Side Rendering (SSR)

- **Definition**: The server generates the full HTML for a page on each request.
- **How it works**: When a user requests a page, the server processes the request, fetches data, and sends back a fully rendered HTML page.
- **Benefit**: Better for SEO and faster initial load times.
- **Example**: Traditional websites where each page load involves a round-trip to the server.

### 2. Client-Side Rendering (CSR)

- **Definition**: The browser renders the page using JavaScript.
- **How it works**: The server sends a minimal HTML page with a JavaScript file. The browser executes the JavaScript, fetches data, and updates the UI.
- **Benefit**: Smooth transitions between pages and dynamic content updates without reloading.
- **Example**: Single Page Applications (SPAs) like those built with React.

### 3. Static Site Generation (SSG)

- **Definition**: HTML pages are generated at build time and served as static files.
- **How it works**: During the build process, the server generates all the HTML pages. These pages are then served directly to the user without additional server processing.
- **Benefit**: Extremely fast page loads and great for SEO.
- **Example**: Documentation sites, blogs, or marketing websites where content doesn't change frequently.

### 4. Incremental Static Regeneration (ISR)

- **Definition**: Allows static pages to be updated incrementally after the site is built.
- **How it works**: Similar to SSG, but with the ability to update or add static pages at runtime without rebuilding the entire site.
- **Benefit**: Combines the speed of SSG with the flexibility of updating content as needed.
- **Example**: E-commerce sites where product details need periodic updates without rebuilding the entire site.

---

# Softwares & System Design

### The Trombone Effect (Accordion or Telescope Effect)

**The trombone effect**, also known as the telescope effect or accordion effect, refers to the phenomenon where changes made at one end of a system take longer to propagate and be noticed at the other end.

- **Example 1**:  
  In a large company, a decision made by upper management to change policies might take weeks or months before it's fully implemented and understood by employees at the operational level. This delay in communication and implementation illustrates the trombone effect, where there's a significant lag between action and perception across different levels or parts of a system.

- **Example 2**:  
  When making an international call, there's often a delay between speaking and when the person on the other end hears you. This delay occurs because the signal travels through various networks, experiencing processing delays or congestion. This also happens in online gaming, where latency affects the time it takes for actions to reach the game server and for the server’s response to return, impacting gameplay.

---

# Notes

This page is continuously evolving as more knowledge is added. Bookmark this repository and return often for the latest updates in the encyclopedia!
