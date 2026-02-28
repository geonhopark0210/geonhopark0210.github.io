# Huang2025_emotion_dysregulation_perceived_social_support_link_childhoo

**Source**: Huang H, Wu H, Luo L, Jiao B, Wu Y, Zou G, Lin J, Wang W, Ma L (2025). The influence of emotion dysregulation and perceived social support on the link between childhood emotional abuse and depressive symptoms in college students: a moderated mediation model. *Frontiers in Psychiatry*, 16:1538390. DOI: 10.3389/fpsyt.2025.1538390
**Date Read**: 2026-02-24
**Mode**: READ

---

## 1. TL;DR
중국 대학생 1,728명을 대상으로 CEA → DERS → BDI(우울) 경로에서 지각된 사회적 지지(PSSS)의 조절된 매개(moderated mediation) 모형을 PROCESS macro로 검증한 연구. DERS가 CEA → 우울 경로를 유의하게 매개했고(간접효과 95% CI [0.131, 0.189]), PSSS는 EA→BDI 직접 경로와 DERS→BDI 간접 경로 모두를 약화시키는 조절 효과를 보였다. PSSS의 직접 경로 조절 효과는 남성 집단에서만 유의하고 여성 집단에서는 유의하지 않았다.

---

## 2. Core Contribution
- CEA → DERS → 우울 moderated mediation 모형을 중국 대학생 표본에서 확인한 첫 번째 대규모 연구 (기존 유사 연구는 N=276 네덜란드 여대생)
- PSSS가 DERS의 매개 효과 자체도 조절함을 확인 — 사회적 지지가 높을수록 정서조절곤란이 우울에 미치는 영향이 약화됨

---

## 3. Study Type
횡단 조사 (cross-sectional) + moderated mediation (PROCESS macro Model 4, 15) — §2.3, p.4–5 (PDF)

---

## 4. Sample & Setting
- N = 1,728명 (2,310명 모집, 유효 회수율 74.8%)
- 중국 광저우 광저우중의과대학 재학생
- 연령: 18–24세 (M = 18.34, SD = 0.67)
- 성별: 남성 654명(37.8%), 여성 1,074명(62.2%)
- CEA 경험 보고자: 285명(16.49%, EA 점수 9점 이상)
- 제외 기준: 만 18세 미만, 설문 완료 거부, 결측/불일치 응답
- 윤리 승인: 광저우중의과대학 제2부속병원 연구윤리위원회 (IEC GL/07.0/01.1)
- Locator: §2.1 Participants, p.4 (PDF)

---

## 5. Intervention / Exposure & Comparator
- **노출 변수**: CEA — CTQ-SF EA 하위척도
- 중재 없음 (관찰 연구)
- Locator: §2.2.1, p.4 (PDF)

---

## 6. Outcomes & Measures

| 변수 | 도구 | 내용 |
|------|------|------|
| CEA | CTQ-SF EA 하위척도 (중국판; Zhao et al., 2005) | 5문항, 5점 Likert (1=거의 없다 ~ 5=자주); 범위 0–25, **9점 이상 = CEA 경험으로 분류**; α=0.770 |
| 정서조절곤란 | DERS (Difficulties in Emotion Regulation Scale; Gratz & Roemer, 2004; 중국판 Wang et al., 2007) | 36문항, 5점 Likert; 범위 36–180; 6 하위척도: 정서인식, 정서수용, 충동통제, 목표지향행동, 정서조절전략, 정서명확성; **높을수록 더 심한 정서조절곤란**; α=0.942 |
| 지각된 사회적 지지 | PSSS (Perceived Social Support Scale; Zimet et al., 1990; 중국판) | 12문항, 7점 Likert; 범위 12–84; **높을수록 더 강한 지지 지각**; α=0.958 |
| 우울 | BDI (Beck Depression Inventory; Beck et al., 1996) | 21문항, 0–3 척도; 범위 0–63; 절단점: 0–9 정상, 10–18 경증, 19–29 중등도, 30–63 중증; α=0.890 |

- 측정 시점: 단일 횡단
- Locator: §2.2, p.4 (PDF)

---

## 7. Analysis
- **공통방법편향(CMB) 검토**: Harman 단일요인 검사 — 단일 요인 최대 설명 분산 23.6% < 40% 기준 → CMB 문제 없음
- **기술통계 및 상관**: SPSS 26.0, Pearson 상관
- **조절된 매개 분석**: PROCESS macro (Hayes, 2012) — 매개: Model 4, 조절된 매개: Model 15
- **부트스트랩**: 5,000회, 95% CI
- **상호작용항 구성**: 다중공선성 방지를 위해 모든 변수 평균 중심화(mean-centering) 후 상호작용항 생성
- **단순 기울기 분석**: PSSS M±1SD 수준에서 유의한 상호작용 시각화
- **공변인**: 성별, 연령 통제
- **다중공선성 진단**: TOL > 0.1, VIF < 5 확인 → 기준 충족
- **성별 분석**: 남녀 집단 분리 후 동일 모형 재검증
- 사전등록: Not reported
- Locator: §2.3, p.4–5 (PDF)

