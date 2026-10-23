# Hypermedia Project: Personal Portfolio & CV Website

A responsive, single-page Curriculum Vitae and portfolio website designed for **Daniel Teruel Segura**, a Game Design and Development student specialized in programming, interactive mechanics, and 3D environments.


##  Project Links

**Live Website (GitHub Pages):** 
**Figma Design Proposal:** https://www.figma.com/design/AcJmKNEv5LIluemlJxCe2q/Untitled?node-id=1-61&t=sVjhsdZYd2qLJiTd-1



## 1. Project Analysis

###  User Profile (User Persona)

 **Target Audience:** Video game studio recruiters, lead game programmers, and potential project collaborators.
 **User Profile — Technical Recruiter / Studio Lead:**
   **Name:** Sarah Jenkins (Technical Talent Acquisition Specialist at a Game Studio)
   **Goals:** Quickly evaluate candidate skills, verify programming proficiency (C++, C#, engines), inspect actual game projects, and contact the applicant effortlessly.
   **Pain Points:** Hard-to-read traditional PDF resumes, lack of visual proof/code samples, complex website navigation, and non-responsive layouts on mobile devices.
   **Expectations:** A clean, professional, fast-loading, developer-oriented portfolio that highlights technical stack and independent game projects at a glance.


###  Information Architecture

The web project is designed as a single-page layout to offer a fluid narrative. Information is organized hierarchically into six clear numerical sections to maximize the reading flow.

**Header & Hero Section (`#home`):** Serves as the first visual impact. It contains a high-contrast navbar with smooth-scrolling links, a logo (`DTS`), a clear job title (*Programmer & Game Developer*), a brief introduction, and primary buttons (*View Projects*, *Contact Me*).
**01. About Me (`#about`):** Provides a concise personal summary outlining academic background in Game Design and Development at UdG, core technical interests (physics, 3D environments), and a  card highlighting geographic location and current studies.
**02. Skills (`#skills`):** Categorizes core competencies into four distinct cards: *Programming* (C++, C#, Java, Python, Lua, HTML, CSS), *Game Development* (Unity, Unreal Engine), *3D & Environment* (Blender, Gaea, Terragen 4), and *Tools* (Visual Studio, Excel).
**03. Projects (`#projects`):** Highlights three major independent projects (*Mistborn*, *Realistic Scene*, *Programming Projects*). Each card displays an ordinal number, title, concise description, and technology tags.
**04. Education (`#education`):** Displays a structured chronological timeline summarizing academic qualifications (University degree at UdG and Higher Degree in Economics at Escoles Freta).
**05. Languages:** Displays language proficiency (Spanish, Catalan, English C1) in clean grid cards.
**06. Contact (`#contact`) & Footer:** Concludes the page with a dark-themed call to action, offering direct interactive links for email (`mailto:`) and telephone (`tel:`), alongside a copyright notice and a "Back to top" navigation link.


###  Visual Design

The visual design system reflects a modern, technical, and minimal aesthetic tailored specifically for game development and software engineering roles.

**Color Palette:**
  **Primary Backgrounds:** Slate/Dark Navy (`#111827`, `#1f2937`) for header, contact, and footer sections to establish high-tech contrast and focus.
  **Light Background:** Clean Off-White (`#f8fafc`) for body sections to ensure optimal text readability and contrast.
  **Accent Color:** Electric Sky Blue (`#38bdf8`) used for ordinal numbers (`01`, `02`), active links, category highlights, and primary buttons. It draws immediate visual focus to key elements without overwhelming the layout.
  **Text Colors:** Charcoal Dark Gray (`#1e293b`) for primary headings and Muted Gray (`#64748b`) for body prose and sub-captions.
**Typography:**
  Uses a robust system font stack (`system-ui`, `Segoe UI`, `Helvetica`, `Arial`).
  Section index numbers and project codes utilize a `monospace` font family to reinforce a developer-centric coding vibe.
  Heading hierarchy uses heavy weights (`font-weight: 800`) with responsive `clamp()` font scaling for fluid readability across devices.
**Page Layout & UI Patterns:**
  Modern CSS Flexbox and Grid structures (`repeat(auto-fit, minmax(...))`) guarantee dynamic card alignment.
  Interactive micro-interactions (hover elevation `transform: translateY(-5px)` and subtle box shadows) enhance affordance and visual depth.


## 2. Technical Implementation & Considerations

**Technologies Used:** Semantic HTML5, Custom CSS3 (Flexbox, CSS Grid, CSS Custom Properties/Variables), CSS Animations.
**Framework Justification:** Pure HTML5 and CSS3 were chosen over third-party frameworks like Bootstrap or Tailwind to maintain full architectural control over the codebase, ensure zero external dependencies, minimize loading times, and demonstrate solid foundational web development skills.
**Responsiveness:** Fully responsive design tested across desktop, tablets and mobile devices using media queries (`@media (max-width: 768px)`).
**Code Documentation:** Detailed comments and annotations have been added directly within the CSS stylesheet to break down and explain the most interesting lines of code and layout techniques.