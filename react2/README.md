# 김윤성 202030304

## 11.20 강의 내용

### Props 흐름의 이해 
Next.js의 데이터 흐름은 단방향으로 이루어져야한다. <br>
parents에서 child componet의 방향으로 props의 흐름이 이루어진다. <br>
계층 구조가 복잡해 지면 Props Drilling 문제 발생. <br>
Props Drilling은 여러 개의 component를 지나 props가 전달 되면서 발생하는 문제 

### Context API
Context는 UX구축에 많이 사용되는 React의 기능.<br>
React는 16.3 버전부터 정식적으로 context api를 지원 <br> 
일반적으로 props는 부모에서 자식으로 전달되는 단발형 통신을 한다. <br>
Context API는 특정 component가 props를 사용하지 않고, 하위 component를 포함한 모든 component에 데이터를 공유할 수 있는 기능을 제공. <br>
전역으로 데이터를 사용할 수 있게 해준다. <br>


## 11.13 강의 내용

#### Chakra UI
Chakra UI는 React 애플리케이션을 빌드하는데 필요한 블록을 제공하는 간단하고, 모듈적이며, 접근 가능한 컴포넌트 라이브러리. <br>
접근성 표준 WAI-ARIA standards를 엄격하게 따른 개발 <br>
다크 모드 호환성이 좋으며, 다양한 컴포넌트와 prop-based로 이루어져 있다. <br>

### Tailwind CSS

## 10.30 강의 내용

### Next 데이터 불러오기

서버가 데이터 불러오기에는 두 가지 방법이 있다. <br>
1. http 요청 만들고 처리. nods 내장 http 라이브러리 사용할 수 있음 http 클라이언트 라이브버리 사용 가능. 대표적인 것 Axios
서버에서 rest api 사용하기

Json Server

명령으로 json server 설치후에 version 확인

## 09.11 강의 내용

# 서버 사이드 랜더링 
웹 페이지를 제공하는 가장 흔한 방법 중 하나

# 클라이언트 사이드 랜더링 

동적 컴포넌트 로딩 dynamic

정적 사이트 생성(SSG: Static Site Generation)
1. 쉬운 확장 뛰어난 성능 더 안전한 api 요청