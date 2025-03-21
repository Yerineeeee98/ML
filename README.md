- 가상환경 생성
 - python -m venv -vevn
- 가상환경 활성화
    -source venv/Scripts/activate
- 라이브러리 설치
    - pip install pandas jupyterlab
- .gitignore 작성
    - .gitignore 파일 만들고 사이트에서 코드 복사 붙여넣기

> # 1-3
   > - 마켓과 머신러닝
   > -
---
> # 2 : 데이터 다루기
    > - 2-1 : 훈련세트와 테스트 세트
    > - 2-2 : 데이터 전처리

---
> # 3 : 회귀 알고리즘과 모델 규제
    > - 3-1 : k-최근접 이웃 회귀 알고리즘, 과대적합과 과소적합
    > - 3-2 : 선형 회귀, 다항 회귀
    > - 3-3 : 
         > 다중 회귀, 특성 변환기(polynomialfeatures) 
         > 규제(과대적합되지 않도록 만드는 것) - ridge 모델, lasso 모델
    
---
> # 4 : 다양한 분류 알고리즘 
    > - 4-1 : 로지스틱 회귀 
          (이진 분류 - 시그모이드 함수 사용, 다중 분류 - 소프트맥스 함수 사용)     
    > - 4-2 : 
         > 확률적 경사 하강법(미니 배치 경사 하강법, 배치 경사 하강법)
         > 손실 함수(로지스틱 손실 함수, 크로스엔트로피 손실 함수)
---
> # 5 : 트리 알고리즘
    > - 5-1 : 결정트리로 와인 분류하기
    > - 5-2 : 검증 세트, 교차 검증, 그리드 서치
    > - 5-3 : 앙상블 학습
            - 랜덤 포레스트
            - 엑스트라 트리 
            - 그레이디언트 부스팅
            - 히스토그램 기반 그레이디언트 부스팅

> # 6 : 군집 알고리즘
  > - 군집 : 비슷한 샘플끼리 그룹으로 모으는 작업으로       대표적인 비지도 학습
>   -  클러스터 : 군집 알고리즘에서 만든 그룹
    > - 6-1 : 비지도 학습으로 과일 사진(비슷한 샘플) 분류하기
             - 2차원 이미지를 벡터로 변경
             -  subplots(), np.argsort()
             