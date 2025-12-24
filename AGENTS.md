# Agent Instructions for lichsu-ghk1-25-26

## Project Overview
Static HTML educational quiz app for Vietnamese high school students (History & Math).
- No build process, no package manager
- Pure HTML/CSS/JavaScript (vanilla)
- Content: Vietnamese language study materials

## Structure
- `/` - Root index.html (history quiz)
- `/math/` - Math study materials  
- `/word/` - Additional study materials
- `/data/` - Image assets for quizzes

## Testing
Open HTML files directly in browser. No unit tests or build commands.

## Code Style
- Vietnamese content and comments preferred
- Inline `<style>` and `<script>` tags (single-file components)
- CSS: CSS custom properties for theming, BEM-like class naming
- JS: Vanilla ES6+, no frameworks
- Responsive design with mobile-first approach

## Conventions
- MathJax for LaTeX math rendering (`\( \)` inline, `\[ \]` block)
- Image paths: Use `data/` folder or external GitHub Pages URLs
- Quiz data: Stored as JS objects in `<script>` blocks
- Print-friendly CSS with `@media print` rules
