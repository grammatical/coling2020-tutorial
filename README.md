# A Crash Course in Automatic Grammatical Error Correction

This repository contains materials for our tutorial on automatic grammatical
error correction: R. Grundkiewicz, C. Bryant, M. Felice: [_A Crash Course in
Automatic Grammatical Error
Correction_](https://www.aclweb.org/anthology/2020.coling-tutorials.6/),
COLING 2020.

Links and materials:

* [Tutorial proposal with the recommended reading list](https://www.aclweb.org/anthology/2020.coling-tutorials.6.pdf)
* [Slides (Parts I-V)](/slides/GEC_tutorial_2020.pdf)
* [Bibliography](/slides/gec2020.bib)
* [List of GEC resources](#list-of-gec-resources)


## Tutorial outline

Part I: Introduction

* About the tutorial
* Task definition
* Challenges

Part II: Historical and recent approaches

* Rule-based methods
* Language models
* Error-type classifiers
* Statistical machine translation
* Deep neural networks
* Shared tasks

Part III: Data and evaluation

* Data annotation
* Error corpora
* Evaluation metrics
* Human evaluation

Part IV: Neural grammatical error correction

* Neural approach to GEC
* GEC as low-resource NMT
* Data sparsity
* Correction efficacy
* Beyond the NMT framework

Part V: Recent and future work

* Findings from the BEA-2019 shared task
* Towards unsupervised GEC
* Non-English languages
* Future work


## List of GEC resources

Data sets, evaluation scripts and other resources related to the field of automatic grammatical error correction.

### Datasets

Publicly available error corpora for English:

- W&I+LOCNESS Corpora [[paper]](https://www.cl.cam.ac.uk/~hy260/WI-cefr.pdf) [[download v2.1]](https://www.cl.cam.ac.uk/research/nl/bea2019st/data/wi+locness_v2.1.bea19.tar.gz)
- FCE Data Set [[paper]](https://www.aclweb.org/anthology/P11-1019) [[download v2.1]](https://www.cl.cam.ac.uk/research/nl/bea2019st/data/fce_v2.1.bea19.tar.gz)
- JFLEG (JHU FLuency-Extended GUG) Corpus [[download]](https://github.com/keisks/jfleg/)
- AESW (Automated Evaluation of Scientific Writing Data Set) [[download v1.2]](http://textmining.lt/aesw/aesw2016down.html)
- NUCLE (NUS Corpus of Learner English) [[paper]](https://www.aclweb.org/anthology/W13-1703) [[download v3.3]](https://www.comp.nus.edu.sg/~nlp/corpora.html)
- Annotated Test Data from the CoNLL 2013 & 2014 Shared Task [[CoNLL-2013]](https://www.comp.nus.edu.sg/~nlp/conll13st/release2.3.1.tar.gz) [[CoNLL-2014]](https://www.comp.nus.edu.sg/~nlp/conll14st/conll14st-test-data.tar.gz)
- 8 additional annotations for the CoNLL 2014 data set [[paper]](https://www.aclweb.org/anthology/P15-1068) [[download]](https://www.comp.nus.edu.sg/~nlp/sw/10gec_annotations.zip)
- Lang-8 Learner Corpora [[download v2.0]](http://cl.naist.jp/nldata/lang-8/) [[download pre-processed]](http://data.statmt.org/romang/gec-emnlp16/lang8.tgz)
- The WikEd Error Corpus [[download v1.0]](https://github.com/snukky/wikiedits#wiked-error-corpus)
- GMEG data sets [[paper]](https://www.mitpressjournals.org/doi/full/10.1162/tacl_a_00282) [[download]](https://github.com/grammarly/GMEG)
- CWEB (Corrected Websites) data sets [[paper]](https://www.aclweb.org/anthology/2020.emnlp-main.680.pdf) [[download]](https://github.com/SimonHFL/CWEB)

System outputs:

- System outputs from the CoNLL 2014 Shared Task [[download]](https://www.comp.nus.edu.sg/~nlp/conll14st/official_submissions.tar.gz)
- System outputs from the BEA 2019 Shared Task [[download]](https://www.cl.cam.ac.uk/research/nl/bea2019st/data/system_output.bea19.tar.gz)

Publicly available error corpora for other languages:

- Chinese: NLPCC 2018 Task 2 GEC [[paper]](http://tcci.ccf.org.cn/conference/2018/papers/EV11.pdf) [[website]](https://github.com/zhaoyyoo/NLPCC2018_GEC), NLPTEA 2016 CGED [[paper]](https://www.aclweb.org/anthology/W16-4906) [[website]](http://ir.itc.ntnu.edu.tw/lre/nlptea16cged.htm)
- Czech: AKCES-GEC [[paper]](https://www.aclweb.org/anthology/D19-5545.pdf) [[website]](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-3057)
- German: Falko & MERLIN Corpora [[paper]](http://aclweb.org/anthology/W18-6111) [[website]](https://github.com/adrianeboyd/boyd-wnut2018/#falko--merlin-corpora)
- Polish: PlEWiC [[website]](http://romang.home.amu.edu.pl/plewic/)
- Russian: RULEC-GEC dataset [[paper]](http://cogcomp.org/papers/russianGrammar-final.pdf) [[website]](https://github.com/arozovskaya/RULEC-GEC)

### Metrics

- M2Scorer [[software]](https://github.com/nusnlp/m2scorer) [[paper]](https://www.aclweb.org/anthology/N12-1067)
- ERRANT [[software]](https://github.com/chrisjbryant/errant) [[paper]](https://www.aclweb.org/anthology/P17-1074)
- GLEU [[software]](https://github.com/keisks/jfleg/tree/master/eval) [[paper #1]](https://www.aclweb.org/anthology/P15-2097) [[paper #2]](https://arxiv.org/pdf/1605.02592.pdf)

### Shared Tasks

* BEA 2019 Shared Task: Grammatical Error Correction [[website]](https://www.cl.cam.ac.uk/research/nl/bea2019st/) [[paper]](https://www.aclweb.org/anthology/W19-4406.pdf)
* NLPCC 2018 Shared Task 2 - Grammatical Error Correction for Chinese [[website]](https://github.com/zhaoyyoo/NLPCC2018_GEC) [[paper]](http://tcci.ccf.org.cn/conference/2018/papers/EV11.pdf)
* Automated Evaluation of Scientific Writing Shared Task 2016 [[website]](http://textmining.lt/aesw/)
* The Second QALB Shared Task on Automatic Text Correction for Arabic 2015 [[paper]](https://www.aclweb.org/anthology/W15-3204.pdf)
* CoNLL-2014 Shared Task: Grammatical Error Correction [[website]](https://www.comp.nus.edu.sg/~nlp/conll14st.html) [[paper]](https://www.aclweb.org/anthology/W14-1701.pdf)
* CoNLL-2013 Shared Task: Grammatical Error Correction [[website]](https://www.comp.nus.edu.sg/~nlp/conll13st.html) [[paper]](https://www.aclweb.org/anthology/W13-3601.pdf)

### Other materials

- http://nlpprogress.com/english/grammatical_error_correction.html
- [Slides from the COLING2014 tutorial on Automatic GEC for Language Learners](https://slideplayer.com/slide/4549206/)

(This list is incomplete, please feel free to open a pull request if you would like to add something to the list)


## Reference

```
@inproceedings{grundkiewicz-etal-2020-crash,
  title = "A Crash Course in Automatic Grammatical Error Correction",
  author = "Grundkiewicz, Roman and Bryant, Christopher and Felice, Mariano",
  booktitle = "Proceedings of the 28th International Conference
               on Computational Linguistics: Tutorial Abstracts",
  month = dec,
  year = "2020",
  address = "Barcelona, Spain (Online)",
  publisher = "International Committee for Computational Linguistics",
  url = "https://www.aclweb.org/anthology/2020.coling-tutorials.6",
  pages = "33--38",
}
```
