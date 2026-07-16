# Frontend 3D Landing Page - Lifebuoy Concept

## Overview
This is a high-impact, brutalist-inspired landing page built to fulfill the frontend assignment requirements. It integrates custom Three.js 3D rendering and GSAP scroll animations within a WordPress + Elementor environment.

## WordPress + Elementor Integration
To maintain absolute control over the high-performance WebGL canvas and GSAP animations while fulfilling the WordPress requirement, this project was injected into Elementor using the Custom HTML widget on an "Elementor Canvas" page layout. 

## Features
* **Interactive 3D Product:** Built with Three.js. The bottle follows cursor movement on desktop and touch gestures on mobile.
* **GSAP ScrollTrigger:** The 3D model performs a seamless 360-degree rotation tied to the user's scroll depth.
* **Responsive Design:** Custom media queries ensure the layout gracefully degrades from a complex technical diagram on desktop to a clean, stacked layout on mobile (down to 320px).
* **Auto-Scaling Geometry:** The Three.js camera dynamically resizes the 3D model based on viewport width to prevent overflow on mobile devices.