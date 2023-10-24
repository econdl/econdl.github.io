---
layout: course
title: >
    Economics 2355: Unleashing Novel Data at Scale
semester: >
    Spring 2021
overview: >
    Many important economic questions remain unanswered, in substantial part because the data required to examine them has traditionally been inaccessible. Information that could elucidate important questions is scattered throughout text, or contained in scans, photographs, or hard copy documents. This course will provide an introduction to deep learning-based methods that can convert raw information into computable data at scale. The course will examine how object detection models can be used to perform document layout understanding, extracting complex structures from documents such as statistical tables, corporate records, biographical compendia, archival documents, and newspapers. Active learning, which aims to optimally combine inputs from humans and deep learning to conserve tedious human labor, will receive emphasis. We will also consider GAN-based image pre-processing. We will moreover discuss how to optimize character recognition. The second half of the course will examine natural language processing, with a particular focus on recent transformer-based advances for creating computable text measures, as well as their application to retrieval and question answering. We will consider how these methods can be best applied to data with significant OCR noise. By introducing a range of methods to convert diverse information into computable data, the course aims to expand what students view as data and to increase the number of research questions that are feasible to answer. 
---

**Course Description**

This course differs from a computer science course in its intensive focus on methods that achieve the best results when applied to documents likely to be of interest to quantitative social scientists. Our applications are often different in fundamentally important ways from those that tend to predominate in the computer science literature. The course is based on extensive experimentation by the instructor with these methods, as well as a variety of other methods that did not work very well. The deep learning literature is very large and moves at a fast pace. It is my hope that by consolidating this information into a course, it will save others a lot of the inefficiency that we experienced trying to navigate this literature and to figure out what works. This is a very nascent literature, and the course also aims to highlight areas where there is significant scope for future innovations. It covers the most cutting-edge methods, some only released in the past few months. The course is well suited to anyone with an interest in using observational data for applied research who is comfortable with programming and the mathematical concepts that underly deep learning. 



**Schedule**

 (last offered spring 2021)

| DATE                            | TOPIC                                                        | DUE          |
| ------------------------------- | ------------------------------------------------------------ | ------------ |
| **Introduction**                |                                                              |              |
| Jan 25                          | Course Overview                                              |              |
| Jan 27                          | An Introduction to Deep Learning (Part 1)                    |              |
| Feb 1                           | An Introduction to Deep Learning (Part 2)                    |              |
| **Computer Vision**             |                                                              |              |
| Feb 3                           | Convolutional Neural Networks                                |              |
| Feb 8                           | Image Classification                                         |              |
| Feb 10                          | Object Detection                                             |              |
| Feb 15                          | NO CLASS (President’s Day)                                   |              |
| Feb 17                          | Active Learning Based Layout Annotation and Labeling Hacks   |              |
| Feb 22                          | Fine Tuning Object Detection Models                          | Report 1     |
| Feb 24                          | Generative Adversarial Networks                              |              |
| Mar 1                           | NO CLASS (Wellness Day)                                      |              |
| **OCR and Post-Processing**     |                                                              |              |
| Mar 3                           | OCR Model Architectures (CNN+RNN/LSTM+CTC)                   |              |
| Mar 8                           | OCR and Post-Processing in Practice                          |              |
| **Natural Language Processing** |                                                              |              |
| Mar 10                          | Models of Words (word2vec, GLoVe)                            | Report 2     |
| Mar 15                          | Dependency Parsing; Language Models (N-Grams, RNN/LSTM  review, GRU) |              |
| Mar 17                          | Sequence to Sequence Learning                                |              |
| Mar 22                          | The Transformer                                              |              |
| Mar 24                          | Transformer-Based Models                                     |              |
| Mar 29                          | What’s in an Embedding; Sentiment Analysis                   | Report 3     |
| Mar 31                          | NO CLASS (Wellness Day)                                      |              |
| Apr 5                           | Retrieval and Question Answering                             |              |
| Apr 7                           | NLP on Noisy Data                                            |              |
| Apr 12                          | Zero-Shot and Few-Shot Learning in NLP                       |              |
| Apr 14                          | Vision Transformer Models                                    |              |
| **Student Presentations**       |                                                              |              |
| Apr 19                          | Student Presentations and Discussion                         |              |
| Apr 21                          | Student Presentations and Discussion                         |              |
| Apr 26                          | Student Presentations and Discussion                         |              |
| April 28                        | Student Presentations and Discussion                         |              |
| May 6                           |                                                              | Final Report |

 

**Reading List**

 

***An Introduction to Deep Learning\***

 

