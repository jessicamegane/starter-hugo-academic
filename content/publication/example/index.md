---
title: 'Probabilistic Grammatical Evolution'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Nuno Lourenço
  - Penousal Machado

# Author notes (optional)
author_notes:

date: '2021-03-25T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-030-72812-0_13'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-03-25T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In European Conference on Genetic Programming (Part of EvoStar)
publication_short: In EuroGP 2021

abstract: Grammatical Evolution (GE) is one of the most popular Genetic Programming (GP) variants, and it has been used with success in several problem domains. Since the original proposal, many enhancements have been proposed to GE in order to address some of its main issues and improve its performance.\nIn this paper we propose Probabilistic Grammatical Evolution (PGE), which introduces a new genotypic representation and new mapping mechanism for GE. Specifically, we resort to a Probabilistic Context-Free Grammar (PCFG) where its probabilities are adapted during the evolutionary process, taking into account the productions chosen to construct the fittest individual. The genotype is a list of real values, where each value represents the likelihood of selecting a derivation rule. We evaluate the performance of PGE in two regression problems and compare it with GE and Structured Grammatical Evolution (SGE).\nThe results show that PGE has a better performance than GE, with statistically significant differences, and achieved similar performance when comparing with SGE.

# Summary. An optional shortened abstract.
summary: ""

tags: [Genetic Programming, Grammatical Evolution, Probabilistic Context-Free Grammar]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2103.08389'
url_code: 'https://github.com/jessicamegane/pge/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=JkLCJaiCTe4&t=341s'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ""
 # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
#example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
