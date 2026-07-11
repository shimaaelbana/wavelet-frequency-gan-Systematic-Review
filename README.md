# Wavelet-Aware and Frequency-Domain Integrations for Enhancing GANs: A Systematic Review

This repository contains the complete underlying dataset, data extraction parameters, and quality assessment matrices for our systematic review tracking spatial-frequency processing and advanced pooling in Generative Adversarial Networks (GANs).

## Abstract
This systematic review evaluates the integration of wavelet-aware pooling and frequency-domain processing strategies within Generative Adversarial Networks (GANs).Following PRISMA 2020 guidance, we searched PubMed, Scopus, Web of Science, and IEEE Xplore (search last executed on [April 2025]) and included 50 primary studies published between 2020 and 2025. To organize this heterogeneous evidence base, we introduce a structured taxonomy categorizing integrations into pooling-centric mechanisms (explicit wavelet pooling and non-wavelet advanced pooling) and spectral-centric integrations (wavelet feature decomposition, wavelet loss or discriminator design, and broader alternative frequency designs). Quantitative performance improvements were most often observed in super-resolution, image translation, denoising, and medical image enhancement tasks; however, comprehensive evidence comparability across the corpus was heavily limited by highly heterogeneous datasets, inconsistent metric reporting, a sparse distribution of architectural ablation experiments, and low source code availability. The primary practical contributions of this work include a formal structural taxonomy, a comprehensive domain-stratified risk-of-bias quality assessment, and a recommended reporting checklist to guide future reproducible multi-resolution generative AI workflows. The systematic review dataset, data extraction sheets, and quality evaluation matrices are publicly available at \url{https://github.com/shimaaelbana/wavelet-frequency-gan-Systematic-Review}.

## Repository Contents

*   `data_extraction_matrix.xlsx`: Comprehensive extraction sheet covering all 26 collected variables across the 50 included primary studies (2020–2025).
*   `risk_of_bias_evaluation.xlsx`: The 8-domain quality assessment and risk-of-bias evaluation matrix used to benchmark study rigor and generate text visualizations.
*    `risk_of_bias_summary.xlsx` : The final summary for the 8-domain quality assesment
  

## Citation

If you use this dataset or find our taxonomy framework helpful in your research, please cite our paper:

```text
[@article{elbana2025systematic,
  title={A Systematic Review of Wavelet-Based Pooling for Enhancing GANs: Central Trends, Auxiliary Pooling Strategies, and Complementary Wavelet Integrations},
  author={Elbana, Shimaa and Al-Kabbany, Ahmad and El-Khamy, Said},
  year={2025}
}]
