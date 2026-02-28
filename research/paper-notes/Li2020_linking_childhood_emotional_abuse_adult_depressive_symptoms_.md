# Li2020_linking_childhood_emotional_abuse_adult_depressive_symptoms_

**Source**: Li, E. T., Carracher, E., & Bird, T. (2020). Linking childhood emotional abuse and adult depressive symptoms: The role of mentalizing incapacity. *Child Abuse & Neglect*, *99*, 104253. https://doi.org/10.1016/j.chiabu.2019.104253
**Date Read**: 2026-02-18
**Mode**: READ

---

## 1. TL;DR

아동기 정서적 학대(CEA)가 성인 우울 증상으로 이어지는 경로에서 정신화 무능력(hypermentalizing, hypomentalizing)의 매개 역할을 검증한 횡단 연구다. 영국 성인 205명을 대상으로 계층적 다중 회귀분석과 부트스트랩 매개 분석을 실시한 결과, CEA는 다른 아동기 학대 유형 전부를 통제한 후에도 우울의 독립적 예측변수였고, hypermentalizing과 hypomentalizing 모두 CEA → 우울 경로를 유의하게 매개하는 것으로 확인됐다.

---

## 2. Core Contribution

- CEA가 신체적·성적 학대, 방임, antipathy를 모두 통계적으로 통제한 후에도 성인 우울의 가장 강력한 독립 예측변수임을 입증함
- 정신화 무능력의 두 하위유형(hypermentalizing, hypomentalizing)이 각각 CEA → 우울 경로를 매개한다는 것을 처음으로 직접 검증함

---

## 3. Study Type

횡단 온라인 설문 (Cross-sectional online survey) · §2.1, p.3 (PDF)

---

## 4. Sample & Setting

- N = 205 (여성 80.5%)
- 연령: M = 28.2세, SD = 10.86, 16세 이상
- 주 양육자: 친모만 52.6%, 친부모 동등 40.3%
- 모집: 소셜 미디어 및 온라인 연구 플랫폼 광고
- 설정: 영국 에든버러 대학교 윤리 승인, Jisc Online Surveys 플랫폼, 2018년 5~6월
- 포함 기준: 16세 이상 성인, 온라인 동의
- 명시적 제외 기준: Not reported
- G*Power 3.1 사전 검정력 분석: β = 0.8, α = .05에서 최소 N = 68 필요 → 충족
- Locator: §2.2, p.3 (PDF)

---

## 5. Intervention / Exposure & Comparator

- **주요 노출**: 아동기 정서적 학대(CEA) — CATS(Child Abuse and Trauma Scale)-EA 7문항, 5점 Likert (0=Never, 4=Always), Cronbach's α = .92 · §2.3.3, p.3-4 (PDF)
- **공변량으로 통제된 다른 학대 유형**:
  - 성적·신체적 학대: ACE 단일 이분 문항 각 1개
  - 방임·antipathy: CECA.Q 부모 돌봄 하위척도 (각 8문항 × 부모 2명, 5점 Likert), Cronbach's α = .92
- 비교 조건 없음 (관찰 연구), 다른 학대 유형을 계층적 투입 방식으로 통계 통제
- Locator: §2.3.2–2.3.4, p.3-4 (PDF)

---

## 6. Outcomes & Measures

- **결과변수**: 우울 증상 — DASS-21 Depression 하위척도 7문항, 4점 Likert (0~3), Cronbach's α = .91 · §2.3.6, p.4 (PDF)
- **매개변수**: 정신화 무능력 — RFQ(Reflective Functioning Questionnaire) 8문항, 7점 Likert · §2.3.5, p.4 (PDF)
  - RFQ_C (Certainty about Mental States) → hypermentalizing 지표
  - RFQ_U (Uncertainty about Mental States) → hypomentalizing 지표
  - Cronbach's α = .76
- 측정 시점: 단일 시점 (횡단)
- Locator: §2.3, p.3-4 (PDF)

---

## 7. Analysis

