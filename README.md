# Transformer-based model

This work proposed an automatic sleep staging method and tried to provide the interpretability for clinical support by visualizing the decision-making.

We designed a novel physiological-based EEG spectrogram segmentation and introduces the Transformer to finding the stage-dependent feature with it.

The implementation can be found in Transformer_SleepStage.ipynb.

Gradient-attention-based visualization has shown in Vit_visualization.ipynb

Model_xxxxx files represents the different versions of the model architecture.


<img width="877" alt="image" src="https://user-images.githubusercontent.com/34312998/133877516-fc4f2b31-6c1b-4674-ae87-d86107c62005.png">





Try to visualize the decision-making of the model compare with previous work[1] based on [2],[3].

<img width="725" alt="image" src="https://user-images.githubusercontent.com/34312998/134160769-285777f9-8290-4d4e-8c08-d0a765cae049.png">

Result (Vit_visualization.ipynb):

<img width="898" alt="image" src="https://user-images.githubusercontent.com/34312998/133877630-9b2f2eec-11e0-4d41-8c36-5afd02dd78d6.png">

[1] Z. Chen, K. Odani, P. Gao, N. Ono, M. Altaf-Ul-Amin, S. Kanaya, and M. Huang, “Feasibility analysis of transformer model for eeg-based sleep scoring,” in 2021 IEEE International Conference on Biomedical and Health Informatics (BHI’21), Virtual, July 2021.

[2] H. Chefer, S. Gur, and L. Wolf, “Generic attention-model explainability for interpreting bi-modal and encoder-decoder transformers,” CoRR, vol. abs/2103.15679, 2021. [Online]. Available: https://arxiv.org/abs/2103.15679

[3] Hila Chefer, Shir Gur, Lior Wolf, “Transformer interpretability beyond attention visualization,” arXiv preprint arXiv:2012.09838, 2020.