These two lectures will begin by setting the stage for why deep learning is necessary. When curating data at scale, there are generally two approaches: human-designed rules and deep learning. While we’ll see throughout the course that the judicious use of rules has its place in many big data endeavors, generally the performance of rule-based methods is disappointing in comparison to deep learning. We’ll discuss how and why rules often fail. 

 We will then turn to an overview of deep learning. The course assumes that participants already have a basic background in deep learning. For those who need to brush up on deep learning methods, the online text *Neural Networks and Deep Learning* provides an introduction to the main concepts and how they relate. *Deep Learning* by Ian Goodfellow, Yoshua Bengio, and Aaron Courville is the standard reference in the field. It is best suited to those who have some basic familiarity with deep learning. Part I provides a solid introduction to the concepts in applied math that are required to understand deep learning (most Economics PhD students will be familiar with this material, but the book is a good refresher). I recommend the book *Deep Learning with PyTorch* to anyone who does not already have extensive familiarity with PyTorch.  There are also numerous lectures available for free online. Finally, I include a highly cited review article by the leaders of the field, and a blog post that provides a useful summary of deep learning advances during the past decade. 



Nielsen, Michael. *Neural Networks and Deep Learning,* 2019 http://neuralnetworksanddeeplearning.com/



Ian Goodfellow and Yoshua Bengio and Aaron Courville. *Deep Learning,* 2016, MIT Press

https://www.deeplearningbook.org/ 

 

Stevens, Eli, Luca Antiga, and Thomas Viehmann. *Deep learning with PyTorch*. Manning Publications Company, 2020.

 

LeCun, Yann, Yoshua Bengio, and Geoffrey Hinton. "Deep learning." *Nature* 521, no. 7553 (2015): 436-444.

 

“The Decade of Deep Learning”: https://bmk.sh/2019/12/31/The-Decade-of-Deep-Learning/ 

 

This blog is a classic for neural networks background: https://colah.github.io/ 

 

***Convolutional Neural Networks\***

 

Convolutional Neural Networks (CNNs) have revolutionized computer vision in recent years. In this lecture, we will discuss CNN architectures, which form the backbone for object detection. 

 

LeCun, Yann, Léon Bottou, Yoshua Bengio, and Patrick Haffner. “Gradient-based learning applied to document recognition." *Proceedings of the IEEE* 86, no. 11 (1998): 2278-2324.

 

Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." *Advances in neural information processing systems* 25 (2012): 1097-1105 (AlexNet). 

 

Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." *arXiv preprint arXiv:1409.1556* (2014) (VGGNet).

 

Szegedy, Christian, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan, Vincent Vanhoucke, and Andrew Rabinovich. "Going deeper with convolutions." In *Proceedings of the IEEE conference on computer vision and pattern recognition*, pp. 1-9. 2015 (GoogLeNet).

 

He, Kaiming, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. "Deep Residual Learning for Image Recognition." In *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition*, pp. 770-778. 2016 (ResNet).

 

Xie, Saining, Ross Girshick, Piotr Dollár, Zhuowen Tu, and Kaiming He. "Aggregated residual transformations for deep neural networks." In *Proceedings of the IEEE conference on computer vision and pattern recognition*, pp. 1492-1500. 2017 (ResNeXt).

 

***Image Classification\***

 

Image classification is a fundamental task in many big data applications. Originally published in 2012, the Krizhevsky, Sutskever, and Hinton paper and is often recognized as the contribution that sparked the modern approach to deep learning, by showing a massive performance improvement from utilizing a deeper network. I also cite the Imagenet dataset paper (another one of the most cited papers in deep learning). This dataset has been used to develop and test many advances in computer vision. Benchmark datasets like this – associated with annual contests – play a very central role in computer science research. We’ll see others come up throughout the course. One important thing to be aware of is that many applications of relevance to us as social science researchers will not be well-represented by a benchmark dataset, and we will discuss the implications of this at various points during the course. This lecture will also discuss more recent contributions to image classification. 

 

Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." *Communications of the ACM* 60, no. 6 (2017): 84-90. 

 

Deng, Jia, Wei Dong, Richard Socher, Li-Jia Li, Kai Li, and Li Fei-Fei. "Imagenet: A large-scale hierarchical image database." In *2009 IEEE Conference on Computer Vision and Pattern Recognition*, pp. 248-255, 2009. (*Notes: this is the dataset that has been used to develop and test many advancements in computer vision, and is also one of the most cited papers in deep learning. Benchmark datasets like this play a very central role in computer science research)*

 

