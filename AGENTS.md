
## Project

This repository is for Denes Vaghani’s personal portfolio website.

The website should be a GitHub Pages hostable portfolio built with React, Vite, TypeScript, Tailwind CSS, Framer Motion, and React Three Fiber / Three.js.

## Core Concept

The portfolio is called **The Ascent**.

It should feel like a cinematic scroll-based journey. A small 3D character walks along a glowing path and climbs stairs upward as the user scrolls through sections. Each section represents a career checkpoint.

The visual metaphor is:

> Building systems, climbing complexity, shipping clarity.

## Owner Profile

Name: Denes Vaghani
Headline: Senior Product Engineer & System Thinker

Denes builds scalable backend systems, data pipelines, cloud infrastructure, and product-focused engineering solutions.

Professional themes:

* Backend engineering
* Product thinking
* Systems thinking
* Data pipelines
* Search systems
* AWS cloud infrastructure
* Client-focused problem solving
* Documentation and clean execution

## Tech Stack

Use:

* React
* Vite
* TypeScript
* Tailwind CSS
* Framer Motion
* React Three Fiber
* Three.js
* Optional: Drei, only if useful
* GitHub Actions
* GitHub Pages

Do not use:

* Paid 3D assets
* Heavy animation libraries unless necessary
* Backend/server code
* Complex CMS
* Database
* Contact form backend

## Design Direction

The design should feel:

* Premium
* Dark
* Cinematic
* Sharp
* Modern
* Practical
* Slightly poetic
* Senior-engineer level, not student-template level

Visual ideas:

* Starry dark background
* Mountain/stair/path metaphor
* Glassmorphism cards
* Purple/blue gradient accents
* Warm lantern/glow lights along the path
* Character walking upward
* Content cards placed as checkpoints
* Smooth scroll transitions

Avoid:

* Generic particle spam
* Too many rotating objects
* Overloaded 3D scene
* Neon chaos
* Cartoonish childish design
* Broken external assets

## Sections

The site must include:

1. Hero

   * Name: Denes Vaghani
   * Subtitle: Senior Product Engineer & System Thinker
   * Tagline: Building systems, climbing complexity, shipping clarity.
   * Buttons: View Projects, Contact Me

2. About

   * Explain that Denes builds scalable systems, backend platforms, data pipelines, and product-focused engineering solutions.
   * Mention turning messy technical problems into clean, usable systems.

3. Experience

   * Senior Product Engineer / Senior Member of Technical Staff at SentiSum
   * Backend and data pipeline work
   * Java, Spring Boot, Python, AWS, Kafka, Elasticsearch
   * Production systems, client requests, scalability, documentation, refactoring

4. Projects
   Include these project cards:

   * Elasticsearch 7 to 8 Migration
   * Kafka / Data Pipeline Scalability
   * AWS-based S3 / ECS / Airflow Pipeline
   * Jira to Zoho Integration or Product Workflow Automation

   Each project card should include:

   * Problem
   * What I built
   * Tech stack
   * Impact

5. Skills
   Skill groups:

   * Backend: Java, Spring Boot, Python, Django, REST APIs
   * Cloud & DevOps: AWS, ECS, S3, CloudWatch, GitHub Actions
   * Data & Search: Kafka, Elasticsearch, PostgreSQL
   * Frontend: React, JavaScript, TypeScript, Tailwind CSS
   * Product: requirements, client communication, documentation, systems thinking

6. Writing / Thinking

   * Show that Denes writes and thinks about engineering, product, productivity, and life systems.
   * This section can look like a floating notebook or idea board.

7. Contact

   * Email placeholder
   * LinkedIn placeholder
   * GitHub placeholder
   * Use mailto link, no backend form.

## 3D Requirements

Desktop:

* Show full scroll-controlled 3D scene.
* Character should walk from section to section.
* Character should pause near each checkpoint.
* Path/stairs should visually move upward.
* Camera should gently follow the character.
* 3D should be lightweight and performant.

Mobile:

* Use simplified 3D or CSS/SVG fallback.
* Do not make mobile performance suffer.

Performance:

* Keep assets small.
* Lazy load 3D where possible.
* Add loading state.
* Avoid large external models unless optimized.
* `npm run build` must succeed.

## Engineering Requirements

The project must:

* Build successfully with `npm run build`
* Run locally with `npm run dev`
* Deploy to GitHub Pages using GitHub Actions
* Include a clear README.md
* Include accessible semantic HTML where possible
* Avoid console errors
* Be responsive
* Use clean component structure

## Expected Structure

Prefer this structure:

```text
src/
  components/
    layout/
    sections/
    three/
    ui/
  data/
  hooks/
  styles/
  App.tsx
  main.tsx
public/
.github/
  workflows/
    deploy.yml
```

## Verification

Before finalizing work:

* Run install if needed
* Run build
* Fix TypeScript errors
* Fix missing imports
* Check responsive layout
* Confirm GitHub Pages deployment setup
* Update README.md with setup and deployment steps

## Tone

The copy should sound confident, clean, and human.

No fake bragging.
No corporate soup.
No empty buzzwords.

Preferred style:

* Sharp
* Practical
* Memorable
* Slightly poetic

Example tone:
“I build systems that turn messy data, fragile workflows, and vague product needs into clean, reliable software.”
