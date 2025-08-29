
---
title: "D3FNet: A Differential Attention Fusion Network for Fine-Grained Road Structure Extraction in Remote Perception Systems"
collection: publications
category: conferences
permalink: /publication/Conference
excerpt: ''
date: 2025-10
venue: 'International Conference on Computer Vision, ICCV 2025 (DriveX) paper id 5'
paperurl: ''
citation: 'Chang Liu, Yang Xu, Tamas Sziranyi. (2025). &quot; D3FNet: A Differential Attention Fusion Network for Fine-Grained Road Structure Extraction in Remote Perception Systems.&quot; <i>International Conference on Computer Vision </i>.ICCV 2025.'
---

Extracting narrow roads from high-resolution remote sensing imagery remains a significant challenge due to their limited width, fragmented topology, and frequent occlusions. To address these issues, we propose D3FNet, a Dilated Dual-Stream Differential Attention Fusion Network designed for fine-grained road structure segmentation in remote perception systems. Built upon the encoder-decoder backbone of D-LinkNet, D3FNet introduces three key innovations:(1) a Differential Attention Dilation Extraction (DADE) module that enhances subtle road features while suppressing background noise at the bottleneck; (2) a Dual-stream Decoding Fusion Mechanism (DDFM) that integrates original and attention-modulated features to balance spatial precision with semantic context; and (3) a multi-scale dilation strategy (rates 1, 3, 5, 9) that mitigates gridding artifacts and improves continuity in narrow road prediction. Unlike conventional models that overfit to generic road widths, D3FNet specifically targets fine-grained, occluded, and low-contrast road segments. Extensive experiments on the DeepGlobe and CHN6-CUG benchmarks show that D3FNet achieves superior IoU and recall on challenging road regions, outperforming state-of-the-art baselines. Ablation studies further verify the complementary synergy of attention-guided encoding and dual-path decoding. These results confirm D3FNet as a robust solution for fine-grained narrow road extraction in complex remote and cooperative perception scenarios.
