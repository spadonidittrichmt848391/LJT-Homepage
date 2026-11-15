# LJT-Homepage

Personal homepage of **Junteng Liu**, a first-year PhD candidate at the **HKUST NLP Group**, supervised by Professor Junxian He. Research focuses on natural language processing and machine learning, with interests in LLM reasoning and reinforcement learning, hallucination in vision-language models (VLM), and LLM truthfulness and interpretability.

- Site: https://spadonidittrichmt848391.github.io/LJT-Homepage/
- Email: jliugi@connect.ust.hk
- GitHub: [Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)

## Site structure

- `_pages/about.md` — the homepage (About): personal details, academic background, research experience, publications, skills, awards, and contact information.
- `_pages/publications.html` and `_publications/` — the publications page and the individual publication entries.
- `_config.yml` — site-wide configuration and the author sidebar.
- `_data/navigation.yml` — header navigation (About, Publications).

## Deployment

This site is built with Jekyll using the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) (a fork of the [Minimal Mistakes Jekyll theme](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/)). It is deployed to GitHub Pages with the included workflow (`.github/workflows/jekyll.yml`). To publish the site, enable GitHub Pages for this repository (Settings → Pages → Build and deployment → Source: GitHub Actions) and make sure GitHub Actions is enabled; the workflow then builds and deploys the site on every push to `master`.

The template is used under its license (see `LICENSE`).
