# Movie App 2021

<h2>React JS (2021)</h2>

<h3>#2.1 Reusable Componets whith JSX + Pops</h3>
    1. jsx = HTML + JavaScript<br/>
    2. component는 대문자로 시작해야하고, 우리의 component 정보를 보낼 수 있다.<br/>
    3. props = 뭐든지 component에 넣게 되는 것들<br/>
       porps는 argument(인자)로 간다. <br/>

<h3>#2.1 Dynamic Component Generation</h3>
    1. JavaScript 함수를 이용해서 동적으로 componet를 변경 할 수 있다.<br/>
    2  React는 JavaScript라는 걸 잊지 말자<br/>

<h3>#2.3 map Recap</h3>
    1. map은 각각 item 별로 function을 호출 한다. <br/>
    2. Warning: Each child in a list should have a unique "key" prop.<br/>
         -> react의 모든 element는 유일해야한다. list안으로 집어 넣을 때 , 유일성을 읿어 버린다. 따라서 id를 추가

<h3>#2.4 Protection with PropTypes</h3>
    1. prop-types : 내가 전달받은 props 가 내가 원하는 props인지 확인을 해준다.<br/>
    2. PropTypes로 반드시 이름을 지어야 한다.<br/>

<h3>#3.0 Class Components and State</h3>
    1. Function component는 funtion이고 뭔가를 Return 한다. 그리고 screen에 표시된다.<br/>
    2. Class component는 react component로 부터 확장되고 screen에 표시된다.<br/>
    3. state는 object이고 component의 data를 넣을 공간이 있고 이 데이터는 변한다.<br/>
    4. 매순간 setState를 호출할 때 마다 react는 새로운 state와 함께 render function을 호출한다.

