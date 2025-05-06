---
title: "Music Tagging with Classifier Group Chains"
collection: publications
category: conferences
permalink: /publication/2025-04-10-icassp-music
excerpt: "This paper proposes music tagging with classifier group chains, which considers conditional dependence among tag categories."
date: 2025-04-10
venue: 'International Conference on Acoustics, Speech and Signal Processing, 2025'
---

We propose music tagging with classifier chains that model the interplay of music tags. Most conventional methods estimate multiple tags independently by treating them as multiple independent binary classification problems. This treatment overlooks the conditional dependencies among music tags, leading to suboptimal tagging performance. Unlike most music taggers, the proposed method sequentially estimates each tag based on the idea of the classifier chains. Beyond the naive classifier chains, the proposed method groups the multiple tags by category, such as genre, and performs chains by unit of groups, which we call _classifier group chains_. Our method allows the modeling of the dependence between tag groups. We evaluate the effectiveness of the proposed method for music tagging performance through music tagging experiments using the MTG-Jamendo dataset. Furthermore, we investigate the effective order of chains for music tagging.
