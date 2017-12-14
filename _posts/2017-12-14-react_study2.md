---

layout: post

title: 2. JSX 란?

---

React에는 JSX (JavaScript XML)라는 리액트 코드를 사용한다.<br><br>
JSX란 자바스크립트 코드 내에서 쓰는 html,xml와 닮은 코드다.<br><br>
브라우저는 JSX를 인식하지 못하기때문에 <br>
바벨이라는 자바스크립트 컴파일러를 통해 인식가능한 자바스크립트로 변환한다.<br><br>
아래 예시처럼 JSX에서 html을 만들어내는 자바스크립트 코드인 React.createElement()을 통해 변환한다.<br><br>
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_01.PNG?raw=true)
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_02.PNG?raw=true)

즉, JSX > javascript > html이 되는것이다.

## JSX 장점<br>
1. JSX는 컴파일링 되면서 최적화되므로 빠르다.<br><br>
2. Type-sate 하며 컴파일링 과정에서 에러를 감지 할 수 있다.<br>
(※ Type-sate : 어떠한 연산도 정의되지 않은 결과를 내놓지 않는것, 즉 예측 불가능한 결과를 나타내지 않는다.)<br><br>
3. HTML과 비슷해 JSX를 사용하여 더 쉽고 빠르게 템플릿을 작성 할 수 있다. <br><br>

## JSX 특징<br>
1. 아래 예시처럼 자바스크립트 표현식을 중괄호로 묶어 JSX에 삽입 할 수 있다.<br><br>
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_03.PNG?raw=true)

2. JSX에서는 태그안에 style 속성에 css를 직접 지정할 수 없다. 인라인 스타일을 선언하려면 css값을 카멜표기법으로 작성해 javascript 객체에 전달해야 한다.<br><br>
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_04.PNG?raw=true)

3. class는 자바스크립트의 예약어라서 JSX에서는 className로 쓴다.

4. 주석은 자바스크립트의 경우와 동일하나 태그의 자식 위치에 자석을 넣을때, 중괄호로 감싸야 한다.

5. JSX에서는 조건문 if 대신 다음과 같은 삼항연산자를 사용한다. {조건 ? '참' : '거짓'}<br><br>
![이미지](https://github.com/tblynda/tblynda.github.io/blob/master/images/react2_05.PNG?raw=true)
