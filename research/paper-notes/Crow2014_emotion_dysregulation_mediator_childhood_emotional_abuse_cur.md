# Crow2014_emotion_dysregulation_mediator_childhood_emotional_abuse_cur

**Source**: Crow T, Cross D, Powers A, Bradley B (2014). Emotion dysregulation as a mediator between childhood emotional abuse and current depression in a low-income African-American sample. *Child Abuse & Neglect*, 38(10): 1590–1598. DOI: 10.1016/j.chiabu.2014.05.015
**Date Read**: 2026-02-24
**Mode**: READ

---

## 1. TL;DR
저소득 아프리카계 미국인 성인 대표본(N=3,902)에서 CEA(아동기 정서적 학대)가 5가지 아동기 외상 유형 중 우울과 정서조절곤란 모두에서 가장 강력한 예측변수임을 다중회귀로 확인. 부트스트랩 매개 분석 결과 정서조절곤란(EDS)이 CEA → 우울 경로를 보완적 부분 매개(complementary mediation)함을 확인 — 간접효과와 직접효과 모두 유의. CEA + EDS가 현재 우울 증상 분산의 약 절반을 설명함.

---

## 2. Core Contribution
- CEA가 신체적 학대, 성적 학대, 방임 등 다른 모든 아동기 외상 유형보다 우울과 정서조절곤란 두 결과 모두에서 더 강력한 예측변수임을 대규모 표본으로 입증
- 정서조절곤란이 CEA → 성인 우울 경로의 매개변수임을 실증적으로 확인한 초기 연구 중 하나 — CEA → DERS → Depression 경로의 직접적 선행 근거

---

## 3. Study Type
횡단 조사 (cross-sectional) + 위계적 다중회귀 + 부트스트랩 단순 매개 분석 — §Method, p.5–7 (PDF)

---

## 4. Sample & Setting
- N = 3,902명 (전체 측정 완료자), 연령 18–81세 (M = 39.34, SD = 13.76)
- 성별: 여성 68.9%
- 민족: 아프리카계 미국인 92.7%
- 소득: 월 수입 $500 미만 33.8%, $500–$1,000 25.8%, $1,000–$2,000 24.5%, $2,000 이상 12.3%
- 모집처: 미국 조지아주 애틀랜타 Grady Health System 일반의/산부인과 클리닉 (저소득층 대상 공공병원)
- Grady Trauma Project(NIH 5년 지원 연구)의 일부; 데이터 수집 2005–2013
- 대면 인터뷰 방식 (태블릿 응답)
- Locator: §Participants, p.5–6 (PDF)

---

## 5. Intervention / Exposure & Comparator
- **노출 변수**: CEA — CTQ Emotional Abuse 하위척도, 다른 4개 외상 유형(신체적 학대, 성적 학대, 신체적 방임, 정서적 방임) 동시 투입으로 통제
- 중재 없음 (관찰 연구)
- Locator: §Measures, p.6 (PDF)

---

## 6. Outcomes & Measures

| 변수 | 도구 | 내용 |
|------|------|------|
| 아동기 외상 | CTQ (Childhood Trauma Questionnaire; Bernstein et al., 2003) | 28문항, 5점 Likert; 5 하위척도: 신체적 학대, 신체적 방임, 성적 학대, 정서적 방임, 정서적 학대(EA; α=0.84) |
| 정서조절곤란 | EDS 단축형 (Emotion Dysregulation Scale, short version; Powers et al., submitted) | 12문항, 7점 Likert; 정서 경험·인지·행동 3 영역; α=0.94; DERS와 r=0.60 |
| 우울 | BDI-II (Beck Depression Inventory-II; Beck et al., 1996) | 21문항, 0–3 척도; α=0.93 |

- 측정 시점: 단일 횡단
- Locator: §Measures, p.6–7 (PDF)

---

## 7. Analysis
- **기술통계 및 상관**: SPSS (버전 미보고)
- **위계적 다중회귀**: DV=EDS(EDS 예측 모형), DV=BDI(우울 예측 모형); 모든 5개 CTQ 하위척도를 예측변수로 투입; 최종 우울 모형에 EDS 추가
- **매개 분석**: Preacher & Hayes (2008) 매크로, 부트스트랩 5,000회, 95% bias-corrected CI; 간접효과(a×b) 유의성은 CI가 0 포함하지 않으면 유의
- **보완적 매개(complementary mediation)** 판단 기준: Zhao, Lynch & Chen (2010) — a×b×c > 0이면 보완적 매개
- 결측치: 전체 측정 완료자(N=3,902)만 분석 포함
- 사전등록: Not reported
- Locator: §Data analysis, p.7 (PDF)