Afzal, Muhammad Zeshan, Andreas Kölsch, Sheraz Ahmed, and Marcus Liwicki. "Cutting the error by half: Investigation of very deep cnn and advanced training strategies for document image classification." In *2017 14th IAPR International Conference on Document Analysis and Recognition (ICDAR)*, vol. 1, pp. 883-888. 2017. https://doi.org/10.1109/ICDAR.2017.149.

 

Das, Arindam, Saikat Roy, Ujjwal Bhattacharya, and Swapan K. Parui. "Document image classification with intra-domain transfer learning and stacked generalization of deep convolutional neural networks." In *2018 24th International Conference on Pattern Recognition (ICPR)*, pp. 3180-3185. 2018. https://doi.org/10.1109/ICPR.2018.8545630.

 

***Training Neural Nets\*** 

 

Most of what we discussed in class is covered in the textbook treatments listed above, particularly the Goodfellow, Bengio and Courville textbook. Here are some additional references:

 

Goh, Gabriel. "Why momentum really works." *Distill* 2, no. 4 (2017): e6 (excellent treatment of momentum). 

 

Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." In *International conference on machine learning*, pp. 448-456. PMLR, 2015.

 

Santurkar, Shibani, Dimitris Tsipras, Andrew Ilyas, and Aleksander Madry. "How does batch normalization help optimization?." *arXiv preprint arXiv:1805.11604* (2018).

 

He, Tong, Zhi Zhang, Hang Zhang, Zhongyue Zhang, Junyuan Xie, and Mu Li. "Bag of tricks for image classification with convolutional neural networks." In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, pp. 558-567. 2019.

 

Li, Hao, Zheng Xu, Gavin Taylor, Christoph Studer, and Tom Goldstein. "Visualizing the loss landscape of neural nets." *arXiv preprint arXiv:1712.09913* (2017).

 

***Object Detection\***

 

This lecture covers object detection models. We focus on the Fast R-CNN series, as we have found through extensive experimentation that Mask R-CNN (a member of this series) leads to the best results and is easiest to implement for document layout analysis. 

 

Girshick, Ross, Jeff Donahue, Trevor Darrell, and Jitendra Malik. "Rich feature hierarchies for accurate object detection and semantic segmentation." In *Proceedings of the IEEE conference on computer vision and pattern recognition*, pp. 580-587. 2014. https://doi.org/ 10.1109/CVPR.2014.81 

 

Girshick, Ross. "Fast R-CNN." In *Proceedings of the IEEE international conference on computer vision*, pp. 1440-1448. 2015. https://doi.org/10.1109/ICCV.2015.169.

 

Ren, Shaoqing, Kaiming He, Ross Girshick, and Jian Sun. "Faster R-CNN: Towards real-time object detection with region proposal networks." *IEEE transactions on pattern analysis and machine intelligence*, vol. 39, no. 6, pp. 1137-1149. 2016. https://doi.org/10.1109/TPAMI.2016.2577031.

 

He, Kaiming, Georgia Gkioxari, Piotr Dollár, and Ross Girshick. "Mask R-CNN." In *Proceedings of the IEEE international conference on computer vision*, pp. 2961-2969. 2017. https://doi.org/10.1109/ICCV.2017.322.

 

Kirillov, Alexander, Ross Girshick, Kaiming He, and Piotr Dollár. "Panoptic feature pyramid networks." In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, pp. 6399-6408. 2019.

 

Bodla, Navaneeth, Bharat Singh, Rama Chellappa, and Larry S. Davis. "Soft-NMS--improving object detection with one line of code." In *Proceedings of the IEEE international conference on computer vision*, pp. 5561-5569. 2017.

 

Lin, Tsung-Yi, Michael Maire, Serge Belongie, James Hays, Pietro Perona, Deva Ramanan, Piotr Dollár, and C. Lawrence Zitnick. "Microsoft coco: Common objects in context." In *European conference on computer vision*, pp. 740-755. Springer, Cham, 2014.

 

***Active Learning Based Layout Annotation and Labeling Hacks\***

 

Labeling is costly, and the feasibility of a particular pipeline may rely on significantly reducing these costs. We discuss how active learning, as well as various hacks, can be used to substantially reduce annotation costs. 

 

Shen, Zejiang, Jian Zhao, Melissa Dell, Yaoliang Yu, and Weining Li. "OLALA: Object-Level Active Learning Based Layout Annotation." *arXiv preprint arXiv:2010.01762*, pp. 1-9. 2020. https://arxiv.org/pdf/2010.01762.pdf.

 

Shen, Zejiang, Kaixuan Zhang, and Melissa Dell. "A Large Dataset of Historical Japanese Documents with Complex Layouts." In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops*, pp. 548-549. 2020. https://doi.org/10.1109/CVPRW50498.2020.00282.

 

