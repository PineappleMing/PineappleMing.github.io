---
title:          "Fastest Prostate Cancer Prediction on Whole-Mount Pathological Slides using Self-reform Multilayer Transformer"
date:           2025-02-04 00:01:00 +0800
selected:       true
pub:            "IEEE Access"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2025"

abstract: >-
 Objective: In the clinical diagnosis of prostate cancer (PCa), the pathological image is regarded as the ``golden standard''. Pathological images are characterized by their immense size with giga-pixel. Moreover, pixels in each whole-mount slide of PCa are increased by approximately $4\sim 9$ times, therefore containing more information for diagnosis. Therefore, rapid feature extraction of large prostate slices can effectively improve the diagnostic efficiency of prostate pathological images.
 Materials and Methods: This article introduces the self-reform multilayer transformer (SMT) to enhance acceleration of model training and inference in prostate pathological images.} The SMT workflow involves a stepwise focus among three layers, progressing from macro-scale to micro-scale. A gradient-based strategy is proposed to efficiently focus on crucial regions, and a backward rethinking strategy is also proposed to enhance the precision of former layers.
 Results: This iterative process of forward and backward training improves classification and focusing performance. Extensive experiments demonstrate that SMT achieves up to $2.71\times$ faster training and $775\times$ faster inference compared to traditional patch-cropping methods, while maintaining comparable accuracy and requiring less storage compared to existing SOTA methods.
 Discussion: The current approach of cropping each slide into patches results in extensive time and storage consumption. The SMT of this paper applies forward focusing and backward rethinking to achieve fast and accurate diagnosis of PCa. Even for samples with microcarcinoma, SMT can still focus on cancer region precisely, which has great significance for avoiding missed diagnosis in clinic.
 Conclusion: This paper indicates that most regions of pathological slides are inessential or repetitive for diagnosis. The strategy of SMT can provide a new perspective for future task on pathological images.
cover: /assets/images/covers/ieee_amt.jpeg
authors:
  - Linjie Xu
  - Haoming Luo
  - Xiaotian Yu
  - Jili Wang
  - Wenjie Liang 
  - Jing Zhang 
  - Zunlei Feng 
  - Cheng Lu 
  - Xiuming Zhang
links:
  Paper: https://ieeexplore.ieee.org/document/10949171
  # Code: https://github.com/PineappleMing/AMT-WSI
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
