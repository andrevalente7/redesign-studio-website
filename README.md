# ReDesign Studio Website

Premium one-page website for ReDesign Studio, an outsourced marketing team and AI systems partner for growing businesses.

## Status

Production-ready static website. Deployment has not been configured yet.

## Stack

- Static HTML
- CSS
- No build step required
- No JavaScript framework

## Preview

From the project root, run:

```bash
python3 -m http.server 4176 --directory Source
```

Then open:

```text
http://127.0.0.1:4176/Pages/index.html
```

## Project Structure

```text
Archive/
Context/
Copy/
Inspiration/
Source/
  Pages/
  Public/
  Styles/
Visual Assets/
README.md
TODO.md
index.html
```

## Folder Guide

- `Archive/` stores deprecated or replaced material.
- `Context/` stores project strategy, audience, offer, brand and design notes.
- `Copy/` stores page and section copy.
- `Inspiration/` stores UI references and inspiration.
- `Source/` stores the live website implementation.
- `Source/Pages/` contains page HTML.
- `Source/Public/` contains public assets used by the website.
- `Source/Styles/` contains CSS.
- `Visual Assets/` stores project-specific media and visual resources.

## Main Files

- `Source/Pages/index.html`
- `Source/Styles/styles.css`
- `Source/Styles/design-system.css`
- `Source/Public/assets/favicon.svg`

## Notes

- Keep the Agency OS structure intact.
- Do not deploy from this repository until deployment is explicitly approved.
- Use `http://127.0.0.1` for local preview instead of opening files directly.