Tkachenko, Maxim, Mikhail Malyuk, Nikita Shevchenko, Andrey Holmanyuk, and Nikolai Liubimov. “Label studio.” Software, accessed January 5, 2021. *GitHub repository*. 2020. https://github.com/heartexlabs/label-studio.

 

***Fine-Tuning Object Detection Models\***

 

We will discuss the basics of fine-tuning an object detection model. 

 

Wu, Yuxin, Alexander Kirillov, Francisco Massa, Wan-Yen Lo, and Ross Girshick. "Detectron2." 2019. https://github.com/facebookresearch/detectron2. 

 

Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." In International conference on machine learning, pp. 448-456. PMLR, 2015.

 

Huang, Jonathan, Vivek Rathod, Chen Sun, Menglong Zhu, Anoop Korattikara, Alireza Fathi, Ian Fischer et al. "Speed/accuracy trade-offs for modern convolutional object detectors." In *Proceedings of the IEEE conference on computer vision and pattern recognition*, pp. 7310-7311. 2017.

 

Shen, Zejiang, Ruochen Zhang, and Melissa Dell. "LayoutParser." 2020. https://github.com/Layout-Parser/layout-parser.

 

***Generative Adversarial Networks\***

 

GANs have received a substantial attention in the popular press, for tasks such as generating human-like faces. They are also very useful for document layout analysis, for removing document noise such as text bleed. This can lead to a substantial improvement in OCR accuracy. 

 

Goodfellow, Ian J., Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair, Aaron Courville, and Yoshua Bengio. "Generative adversarial networks." *arXiv preprint arXiv:1406.2661* (2014).

 

Goodfellow, Ian. "Nips 2016 tutorial: Generative adversarial networks." *arXiv preprint arXiv:1701.00160* (2016).

 

Zhu, Jun-Yan, Taesung Park, Phillip Isola, and Alexei A. Efros. "Unpaired image-to-image translation using cycle-consistent adversarial networks." In *Proceedings of the IEEE international conference on computer vision*, pp. 2223-2232. 2017.

 

Cleaning Up Dirty Scanned Documents with Deep Learning https://medium.com/illuin/cleaning-up-dirty-scanned-documents-with-deep-learning-2e8e6de6cfa6 

 

***OCR: Architecture, Hacks, and Designing Your Own Engine\***

 

We’ve spent a large amount of time working to optimize existing OCR solutions, and will share what we have learned. We’ll also outline how you could design an OCR engine for a simple case such as number detection, which requires understanding OCR architecture. 

 

Shi, Baoguang, Xiang Bai, and Cong Yao. "An end-to-end trainable neural network for image-based sequence recognition and its application to scene text recognition." *IEEE transactions on pattern analysis and machine intelligence* 39, no. 11 (2016): 2298-2304.

 

Bengio, Yoshua, Patrice Simard, and Paolo Frasconi. "Learning long-term dependencies with gradient descent is difficult." *IEEE transactions on neural networks* 5, no. 2 (1994): 157-166.

Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." *Neural computation* 9, no. 8 (1997): 1735-1780.

 

Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." *Neural computation* 9, no. 8 (1997): 1735-1780.

 

Greff, Klaus, Rupesh K. Srivastava, Jan Koutník, Bas R. Steunebrink, and Jürgen Schmidhuber. "LSTM: A search space odyssey." *IEEE transactions on neural networks and learning systems* 28, no. 10 (2016): 2222-2232.

 

Graves, Alex, Santiago Fernández, Faustino Gomez, and Jürgen Schmidhuber. "Connectionist temporal classification: labelling unsegmented sequence data with recurrent neural networks." In *Proceedings of the 23rd international conference on Machine learning*, pp. 369-376. 2006.

 

Hannun, Awni. "Sequence modeling with ctc." *Distill* 2, no. 11 (2017): e8.

 

JaidedAI. "EasyOCR." *GitHub repository*. 2020. https://github.com/JaidedAI/EasyOCR.

 

tesseract-ocr. "Tesseract OCR." *GitHub repository*. 2014. https://github.com/tesseract-ocr/tesseract.

 

Shen, Zejiang, Ruochen Zhang, and Melissa Dell. "LayoutParser." 2020. https://github.com/Layout-Parser/layout-parser.

 

Xu, Yiheng, Minghao Li, Lei Cui, Shaohan Huang, Furu Wei, and Ming Zhou. "LayoutLM: Pre-training of text and layout for document image understanding." In *Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining*, pp. 1192-1200. 2020. https://doi.org/10.1145/3394486.3403172.

 

***Models of Words\***

 

