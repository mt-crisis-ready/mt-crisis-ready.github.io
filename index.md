---
layout: default
---

Communication in times of crisis is essential. However, there is often a mismatch between the language of governments, aid providers, doctors, and those to whom they are providing aid. Commercial MT systems are reasonable tools to turn to in these scenarios. But how effective are these tools for translating to and from low resource languages, particularly in the crisis or medical domain? 

In the study **Is Machine Translation Ready for the Next Crisis or Pandemic** [(Bansal et al., 2026)](https://arxiv.org/abs/2601.10082), a paper to be presented at the first annual [Language Technology for Crisis Preparedness or Response (LT4CPR)](https://lt4cpr.github.io/aacl2026-workshop-LT4CPR/) workshop (co-located with [AACL-IJCNLP](https://2026.aaclnet.org/) in Hengqin, China in November 2026), the authors evaluated the quality of five existing Machine Translation services. These services, namely, Google Translate, Microsoft Translator, GPT, Gemini and Claude, were evaluated against the [TICO-19 benchmark test set]( https://tico-19.github.io/). The TICO-19 benchmark contains pandemic and medically related content consisting of 2,100 sentences that are n-ways parallel across 36 different languages, many of which are low- to medium-resource languages spoken in Africa and Southeast Asia. The goal of [Bansal et al., 2026](https://arxiv.org/abs/2601.10082) was to determine the "usability" of these commercial MT tools in crisis and pandemic settings for the entire set of TICO-19 languages when paired with English (both from and to). This was done by evaluating the quality of the output retrieved from these engines using multiple metrics, and then setting a threshold of usability on these metrics (see the paper for more details).

This repository was created to host **all** data that was translated as part of the [Bansal et al., 2026](https://arxiv.org/abs/2601.10082) study. This includes snapshots for 2026 for the five translation services (including three snapshots for GPT, namely, GPT-4o, GPT-5.4 and GPT-5.4-mini), and additional snapshots in 2023 and 2025 for Microsoft Translator and Google Translate (2,100 sentences per language and direction per snapshot). Also included are all code used to retrieve the data from the various services, as well as code used to evaluate the output. Evaluation metrics that were used include BLEU, CHRF, CHRF++, BertScore and COMET. (A complete set of scores across all languages can be found in the appendices of the [Bansal et al., 2026](https://arxiv.org/abs/2601.10082) paper.)

## **Citation Requirements**
If you use any of the data from the snapshots or their evaluations, or any of the code used in their retrieval, please cite the [Bansal et al., 2026](https://arxiv.org/abs/2601.10082) paper. The citation is as follows (or in [bib](./bib.md) format):

    Vipasha Bansal, William D. Lewis, Nicole Mihaylova, Elizabeth Brown, and Benjamin Pong. 2026. 
    "Is MT Ready for the Next Crisis or Pandemic?" In Proceedings of the Language Technologies 
    for Crisis Preparedness and Response (LT4CPR Workshop), Hengqin, Zhuhai, China. 
    Association for Computational Linguistics. https://arxiv.org/abs/2601.10082.

## **Downloads**
See the [files page](./files.html) for information about the data and to download output translation files.

## **Communications**

The results of this paper have been used in [(Wilson et al., 2026)](https://arxiv.org/abs/2601.10082) to (**FILL IN HERE and update link**).

## **Future Research**

## **Contact**

Please contact the corresponding author of [Bansal et al., 2026](https://arxiv.org/abs/2601.10082), Vipasha Bansal, at vipashab [at] uw [dot] edu.

## **Acknowledgments**

This work was partially supported by the National Science Foundation under the award CIRC 2346335. We would like to thank the students of the Spring 2023, 2025 and 2026 LT4CPR graduate seminars at the University of Washington (Priyam Basu, Melody Bechler, Allison Burton, Alexandra Cassell, Jose Cols, Richard Forrester, Chelsea Kendrick, Lily Kurek, Vanesa Marar, Ijeoma Osakwe, Yongsin Park, Anantha Rao, Helen Salgi, and Natasha Schimka) for their helpful input and suggestions in the [Bansal et al., 2026](https://arxiv.org/abs/2601.10082) paper and ultimately for this repository. Special thanks also goes to Jen Wilson, whose very closely related paper presented at the same LT4CPR workshop [(Wilson et al., 2026)](https://arxiv.org/abs/2601.10082), along with her work with emergency managers across the United States, spurred many changes to the paper, which led directly to the creation of this repository. 

## **License**

All content is made publicly available through a Creative Commons CC BY license.
