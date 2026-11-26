---
title: Abstract Physics
aliases:
tags:
  - references
  - gemini
  - quantum
up:
stage: seeding
date: 2026-11-21 12:23:25
lastmod: 2026-11-22 13:25:13
draft: true
---
시공간의 직관이나 구체적인 입자 모형을 걷어내고, **순수 수학적 구조(대수, 논리, 범주론, 대칭성 공리화)로부터 물리적 실체와 불변량을 도출하는 분야**의 핵심 참고문헌들을 주제와 접근 수준별로 정리했습니다.

### 1. 범주론적 양자역학 & 정보 구조 (가장 직관적인 진입점)

시공간 배경 없이 '과정(Morphism)들의 합성 구조'만으로 양자역학과 정보의 법칙을 연역적으로 도출하는 분야입니다.

- **Bob Coecke & Aleks Kissinger, _Picturing Quantum Processes: A First Course in Quantum Theory and Diagrammatic Reasoning_ (2017)**
    - **특징:** 행렬이나 미분방정식 대신 끈 다이어그램(String diagrams)과 단검 콤팩트 범주(Dagger compact categories)만을 사용해 양자역학의 공리를 바닥부터 재구성합니다.
    - **추천 이유:** 수학적 엄밀함을 유지하면서도 시각적 직관이 뛰어나 범주론적 물리학의 사고방식을 체득하기에 가장 좋은 입문서입니다.
- **John C. Baez & Mike Stay, _"Physics, Topology, Logic and Computation: A Rosetta Stone"_ (2010, arXiv:0903.0340)**
    - **특징:** 물리학(양자역학), 위상수학(코보디즘), 논리학, 계산 이론이 모두 동일한 '닫힌 대칭 모노이달 범주'의 서로 다른 표현에 불과하다는 것을 보여주는 기념비적 논문입니다.

### 2. 대수적 양자장론(AQFT) & 연산자 대수 (폰 노이만 대수와 시간의 창발)

입자나 장의 값 대신 '관측 가능량들의 대수(Von Neumann Algebras)'만을 유일한 물리적 실체로 다루는 분야입니다.

- **Rudolf Haag, _Local Quantum Physics: Fields, Particles, Algebras_ (1996)**
    - **특징:** 국소적 인과율과 대수적 구조만으로부터 입자 개념, 산란 이론, 그리고 폰 노이만 대수의 Type III 성질이 어떻게 필연적으로 도출되는지 다룬 고전입니다.
- **Edward Witten, _"Notes on Some Entanglement Properties of Quantum Field Theory"_ (2018, Rev. Mod. Phys. / arXiv:1803.04993)**
    - **특징:** 대수적 양자장론의 핵심인 토미타-타케사키 이론(Tomita-Takesaki theory)과 모듈러 흐름(Modular flow), 그리고 왜 양자장론의 대수가 Type III인지 현대 물리학자의 언어로 명쾌하게 풀어낸 리뷰 논문입니다. (최근 블랙홀 정보 역설 및 Type II 대수 연구의 출발점이 된 문헌입니다.)
- **Alain Connes & Carlo Rovelli, _"Von Neumann Algebra Automorphisms and Time-Thermodynamics Relation in General Covariant Quantum Theories"_ (1994, arXiv:gr-qc/9406019)**
    - **특징:** 배경 시공간이 없는 일반 공변 이론에서 '시간의 흐름'이 어떻게 대수의 자기동형사상(Modular flow)과 열역학적 상태로부터 창발하는지 제시한 논문입니다.

### 3. 대칭성의 범주론적 공리화 & 고차/비역전 대칭성 (SymTFT와 새로운 물리량)

대칭성을 '군(Group)'에서 '융합 범주(Fusion Category)'와 '위상적 결함'으로 확장하여 숨겨진 물리량과 선택 규칙을 분류하는 최신 흐름입니다.

- **Pavel Etingof, Shlomo Gelaki, Dmitri Nikshych, Victor Ostrik, _Tensor Categories_ (2015)**
    - **특징:** 융합 범주, 모듈러 텐서 범주(MTC), 드린펠트 중심(Drinfeld Center) 등 현대 위상 양자장론과 비역전 대칭성을 다루는 데 필수적인 대수적·범주론적 도구를 집대성한 표준 교과서입니다.
- **Sakura Schäfer-Nameki, _"ICTP Lectures on (Non-)Invertible Generalized Symmetries"_ (2023, arXiv:2305.18296)**
    - **특징:** 고차 형식 대칭성(Higher-form symmetries), 비역전 대칭성, 그리고 SymTFT(Symmetry Topological Field Theory) 프레임워크가 어떻게 기존에 알려지지 않은 보존량과 상전이를 분류해 내는지 정리한 최신 강의록입니다.
- **Shu-Heng Shao, _"What's Done Cannot Be Undone: TASI Lectures on Non-Invertible Symmetries"_ (2023, arXiv:2308.00747)**
    - **특징:** 추상적인 범주론적 대칭성이 실제 입자물리학(예: 파이온 붕괴 선택 규칙)과 격자 모형에서 어떻게 새로운 물리적 제약을 만들어내는지 구체적인 예시와 함께 설명합니다.

### 4. 코보디즘 가설 & 위상 양자장론(TQFT)의 완전 분류

시공간의 기하학을 위상적 다양체(Cobordism)의 범주로 환원하고, 그 위에 정의될 수 있는 모든 물리 이론을 공리적으로 분류하는 영역입니다.

- **Jacob Lurie, _"On the Classification of Topological Field Theories"_ (2009, arXiv:0905.0465)**
    - **특징:** 고차 범주론($(\infty, n)$-categories)을 사용하여, 모든 확장된 위상 양자장론이 '완전히 쌍대 가능한 대상(Fully dualizable objects)'들에 의해 일대일로 결정된다는 코보디즘 가설을 증명한 역사적 논문입니다. (매우 고난도이지만 현대 수리물리학의 정점 중 하나입니다.)
- **Daniel S. Freed, _"The Cobordism Hypothesis"_ (2012, Bull. Amer. Math. Soc. / arXiv:1210.5100)**
    - **특징:** 루리의 방대한 증명을 물리학자와 수학자가 핵심 직관 위주로 이해할 수 있도록 압축해 해설한 논문입니다.
### 추천하는 읽기 순서

1. 전체적인 큰 그림과 범주론적 언어를 익히려면 **Baez & Stay의 _Rosetta Stone_** 논문으로 가볍게 시작해 보시는 것을 권합니다.
2. 대수적 구조 자체에서 물리적 성질과 시간이 도출되는 과정이 궁금하시다면 **Witten의 2018년 리뷰 논문**과 **Connes & Rovelli의 논문**이 가장 직접적인 통찰을 줍니다.
3. 최신 이론물리학에서 새로운 보존량과 불변량을 찍어내는 공리적 기계를 보시려면 **Schäfer-Nameki의 강의록**을 통해 SymTFT와 드린펠트 중심 개념을 접해보시는 것이 좋습니다.