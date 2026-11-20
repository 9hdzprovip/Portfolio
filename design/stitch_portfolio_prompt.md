# STITCH PROMPT — MODERN JAVA BACKEND DEVELOPER PORTFOLIO

## 1. Project goal

Design a complete, modern, responsive personal portfolio website for **Le Duc Chinh**, a Computer Science student at Hanoi University of Science and Technology who is pursuing **Java Backend Developer / Java Backend Intern / Fresher** opportunities.

The website must feel professional, technically credible, clean, and memorable. It should help a recruiter understand within 5–10 seconds:

- Who the candidate is.
- Which role he is seeking.
- His main backend technologies.
- His strongest projects.
- How to view his CV, GitHub, LinkedIn, and contact him.

This is a **single-page portfolio website**. The navigation items must scroll smoothly to sections on the same page. Do not create separate pages, except optional project-detail modal or expandable case-study panels.

## 2. Visual direction

Use a combination of:

- Modern Bento Grid layout.
- Dark minimal developer aesthetic.
- A small amount of glassmorphism.
- Subtle blue-violet glow.
- Clean typography and generous spacing.
- Professional backend-engineer identity rather than a designer or gaming identity.

The design should resemble a polished combination of Linear, Vercel, GitHub, and a modern SaaS dashboard.

Do not make the site look like a generic template. Do not use excessive 3D objects, large animated illustrations, strong neon, loud gradients, floating blobs, or distracting effects.

## 3. Color system

Use this design system consistently:

- Main background: `#080A0F`
- Secondary background: `#0D1117`
- Card background: `#111722`
- Elevated card background: `#151C29`
- Primary text: `#F4F7FB`
- Secondary text: `#9BA7B7`
- Muted text: `#697586`
- Border: `rgba(255, 255, 255, 0.08)`
- Primary accent: `#6C8CFF`
- Secondary accent: `#8B5CF6`
- Success accent: `#35D07F`
- Hover border: `rgba(108, 140, 255, 0.50)`

Use gradients only as subtle accents:

```css
linear-gradient(135deg, #6C8CFF 0%, #8B5CF6 100%)
```

Cards should have a very subtle inner highlight and soft shadow. Avoid heavy blur that reduces readability.

## 4. Typography

- Main font: Inter, Manrope, or Plus Jakarta Sans.
- Optional monospace font for technical labels: JetBrains Mono.
- Large, bold hero heading with tight letter spacing.
- Clear hierarchy between headings, body copy, labels, and metadata.
- Body text must remain readable and not become too small.

Recommended desktop sizes:

- Hero name: 64–76px.
- Section heading: 36–44px.
- Card title: 20–24px.
- Body: 16–18px.
- Label/tag: 12–14px.

## 5. Global layout

- Maximum content width: 1200–1280px.
- Center the page content.
- Desktop horizontal padding: 32–48px.
- Mobile horizontal padding: 18–20px.
- Use a 12-column grid on desktop.
- Use rounded cards with a 16–22px radius.
- Keep consistent gaps of 16–24px.
- Give each main section enough vertical breathing room.

The website must include these navigation tabs:

1. Home
2. About
3. Skills
4. Projects
5. Education
6. Contact

All tabs point to anchors on the same page.

## 6. Header / navigation

Create a slim sticky navigation bar at the top.

Left side:

- Minimal logo using the initials `LDC` inside a rounded square.
- Text: `Le Duc Chinh`

Center or right side:

- Home
- About
- Skills
- Projects
- Education
- Contact

Far right:

- Theme icon button, even if dark mode is the default.
- Primary compact button: `Download CV`

Behavior:

- Use a semi-transparent dark background with backdrop blur after scrolling.
- Highlight the active section in the navigation.
- Collapse into a clean hamburger menu on mobile.
- The mobile menu must be easy to close and must not cover content incorrectly.

## 7. Hero section — Bento layout

Use an asymmetric Bento Grid. The main introduction card should occupy about two-thirds of the width on desktop. Supporting cards occupy the remaining area.

