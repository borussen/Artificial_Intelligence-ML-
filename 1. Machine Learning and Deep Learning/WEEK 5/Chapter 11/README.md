---------------------------------------------------------------------------------

## 실습자료 11장 개요

> Dropout을 포함한 Deep Neural Networks (11장_DNNforMNIST(+dropout).ipynb) <br>

---------------------------------------------------------------------------------



### Dropout을 포함한 Deep Neural Networks


심층신경망 모델을 python 패키지 'keras'를 통해 구현한다. <br>

코드는 다음과 같이 진행된다. <br>

1. mnist 데이터의 로드
2. 데이터 전처리
3. 모델 생성(선언)
4. 모델 학습
5. 결과 확인
6. dropout 추가 후 결과확인 <br>

해당 코드의 model.fit() 함수의 parameter인 batch_size와 epochs를 조절하여 학습을 조절하고 결과를 토대로 적절한 매개변수를 찾을 수 있다. <br>

6.의 dropout 추가 후 성능이나 적절한 매개변수의 차이를 통해 dropout의 효과를 확인할 수 있다. <br>
