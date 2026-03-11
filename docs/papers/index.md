# 최신 논문

## [Dynamic Stability Assessment of Grid-Connected Data Centers Powered by Small Modular Reactors](https://arxiv.org/abs/2603.09110)
- 저자: Sobhan Badakhshan 외
- 연도/학회(저널): 2026-03-10, arXiv (eess.SY)
- 한 줄 요약: AI·고성능 컴퓨팅 수요가 커지는 데이터센터를 SMR+BESS 통합에너지시스템으로 공급할 때 전압·주파수 안정도가 어떻게 개선되는지 IEEE 118-bus 계통에서 동특성 시뮬레이션으로 검증.

### 핵심 기여
1. CPU 사용률·냉각효율·외기온을 함께 반영한 데이터센터 계산-열부하 연계 모델 제시
2. SMR와 배터리 저장장치를 결합한 계통연계형 전력공급 구조의 안정도 평가
3. AI 데이터센터 전력원으로서 SMR 적용 시 사고 후 회복력과 계통 지원 효과를 정량 비교

---

## [Bayesian neural network with autoencoder for model-based description of α-particle preformation factor](https://arxiv.org/abs/2603.07976)
- 저자: Xiao-Yan Zhu 외
- 연도/학회(저널): 2026-03-09, arXiv (nucl-th)
- 한 줄 요약: 베이지안 신경망과 오토인코더를 결합한 BNN-Auto 프레임으로 중·초중원소의 α 붕괴 전형성 인자와 반감기를 더 정확하게 예측하고, 불확실성까지 함께 제시.

### 핵심 기여
1. 535개 핵종 실험데이터 기반으로 α-입자 preformation factor 예측 오차를 크게 감소
2. 변분추론 기반 확률 모델링으로 예측값과 신뢰구간을 동시에 제공
3. Z=120, N=184 부근 안정섬(shell effect) 후보의 반감기 증가 경향까지 ML로 탐색

---

## [딥러닝 기반 원전 1차 열전달계통 상태변수 다단계 예측](https://www.researchgate.net/publication/401395050_Multistep_forecasting_of_state_variables_in_nuclear_power_plants_using_deep_learning)
- 저자: (Nuclear Engineering and Design 저자팀)
- 연도/학회(저널): 2026-03, *Nuclear Engineering and Design*
- 한 줄 요약: LSTM, CNN, zLSTM 등 딥러닝 모델을 활용해 원전 1차 열전달(PHT) 루프 3개 핵심 노드의 운전 상태변수를 다단계(multistep) 예측하는 프레임워크를 제시하고, 운전원의 추세 파악 및 안전성 향상에 기여.

### 핵심 기여
1. CNN+LSTM 협업 구조로 특징 추출과 시계열 메모리를 동시 활용한 다단계 예측
2. PHT 루프 3개 노드(반응기·증기발생기·펌프) 핵심 파라미터 동시 모델링
3. 원전 운전 중 이상 추세 조기 식별을 위한 데이터 기반 의사결정 지원 플랫폼

---

## [GRU-MLP 기반 원전 계측제어 운전데이터 이상탐지·보정](https://www.mdpi.com/2227-9717/14/2/192)
- 저자: (MDPI Processes 저자팀)
- 연도/학회(저널): 2026-01, *Processes* (MDPI)
- 한 줄 요약: GRU 기반 단기예측과 MLP 분류기를 결합해 원전 I&C 계통의 랜덤 점프·고정값 드리프트·성장 드리프트 등 3가지 이상 패턴을 탐지·보정하는 방법을 제시하고, PWR 운전 데이터로 검증.

### 핵심 기여
1. GRU 모델의 시계열 예측을 기준값으로 활용한 이상탐지 프레임워크 제안
2. MLP 분류기로 이상 유형 자동 식별 및 보정값 생성
3. 가압경수로(PWR) 실제 운전 데이터 기반 실증으로 I&C 데이터 품질 향상 효과 확인

---

## [AI-Assisted Fire Risk Target Detection for Special Operating Conditions in Under-Construction Nuclear Power Plants](https://www.mdpi.com/2571-6155/9/3/115)
- 저자: (MDPI Fire 저자팀)
- 연도/학회(저널): 2026-03, *Fire* (MDPI)
- 한 줄 요약: 건설 중 원전의 야간·저조도 환경에서 화재 위험 요소를 정밀 탐지하기 위해 개선된 YOLOv8n 딥러닝 모델을 제안, 소형 대상 인식률과 오경보 억제를 동시에 달성.

### 핵심 기여
1. 원전 건설 현장의 용접·절단 작업 등 특수 환경에 맞춘 화재 위험 객체 탐지 모델 제시
2. 저조도 환경에서 불꽃과 조명을 구분하는 오경보 억제 메커니즘 포함
3. 건설 단계 원전의 화재안전 감시 자동화에 AI 적용 가능성 실증

---

