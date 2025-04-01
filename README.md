# Hugo Kicking the Tires 🚗💨

This repository documents my hands-on exploration of [Hugo](https://gohugo.io/), a fast and modern static site generator written in Go.

It was created as part of **Part III** of the CIS 3500 Software Engineering assignment: *“Kicking the Tires”*, where we learned how to create a Hugo site from scratch and experiment with layouts, archetypes, and content.

---

## 📚 What I Did

- Created a brand new Hugo site (`portfolio/`)
- Customized the homepage using `layouts/index.html`
- Created pages like:
  - **About** (`about.md`)
  - **Résumé** (`resume.md`)
  - **Contact** (using a custom archetype)
- Built a reusable single-page layout in `layouts/_default/single.html`
- Modified the default archetype to set `draft: false` by default
- Practiced live editing using `hugo server`
- Generated a full static site using `hugo`

---

## 🧪 Live Preview

To run the site locally:

```bash
cd portfolio
hugo server

