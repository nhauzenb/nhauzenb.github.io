---
title: "Topic #4: Macroeconomic forecasting with time series foundation models"
collection: supervision
type: "MSc summer project topic"
permalink: /supervision/topic4
venue: "University of Strathclyde"
excerpt: "Are pretrained (zero-shot) time series models such as Chronos useful for forecasting inflation or nowcasting activity?"
semesters: "Academic year 2026/27"
coauthors: ""
location: ""
---

### Outline.
<p align="justify"> Foundation models for time series are pretrained on large and diverse collections of time series data and produce forecasts for a new series without estimating a model for that series (so-called zero-shot forecasting). Chronos (and Chronos-2), for example, builds on the transformer architectures behind LLMs. Whether such models are useful for macroeconomic time series, which are short, persistent, and subject to structural breaks, is an open question. One application could be inflation forecasting, which is of great interest to central banks and for which machine learning techniques have gained popularity (e.g., Medeiros et al., 2021). Another application could be tracking economic activity/conditions at high frequency, as done by the <a href="https://www.dallasfed.org/research/wei">Weekly Economic Index (WEI)</a> of Lewis, Mertens, and Stock, published by the Federal Reserve Bank of Dallas. This topic is well suited for Option B, since forecasts or nowcasts can be communicated through an interactive Shiny app. For inspiration on what such a Shiny app could look like, see <a href="https://nowcastinglab.org/map">nowcastinglab.org</a>.
</p>

### Suggested initial readings.
* Ansari, A. F., Stella, L., Turkmen, C., et al. (2024). Chronos: Learning the language of time series. *Transactions on Machine Learning Research*. <https://arxiv.org/abs/2403.07815>
* Ansari, A. F., Shchur, O., Küken, J., et al. (2025). Chronos-2: From univariate to universal forecasting. *arXiv preprint*, arXiv:2510.15821. <https://arxiv.org/abs/2510.15821><br>Model: <https://huggingface.co/amazon/chronos-2><br>Code: <https://github.com/amazon-science/chronos-forecasting>
* Medeiros, M. C., Vasconcelos, G. F., Veiga, Á., & Zilberman, E. (2021). Forecasting inflation in a data-rich environment: The benefits of machine learning methods. *Journal of Business & Economic Statistics*, **39**(1), 98–119. <https://doi.org/10.1080/07350015.2019.1637745>
* Lewis, D. J., Mertens, K., Stock, J. H., & Trivedi, M. (2021). High-frequency data and a weekly economic index during the pandemic. *AEA Papers and Proceedings*, **111**, 326–330. <https://www.aeaweb.org/articles?id=10.1257/pandp.20211050>
* Lewis, D. J., Mertens, K., Stock, J. H., & Trivedi, M. (2022). Measuring real activity using a weekly economic index. *Journal of Applied Econometrics*, **37**(4), 667–687. <https://doi.org/10.1002/jae.2873><br>WEI data available at: <https://www.dallasfed.org/research/wei>
