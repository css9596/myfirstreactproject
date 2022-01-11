#React 공부


## React?
    1. react는 웹 프레임워크로, 자바스크립트 라이브러리의 하나로서
       사용자 인터페이스를 만들기 위해 사용한다.
    2. 싱글 페이지 애플리케이션, 모바일 애플리게이션 개발하는데 사용된다.
    3. Facebook이 개발하여 제공하는 프론트엔드 라이브러리이다.
    4. react로 사용자와 상호작용할 수 있는 동적인 UI를 쉽게 만들 수 있다.
##  React 특징
    1. Data Flow
        React는 데이터의 흐름이 한 방향으로만 흐르는 단방향 데이터 흐름을 가지고 있다.
    2. Component 기반 구조
        Component는 독립적인 단위의 소프트웨어 모듈을 말한다.
        React는 UI(view)를 여러 Component를 쪼개서 만들어지기에 전체 적으로 코드를 파악하기가 상대적으로 쉽다.
        이로 인해 재사용하기가 쉽고 유지보수, 관리가 용이하다는 장점이 있다.
    3. Virtual DOM
        이벤트가 발생 할 때마다 Virtual DOM을 만들고, 다시 그릴ㄷ 때마다 실제 DOM과 비교하고 전후 상태를 비교해, 변경이 필요한 최소한의 변경사항만
        실제 DOM에 반영해, 앱의 효율성과 속도를 개선할 수 있다.
    4. Props and State
        Props?
        부모 컴포넌트에서 자식 컴포넌트로 전달해 주는 데이터
        State?
        컴포넌트 내부에서 선언하며 내부에서 값을 변경 할 수 있다.
        동적인 데이터를 다룰 떄 사용하며, 상호작용을 통해 동적으로 변경할 떄 사용.
        클래스형 컴포넌트에서만 사용할 수 있고, 각각의 state는 독립적이다.
    5. JSX
        Javascript를 확장한 문법.
        React는 이벤트가 처리되는 방식, 시간에 따라 state가 변하는 방식
        화면에 표시하기 위해 데이터가 준비되는 방식 등 렌더링 로직이 본질적으로 다른
        UI를 로직과 연결된다는 사실을 받아들인다.
        Javascript 코드 안에서 UI 관련 작업을 할 때 시각적으로 더 도움이 되고, 에러 및 경고 메시지를 표시할 수 있게 해줘
        많이 사용한다.
## create-react-app
`npx create-react-app my-app`

    ReactJS Application을 만들 때 사전 설정 및 다양한 Javascript들이 존재하여 도움이 된다.
    예를 들어 개발 서버에 접근, 자동 새로고침 등 다양한 기능이 있다.
사용하기에 앞서 nodejs가 설치되어 있어야한다.
https://nodejs.org/

`node -v`
`npx`

node 설치 후 위 두개의 명령어를 터미널에서 실행 했을 때 정상적으로 동작하면 준비가 된 것이다.