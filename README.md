# HASHIRU website

The site for the HASHIRU v2 whitepaper, *Agents That Hold the Money* (Kunal Pai and Harshil Patel, November 2026),
served at <https://hashiru-ai.github.io/hashiru-website/>.

- `index.html` is the whole page (plain HTML, CSS and JavaScript, no build step).
- `hashiru-v2-whitepaper.pdf` is the whitepaper, built from `paper/` in
  [HASHIRU-AI/HASHIRU](https://github.com/HASHIRU-AI/HASHIRU).
- `assets/og.png` is the preview image shown when the link is shared.

To update the whitepaper, rebuild it in the HASHIRU repo (`latexmk -pdf main.tex` in `paper/`), copy `main.pdf` here as
`hashiru-v2-whitepaper.pdf`, and check that the numbers on the page still match it.
