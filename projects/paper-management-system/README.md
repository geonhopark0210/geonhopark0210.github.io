# Paper Management System

**임상/상담심리학 논문 자동화 관리 파이프라인**

## 개요

PDF 논문을 수집·분석·인덱싱하는 개인 연구 라이브러리 자동화 시스템.
BibTeX 생성, CSV 마스터 DB 관리, 논문 ID 명명 규칙을 일관되게 적용한다.

## 아키텍처

```
papers/inbox/     ← 새 PDF 투입
      ↓
process_inbox.py  ← SHA256 해싱 + paper_id 생성 + CrossRef API 조회
      ↓
papers/library/   ← 처리 완료 PDF 보관
bib/              ← {paper_id}.bib 자동 생성
index/papers_master.csv ← 마스터 DB 업데이트
      ↓
/paper-analysis   ← Claude Code 스킬로 READ 분석
notes/read/       ← {paper_id}.md 저장
```

## 핵심 기능

| 기능 | 스크립트 | 설명 |
|------|---------|------|
| 논문 처리 | `process_inbox.py` | PDF → SHA256 → paper_id → BibTeX |
| CSV 재생성 | `rebuild_csv.py` | 마스터 DB 전체 재구성 |
| ID 수정 | `fix_unknown_ids.py` | Unknown ID → 정규 paper_id |

## paper_id 명명 규칙

```
{AuthorLast}{YYYY}_{snake_title}
예: Li2020_emotional_abuse_mentalizing_depression
```

## 태그 체계

논문별 3개 이상의 계층 태그 필수 부여:

| 카테고리 | 예시 |
|---------|------|
| `Exposure_*` | ChildhoodAbuse, Trauma, IntimatePartnerViolence |
| `Mechanism_*` | Attachment, EmotionRegulation, Mentalizing |
| `Outcome_*` | Depression, Anxiety, PTSD, BPD |
| `Context_*` | EmergingAdulthood, Adolescence, CollegeStudents |

전체 태그 정의: [tag-taxonomy.md](../../research/tag-taxonomy.md)

## 논문 분석 워크플로우

Claude Code 커스텀 스킬(`/paper-analysis`)로 논문을 15개 섹션 구조로 분석:
TL;DR → Core Contribution → Sample → Outcomes → Key Results → Personal Insights → Research Ideas 순.

## 기술 스택

- **Python 3.12** — 파이프라인 스크립트
- **CrossRef API** — 메타데이터 자동 조회
- **SHA256** — 파일 무결성 + 고유 ID 생성
- **Claude Code** — AI 보조 논문 분석

## 현황

- 논문 PDF: 50+ 편 관리 중
- BibTeX: 95개 생성 완료
- 읽기 노트: [paper-notes 폴더](../../research/paper-notes/) 참조
- 번역 노트: [paper-translations 폴더](../../research/paper-translations/) 참조