The second part of the course will cover natural language processing, with an emphasis on the cutting-edge models that have revolutionized the field in recent years. We will begin with Word2Vec, an older workhorse model for static embeddings.

 

Mikolov, Tomas, Ilya Sutskever, Kai Chen, Greg S. Corrado, and Jeff Dean. "Distributed representations of words and phrases and their compositionality." *Advances in Neural Information Processing Systems* 26 (2013): 3111-3119. (*Notes: this paper developed the word2vec model commonly used in NLP)* 

 

*Mikolov, Tomas, Ilya Sutskever, Kai Chen, Greg Corrado, and Jeffrey Dean. "Distributed representations of words and phrases and their compositionality." arXiv preprint arXiv:1310.4546 (2013).*

 

*Pennington, Jeffrey, Richard Socher, and Christopher D. Manning. "Glove: Global vectors for word representation." In Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP), pp. 1532-1543. 2014.*

 

“Deep Learning, NLP, and Representation” https://colah.github.io/posts/2014-07-NLP-RNNs-Representations/. 

 

Goldberg, Yoav. *Neural network methods for natural language processing.* *Synthesis lectures on human language technologies* 10, no. 1 (2017): 1-309 (textbook treatment). 

 

Levy, Omer, Yoav Goldberg, and Ido Dagan. "Improving distributional similarity with lessons learned from word embeddings." *Transactions of the Association for Computational Linguistics* 3 (2015): 211-225.

 

***Dependency Parsing, Part of Speech Tagging, and Named Entity Recognition\*** 

 

This lecture introduces methods for identifying parts of speech, named entities, and dependency structures. This can be very relevant for extracting data from structured texts, such as biographies. 

 

Chen, Danqi, and Christopher D. Manning. "A fast and accurate dependency parser using neural networks." In Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP), pp. 740-750. 2014.

 

Andor, Daniel, Chris Alberti, David Weiss, Aliaksei Severyn, Alessandro Presta, Kuzman Ganchev, Slav Petrov, and Michael Collins. "Globally normalized transition-based neural networks." *arXiv preprint arXiv:1603.06042* (2016).

 

spaCy. https://spacy.io/

 

Parsey McParseface https://deepai.org/machine-learning-model/parseymcparseface

 

 

***Language Models\*** (N-Grams, RNN/LSTM review, GRU)  

 

Together with the lecture on Transformers, this introduces architectures for language modeling. 

 

Jurafsky, Daniel and James Martin, “N-Gram Language Models” *Speech and Language Processing,* 2020 https://web.stanford.edu/~jurafsky/slp3/3.pdf. 

 

Bengio, Yoshua, Patrice Simard, and Paolo Frasconi. "Learning long-term dependencies with gradient descent is difficult." *IEEE transactions on neural networks* 5, no. 2 (1994): 157-166.

Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." *Neural computation* 9, no. 8 (1997): 1735-1780.

 

Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." *Neural computation* 9, no. 8 (1997): 1735-1780.

 

Greff, Klaus, Rupesh K. Srivastava, Jan Koutník, Bas R. Steunebrink, and Jürgen Schmidhuber. "LSTM: A search space odyssey." *IEEE transactions on neural networks and learning systems* 28, no. 10 (2016): 2222-2232.

 

Chung, Junyoung, Caglar Gulcehre, KyungHyun Cho, and Yoshua Bengio. "Empirical evaluation of gated recurrent neural networks on sequence modeling." *arXiv preprint arXiv:1412.3555* (2014).

 

***Sequence-to-Sequence Learning\***

 

Sequence-to-sequence learning is central to machine translation, but also foundational for other topics we will cover subsequently. 

 

Papineni, Kishore, Salim Roukos, Todd Ward, and Wei-Jing Zhu. "Bleu: a method for automatic evaluation of machine translation." In *Proceedings of the 40th annual meeting of the Association for Computational Linguistics*, pp. 311-318. 2002.

 

Sutskever, Ilya, Oriol Vinyals, and Quoc V. Le. "Sequence to sequence learning with neural networks." *arXiv preprint arXiv:1409.3215* (2014).

 

Bahdanau, Dzmitry, Kyunghyun Cho, and Yoshua Bengio. "Neural machine translation by jointly learning to align and translate." *arXiv preprint arXiv:1409.0473* (2014).

 

Olah, Chris, and Shan Carter. "Attention and augmented recurrent neural networks." *Distill* 1, no. 9 (2016): e1. https://distill.pub/2016/augmented-rnns/

 

Britz, Denny, Anna Goldie, Minh-Thang Luong, and Quoc Le. "Massive exploration of neural machine translation architectures." *arXiv preprint arXiv:1703.03906* (2017).

 

 

