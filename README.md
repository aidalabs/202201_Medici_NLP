# 기반 AI를 활용한 빅데이터 분석가 양성 과정
- 주관기관: 과학기술정보통신부, 정보통신기획평가원
- 사업명: 2021 혁신성장 청년인재 집중양성 사업-빅데이터 분야
- 운영기관: 메디치이앤에스(주) / SK플래닛(주)
- 교육목적: 데이터를 기반으로 AI를 활용한 비즈니스 의사결정, 서비스 및 마케팅 전 략 수립 등이 가능한 데이터 분석 실무 역량을 갖춘 청년인재 양성
---
## **담당강의: 자연어 처리 분야(32H)**
---
## 1일차 (8H)
### 1. 자연어 처리 개요
- 자연어 처리 개요
- 언어학적 요소
- 자연어 처리가 어려운 이유
- 자연어 처리 기술 동향
### 2. 파이썬 기반 개발 기초
- [파이썬 기초](01_Python_Basics.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/01_Python_Basics.ipynb)
- [PyTorch 기초](02_PyTorch_Basic.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/02_PyTorch_Basic.ipynb)
---
## 2일차 (8H)
### 1. 전처리 (Preprocessing)
- 자연어 처리를 위한 전처리 과정
  - 코퍼스 (Corpus, 말뭉치), 정제 (Normalization, 정규화), 분절, 병렬 코퍼스 정렬, 서브워드 분절
- [전처리 실습](03_Preprocessing.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/03_Preprocessing.ipynb)
### 2. 토크나이징 (Tokenizing)
- 토크나이징 개요
- BPE (Byte Pair Encoding)
- 한국어 토크나이징
- [토크나이징 실습](04_Tokenizing.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/04_Tokenizing.ipynb)
### 3. 임베딩 (Embedding)
  - 단어의 의미와 유사성, 모호성
  - 문장 임베딩과  단어 임베딩
  - 시소러스 기반 기법: 워드넷(WordNet)
  - 통계기반 기법
  - 추론기반 기법: Word2Vec
    - CBOW (Continuous Bag-of-Words)
    - skip-gram
  - [임베딩 실습](05_Embedding.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/05_Embedding.ipynb)
---
## 3일차 (8H)
### 1. 텍스트 유사도 (Text Similarity)
- 텍스트 유사도 개요
- n-gram 유사도
- 코사인 유사도
- 기타 유사도 계산 방법(Manhattan Distance, Euclidean Distance, Infinity Norm, Jaccard Similarty)
- [텍스트 유사도 실습](06_Text_Similarity.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/06_Text_Similarity.ipynb)
### 2. RNN (Recurrent Neural Network) 모델
- RNN 모델 개요 및 기본 원리
- LSTM (Long Short-Term Memory) 모델
- GRU (General Recurrent Unit) 모델
- [RNN 모델 실습](07_RNN.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/07_RNN.ipynb)
### 3. Seq2Seq & Attention
- Seq2Seq, Attention 모델 개요
- [Seq2Seq & Attention 실습](08_Seq2Seq.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aidalabs/202201_Medici_NLP/blob/main/08_Seq2Seq.ipynb)
---
## 4일차 (8H)
### 1. 언어모델 (Language Model)
- 언어모델 개요
- 트랜스포머 아키텍처 (Transformer Architecture)
- GPT (Generative Pre-Training)
- BERT (Bidirectional Encoder Representation Transformers)
### 2. 챗봇 시스템
- 음성인식 시스템, 챗봇 시스템 개요
- 챗봇 서비스 기반 스마트 홈의 아키텍처 및 기술 구성, 학습용 데이터 개발 시 주의사항
- 챗봇 엔진
