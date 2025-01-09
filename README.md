# **KNU_DART 금융 데이터 분석 활동**

이 저장소는 **KNU_DART 금융 데이터 분석(퀀트) 동아리**에서 진행한 활동을 기록하고 정리한 것입니다.  
활동은 전략적 포트폴리오 구성, 데이터 스크리닝, 백테스트 수행, 그리고 퀀트 투자 전략 분석 등으로 구성되었습니다.

---

## 📘 **프로젝트 주요 내용**

### 1️⃣ **전략적 포트폴리오 구성**
- **목적**: 데이터 기반으로 투자 전략을 세우고, 최적의 포트폴리오를 구성.  
- **핵심 활동**:  
  - 종목 스크리닝
  - 포트폴리오 생성 및 리밸런싱
  - 리스크 관리 및 투자 성과 분석

- **관련 파일**:  
  - [전략포트폴리오.ipynb](https://colab.research.google.com/github/i-am-U-hyUn/knu-dart/blob/main/%EC%A0%84%EB%9E%B5%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.ipynb)  
  - [전략포트폴리오 간단 버전.ipynb](https://colab.research.google.com/github/i-am-U-hyUn/knu-dart/blob/main/%EC%A0%84%EB%9E%B5%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4%EA%B0%84%EB%8B%A8%EB%B2%84%EC%A0%BC.ipynb)  
  - [종목 스크리닝 포함 전략포트폴리오.ipynb](https://colab.research.google.com/github/i-am-U-hyUn/knu-dart/blob/main/%EC%A0%84%EB%9E%B5%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4%EA%B0%84%EB%8B%A8%EB%B2%84%EC%A0%BC%EC%A2%85%EB%AA%A9%EC%8A%A4%ED%81%AC%EB%A6%AC%EB%8B%9D%EA%B9%8C%EC%A7%80.ipynb)

---

### 2️⃣ **로우볼 전략 (Low Volatility Screening)**
- **목적**: 변동성이 낮은 주식 종목을 선별하여 안정적인 수익률을 추구.  
- **활동 내용**:  
  - 로우볼 전략에 따라 종목 스크리닝  
  - 선별된 종목의 과거 데이터 분석 및 성과 비교  

- **관련 파일**:  
  - [로우볼_스크리닝.ipynb](https://colab.research.google.com/github/i-am-U-hyUn/knu-dart/blob/main/%EB%A1%9C%EC%9A%B0%EB%B3%BC_%EC%8A%A4%ED%81%AC%EB%A6%AC%EB%8B%9D.ipynb)

---

### 3️⃣ **백테스트 (Backtesting)**
- **목적**: 투자 전략의 과거 성과를 검증하여, 실제 투자 적용 가능성을 평가.  
- **핵심 활동**:  
  - 과거 데이터 기반으로 포트폴리오 성과 시뮬레이션  
  - 투자 성과 지표 계산 (CAGR, Sharpe Ratio 등)  

- **관련 파일**:  
  - [백테스트.ipynb](https://colab.research.google.com/github/i-am-U-hyUn/knu-dart/blob/main/%EB%B0%B1%ED%85%8C%EC%8A%A4%ED%8A%B8.ipynb)

---

### 4️⃣ **Bootcamp 학습 프로젝트**
- **목적**: 금융 데이터 분석과 관련된 기본기를 다지는 학습 프로젝트.  
- **활동 내용**:  
  - Python을 활용한 데이터 처리와 시각화  
  - Pandas, NumPy 등 기본 라이브러리 실습  

- **관련 파일**:  
  - [Bootcamp3.ipynb](https://colab.research.google.com/github/i-am-U-hyUn/knu-dart/blob/main/Bootcamp3.ipynb)

---

## 🛠️ **구현 환경 및 기술 스택**

- **개발 환경**: Google Colab  
- **사용 기술 및 라이브러리**:  
  - Python (3.x)  
  - Pandas, NumPy  
  - Matplotlib, Seaborn  
  - yfinance, Scikit-learn  

---

## 📄 **금융 용어 설명**

- **Low Volatility (로우볼)**: 변동성이 낮은 주식을 선별하는 전략으로, 위험 대비 높은 수익률을 목표로 함.  
- **Backtesting (백테스트)**: 과거 데이터를 활용해 투자 전략의 유효성을 검증하는 과정.  
- **Sharpe Ratio (샤프 비율)**: 투자 성과를 위험 대비 평가하는 지표로, 수익률과 표준편차를 이용하여 계산.  
- **CAGR (연평균 성장률)**: 투자 자산의 연평균 수익률을 나타내는 지표.  

---

## 📂 **폴더 구조**

```plaintext
.
├── 전략포트폴리오.ipynb               # 포트폴리오 구성 전체 버전
├── 전략포트폴리오간단버젼.ipynb        # 간단한 포트폴리오 구성
├── 전략포트폴리오간단버젼_스크리닝.ipynb # 종목 스크리닝 포함 포트폴리오
├── 로우볼_스크리닝.ipynb               # 로우볼 전략 스크리닝
├── 백테스트.ipynb                      # 백테스트 시뮬레이션
└── Bootcamp3.ipynb                     # Bootcamp 학습 프로젝트
```
