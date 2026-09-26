# javani.org — Jekyll / GitHub Pages package

This package is ready to replace the contents of the `mjavani54/javani-lab-webpage` GitHub repository.

## 1. Add your portrait

Place your photo at:

`assets/images/mohammad-javani.jpg`

Use that exact filename unless you also update the path in `index.md`.

## 2. Optional: add your CV PDF

Place your current CV PDF at:

`assets/Javani_CV.pdf`

The CV page already links to that location.

## 3. Upload to GitHub

Replace the existing repository contents with the contents of this package and commit to the branch GitHub Pages uses, normally `main`.

The repository root should contain files such as:

- `_config.yml`
- `CNAME`
- `index.md`
- `404.md`
- `_layouts/`
- `_includes/`
- `assets/`
- `research/`
- `publications/`
- `teaching/`
- `students/`
- `cv/`
- `contact/`

Do not upload the outer `javani-jekyll-site` folder as an extra nesting level. Upload its contents to the repository root.

## 4. GitHub Pages settings

In GitHub:

`Repository → Settings → Pages`

Recommended settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`
- Custom domain: `javani.org`
- Enforce HTTPS: enabled after DNS validation succeeds

## 5. Squarespace DNS

The expected GitHub Pages records are:

- A `@` → `185.199.108.153`
- A `@` → `185.199.109.153`
- A `@` → `185.199.110.153`
- A `@` → `185.199.111.153`
- CNAME `www` → `mjavani54.github.io`

The included `CNAME` file contains `javani.org`.

## 6. Local preview (optional)

If Ruby and Bundler are installed:

```bash
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Important content notes

- The publications page intentionally contains only a confirmed selected publication and broad descriptions of current projects. Add accepted/published papers as appropriate.
- The CV download button will return a missing-file error until `assets/Javani_CV.pdf` is added.
- The homepage image will be blank/broken until `assets/images/mohammad-javani.jpg` is added.
