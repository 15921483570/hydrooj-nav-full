# Nav Full

偶尔会遇到做题时, 想点自测开关却点到用户名. 可以将最上方的导航条拓宽, 调成两端顶头, 就没那么容易点到了.

已废弃，不如直接改模版，nav.html 里边加一个 style 即可：

```html
<div class="columns clearfix" style="position: absolute;left: 0;width: 100%;">
```
