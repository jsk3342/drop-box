# drop-box

상기 프로젝트는 하단의 링크를 통해 확인 가능합니다.

https://jsk3342.github.io/drop-box/

![drop-box](https://user-images.githubusercontent.com/85912592/163736854-264e2410-1a2c-468e-a22d-d829fa96dbe8.gif)


## 목표

제한적인 select 옵션에서 벗어나 button 요소를 활용하여 드랍박스를 구현

## 어려운 점

### 1. 버튼 포커스 시 달라지는 border

hover 됬을 때와 focus 됬을때 달라지는 외각을 구현하기 위해 가상요소에 z-index를 활용하여 구현하러 하였지만 자식 레벨의 인덱스 값은 부모 요소를 넘지 못하기 때문에 외각 라인을 따로 구현하여 포커스의 가상 요소로 만들었습니다.
