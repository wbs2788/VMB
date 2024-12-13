# 🎬🎵<img src="imgs/bridge.png" alt="pyramid" height="30"/> VMB

[[[arXiv]](https://arxiv.org/abs/)](https://arxiv.org/abs/2412.09428)

Code for our paper "Multimodal Music Generation with Explicit Bridges and Retrieval Augmentation" 






## 📅 Schedule

* [ ] video-music dataset
* [ ] pretrained model weights
* [ ] inference code
* [ ] evaluation code
* [ ] training code




## ⭐️ Highlights

**TL;DR:** We present Visuals Music Bridge (VMB), a novel framework for multimodal music generation by using text and music as explicit bridges to address challenges in data scarcity, cross-modal alignment, and controllability. VMB significantly improves music quality, modality alignment, and customization across tasks like video-to-music and image-to-music generation.

* Proposes explicit text and music bridges for better multimodal alignment, leveraging detailed textual descriptions and retrieval-augmented generation.

* Introduces a Multimodal Music Description Model, Dual-track Music Retrieval, and Explicitly Conditioned Music Generation for enhanced quality and control.

* Demonstrates state-of-the-art performance in video-to-music, image-to-music, and controllable music generation tasks.

<p align="center">
<img src="imgs/overview.png" alt="ouip" width="100%"/> 
</p>



## 📌 Abstract

Multimodal music generation aims to produce music from diverse input modalities, including text, videos, and images. Existing methods use a common embedding space for multimodal fusion. Despite their effectiveness in other modalities, their application in multimodal music generation faces challenges of data scarcity, weak cross-modal alignment, and limited controllability. This paper addresses these issues by using explicit bridges of text and music for multimodal alignment.
We introduce a novel method named Visuals Music Bridge (VMB). Specifically, a Multimodal Music Description Model converts visual inputs into detailed textual descriptions to provide the text bridge; a Dual-track Music Retrieval module that combines broad and targeted retrieval strategies to provide the music bridge and enable user control. Finally, we design an Explicitly Conditioned Music Generation framework to generate music based on the two bridges. We conduct experiments on video-to-music, image-to-music, text-to-music, and controllable music generation tasks, along with experiments on controllability. The results demonstrate that VMB significantly enhances music quality, modality, and customization alignment compared to previous methods. VMB sets a new standard for interpretable and expressive multimodal music generation with applications in various multimedia fields.





## 🔍 Method

Multimodal Music Description Model (MMDM)

![](imgs/mmdm.png)

Dual-track Music Retrieval and Explicitly Conditioned Music Generation

![](imgs/dmr_ecmg.jpg)




## 🛠️ Usage

TODO




## 📃 License

This project is released under the MIT license.



## 🖊️ Citation

If you find this work helpful for your research, please consider giving this repo a star ⭐ and citing our paper:

```bibtex
@article{
  TODO
}
```

