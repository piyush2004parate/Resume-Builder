# Resume-Builder

A simple, responsive resume/CV builder that lets users fill in their details and generate a printable/resumable resume. This project is primarily built with CSS and HTML, with a small Python component for optional backend/export functionality.

Repository: https://github.com/piyush2004parate/Resume-Builder

## Features

- Clean, responsive resume layout designed with HTML and CSS
- Live preview of the resume as you fill in details (client-side)
- Print-friendly styles for PDF export using browser print or print-to-PDF
- Optional Python backend for advanced export (if present in the repo)

## Screenshots

Below are screenshots showing the app UI and a sample generated resume. The images for the screenshots live in the repository at `static/img`. If you prefer the images to live under a different path, update the `src` values below accordingly.

- Landing / Get Started view  
<img src="static/img/HomePage.png" alt="Landing page with Get Started button" width="100%">

- Landing / action buttons  
<img src="static/img/OnlineResumeGenerator.png" alt="Landing page with action buttons (Create / View / Edit / Download)" width="100%">

- Sections list with Edit / View / Delete actions  
<img src="static/img/EditResumePage.png" alt="Table listing profile sections with Edit, View and Delete buttons" width="80%">

- Generated resume / PDF preview  
<img src="static/img/Resume.png" alt="Generated resume PDF preview" width="65%">


## Tech stack

- CSS (primary) — styling and responsive layout
- HTML — structure and forms
- Python (optional) — backend utilities or export scripts

## Quick demo / Usage

There are two common ways to run the project locally:

1. Static preview (no server required)
   - Clone the repo:
     ```bash
     git clone https://github.com/piyush2004parate/Resume-Builder.git
     cd Resume-Builder
     ```
   - Open `index.html` in your browser to preview and use the builder.

2. Serve locally with a simple HTTP server (recommended for form POSTs or local fetch)
   - Python 3 (from the project root):
     ```bash
     python -m http.server 8000
     ```
   - Then open http://localhost:8000 in your browser.

3. Optional Python backend (if the repository contains a backend application)
   - If there is a backend folder or an `app.py` and a `requirements.txt`, install dependencies and run the app:
     ```bash
     python -m venv venv
     source venv/bin/activate   # Windows: venv\Scripts\activate
     pip install -r requirements.txt
     python app.py
     ```

## Issues & feature requests

Please use the repository’s Issues tab to report bugs or request new features. Provide steps to reproduce, expected vs. actual behavior, and relevant screenshots.

## License

If a LICENSE file is not included, consider adding one (MIT recommended for open source). Example header:

```
MIT License
Copyright (c) 2025 piyush2004parate
```

## Acknowledgements

Thanks for checking out Resume-Builder. If you have suggestions (UI improvements, templates, export features), open an issue or submit a PR.

Maintainers / Contact
- Owner: piyush2004parate
- Repo: https://github.com/piyush2004parate/Resume-Builder
