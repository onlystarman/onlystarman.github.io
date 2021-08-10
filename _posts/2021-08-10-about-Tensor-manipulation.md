---
layout: archive
title:  "Tensor Manipulation"

categories:
  - COMPUTER
tags:
  - computer
  - data
  - tensor
  - tensorflow
---
Tensorflow는 Tensor의 흐름을 우리가 쉽게 control 해줄 수 있게 하는 framework 이다. 

1. Tensor의 정보

Rank, Shape, Axis

Rank : 차원을 나타내며 괄호의 갯수가 Rank를 나타낸다. 

Shape : 각 차원마다 element의 개수를 표현한다. 

Axis : 각 차원(괄호)마다 indexing 한 숫자라고 이해 하면 좋다. axis=0 이 가장 바깥의 괄호 이고, axis=-1은 가장 안쪽의 괄호를 나타낸다.

![1](/assets/images/gun0810/1.png)
![2](/assets/images/gun0810/2.png)

***
***
2. Broadcasting

때로는 편하지만 때로는 조심해야 한다. 

matrix나 tensor의 multiplication을 할때는 shape을 확인하고 행렬곱을 해주는 것이 안전하다. 
* 를 사용한 일반 곱셈은 broadcasting 되어 elementwise 곱셈을 하기 때문에 잘못된 결과를 가져올 수 있다. 

![3](/assets/images/gun0810/3.png)

***
***

3. One_hot

multi classification problem 에서 사용한다.

![4](/assets/images/gun0810/4.png)


Gunhee Lee