### Main hero card

Use this exact content:

```text
AVAILABLE FOR INTERNSHIP / FRESHER OPPORTUNITIES

Hi, I'm
Le Duc Chinh.

Java Backend Developer

I build reliable backend applications with Java, Spring Boot, RESTful APIs, and relational databases.

[View My Projects] [Download CV]
```

Add a small green status dot before the availability label.

Add a subtle terminal-style line near the bottom:

```text
chinh@portfolio:~$ building scalable backend systems
```

The main CTA `View My Projects` uses the blue-violet gradient. `Download CV` is an outlined secondary button.

### Profile card

Include a clean portrait placeholder, not a random stock photo. Label it clearly so the real image can be replaced later:

```text
[PROFILE PHOTO PLACEHOLDER]
```

Under the image:

```text
Le Duc Chinh
Hanoi, Vietnam
```

Add small GitHub and LinkedIn icon buttons.

### Current focus card

```text
CURRENTLY FOCUSED ON

Spring Boot
Docker
Microservices
Kafka
```

Display the technologies as clean rows or compact pills. This represents current learning direction; do not describe all of them as professional experience.

### Quick information card

```text
STATUS
Open to work

ROLE
Java Backend Intern / Fresher

LOCATION
Hanoi, Vietnam
```

### Scroll indicator

Add a small, subtle `Scroll to explore` indicator below the hero grid.

## 8. About section

Section eyebrow:

```text
01 / ABOUT ME
```

Section heading:

```text
Building a strong foundation in backend engineering.
```

Use this body copy:

```text
I am a Computer Science student at Hanoi University of Science and Technology, pursuing a career in Java Backend Development. I enjoy turning business requirements into structured, maintainable applications and learning how reliable backend systems are designed, secured, and deployed.

Through academic and personal projects, I have worked with Spring Boot, Spring Data JPA, Spring Security, JWT authentication, PostgreSQL, MySQL, RESTful APIs, and React. I am currently strengthening my knowledge of Docker, microservices, CI/CD, and event-driven systems.
```

Beside the text, create three compact statistic cards:

```text
02+
Full-stack Projects

Java
Primary Language

HUST
Computer Science
```

Do not invent years of professional experience, client numbers, GitHub statistics, or employment history.

## 9. Skills section

Section eyebrow:

```text
02 / TECH STACK
```

Section heading:

```text
Technologies I use to build applications.
```

Display skills inside a Bento Grid with icons and text. Use official-looking monochrome or softly colored icons, but do not let icons dominate the design.

### Backend card — largest card

```text
BACKEND

Java
Spring Boot
Spring MVC
Spring Security
Spring Data JPA
Hibernate
RESTful API
JWT Authentication
Maven
```

### Database card

```text
DATABASE

PostgreSQL
MySQL
SQL
Database Design
```

### Frontend card

```text
FRONTEND

React
JavaScript
HTML
CSS
Vite
```

### Tools card

```text
TOOLS

Git
GitHub
Postman
IntelliJ IDEA
VS Code
Linux
```

### Currently learning card

```text
CURRENTLY LEARNING

Docker
Microservices
Kafka
CI/CD
```

Make the `Currently Learning` status visually distinct with a small animated pulse or progress-style indicator. Do not show fake percentage levels.

## 10. Projects section

Section eyebrow:

```text
03 / FEATURED PROJECTS
```

Section heading:

```text
Selected projects and technical decisions.
```

Show two large project case-study cards. Project information is more important than decorative images.

Each project card must contain:

- Project number.
- Project type.
- Project title.
- Short business problem.
- Architecture line.
- 4–6 technical highlights.
- Tech-stack pills.
- Buttons for GitHub, Live Demo, and View Details.
- A dashboard or application screenshot placeholder.

### Project 01 — Employee Management System

Use this exact content:

