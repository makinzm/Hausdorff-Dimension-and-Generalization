# git

```
$ git switch -c $NEW-NAME
```

# python

- click : [Python: コマンドラインパーサの Click が便利すぎた](https://blog.amedama.jp/entry/2015/10/14/232045)

# Papers

1. [Mohammadi, Mohammad, Adel Mohammadpour, and Hiroaki Ogata. "On estimating the tail index and the spectral measure of multivariate $\alpha $ α-stable distributions." Metrika 78.5 (2015): 549-561.](https://link.springer.com/content/pdf/10.1007/s00184-014-0515-7.pdf)

2. [Şimşekli, Umut, et al. "Hausdorff dimension, heavy tails, and generalization in neural networks." arXiv preprint arXiv:2006.09313 (2020).](https://arxiv.org/pdf/2006.09313v3.pdf)

3. [Borak, Szymon, Wolfgang Härdle, and Rafał Weron. "Stable distributions." Statistical tools for finance and insurance. Springer, Berlin, Heidelberg, 2005. 21-44.](https://d-nb.info/1206795506/34)

4. [Mikosch, Thomas. "Stable Non-Gaussian Random Processes: Stochastic Models with Infinite Variance." (1995): 805-806.](https://www.jstor.org/stable/pdf/2291104.pdf?casa_token=q58RRiKgSnsAAAAA:YfuT58iyVSyerM6i1bv8qGqFK81fUDFtHy594jVCdCsNz9MJMufgO5dLZJ9Mtu4ecBndVi0JN_IvZLiwOTAfAq48vO2BPwwJiwBOuUzU7iWZ4uX7cHBc)

# Experiment Flow

- Assume SGD can be described by this equation : 
  - $dW_t=-\nabla f(W_t)dt + \Sigma_1(W_t)dB_t+\Sigma_2(W_t)dL_t^{\alpha(W_t)} .$

### Technical Background

- Stable distribution ($1$-dimension) : $X \sim \mathcal{S}\alpha\mathcal{S}$
    - Characteristic function $\mathbb{E}[-\exp(iwX)]=\exp(-|\sigma w|^{\alpha})$
    - When $\alpha=2$, $\mathcal{S}\alpha\mathcal{S}=\mathcal{N}(0,2\sigma^2)$

- Elliptically-contoured $\alpha$-stable distribution