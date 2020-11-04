---
title: "Correction of Automatic Speech Recognition with Transformer Sequence-To-Sequence Model"
collection: publications
permalink: /publications/speech_correction
venue: "ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)"
date: 2020-4-5
citation: 'Oleksii Hrinchuk*, <b>Mariya Popova*</b> and Boris Ginsburg. "Correction of Automatic Speech Recognition with Transformer Sequence-To-Sequence Model." ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, 2020.'
---
[[IEEE]](https://ieeexplore.ieee.org/abstract/document/9053051?casa_token=2nClaTIfVpgAAAAA:Nt7tPXrOPfN9BNWN1KmzbANOzyo8QV2oKP_fPmqXlfEwK4XleUURvQJOz39XzoisZupGTnJu) [[ArXiv]](https://arxiv.org/pdf/1910.10697.pdf)


## Abstract
In this work, we introduce a simple yet efficient post-processing model for automatic speech recognition (ASR). Our model has Transformer-based encoder-decoder architecture which "translates" ASR model output into grammatically and semantically correct text. We investigate different strategies for regularizing and optimizing the model and show that extensive data augmentation and the initialization with pre-trained weights are required to achieve good performance. On the LibriSpeech benchmark, our method demonstrates significant improvement in word error rate over the baseline acoustic model with greedy decoding, especially on much noisier dev-other and test-other portions of the evaluation dataset. Our model also outperforms baseline with 6-gram language model re-scoring and approaches the performance of re-scoring with Transformer-XL neural language model.
