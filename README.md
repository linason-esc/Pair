# Pair
9주차 모달창 par programming

## Rule
- 폰트사이즈는 rem (기본으로 global.css안에 html,body에 font-size : 62.5%; 지정)
- 명명규칙은 카멜케이스
- style은 태그안에 내부에 넣기
- (공용)App.js는 자기 구조에 맞게 변경해서 사용
## 개인 파일 설명

### 변지인

<img width="155" alt="image" src="https://github.com/sprint-part2-team14/Pair/assets/129635857/1eeb9973-4bf5-4a74-b41d-f63e06ded9a8">


**제출한 파일** :

- Modal.js, Modal.css, Kakao.svg, Facebook.svg, link.svg, _close.png

**구조** : 

- Modal.js 위치 : [src폴더] index.js -> [src폴더] App.js -> [components폴더] Modal.js

- Modal.css 위치 : [src폴더] 안의 [components폴더]안의 [css폴더] Modal.css

- 이미지들 위치 : [publlic폴더] 안의 [img폴더] -> Kakao.svg, Facebook.svg, link.svg, _close.png

**특이사항** : 
1. 링크 복사의 경우 개인 파일에 맞춰야할 것 같습니다(setCurrentFolderId)
2. 공통으로 css가 들어가는 부분이 생겨서 어쩔 수 없이 class를 사용하기 위해 Modal.css를 만들었습니다. 내부로 처리할 수 있다면 알려주세욥..