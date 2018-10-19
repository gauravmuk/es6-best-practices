# ES6 Best Practices

1. Use const always when you do not want to change the type of a variable. 
 * https://mathiasbynens.be/notes/es6-const
2. To export class use, export default ClassName.
3. To extract out a key from an object:
```javascript
const obj = {
  keyName1: keyValue1,
  keyName2: keyValue2
};

// It will declare a constant variable keyName1 having value of keyValue1
const { keyName1 } = obj;
console.log(keyName1); // keyValue1
```
