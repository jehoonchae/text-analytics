# text-analytics
Unstructured Data Analysis (Graduate) @Korea University

## Notice
* **Syllabus** ([download](https://github.com/pilsung-kang/text-mining/blob/master/2019_Spring_Unstructured%20Data%20Analysis.pdf)) [[Video](https://www.youtube.com/watch?v=pXCHYq6PXto&list=PLetSlH8YjIfVzHuSXtG4jAC2zbEAErXWm&index=1)]

## Recommended courses
  * CS224d @Stanford: Deep Learning for Natural Language Processing
    * Course Homepage: http://cs224d.stanford.edu/
    * YouTube Video: https://www.youtube.com/playlist?list=PLlJy-eBtNFt4CSVWYqscHDdP58M3zFHIG
  * CS224n @Stanford: Natural Language Processing Deep Learning
    * Course Homepage: http://web.stanford.edu/class/cs224n/
    * Youtube Video: https://www.youtube.com/playlist?list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6
  * Deep Natural Lanugage Processing @Oxford
    * Course Homepage: https://github.com/oxford-cs-deepnlp-2017/lectures

## Schedule
## Topic 1: Introduction to Text Analytics
* Text Analytics: Backgrounds, Applications, & Challanges, and Process [[Video](https://www.youtube.com/watch?v=UInnl60pzkA&list=PLetSlH8YjIfVzHuSXtG4jAC2zbEAErXWm&index=2)]
* Text Analytics Process [[Video](https://www.youtube.com/watch?v=Y0zrFVZqnl4&list=PLetSlH8YjIfVzHuSXtG4jAC2zbEAErXWm&index=3)]

## Topic 2: Text Preprocessing
* Introduction to Natural Language Processing (NLP)
* Lexical analysis
* Syntax analysis & Other topics in NLP
* Reading materials
  * Cambria, E., & White, B. (2014). Jumping NLP curves: A review of natural language processing research. IEEE Computational intelligence magazine, 9(2), 48-57. ([PDF](http://ieeexplore.ieee.org/abstract/document/6786458/))
  * Collobert, R., Weston, J., Bottou, L., Karlen, M., Kavukcuoglu, K., & Kuksa, P. (2011). Natural language processing (almost) from scratch. Journal of Machine Learning Research, 12(Aug), 2493-2537. ([PDF](http://www.jmlr.org/papers/volume12/collobert11a/collobert11a.pdf))
  * Young, T., Hazarika, D., Poria, S., & Cambria, E. (2017). Recent trends in deep learning based natural language processing. arXiv preprint arXiv:1708.02709. ([PDF](https://arxiv.org/pdf/1708.02709.pdf))
  * NLP Year in Review - 2019 ([Medium Post](https://medium.com/dair-ai/nlp-year-in-review-2019-fb8d523bcb19))

## Topic 3: Neural Networks Basics
* Perception, Multi-layered Perceptron
* Convolutional Neural Networks (CNN)
* Recurrent Neural Networks (RNN)
* Practical Techniques

## Topic 4: Text Representation I: Classic Methods
* Bag of words
* Word weighting
* N-grams

## Topic 5: Text Representation II: Distributed Representation
* Word2Vec
* GloVe
* FastText
* Doc2Vec
* Reading materials
  * Bengio, Y., Ducharme, R., Vincent, P., & Jauvin, C. (2003). A neural probabilistic language model. Journal of machine learning research, 3(Feb), 1137-1155. ([PDF](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf))
  * Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781. ([PDF](https://arxiv.org/pdf/1301.3781.pdf))
  * Mikolov, T., Sutskever, I., Chen, K., Corrado, G. S., & Dean, J. (2013). Distributed representations of words and phrases and their compositionality. In Advances in neural information processing systems (pp. 3111-3119). ([PDF](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf))
  * Pennington, J., Socher, R., & Manning, C. (2014). Glove: Global vectors for word representation. In Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP) (pp. 1532-1543). ([PDF](http://www.aclweb.org/anthology/D14-1162))
  * Bojanowski, P., Grave, E., Joulin, A., & Mikolov, T. (2016). Enriching word vectors with subword information. arXiv preprint arXiv:1607.04606. ([PDF](https://arxiv.org/pdf/1607.04606.pdf))

## Topic 6: Topic Modeling as a Distributed Reprentation
* Topic modeling overview & Latent Semantic Analysis (LSA)
* Probabilistic Latent Semantic Analysis: pLSA
* LDA: Document Generation Process
* LDA Inference: Gibbs Sampling
* LDA Evaluation
* Reading Materials
  * Deerwester, S., Dumais, S. T., Furnas, G. W., Landauer, T. K., & Harshman, R. (1990). Indexing by latent semantic analysis. Journal of the American society for information science, 41(6), 391. ([PDF](http://lsa.colorado.edu/papers/JASIS.lsi.90.pdf))
  * Dumais, S. T. (2004). Latent semantic analysis. Annual review of information science and technology, 38(1), 188-230.
  * Hofmann, T. (1999, July). Probabilistic latent semantic analysis. In Proceedings of the Fifteenth conference on Uncertainty in artificial intelligence (pp. 289-296). Morgan Kaufmann Publishers Inc. ([PDF](http://www.iro.umontreal.ca/~nie/IFT6255/Hofmann-UAI99.pdf))
  * Hofmann, T. (2017, August). Probabilistic latent semantic indexing. In ACM SIGIR Forum (Vol. 51, No. 2, pp. 211-218). ACM.
  * Blei, D. M. (2012). Probabilistic topic models. Communications of the ACM, 55(4), 77-84. ([PDF](http://delivery.acm.org/10.1145/2140000/2133826/p77-blei.pdf?ip=175.114.11.68&id=2133826&acc=OPEN&key=4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35%2E6D218144511F3437&__acm__=1524148444_1a7687d674528eeabc9a97afa2db5a29))
  * Blei, D. M., Ng, A. Y., & Jordan, M. I. (2003). Latent dirichlet allocation. Journal of machine Learning research, 3(Jan), 993-1022. ([PDF](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf))
* Recommended video lectures
  * LDA by D. Blei ([Lecture Video](http://videolectures.net/mlss09uk_blei_tm/))
  * Variational Inference for LDA by D. Blei ([Lecture Video](https://www.youtube.com/watch?v=Dv86zdWjJKQ&t=113s))

## Topic 7: Language Modeling & Pre-trained Models
* Sequence-to-Sequence Learning
* Transformer
* ELMo: Embeddings from Language Models
* GPT: Generative Pre-Training of a Language Model
* BERT: Bidirectional Encoder Representations from Transformer
* GPT-2: Language Models are Unsupervised Multitask Learners

## Topic 8: Dimensionality Reduction
* Dimensionality Reduction
* Supervised Feature Selection
* Reading materials
  * Maaten, L. V. D., & Hinton, G. (2008). Visualizing data using t-SNE. Journal of machine learning research, 9(Nov), 2579-2605. ([PDF](http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf)) ([Homepage](https://lvdmaaten.github.io/tsne/))

## Topic 9: Document Classification
* Document classification overview
* Naive Bayesian classifier
* RNN-based document classification
* CNN-based document classification
* Reading materials
  * Kim, Y. (2014). Convolutional neural networks for sentence classification. arXiv preprint arXiv:1408.5882. ([PDF](http://www.aclweb.org/anthology/D14-1181))
  * Zhang, X., Zhao, J., & LeCun, Y. (2015). Character-level convolutional networks for text classification. In Advances in neural information processing systems (pp. 649-657) ([PDF](https://arxiv.org/pdf/1509.01626.pdf))
  * Lee, G., Jeong, J., Seo, S., Kim, C, & Kang, P. (2018). Sentiment classification with word localization based on weakly supervised learning with a convolutional neural network. Knowledge-Based Systems, 152, 70-82. ([PDF](https://www.sciencedirect.com/science/article/pii/S0950705118301710))
  * Yang, Z., Yang, D., Dyer, C., He, X., Smola, A., & Hovy, E. (2016). Hierarchical attention networks for document classification. In Proceedings of the 2016 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (pp. 1480-1489). ([PDF](http://www.aclweb.org/anthology/N16-1174))
  * Bahdanau, D., Cho, K., & Bengio, Y. (2014). Neural machine translation by jointly learning to align and translate. arXiv preprint arXiv:1409.0473. ([PDF](https://arxiv.org/pdf/1409.0473.pdf))
  * Luong, M. T., Pham, H., & Manning, C. D. (2015). Effective approaches to attention-based neural machine translation. arXiv preprint arXiv:1508.04025. ([PDF](https://arxiv.org/pdf/1508.04025.pdf))

## Topic 10: Sentiment Analysis
* Architecture of sentiment analysis
* Lexicon-based approach
* Machine learning-based approach
* Reading materials
  * Hamilton, W. L., Clark, K., Leskovec, J., & Jurafsky, D. (2016, November). Inducing domain-specific sentiment lexicons from unlabeled corpora. In Proceedings of the Conference on Empirical Methods in Natural Language Processing. Conference on Empirical Methods in Natural Language Processing (Vol. 2016, p. 595). NIH Public Access. ([PDF](https://nlp.stanford.edu/pubs/hamilton2016inducing.pdf))
  * Zhang, L., Wang, S., & Liu, B. (2018). Deep learning for sentiment analysis: A survey. Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery, 8(4), e1253. ([PDF](https://arxiv.org/ftp/arxiv/papers/1801/1801.07883.pdf))