## [Bayesian Learning of (n,p) Reaction Cross Sections with Quantified Uncertainties](https://arxiv.org/abs/2603.04789)
- 저자: Arunabha Saha, Songshaptak De
- 연도/학회(저널): 2026-03-05, arXiv (nucl-th)
- 한 줄 요약: 베이지안 신경망(BNN)으로 (n,p) 반응 단면적을 예측하고 불확실성을 함께 정량화해, 실험 데이터가 희소한 핵데이터 평가의 신뢰도를 높임.

### 핵심 기여
1. ENDF/B-VIII.1 기반 학습 + 물리 특성 6개 입력으로 핵반응 단면적 예측 프레임 제시
2. 확률적 변분추론으로 예측값과 신뢰구간을 동시에 제공
3. SHAP 분석으로 이론 단면 입력의 영향도를 설명 가능하게 제시

---

## [Expanding Universal Machine Learning Interatomic Potentials to 97 Elements Towards Nuclear Applications](https://arxiv.org/abs/2603.03223)
- 저자: Naoya Kuroda 외
- 연도/학회(저널): 2026-03-03, arXiv (physics.chem-ph)
- 한 줄 요약: 악티나이드(소악티나이드) 데이터를 포함해 97개 원소 범위의 범용 ML 원자간 퍼텐셜을 구축, 원자력 재료 설계 적용 가능성을 확장.

### 핵심 기여
1. 기존 범용 MLIP의 중원소 공백을 보완하는 HE26 데이터셋 제시
2. 분자/결정 데이터와 통합해 97원소 커버 모델 공개
3. 원자력 재료(고엔트로피 세라믹 등) 탐색 가속 기반 제공

---

## [Quantifying Uncertainty in Void Swelling Prediction: A Conformal Prediction Framework for Reactor Safety Margins](https://arxiv.org/abs/2603.01981)
- 저자: Minhee Kim, Yong Yang
- 연도/학회(저널): 2026-03-02, arXiv (stat.AP)
- 한 줄 요약: 원자로 재료의 공공팽윤 예측에 적합예측(Conformal Prediction)을 결합해, 점추정 중심 ML의 불확실성 한계를 보완.

### 핵심 기여
1. 앙상블 ML + 적합예측으로 신뢰구간 보정
2. 조사 손상 데이터의 이분산성(초기/성장 구간)을 반영한 추론 프레임 제시
3. 재료 건전성·인가 평가에 활용 가능한 확률적 안전여유 평가 기반 제공

---

## [Advances in digital twins and AI/ML for condition monitoring in nuclear applications](https://www.frontiersin.org/journals/energy-research/articles/10.3389/fenrg.2026.1716514/full)
- 저자: W. Neal 외
- 연도/학회(저널): 2026-02-17, *Frontiers in Energy Research*
- 한 줄 요약: 디지털 트윈과 AI/ML을 결합해 원전 상태감시(이상탐지·예지정비·규제적용) 정확도와 현장 적용성을 높이는 최신 사례를 정리.

### 핵심 기여
1. LWR/비경수로 대상 상태감시 use case를 디지털 트윈 관점에서 통합 정리
2. LSTM/오토인코더 기반 이상탐지·분류 모델의 원전 적용 패턴 제시
3. 실증·규제 연계를 위한 데이터 품질·검증 절차 이슈를 구조화

---

## [Physics Informed Bayesian Machine Learning of Sparse and Imperfect Nuclear Data](https://arxiv.org/abs/2602.01808)
- 저자: Junchen Pei 외
- 연도/학회(저널): 2026-02-02, arXiv (nucl-th)
- 한 줄 요약: 물리모델 기반 사전정보를 베이지안 ML에 결합해 희소·불완전 핵분열 수율 데이터를 보정하고 에너지 의존성을 더 안정적으로 추정.

### 핵심 기여
1. 물리모델 posterior를 informative prior로 주입해 소량 데이터 학습 한계 완화
2. 누적 핵분열 수율 제약을 포함해 물리 일관성 유지
3. 고비용 핵데이터 평가에 적용 가능한 베이지안 추론 워크플로우 제시

---

## [Formalization of a Nuclear Power Plant Life-Cycle Model for AI and Machine Learning Applications](https://dmitrishin.github.io/publications/)
- 저자: Yuriy Dmitrishin
- 연도/학회(저널): 2026-02-08
- 한 줄 요약: 원자력발전소 전 수명주기(설계-건설-운영-해체) 관리를 위한 AI/ML 작업을 지원하는 정형화된 연구 모델 제안.

### 핵심 기여
1. 원전 수명주기 각 단계별 AI/ML 적용 과제 체계화
2. 데이터 기반 의사결정 지원을 위한 모델링 프레임워크
3. 규제 준수 및 안전성 검증을 고려한 구조화

---

## [Applications of Machine Learning and Artificial Intelligence in Modern Power and Energy Systems](https://www.mdpi.com/2079-9292/15/5/1045)
- 저자: Mladenov, Sarigiannidis
- 연도/학회(저널): 2026-03-02, Electronics (MDPI)
- 한 줄 요약: 현대 전력·에너지 시스템 전반에 걸친 ML/AI 응용을 종합적으로 다룬 논문으로 원자력 포함 다양한 발전원 최적화 사례 수록.

