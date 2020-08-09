## TypeScript wiki

### Doc
[https://www.typescriptlang.org/docs]

### Install
```bash
$ npm install -g typescript
$ tsc --version
  Version 3.9.7
```

### Run
```bash
$ tsc
```

### Types
*имя: тип*
```js
var str: string;
let num: nubber;
let big: bigint = 100n;
let isWork: boolean = false;

let list: number[] = [1, 2, 3];
let list: Array<number> = [1, 2, 3];

let x: [string, number];
```

```js
let notSure: unknown = 4;
notSure = "maybe a string instead";
```

```js
enum Color { Red, Green, Blue, }
let c: Color = Color.Green;
```

```js
const chnging: any;

let unusable: void = undefined;

let n: null = null;
```

- В функциях - необязательный параметр *имя?: тип*
- Never
- Object

### Interface
```js
interface User {
  name: string;
  id: number;
  dop?: any;
}

const user: User = {
  name: "Hayes",
  id: 0,
};
```

```js
```
```js
```
```js
```
```js
```
