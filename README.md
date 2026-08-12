# Barely Comics Website

A clean, simple, static website for your comics and articles.

## What's included
- `index.html` — Home page (latest comic + recent grid)
- `comics.html` — Grid of all comic thumbnails
- `articles.html` — Grid of articles
- `about.html` — About page
- `css/style.css` — All the styling (easy on the eyes + a little personality)

## How to put it on GitHub Pages (free hosting)

1. Create a new repository on GitHub (public).
   - Name it something like `barely-comics` or `yourusername.github.io`
2. Upload all the files and folders from this project into the repository.
3. Go to **Settings → Pages**.
4. Under "Source", choose the `main` branch and `/ (root)`.
5. Click Save. In a minute or two your site will be live at:
   `https://yourusername.github.io/repository-name/`

## How to add your real comics

1. Put your comic images in the `images/` folder.
2. Open `comics.html` (and `index.html` for the featured one).
3. Replace the placeholder `<img src="...">` with your real file, for example:
   ```html
   <img src="images/comic-01.jpg" alt="Comic title">
   ```
4. Update the title and date text.

Same idea for articles.

## Customizing colors

Open `css/style.css` and change the values near the top under `:root { ... }`.

Enjoy. Your content will do the talking.