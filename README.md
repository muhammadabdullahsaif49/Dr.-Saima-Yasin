# Dr. Saima Yasin — Personal Website

A responsive personal/consultancy website for Dr. Saima Yasin, covering her
profile, engineering consultancy services, teaching & guidance, and women
empowerment work.

## Tech Stack
- HTML5
- CSS3 (custom styles in `style.css`)
- [Bootstrap 5.3.7](https://getbootstrap.com/) (bundled in `lib/`)
- [Font Awesome 7](https://fontawesome.com/) (via CDN)
- Google Fonts — Lora

## Project Structure
```
.
├── index.html          # Main page
├── style.css            # Custom styles
├── lib/
│   └── bootstrap-5.3.7-dist/   # Bootstrap CSS & JS
├── pic-1.png ... pic-8.png     # Section images
├── logo-1.png ... logo-4.png   # Feature card icons
├── BG_1.png, BG_2.png          # Section background images
└── README.md
```

## Running Locally
No build step required — it's a static site.

```bash
git clone https://github.com/<your-username>/dr-saima-yasin-website.git
cd dr-saima-yasin-website
# then just open index.html in your browser, or serve it:
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying with GitHub Pages
1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Branch**, select `main` and folder `/ (root)`.
4. Save — your site will be live at:
   `https://<your-username>.github.io/dr-saima-yasin-website/`

## License
MIT — free to use and modify.
