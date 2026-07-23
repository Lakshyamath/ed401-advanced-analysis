# ED 401 — Advanced Analysis course site

A responsive, accessible, single-page course portal built for GitHub Pages. It is inspired by the clear course-hub pattern of UC Berkeley Statistics 153, while using original content and design for ED 401.

## Best deployment pattern

**GitHub Pages + Google Classroom** is recommended:
- GitHub Pages hosts the polished public course profile, readings, schedule, and downloadable materials.
- Google Classroom handles enrolled-student announcements, submissions, grades, and private interaction.
- Add the published GitHub Pages URL as a permanent item in the Classroom “Classwork” page.

## Publish on GitHub Pages

1. Create a new public repository, for example `ed401-advanced-analysis`.
2. Upload `index.html`, `.nojekyll`, and this `README.md` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then save.
5. GitHub will provide a URL like `https://USERNAME.github.io/ed401-advanced-analysis/`.

## Preview locally

Open `index.html` directly, or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customize before publication

- Add official semester/year, room, class times, office hours, and email.
- Replace schedule entries if the institutional academic calendar differs.
- Add links for syllabus PDFs, lecture notes, assignments, Google Classroom, and GitHub source.
- If using an official BIT Mesra logo, add only an institution-approved asset and follow applicable brand rules.

## Interactive features

- Search and module filter for the weekly schedule
- Per-week completion tracking saved in the browser
- Course-progress bar
- Interactive module tabs
- Dark mode saved in the browser
- MathJax support for mathematical notation
- Print-friendly course profile
- Responsive and keyboard-friendly layout

## Content basis

The supplied ED 401 course document determined course identity, credits, objectives/outcomes, five modules, books, and assessment. The overall information architecture takes inspiration from the UC Berkeley Statistics 153 course hub (Fall 2024), without copying its visual design.
