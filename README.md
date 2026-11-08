# Personal Profile Website

> **Internet Programming I (SWEG3107)**  
> Department of Software Engineering, Addis Ababa Science and Technology University (AASTU)  
> Student: **Abraham Tiruneh**

A multi-page personal portfolio website built with semantic HTML5 strictly adhering to the **SWEG3107 Lab Exercise** specifications. It demonstrates modern markup, media embedding, navigation hierarchy, tables, accessible forms, progress indicators, and rich content structure.

---

## Styling Architecture (Three CSS Methodologies)

To demonstrate mastery of all three CSS styling methodologies, an academic design system has been applied across **three designated pages** (leaving the remaining three pages in pure semantic HTML ready to be styled over time):

1. **External CSS — [`index.html`](file:///c:/Users/hp/Desktop/ip/index.html)**
   - **Method:** Links to an external master stylesheet [`style.css`](file:///c:/Users/hp/Desktop/ip/style.css) via `<link rel="stylesheet" href="style.css">`.
   - **Features:** CSS custom properties (`:root`), global reset, responsive container, dark navy header banner, circular avatar with hover transitions, pill-shaped navigation, clean card elevations, and responsive media queries.

2. **Internal CSS — [`about.html`](file:///c:/Users/hp/Desktop/ip/about.html)**
   - **Method:** Uses a dedicated `<style>` block embedded inside the document's `<head>`.
   - **Features:** Self-contained styling tailored to the page, featuring an academic slate/navy theme, active navigation pill on "About Me", multi-column grid layout for core values (`<dl>`, `<dt>`, `<dd>`), custom quote card, and styled timestamps (`<time>`).

3. **Inline CSS — [`contact.html`](file:///c:/Users/hp/Desktop/ip/contact.html)**
   - **Method:** Exclusively uses direct `style="..."` attributes on individual HTML tags (with zero `<link>` stylesheets and zero internal `<style>` tags).
   - **Features:** Unified academic navy/slate theme, styled fieldsets with clean legend labels, polished form inputs (`text`, `email`, `tel`, `url`, `date`, `color`, `range`), and submit/reset action buttons.

4. **Pure Semantic HTML Pages (To be styled over time):**
   - **[`skills.html`](file:///c:/Users/hp/Desktop/ip/skills.html)**
   - **[`projects.html`](file:///c:/Users/hp/Desktop/ip/projects.html)**
   - **[`media.html`](file:///c:/Users/hp/Desktop/ip/media.html)**

---

## Website Structure

The website consists of six core pages interconnected through a consistent navigation header:

1. **Home (`index.html`)**
   - Profile hero section with student details and portrait.
   - Global navigation menu linking all six pages.
   - Summary preview linking to biography.
   - Itemized goals list linking to skills and education.
   - Personal motto block.
   - Featured work preview linking to projects.

2. **About Me (`about.html`)**
   - Biography and academic background at AASTU.
   - Educational details with `<abbr>` tag.
   - Key academic and extracurricular interests list.
   - Core values structured with a description list (`<dl>`, `<dt>`, `<dd>`).
   - Guiding principle quote block (`<blockquote>`).
   - Future ambitions and learning journey with machine-readable date (`<time>`).

3. **Skills and Education (`skills.html`)**
   - Educational background table (`<table>`, `<caption>`, `<thead>`, `<tbody>`).
   - Core technical competencies table.
   - Visual progress indicators using native HTML5 `<progress>` and `<meter>` elements.
   - Foundational concepts description list (`<dl>`).
   - Interactive disclosure widgets using `<details>` and `<summary>` for academic learning plans.
   - External reference links to MDN and W3Schools documentation.

4. **Projects & Achievements (`projects.html`)**
   - Featured projects with `<article>`, `<figure>`, `<figcaption>`, and descriptive summaries.
   - Categorized nested lists outlining system architectures and platform modules.
   - Categorized achievements (Learning, Academic, Personal).
   - Direct download link for project documentation (`files/project-report.pdf`).
   - Future engineering milestones.

5. **My Media and Interests (`media.html`)**
   - Native HTML5 `<audio>` player with fallback formats (`.mp3`, `.wav`).
   - Native HTML5 `<video>` player with poster image and timed subtitles (`captions.vtt`).
   - Embedded educational resource using `<iframe>`.
   - Categorized nested topics list outlining technical and personal pursuits.
   - Curated technical documentation references.

6. **Contact Me (`contact.html`)**
   - Direct email contact and portfolio links.
   - Comprehensive HTML5 form with 3 grouped fieldsets (`<fieldset>`, `<legend>`):
     1. *Personal Information:* `text` (Full Name), `email` (Email Address), `tel` (Phone Number), and `url` (Website).
     2. *Message Details:* `select` (Subject), `radio` (Discovery source), and `textarea` (Message).
     3. *Optional Information:* `date` (Contact Date), `color` (Preferred Color), `range` (Rating), and `checkbox` (Reply requested).
   - Submit and reset action buttons.
   - Professional network links and return navigation.

---

## Assets & Media Directory (`files/`)

- `profile.jpg`: Personal portrait image.
- `preview.jpg`: Video poster and project preview thumbnail.
- `movie.mp4`: Sample HTML5 video file.
- `captions.vtt`: WebVTT captions track.
- `sound.mp3` & `sound.wav`: Audio demo tracks.
- `project-report.pdf`: Downloadable project specification report.

---

## How to View

Open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari).
