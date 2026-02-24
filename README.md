# Rainier S. Juson III — Portfolio

A high-fidelity, cinematic personal portfolio landing page designed for Rainier S. Juson III, a Hospitality Operations Manager and Cruise Hospitality Supervisor. 

**Live Demo:** [https://ranier.pages.dev](https://ranier.pages.dev)

## Overview

This project is a bespoke, single-file static website built with a "Dark Mode First × Art Deco Influence × Corporate Luxury" aesthetic. The design aims to capture the emotional tone of quiet authority, resembling the experience of entering a five-star hotel lobby.

It features mechanical scroll transitions, organic parallax effects, custom SVG iconography, and a responsive layout tailored to showcase Rainier's competencies, experience, certifications, and education.

## Technical Stack

*   **HTML5**
*   **CSS3** (Inline, Custom Properties, Fluid Typography via `clamp()`)
*   **JavaScript (Vanilla)**
*   **GSAP (GreenSock Animation Platform)** + ScrollTrigger
*   **Lenis** (Smooth scrolling)
*   **Google Fonts** (Cormorant Garamond, Montserrat, IBM Plex Mono)

## Features

*   **Performance First:** The entire website is encapsulated within a single `index.html` file, with all CSS and JavaScript inlined to minimize HTTP requests.
*   **Smooth Scrolling:** Integrated Lenis for a buttery-smooth scrolling experience that enhances the cinematic feel.
*   **Scroll-Triggered Animations:** GSAP ScrollTrigger is used for intentional, weighted element reveals as the user scrolls down the page.
*   **Responsive Design:** Fully fluid layout using CSS variables and `clamp()` for typography, ensuring pixel-perfect rendering across mobile, tablet, and desktop devices.
*   **Offline/No-JS Graceful Degradation:** Core content remains accessible even if JavaScript fails or is disabled.
*   **Reduced Motion Support:** Respects the OS-level `prefers-reduced-motion` settings, wrapping animations in a GSAP `matchMedia` query.
*   **Custom Assets:** Hand-coded SVG icons and a custom-designed structural logo.

## Deployment

This website is statically generated and hosted on **Cloudflare Pages**. Since the project consists solely of static assets (`index.html` and an `assets/` folder), no build step is required. 

To run locally, simply open the `index.html` file in any modern web browser.