---

## 8. Key Results

**기술통계 (Tbl.1, p.5 PDF)**

| 변수 | M | SD | 범위 |
|------|------|------|------|
| EA (CEA) | 6.64 | 2.61 | 5–25 |
| DERS | 80.80 | 22.35 | 36–146 |
| PSSS | 64.81 | 13.12 | 12–84 |
| BDI (우울) | 4.90 | 6.33 | 0–45 |

- BDI 경증 이상 비율: 경증 14.12%(n=244), 중등도 4.17%(n=72), 중증 0.58%(n=10), **총 18.87%(n=326)**

**상관 (Tbl.2, 모두 p<0.001)**

| 쌍 | r |
|------|------|
| EA ↔ DERS | 0.375 |
| EA ↔ BDI | 0.448 |
| EA ↔ PSSS | -0.334 |
| DERS ↔ BDI | 0.534 |
| DERS ↔ PSSS | -0.460 |
| PSSS ↔ BDI | -0.366 |

**경로 분석 (Tbl.3, p.5–6 PDF)**

| 모형 | 예측변수 | B | R² |
|------|------|------|------|
| Model 1 (DV=DERS) | EA | 0.373*** | 0.142 |
| Model 2 (DV=BDI) | EA | 0.444*** | 0.203 |
| Model 3 (DV=BDI) | EA | 0.286***, DERS 0.425*** | 0.358 |
| Model 4 (DV=BDI) | EA 0.210***, DERS 0.402***, PSSS -0.094***, EA×PSSS -0.070***, DERS×PSSS -0.080*** | — | 0.381 |

**매개 효과 (PROCESS Model 4)**
- EA → DERS → BDI 간접효과: **95% CI [0.131, 0.189]** — 유의 (0 포함하지 않음)
- Locator: §3.4, p.5–6 (PDF)

**조절된 매개 효과 — 조건부 직접·간접효과 (Tbl.4, p.7 PDF)**

| PSSS 수준 | EA→BDI 직접 [CI] | EA→DERS→BDI 간접 [CI] |
|------|------|------|
| 낮음 (M−1SD) | 0.280 [0.236, 0.324] | 0.180 [0.142, 0.225] |
| 평균 (M) | 0.210 [0.163, 0.257] | 0.150 [0.123, 0.181] |
| 높음 (M+1SD) | 0.140 [0.068, 0.214] | 0.120 [0.094, 0.149] |

- 쌍별 대비(Tbl.5): 세 수준 간 간접효과 차이 모두 유의 → PSSS가 매개 경로를 유의하게 조절
- 고PSSS vs 저PSSS: 간접효과 감소 = -0.060, CI [-0.098, -0.026]
- Locator: Tbl.4–5, p.7 (PDF)

**성별 분석 (Fig.4, p.9 PDF)**

- 남성 집단: PSSS의 EA→BDI 조절 효과 B=-0.102, 95% CI [-0.161, -0.044] → **유의**; EA→BDI는 저PSSS에서만 유의, 고PSSS에서 유의하지 않음
- 여성 집단: PSSS의 EA→BDI 조절 효과 B=-0.045, 95% CI [-0.096, 0.007] → **유의하지 않음** (CI에 0 포함)
- PSSS의 DERS→BDI 조절 효과: 두 집단 모두 유의
- Locator: §3.6, Fig.4, p.7–9 (PDF)

---

## 9. Limitations
- 중국 의대 대학생 표본 → 임상 집단 및 다른 문화권 일반화 제한 (§5, p.9–10 PDF)
- 성별 불균형 (남:여 ≈ 1:1.64) — 성별 효과 통계적 통제로 보완 (§5, p.9–10 PDF)
- 횡단 설계 → 인과 방향 확정 불가 (§5, p.10 PDF)
- CEA 심각도만 측정, 발생 시점·기간·특성 미수집 (§5, p.10 PDF)
- 사회경제적 지위(SES) 미측정 (§5, p.10 PDF)
- 자기보고 회고 측정 → 회상 편향 가능 (§5, p.10 PDF)
- 지각된 사회적 지지(주관적)와 실제 사회적 지지 구분 없음 (§5, p.10 PDF)

---

## 10. Open Questions
- PSSS가 DERS→BDI 경로를 약화시키는 것처럼, mentalization(RFQ)도 같은 경로를 조절할 수 있는가? — 내 연구의 핵심 질문이 이 논문이 남긴 빈자리를 직접 채운다.
- 성별 차이(PSSS 조절 효과가 남성에서만 유의) — RFQ의 조절 효과도 성별에 따라 달라지는가? 내 연구에서 성별을 공변인으로 통제할 것인가, 아니면 조절변수로 탐색할 것인가?

---

