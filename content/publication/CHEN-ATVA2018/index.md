---
title: "What's to Come is Still Unsure"
subtitle: 'Synthesizing Controllers Resilient to Delayed Interaction'

featured: false
draft: false

authors:
  - Mingshuai Chen
  - Martin Fränzle
  - Yangjia Li
  - Peter Nazier Mosaad
  - Naijun Zhan
# author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2018-09-30T00:00:00Z'
#date: '2015-09-01T00:00:00Z'
#lastmod: 2021-10-07T18:49:05-06:00

doi: '10.1007/978-3-030-01090-4_4'

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *ATVA 2018*
publication_short: In *ATVA 2018*

abstract: The possible interactions between a controller and its environment can naturally be modelled as the arena of a two-player game, and adding an appropriate winning condition permits to specify desirable behavior. The classical model here is the positional game, where both players can (fully or partially) observe the current position in the game graph, which in turn is indicative of their mutual current states. In practice, neither sensing or actuating the environment through physical devices nor data forwarding to and signal processing in the controller are instantaneous. The resultant delays force the controller to draw decisions before being aware of the recent history of a play. It is known that existence of a winning strategy for the controller in games with such delays is decidable over finite game graphs and with respect to $\omega$-regular objectives. The underlying reduction, however, is impractical for non-trivial delays as it incurs a blow-up of the game graph which is exponential in the magnitude of the delay. For safety objectives, we propose a more practical incremental algorithm synthesizing a series of controllers handling increasing delays and reducing game-graph size in between. It is demonstrated using benchmark examples that even a simplistic explicit-state implementation of this algorithm outperforms state-of-the-art symbolic synthesis algorithms as soon as non-trivial delays have to be handled. We furthermore shed some light on the practically relevant case of non-order-preserving delays, as arising in actual networked control, thereby considerably extending the scope of regular game theory under delay pioneered by Klein and Zimmermann.

tags:
  - games
  - safety
  - control
  - delay
  - synthesis

# Summary. An optional shortened abstract.
summary: ''

links:
  - icon_pack: fas
    icon: certificate
    name: "Distinguished Paper Award"
    url: "/files/DPA-ATVA18-photo.jpeg"
url_pdf: '/papers/ATVA2018.pdf'
url_code: 'https://www.notebookarchive.org/synthesizing-controllers-for-safety-games-under-delayed-information--2021-08-5lc88f4/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/slides/MISSION.pdf'
url_source: ''
url_video: 'https://youtu.be/6AjaYHy_3Fo'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
<!-- ![Distinguished Paper Award @ ATVA 2018](/files/DPA-ATVA18.png "Distinguished Paper Award @ ATVA 2018")
![Distinguished Paper Award @ ATVA 2018](/files/DPA-ATVA18-photo.jpeg "Distinguished Paper Award @ ATVA 2018") -->

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->
