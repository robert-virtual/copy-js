```javascript
console.log("hola mundo");
const code = document.getElementById("codigo");
const btn = document.getElementById("btn");
btn.onclick = () => copy(code.textContent);

function copy(text) {
  navigator.clipboard.writeText(text);
}
```
