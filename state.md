# State

    - 컴포넌트 안에서 지속적으로 변경이 일어나는 값을 관리하기 위해 사용.
    - State 값이 변경되고 재 렌더링이 필요한 경우에 React가 자동으로 계산하여 변경된 부분을 렌더링 함.

- 사용법

  - import { useState } from "react"; 추가 후
  - const App = () => {
    const [value, setValue] = useState(초기값);
    return } 와 같은 형식으로 사용한다.
  - EX) let [monotitle, b] = useState(["1", "2", "3",]);
  - <p>{a[0]}</p> // 1
  - <p>{a[1]}</p> // 2
  - <p>{a[2]}</p> // 3

    - 위 값 외에도 boolean, 숫자 등 여러 값들을 사용할 수 있다.
