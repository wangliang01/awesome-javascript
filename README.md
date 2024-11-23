# Awesome JavaScript [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sorrycc/awesome-javascript/)

A collection of awesome browser-side [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) libraries, resources and shiny things.

* [Awesome JavaScript](#awesome-javascript)
  * [Package Managers](#package-managers)
  * [Component management](#component-management)
  * [Loaders](#loaders)
  * [Transpilers](#transpilers)
  * [Bundlers](#bundlers)
  * [Minimizers](#minimizers)
  * [Type Checkers](#type-checkers)
  * [Testing Frameworks](#testing-frameworks)
  * [QA Tools](#qa-tools)
  * [MVC Frameworks and Libraries](#mvc-frameworks-and-libraries)
  * [Node-Powered CMS Frameworks](#node-powered-cms-frameworks)
  * [Templating Engines](#templating-engines)
  * [Game Engines](#game-engines)
  * [Articles/Posts](#articles-and-posts)
  * [Data Visualization](#data-visualization)
    * [Timeline](#timeline)
    * [Spreadsheet](#spreadsheet)
  * [Editors](#editors)
  * [Documentation](#documentation)
  * Utilities
    * [Files](#files)
    * [Functional Programming](#functional-programming)
    * [Reactive Programming](#reactive-programming)
    * [Data Structure](#data-structure)
    * [Date](#date)
    * [String](#string)
    * [Number](#number)
    * [Storage](#storage)
    * [Color](#color)
    * [I18n And L10n](#i18n-and-l10n)
    * [Control Flow](#control-flow)
    * [Routing](#routing)
    * [Security](#security)
    * [Log](#log)
    * [RegExp](#regexp)
    * [Media](#videoaudio)
    * [Voice Command](#voice-command)
    * [API](#api)
    * [Streaming](#streaming)
    * [Vision Detection](#vision-detection)
    * [Browser Detection](#browser-detection)
    * [Operating System](#operating-system)
    * [Benchmark](#benchmark)
    * [Machine Learning](#machine-learning)
    * [Web Worker](#web-worker)
  * UI
    * [Code Highlighting](#code-highlighting)
    * [Loading Status](#loading-status)
    * [Validation](#validation)
    * [Keyboard Wrappers](#keyboard-wrappers)
    * [Tours And Guides](#tours-and-guides)
    * [Notifications](#notifications)
    * [Sliders](#sliders)
    * [Range Sliders](#range-sliders)
    * [Form Widgets](#form-widgets)
    * [Tips](#tips)
    * [Modals and Popups](#modals-and-popups)
    * [Scroll](#scroll)
    * [Menu](#menu)
    * [Table/Grid](#tablegrid)
    * [Frameworks](#frameworks-1)
    * [Boilerplates](#boilerplates)
    * [Image](#image)
  * [Gesture](#gesture)
  * [Maps](#maps)
  * [Typography](#typography)
  * [Animations](#animations)
  * [Image processing](#image-processing)
  * [ES6](#es6)
  * [Generators](#generators)
  * [Full Text Search](#full-text-search)
  * [SDK](#sdk)
  * [Misc](#misc)
* [Worth Reading](#worth-reading)
* [Other Awesome Lists](#other-awesome-lists)
* [Contributing](#contributing)

----

## Package Managers (包管理器)

*用于托管 JavaScript 库并提供获取和打包工具的包管理器*

* [npm](https://www.npmjs.com/) - JavaScript 的包管理器。
* [Bower](https://github.com/bower/bower) - Web 的包管理器。
* [component](https://github.com/componentjs/component) - 用于构建更好的 Web 应用的客户端包管理。
* [spm](https://github.com/spmjs/spm) - 全新的静态包管理器。
* [jam](https://github.com/caolan/jam) - 一个使用面向浏览器且兼容 RequireJS 的仓库的包管理器。
* [jspm](https://github.com/jspm/jspm-cli) - 无摩擦的浏览器包管理。
* [Ender](https://github.com/ender-js/Ender) - 无库的库。
* [volo](https://github.com/volojs/volo) - 从模板创建前端项目,添加依赖,并自动化生成的项目。
* [Duo](https://github.com/duojs/duo) - 下一代包管理器,融合了 Component、Browserify 和 Go 的最佳理念,让组织和编写前端代码变得快速无痛。
* [yarn](https://yarnpkg.com/) - 快速、可靠、安����的依赖管理。
* [pnpm](https://pnpm.io/) - 快速、节省磁盘空间的包管理器。

## Component Management (组件管理)

* [Bit](https://github.com/teambit/bit) - Create, find and reuse components (React, Angular, Node etc.) across applications.

## Loaders (加载器)

*JavaScript 的模块和加载系统。*

* [RequireJS](https://github.com/requirejs/requirejs) - JavaScript 文件和模块加载器。
* [browserify](https://github.com/substack/node-browserify) - 在浏览器端实现 node.js 风格的 require()。
* [SeaJS](https://github.com/seajs/seajs) - Web 端模块加载器。
* [HeadJS](https://github.com/headjs/headjs) - HEAD 中唯一的脚本。
* [lazyload](https://github.com/rgrove/lazyload/) - 小巧的、无依赖的异步 JavaScript 和 CSS 加载器。
* [script.js](https://github.com/ded/script.js) - 异步 JavaScript 加载器和依赖管理器。
* [systemjs](https://github.com/systemjs/systemjs) - 符合 AMD、CJS 和 ES6 规范的模块加载器。
* [LodJS](https://github.com/yanhaijing/lodjs) - 基于 AMD 的模块加载器。
* [ESL](https://github.com/ecomfe/esl) - 浏览器优先的模块加���器,支持延迟定义和 AMD。
* [modulejs](https://github.com/lrsjng/modulejs) - 轻量级 JavaScript 模块系统。

## Transpilers (转译器)

*将现代 JavaScript 语法转换为旧版本 JavaScript 语法的软件。*

* [SWC](https://swc.rs/) - 基于 Rust 的可扩展编译平台。

## Bundlers (打包工具)

* [webpack](https://github.com/webpack/webpack) - 为浏览器打包 CommonJs/AMD 模块。
* [Rollup](https://github.com/rollup/rollup) - 下一代 ES6 模块打包器。
* [Brunch](https://github.com/brunch/brunch) - 快速的前端 Web 应用构建工具,配置简单直观。
* [Parcel](https://github.com/parcel-bundler/parcel) - 极速零配置的 Web 应用打包器。
* [Microbundle](https://github.com/developit/microbundle) - 零配置的小型模块打包器。
* [FuseBox](https://github.com/fuse-box/fuse-box) - 正确实现打包的工具
* [Snowpack](https://www.snowpack.dev/) - 为现代 Web 设计的快速前端构建工具。
* [bundle](https://bundle.js.org) - 快速的在线 npm 包大小检查工具。

# Minimizers (压缩工具)

* [Terser](https://github.com/terser/terser) - ES6+ 的解析器、压缩器和美化器工具包
* [Uglify](https://github.com/mishoo/UglifyJS) - 解析器/压缩器/美化器工具包

## Type Checkers (类型检查器)

* [TypeScript](https://www.typescriptlang.org/) - JavaScript 的类型化超集,可编译为通 JavaScript。
* [Flow.js](https://flow.org/) - Facebook 开发的 JavaScript 静态类型检查器。
* [Hegel](https://hegel.js.org/) - 偏向类型推断和强类型系统的 JavaScript 静态类型检查器。
* [TypL](https://github.com/getify/TypL) - 偏向类型推断的 JavaScript 类型检查器。
* [Hindley Milner Definitions](https://github.com/xodio/hm-def) - 使用类似 Haskell 的 Hindley Milner 类型签名对 JavaScript 函数进行运行时类型检查。

## Testing Frameworks (测试框架)

### Frameworks（框架）

* [mocha](https://github.com/mochajs/mocha) - 简单、灵活、有趣的 JavaScript 测试框架,用于 Node.js 和浏览器。
* [jasmine](https://github.com/jasmine/jasmine) - 无DOM的简单 JavaScript 测试框架。
* [qunit](https://github.com/jquery/qunit) - 一个易于使用的 JavaScript 单元测试框架。
* [jest](https://github.com/facebook/jest) - 简单的 JavaScript 单元测试框架。
* [prova](https://github.com/azer/prova) - 基于 Tape 和 Browserify 的 Node 和浏览器测试运行器
* [DalekJS](https://github.com/dalekjs/dalek) - 自动化的跨浏览器功能测试
* [Protractor](https://github.com/angular/protractor) - AngularJS 应用的端到端测试框架。
* [tape](https://github.com/substack/tape) - TAP 生产测试工具,适用于 node 和浏�������������������������
* [TestCafe](https://github.com/DevExpress/testcafe) - 现代 web 开发栈的自动化浏览器测试。
* [ava](https://github.com/avajs/ava) - 🚀 面向未来的 JavaScript 测试运行器
* [Cypress](https://www.cypress.io/) - 适用于浏览器及其他环境的完整端到端测试框架。
* [WebdriverI/O](https://webdriver.io/) - 下一代 Node.js 浏览器和移动测试框架
* [taiko](https://github.com/getgauge/taiko) - 用于自动化基于 Chromium 浏览器的 Node.js 库。
* [Playwright](https://github.com/microsoft/playwright) - 使用单一 API 自动化 Chromium、Firefox 和 WebKit 的 Node.js 库。

### Assertion (断言)

* [chai](https://github.com/chaijs/chai) - 可与任何测试框架配合使用的 BDD/TDD 断言库。
* [Enzyme](https://airbnb.io/enzyme/index.html) - React 的 JavaScript 测试工具，可以更容易地断言、操作和遍历 React 组件的输出。
* [react testing library](https://github.com/kentcdodds/react-testing-library) - 简单且完整的 React DOM 测试工具，鼓励良好的测试实践。
* [Sinon.JS](https://github.com/sinonjs/sinon) - JavaScript 的测试监视器、存根和模拟。
* [expect.js](https://github.com/Automattic/expect.js) - 适用于 Node.JS 和浏览器的简约 BDD 风格断言库。
* [proxyquire](https://github.com/thlorenz/proxyquire) - Node.js require 方法的存根。

### Coverage (代码覆盖)

* [istanbul](https://github.com/gotwarlost/istanbul) - 又一个 JavaScript 代码覆盖率工具。
* [blanket](https://github.com/alex-seville/blanket) - 一个简单的 JavaScript 代码覆盖率库，设计为易于安装和使用，适用于浏览器和 nodejs。
* [JSCover](https://github.com/tntim96/JSCover) - JSCover 是一个用于测量 JavaScript 程序代码覆盖率的工具。

### Runner（运行器）

* [phantomjs](https://github.com/ariya/phantomjs) - 可编程的无头 WebKit。
* [slimerjs](https://github.com/laurentj/slimerjs) - 一个类似 PhantomJS 的工具,运行在 Gecko 引擎上。
* [casperjs](https://github.com/casperjs/casperjs) - 用于 PhantomJS 和 SlimerJS 的导航脚本和测试工具。
* [zombie](https://github.com/assaf/zombie) - 使用 node.js 的超快速、全栈、无头浏览器测试。
* [totoro](https://github.com/totorojs/totoro) - 一个简单稳定的跨浏览器测试工具。
* [karma](https://github.com/karma-runner/karma) - 壮观的 JavaScript 测试运行器。
* [nightwatch](https://github.com/nightwatchjs/nightwatch) - 基于 node.js 和 selenium webdriver 的 UI 自动化测试框架。
* [intern](https://github.com/theintern/intern) - 下一代 JavaScript 代码测试栈。
* [puppeteer](https://github.com/GoogleChrome/puppeteer) - 由 Google Chrome 官方团队开发的无头 Chrome Node.js API。
* [webdriverio](https://github.com/webdriverio/webdriverio) - 下一代 Node.js 的 WebDriver 测试自动化框架。
* [taiko](https://github.com/getgauge/taiko) - 一个用于自动化基于 Chromium 浏览器的 Node.js 库。
* [Playwright](https://github.com/microsoft/playwright) - 使用单一 API 自动化 Chromium、Firefox 和 WebKit 的 Node.js 库。

## QA Tools (质量保证工具)

* [prettier](https://github.com/prettier/prettier) - Prettier 是一个固执己见的代码格式化工具。
* [JSHint](https://github.com/jshint/jshint/) - JSHint 是一个帮助检测 JavaScript 代码中的错误和潜在问题的工具。
* [jscs](https://github.com/jscs-dev/node-jscs) - JavaScript 代码风格检查器。
* [jsfmt](https://github.com/rdio/jsfmt) - 用于格式化、搜索和重写 JavaScript 代码。
* [jsinspect](https://github.com/danielstjules/jsinspect) - 检测复制粘贴和结构相似的代码。
* [buddy.js](https://github.com/danielstjules/buddy.js) - JavaScript 代码中的魔法数字检测。
* [ESLint](https://github.com/eslint/eslint) - 一个完全可插拔的用于识别和报告 JavaScript 中的模式的工具。
* [JSLint](https://github.com/douglascrockford/JSLint) - 高标准、严格且固执己见的��码质量工具,旨在只保留语言中好的部分。
* [JavaScript Standard Style](https://github.com/feross/standard) - 固执己见的零配置代码风格指南、风格检查器和格式化工具。
* [Pre-evaluate code at buildtime](https://github.com/kentcdodds/preval.macro) - 在构建时预评估前端 JavaScript 代码。
* [JS-Beautifier](https://github.com/beautify-web/js-beautify) - 用于格式化 JS 代码的 npm cli 和库。
* [husky](https://github.com/typicode/husky) - 防止糟糕的 git commit、git push 等操作。

## MVC Frameworks and Libraries (MVC 框架和库)

* [angular.js](https://github.com/angular/angular.js) - HTML 增强型 web 应用框架(已弃用)。
* [angular](https://github.com/angular/angular) - Angular 是一个使用 TypeScript/JavaScript 构建移动端和桌面 Web 应用的开发平台。
* [aurelia](http://aurelia.io) - 用于移动端、桌面和 Web 的 JavaScript 客户端框架。
* [backbone](https://github.com/jashkenas/backbone) - 为你的 JS 应用提供带有模型、视图、集合和事件的主干。
* [ember.js](https://github.com/emberjs/ember.js) - 用于创建雄心勃勃的 Web 应用的 JavaScript 框架。
* [meteor](https://github.com/meteor/meteor) - 超简单的、无处不在数据库、在线数据、纯 JavaScript 的 Web 框架。
* [ractive](https://github.com/ractivejs/ractive) - 新一代 DOM 操作库。
* [vue](https://github.com/vuejs/vue) - 用于构建用户界面的直观、快速和可组合的 MVVM 框架。
* [svelte](https://github.com/sveltejs/svelte) - 通过编译实现真正的响应式用户界面。
* [knockout](https://github.com/knockout/knockout) - Knockout 使用 MVVM 模式让 JavaScript UI 动态化。
* [spine](https://github.com/spine/spine) - 用于构建 JavaScript 应用的轻量级 MVC 库。
* [espresso.js](https://github.com/techlayer/espresso.js) - 用于制作用户界面的最小的 JavaScript 库。
* [canjs](https://github.com/canjs/canjs) - 可以让 JS 更好、更快、更简单的框架。
* [react](https://reactjs.org/) - 用于构建用户界面的库。
* [hyperapp](https://github.com/hyperapp/hyperapp) - 用于构建前端应用的微型框架。
* [preact](https://github.com/developit/preact) - React 的 3kb 轻量化替代方案,拥有相同的 ES6 API。
* [nativescript](https://github.com/NativeScript/NativeScript) - 使用 JavaScript 构建真正的原生跨平台 iOS 和 Android 应用。
* [react-native](https://github.com/facebook/react-native) - 用 React 构建原生应用的框架。
* [riot](https://github.com/riot/riot) - 类 React 库,但体积非常小。
* [thorax](https://github.com/walmartlabs/thorax) - 加强你的 Backbone。
* [chaplin](https://github.com/chaplinjs/chaplin) - 使用 Backbone.js 库的 JavaScript 应用架构。
* [marionette](https://github.com/marionettejs/backbone.marionette) - 一个 Backbone.js 的复合应用程序库。
* [ripple](https://github.com/ripplejs/ripple) - 一个小巧的、用于构建响应式视图的基础库。
* [rivets](https://github.com/mikeric/rivets) - 轻量级和强大的数据绑定和模板解决方案。
* [derby](https://github.com/derbyjs/derby) - MVC 框架,使编写实时协作应用变得容易。
* [way.js](https://github.com/gwendall/way.js) - 简单、轻量级、持久化的双向数据绑定。
* [mithril.js](https://github.com/lhorie/mithril.js) - Mithril 是一个客户端 MVC 框架(轻量级、健壮、快速)。
* [jsblocks](https://github.com/astoilkov/jsblocks) - jsblocks 是更好的 MV* 框架。
* [feathers](https://github.com/feathersjs/feathers) - 为未来的应用设计的极简实时 JavaScript 框架。
* [Keo](https://github.com/Wildhoney/Keo) - 支持 Shadow DOM 的函数式无状态 React 组件。
* [atvjs](https://github.com/emadalam/atvjs) - 使用纯 JavaScript 快速开发 Apple TV 应用。
* [Alpine.js](https://github.com/alpinejs/alpine) - 以更低成本��供��似 Vue 或 React 的��应��和��明���特���。
* [inferno](https://github.com/infernojs/inferno) - 🔥 一个极快的、类 React 的 JavaScript 库,用于构建现代用户界面。
* [FoalTS](https://foalts.org) - 优雅且全面的 Node.JS Web 框架(TypeScript)。
* [Lucia](https://github.com/aidenybai/lucia) - 3kb 的小型 Web 应用库。
* [Adonis](https://github.com/adonisjs/core) - 专注于开发人员体验、稳定性和信心的 Node.js Web 框架。
* [GrapesJS](https://github.com/artf/grapesjs) - 免费开���的 Web ��建器框架。下一代无需编码的模板构建工具。
* [Rete.js](https://github.com/retejs/rete) - 一个模块化的可视化编程框架,允许在浏览器中创建基于节点的编辑器。
* [litegraph.js](https://github.com/jagenjo/litegraph.js) - 类似 PD 或 UDK Blueprints 的图形节点引擎和编辑器,带有 HTML5 Canvas2D 编辑器。
* [Drawflow](https://github.com/jerosoler/Drawflow) - 让你能够轻松快速地创建数据流。
* [Blockly](https://github.com/google/blockly) - Google 开发的为 Web 和移动应用添加可视化代码编辑器的库。
* [Million](https://github.com/aidenybai/million) - <1kb 编译器驱动的虚拟 DOM。速度超快！
* [Whatsup](https://github.com/whatsup/whatsup) - 一个轻松开发模式的前端框架 🥤。基于生成器的 JSX 组件、快速类 mobx 状态管理和独特的 cssx 样式系统。
* [Remult](https://github.com/remult/remult) - 全栈 TypeScript 的 CRUD 框架。

## Node-Powered CMS Frameworks (基于 Node 的 CMS ��架)

* [KeystoneJS](https://github.com/keystonejs/keystone) - 强大的 CMS 和 Web 应用框架。
* [Reaction Commerce](https://github.com/reactioncommerce/reaction) - 响应式 CMS，实时架构和设计。
* [Ghost](https://github.com/tryghost/Ghost) - 简单而强大的发布平台。
* [Apostrophe](https://github.com/punkave/apostrophe) - 提供内容编辑和基础服务的 CMS。
* [We.js](https://github.com/wejs/we/) - 用于实时应用、网站或博客的框架。
* [Hatch.js](https://github.com/inventures/hatchjs) - 具有社交功能的 CMS 平台。
* [TaracotJS](https://github.com/xtremespb/taracotjs-generator/) - 基于 Node.js 的快速简约 CMS。
* [Nodizecms](https://github.com/nodize/nodizecms) - 为 CoffeeScript 爱好者设计的 CMS。
* [Cody](https://github.com/jcoppieters/cody) - 带有所见即所得编辑器的 CMS。
* [PencilBlue](https://github.com/pencilblue/pencilblue/) - CMS 和博客平台。
* [Strapi](https://github.com/strapi/strapi) - 开源的 Node.js Headless CMS，用于轻松构建可定制的 API。
* [Factor](https://github.com/fiction-com/factor) - JavaScript CMS。

## Templating Engines（模板引擎）

*Templating engines allow you to perform string interpolation.*

* [mustache.js](https://github.com/janl/mustache.js) - JavaScript 最简洁的模板语法实现。
* [handlebars.js](https://github.com/handlebars-lang/handlebars.js) - Mustache 模板语言的扩展。
* [nunjucks](https://mozilla.github.io/nunjucks/) - 丰富���强大的 JavaScript 模板语言。
* [hogan.js](https://github.com/twitter/hogan.js) - Mustache 模板语言的编译器。
* [doT](https://github.com/olado/doT) - 最快速简洁的 JavaScript 模板引擎。
* [dustjs](https://github.com/linkedin/dustjs/) - 适用于浏览器和 Node.js 的异步模板。
* [eco](https://github.com/sstephenson/eco/) - 嵌入式 CoffeeScript 模板。
* [JavaScript-Templates](https://github.com/blueimp/JavaScript-Templates) - 轻量级、快速且强大的 JavaScript 模板引擎。
* [t.js](https://github.com/jasonmoo/t.js) - 小巧的 JavaScript 模板框���,压缩后仅有 400 字节。
* [Pug](https://github.com/pugjs/pug) - 健壮、优雅且功能丰富的 Node.js 模板引擎。
* [EJS](https://github.com/mde/ejs) - 高效的 JavaScript 模板。
* [xtemplate](https://github.com/xtemplate/xtemplate) - 可扩展的模板引擎,支持 Node 和浏览器。
* [marko](https://github.com/marko-js/marko) - 快速、轻量级、基于 HTML 的模板引擎,支持异步、流式传输、自定义标签和 CommonJS 模块。

## Game Engines (游戏引擎)

* [A-Frame](https://aframe.io) - 用于构建 WebVR 的框架。
* [Cocos](https://www.cocos.com) - 开源跨平台游戏开发框架。
* [Impact](https://impactjs.com) - HTML5 Canvas 和 JavaScript 游戏引擎���
* [GDevelop](https://gdevelop.io) - 免费且易用的游戏制作应用。
* [Kaboom.js](https://kaboomjs.com) - 一个帮助你快速有趣地制作游戏的游戏编程库。
* [Matter.js](https://brm.io/matter-js) - 2D JavaScript 物理引��。
* [melonJS](https://melonjs.org) - 开源的 HTML5 ��戏引擎,让开发者和设计师专注于内容。
* [Phaser](https://phaser.io) - 快速、有趣且免费的开源 HTML5 游戏框架。
* [PixiJS](https://pixijs.com) - HTML5 创作引擎。
* [PlayCanvas](https://playcanvas.com) - WebGL 游戏引擎。

## Articles and Posts（文章与帖子）

* [The JavaScript that you should know](https://medium.com/@pedropolisenso/o-javasscript-que-você-deveria-conhecer-b70e94d1d706) - 关于 JavaScript 概念的文章。
* [JavaScript Modules: A Beginner's Guide](https://medium.freecodecamp.com/javascript-modules-a-beginner-s-guide-783f7d7a5fcc#.jw1txw6uh) - JavaScript 模块详解。
* [Understanding JavaScript Closures](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-closure-b2f0d2152b36#.4s2wtwc7i) - JavaScript 闭包概念解释。
* [JavaScript Design Patterns](https://medium.com/beginners-guide-to-mobile-web-development/javascript-design-patterns-25f0faaaa15) - JavaScript 设计模式。
* [This is how a developer goes about learning React](https://www.freecodecamp.org/news/this-is-how-a-developer-goes-about-learning-react-71b0e4e7a312/) - 如何学习 React 的建议。

## Data Visualization (数据可视化)

*用于网页的数据可视化工具*

* [d3](https://github.com/d3/d3) - 用于 HTML 和 SVG 的 JavaScript 可视化库。
* [metrics-graphics](https://github.com/mozilla/metrics-graphics) - 为简洁、原则性的数据图形和布局优化的库。
* [three.js](https://github.com/mrdoob/three.js) - JavaScript 3D 库。
* [Chart.js](https://github.com/chartjs/Chart.js) - 使用 &lt;canvas&gt; 标签的简单 HTML5 图表。
* [paper.js](https://github.com/paperjs/paper.js) - 矢量图形脚本的瑞士军刀 - Scriptographer 移植到 JavaScript 和浏览器,使用 HTML5 Canvas。
* [fabric.js](https://github.com/kangax/fabric.js) - JavaScript Canvas 库, SVG 转 Canvas (& Canvas 转 SVG) 解析器。
* [peity](https://github.com/benpickles/peity) - 渐进式 <svg> 条形图、折线图和饼图。
* [raphael](https://github.com/DmitryBaranovskiy/raphael) - JavaScript 矢量库。
* [echarts](https://github.com/apache/echarts) - 企业级图表库。
* [visjs](https://github.com/visjs) - 用于基于浏览器的动态数据可视化的多个库。
* [two.js](https://github.com/jonobr1/two.js) - 与渲染器无关的二维绘图 API。
* [g.raphael](https://github.com/DmitryBaranovskiy/g.raphael) - Raphaël 的图表库。
* [sigma.js](https://github.com/jacomyal/sigma.js) - 专注于图形绘制的 JavaScript 库。
* [arbor](https://github.com/samizdatco/arbor) - 使用 web workers 和 jQuery 的图形可视化库。
* [cubism](https://github.com/square/cubism) - D3 的插件,用于可视化时间序列。
* [dc.js](https://github.com/dc-js/dc.js) - 多维图表库,与 d3.js 配合使用。
* [vega](https://github.com/trifacta/vega) - 可视化语法。
* [envisionjs](https://github.com/HumbleSoftware/envisionjs) - 动态 HTML5 可视化。
* [rickshaw](https://github.com/shutterstock/rickshaw) - 用于创建交互式实时图表的 JavaScript 工具包。
* [flot](https://github.com/flot/flot) - 具有吸引力的 jQuery 图表库。
* [morris.js](https://github.com/morrisjs/morris.js) - 漂亮的时间序列线图。
* [nvd3](https://github.com/novus/nvd3) - 为 d3.js 构建可复用图��和图表组件��
* [svg.js](https://github.com/wout/svg.js) - 用于操作和动画 SVG 的轻量级库。
* [heatmap.js](https://github.com/pa7/heatmap.js) - 基于 HTML5 canvas 的热力图 JavaScript 库。
* [jquery.sparkline](https://github.com/gwatts/jquery.sparkline) - 一个 jQuery 插件,用于直接在浏览器中生成小型图表。
* [trianglify](https://github.com/qrohlf/trianglify) - 低多边形风格背景图形生成器。
* [d3-cloud](https://github.com/jasondavies/d3-cloud) - 在 JavaScript 中创建词云。
* [d4](https://github.com/heavysixer/d4) - 一个友好的可重用图表 DSL,基于 D3。
* [dimple.js](http://dimplejs.org) - 由 d3 驱动的简单业务分析图表。
* [chartist-js](https://github.com/gionkunz/chartist-js) - 简单的响应式图表。
* [epoch](https://github.com/epochjs/epoch) - 一个通用的实时图表库。
* [c3](https://github.com/c3js/c3) - 基于 D3 的可重用图表库。
* [BabylonJS](https://github.com/BabylonJS/Babylon.js) - 使用 HTML5 和 WebGL 构建 3D 游戏的框架。
* [recharts](https://github.com/recharts/recharts) - 使用 React 和 D3 重新定义的图表库。
* [GraphicsJS](https://github.com/AnyChart/GraphicsJS) - 具有直观 API 的轻量级 JavaScript 图形库。
* [mermaid](https://github.com/knsv/mermaid) - 从文本生成图表和流程图。
* [Frappe Charts](https://github.com/frappe/charts) - GitHub 启发的简单现代的 SVG 图表。
* [Frappe Gantt](https://github.com/frappe/gantt) - 简单、交互式、现代的甘特图库。
* [G2](https://github.com/antvis/G2) - 具有高度交互性的数据驱动的统计图表可视化语法。
* [G2Plot](https://github.com/antvis/G2Plot) - 交互式响应式图表库,基于图形语法。
* [Cytoscape.js](https://github.com/cytoscape/cytoscape.js) - 功能齐全的图论库。
* [cola.js](https://ialab.it.monash.edu/webcola/) - 使用基于约束的优化技术布局 HTML5 文档和图表的库。
* [jointjs](https://github.com/clientIO/joint) - 用于创建静态图表或完全交互式图表工具的图表库。
* [vizzu](https://github.com/vizzuhq/vizzu-lib) - 用于动画数据可视化和数据故事的库。

此外还有一些优秀的商业库,如 [amchart](https://www.amcharts.com/), [anychart](https://www.anychart.com/), [plotly](https://plotly.com/), 和 [lightning chart](https://www.arction.com/lightningchart-js/)。

## 大屏可视化适配

* [autofit.js](https://github.com/Auto-Plugin/autofit.js) - 一个用于大屏可视化适配的 JavaScript 库。
* [v-scale-screen](https://github.com/Alfred-Skyblue/v-scale-screen) - 一个用于大屏可视化适配的 Vue 组件。
* [fit-screen](https://github.com/jp-liu/fit-screen) - 一个用于大屏可视化适配的 React, Vue 组件。

## Timeline (时间轴)

* [TimelineJS v3](https://github.com/NUKnightLab/TimelineJS3) - 用 JavaScript 构建的故事时间轴。
* [timesheet.js](https://github.com/sbstjn/timesheet.js) - 用于简单 HTML5 & CSS3 时间表的 JavaScript 库。

## Spreadsheet (电子表格)

* [HANDSONTABLE](https://github.com/handsontable/handsontable) - Handsontable 是一个面向开发者的 JavaScript/HTML5 电子表格库。
* [Frappe Datatable](https://github.com/frappe/datatable) - Frappe DataTable 是一个简单、现代和交互式的数据表格库,用于显示表格数据。
* [Luckysheet](https://github.com/mengshukeji/Luckysheet) - Luckysheet 是一个类似 excel 的在线电子表格,功能强大、配置简单且完全开源。
* [Jspreadsheet CE](https://github.com/jspreadsheet/ce) - Jspreadsheet 是一个轻量级的原生 javascript 插件,用于创建与其他电子表格软件兼容的令人惊叹的 web 交互式表格和电子表格。
* [RevoGrid](https://github.com/revolist/revogrid) - RevoGrid 是一个快速、响应式的类 excel 数据网格库,用于现代 web 应用。

## Editors (编辑器)

* [ace](https://github.com/ajaxorg/ace) - Ace (Ajax.org Cloud9 编辑器)。
* [CodeMirror](https://github.com/codemirror/CodeMirror) - 浏览器内代码编辑器。
* [esprima](https://github.com/ariya/esprima) - 用于多用途分析的 ECMAScript 解析基础设施。
* [quill](https://github.com/quilljs/quill) - 具有 API 的跨浏览器富文本编辑器。
* [medium-editor](https://github.com/yabwe/medium-editor) - Medium.com 所见即所得编辑器克隆版。
* [pen](https://github.com/sofish/pen) - 享受实时编辑(支持 markdown)。
* [jquery-notebook](https://github.com/raphaelcruzeiro/jquery-notebook) - 一个简单、干净、优雅的文本编辑器。灵感来自 Medium 的出色设计。
* [bootstrap-wysiwyg](https://github.com/mindmup/bootstrap-wysiwyg) - 小巧的、兼容 bootstrap 的所见即所得富文本编辑器。
* [ckeditor-releases](https://github.com/ckeditor/ckeditor-releases) - 适用于所有人的最佳网页文本编辑器。
* [editor](https://github.com/lepture/editor) - Markdown 编辑器。
* [EpicEditor](https://github.com/OscarGodson/EpicEditor) - 可嵌入的 JavaScript Markdown 编辑器。
* [jsoneditor](https://github.com/josdejong/jsoneditor) - 用于查看、编辑和格式化 JSON 的 Web 工具。
* [vim.js](https://github.com/coolwanglu/vim.js) - 在 JavaScript 中实现的 Vim。
* [Squire](https://github.com/neilj/Squire) - HTML5 富文本编辑器。
* [TinyMCE](https://github.com/tinymce/tinymce) - JavaScript 富文本编辑器。
* [trix](https://github.com/basecamp/trix) - 用于日常写作的富文本编辑器。
* [Trumbowyg](https://github.com/Alex-D/Trumbowyg) - 一个轻量且惊人的所见即所得 JavaScript 编辑器。
* [Draft.js](https://github.com/facebook/draft-js) - 用于构建文本编辑器的 React 框架。
* [bootstrap-wysihtml5](https://github.com/jhollingworth/bootstrap-wysihtml5) - 简单、漂亮的所见即所得编辑器。
* [wysihtml5](https://github.com/xing/wysihtml5) - 基于 HTML5 和渐进增强方法的开源富文本编辑器。
* [raptor-editor](https://github.com/PANmedia/raptor-editor) - Raptor, 一个 HTML5 所见即所得内容编辑器！
* [popline](https://github.com/kenshin54/popline) - HTML5 富文本编辑器工具栏。
* [Summernote](https://github.com/summernote/summernote) - 超级简单的所见即所得编辑器。
* [Everright-formEditor](https://github.com/Liberty-liu/Everright-formEditor) - 可视化拖放低代码表单编辑器。
* [wangEditor](https://github.com/wangeditor-team/wangEditor) - 轻量级 web 富文本编辑器，配置方便，使用简单。支持 IE10+ 浏览器。

## Documentation（文档）

* [DevDocs](https://devdocs.io/) - 多个 API 文档的聚合器。
* [docco](https://github.com/jashkenas/docco) - 文学编程风格的文档生成器。
* [styledocco](https://github.com/jacobrask/styledocco) - 从样式表生成文档。
* [Ronn](https://github.com/rtomayko/ronn) - 构建手册。手册是用于 Unix 系统的文档。
* [dox](https://github.com/tj/dox) - Node.js 的 JavaScript 文档生成器。
* [jsdox](https://github.com/sutoiku/jsdox) - JSDoc3 到 Markdown 文档生成��。
* [ESDoc](https://github.com/esdoc/esdoc) - 针对 ES6 的优秀文档生成器。
* [YUIDoc](https://github.com/yui/yuidoc) - Node.js 应用的文档生成器��
* [coddoc](https://github.com/doug-martin/coddoc) - 可扩展的 Node.js 注释解析器/生成器。
* [sphinx-js](https://github.com/mozilla/sphinx-js) - Sphinx JSDoc 构建。
* [beautiful-docs](https://github.com/beautiful-docs/beautiful-docs) - 从 Markdown 文件生成漂亮的文档。
* [documentation.js](https://github.com/documentationjs/documentation) - API 文档生成器，支持 ES2015+ 和流注释。
* [jsdoc](https://github.com/jsdoc3/jsdoc) - JavaScript 的 API 文档生成器。
* [documentjs](https://github.com/bitovi/documentjs) - 优秀的 JS 文档引擎。
* [jsdoc-to-markdown](https://github.com/jsdoc2md/jsdoc-to-markdown) - 从 jsdoc 注释生成 markdown 文档。
* [swagger-ui](https://github.com/swagger-api/swagger-ui) - Swagger UI 是一个可以展示和编辑 Swagger/OpenAPI 规范的工具集合。
* [postman](https://www.getpostman.com/) - 用于 API 开发的完整工具链。

## Files（文件）

*用于处理文件的库*

* [Papa Parse](https://github.com/mholt/PapaParse) - 强大的 CSV 库,支持解析 CSV 文件/字符串以及导出为 CSV。
* [jBinary](https://github.com/jDataView/jBinary) - 用于二进制文件的高级 I/O(加载、��析、操作、序列化、保存),使用声明式语法来��述文��类型和数据结构。
* [diff2html](https://github.com/rtfpessoa/diff2html) - Git diff 输出解析器和漂亮的 HTML 生成器。
* [jsPDF](https://github.com/MrRio/jsPDF) - JavaScript PDF 生成。
* [PDF.js](https://github.com/mozilla/pdf.js) - JavaScript 实现的 PDF 阅读器。

## Functional Programming (函数式编程)

*扩展 JavaScript 函数式编程能力的库*

* [underscore](https://github.com/jashkenas/underscore) - JavaScript 的实用工具库。
* [lodash](https://github.com/lodash/lodash) - 提供一致性、自定义、性能和其他功能的实用工具库。
* [Sugar](https://github.com/andrewplummer/Sugar) - 用于处理原生对象的 JavaScript 库。
* [lazy.js](https://github.com/dtao/lazy.js) - 类似 Underscore，但更懒惰。
* [ramda](https://github.com/ramda/ramda) - 实用的 JavaScript 函数式编程库。
* [mout](https://github.com/mout/mout) - 模块化的 JavaScript 实用工具。
* [preludejs](https://github.com/alanrsoares/prelude-js) - JavaScript 硬核函数式编程。
* [rambda](https://github.com/selfrefactor/rambda) - *Ramda* 的更快更小的替代品。
* [fxts](https://github.com/marpple/FxTS) - 惰性求值和并发。
* [wild-wild-path](https://github.com/ehmicky/wild-wild-path) - 支持通配符和正则表达式的对象属性路径。
* [sweet-monads](https://github.com/JSMonk/sweet-monads) - 包含常用 monads 和惰性迭代器的实用工具库。

## Reactive Programming (响应式编程)

*扩展 JavaScript 响应式编程能力的库*

* [RxJS](https://github.com/ReactiveX/rxjs) - JavaScript 的响应式编程库。
* [Bacon](https://github.com/baconjs/bacon.js) - JavaScript 的函数响应式编程(FRP)库。
* [Kefir](https://github.com/pozadi/kefir) - 受 Bacon.js 和 RxJS 启发的 JavaScript FRP 库，专注于高性能和低内存消耗。
* [Highland](https://caolan.github.io/highland/) - 重新思考 JavaScript 实用工具库，Highland 使用标准 JavaScript 和类 Node 流轻松管理同步和异步代码。
* [Most.js](https://github.com/cujojs/most) - 高性能 FRP 库。
* [MobX](https://github.com/mobxjs/mobx) - 简单、可扩展的状态管理 TFRP 库。
* [Cycle.js](https://cycle.js.org) - 用于更清晰代码的函数式和响应式 JavaScript 库。
* [concent](https://github.com/concentjs/concent) - 绝对是最简单但最强大的 React 状态管理工具，它是可预测的、渐进式的和高效的。

## Data Structure (数据结构)

*用于构建更复杂应用的数据结构库*

* [immutable-js](https://github.com/facebook/immutable-js) - 不可变数据集合,包括 Sequence、Range、Repeat、Map、OrderedMap、Set 和稀疏 Vector。
* [mori](https://github.com/swannodette/mori) - 一个库,让你可以在原生 JavaScript 中使用 ClojureScript 的持久数据结构和支持 API。
* [buckets](https://github.com/mauriciosantos/Buckets-JS) - 完整的、经过充分测试和文档化的 JavaScript 数据结构库。
* [hashmap](https://github.com/flesler/hashmap) - 支持任何类型键的简单哈希映射实现。
* [ngraph.graph](https://github.com/anvaka/ngraph.graph) - JavaScript 中的图数据结构。
* [js-sdsl](https://github.com/zly201/js-sdsl) - 参考 C++ STL 实现的 JavaScript 标准数据结构库,支持 C++ 双向迭代器模式。

## Date (日期)

* [moment](https://github.com/moment/moment) - 在 JavaScript 中解析、验证、操作和显示日期。
* [moment-timezone](https://github.com/moment/moment-timezone) - moment.js 的时区支持。
* [jquery-timeago](https://github.com/rmm5t/jquery-timeago) - 一个 jQuery 插件,让显示模糊时间戳变得简单(如"4 分钟前")。
* [timezone-js](https://github.com/mde/timezone-js) - 支持时区的 JavaScript Date 对象。使用 Olson 时区数据。
* [date](https://github.com/MatthewMueller/date) - 人性化的 Date()。
* [ms.js](https://github.com/rauchg/ms.js) - 微小的毫秒转换工具。
* [countdown.js](https://github.com/gumroad/countdown.js) - 超级简单的倒计时。
* [timeago.js](https://github.com/hustcc/timeago.js) - 一个微小的库(小于 2kb),用于格式化日期显示为"*** 时间前"的形式。
* [fecha](https://github.com/taylorhakes/fecha) - 轻量级的日期格式化和解析库(~2KB)。旨在替代 moment.js 的解析和格式化功能。
* [date-fns](https://github.com/date-fns/date-fns) - 现代 JavaScript 日期工具库。
* [map-countdown](https://github.com/dawidjaniga/map-countdown) - 基于 Google Maps 构建的浏览器倒计时。
* [dayjs](https://github.com/iamkun/dayjs) - Day.js 是一个轻量的(2KB) JavaScript 日期库,API 与 Moment.js 兼容。
* [luxon](https://github.com/moment/luxon) - Luxon 是一个用于在 JavaScript 中处理日期和时间的库。
* [tempo](https://github.com/formkit/tempo) - 解析、格式化和时区处理 - Tempo 是一个用于原生 Date 对象的小型可摇树优化库。

## String (字符串)

* [voca](https://github.com/panzerdp/voca) - 终极 JavaScript 字符串库。
* [selecting](https://github.com/EvandroLG/selecting) - 一个允许你获取用户选择的文本的库。
* [underscore.string](https://github.com/epeli/underscore.string) - Underscore.js JavaScript 库的字符串操作扩展。
* [string.js](https://github.com/jprichardson/string.js) - 额外的 JavaScript 字符串方法。
* [he](https://github.com/mathiasbynens/he) - ��� JavaScript 编写的强大的 HTML 实体编码器/解码器。
* [multiline](https://github.com/sindresorhus/multiline) - JavaScript 中的多行字符串。
* [query-string](https://github.com/sindresorhus/query-string) - 解析和序列化 URL 查询字符串。
* [URI.js](https://github.com/medialize/URI.js/) - JavaScript URL 操作库。
* [jsurl](https://github.com/Mikhus/domurl) - 使用 JavaScript 进行轻量级 URL 操作。
* [sprintf.js](https://github.com/alexei/sprintf.js) - sprintf 的实现。
* [url-pattern](https://github.com/snd/url-pattern) - 比正则表达式更容易的 URL 和其他字符串的匹配模式。将字符串转换为数据或将数据转换为字符串。
* [plexis](https://github.com/plexis-js/plexis) - 低调但强大的社区驱动字符串操作库。
* [url-state-machine](https://github.com/anonrig/url-js) - 超快的符合规范的 URL 解析状态机,适用于 Node.js。

## Number (数字)

* [Numeral-js](https://github.com/adamwdraper/Numeral-js) - 用于格式化和操作数字的 JavaScript 库。
* [chance.js](https://github.com/chancejs/chancejs) - JavaScript 随机生成器助手。可以生成数字���字符串等。
* [odometer](https://github.com/HubSpot/odometer) - 平滑数字转换效果。
* [accounting.js](https://github.com/josscrowcroft/accounting.js) - 用于数字、货币和货币格式化的轻量级 JavaScript 库 - 完全本地化,零依赖。
* [money.js](https://github.com/josscrowcroft/money.js) - 一个微小的(1kb)JavaScript 货币转换库,适用于 web 和 nodeJS。
* [Fraction.js](https://github.com/infusion/Fraction.js) - JavaScript 的有理数库。
* [Complex.js](https://github.com/infusion/Complex.js) - JavaScript 的复数库。
* [Polynomial.js](https://github.com/infusion/Polynomial.js) - JavaScript 的多项式库。
* [Quaternion.js](https://github.com/infusion/Quaternion.js) - JavaScript 的四元数库。

## Storage (存储)

* [store.js](https://github.com/marcuswestin/store.js) - 所有浏览器的 LocalStorage 包装器,无需使用 cookie 或 flash。底层使用 localStorage、globalStorage 和 userData 行为。
* [localForage](https://github.com/mozilla/localForage) - 离线存储的改进版。包装了 IndexedDB、WebSQL 或 localStorage,提供简单但强大的 API。
* [jStorage](https://github.com/andris9/jStorage) - jStorage ��一个简单的键值对数��库,用于在浏览器端存储数据。
* [cross-storage](https://github.com/zendesk/cross-storage) - 跨域本地存储,带权限控制。
* [basket.js](https://github.com/addyosmani/basket.js) - 用于缓存和加载脚本的脚本和资源加载器。
* [bag.js](https://github.com/nodeca/bag.js) - 类似 basket.js 的缓存和资源加载器,但增加了键值接口和 localStorage/websql/indexedDB 支持。
* [basil.js](https://github.com/Wisembly/basil.js) - JavaScript 智能持久层缺失的部分。
* [jquery-cookie](https://github.com/carhartl/jquery-cookie) - 一个用于读写 cookie 的轻量级 jQuery 插件。
* [js-cookie](https://github.com/js-cookie/js-cookie) - 一个用于处理浏览器 cookie 的简单、轻量级的 JavaScript API。
* [Cookies](https://github.com/ScottHamper/Cookies) - JavaScript 客户端 Cookie 操作库。
* [DB.js](https://github.com/aaronpowell/db.js/) - 基于 Promise 的 IndexDB 包装库。
* [lawnchair.js](https://github.com/brianleroux/lawnchair/) - 简单的客户端 JSON 存储。
* [sql.js](https://github.com/kripken/sql.js) - 通过 Emscripten 编译成 JavaScript 的 SQLite。
* [pouchdb](https://github.com/pouchdb/pouchdb) - 受 Apache CouchDB 启发的 JavaScript 数据库,可以很好地运行在浏览器中。
* [crumbsjs](https://github.com/nirtz89/crumbsjs) - 轻量级的原生 ES6 cookies 和本地存储 JavaScript 库。
* [awesome-web-storage](https://github.com/softvar/awesome-web-storage) - 关于客户端存储你需要知道的一切。
* [datavore](https://github.com/StanfordHCI/datavore) - 一个用 JavaScript 编写的小型、快速的浏览器内数据库引擎。
* [Hoodie](https://github.com/hoodiehq/hoodie) - 离线优先的后端,可以在没有网络连接的情况下在浏览器中工作。
* [NeDB](https://github.com/louischatriot/nedb) - 用于浏览器和 nw.js、electron 的嵌入式持久数据库。
* [Lovefield](https://google.github.io/lovefield) - Lovefield 是 Google 开发的用于 web 应用的关系数据库。
* [Dexie.js](https://github.com/dexie/Dexie.js) - Dexie.js 是 indexedDB 的包装库。
* [proxy-web-storage](https://github.com/KID-joker/proxy-web-storage) - 保持存储值类型不变并直接更改数组和对象。支持监听变化和设置过期时间。
* [PostgreSQL Browser](https://github.com/datawan-labs/pg) - 浏览器 PostgreSQL 游乐场,无服务器,仅客户端和 pglite (postgresql wasm)。

## Scroll (滚动)

* [scrollMonitor](https://github.com/stutrek/scrollMonitor) - 简单快速的 API 用于监控元素的滚动。
* [headroom](https://github.com/WickyNilliams/headroom.js) - 给你的页���一些空间。在需要时隐藏你的页眉。
* [onepage-scroll](https://github.com/peachananr/onepage-scroll) - 创建类似 Apple 的单页滚动网站。
* [iscroll](https://github.com/cubiq/iscroll) - iScroll 是一个高性能、小巧、无依赖、多平台的 JavaScript 滚动器。
* [skrollr](https://github.com/Prinzhorn/skrollr) - 独立的视差滚动库,适用于移动设备(Android + iOS)和桌面。无需 jQuery。
* [parallax](https://github.com/wagerfield/parallax) - 对智能设备方向做出反应的视差引擎。
* [stellar.js](https://github.com/markdalgleish/stellar.js) - 轻松实现视差滚动。
* [plax](https://github.com/cameronmcefee/plax) - jQuery 驱动的视差效果。
* [jparallax](https://github.com/stephband/jparallax) - 用于创建交互式视差效果的 jQuery 插件。
* [fullPage](https://github.com/alvarotrigo/fullPage.js) - 简单易用的插件用于创建全屏滚动网站。
* [ScrollMenu](https://github.com/s-yadav/ScrollMenu) - 一个新界面替代旧的无聊滚动条。
* [Clusterize.js](https://github.com/NeXTs/Clusterize.js) - 用于轻松显示大数据集的小型原生 JS 插件。
* [simpleParallax](https://github.com/geosigno/simpleParallax) - 用于为任何图像添加视差���画的���单小型 JavaScript 库。
* [rellax](https://github.com/dixonandmoe/rellax) - 轻量级、原生 JavaScript 视差库。
* [asscroll](https://github.com/ashthornton/asscroll) - 混合平滑滚动设置,结合了虚拟滚动的性能优势和原生滚动的可靠性。
* [stroll](https://github.com/hakimel/stroll.js) - CSS 列表滚动效果的集合。
* [locomotive-scroll](https://github.com/locomotivemtl/locomotive-scroll) - 检测视口中的元素并实现平滑���动和视差效果��
* [elevator.js](https://github.com/tholman/elevator.js) - 一个"返回顶部"按钮,行为就像真正的电梯。

## Menu (菜单)

* [jQuery-menu-aim](https://github.com/kamens/jQuery-menu-aim) - 当用户的光标瞄准特定下拉菜单项时触发事件的 jQuery 插件。
* [jQuery contextMenu](https://github.com/swisnl/jQuery-contextMenu) - 上下文菜单管理器。
* [Slideout](https://github.com/mango/slideout) - 适用于移动���络应用的响应式触摸滑出式导航菜单。
* [Slide and swipe](https://github.com/JoanClaret/slide-and-swipe-menu) - 与 touchSwipe 库配合使用的滑动菜单。
* [mmenu](https://github.com/FrDH/jQuery.mmenu) - 最好的 jQuery ���件,用于创建类似应用程序的开关式菜单。

## Table/Grid (表格/网格)

* [jTable](https://github.com/hikalkan/jtable) - 一个基于 AJAX 的 CRUD 表格 jQuery 插件。
* [DataTables](https://www.datatables.net/) - (jQuery 插件)一个高度灵活的工具,基于渐进增强的基础,为任何 HTML 表格添加高级交互控件。
* [Tabulator](http://olifolkerd.github.io/tabulator/) - (jQuery 插件)一个极其灵活的库,可以从任何 JSON 数据源或现有 HTML 表格创建具有一系列交互功���的表格。
* [Bootstrap Table](https://bootstrap-table.com/) - Bootstrap 框架的扩展,用于创建适合您网站风格的表格。
* [floatThead](https://github.com/mkoryak/floatThead) - (jQuery 插件)在滚动表格主体时锁定任何表格的表头。
* [Masonry](https://masonry.desandro.com/) - 级联网格布局库。
* [Packery](https://packery.metafizzy.co/) - 使用装箱算法的网格布局库。支持拖拽布局。
* [Isotope](https://isotope.metafizzy.co/) - 可过滤、可排序的网格布局库。可以实现 Masonry、Packery 等布���。
* [flexboxgrid](https://github.com/kristoferjoseph/flexboxgrid/) - 基于 CSS3 flexbox 的网格。

## Frameworks (框架)

* [Semantic UI](https://semantic-ui.com/) - 具有大量���题和元素的 UI 工具包。
* [w2ui](http://w2ui.com/) - 一套用于数据驱动的 web 应用前端开发的 jQuery 插件。
* [fluidity](https://github.com/mrmrs/fluidity) - 世界上最小的完全响应式 CSS 框架。
* [Ink](https://github.com/sapo/Ink) - SAPO 使用的 HTML5/CSS3 框架,用于快速高效的网站设计和原型开发。
* [DataFormsJS](https://github.com/dataformsjs/dataformsjs) - 用于快速开发网站和单页应用的最小 JavaScript 框架和独立组件。
* [Next.js](https://github.com/vercel/next.js) - React 框架，用于生产环境的全栈开发，支持SSR/SSG/ISR等渲染方式。
* [Nuxt.js](https://github.com/nuxt/nuxt) - Vue.js 的通用应用框架，支持服务端渲染、静态站点生成等多种渲染模式。
* [Remix](https://github.com/remix-run/remix) - 全栈 Web 框架，专注于网页基础和 Web 标准。
* [SvelteKit](https://github.com/sveltejs/kit) - Svelte 的应用框架，用于构建高性能 web 应用。
* [Astro](https://github.com/withastro/astro) - 现代化的静态站点构建工具，支持多框架组件集成。
* [Qwik](https://github.com/BuilderIO/qwik) - 新一��前端框架，专注于即时交互性和性能优化。
* [Solid Start](https://github.com/solidjs/solid-start) - SolidJS 的全栈 Web 框架。
* [Blitz.js](https://github.com/blitz-js/blitz) - 全栈 React 框架，构建于 Next.js 之上。
* [RedwoodJS](https://github.com/redwoodjs/redwood) - 全栈 JAMstack 框架，整合了 React、GraphQL、Prisma 等技术。

## Boilerplates (样板文件)

* [html5-boilerplate](https://github.com/h5bp/html5-boilerplate) - 用于构建快速、健壮和适应性强的 web 应用或网站的专业前端模板。
* [mobile-boilerplate](https://github.com/h5bp/mobile-boilerplate) - 帮助你构建快速、现代化移动 web 应用的前端模板。
* [webplate](https://github.com/chrishumboldt/webplate) - 一个很棒的前端框架,让你专注于构建网站或应用,同时保持使用简单。
* [Cerberus](https://github.com/TedGoas/Cerberus) - 一些简单但可靠的响应式 HTML 邮件模板。即使在 Outlook 中也能正常工作。
* [full-page-intro-and-navigation](https://github.com/CodyHouse/full-page-intro-and-navigation) - 一个带有全宽背景图片、粗体动画菜单和类似 iOS 的导航模糊效果的���绍页面。
* [Fluid-Squares](https://github.com/crozynski/Fluid-Squares) - 流体正方形单元网格。
* [Mobile-First-RWD](https://github.com/bradfrost/Mobile-First-RWD) - 移动优先的响应式网页设计示例。
* [this-is-responsive](https://github.com/bradfrost/this-is-responsive) - 这就是响应式设计。
* [npm run-scripts](https://gist.github.com/addyosmani/9f10c555e32a8d06ddb0) - 使用 NPM run-scripts 实现任务自动化。
* [Wasp](https://github.com/wasp-lang/wasp) - Wasp 是一个声明式的领域特定语言,用于使用更少的代码开发、构建和部署现代 JavaScript 全栈 web 应用。

## Images (图片)

* [Drift](https://github.com/imgix/drift) - 轻松为网站图片添加"悬停缩放"功能。轻量级、无依赖的 JavaScript。
* [Magnificent.js](https://github.com/AndersDJohnson/magnificent.js) - 响应式缩放图片等,基于 jQuery。
* [Panolens.js](https://github.com/pchen66/panolens.js) - 基于事件驱动和 WebGL 的全景查看器。轻量级且灵活。

## Gesture (手势)

* [hammer.js](https://github.com/hammerjs/hammer.js) - 用于多点触控手势的 JavaScript 库。
* [touchemulator](https://github.com/hammerjs/touchemulator) - 在桌面端模拟触摸输入。
* [Dragula](https://github.com/bevacqua/dragula/) - 超简单的拖放功能实现。

## Maps

* [Leaflet](https://github.com/Leaflet/Leaflet) - 用于移动友好的交互式地图的 JavaScript 库。
* [Cesium](https://github.com/AnalyticalGraphicsInc/cesium) - 开源的 WebGL 虚拟地球和地图引擎。
* [gmaps](https://github.com/HPNeo/gmaps) - 使用 Google Maps 的最简单方法。
* [polymaps](https://github.com/simplegeo/polymaps) - 一个免费的 JavaScript 库,用于在现代浏览器制作动态交式地图。
* [kartograph.js](https://github.com/kartograph/kartograph.js) - Kartograph SVG 地图的开源 JavaScript 渲染器。
* [mapbox.js](https://github.com/mapbox/mapbox.js) - Mapbox JavaScript API, 一个 Leaflet 插件。
* [jqvmap](https://github.com/manifestinteractive/jqvmap) - jQuery 矢量地图库。
* [OpenLayers3](https://openlayers.org/) - 高性能、功能丰富的地图库。
* [H3js](https://github.com/uber/h3) - Uber 开发的用于地理空间可视化的六边形分层地理空间索引系统。
* [AMap](https://lbs.amap.com/api/javascript-api/summary) - 高德地图 JavaScript API，提供了丰富的地图功能，包括地图展示、定位、搜索、路线规划等。

## Video/Audio (视频/音频)

* [prettyembed.js](https://github.com/mike-zarandona/prettyembed.js) - 更漂亮的 YouTube 嵌入 - 具有高分辨率预览图像、嵌入选项的高级自定义等功能。
* [Play-em JS](https://github.com/adrienjoly/playemjs) - 管理音乐/视频播放队列的 JavaScript 组件。
* [polyplayer](https://github.com/Acconut/polyplayer) - 用统一的 API 控制 YouTube、Soundcloud 和 Vimeo 播放器。
* [flowplayer](https://github.com/flowplayer/flowplayer) - 用于网页的 HTML5 视频播放器。
* [mediaelement](https://github.com/johndyer/mediaelement) - HTML5 音频或视频播放器。
* [SoundJS](https://github.com/CreateJS/SoundJS) - 简化在网页上处理音频的库。
* [video.js](https://github.com/videojs/video.js) - 开源的 HTML5 和 Flash 视频播放器。
* [FitVids.js](https://github.com/davatron5000/FitVids.js) - 用于流式视频嵌入的轻量级 jQuery 插件。
* [Ion.Sound](https://github.com/IonDen/ion.sound) - 在任何网页上播放简单的声音。
* [photobooth-js](https://github.com/WolframHempel/photobooth-js) - 允许用户在您的网站上拍摄头像照片的小部件。
* [clappr](https://github.com/clappr/clappr) - 可扩展的网页媒体播放器。
* [ts-audio](https://github.com/EvandroLG/ts-audio) - 用于处理 AudioContext API 的简单易用库。
* [AmplitudeJS](https://521dimensions.com/open-source/amplitudejs) - 开源的 HTML5 网页音频库。
* [ractive-player](https://github.com/ysulyma/ractive-player) - 用于在 React.js 中制作交互式视频的库。
* [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) - 为浏览器使用优化的 FFmpeg。
* [flv.js](https://github.com/bilibili/flv.js) - 纯 JavaScript 编写的 HTML5 Flash 视频播放器。
* [hls.js](https://github.com/video-dev/hls.js) - 实现 HTTP Live Streaming 客户端的 JavaScript 库。

## Typography (排版)

* [FlowType.JS](https://github.com/simplefocus/FlowType.JS) - 最佳的 Web 排版:基于元素宽度的字体大小和行高。
* [BigText](https://github.com/zachleat/BigText) - jQuery 插件,计算字体大小和字间距以匹配特定宽度的文本行。
* [circletype](https://github.com/peterhry/circletype) - 一个让网页文字呈现曲线效果的 jQuery 插件。
* [slabText](https://github.com/freqDec/slabText/) - 用于生成大胆响应式标题的 jQuery 插件。
* [simple-text-rotator](https://github.com/peachananr/simple-text-rotator) - 为��站添加超级简单的文字轮播效果。
* [novacancy.js](https://github.com/chuckyglitch/novacancy.js) - 文字霓虹金效果 jQuery 插件。
* [jquery-responsive-text](https://github.com/ghepting/jquery-responsive-text) - 让你的文字大小响应式化！
* [FitText.js](https://github.com/davatron5000/FitText.js) - 用于网页文字自适应的 jQuery 插件。
* [Lettering.js](https://github.com/davatron5000/Lettering.js) - 一个轻量级、易用的 JavaScript `<span>` 注入器,用于激进的 Web 排版。

## Animations (动画)

* [velocity](https://github.com/julianshapiro/velocity) - 加速的 JavaScript 动画。
* [jquery.transit](https://github.com/rstacruz/jquery.transit) - 用于 jQuery 的超平滑 CSS3 变换和过渡。
* [bounce.js](https://github.com/tictail/bounce.js) - 快速创建漂亮的 CSS3 动画。
* [GreenSock-JS](https://github.com/greensock/GreenSock-JS) - 适用于所有主流浏览器的高性能 HTML5 动画。
* [TransitionEnd](https://github.com/EvandroLG/transitionEnd) - 跨浏览器的过渡事件处理库。
* [Dynamic.js](https://github.com/michaelvillar/dynamics.js) - 基于物理的 CSS 动画 JavaScript 库。
* [the-cube](https://github.com/pstadler/the-cube) - CSS3 过渡效果实��。
* [Effeckt.css](https://github.com/h5bp/Effeckt.css) - 高性能过渡和动画库。
* [animate.css](https://github.com/daneden/animate.css) - 跨浏览器的 CSS 动画库。使用简单如同简单的事情。
* [textillate](https://github.com/jschr/textillate) - CSS3 文字动画简单插件。
* [move.js](https://github.com/visionmedia/move.js) - 基于 CSS3 的 JavaScript 动画框架。
* [animatable](https://github.com/LeaVerou/animatable) - 一个属性,两个值,无限可能。
* [shuffle-images](https://github.com/peachananr/shuffle-images) - 以创意方式切换图片的最简单方法。
* [smoothState.js](https://github.com/miguel-perez/smoothState.js) - 使用 jQuery 实现无干扰的页面过渡。
* [Anime.js](https://animejs.com/) - JavaScript 动画引擎。
* [Mo.js](https://mojs.github.io/) - 网页运动图形工具带。
* [particles.js](https://github.com/VincentGarreau/particles.js) - 用于创建粒子的轻量级 JavaScript 库。
* [tsParticles](https://github.com/matteobruni/tsparticles) - particles.js 的改进版本,修复了 bug 并添加了许多新功能。
* [particles-bg](https://github.com/lindelof/particles-bg) - 轻量级的 React 粒子动画背景组件。
* [barbajs](https://github.com/barbajs/barba) - 帮助你创建网站页面之间流畅平滑的过渡。
* [typicaljs](https://github.com/camwiegert/typical) - ~400 字节 🐡 的 JavaScript 打字动画。
* [AutoAnimate](https://auto-animate.formkit.com) - 只需一行代码即可为应用添加动效。
* [GSAP](https://github.com/greensock/GSAP) - 专业级的 JavaScript 动画库,提供流畅的���性能动画效果��
* [Lottie](https://github.com/airbnb/lottie-web) - Airbnb 开源的轻量级动画库,可以渲染 After Effects 动画。
* [wow.js](https://github.com/matthieua/WOW) - 当元素滚动到视图中时展现动画效果。与 animate.css 完美配合。
* [aos.js](https://github.com/michalsnik/aos) - 用于创建响应式网站的轻量级库,提供平滑的滚动和动画效果。

## Image Processing (图像处理)

* [lena.js](https://github.com/davidsonfellipe/lena.js) - 带有滤镜和实用功能的图像处理库。
* [pica](https://github.com/nodeca/pica) - 高质量图像缩放(使用纯 JS 实现的快速 Lanczos 滤镜)。
* [cropper](https://github.com/fengyuanchen/cropper) - 简单的 jQuery 图像裁剪插件。

## ES6 (ES6)

* [es6features](https://github.com/lukehoban/es6features) - ECMAScript 6 特性概述。
* [es6-features](https://github.com/rse/es6-features) - ECMAScript 6: 特性概述和比较。
* [es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet) - ES2015 [ES6] 速查表,包含提示、技巧、最佳实践和代码片段。
* [ECMAScript 6 compatibility table](https://compat-table.github.io/compat-table/es6/) - 各种环境下 ECMAScript 6 特性的兼容性表格。
* [Babel](https://github.com/babel/babel) - 将 ES6+ 代码转换为普通的 ES5 代码,无需运行时。
* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 特性转换为 ES5。包括类、生成器、Promise、解构模式、默认参数等。

## Canvas (画布)

* [Fabric.js](https://github.com/fabricjs/fabric.js) - 强大的 JavaScript Canvas 库,让处理 HTML5 画布变得简单。
* [Paper.js](https://github.com/paperjs/paper.js) - 矢量图形脚本的瑞士军刀,基于 HTML5 Canvas。
* [Konva.js](https://github.com/konvajs/konva) - HTML5 Canvas JavaScript 框架,用于桌面和移动应用。
* [Two.js](https://github.com/jonobr1/two.js) - 面向现代 web 浏览器的二维绘�� API。
* [Rough.js](https://github.com/rough-stuff/rough) - 创建手绘风格图形的 Canvas 库。
* [p5.js](https://github.com/processing/p5.js) - 用于创意编码的 JavaScript 库,让艺术家和设计师能够编程。
* [Pts.js](https://github.com/williamngan/pts) - 用于可视化和创意编码的库。
* [Pencil.js](https://github.com/pencil-js/pencil.js) - 漂亮的模块化 2D 绘图库。
* [Ocanvas](https://github.com/koggdal/ocanvas) - JavaScript 库,让 HTML5 Canvas 更加面向对象。
* [EaselJS](https://github.com/CreateJS/EaselJS) - 让在 HTML5 Canvas 上工作变得更简单的库。
* [PixiJS](https://github.com/pixijs/pixijs) - 快速的 2D 渲染引擎,使用 WebGL,支持 canvas 回退。
* [ZRender](https://github.com/ecomfe/zrender) - 轻量级的 Canvas 类库,提供 2D 绘制能力。

## Flow（流程）

* [Flowbite](https://github.com/themesberg/flowbite-svelte) - 一个基于 Tailwind CSS 的组件库，用于构建现代、响应式的网页。
* [Mermaid](https://github.com/mermaid-js/mermaid) - 以类似 Markdown 的文本语法生成流程图和图表。
* [GoJS](https://github.com/NorthwoodsSoftware/GoJS) - 功能丰富的交互式流程图、组织结构图等图表库。
* [JointJS](https://github.com/clientIO/joint) - 用于创建静态和交互式图表的强大工具。
* [Drawflow](https://github.com/jerosoler/Drawflow) - 简单的流程图库,让你能够轻松快速地创建数据流。
* [Dagre](https://github.com/dagrejs/dagre) - 有向图布局的 JavaScript 库。
* [Flowchart.js](https://github.com/adrai/flowchart.js) - 从文本描述生成流程图的库。
* [js-sequence-diagrams](https://github.com/bramp/js-sequence-diagrams) - 从文本生成 UML 序列图。
* [D3.js](https://github.com/d3/d3) - 用于创建数据可视化和流程图的强大库。
* [Vue Flow](https://github.com/bcakmakoglu/vue-flow) - Vue.js 的流程图组件库。
* [React Flow](https://github.com/wbkd/react-flow) - React 的高度定制化流程图库。
* [X6](https://github.com/antvis/X6) - 蚂蚁集团开源的图编辑引擎。
* [Butterfly](https://github.com/alibaba/butterfly) - 阿里巴巴��源的基于 JavaScript/React 的流程图组件。
* [bpmn-js](https://github.com/bpmn-io/bpmn-js) - BPMN 2.0 流程图渲染和编辑工具。

## Generators

* [Gatsby.js](https://github.com/gatsbyjs/gatsby) - 基于 React 的静态站点生成器。
* [Gridsome](https://github.com/gridsome/gridsome) - Vue 驱动的静态站点生成器。
* [Docusaurus](https://github.com/facebook/docusaurus) - Facebook 开发的基于 React 的静态站点生成器,适合内容��中心的网站。
* [Next.js](https://github.com/vercel/next.js) - React 驱动的静态站点生成器,"让 Web 更快的所有工具"。
* [Lume](https://github.com/lumeland/lume) - Deno 的静态站点生成器。

## SDK (软件开发工具包)

* [javascript-sdk-design](https://github.com/huei90/javascript-sdk-design) - 从工作和人验中取的 JavaScript SDK 设计指南。
* [Spotify SDK](https://github.com/loverajoel/spotify-sdk) - 用于处理 Spotify Web API 的面向实体的 SDK。
* [Square Node.js SDK](https://github.com/square/connect-nodejs-sdk/) - Square 支付和其他 API 的 JavaScript 客户端库。

## Full Text Search

* [lunr](https://github.com/olivernn/lunr.js) - 浏览器端的库,为 JSON 文档建立索引并提供简单的搜索接口。
* [flexsearch](https://github.com/nextapps-de/flexsearch) - 下一代浏览器和 Node.js 的全文搜索库。
* [Elasticlunr](https://github.com/weixsong/elasticlunr.js) - 基于 lunr.js,但更灵活和可定制。

## Translate（翻译）

* [translate.js](https://github.com/xnx3/translate) 两行 JS 实现 HTML 全自动翻译。无需改动页面、无语言配置文件、无 API Key、对 SEO 友好！
* [i18next](https://github.com/i18next/i18next) - 国际化(i18n)的 JavaScript 实现,简单易用。
* [vue-i18n](https://github.com/kazupon/vue-i18n) - Vue.js 的国际化插件。
* [react-intl](https://github.com/formatjs/react-intl) - React 组件的国际化。
* [polyglot](https://github.com/airbnb/polyglot.js) - 小巧的 i18n 助手库,带有友好的 API。
* [ttag](https://github.com/ttag-org/ttag) - 基于 ES6 标记模板的现代 JavaScript i18n 本地化库。
* [jquery.i18n](https://github.com/wikimedia/jquery.i18n) - jQuery 国际化插件。
* [google-translate-api](https://github.com/matheuss/google-translate-api) - 免费和无限制的 Google 翻译 API。
* [translatte](https://github.com/extensionsapp/translatte) - 使用 Google 翻译进行翻译的 JavaScript 库。
* [node-translate](https://github.com/moimikey/node-translate) - 简单的 Google 翻译 CLI 工具。
* [deepl-translator](https://github.com/vsetka/deepl-translator) - DeepL 翻译 API 的非官方 Node.js 库。
* [Rosetta](https://github.com/lukeed/rosetta) - 轻量级的国际化工具。
* [Globalize](https://github.com/globalizejs/globalize) - 一个支持多语言、本地化和格式化的 JavaScript 库。
* [Fluent.js](https://github.com/projectfluent/fluent.js) - Mozilla 的本地化系统。
* [Lingui](https://github.com/lingui/js-lingui) - JavaScript 的无缝国际化。

## OCR（光学字符识别）

* [Tesseract.js](https://github.com/naptha/tesseract.js) - 纯 JavaScript 实现的 OCR 引擎,支持超过100种语言。
* [OCRAD.js](https://github.com/antimatter15/ocrad.js) - 通过 Emscripten 将 OCR 引擎编译为 JavaScript。
* [tracking.js](https://github.com/eduardolundgren/tracking.js) - 一个现代的网页计算机视觉库,包含文字识别功能。
* [node-tesseract-ocr](https://github.com/zapolnoch/node-tesseract-ocr) - Node.js 的 Tesseract OCR 封装。
* [jimp](https://github.com/oliver-moran/jimp) - 纯 JavaScript 图像处理库,可用于 OCR 预处理。
* [OCR.space](https://github.com/JaidedAI/EasyOCR) - 提供 API 的在线 OCR 服务。
* [PaddleOCR.js](https://github.com/paddlepaddle/paddleocr) - 基于 PaddlePaddle 的高性能 OCR 工具包的 JavaScript 版本。
* [TensorFlow.js OCR](https://github.com/tensorflow/tfjs-examples/tree/master/mnist) - 使用 TensorFlow.js 实现的手写数字识别。
* [GOCR.js](https://github.com/antimatter15/gocr.js) - 将 GOCR 编译到 JavaScript。
* [Tess.js](https://github.com/naptha/tess.js) - 基于 Emscripten 的 Tesseract OCR 引擎的 JavaScript 移植版。

## Misc (杂项)

* [echo](https://github.com/toddmotto/echo) - 使用 data-* 属性实现图片懒加载。
* [picturefill](https://github.com/scottjehl/picturefill) - 响应式图片的 polyfill,支持 &lt;picture&gt;、srcset、sizes。
* [platform.js](https://github.com/bestiejs/platform.js) - 适用于几乎所有 JavaScript 平台的平台检测库。
* [json3](https://github.com/bestiejs/json3) - 与几乎所有 JavaScript 平台兼容的现代 JSON 实现。
* [Logical Or Not](https://gabinaureche.com/logicalornot/) - 关于 JavaScript 特性的小游戏。
* [BitSet.js](https://github.com/infusion/BitSet.js) - JavaScript 位向量实现。
* [spoiler-alert](https://github.com/joshbuddy/spoiler-alert) - 剧透警告！一个用于在网站上隐藏剧透内容的 jQuery 插件。
* [jquery.vibrate.js](https://github.com/illyism/jquery.vibrate.js) - 振动 API 封装。
* [list.js](https://github.com/javve/list.js) - 为表格、列表和各种 HTML 元素添加搜索、排序、过滤和灵活性。设计为无感知并适用于现有 HTML。
* [mixitup](https://github.com/patrickkunka/mixitup) - 过滤和排序插件。
* [grid](https://github.com/hootsuite/grid) - 用于二维、可调整大小和响应式列表的拖放库。
* [jquery-match-height](https://github.com/liabru/jquery-match-height) - 一个响应式等高插件。
* [SurveyJS](https://github.com/surveyjs/survey-library) - JavaScript 调查和表单库。
* [Array Explorer](https://github.com/sdras/array-explorer) 和 [Object Explorer](https://objectexplorer.netlify.app/) - 帮助确定在任何给定时间使用哪种原生 JavaScript 方法的��源。
* [Clipboard.js](https://clipboardjs.com/) - "Copy to clipboard" without Flash or use of Frameworks.
* [ky](https://github.com/sindresorhus/ky) - 基于浏览器 Fetch API 的小巧优雅的 HTTP 客户端。
* [Fcal](https://github.com/5anthosh/fcal) - 数学表达式计算器。
* [emoji-button](https://github.com/joeattardi/emoji-button) - 原生 JavaScript emoji 选择器组件。
* [iooxa](https://github.com/iooxa/article) - 用于交互式科学写作、响应式文档和可探索解释的组件。
* [Idyll](https://github.com/idyll-lang/idyll) - 创建可探索的解释和交互式故事文章。可以[嵌入 HTML](https://github.com/idyll-lang/idyll-embed)。
* [javascript-algorithms](https://github.com/trekhleb/javascript-algorithms) - JavaScript 实现的算法和数据结构,包含解释和进一步阅读的链接。
* [FingerprintJS](https://github.com/fingerprintjs/fingerprintjs) - 从浏览器指纹创建访问者标识符,在隐身模式下和清除浏览器数据时保持不变。
* [Peg.js](https://github.com/pegjs/pegjs) - 简单的 JavaScript 解析器生成器,生成具有出色错误报告的快速解析器。可以在浏览器、命令行或通过 JavaScript API 使用。
* [lune](https://github.com/ryanseys/lune) - 准确计算月相的库。
* [jsemu](https://github.com/fcambus/jsemu) - 用 JavaScript 编写的模拟器列表。

## Danmaku (弹幕)

* [CommentCoreLibrary](https://github.com/jabbany/CommentCoreLibrary) - JavaScript 弹幕引擎核心,提供从基本的弹幕显示到高级弹幕操作的支持。
* [danmaku](https://github.com/weizhenye/danmaku) - 高性能的 JavaScript 弹幕引擎。
* [danmu](https://github.com/imtaotao/danmu) - 轻量级的弹幕库,支持多种弹幕类型和自定义样式。
* [DanmuPlayer](https://github.com/chiruom/DanmuPlayer) - HTML5 视频播放器弹幕插件。
* [Barrager.js](https://github.com/yaseng/jquery.barrager.js) - 专注于网页弹幕效果的 jQuery 插件。
* [Barrage](https://github.com/parksben/barrage) - 基于 Canvas 的弹幕组件。
* [vue-danmaku](https://github.com/hellodigua/vue-danmaku) - Vue 的弹幕组件。
* [react-danmaku](https://github.com/zerosoul/react-danmaku) - React 的弹幕组件。
* [danmu.js](https://github.com/bytedance/danmu.js) - 字节跳动开源的弹幕库。
* [bullet-screen](https://github.com/Binaryify/vue-danmu) - 基于 Vue 的弹幕交互组件。

# Worth Reading (值得一读)

* [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS) - 可能是现代 JavaScript 最好的书籍,可以在线免费阅读,也可以购买支持作者。
* [braziljs/js-the-right-way](https://github.com/braziljs/js-the-right-way/) - JavaScript 最佳实践、编码标准和网络资源的快速参考。
* [JSbooks](https://github.com/revolunet/JSbooks) - 免费 JavaScript 电子���目录。
* [Superhero.js](http://superherojs.com) - 关于创建、测试和维护大型 JavaScript 代码库的资源集合。
* [SJSJ](https://github.com/KittyGiraudel/SJSJ) - 简化的 JavaScript 术语表,用简单的语言解释��前 JavaScript 生态系统中的各种术语。
* [How to Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) - 发布 JavaScript 开源库的完整指南。
* [JavaScript Tutorials](https://hackr.io/tutorials/learn-javascript) - 从用户评分的在线教程中学习 JavaScript。
* [Functional-Light JavaScript](https://github.com/getify/Functional-Light-JS) - JavaScript 中实用、平衡的函数式编程。
* [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript) - 适用于 JavaScript 的代码整洁之道。
* [Roadmap.sh JavaScript Roadmap](https://roadmap.sh/javascript) - 社区驱动的 JavaScript 学习路线图。

# Other Awesome Lists (其他优秀列表)

* [sotayamashita/awesome-css](https://github.com/sotayamashita/awesome-css) - 优秀的 CSS 资源列表
* [emijrp/awesome-awesome](https://github.com/emijrp/awesome-awesome) - 优秀列表的列表
* [bayandin/awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - 优秀资源集合
* [sindresorhus/awesome](https://github.com/sindresorhus/awesome) - 优�����表集合
* [jnv/list](https://github.com/jnv/lists) - 列表的列表
* [gianarb/angularjs](https://github.com/gianarb/awesome-angularjs) - AngularJS 资源
* [peterkokot/awesome-dojo](https://github.com/peterkokot/awesome-dojo) - Dojo 工具包资源
* [addyosmani/es6-tools](https://github.com/addyosmani/es6-tools) - ES6 工具
* [ericdouglas/ES6-Learning](https://github.com/ericdouglas/ES6-Learning) - ES6 学习资源
* [obetomuniz/awesome-webcomponents](https://github.com/obetomuniz/awesome-webcomponents) - Web Components 资源
* [willianjusten/awesome-svg](https://github.com/willianjusten/awesome-svg) - SVG 资源
* [davidsonfellipe/awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo) - Web 性能优化
* [instanceofpro/awesome-backbone](https://github.com/sadcitizen/awesome-backbone) - Backbone.js 资源
* [enaqx/awesome-react](https://github.com/enaqx/awesome-react) - React 资源
* [bolshchikov/js-must-watch](https://github.com/bolshchikov/js-must-watch) - 必看的 JavaScript 视频
* [peterkokot/awesome-jquery](https://github.com/peterkokot/awesome-jquery) - jQuery 资源
* [davidyezsetz/you-might-not-need-jquery-plugins](https://github.com/davidyezsetz/you-might-not-need-jquery-plugins) - 不需要 jQuery 插件的替代方案
* [MaximAbramchuck/awesome-interviews](https://github.com/MaximAbramchuck/awesome-interview-questions) - 面试问题集合
* [denolib/awesome-deno](https://github.com/denolib/awesome-deno) - Deno 资源
* [apvarun/awesome-bun](https://github.com/apvarun/awesome-bun) - Bun 资源

# Contributing (贡献)

欢迎���献！请先阅���[贡献指南](CONTRIBUTING.md)。

# License (许可证)

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内,[chencheng](https://github.com/sorrycc) 已放弃本作���的所有版权和相关权利。

## Loading Status (加载状态)

*用于指示加载状态的库*

* [Mprogress.js](https://github.com/lightningtgc/MProgress.js) - 创建 Google Material Design 风格的线性进度条。
* [NProgress](https://ricostacruz.com/nprogress/) - 为 Ajax 应用添加纤细的进度条。
* [Spin.js](https://github.com/fgnass/spin.js) - 一个旋转的活动指示器。
* [progress.js](https://github.com/usablica/progress.js) - 为页面上的任何��象创建和管��进度条。
* [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js) - 带有动画 SVG 路径的漂亮和响应式进度��。
* [pace](https://github.com/HubSpot/pace) - 自动为你的网站添加进度条。
* [topbar](https://github.com/buunguyen/topbar) - 小巧漂亮的网站全局进度指示器。
* [nanobar](https://github.com/jacoborus/nanobar) - 非常轻量级的进度条。不依赖 jQuery。
* [PageLoadingEffects](https://github.com/codrops/PageLoadingEffects) - 使用 SVG 动画展示新内容的现代方式。
* [SpinKit](https://github.com/tobiasahlin/SpinKit) - 一组使用 CSS 动画的加载指示器。
* [Ladda](https://github.com/hakimel/Ladda) - 带有内置加载指示器的按钮。
* [css-loaders](https://github.com/lukehaas/css-loaders) - 一组使用 CSS 动画的加载���转器。

* [css-loaders](https://github.com/lukehaas/css-loaders) - 一组使用 CSS 动画的加载旋转器。
