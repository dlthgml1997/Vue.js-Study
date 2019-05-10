 <h1>'SOPT 23th Genius'들의 vue.js 스터디</h1>

### hw1<br>
css 적용해보기<br>
### week1<br>
자바스크립트와 css 복습<br>
### week2<br>
css 생성자/ 게임 및 공부 정리 (참고: https://flukeout.github.io/)<br>
### week3<br>
   * 선언적 렌더링
   * 조건문과 반복문
   * 사용자 입력 핸들링
   * 컴포넌트를 사용한 작성방법
        사용자 정의 엘리먼트와의 관계
### week4<br>
   * Vue Instance
   * 속성과 메소드
   * 인스턴스 라이프사이클 훅
   * 라이프사이클 다이어그램 (아래 사진 참고: [출처] [구글 이미지](https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiTj629uLXhAhXUA4gKHbppDhEQjRx6BAgBEAU&url=%2Furl%3Fsa%3Di%26source%3Dimages%26cd%3D%26cad%3Drja%26uact%3D8%26ved%3D2ahUKEwiTj629uLXhAhXUA4gKHbppDhEQjRx6BAgBEAU%26url%3Dhttps%253A%252F%252Fwww.pinterest.com%252Fpin%252F317855686189562134%252F%26psig%3DAOvVaw2wa2H0aYn45GrCJpkm9Q3f%26ust%3D1554433037078830&psig=AOvVaw2wa2H0aYn45GrCJpkm9Q3f&ust=1554433037078830)) 
![image](https://user-images.githubusercontent.com/18275619/55526658-d815bb80-56d0-11e9-8bfd-ddbc76ecff65.png)

### week5<br>
   * local Component / global Component
   * 컴포넌트 간의 통신 (이미지 출처: [구글 이미지](https://cdn-images-1.medium.com/max/790/0*Xzkw0-T4Uea3d5Yh.png))
   ![image](https://user-images.githubusercontent.com/18275619/55624975-6cbc0e80-57e2-11e9-845a-b437f686421d.png)
   
### week6<br>
   * EventBus<br>
      : 같은 컴포넌트 레벨 간의 통신<br>
      : 보내는 컴포넌트에서는 $emit(), 받는 컴포넌트에서는 $on()을 구현합니다.<br>
   * Vue Router

### week7<br>
   * Axios<br>
     : 액시오스는 Promise 기반의 API형식(데이터를 요청하고 받아 올 때 까지 기다렸다가 화면에 나타내는 로직을 실행해야 할 때 주로 활용됨)으로 되어있다.
   * Axios vs Vue Resource<br>
     : 액시오스의 경우 data 속성이 일반 문자열 형식이 아니라 객체 형태이기 때문에 별도로 JSON.parse()를 사용하여 객체로 변환할 필요가 없습니다.
   
