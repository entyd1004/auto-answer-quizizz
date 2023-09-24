# <img src="https://github.com/entyd1004/auto-answer-quizizz/assets/76547160/0f1f7f4d-2a02-43d3-87e8-7f3c7705214c" alt="image" width="25" height="25"> Auto Answer Quizizz 
- Edit your Pin Code, after paste to Console of devtool
- Press `F` to enable/disable auto answer, please don't spam or keep it as it will cause rate limiting
```js
fetch("https://raw.githubusercontent.com/entyd1004/auto-answer-quizizz/main/bundle.js")
    .then((res) => res.text())
    .then((t) => {
        eval(t);
        autoAnswer(yourPinCode);
    });
```

