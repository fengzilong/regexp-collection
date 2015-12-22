# regexp-collection

html tag

```js
/<([-\w]+)\s*([^"'\/>]*(?:(?:"[^"]*"|'[^']*'|\/[^>])[^'"\/>]*)*)(\/?)>/g
```

html comment
```js
```

js line comment
```js
/^\s*\/\/.*$/gm
```

js block comment
```js
/\/\*[\s\S]*?\*\//g
```
