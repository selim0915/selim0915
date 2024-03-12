```javascript
const isName = (name) => name.split('').sort(() => Math.random() - 0.5).join('');

console.log(isName('selim'));
// smile
// slime
// sliem
```
