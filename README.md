# Property Inference Attacks and Defenses Literature
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of property inference attacks and defenses papers.

Paper are sorted by their released dates in descending order.

## How to Search?
Search keywords like conference name (e.g., ```CCS```), adversarial knowledge (e.g., ```Black-box```), or target model (e.g., ```Classification Model```) over the webpage to quickly locate related papers.

## Quick Links
**Attack papers sorted by year:** | [2024](#attack-papers-2024-back-to-top) | [2023](#attack-papers-2023-back-to-top) | [2022](#attack-papers-2022-back-to-top) | [2021](#attack-papers-2021-back-to-top) | [2019](#attack-papers-2019-back-to-top) | [2018](#attack-papers-2018-back-to-top) | [2015](#attack-papers-2015-back-to-top) |

**Defense papers sorted by year:** | [2024](#defense-papers-2024-back-to-top) | [2023](#defense-papers-2023-back-to-top) | [2022](#defense-papers-2022-back-to-top) | [2021](#defense-papers-2021-back-to-top) |

## Property Inference Attacks

### Attack Papers 2024 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2024 | **Towards More Efficient Property Inference Attacks on Graph Neural Networks** | Black-box | GNNs | NIPS |  |  |
| 2024 | **Quantifying Privacy Risks of Prompts in Visual Prompt Learning** | Black-box | Visual Prompt Learning | USENIX | [Link](https://arxiv.org/abs/2310.11970) | [Link](https://github.com/yxoh/prompt_leak_usenix2024/) |
| 2024 | **Attesting Distributional Properties of Training Data for Machine Learning** | Black-box | Classification model | ESORICS | [Link](https://arxiv.org/abs/2308.09552) | [Link](https://github.com/ssg-research/distribution-attestation) |
| 2024 | **Property Existence Inference against Generative Models** | Black-box | Generative model | USENIX | [Link](https://www.usenix.org/conference/usenixsecurity24/presentation/wang-lijin) | [Link](https://github.com/wljLlla/PEI_Code) |
| 2024 | **Property Inference as a Regression Problem: Attacks and Defense** | Black-box;White-box | Classification model | SECRYPT | [Link](https://www.insticc.org/node/TechnicalProgram/SECRYPT/2024/presentationDetails/128638) | |

### Attack Papers 2023 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **Distribution Inference Risks: Identifying and Mitigating Sources of Leakage** | Black-box;White-box | Classification model | IEEE SaTML | [Link](https://arxiv.org/abs/2209.08541) | [Link](https://github.com/epfl-dlab/distribution-inference-risks) |
| 2023 | **Dissecting Distribution Inference** | Black-box | Classification model | IEEE SaTML | [Link](https://arxiv.org/abs/2212.07591) | [Link](https://github.com/iamgroot42/dissecting_dist_inf) |
| 2023 | **Property Inference Attacks Against t-SNE Plots** | unknown | unknown | openreview | [Link](https://openreview.net/forum?id=q5ZwEiLzDft) | |
| 2023 | **SNAP: Efficient Extraction of Private Properties with Poisoning** | Black-box | Classification model | S&P | [Link](https://arxiv.org/abs/2208.12348) | |
| 2023 | **SoK: Let the Privacy Games Begin! A Unified Treatment of Data Inference Privacy in Machine Learning** | unknown | Classification model | S&P | [Link](https://arxiv.org/abs/2212.10986) | |
| 2023 |**Manipulating Transfer Learning for Property Inference** | unknown | unknown | CVPR | [Link](https://arxiv.org/abs/2303.11643) | |
| 2023 |**Exploring Clustered Federated Learning’s Vulnerability against Property Inference Attack** | White-box | Federated learning | RAID | [Link](https://dl.acm.org/doi/abs/10.1145/3607199.3607218) | |

### Attack Papers 2022 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2022 | **Property Inference Attacks against GANs** | Black-box;Partial black-box | Generative model | NDSS | [Link](https://arxiv.org/abs/2111.07608) | |
| 2022 | **Group Property Inference Attacks Against Graph Neural Networks** | White-box;Black-box | GNNs | CSS | [Link](https://dl.acm.org/doi/abs/10.1145/3548606.3560662) | |
| 2022 | **Property Inference from Poisoning** | Black-box | Classification model | S&P | [Link](https://ieeexplore.ieee.org/abstract/document/9833623) | |
| 2022 | **Poisoning-Assisted Property Inference Attack against Federated Learning** | unknown | unknown | TDSC | [Link](https://ieeexplore.ieee.org/abstract/document/9851511) | |
| 2022 | **Formalizing and Estimating Distribution Inference Risks** | Black-box;White-box | Classification model;GNNs | PETS | [Link](https://arxiv.org/abs/2109.06024) | [Link](https://github.com/iamgroot42/FormEstDistRisks) |
| 2022 | **Inference Attacks Against Graph Neural Networks** | Black-box | GNNs | USENIX | [Link](https://www.usenix.org/conference/usenixsecurity22/presentation/zhang-zhikun) | |
| 2022 | **Black-Box Audits for Group Distribution Shifts** | Black-box | Classification model | arXiv | [Link](https://arxiv.org/abs/2209.03620) | |

### Attack Papers 2021 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **Leakage of Dataset Properties in Multi-Party Machine Learning** | Black-box | Classification model | USENIX | [Link](https://www.usenix.org/conference/usenixsecurity21/presentation/zhang-wanrong) | |
| 2021 | **Unleashing the Tiger: Inference Attacks on Split Learning** | Splitting | Classification model | CCS | [Link](https://dl.acm.org/doi/10.1145/3460120.3485259) | [Link](https://github.com/pasquini-dario/SplitNN_FSHA) |
| 2021 | **Property Inference Attacks on Convolutional Neural Networks: Influence and Implications of Target Model's Complexity** | unknown | Classification model | arXiv | [Link](https://arxiv.org/abs/2104.13061) | |

### Attack Papers 2019 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2019 | **Exploiting Unintended Feature Leakage in Collaborative Learning** | White-box | Classification model | S&P | [Link](https://ieeexplore.ieee.org/abstract/document/8835269) | |
| 2019 | **Property Inference Attacks on Neural Networks using Dimension Reduction Representations** | unknown | Classification model | unknown | [Link](https://www.semanticscholar.org/paper/Property-Inference-Attacks-on-Neural-Networks-using-Wang/54232c6de4614862d3c8b0258d44209e70383c36) | |

### Attack Papers 2018 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2018 | **Property Inference Attacks on Fully Connected Neural Networks using Permutation Invariant Representations** | White-box | Classification Model | CCS | [Link](https://dl.acm.org/doi/abs/10.1145/3243734.3243834) | |

### Attack Papers 2015 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2015 | **Hacking Smart Machines with Smarter Ones: How to Extract Meaningful Data from Machine Learning Classifiers** | White-box | HMMs and SVMs | International Journal of Security and Networks | [Link](https://www.inderscienceonline.com/doi/abs/10.1504/IJSN.2015.071829) | |


## Property Inference Defenses
### Defense Papers 2024 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2024 | **Inf2Guard: An Information-Theoretic Framework for Learning Privacy-Preserving Representations against Inference Attacks** | Black-box | Classification model | USENIX | [Link](https://www.usenix.org/system/files/sec24fall-prepub-1985-noorbakhsh.pdf) | [Link](https://github.com/leilynourbakhsh/Inf2Guard) |
| 2024 | **Property Inference as a Regression Problem: Attacks and Defense** | Black-box;White-box | Classification model | SECRYPT | [Link](https://www.insticc.org/node/TechnicalProgram/SECRYPT/2024/presentationDetails/128638) | |

### Defense Papers 2023 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2023 | **PriSampler: Mitigating Property Inference of Diffusion Models** | unknown | Diffusion model | arXiv | [Link](https://arxiv.org/abs/2306.05208) | |
| 2022 | **Lessons Learned: Defending Against Property Inference Attacks** | unknown | unknown | SECRYPT | [Link](https://www.scitepress.org/Papers/2023/120492/120492.pdf) | |
| 2023 | **Distribution Inference Risks: Identifying and Mitigating Sources of Leakage** | Black-box;White-box | Classification model | IEEE SaTML | [Link](https://arxiv.org/abs/2209.08541) | [Link](https://github.com/epfl-dlab/distribution-inference-risks) |
| 2023 |**Secure Split Learning against Property Inference, Data Reconstruction, and Feature Space Hijacking Attacks** | unknown | unknown | arXiv | [Link](https://arxiv.org/abs/2304.09515) | |
| 2023 |**Protecting Global Properties of Datasets with Distribution Privacy Mechanisms** | White-box | Classification | AISTATS | [Link](https://proceedings.mlr.press/v206/chen23f.html) | [Link](https://github.com/mgcsls/mechanisms-global-properties) |

### Defense Papers 2022 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2022 |**Lessons Learned: How (Not) to Defend Against Property Inference Attacks** | unknown | unknown | arXiv | [Link](https://arxiv.org/abs/2205.08821) | |

### Defense Papers 2021 [[Back to Top](#property-inference-attacks-and-defenses-literature)]
| Year   | Title |  Adversarial Knowledge | Target Model  |   Venue  | Paper Link  | Code Link |
|-------|--------|--------|--------|-----------|------------|---------------|
| 2021 | **NOSnoop: An Effective Collaborative Meta-Learning Scheme Against Property Inference Attack** | unknown | unknown | ITJ | [Link](https://ieeexplore.ieee.org/abstract/document/9538829) | |

