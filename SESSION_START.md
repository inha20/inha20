# SESSION_START — 세션 시작 진입점
## Structure Recognition Research Program

**Version:** 5.4 (Session 49 갱신)
**Date:** 2026-06-27  
**Author:** Choi Jonghun (Independent researcher; graduate of Inha Technical College)  
**Maintained by:** Research-Portfolio / ANTIGRAVITY

> 📌 **AI 진입점 통합 안내 (v5.0):** `ai-workspace/OperatingPrinciples.md`, `AIHandoverInstructions.md`의 핵심 원칙과 작업 현황(Active Queue, Health 표)이 이 단일 문서로 완전히 통합되었습니다. AI 세션 시작 시 **오직 이 문서 하나만** 읽고 작업을 시작하세요.

---

## 🛑 CRITICAL: Read This First

This document is the **single authoritative entry point** for any AI collaborator, research assistant, or future contributor joining this research program.

Do **not** begin working on any repository without reading this document in full.

---

## 📋 Session Start Quick Reference

**새 세션 시작 시 이 순서로 읽고 진행하세요:**

1. **이 파일** (`inha20-main/SESSION_START.md`) — 프로그램 전체 구조, AI 원칙, **현재 작업 현황** 모두 포함

**연구자에게 첫 질문:** "Where did we leave off?"

---

## 📋 현재 작업 현황

### 🤖 Active Queue

*(현재 대기 중인 작업 없음)*

> **Work-Then-Record Protocol:** 작업 완료 → 파일 re-read → 이 섹션 갱신

#### 📝 Session 49 완료 기록 (2026-06-27)
- **FR-3 n=5 군론 계산 완료 및 문서 일관성 복구:**
  - **FR-3 n=5 Space(XOR) + Space(AND) Python 완전 계산:**
    - Space(XOR)_n5: 64개 함수 → 12궤도 ✅ (Burnside 이론 예측값과 일치)
    - Space(AND)_n5: 7,581개 함수 → 210궤도 ✅ (열거↔Burnside 일치)
    - Space(XOR)_n5 S₅-불동점 4개 (f=0, A⊕B⊕C⊕D⊕E, 보수, f=1)
    - `scripts/s4_orbit_calculator.py` 섹션 8 신규 추가: `run_n5_full_analysis()`, `_generate_n5_monotone()` 등 실제 계산 함수 + `--n5-compute` 옵션 추가
    - `SubTODO.md` FR-3 셀션 갱신: 계산 결과 기록, 체크박스 ✅ 완료
  - **문서 일관성 복구 (3건):**
    - `SESSION_START.md` 버전 불일치 수정: 5.2(Session 47) → 5.4(Session 49) (이전 세션에서 누락된 버전 업데이트 수정 포함)
    - `6BooleanFunctionSpaceTheory-main/SubTODO.md`: `SESSION_START.md Phase 5 체크 갱신` 체크박스가 미체크 상태였으나 Session 48에서 이미 완료된 사실 확인 원료 표시 정리
    - `inha20-main/README.md`: 존재하지 않는 `ProjectDashboard.md`, `Research_History.md` 파일 참조 제거, SESSION_START.md 버전 v4.7 → v5.3 수정, `HumanAICollaborationProposal_Outline.md` 허브 링크 테이블에 추가

#### 📝 Session 48 완료 기록 (2026-06-27)
- **6BooleanFunctionSpaceTheory 이번 사이클 종결 및 통합 소논문 작성:**
  - 연구 방향 조정: Phase 3(SRT 인지 실험 전체) 및 Phase 4 일부(학생 실습·워크숍)를 후속 연구(FutureWorks)로 이관. 인지 실험을 SubTODO의 후속 연구 과제로 분리 반영.
  - 소논문 `paper.md` 신규 작성 완료 및 `index.html` 통합: Phase 1·2 완료 기준으로 전체 연구를 하나의 완결된 문서로 통합. `index.html`을 전면 재작성하여 KaTeX 수식과 논문 전체 내용을 웹 페이지로 배포.
  - 저장소 파일 단순화: 18개 파일을 `_absorbed/`로 이동, 내용 중복 및 필요 없는 7개 파일과 디렉토리 삭제. `SubTODO.md`를 단일 작업 관리 문서로 통합 개편(TODO.md, FUTURE_RESEARCH.md 내용 흡수).
  - **6번 저장소 현재 완료 상태:** Phase 1(기반 정립) ✅, Phase 2(S₄ 군론 분류, OC-1~OC-5) ✅, Phase 5(본문 통합 및 소논문 작성) ✅. Phase 3(인지 실험) · Phase 4 일부(실습) → FutureWorks 이관.
  - **잔여 항목 (개인 보완):** `index.html`과 `paper.md`의 §6 (Phase 0~5) 개인 경험 서술 — 연구자 직접 작성 필요.

