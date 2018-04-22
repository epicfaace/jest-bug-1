Minimal repository that is related to this issue: https://github.com/kulshekhar/ts-jest/issues/494

Instructions:
```
npm i
npm run test
```

Error message I get:
```
 FAIL  .\test.ts
  ● Test suite failed to run

    C:\Users\arama\git\jest-bug-1\node_modules\lodash-es\lodash.js:10
    export { default as add } from './add.js';
    ^^^^^^

    SyntaxError: Unexpected token export

      1 | import {add} from "lodash-es";
      2 | test('should work', () => {
    > 3 |   expect(add(6,4)).toEqual(10);
      4 | });

      at ScriptTransformer._transformAndBuildScript (node_modules/jest-runtime/build/script_transformer.js:316:17)
      at Object.<anonymous> (test.ts:3:19)
```