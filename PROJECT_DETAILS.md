# Current Portfolio Project Details

This document describes the current state of Paban Bhandari's personal portfolio website so another AI assistant or developer can understand the project without first reverse-engineering the code.

## Project Summary

This is a static personal portfolio website for Paban Bhandari, a Python developer from Kathmandu, Nepal.

The current positioning is honest and learning-focused:

- Paban is a Python developer.
- He has basic to intermediate Django knowledge.
- He is actively learning Django.
- He is focused on becoming a full-stack web developer using Python and Django.
- He knows frontend development with HTML, CSS, JavaScript, and Tailwind CSS.
- The website is a simple showcase of projects, skills, and contact information.

The site is built with plain HTML, CSS, JavaScript, Bootstrap, Bootstrap Icons, EmailJS, particles.js, and Google Fonts. Bootstrap is used by the website layout, but the personal skill messaging emphasizes HTML, CSS, JavaScript, Tailwind CSS, Python, and Django.

## Main Files

- `index.html`: Main markup, content, SEO metadata, sections, Bootstrap layout, CDN imports, and portfolio content.
- `style.css`: Custom dark theme, layout styling, responsive rules, animations, buttons, project cards, contact form styling, loading screen, notifications, and floating UI styling.
- `script.js`: Client-side interactivity for loading screen, smooth scrolling, active nav updates, mobile nav closing, EmailJS contact form, project filtering, typing animation, particles.js setup, and notifications.
- `images/LOGO.png`: Logo used in the favicon, loading screen, and navbar.
- `images/profile-photo.jpg`: Profile photo used in the About section and social metadata.
- `cv.pdf`: CV linked from the navbar and About section.

## Current Developer Identity

The portfolio should communicate:

- Python is Paban's strongest area.
- Django is currently basic to intermediate, and he is actively learning it.
- He is building projects to improve backend structure, data handling, and web application development.
- He also works with frontend technologies: HTML, CSS, JavaScript, and Tailwind CSS.
- The tone should stay simple, honest, and professional.

Avoid exaggerating experience or presenting him as an advanced Django engineer.

## Current Tech Stack Shown On Site

The About section currently lists:

- Python
- Django
- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- Git

## External Dependencies

The website loads these dependencies from CDNs:

- Bootstrap 5.3 CSS
- Bootstrap 5.3 bundle JS
- Bootstrap Icons 1.10
- Google Fonts: Poppins and Montserrat
- EmailJS browser SDK: `emailjs-com@3`
- particles.js 2.0

Because these are CDN-loaded, internet access is needed for the full experience unless assets are downloaded and hosted locally.

## SEO And Structured Data

The site includes:

- `<title>Paban Bhandari | Portfolio</title>`
- Meta description focused on Python, Django learning, full-stack web projects, HTML, CSS, JavaScript, and Tailwind CSS.
- Open Graph metadata for social sharing.
- Twitter card metadata.
- Favicon from `images/LOGO.png`.
- JSON-LD `Person` schema.
- JSON-LD `WebSite` schema.

The `Person` schema currently uses:

- `jobTitle`: `Python Developer`
- `description`: `Python developer learning Django and building full-stack web projects with HTML, CSS, JavaScript, and Tailwind CSS`
- `addressLocality`: Kathmandu
- `addressCountry`: Nepal
- Links to LinkedIn, GitHub, and Instagram.
- Contact email and phone.

## Page Sections

### Loading Screen

The page starts with a full-screen loading overlay.

It contains:

- Logo image.
- Name: `Paban Bhandari`
- Text: `Preparing portfolio...`
- CSS spinner.

JavaScript hides the loading screen after window load. If the user prefers reduced motion, the delay is removed.

### Navbar

The navbar is fixed to the top and uses Bootstrap's responsive navbar behavior.

It contains:

- Logo.
- Brand text: `Paban Bhandari`
- Navigation links:
  - Home
  - About
  - Projects
  - Contact
  - CV

JavaScript handles smooth scrolling for internal nav links, active link updates, and closing the mobile menu after navigation.

### Hero Section

Current hero content:

- Kicker: `Python + Django Learner`
- Heading: `Hi, I'm Paban Bhandari`
- Summary: `I build web projects with Python, Django, and frontend technologies while improving my full-stack development skills.`
- Typing line starts with: `Focused on Python Development`
- Skill chips:
  - Python
  - Django
  - HTML
  - CSS
  - JavaScript
  - Tailwind CSS

Hero visual elements:

- Dark gradient background.
- particles.js animated background.
- Subtle yellow SVG wave background.
- Glass-style content panel.
- Yellow gradient name text.
- LinkedIn, GitHub, and Instagram social icons.
- Primary CTA: `View Projects`
- Secondary CTA: `Contact Me`

### About Section

Current About copy:

```text
I'm Paban Bhandari, a Python developer from Kathmandu, Nepal. I am focused on becoming a full-stack web developer using Python and Django.

Python is my strongest area, and I have basic to intermediate knowledge of Django. I am actively learning Django by building projects, understanding backend logic, working with data, and improving how I structure web applications.

I also work with frontend technologies including HTML, CSS, JavaScript, and Tailwind CSS. My goal is to keep building real projects, improve step by step, and become confident in both backend and frontend development.
```

The About section also includes:

- Profile photo with animated yellow glow and border.
- Download CV button.
- Tech stack badges.

### Projects Section

The Projects section is a responsive Bootstrap grid with filter buttons.

Section subtitle:

```text
Selected work showing backend logic, full-stack structure, and practical UI execution
```

Current filter buttons:

- All
- Full-Stack / Web
- Frontend
- Python
- Practice

