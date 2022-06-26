---
layout: single
read_time: false
comments: false
share: false
author_profile: true
title: <br><br><br><br><br>Publications
permalink: /publications/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/publication.jpg
  caption: "Photo: [Poseidon](https://uceap.universityofcalifornia.edu/programs/university-bologna)"
---

## Publications

For a complete list of publications, please refer to <a href="https://scholar.google.co.uk/citations?hl=zh-CN&user=qLiVWVwAAAAJ" itemprop="sameAs"><i class="ai ai-fw ai-google-scholar-square" aria-hidden="true"></i>Google Scholar</a>.

---

## Conference

<!--
### 2022

> <small>
    <b>CompletionFormer: Learning Depth Completion with Convolution and Vision Transformer</b> <br>
    <b>Youmin Zhang</b>, Xianda Guo, Matteo Poggi, Zheng Zhu, Guan Huang, Stefano Mattoccia. <br>
    Arxiv (<b>Arxiv</b>), 2021.<br>
    [<a style="color:grey;cursor: pointer; cursor: hand;" onclick="toggle_visibility('abstract_adagm');">Abstract</a>]
    [<a href="" style="color:green">Arxiv</a>]
    [<a href="https://youmi-zym.github.io/media/papers/2022-Arxiv-CompletionFormer.pdf" style="color:green">PDF</a>]
    [<a href="https://github.com/youmi-zym/CompletionFormer" style="color:green">Code</a>]
    [<a style="color:grey;cursor: pointer; cursor: hand;" onclick="toggle_visibility('bibtex_AdaGM');">Bibtex</a>]

-->

### 2021

> <small>
    <b>Adaptive Beam Search Decoding for Discrete Keyphrase Generation</b> <br>
    Xiaoli Huang, Tongge Xu, Lvan Jiao, Yueran Zu, <b>Youmin Zhang</b>. <br>
    Proceedings of the AAAI Conference on Artificial Intelligence (<b>AAAI</b>), 2021.<br>
    [<a style="color:grey;cursor: pointer; cursor: hand;" onclick="toggle_visibility('abstract_adagm');">Abstract</a>]
    [<a href="https://www.aaai.org/AAAI21Papers/AAAI-8780.HuangXL.pdf" style="color:green">Arxiv</a>]
    [<a href="https://youmi-zym.github.io/media/papers/2021-AAAI-AdaGM.pdf" style="color:green">PDF</a>]
    [<a href="https://github.com/huangxiaolist/adaGM" style="color:green">Code</a>]
    [<a style="color:grey;cursor: pointer; cursor: hand;" onclick="toggle_visibility('bibtex_AdaGM');">Bibtex</a>]


> <small>
    <b>HMFlow: Hybrid Matching Optical Flow Network for Small and Fast-Moving Objects</b> <br>
    Suihanjin Yu, <b>Youmin Zhang</b>, Chen Wang, Xiao Bai, Liang Zhang, Edwin R Hancock. <br>
    Proceedings of 25th International Conference on Pattern Recognition (<b>ICPR</b>), 2021. <br>
    [<a style="color:grey;cursor: pointer; cursor: hand;" onclick="toggle_visibility('abstract_hmflow');">Abstract</a>]
    [<a href="https://arxiv.org/abs/2011.09654" style="color:green">Arxiv</a>]
    [<a href="https://youmi-zym.github.io/media/papers/2021-ICPR-HMFlow.pdf" style="color:green">PDF</a>]
    [<a href="" style="color:grey">Code</a>]
    [<a style="color:grey;cursor: pointer; cursor: hand;" onclick="toggle_visibility('bibtex_AdaGM');">Bibtex</a>]

### 2020

> <small>
    <b>Adaptive unimodal cost volume filtering for deep stereo matching</b> <br>
    <b>Youmin Zhang</b>, <a href="https://minwellcym.github.io/" style="color:green"><ins>Yimin Chen*</ins></a>, Xiao Bai, Suihanjin Yu, Kun Yu, Zhiwei Li, <a href="https://sites.google.com/site/kuiyuanyang/" style="color:green"><ins>Kuiyuan Yang</ins></a>. <br>
    Proceedings of the AAAI Conference on Artificial Intelligence (<b>AAAI</b>), 2020.<br>
    <img src='/assets/images/acfnet_architecture.png' alt="network" width="98%"> <br>
    [<a href="https://arxiv.org/abs/1909.03751v2" style="color:green">Arxiv</a>]
    [<a href="https://youmi-zym.github.io/media/papers/2020-AAAI-AcfNet.pdf" style="color:green">PDF</a>]
    [<a href="https://github.com/DeepMotionAIResearch/DenseMatchingBenchmark" style="color:green">Code</a>]
    [<a style="color:green;cursor: pointer; cursor: hand;" onclick="toggle_visibility('bibtex_acfnet');">Bibtex</a>]
</small>
<div id="bibtex_acfnet" style="display:none;">
<small><div class="highlighter-rouge"><pre class="highlight">
<code>@inproceedings{zhang2020adaptive,
  title={Adaptive unimodal cost volume filtering for deep stereo matching},
  author={Zhang, Youmin and Chen, Yimin and Bai, Xiao and Yu, Suihanjin and Yu, Kun and Li, Zhiwei and Yang, Kuiyuan},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={34},
  number={07},
  pages={12926--12934},
  year={2020}
}
</code></pre></div></small>
</div>

<!--
[<a style="color:green;cursor: pointer; cursor: hand;" onclick="toggle_visibility('abstract_acfnet');">Abstract</a>]
<div id="abstract_acfnet" >
<img src='/assets/images/acfnet_architecture.png' alt="network" width="70%">
</div>
<div id="abstract_acfnet" style="display:none;">
<small><div class="highlighter-rouge"><table style="width:100%"><pre class="highlight"><p style="text-align:justify;font-family:courier;">
    State-of-the-art deep learning based stereo matching approaches treat disparity estimation as a regression problem, where loss function is directly defined on true disparities and their estimated ones. However, disparity is just a byproduct of a matching process modeled by cost volume, while indirectly learning cost volume driven by disparity regression is prone to overfitting since the cost volume is under constrained. In this paper, we propose to directly add constraints to the cost volume by filtering cost volume with unimodal distribution peaked at true disparities. In addition, variances of the unimodal distributions for each pixel are estimated to explicitly model matching uncertainty under different contexts. The proposed architecture achieves state-of-the-art performance on Scene Flow and two KITTI stereo benchmarks. In particular, our method ranked the 1 st place of KITTI 2012 evaluation and the 4 th place of KITTI 2015 evaluation (recorded on 2019.8. 20). The codes of AcfNet are available at: https://github. com/youmi-zym/AcfNet.
</p></pre></table></div></small>
<p align="center">
  <a href="">
    <img src="./assets/images/acfnet_architecture.png" alt="Logo" width="98%">
  </a>
</p>
</div>
-->


<script type="text/javascript">
   function toggle_visibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
</script>	
