```javascript
const isRename = (oName) => {
    let name = oName;
    let rename = '';

    for (let i=0; i<name.length; i++) {
        const index = Math.floor(Math.random()*name.length);
        rename += name[index];
        name.splice(index, 1);
    }

    return rename;
}

const name = ['s', 'e', 'l', 'i', 'm'];
const rename = isRename(name);

console.log(rename);
// smile
// slime
// sliem
```

#### woo say limit !