- SPSS Statistics 24.0
- 상관분석: 연속 변수 간 Pearson, 이분 변수(성적·신체적 학대)와 연속 변수 간 point-biserial, 방임·antipathy는 Spearman's rank
- 계층적 다중 회귀분석: 6모델 (성적학대 → 신체학대 → 방임 → antipathy → CEA → hypermentalizing → hypomentalizing 순 단계별 투입)
- 매개 분석: PROCESS macro v3 (Hayes, 2018), 5000 bootstrap resamples, 95% bias-corrected CI
- 결측치: 없음 (no missing values)
- 사전등록: Not reported
- Locator: §2.4, p.4 (PDF)

---

## 8. Key Results

**상관분석** (Tbl.1, p.5):
- CEA ↔ hypermentalizing: β = -.33, p < .001 (음의 상관 → CEA 높을수록 hypermentalizing 낮음 = 확신 증가)
- CEA ↔ hypomentalizing: β = .34, p < .001
- Hypermentalizing ↔ hypomentalizing: r = .54, p < .01 (동시 발생 가능)

**회귀분석** — 최종 모델 (Model 6, Tbl.2, p.6):
- R² = .36, F(7, 197) = 14.33, p < .001
- CEA: β = .31, p < .01 (모든 변수 투입 후에도 독립적 예측)
- Hypomentalizing: β = .40, p < .001
- 성적·신체적 학대, 방임, antipathy, hypermentalizing: 모두 비유의 (p > .05)

**매개 분석** (Fig.1, p.6 / Fig.2, p.7):
- Hypomentalizing 매개: indirect effect b = 2.02, 95% CI [0.96, 3.25] → **유의한 매개**
  - Path a (CEA → hypomentalizing): b = 0.29***
  - Path b (hypomentalizing → depression): b = 6.94***
  - 직접 효과 c' = 3.54***
- Hypermentalizing 매개: indirect effect b = 1.26, 95% CI [0.59, 1.99] → **유의한 매개**
  - Path a (CEA → hypermentalizing): b = -0.36*** (CEA 높을수록 certainty 증가)
  - Path b (hypermentalizing → depression): b = -3.50***
  - 직접 효과 c' = 4.30***

---

## 9. Limitations

1. 횡단 설계 → 인과관계 추론 불가, 종단 연구 필요 · §4, p.8 (PDF)
2. 자기보고식 도구만 사용 → 우울한 사람이 아동기 경험을 더 부정적으로 회상하는 인지 왜곡 가능성 · §4, p.8 (PDF)
3. 성적·신체적 학대를 단일 이분 문항(ACE)으로 측정 → CEA(7문항 Likert)와 측정 정밀도 불균형 · §4, p.8 (PDF)
4. N = 205, 여성 80.5% → 남성 과소 대표, 일반화 제한 · §4, p.8 (PDF)
5. RFQ가 타인이 아닌 자기 정신 상태 추론 위주 → 측정 범위 제한; 향후 AAI-RF 또는 MentS 척도 권고 · §4, p.8 (PDF)
6. 다양한 학대 유형의 누적·상호작용 효과 미반영 · §4, p.8 (PDF)

---

## 10. Open Questions

1. Hypermentalizing과 hypomentalizing이 각각 어떤 발달 경로로 CEA → 우울에 기여하는지 — 두 유형이 공존하면서 억제 효과(suppressor effect)가 발생할 가능성도 언급됨
2. 정신화 능력 향상 개입(예: MBT, CBASP)이 CEA 경험자의 우울 예방에 얼마나 효과적인지 무선통제연구로 검증 필요

---

## 11. Personal Insights (개인 인사이트)

- CEA가 신체적·성적 학대보다 우울 예측력이 강하다는 결과가 반직관적이면서도 납득된다. "침묵하는" 학대라서 피해자가 스스로 학대로 인식하지 못한 채 자기 표상에 만성적으로 스며들기 때문
- Hypermentalizing과 hypomentalizing 두 방향 모두 우울로 이어진다는 점이 흥미롭다. 정신화 능력이 없는 것뿐 아니라, 과도하게 정신화하는 것도 오히려 해가 된다는 역설
- RFQ를 매개변수로 활용한 방식이 실증적으로 잘 작동한다는 것을 보여줌. 내 연구에서는 조절변수로 쓰는데, 이 결과가 "왜 조절인가"를 정당화하는 배경 근거로 쓸 수 있음
- 이 연구에 DERS(정서조절곤란)가 빠져 있다. CEA → 정신화 무능력 → 우울 경로와 CEA → DERS → 우울 경로가 어떻게 경쟁하거나 보완하는지는 아직 미검증 상태
- PROCESS macro 5000 bootstrap 방식이 내 연구의 moderated mediation 분석에 그대로 적용 가능하다는 확신이 생겼다

