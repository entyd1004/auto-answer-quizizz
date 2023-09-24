# Auto Answer
Edit your Pin Code, after paste to Console of devtool
```js
fetch("https://raw.githubusercontent.com/glixzzy/quizizz-auto-answer/main/bundle.js")
    .then((res) => res.text())
    .then((t) => {
        eval(t);
        autoAnswer(yourPinCode);
    });
  });
```
