# Personal Profile Website

> **Course:** Internet Programming I (SWEG3107)  
> **Institution:** Addis Ababa Science and Technology University (AASTU)  
> **Department:** Department of Software Engineering  
> **Student:** Abraham Tiruneh

A multi-page personal portfolio developed as a practical laboratory project for Internet Programming I. This repository serves as a step-by-step learning platform for web technologies, starting with semantic HTML5 document structures, progressing through CSS layouts, and preparing for client-side JavaScript interactivity.

---

## Learning & Implementation Roadmap

This project is built incrementally through practical laboratory exercises:

1. **Phase 1: Semantic HTML5 (Current Foundation)**
   - Standard document structure (`<!DOCTYPE html>`, `<head>`, `<body>`).
   - Semantic content elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`).
   - Hyperlinks and multi-page site navigation.
   - Data presentation with tables (`<thead>`, `<tbody>`, `<caption>`).
   - Built-in indicators and interactive disclosures (`<progress>`, `<meter>`, `<details>`, `<summary>`).
   - Native multimedia embedding (`<audio>`, `<video>` with WebVTT captions, `<iframe>`).
   - Comprehensive user input forms with fieldsets, legends, input types, and native validation.

2. **Phase 2: CSS Styling & Layout (In Progress)**
   - Practicing the three fundamental CSS integration methods:
     - **External Stylesheet:** Applied to `index.html` using a shared `style.css` file for site-wide rules.
     - **Internal Stylesheet:** Applied to `about.html` using a `<style>` block in the document `<head>`.
     - **Inline Styles:** Applied to `contact.html` using `style` attributes directly on HTML tags.
   - Future practice: Progressively styling the remaining pages (`skills.html`, `projects.html`, `media.html`), applying Flexbox, CSS Grid, and responsive media queries.

3. **Phase 3: JavaScript & Interactivity (Upcoming)**
   - Client-side form validation and feedback.
   - Dynamic DOM manipulation and content updates.
   - Interactive UI behavior and event handling.

---

## Website Pages

The repository contains six interconnected pages:

| Page | File | Purpose |
| :--- | :--- | :--- |
| **Home** | `index.html` | Welcome introduction, portrait image, navigation menu, and overview links. |
| **About Me** | `about.html` | Personal biography, academic background, interests, core values, and quotes. |
| **Skills & Education** | `skills.html` | Academic qualifications, technical competencies, learning progress indicators, and study plans. |
| **Projects & Achievements** | `projects.html` | Project showcases with figures, architecture outlines, categorized achievements, and downloadable reports. |
| **My Media & Interests** | `media.html` | Native audio and video playback, closed captions, embedded learning videos, and reference resources. |
| **Contact Me** | `contact.html` | Direct email contact and a multi-section form with various input types and validation. |

---

## Media & Asset Files (`files/`)

All static media and document files are organized inside the `files/` directory:

- `profile.jpg`: Personal portrait image.
- `preview.jpg`: Poster image for video playback and project previews.
- `movie.mp4`: Sample video file for native video playback.
- `captions.vtt`: WebVTT closed captions file for video accessibility.
- `sound.mp3` & `sound.wav`: Audio tracks demonstrating format fallback support.
- `project-report.pdf`: Sample downloadable project documentation report.

---

## How to View the Project

1. Clone or download the repository to your local computer:
   ```bash
   git clone https://github.com/EstarCode/IP-lab.git
   ```
2. Navigate into the project folder:
   ```bash
   cd IP-lab
   ```
3. Open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari).
