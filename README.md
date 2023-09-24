# Auto Answer
Edit your Pin Code, after paste to Console of devtool
Press `F` to enable/disable auto reply, please do not spam or keep it as it will cause rate limiting
```js
fetch("https://raw.githubusercontent.com/entyd1004/auto-answer-quizizz/main/bundle.js")
    .then((res) => res.text())
    .then((t) => {
        eval(t);
        autoAnswer(yourPinCode);
    });
```
