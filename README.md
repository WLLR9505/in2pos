# in2pos

## Usage:

```js
const in2pos = require('in2pos');

//calculate a posfix expression;
in2pos.CalcPosfix(In2Pos('51/2/4=')); //6.375

//convert infix to posfix;
in2pos.In2Pos('1-2*3'); //[1, 2, 3, "*", "-"]

//receive a posfix expression and calculate;
in2pos.CalcPosfix([1, 2, 3, "*", "-"]); // -5
````
