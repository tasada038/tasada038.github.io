---
title: "Motivation-based Action Selection and Emergence of Locomotion Behavior for BURs"
authors:
- me
- Hideo Furuhashi
- Kenta Tabata
- Renato Miyagusuku
- Koichi Ozaki
date: "2026-09-16T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2026-09-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication metadata — structured fields used by citation styles and BibTeX export.
publication:
  name: "IEEE Robotics and Automation Letters"
  # volume: 308
  # issue: 118261

peer_reviewed: true
open_access: true
license: CC-BY-4.0

external_link: https://tasada038.github.io/as-emergence-bur/

# Summary. An optional shortened abstract.
summary: Conventional multifunctional BURs rely on explicitly programmed, task-level behaviors, limiting how flexibly actions are selected and how much behavioral diversity can emerge. This paper proposes a control system that integrates motivational states directly to motion primitives, with the dominant primitive selected for each joint via an element-wise maximum. Hybrid, multi-mode behaviors thereby emerge from the interaction of motivations, rather than from predefined rules. Physical experiments (slope traversal, a sedimentation basin, swimming, walking, crab-like gait, and bouncing gait) confirmed the approach, with a potential-method analysis showing a 15.6% improvement in energy cost per behavior over a conventional method.

tags:
- Journal
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/projects/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---