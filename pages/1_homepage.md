---
layout: page
title: Jinfan Hu
comments: true
permalink: /homepage/
---

* content
{:toc}

<style>
.biblist { }

/* The item */
.biblist li { }

/* You can define custom styles for plstyle field here. */


/*************************************
   The box that contain BibTeX code
 *************************************/
div.noshow { display: none; }
div.BibTeX {
  margin-right: 1%;
  margin-left: 3%;
  margin-top: 1.2em;
  margin-bottom: 1.3em;
  border: 1px solid silver;
  padding: 0.3em 0.5em;
  background: #eeeeee;
}
div.BibTeX pre { font-size: 85%; overflow: auto;  width: 100%; }
</style>

<script>
function toggleBibtex(articleid) {
  var bib = document.getElementById('bib_'+articleid);
  if (bib) {
    if(bib.className.indexOf('BibTeX') != -1) {
    bib.className.indexOf('noshow') == -1?bib.className = 'BibTeX noshow':bib.className = 'BibTeX';
    }
  } else {
    return;
  }
}
</script>



	
### 📚 Biography
 
| <br>**Jinfan Hu** is pursuing his Ph.D. degree in [XPixel Group](http://xpixel.group/index.html), Shenzhen Institute of Advanced Technology ([SIAT](https://www.siat.ac.cn/)), Chinese Academy of Sciences ([CAS](https://english.cas.cn/index.shtml)). He is now supervised by Prof. [Chao Dong](http://xpixel.group/2010/01/20/chaodong.html). He obtained his Bachelor and Master degrees in Mathematics (supervised by Prof. [Ting-Zhu Huang](http://www.math.uestc.edu.cn/info/1081/2041.htm) and Prof. [Liang-Jian Deng](https://liangjiandeng.github.io/)) from the University of Electronic Science and Technology of China ([UESTC](https://www.uestc.edu.cn/)), Chengdu, China in 2019 and 2022. His research interests include low-level vision (LV) and AI interpretability. <br> <br> **Email:** <jf.hu1@siat.ac.cn> <br> **Follow Me:** [Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=hT-EiJEAAAAJ) &emsp; [Github](https://github.com/J-FHu) <br><br> |&emsp;![image](https://J-FHu.github.io/images/Hu.jpg)&emsp;|

### 🔥 Headlines

* [02/2025] 🎉🎉🎉 We revisit the generalization problem of low-level vision models in this [paper](https://arxiv.org/abs/2502.12600). We demonstrate that the common strategy of blindly expanding the training set is ineffective. Instead, the key to better generalization lies in guiding the network to learn the image content rather than the degradation! 
  <div style="text-align: center;">
    <img src="https://J-FHu.github.io/images/Real_compare.png" width="700px">
  </div>

* [02/2025] 🎉🎉🎉 The book [《底层视觉之美》](https://item.jd.com/10137558708716.html), co-authored with my supervisor Prof. Chao Dong, has been published. We hope this book provides valuable insights for researchers and enthusiasts in the field!
  <div style="text-align: center;">
    <img src="https://J-FHu.github.io/images/Book.png" width="400px">
  </div>

* [07/2024] 🎉🎉🎉 We propose a model/task-agnostic interpreting method ([CEM](https://arxiv.org/abs/2407.19789)) for low-level vision models, bringing causality analysis into the field. We hope this work contributes to a deeper understanding and enhancement of low-level vision models! 
  <div style="text-align: center;">
    <img src="https://J-FHu.github.io/images/teaser_CEM.png" width="700px">
  </div>

* [01/2024] 🎉🎉🎉 We release a groundbreaking image restoration method ([SUPIR](https://supir.xpixel.group/)) that harnesses generative prior and the power of model scaling up. We believe this method will provide valuable insights and improved performance for real-world image restoration tasks!
  <div style="text-align: center;">
    <img src="https://J-FHu.github.io/images/teaser.png" width="700px">
  </div>



---

### 📝 Publications

_**Book**_

* C. Dong, **J. Hu**, [《底层视觉之美》](https://item.jd.com/10137558708716.html) (The Beauty of Low-level Vision), 2025.

_**Paper**_
* **J. Hu<sup>\*</sup>**,  Z. You<sup>\*</sup>, J. Gu, K. Zhu, T. Xue, C. Dong. Revisiting the Generalization Problem of Low-level Vision Models Through the Lens of Image Deraining. arXiv, 2025. [[PDF](https://arxiv.org/abs/2502.12600)]
  
* **J. Hu**, J. Gu, S. Yao, F. Yu, Z. Li, Z. You, C. Lu, C. Dong. Interpreting Low-level Vision Models with Causal Effect Maps. arXiv, 2024. [[Code](https://github.com/J-FHu/CEM)][[PDF](https://arxiv.org/abs/2407.19789)]

* F. Yu, J. Gu, Z. Li, **J. Hu**, X. Kong, X. Wang, J. He, Y. Qiao, and C. Dong. Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild. **_Conference on Computer Vision and Pattern Recognition (CVPR)_**, 2024. [[Project Page](https://supir.xpixel.group/)][[PDF](https://arxiv.org/abs/2401.13627)]
  
* R. Ran, L.-J. Deng, T.-X. Jiang, **J.-F. Hu**, J. Chanussot, and G. Vivone. GuidedNet: A General CNN Fusion Framework via High-resolution Guidance for Hyperspectral Image Super-resolution. **_IEEE Transactions on Cybernetics (TCYB)_**, 2023. (<span style="color:red">ESI Highly Cited</span>) [[Code](https://github.com/Evangelion09/GuidedNet)][[PDF](https://ieeexplore.ieee.org/abstract/document/10035506/)]

* X. Liu<sup>\*</sup>, **J. Hu<sup>\*</sup>**, X. Chen, and C. Dong. UDC-UNet: Under-Display Camera Image Restoration via U-shape Dynamic Network. **_European Conference on Computer Vision Workshop (ECCVW)_**, 2022. [[Code](https://github.com/J-FHu/UDCUNet)][[PDF](https://link.springer.com/chapter/10.1007/978-3-031-25072-9_8)]

* Y.-W. Zhuo, T.-J. Zhang, **J.-F. Hu**, H.-X. Dou, T.-Z. Huang, and L.-J. Deng. Hyper-DSNet: Hyperspectral Pansharpening via A Deep-Shallow Fusion Network with Multi-Detail Extractor and Spectral Attention. **_IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing_**, 2022. [[PDF](https://ieeexplore.ieee.org/abstract/document/9870551)]


* **J.-F. Hu**, T.-Z. Huang, L.-J. Deng, H.-X. Dou, D. Hong, and G. Vivone. Fusformer: A Transformer-based Fusion Approach for Hyperspectral Image Super-resolution. **_IEEE Geoscience and Remote Sensing Letters_**, 2022. (<span style="color:red">ESI Highly Cited</span>) [[Code](https://github.com/J-FHu/Fusformer)][[PDF](https://ieeexplore.ieee.org/abstract/document/9841513)]

* S. Peng, L.-J. Deng, **J.-F. Hu**, and Y.-W. Zhuo. Source-Adaptive Discriminative Kernels based Network for Remote Sensing Pansharpening. **_International Joint Conferences on Artificial Intelligence (IJCAI)_**, 2022. [[Code](https://github.com/liangjiandeng/ADKNet)][[PDF](https://pluto-wei.github.io/papers/2022/peng-ijcai2022.pdf)]

* **J.-F. Hu**, T.-Z. Huang, L.-J. Deng, T.-X. Jiang, G. Vivone, and J. Chanussot. Hyperspectral Image Super-Resolution via Deep Spatiospectral Attention Convolutional Neural Networks. **_IEEE Transactions on Neural Networks and Learning Systems (TNNLS)_**, 2021. (<span style="color:red">ESI Highly Cited</span>) [[Project Page](https://liangjiandeng.github.io/Projects_Res/HSRnet_2021tnnls.html)][[PDF](https://liangjiandeng.github.io/papers/2021/HSRnet_tnnls_2021.pdf)]

* T. Xu, T.-Z. Huang, L.-J. Deng, X.-L Zhao, and **J.-F. Hu**. Exemplar-based Image Inpainting Using Adaptive Two-Stage Structure-Tensor Based Priority Function and Nonlocal Filtering. **_Journal of Visual Communication and Image Representation_**, 2021. [[PDF](https://www.sciencedirect.com/science/article/abs/pii/S1047320321002893)]

* Z.-C. Wu, T.-Z. Huang, L.-J. Deng, **J.-F. Hu**, and G. Vivone. VO+ Net: An Adaptive Approach Using Variational Optimization and Deep Learning for Panchromatic Sharpening. **_IEEE Transactions on Geoscience and Remote Sensing (TGRS)_**, 2021. [[Project page](https://liangjiandeng.github.io/Projects_Res/VOFF_2021tgrs.html)][[PDF](https://liangjiandeng.github.io/papers/2021/VOFF.pdf)]

* Z.-C. Wu, T.-Z. Huang, L.-J. Deng, G. Vivone, J.-Q Miao, **J.-F. Hu**, and X.-L Zhao. A New Variational Approach Based on Proximal Deep Injection and Gradient Intensity Similarity for Spatio-Spectral Image Fusion. **_IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing_**, 2020. [[Project page](https://liangjiandeng.github.io/Projects_Res/DMPIF_2020jstars.html)][[PDF](https://liangjiandeng.github.io/papers/2020/dmpif_2020jstars.pdf)]

<p align="left">
<small>(<sup>*</sup> Equal contributions)</small>
</p>


---

### 📖 Experiences 

* 09/2022-present: Ph.D. student in computer science. (Supervisor: Prof. [Chao Dong](http://xpixel.group/2010/01/20/chaodong.html)); Shenzhen Institute of Advanced Technology ([SIAT](https://www.siat.ac.cn/)), University of Chinese Academy of Sciences ([UCAS](https://www.ucas.ac.cn/))

* 09/2019-06/2022: Master student in mathematics. (Supervisor: Prof. [Ting-Zhu Huang](http://www.math.uestc.edu.cn/info/1081/2041.htm) and Prof. [Liang-Jian Deng](https://liangjiandeng.github.io/)); University of Electronic Science and Technology of China ([UESTC](https://www.uestc.edu.cn/))

* 09/2015-06/2019: Bachelor student in information and computing science; University of Electronic Science and Technology of China ([UESTC](https://www.uestc.edu.cn/))

---

### 🏆 Honors and Awards
* 2nd Place in ECCV [MIPI 2022 Challenge](http://mipi-challenge.org/) on UDC image restoration, 2022

* National Scholarship, 2021

<!-- * Academic Scholarship, 2020 and 2021 -->

* National First Prize of [CUMCM](http://www.mcm.edu.cn/), 2017

<!-- * People Scholarship, 2017 and 2018  -->

---

### 💬 Academic Activities

Peer-Reviewer: 
* IEEE Transactions on Pattern Analysis and Machine Intelligence

* IEEE Transactions on Cybernetics
  
* IEEE Transactions on Geoscience And Remote Sensing

* IEEE Geoscience and Remote Sensing Letters

* IEEE Transactions on Computational Imaging
* ...
  
---

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=300&t=tt&d=5Tnjvlx4pwYiXFQMdiOgvLHFKUuOMdlwnkZD9DMfS6c'></script>


<!DOCTYPE html>
<html>
<head>
    <style>
        .float-box {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 50px;
            height: 50px;
            cursor: pointer;
            z-index: 1000;
            /* 移除动画相关代码 */
        }

        .close-btn {
            position: absolute;
            top: -6px;
            right: -6px;
            width: 18px;
            height: 18px;
            background: #ff4444;
            border-radius: 50%;
            color: white;
            text-align: center;
            line-height: 18px;
            font-size: 12px;
            font-family: Arial;
            cursor: pointer;
            z-index: 1001;
            transition: background 0.3s;
        }

        .close-btn:hover {
            background: #cc0000;
        }

        .float-image {
            width: 100%;
            height: 100%;
            border-radius: 4px;
            box-shadow: 0 0 8px rgba(0,0,0,0.2);
            transition: transform 0.3s;
        }

        .float-image:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="float-box" id="floatBox">
        <div class="close-btn" id="closeBtn">×</div>
        <a href="https://item.jd.com/10137558708716.html" target="_blank">
            <img src="https://J-FHu.github.io/images/icon.png" 
                 alt="京东商品" 
                 class="float-image">
        </a>
    </div>

    <script>
        document.getElementById('closeBtn').addEventListener('click', function(e) {
            e.stopPropagation();
            document.getElementById('floatBox').style.display = 'none';
        });
    </script>
</body>
</html>
