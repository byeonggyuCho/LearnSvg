# SVG 마스터

## emmet

html을 쉽게 작성하기 위한 도구

## SVG(scalable Vector Graphics)

- 확장 가능한 백터 그래픽
- xml기반의 2차원 그래픽
- 모양이 복잡하고 개체수가 많을 수록 성능이 떨어짐

### 사용법

1. img 태그
2. css background

### viewbox

- viewbox의 비율로 내부 요소의 크기가 상대적으로 결정된다.
- svg의 절대적 크기가 지정되지 않으면 반응형으로 움직이며 내부요소의 비율을 결정하는것이 viewbox이다.

### svgomg

- svg파일을 압축하는데 사용
- [SVGOMG](https://jakearchibald.github.io/svgomg/)

## Canvas

비트맵 기반 그래픽.

- 이미지나 비디오의 픽셀 조작, 게임등 퍼포먼스가 중요한 이미지 조작에 쓴다
- 자바스크립트를 이용해서 조작이 가능한다.
- 저수준 API로 코딩량이 많고 까다롭다.
