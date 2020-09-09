# 1. [퍼셉트론](https://en.wikipedia.org/wiki/Perceptron) 알고리즘
## 1-1. 알고리즘$^{algorihtm}$ 

우리가 구하고자 하는 것은 입력값 $ x $들을 분류해 낼 수 있는 가중치 $w$인데, [로젠블라트](https://en.wikipedia.org/wiki/Frank_Rosenblatt)가 처음 제안한 학습 알고리즘은 다음과 같이 요약할 수 있습니다.

1. 가중치를 0 혹은 무작위 작은 수로 초기화 한다.
1. 각 학습 자료$^{Training Sample}$ $x^{(i)}$에 대해 다음을 실행한다. 

 * 출력 $\hat{y}$를 계산한다. 즉 $\hat{y}=h\mathbf{(w^Tx)}$  
 * 가중치 $w_j$를 조정한다. 즉 $w_j:=w_j+\Delta w_j  $

<img src="https://raw.githubusercontent.com/idebtor/KMOOC-ML/master/ipynb/images/person.png" width="110">
<center>그림 4: 마크 다운 문서 작성하기</center>

 







```python

```
