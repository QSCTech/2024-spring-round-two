# sandbox
## 背景
现在，web技术（包括html、css、js及其衍生技术）越来越流行。有时，我们会希望能安全地执行来自不信任来源的（如其它用户上传的）js代码。  
然而，直接使用在当前网页中执行未知来源js代码是十分危险的。js能够修改UI，也可以直接跳转到其它网页，还可以以用户的身份发起请求。

我们希望能有一个较安全的沙箱机制，能够执行一段js代码但不会影响网页自身的安全，并能获取运行的结果值。

## 要求
- 使用JavaScript实现沙箱机制。代码运行结果只要求判定是否为真值，并且能由沙箱外侧的js调用方获取以执行其他逻辑。
- 实现简易的用户界面，至少提供一个输入框，一个运行按钮，一个区域显示运行结果。
- 实现可重用的沙箱类，至少可以多次新建沙箱。
- 不允许使用直接实现沙箱的第三方库，不允许使用模拟js引擎或类似功能的第三方库(也不应尝试自己实现)。
- 不能在运行时访问网络获取动态数据。
- 完成编程后，**简要谈谈从此题目中有什么收获/感想/吐槽**，可以从题目的角度谈，也可以从学习时所用的资料、对web技术的看法等角度谈。*如果时间紧迫，您也可以选择在二面现场再与面试官交流。*

## Bonus
- 可在同一沙箱内运行多次代码。
- 使用任一主流前端框架进行渲染。`Web Components`视同主流前端框架。
- 使用TypeScript。
- 适当使用前端工具链，并根据自己喜好配置一些有利于开发的包，如less/sass,webpack/esbuild/rollup/vite等。

## 参考资料
- [JavaScript 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [MDN](https://developer.mozilla.org)
- [使用 Web Workers](https://developer.mozilla.org/zh-CN/docs/Web/API/Web_Workers_API/Using_web_workers)
- [TypeScript 官网](https://www.typescriptlang.org)
- [Web Component](https://developer.mozilla.org/zh-CN/docs/Web/API/Web_components)