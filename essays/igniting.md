---
layout: essay
type: essay
title: "[COLING 2024] Awareness of Time: Video-Language Models Embedding with Temporal Reasoning"
# All dates must be YYYY-MM-DD format!
date: 2023-10-25
published: true
labels:
  - Paper
  - Pre-trained language model
  - Video-language model
  - multimode
---
Video-language pre-training has significantly improved the performance of diverse downstream tasks related to video and language. However, existing approaches often directly adapt image-language pre-training paradigms to video-language tasks, neglecting the unique temporal characteristics of videos. In this paper, we present a novel temporal-aware video-language pre-training framework. It introduces two innovative pre-training tasks to enhance temporal-awareness in multi-modal representations, incorporating fine-grained temporal moment information and temporal contextual relations between video-text pairs. Firstly, we propose a cross-modal moment exploration task, leveraging paired texts to uncover detailed video moment representations. Subsequently, using the acquired moment representations, we capture inherent temporal contextual relations by aligning video-text pairs across different time resolutions in a multi-modal temporal relation exploration task. Additionally, we introduce a shuffling test to assess the temporal reliance of datasets and the efficacy of video-language pre-training. This framework aims to fully exploit the temporal dimension in video data for more effective pre-training and improved downstream task performance.
