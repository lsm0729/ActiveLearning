# ActiveLearning

Not All Labels Are Equal: Rationalizing The Labeling Costs for Training Object Detection[https://arxiv.org/abs/2106.11921]

논문 기반하여 테스트. Acquisition 부분까지만 진행함

해당논문은 Object Detection 에서의 Active Learning 기법에 대해서 다룸.

현재 사용중인 모델은 Activation Function이 Sigmoid 이어서 약간의 수정을 했지만, 

기본적으로 해당 논문은 box 별로 클래스 확률분포를 보기때문에, softmax 기반이 되어야 한다.

논문자체는 Mobilenet SSD 기반으로 작성된듯 하다.



