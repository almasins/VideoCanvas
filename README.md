# VideoCanvas: Unified Video Completion from Arbitrary Spatiotemporal Patches via In-Context Conditioning



**[Minghong Cai<sup>1 &dagger;</sup>](https://onevfall.github.io/personal_page/), 
[Qiulin Wang<sup>2 &#9993;</sup>](https://openreview.net/profile?id=~Qiulin_Wang1), 
[Zongli Ye<sup>1</sup>](https://scholar.google.com/citations?user=iD1EoKMAAAAJ&hl=en), 
[Wenze Liu<sup>1</sup>](https://openreview.net/profile?id=~Wenze_Liu1), 
[Quande Liu<sup>2</sup>](https://liuquande.github.io/), 
[Weicai Ye<sup>2</sup>](https://ywcmaike.github.io/), 
[Xintao Wang<sup>2</sup>](https://xinntao.github.io/), 
[Pengfei Wan<sup>2</sup>](https://scholar.google.com/citations?user=P6MraaYAAAAJ&hl=en), 
[Kun Gai<sup>2</sup>](https://scholar.google.com/citations?user=PXO4ygEAAAAJ&hl=zh-CN), 
[Xiangyu Yue<sup>1 &#9993;</sup>](https://xyue.io/)**
<br>
<sup>1</sup>MMLab, The Chinese University of Hong Kong
<sup>2</sup>Kling Team, Kuaishou Technology
<br>
&dagger;: Intern at Kuaishou Technology, &#9993;: Corresponding Authors

<a href='https://arxiv.org/abs/2510.08555'><img src='https://img.shields.io/badge/ArXiv-2510.08555-red'></a> 
<a href='https://onevfall.github.io/project_page/videocanvas/#'><img src='https://img.shields.io/badge/Project-Page-Green'></a>





## 📋 News
- [2025.10.9] Release Arxiv paper.


## 📖 Introduction
VideoCanvas has two key contributions:
- 🎯 Unified Tasks: VideoCanvas introduces a unified paradigm for arbitrary spatio-temporal video generation, seamlessly integrating diverse capabilities including image/patch-to-video conditioning at any timestamp, inpainting/outpainting, camera control, scene transitions, and video extension.
- 🛠️ Simple Solution: Our technical innovation leverages In-Context Conditioning with zero-padding for spatial control and Temporal RoPE Interpolation for temporal alignment, achieving frame-precise video generation without fine-tuning VAEs or adding parameters. <br>


<div>
  <video controls autoplay loop muted playsinline width="100%">
    <source src="https://github.com/KwaiVGI/VideoCanvas/raw/main/assets/teaser.mp4" type="video/mp4">
  </video>
</div>


## 📖 VideoCanvasBench

We will release this benchmark, including intra-scene and inter-scene evaluation data.

## ⚙️ Code (Coming soon)


## Citation

```bibtex
 @article{cai2025videocanvas,
    title={VideoCanvas: Unified Video Completion from Arbitrary Spatiotemporal Patches via In-Context Conditioning},
    author={Minghong Cai, Qiulin Wang, Zongli Ye, Wenze Liu, Quande Liu, Weicai Ye, Xintao Wang, Pengfei Wan, Kun Gai, Xiangyu Yue},
    journal={arXiv preprint arXiv:2510.08555},
    year={2025}
}