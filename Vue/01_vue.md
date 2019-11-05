# Vue

> M(Model) V(View) VM(ViewModel)

1. 프론트엔드 자바스크립트 프레임워크
   * 작고 가벼우며 배우기가 쉬움
   * 컴포넌트의 종속성이 렌더링 중 자동으로 추적되어 다시 렌더링해야하는 컴포넌트에 대해서 정확히 알고 있다.
   * 이러한 이유로 불필요한 업데이트를 방지할 수 있다.

2. 컴포넌트
   * 컴포넌트화하여 재사용성과 유지보수 성능을 높일 수 있다.

## Vue CLI

* vue 개발 환경을 설정해주는 도구
* 기본적인 개발 환경을 셋팅해주기 때문에 폴더구조, build 등에 대한 고민을 덜을 수 있다.



function은 호출한 애를 잡는다. (호출한 곳을 찾는다?)

: this 동작을 위하여.

arrow function => lexicial this



this 쓸 때

1. 모든 함수는 function 키워드로
2. 메서드에서 쓰이는 함수 중에 콜백함수는 arrow function
3. 메서드 정의시에는 function 키워드