```text
01 / FULL-STACK WEB APPLICATION

Employee Management System

A role-based employee management platform that supports employee records, departments, positions, monthly attendance, leave requests, payroll calculation, and account management.

Architecture
React → REST API → Spring Boot → PostgreSQL

Key highlights
• JWT authentication and role-based authorization
• Employee, department, and position management
• Monthly attendance import from Excel
• Leave request approval workflow
• Monthly payroll calculation
• Protected routes for Admin and Employee roles

Tech Stack
Java · Spring Boot · Spring Security · JPA · PostgreSQL · React · JWT · Apache POI

[Live Demo] [GitHub] [View Case Study]
```

For the screenshot area use:

```text
[EMPLOYEE MANAGEMENT DASHBOARD SCREENSHOT PLACEHOLDER]
```

### Project 02 — Library Management System

Use this exact content:

```text
02 / FULL-STACK WEB APPLICATION

Library Management System

A full-stack library application for managing books, authors, categories, users, borrow records, book availability, returns, overdue records, and notifications.

Architecture
React → REST API → Spring Boot → PostgreSQL

Key highlights
• JWT authentication with stateless Spring Security
• Admin and User role-based access control
• Book borrowing and return business logic
• Automatic book availability updates
• Overdue record processing
• Validation and relational database modeling

Tech Stack
Java · Spring Boot · Spring Security · Spring Data JPA · PostgreSQL · React · JWT

[Live Demo] [GitHub] [View Case Study]
```

For the screenshot area use:

```text
[LIBRARY MANAGEMENT DASHBOARD SCREENSHOT PLACEHOLDER]
```

### Project card behavior

- On desktop, alternate screenshot and text alignment between project 01 and project 02.
- On mobile, show the screenshot first, then the project information.
- On hover, raise the card by only 3–5px and brighten the border slightly.
- `View Case Study` may open a modal or expand the card.
- Do not invent repository links, live-demo links, performance metrics, users, downloads, or test coverage.

## 11. Project case-study modal / expandable panel

When `View Case Study` is selected, show a clean overlay or expandable section containing:

```text
Overview
The problem the application solves and the main user roles.

My contribution
Requirements analysis, database design, backend API development, authentication, business logic, and frontend integration.

Technical challenges
Designing entity relationships, implementing role-based access, validating business rules, and keeping application state consistent.

What I learned
Layered architecture, RESTful API design, Spring Security, relational database modeling, debugging, and full-stack integration.
```

Use accurate high-level statements only. Do not add fabricated achievements or production-scale claims.

## 12. Education and achievements section

Section eyebrow:

```text
04 / EDUCATION & ACHIEVEMENTS
```

Section heading:

```text
Academic background and milestones.
```

Create a two-column Bento layout.

### Education card

```text
Hanoi University of Science and Technology

Computer Science
School of Information and Communication Technology

Relevant areas
Object-Oriented Programming · Database · Computer Networks · Software Engineering · System Analysis and Design · Information Security
```

Do not display a graduation year, GPA, or exact academic year unless it is later provided.

### Achievements card

```text
ACHIEVEMENTS

Outstanding Student 2024–2025
Hanoi University of Science and Technology

Excellent Academic Encouragement Scholarship
2024, 2025 · Hanoi University of Science and Technology

Second Prize in Provincial Mathematics Competition
2023
```

### Certificates card

```text
CERTIFICATES

Google Data Analytics
Coursera

Google AI Essentials
Coursera

VSTEP B1 English Certificate
```

Use simple timeline lines, badges, or academic icons. Avoid trophy illustrations that look childish.

## 13. Contact section

Create one prominent full-width Bento card near the bottom.

Use this content:

```text
05 / CONTACT

Let's build something meaningful together.

I am currently looking for Java Backend Intern and Fresher opportunities in Hanoi. If you have a suitable role or would like to discuss one of my projects, feel free to contact me.

[Send an Email] [LinkedIn] [GitHub]
```

Add a compact contact information group:

```text
Email
[YOUR EMAIL]

Location
Hanoi, Vietnam

Website
9hdzprovip.bbroot.com
```