### 핵심 기여
1. 전력 시스템 운영 최적화에 ML/AI 적용 방법론 정리
2. 재생에너지-원자력 혼합 시스템에서 AI 활용 사례
3. 스마트그리드 및 에너지 저장 시스템과의 연계 방안

---

## [Machine Learning Applied to Problems of Nuclear Fusion](https://www.researchgate.net/publication/400778494_Machine_Learning_Applied_to_Problems_of_Nuclear_Fusion)
- 저자: E. I. Chetkin 외
- 연도/학회(저널): 2026-02-14
- 한 줄 요약: 핵융합 연구의 주요 난제(플라즈마 제어, 재료 내성, 에너지 수율 최적화)에 ML 기법을 적용한 연구 동향 정리.

### 핵심 기여
1. 플라즈마 불안정성 예측에 딥러닝 활용 방안
2. 핵융합로 재료 개발 가속화를 위한 ML 접근
3. DOE Genesis Mission의 융합 에너지 AI 챌린지와 연계

---

## [A Fifth Face? The Evolving Threat of Nuclear Terrorism in the Age of Artificial Intelligence](https://kclpure.kcl.ac.uk/portal/en/publications/5f31843a-b318-4c70-84df-c47b6a46f22d)
- 저자: Muhammed Ali Alkis 외
- 연도/학회(저널): 2026, *The Nonproliferation Review*
- 바로가기: [King’s College London Repository](https://kclpure.kcl.ac.uk/portal/en/publications/5f31843a-b318-4c70-84df-c47b6a46f22d)
- 한 줄 요약: 생성형 AI 확산이 핵테러 위협 지형을 어떻게 바꾸는지 분석하고, 비확산·안보 거버넌스의 대응 프레임을 제시.

### 핵심 기여
1. AI 도구가 핵안보 위협에 미치는 경로를 정책 관점에서 구조화
2. 기술 접근성 확대가 비국가 행위자 리스크에 주는 영향 정리
3. 핵안보·AI 거버넌스 통합 대응 필요성 제시

### 실무 적용 아이디어
- 원자력 시설 사이버·물리 통합 보안 훈련 시 AI 기반 위협 시나리오를 포함하는 체크리스트로 활용

---

## [ReactorFold: Generative discovery of nuclear reactor cores via emergent physical reasoning](https://arxiv.org/abs/2512.15756)
- 저자: Yutong Xie 외
- 연도/학회(저널): 2025, arXiv
- 바로가기: [ArXiv 원문](https://arxiv.org/abs/2512.15756)
- 한 줄 요약: 원자로 연료집합체 설계를 시퀀스 생성 문제로 바꿔 언어모델 기반 생성·선호최적화(DPO)로 신규 설계 후보를 탐색.

### 핵심 기여
1. 고정된 수동 탐색 공간을 넘어 생성형 모델로 설계 공간 확장
2. Monte Carlo 데이터 + 파라미터 효율 미세조정으로 설계 품질 개선
3. 원자로 코어 설계 자동화 워크플로우 가능성 제시

### 실무 적용 아이디어
- 설계 초안 생성기(아이디어 엔진)로 사용 후 기존 중성자해석 코드와 결합 검증

---

## [AI-Driven Cybersecurity Testbed for Nuclear Infrastructure](https://arxiv.org/abs/2512.01727)
- 저자: Pedro H. Ferreira 외
- 연도/학회(저널): 2025, arXiv
- 바로가기: [ArXiv 원문](https://arxiv.org/abs/2512.01727)
- 한 줄 요약: METL 운전 데이터를 바탕으로 원자력 제어계통 대상 AI 기반 이상탐지 방법(Change Point, LSTM, Autoencoder 등)을 비교 평가.

### 핵심 기여
1. 원자력 사이버-물리 공격 시나리오 다중 분류/평가 프레임워크 제시
2. 탐지 패러다임별 강점·한계(정밀도/지연/강건성) 비교
3. 실제 인프라 적용을 염두에 둔 시험환경 기반 검증 절차 제안

### 실무 적용 아이디어
- 원전 보안관제에서 다중 모델 앙상블 탐지 체계 구축 시 기준 레퍼런스로 활용

---

## [Nuclear Microreactor Control with Deep Reinforcement Learning](https://arxiv.org/abs/2504.00156)
- 저자: James A. R. Walker 외
- 연도/학회(저널): 2025, arXiv
- 바로가기: [ArXiv 원문](https://arxiv.org/abs/2504.00156)
- 한 줄 요약: 마이크로리액터 실시간 제어(load-following)에 RL 제어기를 적용해 PID 대비 성능 가능성을 검토.

### 핵심 기여
1. 점동역학 + 열/제논 피드백 모델 기반 RL 제어 실험
2. 단일 출력 RL과 전통 PID 제어기 성능 비교
3. 자율운전형 마이크로리액터 제어 가능성 실증

### 실무 적용 아이디어
- 디지털 트윈 환경에서 RL 제어기 사전학습 후 운전보조(의사결정 추천) 단계부터 점진 적용