#### 📝 Session 47 완료 기록 (2026-06-27)
- **Github 전 저장소 연구자 이력·소속 표기 정정:**
  - 사용자 확인 사실을 기준으로 잘못 기록된 대학 소속을 `인하공업전문대학 출신 독립 연구자`로 정정.
  - 9개 저장소의 Markdown·HTML 21개 파일에서 저자 정보, 프로필, 푸터, 메타 설명·키워드의 잘못된 소속 표기를 수정.
  - 논문의 잘못된 소속 표기는 실제 소속으로 오해되지 않도록 `연구자 정보: 인하공업전문대학 출신 · 독립 연구자`로 변경.
  - Phase 3 IRB 작업은 졸업 대학의 위원회 이용을 전제하지 않고 `현재 소속기관 또는 공용기관생명윤리위원회`의 이용 자격·심의 기준을 확인하도록 수정. IRB 검토 자체는 미완료 상태 유지.
  - 유일한 PPTX 내부 텍스트까지 감사했으며 잘못된 학교 표기는 없음을 확인.
  - 전체 재검색 및 배포 파일 SHA-256 대조 결과 이상 없음. 이 현황판 갱신 후 잘못된 대학 소속 표기는 0건.
  - **잔여 항목 (Phase 3):** 실제 자극 이미지 제작(F01–F08 V2·V3), 파일럿 실시(N=3), 현재 소속기관 또는 공용 IRB 심의 여부 확인.

