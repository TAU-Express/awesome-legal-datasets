# Awesome Legal Datasets

A curated list of datasets for legal NLP / legal AI, for evaluation and research use.

Part of the [ACE-EXP](https://github.com/TAU-Express/ace-exp) legal-AI evaluation project.

## Contents

- [Datasets](#datasets)
- [Contributing](#contributing)
- [License](#license)

## Datasets

| Name | Jurisdiction | Task | License | Source |
|---|---|---|---|---|
| ECtHR (Chalkidis 2019) | European Court of Human Rights; English | Multi-label violation classification + binary; paragraph-level long-doc | CC-BY-4.0 | https://huggingface.co/datasets/coastalcph/lex_glue |
| CAIL2018 | China (criminal); Chinese | Law-article + charge prediction (multi-class) + prison-term (regression) | Unknown (competition) — check repo | https://github.com/thunlp/CAIL |
| ILDC / CJPE | India (Supreme Court); English | Binary judgment prediction (accept/reject) + rationale extraction | Not confirmed | https://github.com/Exploration-Lab/CJPE |
| Swiss-Judgment-Prediction (SJP) | Switzerland (Fed. Supreme Court); DE/FR/IT | Binary outcome (approval/dismissal); fairness metadata | CC-BY-SA-4.0 | https://huggingface.co/datasets/rcds/swiss_judgment_prediction |
| MultiEURLEX | EU; 23 languages | Multi-label classification vs EUROVOC; zero-shot cross-lingual | Not confirmed — check HF card | https://huggingface.co/datasets/nlpaueb/multi_eurlex |
| SLJA (Syllogistic LJP) | China (criminal); Chinese | Statute + facts -> judgment via legal syllogism | Not confirmed | https://aclanthology.org/2023.emnlp-main.864/ |
| NyayaAnumana + INLegalLlama | India; English | Largest Indian LJP dataset (claimed) + companion model | Not confirmed | https://arxiv.org/abs/2412.08385 |
| CUAD | US commercial contracts; English | Extractive QA / span extraction; 41 clause types | CC-BY-4.0 | https://huggingface.co/datasets/theatticusproject/cuad-qa |
| ContractNLI | US NDAs; English | Document-level NLI (E/C/NotMentioned) + evidence span | CC-BY-NC-SA-4.0 | https://stanfordnlp.github.io/contract-nli/ |
| LEDGAR | US SEC filings; English | Multi-label / multi-class provision classification | CC-BY-4.0 (LexGLUE copy) | https://github.com/dtuggener/LEDGAR_provision_classification |
| MAUD | US M&A agreements; English | Multiple-choice reading comprehension; 92 questions | CC-BY-4.0 | https://huggingface.co/datasets/theatticusproject/maud |
| UNFAIR-ToS (CLAUDETTE) | EU consumer ToS; English | Multi-label sentence classification; 8 unfair-clause types | CC-BY-4.0 (LexGLUE) | https://huggingface.co/datasets/coastalcph/lex_glue |
| German LER | Germany (federal courts); German | NER (token classification); 19 fine-grained classes | CC-BY-4.0 | https://github.com/elenanereiss/Legal-Entity-Recognition |
| InLegalNER | India (court judgments); English | NER; 14 entity types; preamble + judgment splits | Not confirmed | https://huggingface.co/datasets/opennyaiorg/InLegalNER |
| 3CEL | Spain (public procurement); Spanish | Clause/entity span tagging; 19 categories | Not confirmed | https://arxiv.org/abs/2501.15990 |
| COLIEE (annual competition) | Japan + Canada; English/Japanese | Case+statute retrieval (T1/3) + entailment/QA (T2/4) | Registered participants only | https://coliee.org |
| LeCaRD / LeCaRDv2 | China (criminal, SPC); Chinese | Similar-case retrieval (ranked) | Not confirmed | https://github.com/myx666/LeCaRD |
| BSARD (+ LLeQA) | Belgium; French | Statutory article retrieval; LLeQA adds long-form QA | CC-BY-NC-SA-4.0 | https://huggingface.co/datasets/maastrichtlawtech/bsard |
| GerDaLIR | Germany; German | Case/passage retrieval (citation-derived queries) | Not confirmed | https://github.com/lavis-nlp/GerDaLIR |
| STARD | China; Chinese | Statute retrieval from real lay (non-professional) queries | Not confirmed | https://github.com/oneal2000/STARD |
| AILA 2019 (FIRE) | India; English | Precedent + statute retrieval | CC-BY-4.0 | https://github.com/Law-AI/aila-2019-dataset |
| CLERC | US federal case law; English | Citation retrieval + retrieval-augmented legal analysis | Not confirmed | https://github.com/abehou/CLERC |
| LegalBench-RAG | US contracts; English | Precise snippet-level retrieval for RAG | CC-BY-4.0 (per arXiv) | https://github.com/zeroentropy-ai/legalbenchrag |
| Bar Exam QA (reglab legal-rag) | US; English | MBE-style Qs + gold passages; ~900K passage pool | Not confirmed | https://reglab.github.io/legal-rag-benchmarks/ |
| JEC-QA | China; Chinese | Multiple-choice QA from China bar exam | Research use | http://jecqa.thunlp.org/ |
| PrivacyQA | US; English | Relevance-classification QA over privacy policies | Research use | https://github.com/AbhilashaRavichander/PrivacyQA_EMNLP |
| SARA | US; English | Statute + facts -> entailment + numeric tax computation | MIT (LegalBench task) | https://hazyresearch.stanford.edu/legalbench/tasks/sara_entailment.html |
| CaseHOLD | US case law; English | Multiple-choice holding identification | CC-BY-4.0 | https://huggingface.co/datasets/casehold/casehold |
| LEXam | Switzerland/EU + intl law; multi | Law-school exam Qs: MCQ + open-ended (rubric-graded) | CC-BY-4.0 | https://huggingface.co/datasets/LEXam-Benchmark/LEXam |
| BillSum | US (federal + CA); English | Single-doc summarization of legislative bills | CC0-1.0 | https://huggingface.co/datasets/FiscalNote/billsum |
| EUR-Lex-Sum | EU; 24 languages | Long-form single/cross-lingual summarization of EU acts | Not confirmed — check repo | https://github.com/achouhan93/eur-lex-sum |
| Multi-LexSum | US civil-rights class actions; English | Multi-doc summarization at 3 granularities | ODC-By | https://huggingface.co/datasets/allenai/multi_lexsum |
| IN-Abs / IN-Ext | India; English | Abstractive headnote gen / extractive rhetorical-role | Not confirmed | https://github.com/Law-AI/summarization |
| CaseSumm | US (SCOTUS); English | Long-context SCOTUS opinion -> syllabus | Not confirmed | https://mheddaya.com/research/legal-summarization/ |
| MILDSum | India; English->Hindi | English judgment -> Hindi summary | Not confirmed | https://github.com/Law-AI/MILDSum |
| CivilSum | India; English | Abstractive summarization of SC/HC decisions | Not confirmed | https://github.com/ra-MANUJ-an/CivilSum |
| SLDS (Swiss Landmark) | Switzerland; DE/FR/IT | Ruling -> headnote (DE/FR/IT) | CC-BY-4.0 (arXiv-stated) | https://arxiv.org/abs/2410.13456 |
| MultiLegalPile | 17 jurisdictions; 24 languages | Multilingual pretraining corpus (not a labeled benchmark) | Mixed (per source) | https://huggingface.co/datasets/joelniklaus/MultiLegalPile |


## Sources & Acknowledgments

Entries in this list were seeded in part from:

- [maastrichtlawtech/awesome-legal-nlp](https://github.com/maastrichtlawtech/awesome-legal-nlp)
- [CSHaitao/Awesome-LegalAI-Resources](https://github.com/CSHaitao/Awesome-LegalAI-Resources)
- [thunlp/LegalPapers](https://github.com/thunlp/LegalPapers)
- [Jeryi-Sun/LLM-and-Law](https://github.com/Jeryi-Sun/LLM-and-Law)
- [ZhitianHou/LLMs4LegalAI](https://github.com/ZhitianHou/LLMs4LegalAI)
- [czyssrs/LLM_X_papers](https://github.com/czyssrs/LLM_X_papers)
- [Liquid-Legal-Institute/Legal-Text-Analytics](https://github.com/Liquid-Legal-Institute/Legal-Text-Analytics)
- [openlegaldata/awesome-legal-data](https://github.com/openlegaldata/awesome-legal-data)
- [hecongqing/Awesome-LLM4Law](https://github.com/hecongqing/Awesome-LLM4Law)
- [chen-friedman/awesome-legaltech](https://github.com/chen-friedman/awesome-legaltech)
- [dalinvip/Awesome-Law-NLP-Research-Work](https://github.com/dalinvip/Awesome-Law-NLP-Research-Work)

## Contributing

PRs welcome. Each entry must cite a source link and a license; unlicensed or ambiguously-licensed datasets should note that explicitly rather than being omitted.

## License

This list (the curation itself) is released under [CC0](https://creativecommons.org/publicdomain/zero/1.0/). Individual datasets retain their own licenses — check before use.
