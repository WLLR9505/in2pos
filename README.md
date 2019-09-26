# in2pos
[![npm version](https://badge.fury.io/js/in2pos.svg)](https://badge.fury.io/js/in2pos)
## Usage:

```js
const in2pos = require('in2pos');

//calculate a expression;
in2pos.CalcPosfix(In2Pos('51/2/4=')); //6.375

//convert infix to posfix;
in2pos.In2Pos('1-2*3'); //[1, 2, 3, "*", "-"]

//receive a posfix expression and calculate;
in2pos.CalcPosfix([1, 2, 3, "*", "-"]); // -5
````
