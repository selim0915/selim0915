```javascript
const name = ['s', 'e', 'l', 'i', 'm'];

let rename = '';
for (let i=0; i<name.length; i++) {
    const index = Math.floor(Math.random()*name.length);
    rename += name[index];
    name.splice(index, 1);
}

console.log(rename);
// smile
// slime
// sliem
```

#### woo say limit !