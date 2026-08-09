# Health Essentials — HCI Midterm Case Study

An end-to-end user research and information architecture case study analyzing how students in a university hostel find health essentials during urgent, painful, and ordinary moments. 

This repository contains the interactive case file built using pure semantic HTML and CSS, designed to resemble a professional research file.

## 📂 Project Structure

```
health-essentials-case-study/
│
├── README.md                          # Project overview and documentation (this file)
└── health-essentials-case-study/      # Main application directory
    ├── index.html                     # Core HTML file containing the research case study
    ├── style.css                      # Custom vanilla CSS for layouts, typography, and charts
    └── assets/                        # Supporting scans of field notes and diagrams
        ├── broken-experience.jpg
        ├── proto-persona.jpg
        ├── true-persona.jpg
        ├── empathy-map.jpg
        ├── journey-map.jpg
        ├── emotion-line.jpg
        ├── user-stories.jpg
        ├── ia-v1.png
        ├── ia-v2.png
        ├── tree-test-1.png
        ├── tree-test-2.png
        └── moscow.png
```

---

## 🔬 Research & Design Process

This project documents a rigorous Human-Computer Interaction (HCI) research and design methodology split into three core phases:

### Phase 1: Empathize & Define
* **The Broken Experience:** Traced the real-world friction students face when looking for health essentials (like bandages or sprays) in a hostel environment.
* **User Personas:** Designed a Proto-Persona and subsequently refined it into a data-driven True Persona using insight from 3 target user interviews and an 8-respondent survey.
* **Empathy Map:** Mapped what users Say, Think, Do, and Feel during a health emergency.
* **Journey Mapping:** Charted the user journey for a specific late-night incident (insect bite), tracing user actions, thoughts, and emotions to pinpoint the exact moment of greatest frustration.

### Phase 2: Ideate & Evaluate
* **Card Sorting:** Conducted an open/hybrid card sorting exercise with 10 participants using 20 candidate features, resulting in 5 logical categories: *Find Essentials*, *Requests*, *Contacts*, *Medical Support*, and *My Essentials*.
* **Tree Testing:** Evaluated the V1 Information Architecture (IA) with 5 students across 5 core findability tasks. The feedback highlighted user navigation expectations for "Request History" and "Campus Emergency Contacts", leading to the revised and optimized Final IA (V2).

### Phase 3: Prioritization
* **MoSCoW Matrix:** Classified features into *Must Have*, *Should Have*, *Could Have*, and *Won't Have* to define a clean Minimum Viable Product (MVP).
* **DFV (Desirability, Feasibility, Viability) Analysis:** Evaluated core features on a 1–5 scoring scale to finalize development priorities (e.g., verifying why *Search Health Essentials* won the final Must-Have spot over other candidates).

---

## 🛠️ Built With

* **HTML5:** Semantic markup structure (using `<main>`, `<section>`, `<nav>`, `<figure>`, `<article>`, `<header>`, etc.) optimized for accessibility.
* **CSS3:** Custom responsive layout, styled charts, and interactive sidebar navigation. 
* **SVG:** Custom inline SVG vector drawings for interactive vitals/emotion line charts.
* **Zero Frameworks:** No JavaScript or CSS frameworks are used, adhering strictly to pure front-end fundamentals.

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/shindepratiksha885-sudo/Human-computer-interaction-UI-UX.git
   ```
2. Navigate into the project folder:
   ```bash
   cd health-essentials-case-study/health-essentials-case-study
   ```
3. Open `index.html` directly in any web browser to view the interactive case study file.
