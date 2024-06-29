# Pretraining Strategies for Multimodal Large Language Models
*Here're some resources about how to pretrain MMLMs*



## Multi-Modality Alignment Pretraining


### OmniTokenizer: A Joint Image-Video Tokenizer for Visual Generation

paper link: [here](https://arxiv.org/pdf/2406.09399)

github link: [here](https://github.com/FoundationVision/OmniTokenizer)

citation:

```bibtex
@misc{wang2024omnitokenizerjointimagevideotokenizer,
      title={OmniTokenizer: A Joint Image-Video Tokenizer for Visual Generation}, 
      author={Junke Wang and Yi Jiang and Zehuan Yuan and Binyue Peng and Zuxuan Wu and Yu-Gang Jiang},
      year={2024},
      eprint={2406.09399},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
      url={https://arxiv.org/abs/2406.09399}, 
}
```

#### Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding

paper link: [here](https://arxiv.org/pdf/2311.08046)

github link: [here](https://github.com/PKU-YuanGroup/Chat-UniVi)

citation: 
```bibtex
@misc{jin2024chatunivi,
      title={Chat-UniVi: Unified Visual Representation Empowers Large Language Models with Image and Video Understanding}, 
      author={Peng Jin and Ryuichi Takanobu and Wancai Zhang and Xiaochun Cao and Li Yuan},
      year={2024},
      eprint={2311.08046},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


## Image-Text Alignment Pretraining


#### MobileVLM V2: Faster and Stronger Baseline for Vision Language Model (LDPv2)

paper link: [here](https://arxiv.org/pdf/2402.03766)

github link: [here](https://github.com/Meituan-AutoML/MobileVLM)


citation:
```bibtex
@article{chu2024mobilevlm,
  title={MobileVLM V2: Faster and Stronger Baseline for Vision Language Model},
  author={Chu, Xiangxiang and Qiao, Limeng and Zhang, Xinyu and Xu, Shuang and Wei, Fei and Yang, Yang and Sun, Xiaofei and Hu, Yiming and Lin, Xinyang and Zhang, Bo and others},
  journal={arXiv preprint arXiv:2402.03766},
  year={2024}
}
```


#### MoE-LLaVA: Mixture of Experts for Large Vision-Language Models (MoE-Tuning)

paper link: [here](https://arxiv.org/pdf/2401.15947)

github link: [here](https://github.com/PKU-YuanGroup/MoE-LLaVA)

model-zoo link: [here](https://github.com/PKU-YuanGroup/MoE-LLaVA?tab=readme-ov-file#-model-zoo)


citation:
```bibtex
@misc{lin2024moellava,
      title={MoE-LLaVA: Mixture of Experts for Large Vision-Language Models}, 
      author={Bin Lin and Zhenyu Tang and Yang Ye and Jiaxi Cui and Bin Zhu and Peng Jin and Jinfa Huang and Junwu Zhang and Munan Ning and Li Yuan},
      year={2024},
      eprint={2401.15947},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


#### MobileVLM: A Fast, Strong and Open Vision Language Assistant for Mobile Devices (LDP)

paper link: [here](https://arxiv.org/pdf/2312.16886)

github link: [here](ttps://github.com/Meituan-AutoML/MobileVLM)

model links:

|model name|link|
|-|-|
|MobileLLaMA-1.4B-Chat|[here](https://huggingface.co/mtgv/MobileLLaMA-1.4B-Chat)|
|MobileLLaMA-1.4B-Base|[here](https://huggingface.co/mtgv/MobileLLaMA-1.4B-Base)|

updated version: [here](https://arxiv.org/pdf/2402.03766)


citation:
```bibtex
@article{chu2023mobilevlm,
  title={Mobilevlm: A fast, reproducible and strong vision language assistant for mobile devices},
  author={Chu, Xiangxiang and Qiao, Limeng and Lin, Xinyang and Xu, Shuang and Yang, Yang and Hu, Yiming and Wei, Fei and Zhang, Xinyu and Zhang, Bo and Wei, Xiaolin and others},
  journal={arXiv preprint arXiv:2312.16886},
  year={2023}
}
```


#### CogVLM: Visual Expert for Pretrained Language Models

paper link: [here](https://arxiv.org/pdf/2311.03079.pdf)

github link: [here](https://github.com/THUDM/CogVLM)

model links: 

|model name|link|
|-|-|
|CogVLM-chat-hf|[here](https://huggingface.co/THUDM/cogvlm-chat-hf)|
|CogVLM|[here](https://huggingface.co/THUDM/CogVLM)|

citation: 
```bibtex
@misc{wang2023cogvlm,
      title={CogVLM: Visual Expert for Pretrained Language Models}, 
      author={Weihan Wang and Qingsong Lv and Wenmeng Yu and Wenyi Hong and Ji Qi and Yan Wang and Junhui Ji and Zhuoyi Yang and Lei Zhao and Xixuan Song and Jiazheng Xu and Bin Xu and Juanzi Li and Yuxiao Dong and Ming Ding and Jie Tang},
      year={2023},
      eprint={2311.03079},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


#### BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models (Q-Former)

paper link: [here](https://arxiv.org/pdf/2301.12597)

github link: [here](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)


citation:
```bibtex
@misc{li2023blip2,
      title={BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models}, 
      author={Junnan Li and Dongxu Li and Silvio Savarese and Steven Hoi},
      year={2023},
      eprint={2301.12597},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}     
```


#### Reproducible scaling laws for contrastive language-image learning (OpenCLIP)

paper link: [here](https://arxiv.org/abs/2212.07143)

blog link: [here](https://towardsdatascience.com/using-openclip-for-image-search-and-automatic-captioning-fa1cbbd48ce4)

github link: [here](https://github.com/LAION-AI/scaling-laws-openclip)

citation:
```bibtex
@misc{cherti2022reproducible,
      title={Reproducible scaling laws for contrastive language-image learning}, 
      author={Mehdi Cherti and Romain Beaumont and Ross Wightman and Mitchell Wortsman and Gabriel Ilharco and Cade Gordon and Christoph Schuhmann and Ludwig Schmidt and Jenia Jitsev},
      year={2022},
      eprint={2212.07143},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```


#### OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework

paper link: [here](https://arxiv.org/pdf/2202.03052)

github link: [here](https://github.com/OFA-Sys/OFA)

model-zoo link: [here](https://github.com/OFA-Sys/OFA/blob/main/checkpoints.md)

citation:
```bibtex
@misc{wang2022ofa,
      title={OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework}, 
      author={Peng Wang and An Yang and Rui Men and Junyang Lin and Shuai Bai and Zhikang Li and Jianxin Ma and Chang Zhou and Jingren Zhou and Hongxia Yang},
      year={2022},
      eprint={2202.03052},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```


#### Learning transferable visual models from natural language supervision (CLIP)

paper link: [here](http://proceedings.mlr.press/v139/radford21a/radford21a.pdf)

github link: [here](https://github.com/OpenAI/CLIP)

citation: 
```bibtex
@inproceedings{radford2021learning,
  title={Learning transferable visual models from natural language supervision},
  author={Radford, Alec and Kim, Jong Wook and Hallacy, Chris and Ramesh, Aditya and Goh, Gabriel and Agarwal, Sandhini and Sastry, Girish and Askell, Amanda and Mishkin, Pamela and Clark, Jack and others},
  booktitle={International conference on machine learning},
  pages={8748--8763},
  year={2021},
  organization={PMLR}
}
```


## Video-Text Alignment Pretraining

#### LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment

paper link: [here](https://arxiv.org/pdf/2310.01852)

github link: [here](https://github.com/PKU-YuanGroup/LanguageBind)

citation: 
```bibtex
@misc{zhu2024languagebind,
      title={LanguageBind: Extending Video-Language Pretraining to N-modality by Language-based Semantic Alignment}, 
      author={Bin Zhu and Bin Lin and Munan Ning and Yang Yan and Jiaxi Cui and HongFa Wang and Yatian Pang and Wenhao Jiang and Junwu Zhang and Zongwei Li and Wancai Zhang and Zhifeng Li and Wei Liu and Li Yuan},
      year={2024},
      eprint={2310.01852},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```