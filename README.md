# task1_web
# Simple Responsive Landing Page

A minimal, responsive landing page built with **pure HTML & CSS**. Clean, modern, and easy to customize — perfect for beginners or as a quick project starter.

## Demo

Open `index.html` in your browser (or deploy with GitHub Pages) to see the page.

## Features

* Responsive layout with a hero section
* Mobile-friendly typography and navigation
* Simple, easily-customizable styles
* No JavaScript required

## File Structure

```
/simple-landing-page
├─ index.html
├─ README.md
└─ assets/
   └─ (images, fonts, etc.)
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open `index.html` in your browser:

   * Double-click the file, or
   * `open index.html` (macOS) / `start index.html` (Windows)

## Code Snippet (example)

The repository contains a simple `index.html` and internal CSS. Example hero markup:

```html
<section class="hero">
  <h2>Build Something Amazing</h2>
  <p>A simple responsive landing page built using pure HTML & CSS. Clean, modern, and easy to customize for beginners.</p>
  <a href="#" class="btn">Get Started</a>
</section>
```

## Customize

* Change colors: edit the `.btn` background and `:hover` styles.
* Update typography: change the `font-size` values in `.hero h2` and `.hero p`.
* Add assets: place images in `assets/` and reference them in HTML or CSS.

### Responsive tips

* The project includes a basic media query for screens `max-width: 768px`. Tweak breakpoints and font sizes to match your needs.
* For more complex responsive layouts consider using CSS Grid or Flexbox for header and hero alignment.

## Deploy to GitHub Pages

1. Push your repo to GitHub.
2. In repo settings → Pages, choose the `main` branch and `/ (root)` and save.
3. Your page will be available at `https://your-username.github.io/your-repo-name/`.

## Contributing

Feel free to:

* Improve accessibility (ARIA attributes, better contrast)
* Add a nav toggle for mobile with JS
* Replace internal CSS with an external stylesheet

## License

MIT License — feel free to use and modify.

