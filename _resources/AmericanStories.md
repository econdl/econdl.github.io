---
layout: post
title: American Stories
description: A Billion Scale Dataset of Structured Texts and Layouts from U.S. Public Domain Newspapers
category: datasets
image_small: /assets/publications/as_layouts.png
website: https://huggingface.co/datasets/dell-research-harvard/AmericanStories
paper: https://arxiv.org/abs/2308.12477
---

Introducing American Stories, a new billion-scale dataset of structured texts/layouts from public domain newspapers (1780-1960) that we’ve built using our deep learning packages. 

 [Dataset](https://huggingface.co/datasets/dell-research-harvard/AmericanStories)

 [Paper](https://arxiv.org/abs/2308.12477)

 [Github](https://github.com/dell-research-harvard/americanstories)

We detect 1.14 billion individual content regions in around 20M newspaper scans from Library of Congress’s Chronicling America collection. Headlines, articles, bylines, and captions are custom-OCRed. The dataset contains 438 million structured article texts. 

![](/assets/projects/as_layouts.png) 

It covers all 50 states, with content concentrated pre-1920. 

![](/assets/projects/ca_map.png)

The pipeline is highly efficient to deploy and has been [open-sourced](https://github.com/dell-research-harvard/americanstories). We’ve also created open-source packages – LayoutParser and EfficientOCR – to help researchers develop similar pipelines for their own document collections.  

The existing Chronicling America OCR from Library of Congress doesn’t recognize layouts, scrambling articles, headlines, ads, etc. American Stories significantly improves accuracy on text classification (allowing it at the article level) and on detecting reproduced content.

![](/assets/projects/as_results.png)

Structured article texts also support analyses that are impossible with existing page level texts. We detect the biggest stories of the year, using a custom trained large language model to embed texts and then applying clustering to group articles into coherent stories.

![](/assets/projects/stories.png)

Another distinguishing feature of American Stories: after detecting text regions (articles, headlines, captions, bylines), we classify whether they are legible.

![](/assets/projects/illeg_ex.png)

This is important because there are lots of illegible scans, with illegibility varying across space and time. Illegibility could bias analyses if researchers include illegible content in the denominator when measuring the presence of different terms or textual features. 

![](/assets/projects/illeg_map.png)

Our texts are high quality. This figure compares the non-word rate in our custom OCR to the Library of Congress OCR. Differences are due to a combination of our high-quality custom-OCR and filtering of illegible content and ads before OCRing. 

![](/assets/projects/nwr_compare.png)

Interested in a later period? See our massive scale [headlines dataset](https://huggingface.co/datasets/dell-research-harvard/headlines-semantic-similarity) (1920s-80s) and [paper](https://arxiv.org/pdf/2306.17810.pdf), consisting of locally written headlines from news wire articles 

![](/assets/projects/headlines_main.png)

We're pretty pumped to have a billion+ observations in a historical dataset description table.

![](/assets/projects/as_describe.png)

If you think [American Stories](https://huggingface.co/datasets/dell-research-harvard/AmericanStories) may be useful for you, please like or download. It is challenging to fund dataset/open-source projects, and we need to show that people find our work useful so we can do more! 

Funding: Harvard Data Science Initiative, Harvard Catalyst, Harvard Griffin Fund, and MS Azure 

