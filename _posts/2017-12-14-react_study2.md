---

layout: post

title: 2. JSX 란?

---

React에는 JSX (JavaScript XML)라는 리액트 코드를 사용한다.<br><br>
JSX란 자바스크립트 코드 내에서 쓰는 html,xml와 닮은 코드다.<br><br>
브라우저는 JSX를 인식하지 못하기때문에 <br>
바벨이라는 자바스크립트 컴파일러를 통해 인식가능한 자바스크립트로 변환한다.<br><br>
아래 예시처럼 html을 만들어내는 자바스크립트 코드인 React.createElement()을 통해 변환한다.<br><br>
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_01.PNG?raw=true)

즉 JSX > javascript > html이 되는것이다.


## 특징<br>
>아래 예시처럼 자바스크립트 표현식을 중괄호로 묶어 JSX에 삽입 할 수 있다.<br><br>
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_02.PNG?raw=true)