Filter buttons use:

- `data-filter`
- `aria-pressed`
- JavaScript toggles active state and visibility of project cards.

### Current Projects

#### Portfolio Website

Categories:

- `frontend`
- `web`

Description:

```text
Static portfolio built with structured content, responsive Bootstrap layout, EmailJS contact handling, project filtering, SEO metadata, and production-ready deployment setup.
```

Tech tags:

- HTML
- CSS
- JavaScript
- Bootstrap

Links:

- Live demo: `https://pabanbhandari.com`
- GitHub repo: `https://github.com/Paban-Bhandari/Portfolio`

#### To-Do List

Categories:

- `python`
- `web`

Description:

```text
Django CRUD application with user authentication, session-based access, persistent task storage, and backend logic organized around practical user workflows.
```

Tech tags:

- Django
- Python
- JavaScript
- CSS

Link:

- GitHub repo: `https://github.com/Paban-Bhandari/todo_list`

#### Memory Game

Categories:

- `practice`

Description:

```text
Practice memory game project focused on matching logic, interaction flow, and building a simple interactive user experience.
```

Tags:

- Practice Project
- Game Logic

Link:

- GitHub repo: `https://github.com/Paban-Bhandari/Memory_Game`

### Contact Section

The Contact section includes:

- Heading: `Get In Touch`
- Subtitle: `Open to junior backend, full-stack, internship, and freelance Django opportunities`
- Contact form fields:
  - Full Name
  - Email Address
  - Subject
  - Message
- Submit button: `Send Message`

The form uses EmailJS, not a custom backend.

EmailJS configuration in `script.js`:

- Public key: `Jy04q4eVfNerskfqF`
- Service ID: `service_dwnmjzs`
- Template ID: `template_ds7q5ek`

Contact cards:

- Email: `bhandaripawan841@gmail.com`
- Location: `Kathmandu, Nepal`
- Phone: `+977-9848436507`

### Footer

The footer includes:

- Copyright text:
  - `© 2026 Paban Bhandari. All rights reserved.`
- Social links:
  - LinkedIn
  - GitHub
  - Instagram

### Floating UI

The site includes:

- Scroll progress bar at the top.
- Scroll-to-top floating button.
- Floating "Hire Me" button linked to the contact section.

## JavaScript Behavior

The JavaScript file currently handles:

- EmailJS initialization only if `emailjs` is available.
- Loading screen fade-out after window load.
- Reduced-motion-friendly loading delay.
- Scroll progress bar width calculation.
- Smooth scrolling for internal navbar links.
- Active navbar link updates based on scroll position.
- Mobile Bootstrap menu close after clicking a section nav link.
- Contact form submission through EmailJS.
- Contact form loading state: button changes to `Sending...`.
- Success notification after successful EmailJS submission.
- Error notification after failed EmailJS submission.
- Fallback error if EmailJS is unavailable.
- Project filtering by category classes.
- `aria-pressed` updates on filter buttons.
- Typing animation in the hero section.
- particles.js configuration for hero background.
- Notification creation and removal.

Typing animation roles:

- Python Development
- Django Learning
- Frontend Basics
- Building Projects
- Full-Stack Practice

## Styling System

The CSS uses a custom dark theme with CSS variables:

```css
:root {
    --bg-dark: #18191a;
    --bg-darker: #121314;
    --surface-dark: #232526;
    --surface-muted: #393e46;
    --accent: #ffd369;
    --accent-strong: #ffb347;
    --text-light: #f8f9fa;
    --text-muted: #c8c8c8;
}
```

Design characteristics:

- Dark theme.
- Gold/yellow accent color.
- Glass-style hero panel.
- Gradient text and buttons.
- Rounded buttons and project cards.
- Animated hero particles.
- Animated profile-photo glow.
- Hover effects on project cards, buttons, and social icons.
- Responsive Bootstrap grid.
- Mobile-specific hero spacing and project stacking.

## Accessibility And UX Details

Current accessibility/UX details include:

- `aria-label` on main navigation.
- `aria-label` on social links and project links.
- `aria-live="polite"` on typing text.
- `aria-pressed` on project filter buttons.
- `type="button"` on filter buttons.
- Focus-visible styles for links, buttons, and form controls.
- Reduced-motion-aware loading screen delay.
- Mobile navbar closes after selecting a nav item.
- Contact form has associated labels and required fields.

## Important Constraints For Future Edits

When improving this project, keep these constraints:

- Keep it a static HTML/CSS/JS portfolio.
- Do not convert it to Django unless explicitly requested.
- Keep Bootstrap and the current styling direction.
- Do not remove existing features:
  - Loading screen
  - particles.js
  - EmailJS contact form
  - project filtering
  - typing animation
  - scroll progress bar
  - floating contact/scroll buttons
- Do not introduce fake skills or fake project features.
- Keep the developer positioning honest: Python developer, learning Django, building toward full-stack web development.
- Keep frontend skills limited to the real stated set: HTML, CSS, JavaScript, Tailwind CSS.

## Short Claude Prompt

Use this if sending the project to Claude:

```text
This is my current static portfolio website. It is built with HTML, CSS, JavaScript, Bootstrap, Bootstrap Icons, Google Fonts, EmailJS, and particles.js. It positions me as Paban Bhandari, a Python developer from Kathmandu, Nepal who has basic to intermediate Django knowledge and is actively learning full-stack web development with Python and Django. I know frontend technologies including HTML, CSS, JavaScript, and Tailwind CSS. Keep the tone honest, simple, and professional. Keep it static, keep Bootstrap, do not remove existing features, and do not add fake technologies or exaggerated experience.
```
