# CPIT-405 Lab 3

Student: Nawaf Baryan

## Preview

Open this folder in VS Code and choose **Open with Live Server** for `index.html`. You can also open the file directly in your browser.

## Publish

1. Create a public GitHub repository named `cpit-405-lab-3` under `N1W1F`.
2. Upload `index.html`, `styles.css`, and the `images` folder, preserving the paths.
3. Under **Settings > Pages**, choose **Deploy from a branch**, **main**, and **/(root)**, then save.
4. Wait for deployment and submit the URL shown by GitHub Pages. The expected URL after publication is `https://n1w1f.github.io/cpit-405-lab-3/`.

## Learn it later

- `.image-preview img` selects images inside the element with the `image-preview` class.
- `p > span` selects a direct child, making the quote's span red.
- `#header span` overrides the plain `span` rule because its ID gives it higher specificity. The first two words are pink.
- `#header *:last-child` has an ID and a pseudo-class, overriding `#header span`. The third word is orange.
- `#header span:first-child:hover` turns only the first span blue when hovered. The other spans keep their colors.
- CSS compares specificity before source order; source order breaks ties.

Course instructions: https://cpit405.gitlab.io/labs/lab-3/
