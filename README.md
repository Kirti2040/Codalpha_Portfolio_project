# Kirti Pandey: Portfolio Site

A personal portfolio built with plain HTML, CSS and JavaScript. No frameworks, no build step.

## Sections

- **Home**: large name, short intro and a scrolling skills ticker
- **About**: who I am, course and focus
- **Skills**: Front-end, Back-end and Tools
- **Projects**: Image Gallery, Calculator, Portfolio Website
- **Certificates**: four cards for your courses and certificates (edit the text in `index.html`)
- **Resume**: summary on the page and a downloadable PDF
- **Contact**: email with a "Copy email" button

## Features

- Clean, responsive layout (phone, tablet, desktop)
- Smooth scrolling between sections, with the current section highlighted in the menu
- Animations: page-load entrance, sections that fade in on scroll, scrolling ticker
- Hover effects on cards, skill chips, buttons and the name
- Dark and light theme that follows the device, with a toggle that remembers the choice
- Accessible: skip link, keyboard focus styles, reduced-motion support

## Project structure

```
portfolio-project/
├── index.html    # page content
├── style.css     # layout, theme, animations
├── script.js     # theme toggle, active menu link, copy email
├── resume.pdf    # one-page resume (download button)
└── README.md
```

## Run locally

Keep all files in one folder and open `index.html` in a browser. Fonts load from Google Fonts, so the first load needs internet.

## Edit your content

- **Text, projects, skills**: edit `index.html`. Each project is one `<article class="proj">` block. Copy a block to add another.
- **Colors**: change the values at the top of `style.css` (`--accent` is the main color).
- **Resume**: replace `resume.pdf` with your own file and keep the same name.
- **Certificates**: in the `Certificates` section, change the title, issuer and year inside each `<article class="card cert">`. Copy a block to add more.
- **Project links**: each project has a Live demo and a GitHub button. Replace `YOUR-USERNAME` (and the repo name if different) with your real GitHub username in `index.html`.
- **Social links** (GitHub, LinkedIn): add them in the Contact section next to the email.

## Deploy (bonus)

### GitHub Pages

1. Create a new repository on GitHub (for example `portfolio`).
2. Upload all files from this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute the site is live at `https://<your-username>.github.io/portfolio/`.

### Netlify

1. Go to [netlify.com](https://www.netlify.com) and sign in.
2. Choose **Add new site → Deploy manually**.
3. Drag the whole `portfolio-project` folder onto the page.
4. Netlify gives you a live link right away. You can rename it in **Site settings → Change site name**.

## Contact

kp032707@gmail.com
