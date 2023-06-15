## ✍️ **관련 개념 정리**

## Hooks란?

함수 컴포넌트에서 React state과 생명주기 기능을 “연동(**_hook_** into)”할 수 있게 해주는 함수

기존 Class 기반의 코드가 아니어도 상태값 등을 사용해 **함수형 방식의 프로그래밍**을 할 수 있다.

## Hooks의 필요성

함수 컴포넌트도 클래스 컴포넌트처럼 사용할 수 있다.

함수 컴포넌트는 클래스 컴포넌트와 다르게, 모듈로 활용하기가 쉽다.

## Hooks의 장점

- 코드가 간결하며 직관적
- class를 사용하지 않고 함수형 프로그래밍이 가능
- 보다 짧은 코드로 state를 사용
  - 원래 state를 사용하려면 `this`같은 문장 규칙, `render`를 사용하는 방법을 생각했어야 했다.

## Hooks의 종류

### 1. useAxios

> HTTP 통신 라이브러리 Axios를 활용한 서버와 통신을 하게 해주는 hook

### 2. useBeforeLeave

> 페이지를 벗어날 때 사용자에게 팝업이나 알림을 띄워 줄 수 있는 hook

### 3. useClick

> 누군가 element를 클릭하였을 때 함수를 실행시켜주는 hook

### 4.  useConfirm

> 이벤트를 실행하기 전에 사용자에게 확인을 받게 해주는 hook

### 5. useFadeIn

> 어떤 요소를 시간이 지남에 따라 서서히 나타나게 하는 hook

### 6. useFullscreen

> 어떤 요소를 풀스크린으로 보여주는 hook

### 7. useHover

> useClick와 동일한 방식

### 8. useInput

> 기본적으로 input을 업데이트 해주는 hook

### 9. useNetwork

> 네트워크가 online/offline일 경우에 맞게 true/false가 반환해주는 hook

### 10. useNotification

> 알람 실행해주는 Hook

### 11. usePreventLeave

> 사용자들이 브라우저를 떠나기 전에 confirm창을 띄워 확인 받는 hook

### 12. useScroll

> 스크롤을 해서 무언가를 지나쳤을때 색상을 바꾸거나 어떤 행동을 하게 해주는 hook

### 13. useTabs

> 버튼에 따라 노출되는 내용을 변화시켜주는 hook

### 14. useTitle

> 문서 제목 업데이트 해주는 hook

💻실습환경

https://codesandbox.io/

**📚** 레퍼런스

https://ko.reactjs.org/docs/hooks-intro.html

https://defineall.tistory.com/900
