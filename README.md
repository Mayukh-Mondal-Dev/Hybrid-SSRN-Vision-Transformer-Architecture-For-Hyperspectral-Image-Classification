# Hybrid-SSRN-Vision-Transformer-Architecture-For-Hyperspectral-Image-Classification
A SSRN Layer with Vision Transformer Architecture for Hyperspectral Image Classification On Indian Pines Dataset
---
## Abstract

In this project, we propose a hyperspectral image classification method that combines the strengths of Vision Transformers and Convolutional Neural Networks (CNNs). Vision Transformers, renowned for their effectiveness in natural language processing, offer a unique architecture utilizing multi-head attention mechanisms to establish long-range contextual relations between pixels in images. Our method involves dividing images into patches, converting them into sequences through flattening and embedding processes. To preserve positional information, we incorporate position embeddings into these patches. The resulting sequences then pass through multiple multi-head attention layers to generate comprehensive representations. For the classification phase, the initial token sequence is directed to a softmax classification layer. To enhance classification performance, we explore various data augmentation strategies. Additionally, through experimentation, we demonstrate the network's ability to achieve competitive classification accuracies even after pruning half of its layers, showcasing its efficiency. Results from experiments conducted on diverse remote-sensing image datasets underscore the promising capabilities of our model compared to state-of-the-art methods.

---

## Architecture

![Architechural diagram final 1](https://github.com/Mayukh-Mondal-Dev/Hybrid-SSRN-Vision-Transformer-Architecture-For-Hyperspectral-Image-Classification/assets/103057066/efd9f967-3c30-48d0-8973-ea7771f0ec48)
