# 🏆 SCINNOVA IX — Official Science Olympiad Web Platform

[![Organization: Cedar College](https://img.shields.io/badge/Institution-Cedar_College-green?style=for-the-badge)]()
[![Society: Cedar CODES](https://img.shields.io/badge/Society-Cedar_CODES-blue?style=for-the-badge)]()
[![Award: Honorary Shield](https://img.shields.io/badge/Distinction-Honorary_Award_Shield-gold?style=for-the-badge)]()
[![Animation: GSAP 3](https://img.shields.io/badge/Motion-GSAP_3.12_%2F_ScrollTrigger-88CE02?style=for-the-badge&logo=greensock&logoColor=white)]()

Official digital gateway and interactive platform engineered for **SCINNOVA IX**—Cedar College's 9th International Inter-School Science Olympiad held in Karachi, Pakistan. 

Awarded the **Honorary Award Shield** and **Certificate of Recognition** on stage by Event Patron **Sir Rayyan Dawood** for sole technical architecture and design execution.

---

## 🎖️ Institutional Commendation & Recognition

<div align="center">
  <img src="Scinnova%20IX%20Photo.jpeg" width="450" alt="Honorary Shield presented by Patron Sir Rayyan Dawood" />
  <p><em>Honorary Award Shield presented by Patron Sir Rayyan Dawood on stage during the SCINNOVA IX Grand Closing Ceremony</em></p>
  <br />
  <img src="Scinnova%20IX.png" width="450" alt="Certificate of Recognition" />
  <p><em>Official Cedar College Certificate of Recognition for Technical Architecture</em></p>
</div>

---

## 🏛️ Platform Mission & Event Overview

SCINNOVA IX is one of Pakistan's premier high school science competitions, convening hundreds of delegates across competing schools. The event required an immersive, modern web experience to showcase complex tournament modules, rules, schedule timelines, and FAQs.

### Competitive STEM Modules Featured:
1. **Arcanum (Chemical Sciences):** High-stakes laboratory puzzles and qualitative analysis.
2. **Asclepius (Biological & Medical Sciences):** Clinical diagnostic rounds and emergency medicine simulations.
3. **Redshift (Astrophysics & Cosmology):** Orbital mechanics, stellar evolution, and deep-space physics.
4. **Ptolemy's Puzzle (Mathematics & Logic):** Combinatorics, number theory, and algorithmic problem-solving.

---

## 🛠️ Frontend Motion Architecture & Performance

```mermaid
flowchart TD
    subgraph Viewport & Smooth Scroll
        LENIS[Studio Freight Lenis / Inertial Scroll Engine]
        NOISE[Custom Canvas Noise & Cursor DOT Engine]
        WRAP[Smooth Scroll DOM Wrapper]
        LENIS --> WRAP
    end

    subgraph Motion Graphics Pipeline [GSAP 3.12]
        ST[ScrollTrigger / Hardware Accelerated Milestones]
        TP[TextPlugin / Dynamic Typography Shifts]
        PARTICLES[Canvas Confetti / Celebration Particles]
        ST --> WRAP
        TP --> WRAP
    end

    subgraph Responsive Layout Modules
        HERO[Hero Gateway & Event Countdown]
        MODULES[Interactive Competition Directories]
        FAQS[Dynamic Accordion & Rule Breakdown]
        REG[Registration Routing & Link Gateways]
    end

    WRAP --> HERO
    WRAP --> MODULES
    WRAP --> FAQS
    WRAP --> REG
```

### Engineering Highlights:
* **Zero-Framework Vanilla JS Engine:** Built with semantic HTML5, modular CSS3, and modern ES6+ to avoid framework bundle bloat and ensure instantaneous initial contentful paint (FCP < 0.8s).
* **Inertial Smooth Scrolling (`Lenis`):** Normalized scroll mechanics across Mac, Windows, iOS, and Android to guarantee consistent interaction physics.
* **Scroll-Driven Milestones (`GSAP ScrollTrigger`):** Pinned sections and scrubbed timeline animations that reveal module details as delegates navigate through the site.
* **120Hz Mobile Frame-Rate Tuning:** Converted layout animations to use GPU-accelerated CSS `transform` and `opacity` properties, maintaining a sustained 60+ FPS across low-to-mid range mobile viewports.

---

## 📁 Repository Contents

* `Scinnova IX Photo.jpeg`: High-resolution photograph of the Honorary Award Shield.
* `Scinnova IX.png`: High-resolution scan of the Cedar College Certificate of Recognition.
* `README.md`: Event specifications, motion architecture, and engineering review.

---

## 📄 License
Documented and published under the [MIT License](LICENSE).