#### 📝 Session 46 완료 기록 (2026-06-23)
- **6BooleanFunctionSpaceTheory Phase 2 최종 정합성 확인 및 Phase 3 자극 정련 착수:**
  - 발견: Session 45 완료 기록의 "잔여 항목: README.md 스크립트 가이드 추가"가 미완료로 기록되어 있었으나, 실제 파일시스템 확인 결과 README.md에 Scripts 섹션이 이미 완비, TODO.md·SubTODO.md 모두 ✅ 상태 — Session 45 내에서 완료 후 SESSION_START.md 갱신만 누락된 것으로 판명.
  - 조치 1: SubTODO.md Phase 2 아카이브 섹션 정리 및 SESSION_START.md 불일치 주석 추가.
  - 조치 2 (Phase 3 착수): `theory/KMapVisualizationSpec.md` v1.0 신규 작성 완료 — K-map 자극 시각화 완전 표준화 명세. 포함 내용: §1 그리드 레이아웃(Gray code), §2 치수(400×400px), §3 색상 팔레트(1-셀 #2D2D2D), §4 타이포그래피, §5 버전 정의(V1–V4), §6 기준 자극 F01–F08 셀 매핑, §7 통제 자극, §8 파일 저장 규칙, §9 제작 방법 지침(HARD RULE 포함), §10 파일럿 전 체크리스트.
  - SubTODO.md 갱신: Phase 3 "자극 정련 및 시각화 표준화" ✅ 처리, 잔여 Micro-task 목록 정리.
  - **잔여 항목 (Phase 3):** 실제 자극 이미지 제작(F01–F08 V2·V3), 파일럿 실시(N=3), IRB 심의 여부 확인.

#### 📝 Session 45 완료 기록 (2026-06-23)
- **6BooleanFunctionSpaceTheory Phase 2 사실 검증 및 정합성 복구:**
  - 발견: S4GroupAnalysis.md v1.2에 "Python 스크립트 검증 완료"로 기록되어 있었으나 `scripts/` 폴더 자체가 파일시스템에 없는 불일치(허위 완료 기록) 확인.
  - 조치: `scripts/` 디렉토리 생성 → `s4_orbit_calculator.py` 실제 작성 → Claude 컴퓨터에서 실행 검증.
  - 검증 결과: Space(XOR) 10궤도 ✅, Space(AND) 30궤도 ✅, Space(NOT) 32궤도 ✅, L∩M 3궤도 ✅ — 전체 통과.
  - `SubTODO.md` 및 `TODO.md` Phase 2 실제 완료 상태 반영(OC-4·OC-5·n=5 스캐폴드 체크 처리).
  - README.md 스크립트 사용 가이드 섹션 추가 완료 *(Session 45 내 완료 — Session 46에서 최종 확인)*.

### 🏥 Repository Health

| Repository | Health | Phase | Immediate Next Action |
|---|---|---|---|
| 1KMapStructureInvariance | 🟡 Stable | Phase 1 | ✅ 완료 |
| 2SymmetricBooleanFunctionMinorThesis | 🟡 Stable | Phase 1 | ✅ 완료 |
| 3VariableRearrangementInvarianceMinorThesis | 🟡 Stable | Phase 3 | ✅ 완료 |
| 4StructureRecognitionTheory | 🟡 Stable | Phase 4 | ✅ 완료 |
| **5HumanAIResearchCollaboration** | 🟢 Complete | Phase 4 | GitHub Pages 배포 완료 |
| **6BooleanFunctionSpaceTheory** | 🟢 Active | Phase 1·2·5 | **현재 연구 진행 중.** 잔여: §6 개인 서술 보완 (연구자 직접) |
| ANTIGRAVITY | 🔵 Monitoring | All | README.md 단일 운영 |
| inha20 | 🔵 Monitoring | Phase 1-5 | 통합 대시보드 체제 가동 |

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
- **금지:** 작업 완료 전에 현황판(Active Queue)을 체크하지 마십시오.
- **적용 대상:** 이 파일(`SESSION_START.md`)의 "📋 현재 작업 현황" 섹션 및 각종 체크리스트.

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

## 📂 Local Environment Context (다중 저장소 탐색 규칙)

**⚠️ CRITICAL: Cross-Repository Navigation**
이 로컬 환경(`C:\Users\cjh3c\OneDrive\바탕 화면\Github\`)에는 여러 개의 저장소가 병렬(sibling) 구조로 배치되어 있으며, 모든 디렉토리 이름에는 `-main`이 붙어 있습니다.
현재 `inha20-main` 내부에서 작업을 수행하더라도, 다른 저장소의 상태를 확인해야 할 때는 **반드시 상위 디렉토리로 이동하여 `-main` 접미사가 붙은 폴더를 탐색**해야 합니다.

- **예시 1:** `6BooleanFunctionSpaceTheory` 탐색 필요 시 → `../6BooleanFunctionSpaceTheory-main` 경로 확인.
- **예시 2:** `4StructureRecognitionTheory` 탐색 필요 시 → `../4StructureRecognitionTheory-main` 경로 확인.

"해당 폴더가 없다"고 판단하기 전에 반드시 `../[저장소명]-main` 경로가 존재하는지 확인(list_dir 등)하십시오.

---

## 🗺 Key Files Navigation

### Program-Level Documents
- `SESSION_START.md` ← **This file** (AI 단일 진입점 · 작업 현황 포함)

(위 파일은 이 저장소(`inha20`) 루트에 위치 — 경로 접두사 없이 바로 참조 가능)

### Theory Core Documents
- `StructureRecognitionTheory_Unified.md` ← **이론 통합본 (Definitions 3.1–3.3, H1–H10, Q1–Q15, OP-01–09)** — 이 저장소 루트
- [Hypotheses.md](https://github.com/inha20/4StructureRecognitionTheory/blob/main/theory/Hypotheses.md) ← H1–H10 전문 *(별도 저장소: 4StructureRecognitionTheory/theory/)*
- [CoreQuestions.md](https://github.com/inha20/4StructureRecognitionTheory/blob/main/theory/CoreQuestions.md) ← v2.0 (Level 0–8, Q1–Q15) *(별도 저장소)*
- [OpenProblems.md](https://github.com/inha20/4StructureRecognitionTheory/blob/main/theory/OpenProblems.md) ← v1.1 (OP-01–09) *(별도 저장소)*

---

*Last Updated: 2026-06-27 (Session 49 — FR-3 n=5 계산 완료, 문서 일관성 복구)*
