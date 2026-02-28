# 최신 논문

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
