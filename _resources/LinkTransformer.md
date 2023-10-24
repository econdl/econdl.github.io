---
layout: post
title: LinkTransformer
description: A Unified Python Package for Record Linkage with Transformer Models
category: software
image_small: /assets/publications/lt_image.png
website: https://linktransformer.github.io/
paper: https://scholar.harvard.edu/sites/scholar.harvard.edu/files/dell/files/linkt.pdf
---

![](/assets/projects/lt_logo.png)

Introducing LinkTransformer: LinkTransformer brings the advantages of AI to standard data frame manipulation tasks like merges, deduplication, and clustering, making it easy to use large language models in a standard data wrangling workflow. 

[Webpage](https://linktransformer.github.io/)

 [Paper](https://scholar.harvard.edu/sites/scholar.harvard.edu/files/dell/files/linkt.pdf)

 [Github](https://github.com/dell-research-harvard/linktransformer)

[Intoductory Notebook](https://colab.research.google.com/drive/1SAvQdgYiX2CinoTC8Y5qtKScNwx3DYXf#scrollTo=jR0-0I6jPm2S)

[Inference Deep-Dive](https://colab.research.google.com/drive/1OqUB8sqpUvrnC8oa_1RoOUzV6DaAKL4N)

[Training Deep-Dive]([ttps://colab.research.google.com/drive/1tHitPGjMMI2Nvh4wwA8rdcbYfbLaJDvg](https://colab.research.google.com/drive/1tHitPGjMMI2Nvh4wwA8rdcbYfbLaJDvg))

Merge with transformer language models like you would in Pandas. The API is designed to be as simple as possible and very familiar to practitioners coming from other environments like R and Stata. 

![](/assets/projects/lt_image.png)

LinkTransformer supports all models on the Hugging Face Hub and OpenAI Embedding models. We’ve also trained our own collection of over 20 open-source language models for different languages and tasks. A guide to selecting models is [here](https://colab.research.google.com/drive/1SAvQdgYiX2CinoTC8Y5qtKScNwx3DYXf#scrollTo=jR0-0I6jPm2S)

LinkTransformer supports a wide range of data wrangling tasks with transformers: standard merging, merge with blocking or multiple keys, cross-lingual merges (no need to translate), 1-m and m-m merges, aggregation/classification, clustering and de-duplication. [Examples](https://colab.research.google.com/drive/1OqUB8sqpUvrnC8oa_1RoOUzV6DaAKL4N)

Training your own models is as easy as one line of code, with most of the heavy lifting done behind the scenes.  You can fine-tune any pretrained model from Hugging Face. Learn more at our [repo](https://github.com/dell-research-harvard/linktransformer) and [demo notebook]([ttps://colab.research.google.com/drive/1tHitPGjMMI2Nvh4wwA8rdcbYfbLaJDvg](https://colab.research.google.com/drive/1tHitPGjMMI2Nvh4wwA8rdcbYfbLaJDvg))

 ![](/assets/projects/train.png)

LinkTransformer aims to create a community for deep record linkage, streamlining the distribution of record linkage models and promoting the reusability and reproducibility of pipelines.  Users can tag and share their models on the Hugging Face hub with a single line of code. 

![](/assets/projects/hub.png)

This is our initial release, and we welcome feedback via Github. Planned features for the next release include integrating vision transformer models for visual record linkage (forgo OCR altogether!) and FAISS GPU support. 

If you find LinkTransformer useful, please cite it and consider starring our repo  [repo](https://github.com/dell-research-harvard/linktransformer). We funded LT out of the PI’s very limited unrestricted funds, and to maintain/expand we need to show potential funders that it is having a positive impact on the community!