# Projects Page Content Instructions

Place project entries here. Suggested structure:

- projects.yml: structured list of projects with fields:
  - title, period, links (code/demo/paper), tech, summary, image(optional)
- writeups/: optional per-project markdown files (one per project)
- images/: optional project images

YAML example:
- title: Awesome Project
  period: 2024
  links:
    code: https://github.com/...
    paper: https://arxiv.org/...
    demo: https://...
  tech: [Python, PyTorch]
  summary: Short 1-3 sentence overview.
  image: /assets/images/projects/awesome.png

We will render this into /projects/ using Minimal Mistakes cards.