The email button must use a `mailto:` link after the real email is supplied.

Add a copy-email icon with a small `Copied!` toast interaction.

## 14. Footer

Use a minimal footer:

```text
© 2026 Le Duc Chinh. Built with React and Vite.

Designed for clarity. Built for growth.
```

Add a small back-to-top button.

## 15. Interaction and animation

Animations must feel smooth and restrained:

- Fade and translate sections upward slightly when entering the viewport.
- Stagger Bento cards by 50–100ms.
- Use smooth anchor scrolling.
- Add a subtle glow following the cursor only on desktop, if it does not reduce performance.
- Use button and card transitions between 180–250ms.
- Respect `prefers-reduced-motion`.
- Avoid long loading animations.
- Avoid typing animations that repeatedly delete and rewrite the job title.
- Avoid parallax that makes text difficult to read.

## 16. Responsive behavior

### Desktop — 1200px and above

- Use full Bento Grid layout.
- Hero introduction card spans about 8 columns.
- Supporting cards span about 4 columns.
- Project cards use spacious two-column layouts.

### Tablet — 768px to 1199px

- Reduce the grid to 2 columns.
- Keep primary content larger than secondary cards.
- Ensure navigation still fits or changes to a hamburger menu when needed.

### Mobile — below 768px

- Use one column.
- Hero name should be approximately 42–50px and must not overflow.
- Stack CTAs vertically or wrap them cleanly.
- Turn navigation into a hamburger drawer.
- Make all buttons at least 44px high.
- Ensure cards never create horizontal scrolling.
- Keep project details readable without requiring hover.

## 17. Accessibility and usability

- Use semantic sections and heading order.
- Ensure sufficient color contrast.
- Include visible keyboard focus styles.
- Every icon-only button needs an accessible label.
- Use meaningful alt text for the real profile and project images.
- Do not rely only on color to communicate status.
- Keep touch targets large enough on mobile.
- Make modals keyboard accessible and closable using Escape.

## 18. Components Stitch should generate

Create reusable components for:

- Navbar
- HeroBento
- StatusBadge
- BentoCard
- SectionHeading
- SkillGroup
- TechTag
- ProjectCard
- ProjectCaseStudy
- EducationCard
- AchievementCard
- ContactCard
- SocialLinks
- Footer

Maintain consistent card, tag, button, and spacing styles across the entire design.

## 19. Placeholder links and assets

Use obvious placeholders and never invent real URLs:

```text
[PROFILE_PHOTO_URL]
[CV_FILE_URL]
[EMAIL_ADDRESS]
[GITHUB_PROFILE_URL]
[LINKEDIN_PROFILE_URL]
[EMPLOYEE_MANAGEMENT_GITHUB_URL]
[EMPLOYEE_MANAGEMENT_DEMO_URL]
[EMPLOYEE_MANAGEMENT_SCREENSHOT_URL]
[LIBRARY_MANAGEMENT_GITHUB_URL]
[LIBRARY_MANAGEMENT_DEMO_URL]
[LIBRARY_MANAGEMENT_SCREENSHOT_URL]
```

All external links must open in a new tab with safe link attributes.

## 20. Final quality requirements

- Generate the complete website, not only the hero section.
- Keep all sections visually connected through one design system.
- The final result must look credible for a Java Backend Intern / Fresher application.
- Prioritize recruiter readability and project depth.
- Do not invent experience, statistics, companies, GPA, testimonials, repository URLs, or awards.
- Do not add a blog, pricing section, services section, customer logos, newsletter, or testimonials.
- Do not use lorem ipsum.
- Do not repeat the same introduction in multiple sections.
- Make the final screen ready to export and continue developing in React + Vite using VS Code.

## 21. Expected output from Stitch

Generate responsive UI screens for:

1. Full desktop homepage.
2. Tablet layout.
3. Mobile homepage with hamburger navigation.
4. Open project case-study modal or expanded state.

Use clean reusable components and preserve all exact text above. The desktop homepage is the primary screen.
