---
title:          "Hundredfold accelerating for pathological images diagnosis and prognosis through self-reform critical region focusing"
date:           2024-08-16 00:01:00 +0800
selected:       true
pub:            "33rd Int. Joint Conf. on Artificial Intelligence (IJCAI2024)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  Pathological slides are commonly gigapixel images with abundant information and are therefore significant for clinical diagnosis. However, the ultralarge size makes both training and evaluation extremely time-consuming. Most existing methods need to crop the slide into patches, which also leads to large memory requirements. In this paper, we propose the Self-reform Multilayer Transformer (SMT) to accelerate the pathological image diagnosis and prognosis. Inspired by the pathologists’ diagnostic procedure, SMT is designed to achieve layer-by-layer focus on critical regions. In the forward process, the first layer takes thumbnails as inputs and measures the significance of each patch that deserves focusing. Images from focused regions are cropped with a higher magnification and used as the input of the next layer. By analogy, the third layer inputs are focused images of second layer, which contain abundant cellular features. In addition to the forward focusing, the backward reform strategy is proposed to improve the precision of former layers. This cyclic process achieves iterative interactions for better performance on both classification and focusing. In this way, only a small part of critical patches are required in SMT for diagnosis and prognosis. Sufficient experiments demonstrate that SMT achieves hundreds times faster speed, while achieving comparable accuracy and less storage compared with existing SOTA methods.
cover: /assets/images/covers/AMT.png
authors:
  - Xiaotian Yu
  - Haoming Luo
  - Jiacong Hu
  - Xiuming Zhang
  - Yuexuan Wang
  - Wenjie Liang
  - Yijun Bei
  - Mingli Song
  - Zunlei Feng
links:
  Paper: https://www.ijcai.org/proceedings/2024/0178.pdf
  Code: https://github.com/PineappleMing/AMT-WSI
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
