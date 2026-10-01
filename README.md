# Javani Research Lab — GitHub Pages / Jekyll

This package contains the complete Jekyll site for javani.org. It includes the People page, Mohammad Javani's portrait from javani.org, and direct Google Scholar publication links. The student name is Abias Dotson.

## Put it on your existing domain

1. Extract this ZIP. Copy its contents (including the layouts folder, configuration, CNAME, the five HTML pages, and assets) into the root of the existing mjavani54/javani-lab-webpage repository.
2. Replace the previous website pages and assets rather than leaving competing old index or route files in the repository. If using Git locally, preserve the repository's .git directory.
3. Commit and push to your publishing branch. In GitHub repository Settings → Pages, use deployment from the branch and / (root) folder.
4. Keep javani.org configured as the custom domain. This package already contains CNAME; it does not require mail or MX records.

The site uses Jekyll front matter and one shared layout. Navigation and assets use Jekyll's relative_url filter. The Gemfile supports local preview with bundle install and bundle exec jekyll serve, if Ruby/Bundler are installed.

## Editing

- Page copy: index.html, research.html, people.html, publications.html, about.html
- Shared navigation, header, footer, and metadata: _layouts/default.html
- Styling: assets/site.css
- Portrait: assets/mohammad-javani.webp
- Hero image: assets/hero-visual.webp

The People page uses a typographic profile for Abias because no student portrait was supplied.
