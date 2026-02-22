# SciDER: Scientific Data-centric End-to-end Researcher

**ACL Demo 2026 Submission**

SciDER is a data-centric end-to-end system for autonomous scientific discovery. It parses raw experimental data, designs hypotheses, and drives self-evolving scientific workflows across domains.

## Overview

Unlike traditional frameworks, SciDER implements a **data-centric workflow** by directly parsing and analyzing raw experimental data across diverse domains. This grounding enables hypothesis generation and experimental design tailored to specific data characteristics. SciDER excels in specialized scientific discovery through:

- **Data-first pipeline** — Parses raw experimental artifacts and metadata directly
- **Self-evolving memory** — Curates discoveries into reusable scientific context
- **Critic-led feedback** — Iteratively validates hypotheses before execution
- **Domain versatility** — Built to generalize across scientific disciplines

## Links

| Resource | Link |
|----------|------|
| **Project Page** | [harryluumn.github.io/scievo-project-page](https://harryluumn.github.io/scievo-project-page/) |
| **Live Demo** | [Hugging Face Spaces](https://huggingface.co/spaces/AI4Research/scievo) |
| **Code** | [GitHub - SciEvo](https://github.com/leonardodalinky/SciEvo) |

## Authors

- **Ke Lin** — William & Mary (Core contributor)
- **Yilin Lu** — University of Minnesota (Core contributor)
- **Qingyun Wang** — William & Mary

## Contact

- klin07@wm.edu
- qwang16@wm.edu
- lu000661@umn.edu

## This Repository

This repo hosts the **project landing page** for SciDER — a static website that showcases the system, abstract, demo walkthrough, and resources. The landing page is built with plain HTML, CSS, and JavaScript.

### Running Locally

Open `index.html` in a browser, or serve the directory with any static file server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .
```

Then visit `http://localhost:8000`.

## License

© 2026 SciDER — ACL Demo 2026
