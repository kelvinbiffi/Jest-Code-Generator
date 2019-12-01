# Jest-Code-Generator
Jest code generator based on function documentations

```javascript
// Base code
/**
 * #jest
 * Function Description
 *
 * @param {Integer} num1 description [4,6]
 * @param {Integer} num2 description [4,3]
 *
 * @return {Integer} [8,9]
 */
export function sumFunction (num1, num2) { ... }
```

```javascript
// Jest code

import {sumFunction} from 'File'

...
```

