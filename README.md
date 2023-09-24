# Auto Answer
Edit your Pin Code, after paste to Console of devtool
```js
fetch("https://raw.githubusercontent.com/entyd1004/auto-answer-quizizz/main/bundle.js")
    .then((res) => res.text())
    .then((t) => {
        eval(t);
        autoAnswer(575881);
    });
```