***The Transformer\***

 

This architecture has revolutionized NLP in recent years. 

 

Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, and Illia Polosukhin. "Attention is all you need." In *Advances in Neural Information Processing Systems*, pp. 5998-6008. 2017.  

 

“The Annotated Transformer”: http://nlp.seas.harvard.edu/2018/04/03/attention.html (a guide annotating the paper with PyTorch implementation) 

 

“The Illustrated Transformer” http://jalammar.github.io/illustrated-transformer/ 

 

“Transformers-based Encoder-Decoder Models” https://huggingface.co/blog/encoder-decoder 

 

“Glass Box: The Transformer – Attention is All you Need” https://glassboxmedicine.com/2019/08/15/the-transformer-attention-is-all-you-need/ 

 

Olah, Chris, and Shan Carter. "Attention and augmented recurrent neural networks." *Distill* 1, no. 9 (2016): e1.

 

***Transformer-Based Architectures\*** 

 

We will cover a range of models: BERT, XLNet, Albert, Distilbert, Roberta, Sentence BERT, T5, and BigBird. The aim is to understand the general architecture and the advantages and disadvantages of these alternative models. 

 

Devlin, Jacob, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. "Bert: Pre-Training of Deep Bidirectional Transformers for Language Understanding." *arXiv preprint arXiv:1810.04805* (2018).

 

Liu, Yinhan, Myle Ott, Naman Goyal, Jingfei Du, Mandar Joshi, Danqi Chen, Omer Levy, Mike Lewis, Luke Zettlemoyer, and Veselin Stoyanov. "Roberta: A robustly optimized bert pretraining approach." *arXiv preprint arXiv:1907.11692* (2019).

 

Yang, Zhilin, Zihang Dai, Yiming Yang, Jaime Carbonell, Ruslan Salakhutdinov, and Quoc V. Le. "Xlnet: Generalized autoregressive pretraining for language understanding." *arXiv preprint arXiv:1906.08237* (2019).

 

Lan, Zhenzhong, Mingda Chen, Sebastian Goodman, Kevin Gimpel, Piyush Sharma, and Radu Soricut. "Albert: A lite bert for self-supervised learning of language representations." *arXiv preprint arXiv:1909.11942* (2019).

 

Sanh, Victor, Lysandre Debut, Julien Chaumond, and Thomas Wolf. "DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter." *arXiv preprint arXiv:1910.01108* (2019).

 

Reimers, Nils, and Iryna Gurevych. "Sentence-bert: Sentence embeddings using siamese bert-networks." *arXiv preprint arXiv:1908.10084* (2019).

 

Brown, Tom B., Benjamin Mann, Nick Ryder, Melanie Subbiah, Jared Kaplan, Prafulla Dhariwal, Arvind Neelakantan et al. "Language models are few-shot learners." *arXiv preprint arXiv:2005.14165* (2020). (https://www.technologyreview.com/2020/09/23/1008729/openai-is-giving-microsoft-exclusive-access-to-its-gpt-3-language-model/); see also: Radford, Alec, Jeffrey Wu, Rewon Child, David Luan, Dario Amodei, and Ilya Sutskever. "Language models are unsupervised multitask learners." *OpenAI blog* 1, no. 8 (2019): 9.

 

Raffel, Colin, Noam Shazeer, Adam Roberts, Katherine Lee, Sharan Narang, Michael Matena, Yanqi Zhou, Wei Li, and Peter J. Liu. "Exploring the limits of transfer learning with a unified text-to-text transformer." *arXiv preprint arXiv:1910.10683* (2019).

 

Zaheer, Manzil, Guru Guruganesh, Avinava Dubey, Joshua Ainslie, Chris Alberti, Santiago Ontanon, Philip Pham et al. "Big bird: Transformers for longer sequences." *arXiv preprint arXiv:2007.14062* (2020).

 

Wang, Alex, Amanpreet Singh, Julian Michael, Felix Hill, Omer Levy, and Samuel R. Bowman. "GLUE: A multi-task benchmark and analysis platform for natural language understanding." *arXiv preprint arXiv:1804.07461* (2018).

 

The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning): http://jalammar.github.io/illustrated-bert/

 

Smith, Noah A. "Contextual word representations: A contextual introduction." *arXiv preprint arXiv:1902.06006* (2019).

 

***Understanding and Visualizing Embeddings\*** 

 

We will work to deepen our intuition for what embeddings contain and discuss how to visualize them. 

 

McInnes, Leland, John Healy, and James Melville. "Umap: Uniform manifold approximation and projection for dimension reduction." *arXiv preprint arXiv:1802.03426* (2018).

 

