# G2SC

The Pytorch implementation for the paper "GenAI-Driven Privacy-Preserving Semantic Communications via Knowledge Distillation".

## Introduction

Semantic communication (SC) skillfully combines advanced artificial intelligence (AI) technologies with traditional wireless communication to accommodate the demands of end-to-end intelligent services better. However, with the growing demand for personalized services, users expect customized intelligent communication, which presents new challenges for SC. Semantic extraction relies on AI models, and traditional centralized training requires users to upload personal data, which infringes upon user privacy. Although federated learning (FL) can address this issue, it is difficult to integrate with the channel simulations required in SC. In this paper, we propose a two-stage privacy-preserving SC framework for wireless image transmission, named distillation-to-SC (D2SC). In the first stage, we employ FL to extract personalized knowledge from private data. To address the training instability caused by data heterogeneity and the communication burden from frequent model aggregation, we use a generative AI model with high generalization as the teacher and transfer knowledge to a smaller student model through distillation. In the second stage, we inherit the student model and fine-tune it on the public dataset, endowing the model with specific task execution and image reconstruction capabilities. Furthermore, we incorporate a signal-to-noise ratio modulation module and introduce the information bottleneck to enhance the robustness against channel attenuation. Extensive experiments demonstrate that D2SC not only effectively mitigates challenges posed by heterogeneous data distributions but also accomplishes a variety of task objectives under different channel conditions.

## Code

We will make the code available after the paper is accepted.
