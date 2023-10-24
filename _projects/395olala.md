---
layout: project
show_nav: true

title: OLALA
description: >
    Shen, Zejiang, Jian Zhao, Yaoliang Yu, Weining Li, and Melissa Dell. “OLALA: Object-Level Active Learning Based Layout Annotation." *EMNLP Computational Social Science Workshop* (2023). [Paper](https://scholar.harvard.edu/files/dell/files/nlpcss_1.pdf); [Code](https://github.com/lolipopshock/detectron2_al)
keywords: document image analysis, annotation, active learning
image_small: /assets/publications/olala.png

---



**Abstract:** Layout detection is an essential step for accurately extracting structured contents from historical documents. The intricate and varied layouts present in these document images make it expensive to label the numerous layout regions that can be densely arranged on each page. Current active learning methods typically rank and label samples at the image level, where the annotation budget is not optimally spent due to the overexposure of common objects per image. Inspired by recent progress in semi-supervised learning and self-training, we propose Olala, an Object-Level Active Learning framework for efficient document layout Annotation. Olala aims to optimize the annotation process by selectively annotating only the most ambiguous regions within an image, while using automatically generated labels for the rest. Central to Olala is a perturbation-based scoring function that determines which objects require manual annotation. Extensive experiments show that Olala can significantly boost model performance and improve annotation efficiency, facilitating the extraction of masses of structured text for downstream NLP applications.

[Paper](https://scholar.harvard.edu/files/dell/files/nlpcss_1.pdf)

[Code](https://github.com/lolipopshock/detectron2_al)