# Structure Recognition Theory (SRT) — Unified Summary

**Version:** 1.0 (Unified)  
**Date:** 2026-06-21  
**원문(전문) 저장소:** [4StructureRecognitionTheory](https://github.com/inha20/4StructureRecognitionTheory/tree/main/theory)

이 문서는 분산되어 있던 `SRT_Summary.md`, `CoreQuestions_Summary.md`, `Hypotheses_Summary.md` 세 개의 요약본을 하나로 통합한 **이론 단일 진입점**입니다.

---

## 1. Core Research Questions

### Central Questions
| Level | Question |
|---|---|
| **Program** | How do humans come to see something new? |
| **Theory** | How do humans detect explanatory significance? |

### Question Hierarchy (Level 0–8)
The hierarchy forms a layered structure: from empirical observation (Level 0) through structure and discovery (Levels 1–2), significance and questions (Levels 3–4), explanation (Level 5), to concept evolution (Levels 6–8).

| Level | Theme | Key Questions | Connected Hypotheses |
|---|---|---|---|
| **0** | Observation | Why do XOR/XNOR produce checkerboard patterns? Why do symmetric functions produce ring/corner/point forms? | H2 |
| **1** | Structure | Why do humans recognize patterns as *structures* rather than noise? What distinguishes pattern from structure? | H1, H2 |
| **2** | Discovery | Why do humans discover particular structures and not others? What determines sustained investigative attention? | H1, H3 |
| **3** | Significance | Why do certain structures feel *important*? What are the operative criteria of the significance filter? | H4, H6, H7 |
| **4** | Question Generation | How do structures become research questions? Can research question generation be trained? | H4, H6, H7 |
| **5** | Explanation | How do humans detect *explanatory significance*? How do humans orient toward explanation before finding it? | H5, H6 |
| **6** | Concept | What makes a concept effective as an observation lens? Can a concept be designed to maximize structure-revealing power? | H8, H10 |
| **7** | Expanded Perception | How do concepts change what a researcher can observe? Can new observations be produced by conceptual change alone? | H8, H9 |
| **8** | New Discovery | How does the concept evolution cycle generate new discovery cycles? Can the cycle be used deliberately? | H9, H10 |

---

## 2. Formal Definitions (SRT v0.3)

### Definition 3.1 — Structure
A configuration *C* qualifies as a *structure* (relative to observer *O*) if and only if:
1. **Holistic recognition** — *O* recognizes *C* as a unified whole (not cell-by-cell aggregation)
2. **Non-triviality** — *C* is not immediately explicable by random distribution
3. **Transformational stability** — *C* persists across at least one representation transformation
4. **Generative implication** — *C* implies the existence of a generating mechanism

### Definition 3.2 — Attention
A researcher *O* directs *attention* to configuration *C* if and only if:
1. **Selectivity** — *O* selectively allocates investigative resources to *C* over alternatives
2. **Antecedence** — *O*'s attention to *C* precedes, and is not caused by, full structural analysis
3. **Persistence** — *O*'s attention to *C* is sustained across multiple investigative episodes
4. **Criterion opacity** — the criteria governing *O*'s attention to *C* are not fully accessible to *O*

### Definition 3.3 — Explanatory Significance
A structure *C* has *explanatory significance* for observer *O* if and only if:
1. **Non-randomness perception** — *O* judges *C* as non-randomly generated
2. **Explanation-implication** — *O* judges that *C* implies the existence of an explanatory mechanism
3. **Productive research expectation** — *O* expects that investigation of *C* will produce non-trivial findings
4. **Research-threshold crossing** — *O*'s judgment of (1)–(3) is sufficient to initiate sustained investigation

---

## 3. Hypotheses (H1–H10)

### H1–H7: First-Order Hypotheses (Research Generation)
These hypotheses describe the process from a single encounter with a phenomenon through to research generation.

| # | Name | Claim | Status |
|---|---|---|---|
| **H1** | Structure Discoverer | Humans may have a comparative advantage in structure discovery over AI | Exploratory |
| **H2** | Representation Transformation | Some problems become tractable by changing representation, not reducing computation | Supported by multiple case observations |
| **H3** | Attention Filter | Humans do not investigate every pattern; a prior selection process occurs. Criteria operate implicitly | Exploratory |
| **H4** | Significance Filter | Beyond attention, humans apply an implicit filter evaluating whether a structure is *worth investigating*. Criteria: compression, prediction, generalization, explanation pull | Exploratory — criteria operationalized |
| **H5** | Explanation Anticipation | Humans anticipate the existence of an explanation *before* they discover it | Exploratory — empirical design proposed |
| **H6** | Explanatory Significance | Research begins not from structure discovery per se, but from detecting *explanatory potential* in a structure | Exploratory — empirical design proposed |
| **H7** | Structure Discoverer (Mature) | The core human advantage is not pattern recognition but evaluating which structures carry explanatory significance | Exploratory — revision of H1 |

### H8–H10: Second-Order Hypotheses (Concept Evolution)
These hypotheses describe how *completed research changes the researcher* — enabling new observations impossible before the research.

| # | Name | Claim | Status |
|---|---|---|---|
| **H8** | Concept-as-Lens | Concepts function as observation lenses: acquiring a concept expands the set of configurations that can be recognized as structures | Integrated extension |
| **H9** | Concept Evolution | Research generates concepts, and concepts (via H8) generate further research through expanded perception — a self-reinforcing cycle | Integrated extension |
| **H10** | Generative Concept | Concepts differ in generativity — some expand perception more broadly and durably than others | Integrated extension |

---

## 4. Operationalized Criteria & Research Design

### H4: Significance Filter — Operationalized Criteria
| Criterion | Description | Formal Operationalization |
|---|---|---|
| Compression | Structure compresses large information into short rule | *comp(C) = 1 − (\|description(G)\| / \|enumeration(C)\|)* |
| Prediction | Structure enables prediction of unobserved cases | Accuracy on held-out test set above domain baseline |
| Generalization | Structure applies across multiple domains | *gen(C) = \|{domains d : C instantiated in d}\|* |
| Explanation pull | Researcher anticipates finding an explanation | Pre-investigation confidence rating (1–10) |

### Empirical Research Designs (SRT v0.3 §10)
| Hypothesis | Paradigm | Core Method |
|---|---|---|
| H1/H7 | Competitive Discovery Paradigm | Human vs. AI K-map structure discovery, then significance rating |
| H5 | Pre-Discovery Confidence Rating | Confidence rating before and after structure explanation |
| H6 | Research Worthiness Judgment | Binary "is this worth investigating?" judgments across structures |

---

## 5. Open Problems Summary (OP-01–OP-09)
| OP | Problem |
|---|---|
| OP-01 | Attention selection — what determines which patterns pass H3? |
| OP-02 | Significance boundary — what are the exact criteria of H4? |
| OP-03 | Explanation anticipation mechanism — cognitive basis of H5 |
| OP-04 | Representation design — what makes a representation structure-revealing? |
| OP-05 | Invariance significance — is invariance a universal or domain-specific criterion? |
| OP-06 | AI structure discovery — can AI discover or only generate structures? |
| OP-07 | Concept-as-Lens — how to measure concept generativity (H10)? |
| OP-08 | Research question origin — where exactly do research questions come from? |
| OP-09 | Definition 3.3 Necessity Conditions — are the four conditions of Explanatory Significance necessary AND sufficient? |
