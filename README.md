# Personal Profile Website

> **Internet Programming I (SWEG3107)**  
> Department of Software Engineering, Addis Ababa Science and Technology University (AASTU)  
> Student: **Abraham Tiruneh**

A multi-page personal portfolio website built with semantic HTML5 strictly adhering to the **SWEG3107 Lab Exercise** specifications and reference examples. It demonstrates modern markup, media embedding, navigation hierarchy, tables, accessible forms, progress indicators, and rich content structure.

---

## CSS Implementation & Demonstration (3 Techniques across 3 Pages)

To demonstrate mastery of all three CSS styling methodologies, an expert and cohesive design system has been applied across **three designated pages** (leaving the remaining pages in pure HTML ready to be styled over time):

1. **External CSS — [`index.html`](file:///c:/Users/hp/Desktop/ip/index.html)**
   - **Method:** Links to an external master stylesheet [`style.css`](file:///c:/Users/hp/Desktop/ip/style.css) via `<link rel="stylesheet" href="style.css">`.
   - **Features:** CSS variables (`:root`), global reset, responsive container, gradient hero banner, circular avatar with hover transitions, pill-shaped navigation, card elevations with subtle shadows, and responsive media queries.
   - **Bonus Demonstrations:** Includes an internal style badge in `<head>` and an inline style override on the motto card to illustrate cascading precedence.

2. **Internal CSS — [`about.html`](file:///c:/Users/hp/Desktop/ip/about.html)**
   - **Method:** Uses a dedicated `<style>` block embedded inside the document's `<head>`.
   - **Features:** Self-contained styling tailored to the page, featuring an indigo/violet nocturnal theme, glowing badge, active navigation pill on "About Me", multi-column grid layout for core values (`<dl>`, `<dt>`, `<dd>`), custom quote card, and styled timestamps (`<time>`).

3. **Inline CSS — [`contact.html`](file:///c:/Users/hp/Desktop/ip/contact.html)**
   - **Method:** Exclusively uses direct `style="..."` attributes on individual HTML tags (with zero `<link>` stylesheets and zero internal `<style>` tags).
   - **Features:** Emerald green color theme, styled fieldsets with colored legends, polished form inputs (`text`, `email`, `tel`, `url`, `date`, `color`, `range`), custom radio options, and gradient submit/reset action buttons.

4. **Pure HTML Pages (To be styled over time):**
   - **[`skills.html`](file:///c:/Users/hp/Desktop/ip/skills.html)**
   - **[`projects.html`](file:///c:/Users/hp/Desktop/ip/projects.html)**
   - **[`media.html`](file:///c:/Users/hp/Desktop/ip/media.html)**

---

## Website Structure

The website consists of six core pages interconnected through a consistent navigation header:

1. **Home (`index.html`)**
   - Welcome introduction and profile hero section.
   - Profile image with appropriate alt text.
   - Global navigation menu linking all six pages.
   - "A Little About Me" summary preview linking to `about.html`.
   - "What I'm Working Toward" itemized list linking to `skills.html`.
   - Personal motto quote block.
   - "Explore My Work" preview linking to `projects.html`.
   - Semantic `<header>`, `<main>`, `<section>`, and `<footer>` elements.

2. **About Me (`about.html`)**
   - Personal biography and background in Software Engineering at AASTU.
   - Educational background with `<abbr>` abbreviation tag.
   - Personal and academic interests list.
   - Core values structured with a description list (`<dl>`, `<dt>`, `<dd>`).
   - Quotation block (`<blockquote>`, `<q>`).
   - Future ambitions and learning journey with machine-readable date (`<time>`).
   - Return navigation links in the footer.

3. **Skills and Education (`skills.html`)**
   - Educational background table (`<table>`, `<caption>`, `<thead>`, `<tbody>`).
   - Technical skills matrix table.
   - Visual progress indicators using native HTML5 `<progress>` and `<meter>` elements.
   - Technical definitions using a description list (`<dl>`).
   - Interactive disclosure widgets using `<details>` and `<summary>` for monthly learning plans.
   - External reference links to MDN and W3Schools documentation.

4. **Projects & Achievements (`projects.html`)**
   - Featured projects with `<article>`, `<figure>`, `<figcaption>`, and descriptive summaries.
   - Categorized nested lists outlining website sections and system architectures.
   - Categorized achievements (Learning, Academic, Personal).
   - Direct download link for project documentation (`files/project-report.pdf`).
   - Future goals roadmap.

5. **My Media and Interests (`media.html`)**
   - Native HTML5 `<audio>` player with fallback formats (`.mp3`, `.wav`).
   - Native HTML5 `<video>` player with poster image and timed subtitles (`captions.vtt`).
   - Responsive embedded YouTube media using `<iframe>`.
   - Categorized nested topics list outlining technological and personal interests.
   - Curated external learning resources.

6. **Contact Me (`contact.html`)**
   - Direct email contact link and website link.
   - Comprehensive HTML5 form with 3 grouped fieldsets (`<fieldset>`, `<legend>`):
     1. *Personal Information:* `text` (Full Name), `email` (Email Address), `tel` (Phone Number), and `url` (Website).
     2. *Message Details:* `select` (Subject), `radio` (Discovery source), and `textarea` (Message).
     3. *Optional Information:* `date` (Contact Date), `color` (Favorite Color), `range` (Website Rating), and `checkbox` (Reply requested).
   - Submit and reset action buttons.
   - Social links and return navigation.

---

## Assets & Media Directory (`files/`)

- `profile.jpg`: Personal portrait image.
- `preview.jpg`: Video poster and project preview thumbnail.
- `movie.mp4`: Sample HTML5 video file.
- `captions.vtt`: WebVTT captions track.
- `sound.mp3` & `sound.wav`: Audio demo tracks.
- `project-report.pdf`: Sample downloadable project documentation.

---

## How to View

Open `index.html` in any modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari).
