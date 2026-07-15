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
| LexGLUE | US + EU/ECtHR; English | 7 English legal NLU tasks (classification + MCQ) | CC-BY-4.0 | https://huggingface.co/datasets/coastalcph/lex_glue |
| LEXTREME | EU + national; 24 languages | 11 datasets / 18 configs; classification + NER | CC-BY-4.0 (mixed subsets) | https://huggingface.co/datasets/joelniklaus/lextreme |
| LegalBench | Predominantly US; English | 162 tasks; 6 reasoning types (IRAC) | CC-BY-4.0 (mixed task licenses) | https://huggingface.co/datasets/nguha/legalbench |
| LawBench | China; Chinese | 20 tasks; 3 cognitive tiers | Apache-2.0 | https://github.com/open-compass/LawBench |
| LAiW | China; Chinese | 14 tasks; 3 ability levels (BIR/LFI/CLA) | Not confirmed | https://github.com/Dai-shen/LAiW |
| LexEval | China; Chinese | 23 tasks; LexCog cognitive taxonomy (6 abilities) | MIT | https://huggingface.co/datasets/CSHaitao/LexEval |
| IL-TUR | India; English/Hindi + 9 langs | 8 tasks (NER, rhetorical role, LJP, retrieval, summ, MT) | CC-BY-NC-ND-4.0 | https://huggingface.co/datasets/Exploration-Lab/IL-TUR |
| LBOX Open | South Korea; Korean | Corpus + classification + LJP + summarization | Not confirmed | https://huggingface.co/datasets/lbox/lbox_open |
| KBL | South Korea; Korean | Knowledge (510) + reasoning (288) + bar exam (2,510) | Not confirmed | https://github.com/lbox-kr/kbl |
| ArabLegalEval | Saudi Arabia; Arabic | Multitask QA / entailment / classification | Not confirmed | https://aclanthology.org/2024.arabicnlp-1.20/ |
| LegalAgentBench | China; Chinese | 300 agent tasks; 17 corpora; 37 tools; multi-hop | Not confirmed | https://github.com/CSHaitao/LegalAgentBench |
| LexSumm / LexT5 | US/UK/EU/India; English | 8 English legal summarization datasets | Not confirmed | https://github.com/TUMLegalTech/LexSumm-LexT5 |
| MLEB | US/UK/EU/AU/IE/SG; English | 10 datasets; retrieval + zero-shot classification + QA | Not confirmed | https://github.com/isaacus-dev/mleb |
| TW-LegalBench | Taiwan; Traditional Chinese | MCQ across 6 legal domains | Apache-2.0 (HF card) | https://huggingface.co/datasets/lianghsun/tw-legal-benchmark-v1 |
| BigLaw Bench (Harvey) | US (initially) | Real billable legal work (drafting, research, due diligence, litigation) | Partial (samples + rubrics on GitHub; full set on request) | https://www.harvey.ai/blog/introducing-biglaw-bench |
| BigLaw Bench: Global (Harvey) | UK, Australia, Spain (+US) | BLB extended to more jurisdictions | Partial | https://www.harvey.ai/blog/introducing-big-law-bench-global |
| BigLaw Bench: Research (Harvey) | US case law | Hard agentic US case-law research problems | Partial | https://www.harvey.ai/blog/introducing-big-law-bench-research |
| Legal Agent Benchmark (LAB / HLAB) (Harvey) | US BigLaw practice areas | Long-horizon legal AGENT tasks (client-matter workflows) | Open-source (code fully open; portion of data open) | https://www.harvey.ai/blog/introducing-harveys-legal-agent-benchmark |
| 2026 Contract Review Benchmark (LegalOn Technologies) | US-style English contracts | Provision-level contract review precision vs 11 LLMs | Proprietary (results + methodology only; no data/code) | https://www.legalontech.com/post/the-contract-review-benchmark-2026 |
| MLEB (Massive Legal Embedding Benchmark) (Isaacus) | US/UK/EU/AU/IE/SG; English | Legal embedding/retrieval: search, zero-shot classification, QA | Fully open (code + data + arXiv) | https://isaacus.com/mleb |
| Legal RAG Bench (Isaacus) | Victoria, Australia (criminal law) | End-to-end legal RAG w/ error decomposition (halluc/retrieval/reasoning) | Fully open (HF + arXiv) | https://isaacus.com/blog/legal-rag-bench |
| Open Australian Legal Corpus / QA (Isaacus) | Australia; English | Corpus (229K texts, 1.4B tokens) + 2,124 synthesized QA pairs | Fully open (HF) | https://huggingface.co/datasets/isaacus/open-australian-legal-corpus |
| Vals Legal AI Report (VLAIR) (Vals AI) | US; English | 7 legal tasks across vendor tools vs lawyer baseline | Report public; task data proprietary | https://www.vals.ai/industry-reports/vlair-2-27-25 |
| Legal Research Bench (Vals AI) | US federal/state; English | Agentic legal research (case/web/doc retrieval -> synthesis) | Partial (public samples + harness; val/test gated) | https://www.vals.ai/benchmarks/legal_research |
| CaseLaw v1/v2 (Vals AI (w/ Jurisage)) | US; English | Litigation precedent QA (family + criminal law) | Proprietary (results only; criticized as unreproducible) | https://www.vals.ai/benchmarks/case_law-04-11-2025 |
| CoCoBench (Thomson Reuters / CoCounsel) | US; English | Fiduciary-grade legal task completion; longitudinal tracking | Closed / proprietary (described in blogs) | https://www.thomsonreuters.com/en-us/posts/innovation/why-legal-ai-needs-a-new-standard-inside-thomson-reuters-cocobench/ |
| LegalRikai (Open Benchmark) (LegalOn Technologies) | Japan; Japanese | 4 tasks: complex Japanese corporate legal work (long-form doc editing) | Open (HF gated + arXiv; LREC 2026) | https://arxiv.org/abs/2512.11297 |
| JudgmentBench (Snorkel AI + Stanford Law) | US; English | Rubric vs comparative(pairwise) judgment as eval methodology (on 30 BigLawBench tasks) | Open (methodology paper; check data terms) | https://arxiv.org/abs/2605.25240 |
| PRBench-Legal (Scale AI) | US (47 jurisdictions); English | High-stakes professional legal reasoning; weighted rubric criteria | Open methodology + leaderboard (full items partial) | https://scale.com/research/prbench |
| APEX (Big Law associate split) (Mercor) | US; English | Professional-work tasks; law is one of 4 domains | Mixed (paper open; heldout private) | https://arxiv.org/abs/2509.25721 |
| AI IE + Contract Drafting Benchmarks (legalbenchmarks.ai (consortium)) | US in-house; English | Phase1: info extraction (6 tools); Phase2: contract drafting (14+ tools) | Open (CC-BY-4.0; data on request) | https://www.legalbenchmarks.ai/research/phase-1-research |
| ContractIQ Bench (Luna) (Luminance) | Multi; English | Contract provision annotations to validate Luna/Luna Crescent model | Proprietary (not released) | https://www.luminance.com/resources/insights/the-era-of-vertical-ai-is-here-introducing-luna-crescent-luminances-proprietary-legal-intelligence-model/ |
| State of Contracts clause benchmarks (Spellbook) | 30 countries; English | 270+ clause benchmarks across 13 agreement types | Proprietary (product/report) | https://www.spellbook.legal/blog/2026-state-of-contracts-report |


## Sources & Acknowledgments

This list is currently seeded from `Legal_NLP_Resource_Catalog.xlsx`. The following upstream lists have been forked as sources for further research and will be credited for specific entries as they're mined in:

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
