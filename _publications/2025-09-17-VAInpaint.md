---
title: "VAINPAINT: ZERO-SHOT VIDEO-AUDIO INPAINTING FRAMEWORK WITH LLMS-DRIVEN MODULE"
collection: publications
category: conferences
permalink: /publication/2025-09-17-VAInpaint
excerpt: 'This paper is about fixing template issue #693.'
date: 2025-09-17
venue: 'ICASSP 2026 (Under Review)'
paperurl: 'http://academicpages.github.io/files/VAInpaint.pdf'
citation: 'Wu, Kam Man, Zeyue Tian, Liya Ji, and Qifeng Chen. (2025). &quot;VAInpaint: Zero-Shot Video-Audio inpainting framework with LLMs-driven Module.&quot; <i>arXiv preprint arXiv:2509.17022</i>.'
---

Video and audio inpainting for mixed audio-visual content has become a crucial task in multimedia editing recently. However, precisely removing an object and its corresponding audio from a video without affecting the rest of the scene remains a significant challenge. To address this, we propose VAInpaint, a novel pipeline that first utilizes a segmentation model to generate masks and guide a video inpainting model in removing objects. At the same time, an LLM then analyzes the scene globally, while a region-specific model provides localized descriptions. Both the overall and regional descriptions will be inputted into an LLM, which will refine the content and turn it into text queries for our text-driven audio separation model. Our audio separation model is fine-tuned on a customized dataset comprising segmented MUSIC instrument images and VGGSound backgrounds to enhance its generalization performance. Experiments show that our method achieves performance comparable to current benchmarks in both audio and video inpainting.
