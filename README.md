# Tanush's personal website - EE461L HW4, Task 1

This site uses only HTML and an external CSS stylesheet. The circuit-board illustration is an original local SVG asset; it does not require a network request.

## Rubric

- Tag selector: `p`; reused class: `.content-section`; styled ID: `#about`.
- Content sections use `div` elements for About, Coursework, and Learning.
- External links point to MDN, React, and Material UI; `a:hover` changes their color.
- The stylesheet sets margin, padding, and border properties.
- An `img` tag displays `assets/circuit.svg` with descriptive alt text.
- The page includes a search-engine description meta tag and no JavaScript.

Open `index.html` in any browser, or run `python3 -m http.server 8000` from this folder and open `http://localhost:8000`.

## GitHub Pages

Repository: https://github.com/IBeatUAgain/IBeatUAgain.github.io

Website: https://ibeatuagain.github.io/

For a user site, the repository must be named `<your-github-username>.github.io`. Put the **contents** of this folder at the root of that repository, including `index.html`, `stylesheet.css`, `assets/`, and `.nojekyll`.

In the repository's Settings -> Pages, select **Deploy from a branch**, choose **main**, choose **/ (root)**, and save. The published site will be `https://<your-github-username>.github.io/`. Submit the **repository URL** on Canvas, as requested in the assignment.

If you already have a user Pages site, preserve that site. The handout permits this assignment in a separate repository, submitted with the existing Pages site link. A separate project Pages site is served at `https://<your-github-username>.github.io/<repository-name>/`; all assets in this site use relative paths to support that layout.

Deployment reference: https://docs.github.com/en/pages/quickstart.