---

## 8. Key Results

**기술통계 (Tbl.1, p.16 PDF)**

| 변수 | M | SD |
|------|------|------|
| CTQ 신체적 학대 | 8.03 | 3.95 |
| CTQ 신체적 방임 | 7.05 | 3.17 |
| CTQ 성적 학대 | 7.61 | 4.94 |
| CTQ 정서적 방임 | 9.15 | 5.02 |
| CTQ 정서적 학대 (EA) | Not clearly reported (중등도/중증 19.2%, 경미 20.2%, 없음 60.7%) |
| BDI (우울) | 13.81 | Not reported |
| EDS (정서조절곤란) | 37.52 | Not reported |

**주요 상관 (Tbl.1, 모두 p<.001)**
- EA ↔ EDS: r = 0.45
- EA ↔ BDI: r = 0.39
- EDS ↔ BDI: r = 0.64
- EA는 5개 CTQ 하위척도 중 EDS, BDI 모두와 가장 강하게 상관

**위계적 회귀 (Tbl.2, p.17 PDF)**

EDS 예측 모형:
- EA: β = 0.21, p<.001 (단독 투입 시); 다른 외상 유형 통제 후에도 유의한 가장 강한 예측변수
- 최종 모형 R² = 0.149

우울(BDI) 예측 모형:
- 5개 외상 유형만 투입 시 EA β = 0.33***, R² = 0.217
- EDS 추가 투입 시 EA β = 0.16***, EDS β = 0.54***, R² = 0.466
- EA의 95% CI [0.30, 0.49] → 정서적 방임 [0.11, 0.28], 성적 학대 [0.08, 0.21]과 겹치지 않음 → EA가 유의하게 더 강한 예측변수
- 신체적 학대·신체적 방임: 최종 모형에서 유의하지 않음

**매개 분석 (Fig.1, p.15 PDF)**

| 경로 | 비표준화 계수 | 유의성 |
|------|------|------|
| Path a: CEA → EDS | B = 3.31 | *** |
| Path b: EDS → BDI | B = 0.16 | *** |
| Path c: CEA → BDI (총 효과) | B = 1.14 | *** |
| Path c': CEA → BDI (직접효과, EDS 통제) | B = 0.61 | *** |
| 간접효과 (a×b) | 0.525, 95% CI [0.48, 0.55] | 유의 |

- 보완적 매개 확인: a×b×c > 0 → 직접·간접효과 모두 유의
- Locator: Fig.1 p.15 (PDF), Tbl.2 p.17 (PDF), §Results p.7–8 (PDF)

---

## 9. Limitations
- 횡단 설계 → 인과 방향, 발병 시점 확정 불가; 종단 연구 필요 (§Discussion, p.10 PDF)
- EDS가 당시 새로운 척도 (미발표 논문 기반) — 단, DERS와 r=0.60으로 수렴 타당도 확인 (§Discussion, p.10 PDF)
- 자기보고 편향 — 아동기 외상 과소보고 가능성 (§Discussion, p.10 PDF)
- 표본 동질성(저소득 아프리카계 미국인) → 외적 타당도 제한 (§Discussion, p.10 PDF)

---