Embedding Projector: http://projector.tensorflow.org

 

Köhn, Arne. "What’s in an embedding? Analyzing word embeddings through multilingual evaluation." In *Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing*, pp. 2067-2073. 2015.

 

Rogers, Anna, Olga Kovaleva, and Anna Rumshisky. "A primer in bertology: What we know about how bert works." *Transactions of the Association for Computational Linguistics* 8 (2021): 842-866.

 

Wiedemann, Gregor, Steffen Remus, Avi Chawla, and Chris Biemann. "Does BERT make any sense? Interpretable word sense disambiguation with contextualized embeddings." *arXiv preprint arXiv:1909.10430* (2019).

 

Coenen, Andy, Emily Reif, Ann Yuan, Been Kim, Adam Pearce, Fernanda Viégas, and Martin Wattenberg. "Visualizing and measuring the geometry of bert." *arXiv preprint arXiv:1906.02715* (2019).

 

Ethayarajh, Kawin. "How contextual are contextualized word representations? comparing the geometry of BERT, ELMo, and GPT-2 embeddings." *arXiv preprint arXiv:1909.00512* (2019).

 

Merchant, Amil, Elahe Rahimtoroghi, Ellie Pavlick, and Ian Tenney. "What Happens to BERT Embeddings During Fine-tuning?." *arXiv preprint arXiv:2004.14448* (2020).

 

***Sentiment Analysis\***

 

We will discuss how to conduct sentiment analysis, through training a classifier. Zero shot approaches are covered separately later in the course. 

 

Sentiment Analysis Leaderboard: https://paperswithcode.com/task/sentiment-analysis and https://paperswithcode.com/sota/sentiment-analysis-on-sst-2-binary 

 

Stanford NLP. Sentiment Analysis https://nlp.stanford.edu/sentiment/

 

Munikar, Manish, Sushil Shakya, and Aakash Shrestha. "Fine-grained sentiment classification using BERT." In *2019 Artificial Intelligence for Transforming Business and Society (AITB)*, vol. 1, pp. 1-5. IEEE, 2019.

 

Bostan, Laura, Evgeny Kim, and Roman Klinger. "GoodNewsEveryone: A corpus of news headlines annotated with emotions, semantic roles, and reader perception." *arXiv preprint arXiv:1912.03184* (2019).

 

Schick, Timo, and Hinrich Schütze. "Exploiting cloze questions for few-shot text classification and natural language inference." *arXiv preprint arXiv:2001.07676* (2020).

 

Hewitt, John, and Christopher D. Manning. "A structural probe for finding syntax in word representations." In *Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers)*, pp. 4129-4138. 2019.

 

Han, Jiyoung, Youngin Lee, Junbum Lee, and Meeyoung Cha. "The fallacy of echo chambers: Analyzing the political slants of user-generated news comments in Korean media." In *Proceedings of the 5th Workshop on Noisy User-generated Text (W-NUT 2019)*, pp. 370-374. 2019.

 

***Retrieval and Question Answering\***

 

In working with very large text datasets, retrieval (closely related to question answering) is essential, and topic classification is likewise often of interest. 

 

Karpukhin, Vladimir, Barlas Oğuz, Sewon Min, Ledell Wu, Sergey Edunov, Danqi Chen, and Wen-tau Yih. "Dense passage retrieval for open-domain question answering." *arXiv preprint arXiv:2004.04906* (2020).https://github.com/facebookresearch/DPR

 

Rajpurkar, Pranav, Jian Zhang, Konstantin Lopyrev, and Percy Liang. "Squad: 100,000+ questions for machine comprehension of text." *arXiv preprint arXiv:1606.05250* (2016).

 

Garg, Siddhant, Thuy Vu, and Alessandro Moschitti. "Tanda: Transfer and adapt pre-trained transformer models for answer sentence selection." In *Proceedings of the AAAI Conference on Artificial Intelligence*, vol. 34, no. 05, pp. 7780-7788. 2020.

 

Lee, Kenton, Ming-Wei Chang, and Kristina Toutanova. "Latent retrieval for weakly supervised open domain question answering." *arXiv preprint arXiv:1906.00300* (2019).

 

Lewis, Patrick, Ethan Perez, Aleksandara Piktus, Fabio Petroni, Vladimir Karpukhin, Naman Goyal, Heinrich Küttler et al. "Retrieval-augmented generation for knowledge-intensive nlp tasks." *arXiv preprint arXiv:2005.11401* (2020).

 

***Zero-Shot and Few-Shot Learning\*** 

 

What methods are available when we have little or no data for fine tuning? What can we achieve and how? 

 