---

## 12. Research Ideas (연구 아이디어)

- 이 연구는 mentalizing을 **매개변수**로 썼지만, 내 모델은 **조절변수**로 설정 → 선행 연구 리뷰에서 "Li et al.(2020)은 정신화를 매개로 검증했으나, 본 연구는 조절 기제를 검토한다"는 식으로 차별성 서술 가능
- DERS를 추가하면 mentalizing의 역할이 어떻게 변화하는지 — 이 연구에서 빠진 DERS가 CEA → 우울 경로에서 mentalizing과 어떻게 상호작용하는지가 내 연구의 핵심 기여가 됨
- RFQ_C(hypermentalizing)와 RFQ_U(hypomentalizing)를 각각 따로 조절변수로 분석하면 보다 정교한 모델 가능
- 통제변수 처리 방식 참고: 다른 학대 유형(신체적·성적 학대)을 공변량으로 포함하는 전략을 내 연구에도 적용 (CTQ 하위척도 활용)
- DASS-21 Depression 척도를 결과변수로 검토할 것 (신뢰도·타당도 확인됨)

---

## 13. Connections (연결 고리)

- **Schulz et al. (2017)**: CEA → BPD 특성 → 우울 경로. 본 논문의 이론적 출발점. 정신화 손상이 BPD와 우울의 공통 기제임을 시사
- **Crow et al. (2014)**: 정서조절곤란(emotion dysregulation)이 CEA → 우울 경로 매개 — 본 논문에서 DERS를 포함하지 않은 공백을 채우는 핵심 선행 연구, 내 연구의 직접적 근거
- **Fonagy et al. (2016)**: RFQ 개발 및 타당화 논문. 본 연구의 측정 도구 근거
- **Hayes (2018)**: PROCESS macro. 매개·조절된 매개 분석의 방법론적 근거 — 내 연구에도 동일 적용

---

## 14. Terminology

- **정신화 무능력(mentalizing incapacity)**: 자기 및 타인의 정신 상태를 이해하고 예측하는 능력이 손상된 상태 (§1, p.2-3 PDF)
- **과잉정신화(hypermentalizing)**: 정신 상태에 대해 과도하게 확실하게 추론하는 경향; 반복적·분석적·과도하게 상세한 사고 패턴 (§1, p.3 PDF)
- **저정신화(hypomentalizing)**: 정신 상태에 대한 지식이 거의 없는 상태; 욕구와 감정이 관찰 가능한 행동과 동일시됨 (§1, p.3 PDF)
- **RFQ(Reflective Functioning Questionnaire)**: Fonagy et al.(2016) 개발, 정신화를 자기보고로 측정하는 8문항 척도 (§2.3.5, p.4 PDF)
- **CATS-EA(Child Abuse and Trauma Scale-Emotional Abuse)**: Kent & Waller(1998) 개발, CEA 측정 7문항 5점 Likert (§2.3.3, p.3-4 PDF)
- **DASS-21**: Depression Anxiety Stress Scales-21, Lovibond & Lovibond(1995), 우울·불안·스트레스 측정 (§2.3.6, p.4 PDF)
- **CECA.Q**: Childhood Experience of Care and Abuse Questionnaire, 방임·antipathy 측정 (§2.3.4, p.4 PDF)

---

## 15. Deferred

- **Fonagy et al. (2016)** RFQ 개발 논문 직접 읽기 → 내 연구에서 RFQ 사용 시 척도 선택 근거로 필수
- **Crow et al. (2014)** 정서조절곤란 매개 논문 읽기 → 내 연구 모델(CEA → DERS → Depression)의 핵심 선행 연구
