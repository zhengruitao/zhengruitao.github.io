---
title: "A Novel Method for Tool Condition Monitoring Based on Long Short-Term Memory and Hidden Markov Model Hybrid Framework in High-Speed Milling Ti-6Al-4V"
collection: publications
excerpt: 'This paper is submitted to AMT.'
permalink: /publications/AMT
date: 2019-8-19
---
* ***Current Status: Published***

## Abstract
High-speed milling of Ti-6Al-4V produces high temperature in the cutting zone resulting in the rapid notching and severe flank wear, which tend to cause the deterioration of the machined surface and increased manufacturing costs. To track the performance degradation of the cutting tool, more and more studies have been conducted to develop effective tool condition monitoring (TCM) systems, hoping to obtain the tool wear status based on monitoring signals. In recent years, machine learning and deep learning methods have developed rapidly and are becoming increasingly popular, and the related research results inspired this article. In this paper, a novel method based on Long Short-Term Memory network and hidden Markov model (LSTM-HMM) is presented to track the flank wear and predict the remaining useful life (RUL). The model is divided into three parts: training phase, diagnostic phase, and prognostic phase. During the training phase, both the observed monitoring signal and extracted features that characterize tool wear status are used as the inputs to the training algorithms to estimate the parameters of the global model and local models. Then proceed to the diagnostic phase, the established global model is utilized to identify the current tool wear stage deciding which model to select from the local model base. Finally, the mean wear amount, the remaining useful life and the associated confidence interval are calculated in the prognostic phase. The proposed hybrid model and several other published methods are applied to the three datasets acquired from milling experiments. The experimental and analytical results indicate that the integrated framework is applicable to track the tool wear and predict its RUL during the high-speed milling Ti-6Al-4V.
