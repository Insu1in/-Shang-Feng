# GEMINI.md - Project Context: 上楓汽車 (Shang Feng Auto) Website

This document provides essential context and instructions for the "上楓汽車" (Shang Feng Auto) web project.

## Project Overview
A professional, single-page marketing website for a car repair and maintenance shop located in Taichung. The project aims to showcase services, advantages, and contact information with a focus on trust and professional service.

### Key Technologies
- **Frontend:** Vanilla HTML5, CSS3 (using CSS Variables), and basic JavaScript.
- **Data Management:** `data.json` stores the structured content for the website.
- **Design Style:** Modern, clean, and mobile-responsive using a Deep Blue (`#1A365D`) and Red (`#E53E3E`) color scheme.

## Directory Structure
- `index.html`: The main entry point and single-page application structure.
- `data.json`: Structured content used for the website sections (Hero, About, Services, Advantages, Contact).
- `optimized_copy.txt`: Optimized marketing copy and design suggestions.
- `test1.txt`: A concise version of the website copy.

## Building and Running
Since this is a static website:
- **Running:** Open `index.html` directly in any modern web browser.
- **Development:** No build step is required. Changes to `index.html` are reflected upon refreshing the browser.
- **TODO:** If the project grows, consider implementing a simple script to inject `data.json` content into `index.html` dynamically, as it is currently hardcoded in the HTML.

## Development Conventions
- **Styling:** Prefer Vanilla CSS. Use CSS variables defined in `:root` for consistency.
- **Interactivity:** Use minimal, dependency-free JavaScript (e.g., for smooth scrolling).
- **Content Updates:** When updating website text, ensure consistency between `data.json`, `index.html`, and the reference text files.
- **Images:** Currently uses SVG placeholders for background images to remain dependency-free. Replace with real assets when available.
