---
layout: project
show_nav: true

title: Multi-modal Record linkage
description: >
    Noisy OCR can lead to poor linkage performance. Introducing an image-text pipeline that uses visual information for record-linkage as a means to bypass poor OCR 
    [Paper](https://scholar.harvard.edu/sites/scholar.harvard.edu/files/dell/files/rl.pdf) 
    [Repo (Historic Japanese Linkage)](https://github.com/dell-research-harvard/clippings-japanese)
keywords: multimodal learning, contrastive learning, record linkage
image_small: /assets/publications/rl.png


---



**Abstract:** Many applications require grouping instances contained in diverse document datasets into classes. Most widely used methods do not employ deep learning and do not exploit the inherently multimodal nature of documents. Notably, record linkage is typically conceptualized as a string-matching problem. This study develops CLIPPINGS, (Contrastively Linking Pooled Pre-trained Embeddings), a multimodal framework for record linkage. CLIPPINGS employs end-to-end training of symmetric vision and language bi-encoders, aligned through contrastive language-image pre-training, to learn a metric space where the pooled image-text representation for a given instance is close to representations in the same class and distant from representations in different classes. At inference time, instances can be linked by retrieving their nearest neighbor from an offline exemplar embedding index or by clustering their representations. The study examines two challenging applications: constructing comprehensive supply chains for mid-20th century Japan through linking firm level financial records - with each firm name represented by its crop in the document image and the corresponding OCR - and detecting which image-caption pairs in a massive corpus of historical U.S. newspapers came from the same underlying photo wire source. CLIPPINGS outperforms widely used string matching methods by a wide margin and also outperforms unimodal methods. Moreover, a purely self-supervised model trained on only image-OCR pairs also outperforms popular string-matching methods without requiring any labels. 

[Paper](https://scholar.harvard.edu/sites/scholar.harvard.edu/files/dell/files/rl.pdf)
[Repo (Historic Japanese Linkage)](https://github.com/dell-research-harvard/clippings-japanese)