## 10. Open Questions
- 정서조절곤란이 CEA → 우울 경로를 보완적으로(완전이 아닌) 매개한다면, 나머지 직접효과(c'=0.61)를 설명하는 다른 매개변수는 무엇인가? → 내 연구 모형에서 mentalization이 그 역할을 추가로 설명할 수 있는가?
- EDS(12문항, 정서 경험·인지·행동)와 DERS(36문항, 6 하위척도)가 구성 개념적으로 얼마나 중첩되는가? 내 연구에서 DERS를 쓸 때 이 논문 결과를 직접 비교할 수 있는가?

---

## 11. Personal Insights (개인 인사이트)
- CEA가 신체적 학대나 성적 학대보다 우울과 정서조절곤란 모두에서 더 강한 예측변수라는 결과는 "CEA가 독립적 위험 요인"이라는 내 연구의 근거를 강력하게 뒷받침한다. 특히 5개 외상 유형을 동시에 통제한 상황에서도 이 결과가 유지된다는 점이 중요하다.
- 직접효과(c'=0.61)가 여전히 유의하다는 점 — 정서조절곤란이 유일한 매개변수가 아니라는 신호. 내 연구에서 mentalization을 조절변수로 추가했을 때 이 잔여 직접효과가 줄어드는지 확인하는 것이 이론적으로 흥미롭다.
- N=3,902라는 대규모 표본에서 나온 결과라 통계적 검증력 문제가 없다. 반면 내 연구(아마 대학원생 표본, 소규모)는 효과크기 추정치가 달라질 수 있으므로 power analysis가 중요.
- EDS와 DERS가 r=0.60으로 수렴함을 명시 — DERS 쓰는 내 연구에서 이 논문을 선행연구로 직접 인용 가능.
- CTQ를 CEA 측정에 사용하고 BDI를 우울 측정에 사용 — 내 연구와 척도 체계가 유사하므로 결과 비교·인용이 용이.

---

## 12. Research Ideas (연구 아이디어)
- 이 논문의 단순 매개 모형(CEA → DERS → Depression)에 **mentalization(RFQ)을 조절변수로 추가**하면 내 moderated mediation 모형이 된다. 이 논문이 제안한 "다른 매개변수 탐색" 방향과도 일치.
- 직접효과(c')가 여전히 유의하다는 점 → 내 논문 논의 섹션에서 "DERS가 유일한 경로가 아니며, mentalization이 이 잔여 경로를 조절한다"는 주장의 이론적 근거로 활용 가능.
- 이 논문은 저소득 아프리카계 미국인 표본 → 내 표본(한국 대학생/성인)과 문화적 맥락이 다름 → 문화 간 일반화 가능성을 논의 섹션에서 언급하되, 결과의 일관성(타 연구들과의 수렴)을 강조하는 방향으로 서술.
- EDS(12문항)가 아닌 DERS(36문항)를 쓰는 이유를 정당화할 때 — DERS가 더 세분화된 정서조절 차원(수용, 충동통제, 전략 접근 등)을 측정하므로 매개 기제를 더 구체적으로 탐색할 수 있다는 논거 사용 가능.

---

## 13. Connections (연결 고리)
- **MartinGagnon2023_cea_mentalizing_depression_anxiety_bpd**: 이 논문(CEA → DERS → Depression)에 mentalization 변수가 없는 반면, Martin-Gagnon et al.은 mentalization만 매개로 사용. 내 연구는 두 논문을 통합하는 구조.
- **Huang2025_emotion_dysregulation_perceived_social_support_link_childhoo**: 대학생 표본에서 CEA → DERS → Depression 경로를 검증 — 이 논문의 성인 저소득 표본 결과를 대학생 표본으로 확장한 후속 연구와 비교 가능.
- **Christ2019_linking_childhood_emotional_abuse_depressive_symptoms_emotio**: 유사 경로 검증 논문
- **Dagnino2025**: 성인 주요우울장애 임상 표본에서 다양한 ACE 유형과 DERS 차원 관계 — 이 논문의 지역사회 표본 결과와 임상 표본 결과 비교

---

## 14. Terminology
- **EDS (Emotion Dysregulation Scale, short version)**: Powers et al. 개발, 12문항, 7점 Likert; 정서적 경험(emotional experiencing), 인지(cognition), 행동(behavior) 3 영역 측정; DERS 기반 단축형 (§Measures, p.6 PDF)
- **Complementary mediation (보완적 매개)**: Zhao et al. (2010) 분류 체계 — 간접효과(a×b)와 직접효과(c') 모두 유의하고 같은 방향일 때; Baron & Kenny (1986) 부분 매개와 유사하나 개념적으로 구별됨 (§Data analysis, p.7 PDF)
- **CTQ (Childhood Trauma Questionnaire)**: Bernstein et al. 개발, 28문항, 5점 Likert; 신체적 학대·방임, 성적 학대, 정서적 학대·방임 5 하위척도 (§Measures, p.6 PDF)
- **Grady Trauma Project**: 저소득 도시 지역 PTSD 위험·회복탄력성 요인 연구를 위한 NIH 5년 지원 코호트 (§Procedure, p.5 PDF)

---

## 15. Deferred
- Table 2 전체 회귀계수(특히 EDS 예측 모형의 각 CTQ 하위척도 β값) — 이미지 해상도로 일부 수치 불명확, 원문 접근 시 재확인
- 이 논문에서 사용한 Zhao et al. (2010) 보완적 매개 분류 기준 원문 확인 — 내 논문 매개 분석 결과 해석 시 어느 분류가 적용되는지 미리 파악 필요
