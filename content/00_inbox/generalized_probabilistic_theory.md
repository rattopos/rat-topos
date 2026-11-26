---
date: 2026-11-21 21:06:40
lastmod: 2026-11-22 13:25:18
title: Generalized probablistic theory
aliases:
  - GPT
tags:
  - gemini
  - quantum
  - references
up:
stage:
draft: true
---
일반 확률 이론(Generalized Probabilistic Theories, GPT)은 비교적 최근 양자정보이론과 양자 기초론(Quantum Foundations)을 중심으로 폭발적으로 성장한 분야라 단독 입문 교과서보다는 **핵심 리뷰 논문(Review Papers)**, **기념비적인 원전 논문(Seminal Papers)**, 그리고 **관련 단행본**을 순서대로 따라가는 것이 가장 체계적이고 깊이 있게 배우는 방법입니다.

수학적 엄밀함과 학습 단계에 맞춰 추천 문헌을 정리해 드립니다.

### 1. 가장 추천하는 입문 및 종합 리뷰 논문 (Review Papers)

GPT의 전체적인 그림과 수학적 도구를 처음부터 끝까지 독학하기에 가장 좋은 자료들입니다.

- **Martin Plávala, _"General probabilistic theories: An introduction"_** (Physics Reports, 2023 / arXiv:2103.07469)
    
    - **특징:** 현재 GPT 분야의 **가장 표준적이고 완결성 높은 입문 리뷰 논문**입니다.
    - **내용:** 볼록 기하학(Convex Geometry)을 기반으로 상태 공간, 효과 대수(Effect algebra), 텐서곱(합성계), 측정, 채널, 그리고 양자역학의 재구성(Jordan algebras와의 연결)까지 자족적(Self-contained)으로 엄밀하게 다룹니다. 다이어그램 표기법도 함께 소개하여 직관과 엄밀함을 동시에 잡을 수 있습니다.
        
- **Peter Janotta & Haye Hinrichsen, _"Generalized Probability Theories: What determines the structure of quantum theory?"_** (J. Phys. A, 2014 / arXiv:1402.6562)
    
    - **특징:** 수학적 디테일에 매몰되기 전에 **물리적 직관과 모델 빌딩(Model building) 관점**을 잡기에 최적화된 리뷰입니다.
    - **내용:** 실험 데이터 테이블로부터 어떻게 상태 공간과 효과 공간을 구성하는지 단계별로 설명하며, 정사각형 상태 공간(Boxworld)이나 다각형 모델 같은 구체적인 예시들을 통해 비국소성과 얽힘을 직관적으로 보여줍니다.
        
- **Zujin Wen et al., _"Generalised Probabilistic Theories"_** (arXiv:2606.31097, 2026)
    
    - **특징:** 최근에 발표된 입문서로, 블로흐 구(Bloch sphere) 확장에서 시작해 이산/연속 위상 공간에서의 일반화된 해밀턴 역학, 문맥성(Contextuality) 등 최신 연구 흐름까지 폭넓게 연결합니다.

### 2. 현대 GPT 프레임워크를 정립한 원전 논문 (Seminal Papers)

현대적인 형태의 GPT 언어가 어떻게 탄생했는지 이해하려면 아래 세 논문은 필수적으로 읽힙니다.

  

- **Lucien Hardy, _"Quantum Theory From Five Reasonable Axioms"_** (arXiv:quant-ph/0101012, 2001)
    
    - 현대 GPT 연구의 시발점이 된 기념비적인 논문입니다. "준비-변환-측정"이라는 조작적 틀을 세우고, 5개의 단순한 공리로부터 양자역학이 유도됨을 보였습니다.
        
- **Jonathan Barrett, _"Information processing in generalized probabilistic theories"_** (Physical Review A 75, 032304, 2007 / arXiv:quant-ph/0508211)
    
    - Hardy의 프레임워크를 확장하여 **양자정보이론의 핵심 프로토콜(복제 불가능성, 텔레포테이션, 암호화, 비국소성 등)을 일반 GPT 위에서 체계화**한 논문입니다. 오늘날 쓰이는 기호와 개념 대부분이 이 논문에서 정립되었습니다.
        
- **G. Chiribella, G. M. D'Ariano, & P. Perinotti, _"Probabilistic theories with purification"_** (Physical Review A 81, 062348, 2010) 및 **_"Informational derivation of quantum theory"_** (PRA 84, 012311, 2011)
    
    - 정화 원리(Purification Principle)라는 정보이론적 공리를 핵심으로 삼아, 회로(Circuit) 다이어그램 프레임워크 위에서 양자역학을 완벽하게 재구성한 기념비적 연구입니다.
        

### 3. 단행본 및 심화 교재 (Books & Lecture Notes)

논문 외에 책 형태로 깊이 있는 수학적 기초(작용소 대수, 순서 벡터 공간, 범주론적 접근)를 다지고 싶다면 다음 교재들을 추천합니다.

1. **Giacomo Mauro D'Ariano, Giulio Chiribella, & Paolo Perinotti, _Quantum Theory from First Principles: An Informational Approach_** (Cambridge University Press, 2017)
    
    - GPT 및 조작적 확률 이론(Operational Probabilistic Theories, OPT)을 다룬 **가장 대표적인 단행본**입니다. 정보이론적 공리로부터 양자역학을 도출하는 전 과정을 교과서 수준으로 매우 상세하게 서술합니다.
        
2. **Bob Coecke & Aleks Kissinger, _Picturing Quantum Processes: A First Course in Quantum Theory and Diagrammatic Reasoning_** (Cambridge University Press, 2017)
    
    - 범주론(Category Theory)과 다이어그램 추론(String diagrams)을 통해 일반화된 프로세스 이론(Process Theories)을 다룹니다. GPT의 합성계와 얽힘 구조를 위상수학적·대수적으로 이해하는 데 큰 도움을 줍니다.
        
3. **Alexander Wilce & Howard Barnum 관련 논문/챕터 (예: _Foundations of Quantum Mechanics_ 내 수록 챕터들)**
    
    - 순서 벡터 공간(Ordered Vector Spaces), 효과 대수(Effect Algebras), 유클리드 요르단 대수(Euclidean Jordan Algebras) 등 **함수해석학 및 추상대수학 관점**에서 GPT를 가장 엄밀하게 다루는 학파의 저작들입니다.
        

### 추천 학습 로드맵

1. **감 잡기:** `Janotta & Hinrichsen (2014)`의 앞부분을 읽으며 실험 확률표가 어떻게 볼록 집합(상태 공간)이 되는지 기하학적 직관을 익힙니다.
    
2. **수학적 골격 세우기:** `Martin Plávala (2023)` 리뷰 논문을 정독하며 볼록 기하학, 쌍대 원뿔(Dual cone), 최소/최대 텐서곱의 엄밀한 정의를 익힙니다.
    
3. **정보이론적 확장:** `Barrett (2007)` 논문으로 넘어가 비국소성(PR Box)과 정보 처리 한계를 확인한 뒤, 관심이 가는 방향에 따라 `D'Ariano et al. (2017)` 교재나 요르단 대수 관련 문헌으로 확장하시는 것을 권장합니다.