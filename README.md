# toy_project-DecisionTree

# 1. 개발목적
DecisionTree를 공부한 후 이를 구현해보기 위해 개발하게 되었음. 

# 2. 모델설명
데이터셋은 케글의 100,000 UK Used Car Data set에서 hyundai.csv만 따로 가져와 사용하였음. 이 모델은 다양한 특성과 DecisionTreeRegressor을 이용하여 자동차 가격을 예측하는 모델임.

# 3. 개발일지
2021/07/25 결정트리모델을 사용해 학습을 진행해보니 역시 train_score는 매우 뛰어나게 나타나나, test_score는 많이 아쉬운 과대적합 현상을 발견하였음. 그래서 GridSearchCV를 사용하여 매개변수를 조정해주었고 보다 나은 결과를 얻었지만 과대적합이 약간 남아있었음. 이를 해결하기 위해서는 앙상블 학습의 알고리즘을 사용해봐야할 듯함. 확실히 결정트리는 표준화 전처리 과정도 필요없고 학습률도 다른 모델보다 비교적 뛰어나서 편하게 좋다는 것을 느꼈음.
