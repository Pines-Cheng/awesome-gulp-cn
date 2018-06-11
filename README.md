# [awesome-gulp](https://github.com/alferov/awesome-gulp)中文版 

> 一份[gulp](https://github.com/gulpjs/gulp)的资源，插件和使用实例清单， 致力于打造更好的前端工程构建流程。

被老外的[awesome](https://github.com/sindresorhus/awesome) 清单刺激到，觉得有必要翻译一份，为国产的程序员们做点事情，本清单将保持实时更新同步。PS:进都进来了，就顺便看看其他的吧:

- [awesome-nodejs-cn](https://github.com/Pines-Cheng/awesome-nodejs-cn)
- [awesome-react-cn](https://github.com/Pines-Cheng/awesome-react-cn)
- [awesome-npm-cn](https://github.com/Pines-Cheng/awesome-npm-cn)
- [awesome-react-native-cn](https://github.com/Pines-Cheng/awesome-react-native-cn)

> 项目的Github地址：[awesome-gulp-cn](https://github.com/Pines-Cheng/awesome-gulp-cn),欢迎start。
> 
> 翻译得仓促，如有问题，请提[issues](https://github.com/Pines-Cheng/awesome-gulp-cn/issues)。
> 
> 如果想贡献，请[Pull Requests](https://github.com/Pines-Cheng/awesome-gulp-cn/pulls)。

## 目录
- [资源](#资源)
  - [通用资源](#通用资源)
  - [官方文档](#官方文档)
  - [组织](#组织)
  - [入门教程](#入门教程)
    - [Gulp 入门](#gulp入门)
    - [Gulp 4 入门](#gulp-4-入门)
    - [Gulp with Browserify](#gulp-with-browserify)
    - [Gulp with Angular](#gulp-with-browserify)
    - [Gulp with Angular and Browserify](#gulp-with-angular-and-browserify)
    - [Gulp with Angular and Webpack](#gulp-with-angular-and-webpack)
    - [Gulp with React and Browserify](#gulp-with-react-and-browserify)
    - [Gulp with Ember](#gulp-with-ember)
  - [其他资源](#其他资源)
- [插件](#插件)
  - [编辑](#编辑)
  - [编译](#编译)
  - [合并](#合并)
  - [压缩](#压缩)
  - [优化](#优化)
  - [资源注入](#资源注入)
  - [模板](#模板)
  - [代码校验](#代码校验)
  - [实时加载](#实时加载)
  - [缓存](#缓存)
  - [流控制](#流控制)
  - [日志](#日志)
  - [测试](#测试)
  - [其他插件](#其他插件)
- [脚手架](#脚手架)
  - [参考工程](#参考工程)
  - [Yeoman生成器](#yeoman生成器)
- [其他](#其他)

## 资源
### 通用资源
* [官网](http://gulpjs.com/)
* [Github库](https://github.com/gulpjs/gulp)
* [插件注册](http://gulpjs.com/plugins/)
* [NPM模块](https://www.npmjs.com/package/gulp)
* [插件黑名单](https://github.com/gulpjs/plugins/blob/master/src/blackList.json)

### 官方文档
* [快速开始](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
* [API文档](https://github.com/gulpjs/gulp/blob/master/docs/API.md)
* [CLI 文档](https://github.com/gulpjs/gulp/tree/master/docs#articles)
* [开始写一个插件](https://github.com/gulpjs/gulp/blob/master/docs/writing-a-plugin/README.md)
* [使用诀窍](https://github.com/gulpjs/gulp/tree/master/docs/recipes)

### 组织
* [StackOverflow](http://stackoverflow.com/questions/tagged/gulp)
* [Twitter](https://twitter.com/gulpjs)

### 入门教程
#### Gulp入门
* [使用Gulp构建前端工程](https://www.smashingmagazine.com/2014/06/building-with-gulp/)
* [通过Gulp.js轻松自动化构建你的前端工程](https://scotch.io/tutorials/automate-your-tasks-easily-with-gulp-js)
* [Gulp，让前端工程可视化](https://medium.com/@contrahacks/gulp-3828e8126466)
* [Gulp.js是什么？](http://stefanimhoff.de/tag/gulp/)
* [使用Gulp在你的HTML中直接插入Scripts和Styles标签](http://blog.johnnyreilly.com/2015/02/using-gulp-in-asp-net-instead-of-web-optimization.html)
* [5节课学会使用Gulp.js](http://denbuzze.com/post/5-lessons-learned-using-gulpjs/)
* [我是怎样摆脱前端工程的困扰的？](http://lab.brightnorth.co.uk/2014/08/13/automating-linkage-how-i-learned-to-stop-worrying-and-love-the-build/)
* [第一次开始Gulp Task](https://www.codementor.io/development-process/tutorial/how-to-set-up-gulp-beginner-guide#/)
* [为什么你不自己写一个Gulp插件？](http://blog.overzealous.com/post/74121048393/why-you-shouldnt-create-a-gulp-plugin-or-how-to)
* [6个最好的从根本改善你的开发经验的Gulp实战练习](http://blog.rangle.io/angular-gulp-bestpractices/)
* [Gulp初学者教程](https://css-tricks.com/gulp-for-beginners/)

#### Gulp 4 入门
* [迁移到Gulp 4的例子](https://blog.wearewizards.io/migrating-to-gulp-4-by-example)
* [Gulp 4: 新的task执行系统 - gulp.parallel 和 gulp.series](http://fettblog.eu/gulp-4-parallel-and-series/)

#### Gulp with Browserify
* [Gulp + Browserify, the Gulp-y Way](https://medium.com/@sogko/gulp-browserify-the-gulp-y-way-bb359b3f9623)
* [Gulp + Browserify](https://viget.com/extend/gulp-browserify-starter-faq)
* [快速构建Browserify和Watchify](https://github.com/gulpjs/gulp/blob/master/docs/recipes/fast-browserify-builds-with-watchify.md)

#### Gulp with Angular
* [Angular工程需要什么 - Gulp能提供什么](http://blog.jhades.org/what-every-angular-project-likely-needs-and-a-gulp-build-to-provide-it/)

#### Gulp with Angular and Browserify
* [使用 Gulp, Node and Browserify构建先进的 AngularJS工程结构](http://omarfouad.com/blog/2015/03/21/advanced-angularjs-structure-with-gulp-node-and-browserify/)

#### Gulp with React and Browserify
* [Browserify、Gulp 和 React](https://hacks.mozilla.org/2014/08/browserify-and-gulp-with-react/)
* [Taking React to the Next Level: Mixins, Gulp, and Browserify](http://pomax.github.io/1420592591221/taking-react-to-the-next-level-mixins-gulp-and-browserify)

#### Gulp with Ember
* [使用Gulp.js改进你的Ember.js工作流](http://www.sitepoint.com/improving-ember-js-workflow-using-gulp-js/)

### 其他资源
* [Gulp 备忘录](https://github.com/osscafe/gulp-cheatsheet)
* [Gulp清单](https://github.com/johnpapa/gulp-patterns)

## 插件
### 编译
* [gulp-sass](https://github.com/dlmanning/gulp-sass) - 通过 [libsass](https://github.com/sass/libsass)将Sass编译成 CSS 
* [gulp-ruby-sass](https://github.com/sindresorhus/gulp-ruby-sass) - 通过 Ruby Sass将Sass编译成CSS 
* [gulp-compass](https://github.com/appleboy/gulp-compass) - 通过 Ruby Sass和CompassSass编译成CSS 
* [gulp-less](https://github.com/plus3network/gulp-less) - [Less](https://github.com/less/less.js)编译成 CSS.
* [gulp-stylus](https://github.com/stevelacy/gulp-stylus) - [Stylus](https://github.com/stylus/stylus) 编译成 CSS.
* [gulp-postcss](https://github.com/postcss/gulp-postcss) - Pipe CSS 通过 [PostCSS](https://github.com/postcss/postcss) processors with a single parse.
* [gulp-coffee](https://github.com/contra/gulp-coffee) - [Coffeescript](https://github.com/jashkenas/coffeescript) 编译成 JavaScript.
* [gulp-typescript](https://github.com/ivogabe/gulp-typescript) - [TypeScript](https://github.com/Microsoft/TypeScript)编译成JavaScript.
* [gulp-react](https://github.com/sindresorhus/gulp-react) - Facebook [React](https://github.com/facebook/react) JSX 模板编译成JavaScript.
* [webpack-stream](https://github.com/shama/webpack-stream) - 将[webpack](https://github.com/webpack/webpack)集成在Gulp中使用。

* [gulp-babel](https://github.com/babel/gulp-babel) - ES6编译成ES5 通过 [babel](https://github.com/babel/babel).
* [gulp-traceur](https://github.com/sindresorhus/gulp-traceur) - ES6编译成ES5 通过 [Traceur](https://github.com/google/traceur-compiler).
* [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator) - ES6编译成ES5 通过 [Regenerator](https://github.com/facebook/regenerator).
* [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - [过时的] ES6编译成ES5 通过 [es6-transpiler](https://github.com/termi/es6-transpiler).
* [gulp-myth](https://github.com/sindresorhus/gulp-myth) - [Myth](https://github.com/segmentio/myth) - a polyfill for future versions of the CSS spec.
* [gulp-cssnext](https://github.com/MoOx/gulp-cssnext) - [过时的] 使用下一代的 CSS 规范通过 [cssnext](https://github.com/MoOx/postcss-cssnext).

### 合并
* [gulp-concat](https://github.com/contra/gulp-concat) - 合并文件.

### 压缩
* [gulp-clean-css](https://github.com/scniro/gulp-clean-css) - 压缩 CSS 通过 [clean-css](https://github.com/jakubpawlowicz/clean-css).
* [gulp-csso](https://github.com/ben-eb/gulp-csso) - 压缩 CSS 通过 [CSSO](https://github.com/css/csso).
* [gulp-uglify](https://github.com/terinjokes/gulp-uglify) - 压缩 JavaScript 通过 [UglifyJS2](https://github.com/mishoo/UglifyJS2).
* [gulp-htmlmin](https://github.com/jonschlinkert/gulp-htmlmin) - 压缩 HTML 通过 [html-minifier](https://github.com/kangax/html-minifier).
* [gulp-minify-html](https://github.com/murphydanger/gulp-minify-html) - 压缩 HTML 通过
 [Minimize](https://github.com/Swaagie/minimize).
* [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin) - 压缩 PNG, JPEG, GIF and SVG 图片 通过 [imagemin](https://github.com/imagemin/imagemin).
* [gulp-svgmin](https://github.com/ben-eb/gulp-svgmin) - 通过Gulp压缩 SVG 文件

### 优化
* [gulp-uncss](https://github.com/ben-eb/gulp-uncss) - 移除未使用的CSS选择器通过 [UnCSS](https://github.com/giakki/uncss).
* [gulp-css-base64](https://github.com/zckrs/gulp-css-base64) - 将CSS文件中所有的资源(有url()声明的)变成base64-encoded 数据的URI字符串
* [gulp-svg2png](https://github.com/akoenig/gulp-svg2png) - 将SVGs转换成PNGs
* [gulp-responsive](https://github.com/mahnunchik/gulp-responsive) - 生成不同尺寸的图片
* [gulp-svgstore](https://github.com/w0rm/gulp-svgstore) -将svg files 合并成一个通过<symbol> 元素
* [gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) - 通过SVG icons创建 icon fonts

### 资源注入
* [gulp-useref](https://github.com/jonkemp/gulp-useref) - 解析HTML文件中特殊标签里面的script或style标签，合并成一个script或css文件，并替换。
* [gulp-inject](https://github.com/klei/gulp-inject) - 将指定的css或js文件以标签的形式插入到HTML中的指定标志内。
* [wiredep](https://github.com/taptapship/wiredep) - 将Bower依赖自动注入HTML文件中。


### 模板
* [gulp-angular-templatecache](https://github.com/miickel/gulp-angular-templatecache) - 在$templateCache中联系并注册AngularJS模板
* [gulp-jade](https://github.com/phated/gulp-jade) - [Jade](https://github.com/pugjs/jade) 转换成 HTML.
* [gulp-handlebars](https://github.com/lazd/gulp-handlebars) - [Handlebars](https://github.com/wycats/handlebars.js)模板转换成 JavaScript.
* [gulp-hb](https://github.com/shannonmoeller/gulp-hb) - [Handlebars](https://github.com/wycats/handlebars.js) 模板转换成 HTML.
* [gulp-nunjucks](https://github.com/sindresorhus/gulp-nunjucks) - [Nunjucks](https://github.com/mozilla/nunjucks)模板转换成JavaScript.
* [gulp-dustjs](https://github.com/sindresorhus/gulp-dust) - [Dust](https://github.com/linkedin/dustjs)模板转换成JavaScript.
* [gulp-riot](https://github.com/e-jigsaw/gulp-riot) - [Riot](https://github.com/riot/riot)模板转换成JavaScript.
* [gulp-markdown](https://github.com/sindresorhus/gulp-markdown) - Markdown → HTML.
* [gulp-template](https://github.com/sindresorhus/gulp-template) - [Lodash ](https://github.com/lodash/lodash)模板转换成JavaScript.
* [gulp-swig](https://github.com/colynb/gulp-swig) - [Swig](https://github.com/paularmstrong/swig)模板转换成HTML.
* [gulp-remark](https://github.com/denysdovhan/gulp-remark) - Gulp plugin for [remark]的Gulp插件(https://github.com/wooorm/remark) 通过插件处理markdown

### 代码校验
* [gulp-csslint](https://www.npmjs.com/package/gulp-csslint) - 通过[CSSLint](https://github.com/CSSLint/csslint)自动校验CSS.
* [gulp-htmlhint](https://github.com/bezoerb/gulp-htmlhint) - 通过[HTMLHint](https://github.com/yaniswang/HTMLHint)校验HTML.
* [gulp-jshint](https://github.com/spalger/gulp-jshint) - 通过[JSHint](https://github.com/jshint/jshint)发现错误和潜在的问题.
* [gulp-jscs](https://github.com/jscs-dev/gulp-jscs) - 通过[jscs](https://github.com/jscs-dev/node-jscs)检查JavaScript代码风格.
* [gulp-coffeelint](https://github.com/janraasch/gulp-coffeelint) - 一种用来保证[CoffeeScript](https://github.com/jashkenas/coffeescript)代码风格统一的检查。
* [gulp-tslint](https://github.com/panuhorsmalahti/gulp-tslint) - gulp的[TypeScript](https://github.com/Microsoft/TypeScript)代码校验插件.
* [gulp-eslint](https://github.com/adametry/gulp-eslint) - ECMAScript/JavaScript代码校验.
* [gulp-w3cjs](https://github.com/callumacrae/gulp-w3cjs) - 通过[w3cjs](https://github.com/thomasdavis/w3cjs)检验HTML.
* [gulp-lesshint](https://github.com/lesshint/gulp-lesshint) - 通过[lesshint](https://github.com/lesshint/lesshint)校验LESS.

### 实时加载
* [browser-sync](https://github.com/BrowserSync/browser-sync) - 保证多个浏览器或设备网页同步显示 ([recipes](https://github.com/BrowserSync/gulp-browser-sync)).
* [gulp-livereload](https://github.com/vohof/gulp-livereload) - Gulp的实时加载插件.

### 缓存
* [gulp-changed](https://github.com/sindresorhus/gulp-changed) - 仅让发生改变的文件通过.
* [gulp-cached](https://github.com/contra/gulp-cached) - 一个简单的文件内存缓存.
* [gulp-remember](https://github.com/ahaurw01/gulp-remember) - 记忆并回收通过了的文件.
* [gulp-newer](https://github.com/tschaub/gulp-newer) - 只让新的源码通过.

### 流控制
* [merge-stream](https://github.com/grncdr/merge-stream) - 合并多个流到一个插入的流.
* [streamqueue](https://github.com/nfroidure/StreamQueue) - 逐渐输入队列的流.
* [run-sequence](https://github.com/OverZealous/run-sequence) - 按要求运行一些依赖的Gulptask.
* [gulp-if](https://github.com/robrich/gulp-if) - 按照条件运行task.

### 日志
* [gulp-notify](https://github.com/mikaelbr/gulp-notify) - Gulp的通知插件.
* [gulp-size](https://github.com/sindresorhus/gulp-size) - 显示你的项目的大小.
* [gulp-debug](https://github.com/sindresorhus/gulp-debug) - 通过调试文件流来观察那些文件通过了你的Gulp管道.

### 测试
* [gulp-mocha](https://github.com/sindresorhus/gulp-mocha) - 运行[Mocha](https://github.com/mochajs/mocha)测试用例.
* [gulp-jasmine](https://github.com/sindresorhus/gulp-jasmine) - 在Node.js中运行[Jasmine 2](https://github.com/jasmine/jasmine) 测试用例.
* [gulp-protractor](https://github.com/mllrsohn/gulp-protractor) - 为[Protractor](https://github.com/angular/protractor)测试用例包裹Gulp.
* [gulp-coverage](https://github.com/dylanb/gulp-coverage) - 为Node.js覆盖相对于运行的测试运行独立的报告.
* [gulp-karma](https://github.com/karma-runner/gulp-karma) - 通过Gulp运行Karma测试用例.
* [gulp-ava](https://github.com/sindresorhus/gulp-ava)- 通过Gulp运行[AVA](https://github.com/sindresorhus/ava) 测试用例.

### 其他插件
* [gulp-util](https://github.com/gulpjs/gulp-util) - 包含一系列有用插件.
* [gulp-plumber](https://github.com/floatdrop/gulp-plumber) - 防止错误引起管道中断Prevent pipe breaking caused by errors.
* [gulp-load-plugins](https://github.com/jackfranklin/gulp-load-plugins) - 自动加载Gulp插件.
* [main-bower-files](https://github.com/ck86/main-bower-files) - 构建时自动获取bower库的文件.
* [autoprefixer](https://github.com/postcss/autoprefixer) - 解析CSS且根据规则添加浏览器兼容性前缀.
* [gulp-sourcemaps](https://github.com/floridoo/gulp-sourcemaps) - 提供source map支持.
* [gulp-replace](https://github.com/lazd/gulp-replace) - Gulp的一个字符串替换插件.
* [gulp-rename](https://github.com/hparra/gulp-rename) - 轻松重命名文件.
* [gulp-rev](https://github.com/sindresorhus/gulp-rev) - 在静态文件名的后面添加hash值，如: unicorn.css → unicorn-d41d8cd98f.css.
* [del](https://github.com/sindresorhus/del) - 使用globs删除文件/文件夹.
* [gulp-exec](https://github.com/robrich/gulp-exec) - 运行一个shell命令.
* [gulp-strip-debug](https://github.com/sindresorhus/gulp-strip-debug) - 除去javascript代码中的console,alert,debugger声明.
* [gulp-cssimport](https://github.com/unlight/gulp-cssimport) - 解析CSS文件，找到imports,将连接文件替换成imort声明.
* [gulp-inline-css](https://github.com/jonkemp/gulp-inline-css) - 将HTML中的css属性放到style标签中.
* [gulp-gh-pages](https://github.com/shinnn/gulp-gh-pages) - 将内容发布到GiHub有页面.
* [gulp-ng-annotate](https://github.com/Kagami/gulp-ng-annotate) - 通过[ng-annotate](https://github.com/olov/ng-annotate)添加Angular依赖注入.
* [gulp-bump](https://github.com/stevelacy/gulp-bump) - 通过Gulp Bump任何semvar JSON版本.
* [gulp-file-include](https://github.com/coderhaoxin/gulp-file-include) - 通过Gulp Include文件.
* [gulp-zip](https://github.com/sindresorhus/gulp-zip) - 以ZIP格式压缩文件.
* [gulp-git](https://github.com/stevelacy/gulp-git) - 通过Gulp运行git命令.
* [gulp-filter](https://github.com/sindresorhus/gulp-filter) - 使用globbing过滤文件.
* [gulp-preprocess](https://github.com/jas/gulp-preprocess) - 基于自定义内容或环境配置预处理文件.

## 脚手架
### 模板
* [web-starter-kit](https://github.com/google/web-starter-kit) - Google的Web Starter Kit.
* [gulp-plugin-boilerplate](https://github.com/sindresorhus/gulp-plugin-boilerplate) - 创建Gulp插件的开始模板.
* [polymer-starter-kit](https://github.com/polymerelements/polymer-starter-kit) -Polymer 1.0 应用的起点.
* [este](https://github.com/este/este) - 同构的web应用最全面的React/Flux开发栈和开始模板.
* [mnml](https://github.com/mrmrs/mnml) - 开发响应式HTML5/Sass项目的最小开始模板.
* [kraken](https://github.com/cferdinandi/kraken) 一个轻量级的、移动端优先的前端开发开始模板.
* [angularjs-gulp-browserify-boilerplate](https://github.com/jakemmarsh/angularjs-gulp-browserify-boilerplate) - 一个使用AngularJS, Sass, gulp, 和 Browserify技术的开始模板.
* [hapi-ninja](https://github.com/poeticninja/hapi-ninja) - 一个使用Node.js, Hapi, and Swig技术的开始模板.
* [laravel-5-boilerplate](https://github.com/rappasoft/laravel-5-boilerplate) - 一个Laravel 5 开始模板.
* [react-starterkit](https://github.com/wbkd/react-starterkit) - 包含react-router, Reflux, jest, webpack, gulp and Stylus的React开始模板.

### Yeoman生成器
* [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp) - A 一个流行的web应用的gulp生成器.
* [generator-gulp-angular](https://github.com/Swiip/generator-gulp-angular) -  使用Gulp的AngularJS 的Yeoman生成器.
* [generator-react-gulp-browserify](https://github.com/randylien/generator-react-gulp-browserify) - 一个React库的Yeoman生成器，包含gulp, Browserify, Browsersync and Bootstrap.
* [generator-node-gulp](https://github.com/youngmountain/generator-node-gulp) - 一个Node.js模块生成器，包含gulp和 Mocha.
* [generator-gulp-bootstrap](https://github.com/niallobrien/generator-gulp-bootstrap) - 一个包含Bootstrap, gulp 和libsass的Yeoman生成器·.
* [generator-angulpify](https://github.com/jgoux/generator-angulpify) -  一个包含AngularJS, gulp和Browserify的Yeoman生成器.
* [generator-ionic-gulp](https://github.com/tmaximini/generator-ionic-gulp) - 一个Ionic工厂的Yeoman生成器.
* [generator-gulp-plugin-boilerplate](https://github.com/sindresorhus/generator-gulp-plugin-boilerplate) -一个输出 [gulp plugin boilerplate](https://github.com/sindresorhus/gulp-plugin-boilerplate)的脚手架.
* [generator-jekyllized](https://github.com/sondr3/generator-jekyllized) - 一个包含gulp, Sass, AutoPrefixer,资源优化，缓存等的Jekyll工作流.

## 其他
* [elixir](https://github.com/laravel/elixir) - 一个为你的应用定义基本的gulp任务的干净、灵活的API.
* [gulp-app](https://github.com/sindresorhus/gulp-app) - 将Gulp作为一个应用(OS X).
* [lmn-gulp-tasks](https://github.com/Lostmyname/lmn-gulp-tasks) - gulp任务的单元测试示例.
* [gulp-chef](http://gulp-cookery.github.io/gulp-chef/) - 一个优雅的、简单的重复使用gulp task的方法.

## 证书
[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

