## DNN,ANN,CNN등을 어디에 써먹는가?

딥러닝과 뇌과학의 조합, 말로만 들으면 머리가 지끈지끈하죠. 이게 뭔소린지도 모르겠고, 필자도 실제로 연구원 생활 두달째인데 아직까지 1%도 제대로 이해하지 못한 것 같아요.😫

지금 하고 있는 연구를 간략하게 설명드리면서 위 두개의 분야로 어떤 일을 할 수 있는지 말해보도록 할게요.

지금 제가 하고 있는 연구는 대외비라 자세히는 말씀 못드리지만 사람뇌를 fMRI 영상 기법으로 찍은 다음에, 위 영상에서 여러가지 feature를 추출한 다음, feature들로 GLM(간단한 선형회귀 모델)을 학습시켜서 병을 진단하는것이 목표예요.

위에 줄도 한줄로만 적으면 무슨 소린지 이해가 안 가실 분들이 분명 있을 거라 생각합니다. 예를 들어서 말씀드릴게요.

어떤 질병을 가진 사람의 뇌에는 후두엽이 많이 손상되어 있다고 하고, 정상인은 손상이 없다는 결과가 나왔어요. 이런 결과가 자주 나온다면 우리는 아, 후두엽이 손상된 사람은 질병이 있겠구나, 라고 생각할 수 있죠?

여기서 후두엽이 손상된 것을 바로 feature라고 하고, 이런 결과가 반복되는 것을 우리가 보는 것(아는 것)을 training이라고 해요.

제가 하는 일은 단순히 이 일을 컴퓨터보고 대신하라고 하는거죠. 이걸 바로 예측 모델링이라고 한답니다!!!

여러가지 인공지능 모델들을 알고, 모델에 데이터를 잘 집어넣고, 매개변수들을 잘 조정하면 여태까지 우리가 알지못했던 feature들로 질병을 좀 더 빨리 진단할 수도 있어요. 그래서 위 레파지토리에서는 여러 인공지능 모델들에 대해서 공부해보려고 해요.(저 수학 3등급이었는데...잘 할수 있겠죠?😂)



