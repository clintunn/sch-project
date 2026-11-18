# sch-project

Static website for the Department of Cybersecurity at Chrisland University (Abeokuta). It covers the department history, vision and mission, faculty, curriculum, gallery, and a contact section. The contact form posts to `forms/contact.php`.

A closely related copy of the same site is in [cyb-cmu](https://github.com/clintunn/cyb-cmu). The GitHub Pages HTML is in [clintunn.github.io](https://github.com/clintunn/clintunn.github.io).

Live site (from the repository homepage): [cyb-cmu.vercel.app](https://cyb-cmu.vercel.app)

## Tech stack

- HTML, CSS, and JavaScript
- Bootstrap, Bootstrap Icons, and Boxicons
- AOS, GLightbox, Isotope, and PureCounter
- PHP email form helper under `forms/`

## Run locally

For the static pages, open `index.html` or serve the repo root:

```bash
python3 -m http.server 8080
```

Then visit `http://127.0.0.1:8080`. To exercise `forms/contact.php`, serve the folder with PHP (for example `php -S 127.0.0.1:8080`).

## Project structure

```
index.html
inner-page.html
portfolio-details.html
css/style.css
js/main.js
img/                 # department, team, and gallery images
forms/contact.php
vendor/              # Bootstrap and other front-end libraries
```

Built by Clinton Nkamigbo · https://clinton-nkamigbo.vercel.app
