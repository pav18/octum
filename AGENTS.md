# AGENTS.md - OCTUMsite Repository

## Project Overview
This is a static HTML website for OKTUM - a smart apartment protection service for short-term rentals in Moscow.

## Key Files
- `oktum.html` - Main website file containing HTML, CSS, and JavaScript

## Development Guidelines

### Editing
- All code (HTML, CSS, JS) is contained within the single `oktum.html` file
- Make changes directly to this file
- No build process required - changes are immediately visible

### Testing
- Open `oktum.html` in a web browser to view changes
- Test responsiveness using browser dev tools
- Check all interactive elements (nav links, form, buttons)

### Deployment
- Deploy by copying `oktum.html` to any static web server
- No dependencies or build steps needed

### Conventions
- CSS variables are defined in `:root` for easy theming
- Mobile-first responsive design with media query at 768px
- JavaScript handles navbar scroll effects, particles, reveal animations, and smooth scrolling
- Form uses client-side validation with alert on submit (no backend)

### Common Tasks
- Update text/content: Edit HTML elements directly
- Change styles: Modify CSS variables or rules in `<style>` section
- Adjust animations: Edit CSS animation properties or JS timing
- Modify form behavior: Edit JS in form submit handler or HTML inputs