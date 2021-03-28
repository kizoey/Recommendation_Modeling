## 파이썬을 이용한 개인화 추천 시스템
![캡처](https://user-images.githubusercontent.com/81248507/112752414-d8ba6180-900d-11eb-9340-6d8a4950a264.PNG)

### 1. 추천 시스템 소개
1.1 주요 추천 알고리즘<br>
1.2 추천 시스템 적용 사례

### 2. 기본적인 추천 시스템
2.1 데이터 읽기<br>
2.2 인기제품 방식<br>
2.3 추천 시스템의 정확도 측정<br>
2.4 사용자 집단별 추천

### 3. 협업 필터링 추천 시스템(CF)
3.1 협업 필터링의 원리<br>
3.2 유사도지표<br>
3.3 기본 CF 알고리즘<br>
3.4 이웃을 고려한 CF<br>
3.5 최적의 이웃 크기 결정<br>
3.6 사용자의 평가경향을 고려한 CF<br>
3.7 그 외의 CF 정확도 개선 방법<br>
3.8 사용자 기반 CF와 아이템 기반 CF<br>
3.9 추천 시스템의 성과측정지표

### 4. Matrix Factorization(MF) 기반 추천
4.1 Matrix Factorization(MF) 방식의 원리<br>
4.2 SGD(Stochastic Gradient Decent)을 사용한 MF 알고리즘<br>
4.3 SGD를 사용한 MF 기본 알고리즘<br>
4.4 train/test 분리 MF 알고리즘<br>
4.5 MF의 최적 파라미터 찾기<br>
4.6 MF와 SVD

### 5. Surprise 패키지 사용
5.1 Surprise 기본 활용 방법<br>
5.2 알고리즘 비교<br>
5.3 알고리즘 옵션 지정<br>
5.4 다양한 조건의 비교<br>
5.5 외부 데이터 사용

### 6. 딥러닝을 사용한 추천 시스템
6.1 Matrix Factorization(MF)을 신경망으로 변환하기<br>
6.2 Keras로 MF 구현하기<br>
6.3 딥러닝을 적용한 추천 시스템<br>
6.4 딥러닝 모델에 변수 추가하기

### 7. 하이브리드 추천 시스템
7.1 하이브리드 추천 시스템의 장점<br>
7.2 하이브리드 추천 시스템의 원리<br>
7.3 하이브리드 추천 시스템(CF와 MF의 결합)

### 8. 대규모 데이터의 처리를 위한 Sparse Matrix 사용
8.1 Sparse matrix의 개념과 Python에서의 사용<br>
8.2 Sparse matrix를 추천 알고리즘에 적용하기

### 9. 추천 시스템 구축에서의 이슈
9.1 신규 사용자와 아이템(Cold start problem)<br>
9.2 확장성(Scalability)<br>
9.3 추천의 활용(Presentation)<br>
9.4 이진수 데이터(Binary data)의 사용<br>
9.5 사용자의 간접 평가 데이터(Indirect evaluation data) 확보
