# Awesome Partial Label Learning

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

A collection of papers and related materials dedicated to partial label learning.

**Partial Label Leaning** is an emerging weakly-supervised learning framework where each training example is associated with multiple candidate labels among which only one label is valid. The task of partial label learning is to learn a multi-class classification model from the partial label training examples, which can assign proper class label for the unseen instance in prediction phase. The task of learning from examples with candidate label sets naturally arises under many real-world scenarios, such as web mining, multimedia content analysis, ecoinformatics, natural language processing, etc.

# Table of Contents

# Papers

## Surveys

- [A brief introduction to weakly supervised learning](https://academic.oup.com/nsr/article/5/1/44/4093912)(National Science Review 2018) - This article is a classic survey on weakly-supervised learning.
- [Disambiguation-free partial label learning](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2019&filename=PZKX201909001&v=MjQwNDZxZll1WnRGQ25uVTd2SU5UZkFkckc0SDlqTXBvOUZaWVI4ZVgxTHV4WVM3RGgxVDNxVHJXTTFGckNVUjc=)(SCIENCE CHINA Information Sciences 2019) - This article is an up-to-date survey on partial label learning.

## Traditional PLL problems

### Identification-based methods
- [Learning with multiple labels](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.91.8113&rep=rep1&type=pdf)(NIPS'03) - A maximum likelihood approach with expectation maximization (PL-EM).
- [A conditional multinomial mixture model for superset label learning](http://papers.nips.cc/paper/4597-a-conditional-multinomial-mixture-model-for-superset-label-learning.pdf)(NIPS'12) - Logistic StickBreaking Conditional Multinomial Model (LSB-CMM).
- [Maximum margin partial label learning](http://palm.seu.edu.cn/zhangml/files/ACML'15.pdf)(ACML'15) - M3PL which maximize the margin between the maximum output of candidate labels and the maximum output of any other labels.
- [Maximum margin partial label learning](http://palm.seu.edu.cn/zhangml/files/MLJ'16.pdf)(Machine Leaning 2017) - A extended version of M3PL in ACML'15.
- [Classification with partial labels](https://dl.acm.org/doi/10.1145/1401890.1401958)(KDD'08) - PL-SVM which maximize the margin between the maximum output of candidate labels and maximum output of non-candidate labels.

### Averaging-based methods
- [Learning from partial labels](http://jmlr.org/papers/volume12/cour11a/cour11a.pdf)(JMLR 2011) - Convex Learning from Partial Labels (CLPL) which distinguish the average output of candidate labels from that of non-candidate labels.
- [Learning from ambiguously labeled images](https://ieeexplore.ieee.org/document/5206667/)(CVPR'09) A shorter version of CLPL in JMLR 2011.

### Other methods
- [Learning from Ambiguously Labeled Face Images](https://ieeexplore.ieee.org/document/7968363/)(TPAMI 2018)
- [Ambiguously labeled learning using dictionaries](https://ieeexplore.ieee.org/document/6906287)(TIFS 2014)
