# Redux101

Learning Vanila-Redux and React-Redux

- Store는 data를 저장하는 곳
- CreateStore는 reducer를 요구한다.
- Reducer는 data를 변경해주는 함수로 reducer가 return하는 것은 application에 있는 data.
- Action은 function을 부를 때 쓰는 두 번째 parameter, reducer와 소통하는 방법. Object여야 하며 key 이름은 항상 type.
- store.dispatch({key:value});로 reducer에게 action을 보낸다.
- store.subscribe(func); Subscribe는 store 안의 변화를 감지하며, 변화가 감지되면 func 실행.
- store를 수정할 수 있는 유일한 방법은 action을 보내는 것이다.
- State를 mutate 하지 말고, 새로운 state를 create한 후, 그 새로운 state를 return해야 한다.