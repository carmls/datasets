# SNACS datasets

This repository contains pointers to various datasets of adposition/case supersenses in multiple languages.

The name of the language links to annotation guidelines if available. The guidelines version reflected in the corpus appears {in curly braces}.

## Collected release of English, Gujarati, Hindi, Japanese, Chinese

* <https://github.com/WesScivetti/snacs/tree/main/data>: A collection of [.conllulex](https://github.com/nert-nlp/streusle/blob/master/CONLLULEX.md) files for: English STREUSLE; English PASTRIE; English, Gujarati, Hindi, and Chinese Little Prince (all 27 chapters); and Japanese Little Prince (10 chapters).

## [English](https://arxiv.org/abs/1704.02134)

* [STREUSLE](https://github.com/nert-nlp/streusle/): Online reviews section of the English Web Treebank, obtained from the [Universal Dependencies](http://universaldependencies.org/) project. STREUSLE is fully annotated with SNACS (as well as other lexical semantic annotations) and served as the primary reference corpus in developing the [English SNACS guidelines](https://arxiv.org/abs/1704.02134). {EN v2.6} Citation: [Schneider et al. ACL 2018](http://aclweb.org/anthology/P18-1018)

* [_The Little Prince_](https://github.com/nert-nlp/English-Little-Prince-SNACS): {EN v2.5} All except Ch. 1, 4, 5, which are TBD.
   - Ch. 1, 4, and 5 were annotated in a pilot phase with older guidelines, as described in [Schneider et al. ACL 2018](http://aclweb.org/anthology/P18-1018), and need to be updated.

* [PASTRIE](https://github.com/nert-nlp/pastrie) (Reddit international English).  {EN v2.5} Citation: [Kranzlein et al. LAW 2020](https://www.aclweb.org/anthology/2020.law-1.10)

## Mandarin Chinese

* [_小王子(Xiǎo Wáng Zǐ) [The Little Prince]_](https://github.com/nert-nlp/Chinese-SNACS/). {based on EN v2.3} Citation: [Peng et al. LREC 2020](https://www.aclweb.org/anthology/2020.lrec-1.733)

## [Korean](https://github.com/jenahwang/k-snacs/blob/main/k-snacs-guideline-appendix-v0.9.pdf)

* [_어린왕자(Erin Wangca) [The Little Prince]_](https://github.com/jenahwang/k-snacs). {KO v0.9 based on EN v2.5} Citation: [Hwang et al. DMR 2020](https://www.aclweb.org/anthology/2020.dmr-1.6)

## Japanese

* [_星の王子さま(Hoshinoōjisama) [The Little Prince]_](https://github.com/t-aoyam/japanese-snacs). {based on EN v2.6} Ch. 1–10. Citation (paper includes guidelines): [Aoyama et al. LREC-COLING 2024](https://aclanthology.org/2024.lrec-main.839)

## German

* [_Der kleine Prinz [The Little Prince]_](https://github.com/nert-nlp/German-SNACS). {based on EN v2.0 (superset)/2.5 (revised subset)} Citation (paper includes guidelines): [Prange and Schneider *Künstliche Intelligenz* 2021](https://doi.org/10.1007/s13218-021-00712-y)

## [Hindi](https://arxiv.org/abs/2103.01399)

* [नन्हा राजकुमार(Nanhā Rājkumār) _[The Little Prince]_](https://github.com/aryamanarora/carmls-hi). {HI v1.0 based on EN v2.5} Citation: [Arora et al. LREC 2022](https://aclanthology.org/2022.lrec-1.612)

## [Gujarati](https://aclanthology.org/2023.findings-acl.696.pdf#PAX@./papers/5830.pax@72)

* [નાનકડો રાજકુમાર(Nānakado Rājakumār) _[The Little Prince]_](https://github.com/utahnlp/weak-verifiers). {based on HI v1.0/EN v2.5} Citation: [Mehta and Srikumar ACL Findings 2023](https://aclanthology.org/2023.findings-acl.696)

## Finnish, Latin (partial)

<https://github.com/dchensta/adpositions_case> contains two datasets:

* **Finnish:** [Pikku Prinssi _[The Little Prince]_](https://github.com/dchensta/adpositions_case/blob/main/full_annotations/pp_4-5.csv), chapters 4 and 5. {based on EN v2.5}
* **Latin:** [Regulus _[The Little Prince]_](https://github.com/dchensta/adpositions_case/blob/main/full_annotations/regulus_4-5.csv), chapters 4 and 5. {based on EN v2.5}

Citation: [Chen and Hulden LREC 2022](https://aclanthology.org/2022.lrec-1.279)

# References

* Jena D. Hwang, Hanwool Choe, Na-Rae Han, and Nathan Schneider. "[K-SNACS: Annotating Korean adposition semantics](https://www.aclweb.org/anthology/2020.dmr-1.6/)." In Proceedings of the Second International Workshop on Designing Meaning Representations, pp. 53-66. 2020.
* Michael Kranzlein, Emma Manning, Siyao Peng, Shira Wein, Aryaman Arora, and Nathan Schneider. "[PASTRIE: A Corpus of Prepositions Annotated with Supersense Tags in Reddit International English](https://www.aclweb.org/anthology/2020.law-1.10/)." In Proceedings of the 14th Linguistic Annotation Workshop, pp. 105-116. 2020.
* Siyao Peng, Yang Liu, Yilun Zhu, Austin Blodgett, Yushi Zhao, and Nathan Schneider. "[A Corpus of Adpositional Supersenses for Mandarin Chinese](https://www.aclweb.org/anthology/2020.lrec-1.733)." In Proceedings of The 12th Language Resources and Evaluation Conference, pp. 5986-5994. 2020.
* Jakob Prange and Nathan Schneider. "[Draw *mir* a sheep: a supersense-based analysis of German case and adposition semantics](https://doi.org/10.1007/s13218-021-00712-y)." _KI-Künstliche Intelligenz_ 35(291–306). 2021.
* Nathan Schneider, Jena D. Hwang, Vivek Srikumar, Jakob Prange, Austin Blodgett, Sarah Moeller, Aviram Stern, Adi Shalev, and Omri Abend. "[Comprehensive Supersense Disambiguation of English Prepositions and Possessives](http://aclweb.org/anthology/P18-1018)." In Proceedings of the 56th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers), pp. 185-196. 2018.
* Aryaman Arora, Aryaman Arora, Nitin Venkateswaran, and Nathan Schneider. "[MASALA: Modelling and Analysing the Semantics of Adpositions in Linguistic Annotation of Hindi](https://aclanthology.org/2022.lrec-1.612)." In Proceedings of The Thirteenth Language Resources and Evaluation Conference, pp. 5696–5704. 2022.
* Maitrey Metha and Vivek Srikumar. "[Verifying Annotation Agreement without Multiple Experts: A Case Study with Gujarati SNACS](https://aclanthology.org/2023.findings-acl.696)." In Findings of the Association for Computational Linguistics: ACL 2023, pp. 10941-10958. 2023.
* Daniel Chen and Mans Hulden. "[My Case, For an Adposition: Lexical Polysemy of Adpositions and Case Markers in Finnish and Latin](https://aclanthology.org/2022.lrec-1.279)". In Proceedings of the Thirteenth Language Resources and Evaluation Conference, pp. 2610-2616. 2022.
* Tatsuya Aoyama, Chihiro Taguchi, and Nathan Schneider. "[J-SNACS: Adposition and Case Supersenses for Japanese Joshi](https://aclanthology.org/2024.lrec-main.839)." In Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024), pp. 9604–9614. 2024.
* Wesley Scivetti, Lauren Levine, and Nathan Schneider. "[Multilingual Supervision Improves Semantic Disambiguation of Adpositions](https://aclanthology.org/2025.coling-main.247)." In Proceedings of the 31st International Conference on Computational Linguistics (COLING 2025), pp. 3655–3669. 2025.
