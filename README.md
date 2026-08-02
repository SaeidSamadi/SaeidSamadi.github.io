# Saeid Samadi — Personal Portfolio

Static GitHub Pages portfolio for [saeidsamadi.github.io](https://saeidsamadi.github.io).

## Structure

- `index.html` — profile and selected impact
- `education.html` — professional experience and education
- `projects.html` and `projects/` — selected robotics case studies
- `publications.html` — selected research record
- `insights.html` — technical expertise, tools, and recognition
- `assets/css/portfolio.css` — portfolio-specific styles layered over the HTML5 UP base theme
- `static/Saeid_Samadi_CV.pdf` — current downloadable CV

## Local preview

Run a static server from the repository root:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Updating the CV

`static/cv.html` is the editable, print-ready source. Open it in a browser and print to PDF at `static/Saeid_Samadi_CV.pdf` after content changes.

## Deployment

The site deploys directly from the repository's default branch through GitHub Pages. No build step is required.
