---
title: "Empirical Bayesian Independent Deeply Learned Matrix Analysis For Multichannel Audio Source Separation"
collection: publications
category: conferences
permalink: /publication/2021-08-23-eusipco-empirical
excerpt: "This paper propose an IDLMA extension, empirical Bayesian IDLMA (EB-IDLMA) to implicitly consider the reliability of the estimated source power spectrograms for the estimation of demixing filters through the hyperparameters of the prior distribution estimated by the DNN."
date: 2021-08-23
venue: 'ICASSP'
---

Independent deeply learned matrix analysis (IDLMA) is one of the state-of-the-art supervised multichannel audio source separation methods. It blindly estimates the demixing filters on the basis of source independence, using the source model estimated by the deep neural network (DNN). However, since the ratios of the source to interferer signals vary widely among time-frequency (TF) slots, it is difficult to obtain reliable estimated power spectrograms of sources at all TF slots. In this paper, we propose an IDLMA extension, empirical Bayesian IDLMA (EB-IDLMA), by introducing a prior distribution of source power spectrograms and treating the source power spectrograms as latent random variables. This treatment allows us to implicitly consider the reliability of the estimated source power spectrograms for the estimation of demixing filters through the hyperparameters of the prior distribution estimated by the DNN. Experimental evaluations show the effectiveness of EB-IDLMA and the importance of introducing the reliability of the estimated source power spectrograms.