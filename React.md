# React

### 사용이유
- 앱만들기, 발행하기 쉬우며 UX적으로 뛰어나다. (PWA, Native...)
- 2020년 이후로 리액트 문법이 class 없이 쉬워졌다.
- 유저들에게 긍정적인 요인을 제공 (속도 등등)
- 데이터 바인딩(데이터를 HTML에 꽂아넣는 느낌)이 쉽다 ... ex) {변수명, 함수 등} --> 거의 모든곳에 다된다.. 신격화!


### 설치방법 및 미리보기
1. node.js 설치 -> create React App Library를 사용하기 위해 설치 npx, npm 등을 사용하기 위함
2. Visual Studio Code 이용, 터미널에 > npx create-react-app 파일이름 < 작성 후 엔터~
3. File -> Open Folder -> 내가만든 폴더선택 후 오픈


> #### 미리보기
  > - 터미널에 해당 파일 위치가 맞는지 확인 후 npm start 입력

### App.js
 - 이곳에 작성을 시작하면 된다.
 - index.js에서 index.html에 저장하도록 틀이 짜여져있음
 
         - index.js
          const root = ReactDOM.createRoot(document.getElementById('root'));
          root.render(
          <React.StrictMode>
          <App />
          </React.StrictMode>);


### JSX
 - JS + XML, 즉 JS를 확장한 문법이다. React와 함께쓰인다.
 - HTML 문법의 대응으로 생각하며 react는 js 문법이므로 html에서 사용했던 <div <strong>class</strong>=''></div>
 - 를 <div <strong>className</strong>=''></div> 로 사용한다.

.<br>
.<br>
.<br> 지속 
