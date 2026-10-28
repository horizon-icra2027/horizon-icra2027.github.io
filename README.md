# HORIZON @ ICRA 2027 - workshop website

Static one-page site (no build step, no external fonts or scripts, so it also
loads from mainland China). Content follows the Round-2 full proposal
(`Round-2/latex/main.tex`, 28 October 2026).

## Files
- `index.html` - the page
- `assets/css/style.css` - styles
- `assets/img/` - HORIZON logo, favicon, institution and sponsor logos
- `.nojekyll` - tells GitHub Pages to serve files as they are

## Publish on GitHub Pages
1. Create a GitHub organization (e.g. `horizon-icra2027`) owned by your account.
2. In it, create a public repository named `horizon-icra2027.github.io`.
3. Upload the contents of this folder (not the folder itself) to the repository root.
4. Settings -> Pages -> Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
5. After a minute the site is live at `https://horizon-icra2027.github.io/`.
6. Put that URL into the proposal: in `main.tex`, replace
   `\TBD{[workshop website URL]}` with `\url{https://horizon-icra2027.github.io/}`.

## Update before or after acceptance
- Page sections: About, Programme, People (speakers and organizers), Contact.
- Programme and people: edit the matching sections in `index.html`.
- When the poster call opens: replace the one-line note under the hero buttons
  ("Call for posters will be available later.") with the call details or a link.
- Update the "Last updated" date in the footer.
