---
title: "Force-Aware Adaptation: What can we do if the force sensor is unavailable?"
authors: 
- admin 
date: "2023-12-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: We developed a system that learns and distills the force/torque information during training, then deploys the policy when the force/torque sensor is not available. The distillation module consists of a Teacher-Student architectrue for haptic feedback. The adapted policy can reach a 70% success rate even when the force/torque sensor is unavailable, while the baselines system without the two-stage distillation only achieves 20% succcess rate.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Haptic Feedback
- Reinforcement Learning
- Motor Adaptation

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://drive.google.com/file/d/1H0dNrO1rmT-15Uh_x7JDwXUsFMeUP_4K/view?usp=sharing'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
url_slides: 'https://docs.google.com/presentation/d/1ZN7DbITV7c_fYVVH4zHWkLcKjXQcZ-1m/edit?usp=sharing&ouid=109222920278629835448&rtpof=true&sd=true'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Autonomous Tissue Retraction with Haptic Feedback'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
