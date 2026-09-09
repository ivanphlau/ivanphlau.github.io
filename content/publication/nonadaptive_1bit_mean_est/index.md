---
math: true
abstract: >
  We study distributed one-dimensional mean estimation under a 1-bit
  communication constraint. Each agent observes one sample, drawn
  independently from an unknown distribution, and returns a single bit
  in response to a query $Q:\mathbb{R}\to\{0,1\}$ chosen by a central
  learner. The distribution has mean in $[-\lambda,\lambda]$ and
  $k$-th central moment at most $\sigma^k$, for a fixed $k>1$.
  The order-optimal two-stage protocol of Lau and Scarlett uses
  responses from the first batch to choose the second-batch queries,
  motivating the question of whether this single round of interaction
  is necessary. We answer this negatively: for every $k>1$, a
  non-adaptive protocol attains the adaptive 1-bit minimax rate
  (and concurrent works reached the same conclusion via different
  strategies). We further determine the minimax sample complexity
  among non-adaptive 1-bit estimators when every one-set $Q^{-1}(1)$
  is restricted to a union of at most $s$ intervals. Relative to
  unrestricted non-adaptive 1-bit querying, this constraint adds a
  term of order $\frac{\lambda\sigma}{s\varepsilon^2}\log(1/\delta)$,
  giving the full tradeoff between sample complexity and interval
  complexity to within $k$-dependent constant factors. As a corollary,
  we identify, order-wise, the minimum interval budget needed to
  retain the unrestricted 1-bit minimax sample rate.
  
authors:
- admin
- Jonathan Scarlett

date: "2026-09-08T00:00:00Z"
publication: 'In Submission'
publication_short: "In Submission"

title: "Non-Adaptive 1-Bit Mean Estimation: Minimax Rates and the Sample-Interval Tradeoff"

url_dataset: ""
url_pdf: "https://arxiv.org/pdf/2609.08564"
url_poster: 
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---
