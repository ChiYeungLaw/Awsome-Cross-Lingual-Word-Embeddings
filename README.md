# Awsome Cross Lingual Word Embeddings

This repo contains some Cross-lingual word embeddings research. I summarize some papers and categorize them by myself. You are kindly invited to pull requests!

This survey [A survey of cross-lingual word embedding models](https://arxiv.org/abs/1706.04902) has good coverage of this area.

# Word-level Alignment Method

## Linear Mapping

### Supervised

1. Mikolov, Tomas , Q. V. Le , and I. Sutskever . "Exploiting Similarities among Languages for Machine Translation." *Computer Science* (2013). [[paper]](https://arxiv.org/pdf/1309.4168)
2. Faruqui, Manaal & Dyer, Chris. (2014). Improving Vector Space Word Representations Using Multilingual Correlation. 14th Conference of the European Chapter of the Association for Computational Linguistics 2014, EACL 2014. 462-471. 10.3115/v1/E14-1049. [[paper]](https://www.aclweb.org/anthology/E14-1049.pdf) [[code]](https://github.com/mfaruqui/crosslingual-cca)
3. Dinu, Georgiana & Baroni, Marco. (2014). Improving zero-shot learning by mitigating the hubness problem. [[paper]](http://de.arxiv.org/pdf/1412.6568)
4. Lazaridou, Angeliki & Dinu, Georgiana & Baroni, Marco. (2015). Hubness and Pollution: Delving into Cross-Space Mapping for Zero-Shot Learning. 270-280. 10.3115/v1/P15-1027.  [[paper]](https://www.researchgate.net/publication/301404734_Hubness_and_Pollution_Delving_into_Cross-Space_Mapping_for_Zero-Shot_Learning)
5. Xing, Chao & Wang, Dong & Liu, Chao & Lin, Yiye. (2015). Normalized Word Embedding and Orthogonal Transform for Bilingual Word Translation. 1006-1011. 10.3115/v1/N15-1104.  [[paper]](https://www.aclweb.org/anthology/N15-1104/)
6. Lu, Ang & Wang, Weiran & Bansal, Mohit & Gimpel, Kevin & Livescu, Karen. (2015). Deep Multilingual Correlation for Improved Word Embeddings. 250-256. 10.3115/v1/N15-1028.  [[paper]](https://www.researchgate.net/publication/301404407_Deep_Multilingual_Correlation_for_Improved_Word_Embeddings)
7. Artetxe, Mikel & Labaka, Gorka & Agirre, Eneko. (2016). Learning principled bilingual mappings of word embeddings while preserving monolingual invariance. 2289-2294. 10.18653/v1/D16-1250.  [[paper]](https://www.researchgate.net/publication/311990620_Learning_principled_bilingual_mappings_of_word_embeddings_while_preserving_monolingual_invariance) [[code]](https://github.com/artetxem/vecmap)
8. Zhang, Yuan & Gaddy, David & Barzilay, Regina & Jaakkola, Tommi. (2016). Ten Pairs to Tag – Multilingual POS Tagging via Coarse Mapping between Embeddings. 1307-1317. 10.18653/v1/N16-1156.  [[paper]](https://www.aclweb.org/anthology/N16-1156.pdf) [[code]](https://github.com/yuanzh/transfer_pos)
9. Vulić, Ivan & Korhonen, Anna. (2016). On the Role of Seed Lexicons in Learning Bilingual Word Embeddings. 247-257. 10.18653/v1/P16-1024.  [[paper]](https://www.aclweb.org/anthology/P16-1024/)
10. Smith, Samuel & Turban, David & Hamblin, Steven & Hammerla, Nils. (2017). Offline bilingual word vectors, orthogonal transformations and the inverted softmax.  [[paper]](https://arxiv.org/pdf/1702.03859)
11. Mikel Artetxe, Gorka Labaka, and Eneko Agirre. 2018. Generalizing and improving bilingual word embedding mappings with a multi-step framework of linear transformations. In *Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence (AAAI-18)*, pages 5012-5019. [[paper]](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16935/16781)
12. Joulin, Armand & Bojanowski, Piotr & Mikolov, Tomas & Jégou, Hervé & Grave, Edouard. (2018). Loss in Translation: Learning Bilingual Word Mapping with a Retrieval Criterion. 2979-2984. 10.18653/v1/D18-1330. [[paper]](https://www.aclweb.org/anthology/D18-1330/)

### Weak Supervised

1. Zhang, M., Liu, Y., Luan, H., Liu, Y., & Sun, M. (2016). Inducing Bilingual Lexica From Non-Parallel Data With Earth Mover’s Distance Regularization. In Proceedings of COLING 2016, pp. 3188–3198.  [[paper]](http://nlp.csai.tsinghua.edu.cn/~ly/papers/coling2016.pdf)
2. Artetxe, M., Labaka, G., & Agirre, E. (2017). Learning bilingual word embeddings with (almost) no bilingual data. In Proceedings of ACL, pp. 451–462. [[paper]](https://www.aclweb.org/anthology/P17-1042/)
3. Patra, B. , Moniz, J. R. A. , Garg, S. , Gormley, M. R. , & Neubig, G. . (2019). Bilingual lexicon induction with semi-supervision in non-isometric embedding spaces.  [[paper]](https://www.aclweb.org/anthology/P19-1018/)[[Code]](https://github.com/joelmoniz/BLISS)

### Unsupervised

1. Zhang, M., Liu, Y., Luan, H., & Sun, M. (2017). Adversarial training for unsupervised bilingual lexicon induction. In Proceedings of ACL, pp. 1959–1970. [[paper]](https://www.aclweb.org/anthology/P17-1179.pdf)[[unofficial code]](https://github.com/muyeby/Paper-Reimplement/tree/11610ef41ea8d1c4897a11799b6e80fa0496e67d/Adversarial-Lexicon-Induction/zhang2017acl)
2. Zhang, M., Liu, Y., Luan, H., & Sun, M. (2017). Earth Mover’ s Distance Minimization for Unsupervised Bilingual Lexicon Induction. In Proceedings of EMNLP 2017. [[paper]](https://www.aclweb.org/anthology/D17-1207.pdf)
3. Conneau, Alexis & Lample, Guillaume & Ranzato, Marc'Aurelio & Denoyer, Ludovic & Jégou, Hervé. (2017). Word Translation Without Parallel Data.  [[paper]](https://www.researchgate.net/publication/320344586_Word_Translation_Without_Parallel_Data)[(code MUSE)](https://github.com/facebookresearch/MUSE)
4. Søgaard, Anders & Ruder, Sebastian & Vulić, Ivan. (2018). On the Limitations of Unsupervised Bilingual Dictionary Induction.  [[paper]](https://www.aclweb.org/anthology/P18-1072/)
5. Artetxe, M., Labaka, G., & Agirre, E. (2018). A robust self-learning method for fully unsupervised cross-lingual mappings of word embeddings. In Proceedings of ACL 2018. [[paper]](https://arxiv.org/abs/1805.06297v2)
6. Vulić, Ivan & Glavaš, Goran & Reichart, Roi & Korhonen, Anna. (2019). Do We Really Need Fully Unsupervised Cross-Lingual Embeddings?. [[paper]](https://www.aclweb.org/anthology/D19-1449/)	


## Non-linear Mapping

1. Nakashole, Ndapa. (2018). NORMA: Neighborhood Sensitive Maps for Multilingual Word Embeddings. 512-522. 10.18653/v1/D18-1047.  [[paper]](https://www.aclweb.org/anthology/D18-1047/)
2. Patra, Barun & Moniz, Joel & Garg, Sarthak & Gormley, Matthew & Neubig, Graham. (2019). Bilingual Lexicon Induction with Semi-supervision in Non-Isometric Embedding Spaces.  [[paper]](https://www.aclweb.org/anthology/P19-1018/)
3. Vulić, Ivan & Ruder, Sebastian & Søgaard, Anders. (2020). Are All Good Word Vector Spaces Isomorphic?.  [[paper]](https://www.researchgate.net/publication/340523938_Are_All_Good_Word_Vector_Spaces_Isomorphic)
4. Mohiuddin, Tasnim & Bari, M & Joty, Shafiq. (2020). LNMap: Departures from Isomorphic Assumption in Bilingual Lexicon Induction Through Non-Linear Mapping in Latent Space.  [[paper]](https://www.researchgate.net/publication/341040113_LNMap_Departures_from_Isomorphic_Assumption_in_Bilingual_Lexicon_Induction_Through_Non-Linear_Mapping_in_Latent_Space)
5. Glavaš, Goran, and Ivan Vulić. "Non-linear instance-based cross-lingual mapping for non-isomorphic embedding spaces." Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics. 2020. [[paper]](https://www.aclweb.org/anthology/2020.acl-main.675.pdf)
6. [[paper]](https://www.aclweb.org/anthology/2020.acl-main.675.pdf)

## Post-Processing

1. Vulić, Ivan, Anna Korhonen, and Goran Glavaš. "Improving Bilingual Lexicon Induction with Unsupervised Post-Processing of Monolingual Word Vector Spaces." Proceedings of the 5th Workshop on Representation Learning for NLP. 2020. [[paper]](https://www.aclweb.org/anthology/2020.repl4nlp-1.7/)

## Different Self-learning methods

1. Karan, M., Vulić, I., Korhonen, A. and Glavaš, G., 2020, July. Classification-based self-learning for weakly supervised bilingual lexicon induction. In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics (pp. 6915-6922). [[paper]](https://www.aclweb.org/anthology/2020.acl-main.618.pdf)

## Classification-based method

1. Heyman, Geert & Vulić, Ivan & Moens, Marie-Francine. (2017). Bilingual Lexicon Induction by Learning to Combine Word-Level and Character-Level Representations. 1085-1095. 10.18653/v1/E17-1102. [[paper]](https://www.aclweb.org/anthology/E17-1102.pdf)

## Evaluation

1. Glavaš, Goran & Litschko, Robert & Ruder, Sebastian & Vulić, Ivan. (2019). How to (Properly) Evaluate Cross-Lingual Word Embeddings: On Strong Baselines, Comparative Analyses, and Some Misconceptions. 710-721. 10.18653/v1/P19-1070. [[pape]](https://www.aclweb.org/anthology/P19-1070.pdf)