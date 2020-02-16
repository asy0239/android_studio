# Layout

## 1. Linear Layout

- 좌에서 우, 위에서 아래 방향으로 뷰를 배치하는 레이아웃
- orientation : 뷰가 배치될 방향
- weight : Linear Layout 에 배치된 뷰의 속성으로 배치 후 남은 공간을 할당 받을 비율을 설정한다.

## 2. Relative Layout

- Relative Layout 안에 들어있는 뷰들 간의 관계를 설정하여 배치하는 레이아웃이다.
- Relative Layout 은 별다른 속성이 없고 여기에 배치된 뷰들에게 속성이 추가된다.
- Relative Layout 은 부모와의 관계, 다른 뷰와의 관계를 통해 배치하는 레이아웃.

### 부모와의 관계

- alignParentTop : 뷰의 상단을 부모의 상단에 맞춘다.
- alignParentBottom : 뷰의 하단을 부모의 하단에 맞춘다.
- alignParentLeft : 뷰의 좌측을 부모의 좌측에 맞춘다.
- alignParentRight : 뷰의 우측을 부모의 우측에 맞춘다.
- centerHorizontal : 뷰의 가로 중앙을 부모의 가로 중앙에 맞춘다.
- centerVertical : 뷰의 세로 중앙을 부모의 세로 중앙에 맞춘다.
- centerInParent : 뷰의 중앙을 부모의 중앙에 맞춘다.

### 다른 뷰 와의 관계

- align_top : 뷰의 상단을 지정된 뷰의 상단에 맞춘다.
- align_bottom : 뷰의 하단을 지정된 뷰의 하단에 맞춘다.
- align_left : 뷰의 좌측을 지정된 뷰의 좌측에 맞춘다.
- align_right : 뷰의 우측을 지정된 뷰의 우측에 맞춘다.
- below : 지정된 뷰 하단에 위치한다.
- above : 지정된 뷰 상단에 위치한다.
- toRightOf : 지정된 뷰 우측에 위치한다.
- toLeftOf : 지정된 뷰 좌측에 위치한다.
- baseline : 지정된 뷰의 베이스라인에 맞춘다.



