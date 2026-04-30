---
math: true
abstract: >
  In this paper, we study the problem of distributed mean estimation with 1-bit communication constraints. We propose a mean estimator that is based on (randomized and sequentially-chosen) interval queries, whose 1-bit outcome indicates whether the given sample lies in the specified interval. Our estimator is $(\epsilon, \delta)$-PAC for all distributions with bounded mean ($-\lambda \le \mathbb{E}(X) \le \lambda $) and variance ($\mathrm{Var}(X) \le \sigma^2$) for some known parameters $\lambda$ and $\sigma$.  We derive a sample complexity bound $\widetilde{O}\big( \frac{\sigma^2}{\epsilon^2}\log\frac{1}{\delta} + \log\frac{\lambda}{\sigma}\big)$, which matches the minimax lower bound for the unquantized setting up to logarithmic factors and the additional $\log\frac{\lambda}{\sigma}$ term that we show to be unavoidable. We also establish an adaptivity gap for interval-query based estimators: the best non-adaptive mean estimator is considerably worse than our adaptive mean estimator for large $\frac{\lambda}{\sigma}$. Finally, we give tightened sample complexity bounds for distributions with stronger tail decay, and present additional variants that (i) handle an unknown sampling budget (ii) adapt to the unknown true variance given (possibly loose) upper and lower bounds on the variance, and (iii) use only two stages of adaptivity at the expense of more complicated (non-interval) queries.
authors:
- admin
- Jonathan Scarlett

date: "2026-05-02T00:00:00Z"
publication: 'International Conference on Artificial Intelligence and Statistics (AISTATS) 2026'
publication_short: "AISTATS 2026"

title: "Sequential 1-bit Mean Estimation with Near-Optimal Sample Complexity"

url_dataset: ""
url_pdf: "https://arxiv.org/pdf/2509.21940"
url_poster: 
url_project: ""
url_slides: 1Bit_Mean_Est_Poster.pdf
url_source: ""
url_video: ""
---


