---
math: true
abstract: >
  We study stochastic linear bandits under a natural combination of batching and communication constraints: the time horizon is partitioned into batches of equal size $B$, and during each batch the learner sends $B$ requested arm pulls to an agent, who then observes the corresponding $B$ rewards and responds with a single bit of feedback to the learner. 
  For each batch, the learner specifies the 1-bit quantization rule the agent uses, which may depend on all previously received bits but not on any past rewards directly.
  This setting addresses a significant yet unexplored ``middle ground'' between previous models having per-round quantization only \emph{or} total bit budgets only.  We establish a minimax lower bound showing that $\Omega(B\min\{d,\log\lvert \mathcal{A} \rvert\})$ regret is unavoidable due to the 1‑bit communication bottleneck, even in the absence of noise. Combined with standard statistical limits, this yields a general lower bound of $\widetilde{\Omega}(B\min\{d,\log\lvert \mathcal{A} \rvert\} + \sqrt{dT \min\{d,\log\lvert \mathcal{A} \rvert\}})$.  We develop two phased‑elimination algorithms based on $G$-optimal designs and 1‑bit mean estimation. The first achieves $\widetilde{O}(dB + d\sqrt{T})$ regret, matching the lower bound up to logarithmic factors when $\lvert \mathcal{A} \rvert = \exp(\Omega(d))$, and the second incorporates a safe‑arm identification and warm‑start procedure to obtain $\widetilde{O}(B\log\lvert \mathcal{A} \rvert + d^{3/2}\sqrt{B} + \sqrt{dT\log\lvert \mathcal{A} \rvert})$ regret, which is near‑optimal in broad scaling regimes of $(\lvert \mathcal{A} \rvert, B, d, T)$. Together, our results demonstrate that a single bit of feedback per batch suffices to nearly match the minimax regret of \emph{unconstrained} linear bandits in broad scaling regimes, even for batch sizes as large as $\Theta(\sqrt{T})$.
authors:
- admin
- Jonathan Scarlett

date: "2026-02-01T00:00:00Z"
publication: 'In Submission'
publication_short: "In Submission"

title: "Batched Stochastic Linear Bandits with 1-Bit Communication Constraints"

url_dataset: ""
url_pdf: "https://arxiv.org/pdf/2605.30976"
url_poster: 
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---


