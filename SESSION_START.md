# SESSION_START — 세션 시작 진입점
## Structure Recognition Research Program

**Version:** 4.0 (AI 진입점 통합본)
**Date:** 2026-06-21  
**Author:** Choi Jonghun (Inha University)  
**Maintained by:** Research-Portfolio / ANTIGRAVITY

> 📌 **AI 진입점 통합 안내 (v4.0):** 기존 `ai-workspace/OperatingPrinciples.md`와 `program/ProjectManagement/AIHandoverInstructions.md`의 핵심 원칙이 이 단일 문서로 완전히 흡수 통합되었습니다. AI 세션 시작 시 **오직 이 문서 하나만** 읽고 작업을 시작하세요.

---

## 🛑 CRITICAL: Read This First

This document is the **single authoritative entry point** for any AI collaborator, research assistant, or future contributor joining this research program.

Do **not** begin working on any repository without reading this document in full.

---

## 📋 Session Start Quick Reference

**새 세션 시작 시 이 순서로 읽고 진행하세요:**

1. **이 파일** (`management/SESSION_START.md`) — 프로그램 전체 구조 및 AI 원칙 숙지
2. `./ProjectDashboard.md` — 현재 대기 중인 할 일 목록 및 전체 현황, 핵심 원칙

**연구자에게 첫 질문:** "Where did we leave off?"

---

## 🧠 AI Operating Principles (통합됨)

*이 섹션은 구 `OperatingPrinciples.md`에서 이관되었습니다.*

### This Research Program
This is not a collection of independent papers.
The repositories represent different stages of a **single evolving research program**.
- Avoid treating each repository as isolated work
- Always search for conceptual connections across repositories
- The user is not merely writing papers — the user is gradually constructing a research map

### Human-AI Collaboration Model
A recurring pattern has emerged (treat as working hypothesis, not conclusion):

| Human | AI |
|---|---|
| Notices unusual phenomena | Connects concepts |
| Detects anomalies | Suggests frameworks |
| Generates questions | Expands explanation space |

**Your role as AI collaborator:**
- You are the **expansion engine**, not the decision maker
- Suggest frameworks; let the human select
- Document observations as observations, not conclusions
- When something seems important but unresolved, mark it as an open question, not a solved problem

### Workflow Rules
**Prefer:**
- Incremental updates over full rewrites
- Preservation of history over clean slate
- Documentation of decisions (CHANGELOG or handover files)
- Conceptual organization over producing more content
- Preservation of observations, anomalies, unanswered questions

**Avoid:**
- Unnecessary rewrites
- Deleting historical material
- Restructuring without explanation
- Forcing theoretical frameworks too early onto early observations

### Research Priority
**Highest priority:** Structure Recognition Theory (Paper 4)  
**Reason:** It may become the conceptual framework connecting all previous repositories.
**When uncertain between:** A) Producing more content B) Improving conceptual organization **→ Prefer B.**

---

## ⚠️ Critical Workflow Rules (통합됨)

*이 섹션은 구 `AIHandoverInstructions.md`의 핵심 행동 지침(Part 11, Part 12)에서 이관되었습니다.*

### 1. Work-Then-Record Protocol (작업 선행 원칙)
> **허위 완료 기록 방지를 위한 절대 원칙**

**① 작업을 실제로 완료한다 → ② 파일을 다시 읽어 검증한다 → ③ 그 다음에만 현황판을 갱신한다**
- **금지:** 작업 완료 전에 현황판(ProjectDashboard)을 체크하지 마십시오.
- **적용 대상:** `ProjectDashboard.md` 등 각종 체크리스트.

### 2. Multi-File Editing — 검증된 계획 구조
> 다수 파일을 수정하는 모든 세션에서 적용할 것.

- **0단계 (Pre-flight):** 편집 대상 파일 전부를 순서대로 읽고 버전 번호를 파악한다.
- **1단계 (중요도 역순):** 가장 광범위하게 참조되는 파일부터 수정한다.
- **2단계 (원자적 검증):** 파일 하나 편집 완료 직후 다시 읽어(re-read) 수정이 올바른지 확인한다.
- **3단계 (일관성 점검):** 버전 번호 동시 업데이트 및 세션 기록 동기화를 수행한다.

### 3. Image Creation Rule (이미지 생성 규칙 — HARD RULE)
> **모든 이미지 파일은 사람이 생성한 스타일로 통일한다.**

