---
title:          "SEW: Self-calibration Enhanced Whole Slide Pathology Image Analysis"
date:           2024-12-14 00:01:00 +0800
selected:       true
pub:            "Arxiv"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  Pathology images are considered the ``gold standard" for cancer diagnosis and treatment, with gigapixel images providing extensive tissue and cellular information. Existing methods fail to simultaneously extract global structural and local detail features for comprehensive pathology image analysis efficiently. To address these limitations, we propose a self-calibration enhanced framework for whole slide pathology image analysis, comprising three components: a global branch, a focus predictor, and a detailed branch. The global branch initially classifies using the pathological thumbnail, while the focus predictor identifies relevant regions for classification based on the last layer features of the global branch. The detailed extraction branch then assesses whether the magnified regions correspond to the lesion area. Finally, a feature consistency constraint between the global and detail branches ensures that the global branch focuses on the appropriate region and extracts sufficient discriminative features for final identification. These focused discriminative features prove invaluable for uncovering novel prognostic tumor markers from the perspective of feature cluster uniqueness and tissue spatial distribution. Extensive experiment results demonstrate that the proposed framework can rapidly deliver accurate and explainable results for pathological grading and prognosis tasks.
cover: /assets/images/covers/SEW.png
authors:
  - Haoming Luo
  - Xiaotian Yu
  - Shengxuming Zhang
  - Jiabin Xia
  - Yang Jian
  - Liang Xue
  - Wenjie Liang
  - Jing Zhang
  - Xiuming Zhang
  - Mingli Song
  - Zunlei Feng
links:
  Paper: https://arxiv.org/pdf/2412.10853
  # Code: https://github.com/luost26/academic-homepage
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