## 11. Personal Insights (개인 인사이트)
- 이 논문이 사용한 모형 구조(CEA → DERS → BDI, PSSS 조절)가 내 연구 모형과 거의 동일하다. 조절변수만 PSSS → RFQ로 바꾸면 내 연구가 된다. "기존 연구에서 DERS 매개 경로의 조절변수로 mentalization을 검토한 연구가 없다"는 novelty 주장을 이 논문이 직접 뒷받침한다.
- CTQ-SF EA 하위척도(5문항, 0–25)와 full CTQ-28 EA 하위척도(5문항, 5–25)는 같은 내용이나 범위 표기가 다르다 — 내 연구에서 어느 버전을 쓸지 명확히 해야 한다. 이 논문 M=6.64(SD=2.61)가 참조값이 될 수 있다.
- DERS M=80.80(SD=22.35) — 일반 대학생 표본에서의 DERS 기대 범위를 보여줌. 내 표본의 DERS 점수 예측에 참고.
- 우울 유병률이 생각보다 낮다(경증 이상 18.87%) — 한국 대학생 표본에서 유사하거나 더 높을 가능성 있음. 표본 크기 산정 시 참고.
- 성별 조절 효과 차이가 흥미롭다. 한국 표본에서 RFQ의 조절 효과를 분석할 때 성별을 사전 공변인으로 통제하는 것이 안전할 것 같다.

---

## 12. Research Ideas (연구 아이디어)
- **직접 확장 모형**: 이 논문의 PSSS 자리에 RFQ(mentalization)를 대입 — CEA → DERS → 우울, RFQ가 DERS→우울 경로 조절. 이 논문이 제안한 "정서조절곤란 매개 경로의 조절변수 탐색" 방향을 mentalization으로 구체화하는 것.
- RFQ와 PSSS를 **동시에** 조절변수로 포함하는 이중 조절된 매개 모형도 가능하나 — 내 석사 연구에서는 단순성 유지가 중요하므로 RFQ 단독 조절에 집중하는 것이 적절.
- 이 논문의 기술통계(CTQ-SF EA M=6.64, DERS M=80.80, BDI M=4.90)를 내 연구의 예상 기술통계 참조값으로 사용. 단, 한국 표본이므로 차이 발생 가능.
- PROCESS macro Model 14(단순 조절된 매개) 또는 Model 15(이중 조절된 매개) 사용 — 내 연구 설계 시 이 논문의 Model 15 활용 방식 참고.
- 5,000회 부트스트랩 방법 및 mean-centering 절차 → 내 분석 방법 섹션 작성 시 동일 방법 기술.

---

## 13. Connections (연결 고리)
- **Crow2014**: N=3,902 저소득 아프리카계 미국인 성인에서 CEA → DERS → 우울 단순 매개 확인 → 이 논문이 대학생 표본으로 확장하고 조절변수(PSSS) 추가
- **MartinGagnon2023**: CEA → Mentalization → 우울 매개 (DERS 없음) → 내 연구는 두 논문을 통합: DERS 매개 + mentalization 조절
- **Huh2017_childhood_trauma_severity_adulthood_depression_anxiety**: 아동기 외상 → 정서조절 → 우울/불안 경로 검증 (이 논문과 CEA 특이성 vs 전반적 외상 비교)
- 이 논문의 모형 구조 = 내 연구의 **가장 가까운 전신(前身)** — 논문 서론에서 "조절변수로 PSSS 대신 mentalization을 검토할 필요성"을 이 논문을 인용하며 직접 제기할 수 있음

---

## 14. Terminology
- **CTQ-SF (Childhood Trauma Questionnaire-Short Form)**: Bernstein et al. 개발 28문항 단축형; EA 하위척도 5문항, 5점 Likert, 범위 0–25 (이 논문 기준); 9점 이상 = CEA 경험 분류 기준 (§2.2.1, p.4 PDF)
- **DERS (Difficulties in Emotion Regulation Scale)**: Gratz & Roemer (2004) 개발, 36문항, 5점 Likert; 6 하위척도: 비수용(nonacceptance), 목표(goals), 충동(impulse), 인식(awareness), 전략(strategies), 명확성(clarity); 범위 36–180 (§2.2.2, p.4 PDF)
- **PSSS (Perceived Social Support Scale)**: Zimet et al. (1990), 12문항, 7점 Likert; 가족·친구·중요타인 3 영역; 범위 12–84 (§2.2.3, p.4 PDF)
- **Moderated mediation (조절된 매개)**: 매개 효과의 크기가 조절변수 수준에 따라 달라지는 모형; 이 논문에서는 PSSS가 매개 경로(DERS→BDI)와 직접 경로(EA→BDI) 모두를 조절 (§2.3, p.4–5 PDF)
- **Mean-centering (평균 중심화)**: 조절된 매개 분석에서 상호작용항 구성 전 변수에서 평균을 빼는 절차 — 다중공선성 감소 목적 (§2.3, p.5 PDF)

---

## 15. Deferred
- PROCESS macro Model 4 vs Model 15 차이 재확인 — Model 4: 단순 매개; Model 15: 매개변수 경로에 조절변수가 붙는 조절된 매개. 내 연구에서 mentalization이 DERS→BDI만 조절하는지, EA→DERS도 조절하는지에 따라 적합 Model 번호가 다름.
- 성별 분리 분석 결과(Supplementary Materials) — 이 논문에서 남/여 전체 경로 계수를 비교한 보충 자료 내용 확인 필요.
