## Project : PMLP 101
### 파이썬을 활용한 실용적 머신러닝 기초 ( P.M.L.P 101 : Paractical Machine Learning Using Python 101)

--
1. 저자 : int29
2. 프로젝트 시작일 : 2023-02-26
3. 프로젝트 종료일 : 
4. 버전 : 0.9 (Prototype)

--


### 목차

#### 00.들어가며 <br>
- [왜 머신러닝 프로젝트를 혼자 하려면 막막할까?](https://github.com/int29/PMLP-101/blob/main/chapter_00_introduction/00_들어가며%20(Introduction).md) <br>

#### 챕터01 : 머신러닝 이해하기 <br>
- [01.머신러닝 이해하기 : 머신러닝은 도대체 무엇일까?](https://github.com/int29/PMLP-101/blob/main/chapter_01_Understanding_Machine_Learning/01.머신러닝%20이해하기.md) 

#### 챕터02 : 머신러닝 알고리즘 -분류(Classification) <br>
- [02.머신러닝 알고리즘 : 최근접이웃]() 
- [03.머신러닝 알고리즘 : 의사결정나무]() 
- [04.머신러닝 알고리즘 : 부스팅 트리 01 - 이론]() 
- [05.머신러닝 알고리즘 : 부스팅 트리 02 - 적용]() 
- [06.머신러닝 알고리즘 : 앙상블 트리 01]()
- [07.머신러닝 알고리즘 : 정규화 트리 및 최신 트리 알고리즘]() 

#### 챕터03 : 머신러닝 알고리즘 -회귀(Classification) <br>
- [08.머신러닝 알고리즘 : 분류모델 알고리즘의 회귀]() 
- [09.머신러닝 알고리즘 : 기초 회귀 알고리즘]() 
- [10.머신러닝 알고리즘 : 정규화 회귀 알고리즘]()

#### 챕터03 : 비지도 학습 알고리즘 -군집(Clustering) <br>
- [11.머신러닝 알고리즘 : Kmeans , DBSCAN]()

<br>

#### 01. 문서의 목적과 대상 독자 

이 책은 시중에 출판된 기초 서적을 살펴본 후 실제 캐글(Kaggle)과 같은 머신러닝 공모전, 혹은 실무에 적용하는데 어려움을 겪는 독자를 대상으로 머신러닝을 실용적으로 활용하기 위한 기본적인 전체 프로세스를 소개하고, 머신러닝의 기저에 있는 다양한 학문과의 징검다리 역할 하는데 목적이 있다.

#### 02. 이 문서를 통해 독자가 얻는 AS-IS / TO-BE

* AS-IS : 
	* 진행하길 원하는 머신러닝 프로젝트가 있지만, 실제 진행하려 하니 무엇부터 시작해야할지 막막하고, 앞으로 나아가기 위해 무엇을 공부해야 할지 모르겠다.

* TO-BE : 
	* 독자는 실제 진행하고자 하는 머신러닝 프로젝트에서 무엇을 어떻게 진행해야 할지 명확하게 프로세스를 설계할 수 있고 실제로 진행할 수 있게 된다.
	*   만약 어려움에 봉착할 경우 그 어려움을 해결할 수 있는 공부와 연구를 찾아 스스로 나아갈 수 있다.

### 03. 사전 지식
* 파이썬의 기초 자료형 및 반복문(Loop), 조건문(conditional statment), class, 사용자 정의함수(UDF) 등에 익숙
* Pandas, Numpy를 통해 데이터를 전처리할 수 있음. 혹은 stackoverflow나 구글링을 통해 다른사람의 코드를 읽고 적용할 수 있음

### 04. 이 책에서 다루지 않는 것들
* 파이썬의 기초 자료형 및 반복문(Loop), 조건문(conditional statment), class, 사용자 정의함수(UDF)
* pandas, numpy 라이브러리를 활용하는 방법 
*  머신러닝을 다루는 기초 학문에 대한 전체 내용 (예: 선형대수 전체, 통계학 전체) : 이 경우 꼭 필요한 부분에 대한 언급만 진행함.


### 05. 문서 작성 방법에 대하여
빠른 초안을 작성하기 위해 ChatGPT를 활용하여, 초안을 작성하고 이를 검수하고 다듬는 방법을 사용했음을 미리 알린다.
단, ChatGPT는 훈련 텍스트기반의 정보를 제공하기 때문에 100% 옳은 정보를 제공하지는 않는다. 따라서 정확한 정보를 제공해야 하는 정의 및 이론에 관한 부분은 공신력 있는 자료에서 인용하는 것을 작성 원칙으로 하였다. 인용 및 참고 자료는 각 문서 최하단에서 확인할 수 있다.

### 06. 오류 제보 및 토론

시중에 출판되는 책의 경우 검수 과정을 통해 책의 오류를 철저하게 잡고, 모호한 개념에 대해서는 구체화 하는 등 검증과정을 굉장히 철저하게 진행한다. 다만, 이 문서는 영리 목적이 아니다 보니, 급변하는 기술 흐름에 따라서 어제는 맞았지만, 오늘은 틀린 정보도 존재하고 저자의 부족으로 틀린 내용도 있을 수 있다. 

이 경우 자유롭게 제보 및 의견 개진이 가능하며, 문서의 오류일 경우 수정할 예정이다. 이 경우 참여 및 기여자에 등록되게 된다.

### 07. 참여 및 기여자

* Int 29