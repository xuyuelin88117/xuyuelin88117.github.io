---
title: Improving the Efficiency of Self-Supervised Adversarial Training through Latent
  Clustering-based Selection
authors:
- ' Anonymous'
date: '2024-01-01'
publishDate: '2024-07-07T04:29:56.202486Z'
publication_types:
- paper-conference
publication: '*ICML 2024 Next Generation of AI Safety Workshop*'
links:
- name: OpenReview
  url: https://openreview.net/forum?id=FjZsM7D9AT&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICML.cc%2F2024%2FWorkshop%2FNextGenAISafety%2FAuthors%23your-submissions)

url_pdf: 'https://openreview.net/pdf?id=FjZsM7D9AT'

abstract: Compared to standard learning, adversarially ro- bust learning is widely recognized to require a much larger training dataset. Recent works uti- lize external or synthetically generated unlabeled data in adversarial training using self-supervised learning. Despite achieving enhanced robustness, these methods typically require a considerable amount of additional data, leading to substantial memory consumption and convergence time. To address the space and computational challenges, we propose a novel Latent Clustering-based Selec- tion scheme (LCS) to strategically select a small core subset of unlabeled data critical for obtaining better robustness. In particular, our method pri- oritizes selecting unlabeled data that are close to the model’s decision boundary, while balancing the ratio between the boundary and the remaining data points to avoid overfitting. Our experiments show that when incorporated into self-supervised adversarial training, our LCS scheme can signifi- cantly reduce the memory and time complexities while achieving comparable model robustness.
---