Joe Davison. “Zero Shot Learning in Modern NLP” https://joeddav.github.io/blog/2020/05/29/ZSL.html

 

Huggingface. “New Pipeline for zero-shot text classification” https://discuss.huggingface.co/t/new-pipeline-for-zero-shot-text-classification/681 

 

TLDRstory: https://github.com/neuml/tldrstory

 

Yin, Wenpeng, Jamaal Hay, and Dan Roth. "Benchmarking zero-shot text classification: Datasets, evaluation and entailment approach." arXiv preprint arXiv:1909.00161 (2019).

https://github.com/neuml/txtai 

 

Yin, Wenpeng, Jamaal Hay, and Dan Roth. "Benchmarking zero-shot text classification: Datasets, evaluation and entailment approach." *arXiv preprint arXiv:1909.00161* (2019).

 

Schick, Timo, and Hinrich Schütze. "Exploiting cloze questions for few-shot text classification and natural language inference." *arXiv preprint arXiv:2001.07676* (2020).

 

Petroni, Fabio, Tim Rocktäschel, Patrick Lewis, Anton Bakhtin, Yuxiang Wu, Alexander H. Miller, and Sebastian Riedel. "Language models as knowledge bases?." *arXiv preprint arXiv:1909.01066* (2019).

 

***Natural Language Generation and Summarization\*** 

 

We will cover this topic if time permits. Summarization entails using deep learning to automate summarizing textual passage. 

 

Holtzman, Ari, Jan Buys, Li Du, Maxwell Forbes, and Yejin Choi. "The curious case of neural text degeneration." *arXiv preprint arXiv:1904.09751* (2019).

 

See, Abigail, Peter J. Liu, and Christopher D. Manning. "Get to the point: Summarization with pointer-generator networks." *arXiv preprint arXiv:1704.04368* (2017).

 

Liu, Chia-Wei, Ryan Lowe, Iulian V. Serban, Michael Noseworthy, Laurent Charlin, and Joelle Pineau. "How not to evaluate your dialogue system: An empirical study of unsupervised evaluation metrics for dialogue response generation." *arXiv preprint arXiv:1603.08023* (2016).

 

***NLP on Noisy Data\***

 

In contexts where texts are OCR’ed from historical documents, there may be a substantial amount of noise due to OCR errors. We will discuss how to deal with this noise based on the limited literature and our own experience. 

 

Srivastava, Ankit, Piyush Makhija, and Anuj Gupta. "Noisy Text Data: Achilles’ Heel of BERT." In *Proceedings of the Sixth Workshop on Noisy User-generated Text (W-NUT 2020)*, pp. 16-21. 2020.

 

Sergio, Gwenaelle Cunha, and Minho Lee. "Stacked DeBERT: All attention in incomplete data for text classification." *Neural Networks* (2020).

 

Sun, Yifu, and Haoming Jiang. "Contextual Text Denoising with Masked Language Models." *arXiv preprint arXiv:1910.14080* (2019).

 

Nguyen, Dat Quoc, Thanh Vu, and Anh Tuan Nguyen. "BERTweet: A pre-trained language model for English Tweets." *arXiv preprint arXiv:2005.10200* (2020).

 

Vāravs, Andris, and Askars Salimbajevs. "Restoring punctuation and capitalization using transformer models." In *International Conference on Statistical Language and Speech Processing*, pp. 91-102. Springer, Cham, 2018.

 

The Viral Texts Project. https://viraltexts.org/ and Passage Similarity https://github.com/dasmiq/passim 

 

***Vision Transformer Models\*** 

Liu, Ze, Yutong Lin, Yue Cao, Han Hu, Yixuan Wei, Zheng Zhang, Stephen Lin, and Baining Guo. "Swin transformer: Hierarchical vision transformer using shifted windows." *arXiv preprint arXiv:2103.14030* (2021).



Han, Kai, An Xiao, Enhua Wu, Jianyuan Guo, Chunjing Xu, and Yunhe Wang. "Transformer in transformer." *arXiv preprint arXiv:2103.00112* (2021).



Dosovitskiy, Alexey, Lucas Beyer, Alexander Kolesnikov, Dirk Weissenborn, Xiaohua Zhai, Thomas Unterthiner, Mostafa Dehghani et al. "An image is worth 16x16 words: Transformers for image recognition at scale." *arXiv preprint arXiv:2010.11929* (2020).

 

**Low Resource NLP**

 

This is a series of lectures for NLP in low resource languages; time constraints prevent covering these topics in this course, but it is likely to be of interest to some students: Low Resource NLP Bootcamp: https://github.com/neubig/lowresource-nlp-bootcamp-2020 

 

 