- **허용:** PowerPoint, Keynote, Draw.io, 손 그림 스캔, 연구자가 직접 작성한 SVG.
- **절대 금지:** AI 이미지 생성 도구(DALL-E, SD 등) 사용 금지, AI가 작성한 Python/matplotlib/LaTeX/TikZ 코드로 그림 생성 금지.
- AI의 역할은 "본문에 텍스트 플레이스홀더 삽입"과 "그림 명세서(Specification) 작성"에 한정됩니다.

---

## 🏗 The Four-Paper Architecture (Architecture B)

```
Paper 1: KMap Structure Invariance
    ↓  (provides empirical case)
Paper 2: Symmetric Boolean Function Visual Patterns
    ↓  (provides empirical case)
Paper 3: Variable Rearrangement Invariance
    ↓  (provides empirical case)
Paper 4: Structure Recognition Theory (SRT)
    ↑  (integrates all three as theoretical hub)
    ↓
Paper 5: Human-AI Research Collaboration
    (방법론적 연구 — 위 전체 연구를 가능하게 한 과정 연구)
```

Papers 1–3 = **Empirical foundation layer**  
Paper 4 = **Meta-theoretical integration layer**  
Paper 5 = **Methodological self-referential layer**  
Research-Portfolio = **Program navigation hub**  
ANTIGRAVITY = **AI collaboration workspace**  
inha20 = **GitHub public entry point**  
6BooleanFunctionSpaceTheory = **Applied Mathematics Extension — Branch 8** *(2026-06-12 신규 저장소 — 9번째)*

---

## 🧬 Concept Genealogy (Do Not Destroy)

```
Pattern
 ↓
Layer Structure
 ↓
Equivalence
 ↓
Structural Invariance
 ↓
Structure Recognition Theory
 ↓
Human-AI Collaboration Model
```

This genealogy represents the **actual historical development** of the researcher's thinking.  
Preserving this history is mandatory.

---

## 🎯 Current Theory — Structure Recognition Theory (SRT)

### Core Research Questions (Two-Level)
**Program Level:** How do humans come to see something new?
**Theory Level:** How do humans detect explanatory significance?

### Hypotheses (H1–H10)
- **H1** Structure Discoverer Hypothesis
- **H2** Representation Transformation
- **H3** Attention Filter
- **H4** Significance Filter
- **H5** Explanation Anticipation
- **H6** Explanatory Significance
- **H7** H1 Mature
- **H8** Concept-as-Lens *(통합 확장 가설 — SRT v0.3 승격)*
- **H9** Concept Evolution *(통합 확장 가설 — SRT v0.3 승격)*
- **H10** Generative Concept *(통합 확장 가설 — SRT v0.3 승격)*

---

## 🗺 Key Files Navigation

### Program-Level Documents
- `management/SESSION_START.md` ← **This file** (AI 단일 진입점)
- `./ProjectDashboard.md` ← **통합 대시보드 및 할 일 목록 (세션 시작 시 확인)**
- `../program/Research_History.md` ← **개념 계보 및 연구 일지/연표**

### Theory Core Documents
- `4StructureRecognitionTheory-main/theory/StructureRecognitionTheory_v0.3.md` ← **Current version**
- `4StructureRecognitionTheory-main/theory/Hypotheses.md`
- `4StructureRecognitionTheory-main/theory/CoreQuestions.md`
- `4StructureRecognitionTheory-main/theory/OpenProblems.md`
- `4StructureRecognitionTheory-main/theory/CaseStudyConnections.md`

---

## ⏱ Session History (Recent)

| Session | Date | Key Completions |
|---|---|---|
| Session 26 | 2026-06-20 | 잔여 미점검사항 100% 검증 완료 |
| Session 27 | 2026-06-20 | INTEGRATION_DIRECTIVE.md v2.0 전면 재작성; Work-Then-Record Protocol 신설 |
| Session 28 | 2026-06-20 | WorkOrderQueue.md 큐 문서 신설 |
| Session 29 | 2026-06-21 | WorkOrderQueue Task A-4·A-5 완료 + Phase 2 허위 완료 3건 정정 |
| **단일화 (v4.0)** | **2026-06-21** | **`management/`로 이동. `OperatingPrinciples.md` 및 `AIHandoverInstructions.md`의 핵심을 이 파일로 흡수 통합. AI 단일 진입점으로 확립.** |

| Session 32 | 2026-06-21 | originals/ 삭제 확인 Task A-1/A-2 취소; GitHub Topic Tags Task R-2 완료 |

---

*Last Updated: 2026-06-21 (Session 32 업데이트 반영)*
