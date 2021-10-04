# Css

position: absolute -> 따로때서 개별로 자유롭게 움직이게 설정할수있다

position : relative->
예를 들어 노란박스 4개가있고
.box_container {
border: 1px solid;
}
.absolute_box {
width: 100px;
height: 100px;
background-color: indianred;
background-color: yellow;
left: 20px;
top: 20px;
}
이런상태일때 박스 콘테이너 안에서 이동을 시킬때 사용
부모의 박스 기준으로 이동시킬수있음

position : fixed ->
스크롤을 내려도 네비게이션이 고정되있는걸 볼수있는데 이것이 fixed
