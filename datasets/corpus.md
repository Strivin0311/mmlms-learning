# Training Corpus for Multi-Modal Language Models
*Here're some resources about training corpus for mmlms to pretrain or finetune*



## Image-Caption Pretraining

#### ShareGPT4V: Improving Large Multi-Modal Models with Better Captions [`READ`]

paper link: [here](https://arxiv.org/pdf/2311.03079.pdf)

github link: [here](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)

homepage link: [here](https://sharegpt4v.github.io/)

dataset link: [here](https://huggingface.co/datasets/Lin-Chen/ShareGPT4V)


citation:
```bibtex
@misc{chen2023sharegpt4v,
      title={ShareGPT4V: Improving Large Multi-Modal Models with Better Captions}, 
      author={Lin Chen and Jinsong Li and Xiaoyi Dong and Pan Zhang and Conghui He and Jiaqi Wang and Feng Zhao and Dahua Lin},
      year={2023},
      eprint={2311.12793},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


#### Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts (CC12M) [`UNREAD`]

paper link: [here](https://arxiv.org/pdf/2102.08981)

github link: [here](https://github.com/google-research-datasets/conceptual-12m)

dataset link: [here](https://github.com/google-research-datasets/conceptual-12m?tab=readme-ov-file#download)


citation:

```bibtex
@inproceedings{changpinyo2021cc12m,
  title = {{Conceptual 12M}: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts},
  author = {Changpinyo, Soravit and Sharma, Piyush and Ding, Nan and Soricut, Radu},
  booktitle = {CVPR},
  year = {2021},
}
```


#### Conceptual Captions: A Cleaned, Hypernymed, Image Alt-text Dataset For Automatic Image Captioning (CC3M) [`UNREAD`]

paper link: [here](https://aclanthology.org/P18-1238.pdf)

github link: [here](https://github.com/google-research-datasets/conceptual-captions)

dataset link: [google-official-cc3m](https://ai.google.com/research/ConceptualCaptions/download) | [llava-cc3m](https://huggingface.co/datasets/liuhaotian/LLaVA-CC3M-Pretrain-595K)


citation:

```bibtex
@inproceedings{sharma-etal-2018-conceptual,
    title = "Conceptual Captions: A Cleaned, Hypernymed, Image Alt-text Dataset For Automatic Image Captioning",
    author = "Sharma, Piyush  and
      Ding, Nan  and
      Goodman, Sebastian  and
      Soricut, Radu",
    editor = "Gurevych, Iryna  and
      Miyao, Yusuke",
    booktitle = "Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2018",
    address = "Melbourne, Australia",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/P18-1238",
    doi = "10.18653/v1/P18-1238",
    pages = "2556--2565",
    abstract = "We present a new dataset of image caption annotations, Conceptual Captions, which contains an order of magnitude more images than the MS-COCO dataset (Lin et al., 2014) and represents a wider variety of both images and image caption styles. We achieve this by extracting and filtering image caption annotations from billions of webpages. We also present quantitative evaluations of a number of image captioning models and show that a model architecture based on Inception-ResNetv2 (Szegedy et al., 2016) for image-feature extraction and Transformer (Vaswani et al., 2017) for sequence modeling achieves the best performance when trained on the Conceptual Captions dataset.",
}
```


## Visual Instruction Finetuning (V-IFT)


#### Visual instruction tuning (LLaVA-Instruct) [`READ`]

paper link: [here](https://arxiv.org/pdf/2304.08485)

homepage link: [here](https://llava-vl.github.io/)

github link: [here](https://github.com/haotian-liu/LLaVA)

dataset-zoo link: [here](https://github.com/haotian-liu/LLaVA/blob/main/docs/Data.md)

citation: 
```bibtex
@inproceedings{liu2023llava,
    author = {Liu, Haotian and Li, Chunyuan and Wu, Qingyang and Lee, Yong Jae},
    title = {Visual Instruction Tuning},
    booktitle = {NeurIPS},
    year = {2023}
}
```