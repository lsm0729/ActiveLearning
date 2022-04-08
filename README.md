# ActiveLearning

Not All Labels Are Equal: Rationalizing The Labeling Costs for Training Object Detection[https://arxiv.org/abs/2106.11921]

시리즈 논문으로 해당편이 최종 결론을 담고 있어서 해당 논문만 주로 살펴봄. 

해당논문은 Object Detection 에서의 Active Learning 기법에 대해서 다룸.

핵심은 영상의 변화에 robust 한 model을 만드는 것이다.

예를 들어 원본영상과 vertical flip 한 영상이 있는데, 원본 영상에서만 detect가 잘되고 vertical flip한 영상에서는 detect 가 잘되지 않으면,

robust 한 모델이 아니라는 것이다.

논문에서는 horizontal flip 한 영상에 대해서만 진행을 하였고, 현업에서 논문 검토를 할떄는 verical flip 과 both flip모두를 검토 해보았는데, 

horizontal flip을 적용할 때 성능이 제일 잘 나왔다.

