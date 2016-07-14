##  Rollup Tree Shaking

```js
// main.js
import AwesomeSauce from 'awesome-sauce';

let sauce = new AwesomeSauce();
sauce.makeIt();
```

```js
// awesome-sauce.js

class AwesomeSauce {
  // 100 lines of code
}

class EnterpriseSauce {
  // 2000 lines of code
}

export EnterpriseSauce;
export default AwesomeSauce;
```
