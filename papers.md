---
layout: default
title: Papers
active_tab: papers
---

#### Papers that are recommended for presentation are denoted by **&#9829;**

### <font color="blue">Introduction</font> (Lecture [1](slides/Lec1-Intro-2017.pptx))

#### General: ML in NLP

The following two papers are here for historical reasons. These are survey papers that describe the state of the art in Machine Learning for NLP in 1999 and 2005.

*   C. Cardie and R. Mooney, [Guest Editors' Introduction: Machine Learning and Natural Language Processing.](https://www.cs.cornell.edu/home/cardie/papers/mljnll-editorial.ps) Machine Learning Journal. Special Issue on Natural Language Learning 1999
*   P. Fung and and D. Roth, [Guest Editors' Introduction: Machine Learning in Speech and Language Technologies.](http://l2r.cs.uiuc.edu/~danr/Papers/FungRo05.pdf) Machine Learning Journal, Special Issue on Natural Language Learning 2005

#### Generative and Discriminative Models

*   A. Ng and M. Jordan [On Discriminative vs. Generative Classifiers. A comparison of Logistics Regression and naive Bayes](https://papers.nips.cc/paper/2020-on-discriminative-vs-generative-classifiers-a-comparison-of-logistic-regression-and-naive-bayes.pdf) NIPS 2002
*   D. Roth [Learning to Resolve Natural Language Ambiguities: A Unified Approach](http://l2r.cs.uiuc.edu/~danr/Papers/aaai98.pdf) AAAI 1998
*   D. Roth [Learning in Natural Language](http://l2r.cs.uiuc.edu/~danr/Papers/ijcai99r.pdf) IJCAI 1999

#### Multiclass

*   S. Har-Peled, D. Roth and D. Zimak, [Constraint Classification for Multiclass Classification and Ranking](http://cogcomp.cs.illinois.edu/page/publication_view/108) NIPS 2003
*   Y. Crammer and T. Singer, [Ultraconservative Online Algorithms for Multiclass Problems](http://www.jmlr.org/papers/volume3/crammer03a/crammer03a.pdf) JMLR 2003
*   Y. Even-Zohar and D. Roth, [A Sequential Model for Multi Class Classification](http://l2r.cs.uiuc.edu/~danr/Papers/emnlp01.pdf) EMNLP 2001
*   X. Li and D. Roth, X. Lin and D. Roth, [Learning Questions Classifiers: The Role of Semantic Information](http://cogcomp.cs.illinois.edu/papers/LiRo05a.pdf) NLE 2005
*   M. Gupta, S. Bengio and J. Weston, [Training Highly Multiclass Classifiers](http://jmlr.org/papers/volume15/gupta14a/gupta14a.pdf) JMLR 2014

### <font color="blue">Basic Structured Models: Sequential Models</font>

#### Background

*   Chapter 9-10 Manning and Schutze
*   Y. Bengio, [Markovian Models for Sequential Data](ftp://ftp.icsi.berkeley.edu/pub/ai/jagota/vol2_5.pdf), Neural Computing Surveys 1999.
*   L. R. Rabiner, [A Tutorial on Hidden Markov Models and Selected Applications in Speech Recognition](http://www.ece.ucsb.edu/Faculty/Rabiner/ece259/Reprints/tutorial%20on%20hmm%20and%20applications.pdf), IEEE 1989.

#### Inference with Classifiers

*   **&#9829;**  V. Punyakanok and D. Roth, [The Use of Classifiers in Sequential Inference](http://cogcomp.cs.illinois.edu/papers/nips01.pdf), NIPS 2001
*   A. McCallum, D. Freitag, and F. Pereira, [Maximum entropy Markov models for information extraction and segmentation](http://www.ai.mit.edu/courses/6.891-nlp/READINGS/maxent.pdf), ICML 2000.

#### CRF

*   **&#9829;**  J. Lafferty, A. McCallum, F. Pereira [Conditional Random Fields: Probabilistic Models for Segmenting and Labeling Sequence Data](http://repository.upenn.edu/cgi/viewcontent.cgi?article=1162&context=cis_papers) ICML 2002
*   C. Sutton and A. McCallum [Introduction to Conditional Random Fields for Relational Learning](https://people.cs.umass.edu/~mccallum/papers/crf-tutorial.pdf) In Statistical Relational Learning, 2007
*   **&#9829;**  A. F. T. Martins, N. A. Smith, P. M. Q. Aguiar, and M. A. T. Figueiredo [Structured Sparsity in Structured Prediction](http://www.cs.cmu.edu/~nasmith/papers/martins+smith+aguiar+figueiredo.emnlp11b.pdf) EMNLP 2011
*   T. Vieira, R. Cotterell and J. Eisner [Speed-Accuracy Tradeoffs in Tagging with Variable-Order CRFs and Structured Sparsity](https://timvieira.github.io/doc/2016-emnlp-vocrf.pdf) EMNLP 2016

#### Structured Perceptron

*   M. Collins, [Discriminative Training for Hidden Markov Models: Theory and Experiments with Perceptron Algorithms](http://www.cs.columbia.edu/~mcollins/papers/tagperc.pdf) EMNLP 2002.
*   **&#9829;** K. Crammer, Y. Singer [Pranking with Ranking](https://pdfs.semanticscholar.org/906f/50f545890ca81231be7cec7c59555c679dba.pdf) NIPS 2002.
*   **&#9829;** L. Huang, S. Fayong, Y. Guo, [Structured Perceptron with Inexact Search](http://www.aclweb.org/anthology/N12-1015) NAACL 2012.
*    **&#9829;** R. McDonald, K. Hall, G. Mann [Distributed Training Strategies for the Structured Perceptron](http://www.aclweb.org/anthology/N10-1069) NAACL 2010.


**<font color="red">BONUS</font>**: To learn how to efficiently implement averaged perceptron (without storing weight vectors), refer Fig 2.3 on page 19 in [Hal Daume's thesis](http://www.umiacs.umd.edu/~hal/docs/daume06thesis.pdf).


#### SVM

*   C. Burges [A Tutorial on Support Vector Machines for Pattern Recognition](http://research.microsoft.com/en-us/um/people/cburges/papers/SVMTutorial.pdf), 1998
*   **&#9829;**  B. Taskar, C. Guestrin and D. Koller [Max-Margin Markov Networks](https://papers.nips.cc/paper/2397-max-margin-markov-networks.pdf) NIPS 2003
*   **&#9829;**  I. Tsochantaridis, T. Hofman, T. Joachims, Y. Altun [Large Margin Methods for Structured and Interdependent Output Variables](http://www.jmlr.org/papers/volume6/tsochantaridis05a/tsochantaridis05a.pdf) JMLR 2005

### <font color="blue">Constrained Conditional Models</font>

#### Constraint-based Models

*   D. Roth and W. Yih, [A Linear Programming Formulation for Global Inference in Natural Language Tasks.](http://l2r.cs.uiuc.edu/~danr/Papers/RothYi04.pdf) CoNLL 2004
*   **&#9829;** D. Roth and W. Yih [Global Inference for Entity and Relation Identification via a Linear Programming Formulation.](http://l2r.cs.uiuc.edu/~danr/Papers/RothYi07.pdf) Introduction to Statistical Relational Learning, 2007
*   M. Richardson and P. Domingos, [Markov Logic Networks](http://www.cs.kun.nl/~peterl/teaching/CI/markovlogic2006.pdf) Machine Learning Journal 2006

**<font color="red">BONUS</font>**: To learn how to convert boolean constraints to ILP constraints, refer,

*   W. Yih [Global Inference Using Integer Linear Programming](https://pdfs.semanticscholar.org/d7fe/bee4e936c5e165c8a9cc48786b97299c5043.pdf) Technical Report 2004.
#### Applications

*   **&#9829;**  J. Clarke and M. Lapata [Constraint-Based Sentence Compression: An Integer Programming Approach](http://jamesclarke.net/media/papers/clarke-lapata-acl06b.pdf) COLING/SCL 2006
*   **&#9829;**  S. Riedel and J. Clarke, [Incremental Integer Linear Programming for Non-projective Dependency Parsing](http://jamesclarke.net/media/papers/riedel-clarke-emnlp06.pdf) EMNLP 2006
*   **&#9829;** J. Clarke and M. Lapata [Global Inference for Sentence Compression: An Integer Linear Programming Approach](http://www.jair.org/papers/paper2433.html) JAIR 2008
*   **&#9829;**  A. F. T. Martins, N. A. Smith, and E. P. Xing, [Concise Integer Linear Programming Formulations for Dependency Parsing](https://homes.cs.washington.edu/~nasmith/papers/martins+smith+xing.acl09.pdf) ACL 2009
*   **&#9829;**  Y. Choi and C. Cardie, [Adapting a Polarity Lexicon Using Integer Linear Programming for Domain-Specific Sentiment Classification](https://www.cs.cornell.edu/home/cardie/papers/emnlp-2009.pdf) EMNLP 2009
*   **&#9829;**  X. Cheng and D. Roth, [Relational Inference for Wikification](http://cogcomp.cs.illinois.edu/papers/ChengRo13.pdf) EMNLP 2013.

### <font color="blue">Training Paradigms</font>

#### Training Paradigms: Constraint-based Models

*   **&#9829;**  V. Punyakanok, D. Roth, W. Yih, and D. Zimak [Learning and Inference over Constrained Output](http://l2r.cs.uiuc.edu/~danr/Papers/PRYZ05.pdf) IJCAI 2005
*   **&#9829;**  D. Roth, W. Yih [Integer Linear Programming Inference for Conditional Random Fields](http://l2r.cs.uiuc.edu/~danr/Papers/RothYi05.pdf) ICML 2005.

#### Distributed Output Representations

*   V. Srikumar and C. Manning [Learning Distributed Representations for Structured Output Prediction.](http://svivek.com/research/publications/SrikumarMa2014.pdf) NIPS 2014

#### Applications

*   **&#9829;**  B. Taskar, D. Klein, M. Collins, D. Koller and C. Manning. [Max-Margin Parsing](http://acl.ldc.upenn.edu/acl2004/emnlp/pdf/Taskar.pdf) EMNLP 2004
*   **&#9829;**  M. Collins [Discriminative Reranking for Natural Language Parsing](http://people.csail.mit.edu/mcollins/papers/rerank.ps) ICML 2000
*   **&#9829;** R. Johansson and P. Nugues [Dependency-based Semantic Role Labeling of PropBank.](http://www.aclweb.org/anthology/D08-1008) EMNLP 2008
*   **&#9829;**  V. Punyakanok, D. Roth and W. Yih, [The Importance of Syntactic Parsing and Inference in Semantic Role Labeling](http://l2r.cs.uiuc.edu/~danr/Papers/PunyakanokRoYi07.pdf) Computational Linguistics 2008.
*   **&#9829;**  Y. Yang and M-W. Chang, [S-MART: Novel Tree-based Structured Learning Algorithms Applied to Tweet Entity Linking,](http://research.microsoft.com/en-us/um/people/minchang/publication/YangChang15.pdf) ACL 2015.
*   **&#9829;**  K.-W. Chang and R. Samdani and D. Roth, [A Constrained Latent Variable Model for Coreference Resolution,](http://cogcomp.cs.illinois.edu/papers/ChangSaRo13.pdf) EMNLP 2013.

### <font color="blue">Unsupervised Learning and Indirect Supervision</font>

#### Constraint-Driven Learning

*   M. Chang, L. Ratinov, N. Rizzolo and D. Roth, [Learning and Inference with Constraints](http://l2r.cs.uiuc.edu/~danr/Papers/CRRR08.pdf) AAAI 2008.
*   **&#9829;**  M. Chang, L. Ratinov, and D. Roth, [Guiding Semi-Supervision with Constraint-Driven Learning](http://cogcomp.cs.illinois.edu/papers/ChangRaRo07.pdf) ACL 2007.
*   **&#9829;**  K. Ganchev, J. Graca, J. Gillenwater and B. Taskar, [Posterior Regularization for Structured Latent Variable Models](http://www.seas.upenn.edu/~taskar/pubs/pr_jmlr10.pdf) JMLR 2010.
*   **&#9829;**  K. Hall, R. McDonald, J. Katz-Brown and M. Ringgaard, [Training dependency parsers by jointly optimizing multiple objectives](http://www.ryanmcd.com/papers/augmented_lossEMNLP2011.pdf) EMNLP 2011.

#### Latent Variables

*   **&#9829;**  M. Chang, D. Goldwasser, D. Roth and V. Srikumar, [Discriminative Learning over Constrained Latent Representations](http://l2r.cs.uiuc.edu/~danr/Papers/CGRS10.pdf) NAACL 2010.
*   **&#9829;**  Chun-Nam John Yu and T. Joachims, [Learning Structural SVMs with Latent Variables](http://www.cs.cornell.edu/~cnyu/papers/icml09_latentssvm.pdf) ICML 2009.
*   A. McCallum, K. Bellare and F. Pereira, [A Conditional Random Field for Discriminatively-trained Finite-state String Edit Distance](http://www.cs.umass.edu/~mccallum/papers/crfstredit-uai05.pdf) UAI, 2005.
*   **&#9829;**  Sun, Xu, T. Matsuzaki, D. Okanohara and J. Tsujii, [Latent Variable Perceptron Algorithm for Structured Classification](http://ijcai.org/papers09/Papers/IJCAI09-208.pdf) IJCAI 2009.
*   Matsuzaki, Miyao, Tsujii [Probabilistic CFG with Latent Annotations](http://www.aclweb.org/anthology-new/P/P05/P05-1010.pdf) ACL 2005
*   **&#9829;**  Collobert and Weston [A Unified Architecture for Natural Language Processing: Deep Neural Networks with Multitask Learning.](http://ronan.collobert.com/pub/matos/2008_nlp_icml.pdf)
*   S. Petrov, L. Barrett, R. Thibaux and D. Klein, COLING/ACL 2006 [Learning Accurate, Compact, and Interpretable Tree Annotation](http://www.eecs.berkeley.edu/~petrov/data/acl06.pdf)
*   P. Liang, S. Petrov, M. Jordan, and D. Klein, EMNLP 2007 [The Infinite PCFG using Hierarchical Dirichlet Processes](http://www.cs.berkeley.edu/~pliang/papers/hdppcfg-emnlp2007.pdf)

#### Indirect Supervision

*   **&#9829;**  M. Chang, V. Srikumar, D. Goldwasser and D. Roth, [Structured Output Learning with Indirect Supervision](http://l2r.cs.uiuc.edu/~danr/Papers/CSGR10.pdf) ICML 2010.
*   **&#9829;**  Noah A. Smith and Jason Eisner, [Contrastive Estimation: Training Log-Linear Models on Unlabeled Data](http://acl.ldc.upenn.edu/P/P05/P05-1044.pdf) ACL 2005.
*   **&#9829;**  G.S. Mann and A. McCallum, [Generalized Expectation Criteria for Semi-Supervised Learning with Weakly Labeled Data](http://jmlr.csail.mit.edu/papers/volume11/mann10a/mann10a.pdf) JMLR 2010.

### <font color="blue">Inference</font>

#### Inference

*   **&#9829;**  T. Finley, T. Joachims, [Training Structural SVMs when Exact Inference is Intractable](https://www.cs.cornell.edu/people/tj/publications/finley_joachims_08a.pdf) ICML 2008.
*   **&#9829;**  C. Sutton and A. McCallum [Piecewise Pseudolikelihood for Efficient Training of Conditional Random Fields](https://people.cs.umass.edu/~mccallum/papers/pwpl-icml2007.pdf) ICML 2007
*   **&#9829;**  T. Joachims, T. Finley, Chun-Nam Yu, [Cutting-Plane Training of Structural SVMs](https://www.cs.cornell.edu/people/tj/publications/joachims_etal_09a.pdf) Machine Learning 2009.
*   **&#9829;**  T. Koo, A. M. Rush, M. Collins, T. Jaakkola, and D. Sontag, [Dual Decomposition for Parsing with Non-Projective Head Automata.](http://cs.nyu.edu/~dsontag/papers/KooEtAl_emnlp10.pdf) EMNLP 2010.
*   **&#9829;**  V. Srikumar, G. Kundu and D. Roth [On Amortizing Inference Cost for Structured Prediction](http://cogcomp.org/papers/SrikumarKuRo12.pdf) EMNLP 2012.


#### Search Based Inference

*   **&#9829;**  H. Daume, J. Langford, and D. Marcu, [Search-based Structured Prediction](http://hunch.net/~jl/projects/reductions/searn/searn.pdf) Machine Learning 2009
*   J.R. Doppa, A. Fern and P. Tadepalli, [HC-Search: A Learning Framework for Search-based Structured Prediction](http://www.jair.org/media/4212/live-4212-7985-jair.pdf) JAIR 2014
*   K.-W. Chang, A. Krishnamurthy, A. Agarwal, H. Daumé III, J. Langford, [Learning to Search Better Than Your Teacher](http://proceedings.mlr.press/v37/changb15.pdf) ICML 2015
*   T. Vieira and J. Eisner, [Learning to Prune: Exploring the Frontier of Fast and Accurate Parsing](https://transacl.org/ojs/index.php/tacl/article/viewFile/924/243) TACL 2017

### <font color="blue">Deep Learning</font>

*   Y. Goldberg [A Primer on Neural Network Models for Natural Language Processing](https://www.jair.org/media/4992/live-4992-9623-jair.pdf
    		       ). JAIR 2016.

#### Applications

*   Richard Socher, John Bauer, Christopher D. Manning, and Andrew Y. Ng, [Parsing With Compositional Vector Grammars](http://nlp.stanford.edu/pubs/SocherBauerManningNg_ACL2013.pdf). ACL 2013.
*   Sutskever, Ilya, Oriol Vinyals, and Quoc V. Le. [Sequence to sequence learning with neural networks](http://machinelearning.wustl.edu/mlpapers/paper_files/NIPS2014_5346.pdf). NIPS 2014.
*   **&#9829;**  S. Wiseman and A. M. Rush. [Sequence-to-sequence learning as beam-search optimization](https://arxiv.org/pdf/1606.02960.pdf). EMNLP 2016.
*   **&#9829;**  A. Karpathy, A. Joulin, and F. F. Li. [Deep fragment embeddings for bidirectional image sentence mapping](http://papers.nips.cc/paper/5281-deep-fragment-embeddings-for-bidirectional-image-sentence-mapping) NIPS, 2014.
*   **&#9829;**  L. Kong, C. Dyer, N. A. Smith [Segmental Recurrent Neural Networks](https://arxiv.org/pdf/1511.06018.pdf) ICLR 2016.
*   **&#9829;**  L. Yu, P. Blunsom, C. Dyer, E. Grefenstette, T. Kocisky [The Neural Noisy Channel](https://arxiv.org/pdf/1511.06018.pdf) ICLR 2017.
*   **&#9829;**  Y. Kim, C. Denton, L. Hoang, A. M. Rush [Structured Attention Networks](https://arxiv.org/abs/1702.00887) ICLR 2017.
*   **&#9829;**  E. Kiperwasser, Y. Goldberg [Easy-First Dependency Parsing with Hierarchical Tree LSTMs](http://aclweb.org/anthology/Q16-1032) TACL 2016.
