# 好文收藏
## HTML
* [Battling BEM – 5 common problems and how to avoid them](https://medium.com/fed-or-dead/battling-bem-5-common-problems-and-how-to-avoid-them-5bbd23dee319#.6jkw93axf)
	* 如嵌套太深 用新的组件
* [前端 Meta 用法大汇总](http://www.jianshu.com/p/850d2a209ba8)

## CSS
* [浏览器的工作原理：新式网络浏览器幕后揭秘](http://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/?from=timeline&isappinstalled=0)
* [12 Little-Known CSS Facts (The Sequel)](http://www.sitepoint.com/12-little-known-css-facts-the-sequel/) 介绍了一些CSS的你可能不知道的用法
* [是时候学习Postcss了](http://davidtheclark.com/its-time-for-everyone-to-learn-about-postcss/)
* [The CSS at…](https://css-tricks.com/css/) 一些大公司是怎么处理 CSS：预译器，前缀，代码风格等
* [2015 Codrops 一大波优秀的资源](http://tympanus.net/codrops2015/)
* [Blending Modes in CSS: Color Theory and Practical Application](http://webdesign.tutsplus.com/tutorials/blending-modes-in-css-color-theory-and-practical-application--cms-25201) 混合模式的不同值的颜色值算法。
* [Masking in the Browser with CSS and SVG](http://www.sitepoint.com/masking-in-the-browser-with-css-and-svg/)
* [CSS custom properties (native variables) In-Depth](https://blog.gospodarets.com/css_properties_in_depth) CSS 变量
* [CSS魔法堂：重新认识Box Model、IFC、BFC和Collapsing margins](https://segmentfault.com/a/1190000004625635)
* CSS Modules
  * http://x-team.com/2015/08/css-modules-a-new-way-to-css/
  * https://github.com/css-modules/webpack-demo/
  * [【译】CSS 模块](http://www.w3ctech.com/topic/1479)
* CSS clip path
  * https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path
  * https://css-tricks.com/almanac/properties/c/clip/
* Post CSS
  * http://webdesign.tutsplus.com/tutorials/using-postcss-for-cross-browser-compatibility--cms-24567
* Sass
  * [Sass & Susy教學手冊](https://github.com/gonsakon/Learn-Sass-in-90-days) Learn Sass in 90 days


### 酷炫效果
* [Star Wars 文字动画](https://cssanimation.rocks/starwars/)
* [Water In A Bubble](https://codepen.io/gingerdude/pen/JXwgdK)
* [CSS 来做 Checkbox](http://www.xiumu.org/technology/style-checkboxes-with-css.shtml)
* [Advanced CSS filters](http://iamvdo.me/en/blog/advanced-css-filters) 滤镜的 Demo
* [利用jQuery和CSS实现环形进度条](http://www.w3cplus.com/css3/create-radial-progress-bar-with-jQuery-and-css3.html)
* [如何使用JavaScript生成lowpoly风格图像？](https://www.zhihu.com/question/29856775)

## JS
### 介绍
* [A re-introduction to JavaScript (JS tutorial)](https://developer.mozilla.org/en-US/docs/Web/JavaScript/A_re-introduction_to_JavaScript)

### 代码质量
* [Superhero.js](http://superherojs.com/) 关于如何创建一个可维护的大型 JS 项目的一系列优秀文章
* [refactoring tales](http://javascriptplayground.com/the-refactoring-tales/refactoring-tales.html) 一些案例，应该如何重构
* [avoid forEach](http://aeflash.com/2014-11/avoid-foreach.html)

## 前端工程化
* [张云龙的前端工程系列文章](https://github.com/fouber/blog/issues?q=is%3Aissue+is%3Aopen+label%3A%E5%89%8D%E7%AB%AF%E5%B7%A5%E7%A8%8B)

### 工具方法
* [7 Essential JavaScript Functions](https://davidwalsh.name/essential-javascript-functions)

## 技巧
* [The Art of Debugging(调试的艺术)](https://remysharp.com/2015/10/14/the-art-of-debugging)
	* 重现 Bug
	* 理解 Bug 是如何产生的
	* 解决 Bug
* [JS 做后台任务](http://www.sitepoint.com/how-to-schedule-background-tasks-in-javascript/)
用 requestIdleCallback。 这个方法会在浏览器空闲时做一些事情。用法，如
```
f ('requestIdleCallback' in window) {
  // requestIdleCallback supported
  requestIdleCallback(backgroundTask);
}
else {
  // no support - do something else
  setTimeout(backgroundTask1, 1);
  setTimeout(backgroundTask2, 1);
  setTimeout(backgroundTask3, 1);
}
```


## 其他
* [The state of Web Components](https://hacks.mozilla.org/2015/06/the-state-of-web-components)
* [10 Interview Questions Every JavaScript Developer Should Know](https://medium.com/javascript-scene/10-interview-questions-every-javascript-developer-should-know-6fa6bdf5ad95#.hbilswjcl)
* [程序员的自我修养](http://wiki.jikexueyuan.com/project/a-programmer-prepares/)
* [UserAgent的历史变迁](http://article.yeeyan.org/view/heart5/19211) 每个浏览器都宣称自己是其他浏览器的乱象的由来
