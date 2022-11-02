이번에는 Action 객체를 완성해봅시다!

Action은 어떻게 state를 변경할지 정의해놓은 객체입니다.
Action 객체는 Dispatch 함수를 통해 Reducer 함수 두번째 인자로 전달됩니다.

Action 객체 안의 type은 필수로 지정을 해주어야 합니다.
여기서 지정한 type에 따라 Reducer 함수에서 새로운 state를 리턴하게 됩니다.

- index.js
  안내한 순서에 따라 index.js를 완성해주세요!

1. 유어클래스에 있는 Action 예제 중 Action Creator 함수 increase를
   복사해오세요.
2. Action Creator 함수 decrease를 만들어 주세요. type은 'DECREASE'로
   설정해주세요.
3. 앞서 만든 Action Creator 함수를 다른 파일에도 사용하기 위해 export를
   붙혀주세요.
