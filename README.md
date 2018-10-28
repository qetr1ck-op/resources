[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Personal list of up to date professional links

TOC:

- [JS](#js)
  - [General](#general)
  - [Patterns](#patterns)
  - [Libs](#libs)
  - [Webpack](#webpack)
  - [IFrame](#iframe)
  - [Animation](#animation)
  - [Data visualization](#data-visualization)
  - [Books](#books)
- [TS](#ts)
  - [General](#general-1)
  - [Patterns](#patterns-1)
  - [Books](#books-1)
- [Node.js](#nodejs)
  - [General](#general-2)
  - [Debugging](#debugging)
  - [Security](#security)
- [Tests](#tests)
  - [General](#general-3)
- [Angular](#angular)
  - [General](#general-4)
  - [Architecture](#architecture)
  - [Debugging](#debugging-1)
  - [Security](#security-1)
  - [View](#view)
  - [Component](#component)
  - [Directive](#directive)
  - [Dynamic template](#dynamic-template)
  - [Custom Elements](#custom-elements)
  - [Forms](#forms)
  - [Change detection](#change-detection)
  - [Routing](#routing)
  - [Ngrx](#ngrx)
  - [Migration from AngularJS](#migration-from-angularjs)
  - [Books](#books-2)
- [Rxjs](#rxjs)
  - [General](#general-5)
  - [Operators](#operators)
  - [Debugging](#debugging-2)
- [CSS](#css)
  - [Flexbox](#flexbox)
- [HTML](#html)
  - [General](#general-6)
- [Git](#git)
  - [Commands](#commands)
- [Networking](#networking)
  - [HTTP](#http)
  - [REST](#rest)
  - [Books](#books-3)
  - [Security](#security-2)
- [Alrorithms and data structure](#alrorithms-and-data-structure)
- [DB](#db)
  - [SQL](#sql)
  - [DynamoDB](#dynamodb)
- [CS](#cs)
- [Serverless](#serverless)
- [Arhitecture](#arhitecture)
  - [General](#general-7)
  - [Security](#security-3)
  - [Books](#books-4)
- [Interview](#interview)
- [Docker](#docker)

# JS

### General

- [Awesome JS](https://github.com/sorrycc/awesome-javascript)
- How Javascript works
  - [How Javascript works RU](https://habr.com/company/ruvds/blog/337042/)
  - [An overview of engine, the runtime and callstack](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
  - [Inside of V8 + 5 tips how to write an optimized code](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized-code-ac089e62b12e)
  - [Memory manedgment + how to hanle 4 common memory leaks](https://blog.sessionstack.com/how-javascript-works-memory-management-how-to-handle-4-common-memory-leaks-3f28b94cfbec)
  - [Event loop and the rise of async programming + 5 ways to better codding with async/await](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)
    - [Asynchronous under the hoood RU](https://habr.com/company/oleg-bunin/blog/417461/)
    - [JavaScript Symbols, Iterators, Generators, Async/Await, and Async Iterators — All Explained Simply (rus)](https://habr.com/company/ruvds/blog/359004)
    - [Lops — how to handle async/await](https://blog.lavrton.com/javascript-loops-how-to-handle-async-await-6252dd3c795)
  - [Deep dive into websockets and HTTP2 with SSE + how to pick the right pass](https://blog.sessionstack.com/how-javascript-works-deep-dive-into-websockets-and-http-2-with-sse-how-to-pick-the-right-path-584e6b8e3bf7)
  - [A comparison with WebAssable + why in certain cases it's better over Javascript](https://blog.sessionstack.com/how-javascript-works-a-comparison-with-webassembly-why-in-certain-cases-its-better-to-use-it-d80945172d79)
  - [The building blocks of Web Workers + 5 use cases when you shoud use them](https://blog.sessionstack.com/how-javascript-works-the-building-blocks-of-web-workers-5-cases-when-you-should-use-them-a547c0757f6a)
  - [Service Worker, their lifestyle and use cases](https://blog.sessionstack.com/how-javascript-works-service-workers-their-life-cycle-and-use-cases-52b19ad98b58)
  - [The mechanizm of Web push notification](https://blog.sessionstack.com/how-javascript-works-the-mechanics-of-web-push-notifications-290176c5c55d)
  - [Tracking changes in DOM using MutationObserver](https://blog.sessionstack.com/how-javascript-works-tracking-changes-in-the-dom-using-mutationobserver-86adc7446401)
  - [The rendering engine and tips to optimize its performance](https://blog.sessionstack.com/how-javascript-works-the-rendering-engine-and-tips-to-optimize-its-performance-7b95553baeda)
  - [Inside of Networing layer + how to optimize its performance and security](https://blog.sessionstack.com/how-javascript-works-inside-the-networking-layer-how-to-optimize-its-performance-and-security-f71b7414d34c)
  - [Under the hood of CSS and Javascript animation + how to optimize their performance](https://blog.sessionstack.com/how-javascript-works-under-the-hood-of-css-and-js-animations-how-to-optimize-their-performance-db0e79586216)
  - [Storage engine + how to choose the proper storage API](https://blog.sessionstack.com/how-javascript-works-storage-engines-how-to-choose-the-proper-storage-api-da50879ef576)
  - [The internals of shadow DOM + how to build a self contained component](https://blog.sessionstack.com/how-javascript-works-the-internals-of-shadow-dom-how-to-build-self-contained-components-244331c4de6e)
  - [WebRTC and the mechanics of peer to peer networking](https://blog.sessionstack.com/how-javascript-works-webrtc-and-the-mechanics-of-peer-to-peer-connectivity-87cc56c1d0ab)
- [33 concepts every JS developer should know](https://github.com/leonardomso/33-js-concepts)
- [Best of JS - most popular open source projects](https://bestofjs.org/)
- [30 seconds of code](https://github.com/30-seconds/30-seconds-of-code#table-of-contents)
- [What the f\*ck JavaScript?](https://github.com/denysdovhan/wtfjs)
- [Full Stack JS Engineer diagram](https://coggle.it/diagram/WmRp9Hic2QABp8X1/t/full-stack-javascript-engineer)
- [JS the right way](http://jstherightway.org)
- [JAMstack - architecture based on client-side JavaScript, APIs, prebuilt Markup](https://jamstack.org/)
- [Awesome Static Web Site Generators](https://github.com/myles/awesome-static-generators)
- [Preload Images with Pure Javascript](https://blog.lovemily.me/preload-images-with-pure-javascript/)
- [Common Threats in Web Application Security](https://auth0.com/blog/common-threats-in-web-app-security/)
- [Decorators: what they are and when to use](https://www.sitepoint.com/javascript-decorators-what-they-are/)
- [The Cost Of JavaScript In 2018](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4)
- [Project Guidelines](https://github.com/elsewhencode/project-guidelines)
- [The Definitive Guide to Object-Oriented JavaScript](http://www.objectplayground.com/)
- [JavaScript Standard Style](https://standardjs.com/#why-should-i-use-javascript-standard-style)
- [Guide to deploy p1: DB and API deplloy](https://auth0.com/blog/the-complete-guide-to-deploying-javascript-applications-part-1)
- [Guide To deploy p2: Single Page Applications, Logging, SSL](https://auth0.com/blog/deploying-javascript-apps-part-2/)

### Patterns

- [JavaScript patterns (rus)](https://proglib.io/p/javascript-patterns/)
- [Object composition with mixins](https://www.barbarianmeetscoding.com/blog/2015/12/28/black-tower-summoning-object-composition-with-mixins)
- [Ultra Flexible JavaScript Object Oriented Programming With Stamps](https://www.barbarianmeetscoding.com/blog/2016/01/18/javascript-ultra-flexible-object-oriented-programming-with-stamps/)
- [Forms of object compositon - Aggregation, Concatenation, Delegation](https://medium.com/javascript-scene/the-hidden-treasures-of-object-composition-60cd89480381)
- [Class composition via mixins](https://alligator.io/js/class-composition/)
- [Functions overloading](https://www.barbarianmeetscoding.com/blog/2015/05/26/mastering-the-arcane-art-of-javascript-mancy-for-c-sharp-developers-chapter-5-more-useful-function-patterns-function-overloading/)
- [OOP - Object Oriented Programming](https://www.barbarianmeetscoding.com/blog/2015/11/23/an-introduction-to-object-oriented-programming-in-javascript-for-c-sharp-developers/)
- [A guide to prototype inheritence](https://tylermcginnis.com/beginners-guide-to-javascript-prototype/)
  - [Object playground](http://www.objectplayground.com/)

### Libs

- [A library of zero-dependency npm modules that do just do one thing](https://github.com/angus-c/just)
- [Time And Date Manipulation Libraries For 2018](https://blog.bitsrc.io/9-javascript-date-time-libraries-for-2018-12d82f37872d)
- [Maybe you don't need moment.js](https://github.com/you-dont-need/You-Dont-Need-Momentjs)
- [Stampit - create objects from reusable, composable behaviors](https://github.com/stampit-org/stampit)
- [Async await wrapper to better handling exception](https://github.com/scopsy/await-to-js)

### Webpack

- [Keep webpack Fast: A Field Guide for Better Build Performance](https://slack.engineering/keep-webpack-fast-a-field-guide-for-better-build-performance-f56a5995e8f1)
- [Optimizing- webpack builds with DLL plugin](https://engineering.bitnami.com/articles/optimizing-your-webpack-builds.html)

### IFrame

- [Make iframe automatically adjust height according to the contents](https://stackoverflow.com/questions/9975810/make-iframe-automatically-adjust-height-according-to-the-contents-without-using)
- [Cross-domain iframe height auto-resizer that works](https://stackoverflow.com/questions/5589756/is-there-a-cross-domain-iframe-height-auto-resizer-that-works)
- [Cross-domain massaging](https://www.npmjs.com/package/post-robot)

### Animation

- [Some of the finest JS-CSS animation libraries around](https://blog.bitsrc.io/11-javascript-animation-libraries-for-2018-9d7ac93a2c59)

### Data visualization

- [NVD3.js](https://css-tricks.com/how-to-make-a-modern-dashboard-with-nvd3-js/)

### Web Components

- [Introduction](https://www.webcomponents.org/introduction)
- [About web components RU](https://habr.com/post/422499/)

### Books

- [clean-code-javascript - Software engineering principles, from Robert C. Martin's book Clean Code](https://github.com/ryanmcdermott/clean-code-javascript)
- [JavaScript Allongé](https://leanpub.com/javascriptallongesix)
- [Functional Light FP](https://github.com/getify/Functional-Light-JS/blob/master/manuscript/README.md/#table-of-contents)
- [The power of serverless for FE developer](https://thepowerofserverless.info)
- [Front-End Developer Handbook 2018](https://frontendmasters.gitbooks.io/front-end-developer-handbook-2018/)

# TS

### General

- [Five tips I wish to know when I started TS](https://codeburst.io/five-tips-i-wish-i-knew-when-i-started-with-typescript-c9e8609029db)
- [Support for import d from "cjs" form CommonJS modules with --esModuleInterop](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript#support-for-import-d-from-cjs-form-commonjs-modules-with---esmoduleinterop)
- [TypeScript Node Starter](https://github.com/Microsoft/TypeScript-Node-Starter)
- [Configure TS compiler with tsconfig](https://blog.angularindepth.com/configuring-typescript-compiler-a84ed8f87e3)
- [Enums as binary flags](https://basarat.gitbooks.io/typescript/docs/enums.html#enums-as-flags)
- [Partial type example](https://netbasal.com/getting-to-know-the-partial-type-in-typescript-ecfcfbc87cb6)
- [Advanced TypeScript Types with Examples](https://levelup.gitconnected.com/advanced-typescript-types-with-examples-1d144e4eda9e)
- [External helpers library - tslib](https://blog.mariusschulz.com/2016/12/16/typescript-2-1-external-helpers-library)
- [Evolition series](https://blog.mariusschulz.com/series/typescript-evolution)]
- [Generics and Augmentation](https://medium.com/@idandrd/two-advanced-techniques-to-make-you-a-typescript-wizard-df42e00b1cf8)

### Patterns

- [Design Patterns in Typescript](https://github.com/gztchan/design-patterns-in-typescript)
- [Dependency Injection in TS](https://nehalist.io/dependency-injection-in-typescript/)
- [InversifyJS - A powerful and lightweight inversion of control container for JavaScript & Node.js apps powered by TypeScript](http://inversify.io)

### Books

- [TypeScript Deep Dive](https://basarat.gitbooks.io/typescript)
- [LEARNING PATH: Modern Web Development with TypeScript 2.x](https://www.safaribooksonline.com/learning-paths/learning-path-modern/9781789130843/)

# Node.js

### General

- [Awesome nodejs](https://github.com/sindresorhus/awesome-nodejs)
- [You don't know nodejs](https://github.com/azat-co/you-dont-know-node)
- [Node.js Best Practices](https://github.com/i0natan/nodebestpractices/#1-project-structure-practices)
- [How to become a better node.js developer in 2018](https://nemethgergely.com/nodejs-best-practices-how-to-become-a-better-developer-in-2018/)
- [Introduction to Webcrawling (with Javascript and Node.js)](https://medium.com/of-all-things-tech-progress/introduction-to-webcrawling-with-javascript-and-node-js-f5a3798ee8ac)
- [How to make beautiful, simple CLI apps with Node](https://codewithhugo.com/how-to-make-beautiful-simple-cli-apps-with-node/)
- [How I automated my job with Node.js](https://medium.com/dailyjs/how-i-automated-my-job-with-node-js-94bf4e423017)
- [Using CSI (client-side-include) instead of SSI (server-side-includes)](https://www.techrepublic.com/article/using-client-side-includes-instead-of-server-side-includes/)
- [Top 10 frameworks in 2018](https://da-14.com/blog/10-best-nodejs-frameworks)
- [Choose framework based on category](http://nodeframework.com/)
- [Load balancing performance: comparing cluster module, iptables, Nginx](https://medium.com/@fermads/node-js-process-load-balancing-comparing-cluster-iptables-and-nginx-6746aaf38272)
- [HMR - hot module replacement](https://github.com/webpack/docs/issues/45#issuecomment-149793458)
- [HMR api](https://github.com/webpack/docs/wiki/hot-module-replacement)

### Architecture
- [Project structure](https://blog.risingstack.com/node-js-project-structure-tutorial-node-js-at-scale/)
- [Everything you need to know about child processes](https://medium.freecodecamp.org/node-js-child-processes-everything-you-need-to-know-e69498fe970a)
- [Cluster module, usage with HTTP, PM2](http://www.acuriousanimal.com/2017/08/12/understanding-the-nodejs-cluster-module.html)
- [Scaling strategies](https://medium.freecodecamp.org/scaling-node-js-applications-8492bd8afadc)
- [Awesome stream](https://github.com/thejmazz/awesome-nodejs-streams)
- [Everything you should to know about stream](https://medium.freecodecamp.org/node-js-streams-everything-you-need-to-know-c9141306be93)

### Debugging

- [Supercharge your debugging experience for Node.js](https://medium.com/@wesharehoodies/supercharge-your-debugging-experience-for-node-js-3f0ddfaffbb2)
- [How to Debug a Node.js app in a Docker Container](https://blog.risingstack.com/how-to-debug-a-node-js-app-in-a-docker-container/)

### Security

- [Checklist: node.js production best practices](http://goldbergyoni.com/checklist-best-practice-of-node-js-in-production/)
- [Checklist: node.js error handling best practices](http://goldbergyoni.com/checklist-best-practices-of-node-js-error-handling/)
- [Checklist: node.js security list](https://blog.risingstack.com/node-js-security-checklist)
- [Node.js security best practices](https://medium.com/@nodepractices/were-under-attack-23-node-js-security-best-practices-e33c146cb87d)
- [CQRS explained](https://blog.risingstack.com/cqrs-explained-node-js-at-scale/)
- [Implement JWT authentication](https://dev.to/adnanrahic/securing-nodejs-restful-apis-with-json-web-tokens)

# Tests

### General

- [The hidden power of Jasmine/Jest matchers](https://medium.com/@boriscoder/the-hidden-power-of-jest-matchers-f3d86d8101b0)

# Angular

### General

- [Awesome Angular](https://github.com/gdi2290/awesome-angular)
- [What problem DI solves; How Angular DI works; What are injector and child injectors; Types of providers; @Inject and @Injectable](https://codecraft.tv/courses/angular/dependency-injection-and-providers/overview)
- [Progressive web apps with angular](https://houssein.me/progressive-angular-applications)
- [Make app search engine SEO friendly](https://www.youtube.com/watch?v=fiT5g9KSxmw)
- [Typical use case of observables](https://habrahabr.ru/post/337512/)
- [Ant design](https://ng.ant.design/docs/introduce/en)

### Architecture

- [Architecture for huge angular based enterprise](https://www.youtube.com/watch?v=q4XmAy6_ucw)
- [Angular Architecture series](https://blog.angular-university.io/angular-2-smart-components-vs-presentation-components-whats-the-difference-when-to-use-each-and-why/)
- [12 Things to Help Large Organizations Do Angular Right](https://blog.nrwl.io/12-things-to-help-large-organizations-do-angular-right-f261a798ad6b)
- [Avoid common confusions with NgModules in Angular](https://blog.angularindepth.com/avoiding-common-confusions-with-modules-in-angular-ada070e6891f)
- [Organizing application: modules and services](https://medium.com/@michelestieven/organizing-angular-applications-f0510761d65a)
  
### Debugging

- [7 ways to debug angular apps](https://angularfirebase.com/lessons/methods-for-debugging-an-angular-application)

### Security

- [Security with DOMSanitizer service](https://netbasal.com/angular-2-security-the-domsanitizer-service-2202c83bd90)

### View

- [Four ways of listening to DOM events in Angular](https://medium.com/claritydesignsystem/four-ways-of-listening-to-dom-events-in-angular-part-1-event-binding-3ec7e9f51a1d)
  - [Articles](https://blog.angularindepth.com/introducing-advanced-angular-component-patterns-13e102e6bbfc)
- [Angular DOM abstractions: ElementRef, TemplateRef, ViewContainerRef](https://blog.angularindepth.com/exploring-angular-dom-abstractions-80b3ebcfc02)
- [Understanding ViewChildren, ContentChildren, and QueryList](https://netbasal.com/understanding-viewchildren-contentchildren-and-querylist-in-angular-896b0c689f6e)
- [ng-content: The hidden docs](https://medium.com/claritydesignsystem/ng-content-the-hidden-docs-96a29d70d11b)

### Component

- [Advanced Angular component patterns](https://blog.angularindepth.com/introducing-advanced-angular-component-patterns-13e102e6bbfc)
- [Implementing custom component decorator in Angular](https://blog.angularindepth.com/implementing-custom-component-decorator-in-angular-4d037d5a3f0d)
- [Using Angular Components with Third-Party Libraries](https://stackblitz.com/edit/angular-caxzwv?file=app%2Fapp.component.ts)
- [Possible parameters for @HostBinding and @HostListener decorators](http://stepansuvorov.com/blog/2017/01/angular2-possible-parameters-for-hostbinding-and-hostlistener-decorators/)
- [Angular dropdown with popper.js](https://stackblitz.com/edit/angular-dropdown-with-popper?file=app%2Fapp.component.html)
- [Angular custom overlays with angulars material cdk](https://stackblitz.com/edit/angular-custom-overlays-with-angulars-cdk?file=app/app.component.html)
- [Angular Material Dialog: A Complete Example](https://blog.angular-university.io/angular-material-dialog/)
- [Reactive Sticky Header in Angular](https://netbasal.com/reactive-sticky-header-in-angular-12dbffb3f1d3)
- [@Attribute decorator](https://netbasal.com/getting-to-know-the-attribute-decorator-in-angular-4f7c9fb61243)

### Directive

- [The power of structural directives](https://netbasal.com/the-power-of-structural-directives-in-angular-bfe4d8c44fb1)
- [Handling conditional subscriptions in structural directive](https://netbasal.com/diy-subscription-handling-directive-in-angular-c8f6e762697f)

### Dynamic template

- [Everything you need to know about dynamic components](https://blog.angularindepth.com/here-is-what-you-need-to-know-about-dynamic-components-in-angular-ac1e96167f9e)
- [Dynamic Angular or manipulate it in right way RU](https://habr.com/company/infowatch/blog/330030/)
- [Dynamic template in component, or alteranative for ng1.$compile](https://stackoverflow.com/questions/38888008/how-can-i-use-create-dynamic-template-to-compile-dynamic-component-with-angular)
- [Dynamic tooltips](https://stackblitz.com/edit/dynamically-create-tooltip-angular?file=app/tooltip/tooltip.directive.ts)
- [Content projection, dialog example](http://blog.ng-book.com/dynamic-components-with-content-projection-in-angular)

### Custom Elements

- [ng-conf intro](https://www.youtube.com/watch?v=Z1gLFPLVJjY)
- [tutorial video](https://www.academind.com/learn/angular/snippets/angular-elements-tutorial-introduction/)
- [tutorial + demo](https://nitayneeman.com/posts/a-practical-guide-to-angular-elements/)
- [build flow](https://medium.com/codingthesmartway-com-blog/angular-elements-a-practical-introduction-to-web-components-with-angular-6-52c0b3076c2c)

### Forms

- [Using ControlValueAccessor to create custom form controls in Angular](https://stackblitz.com/edit/control-value-anccessor?file=app%2Frating-input-accessor%2Findex.ts)
- [Dynamic reactive forms](https://stackblitz.com/edit/angular-fjvd2x?file=app%2Fdynamic-form%2Fdynamic-form.component.ts)
- [Forms in v5, custom controlls, nested forms strategies](https://www.youtube.com/watch?v=CD_t3m2WMM8)
- [Attribute Directives with injecting ngControl ❤ Angular Forms](https://netbasal.com/attribute-directives-angular-forms-b40503643089)
- [Custom validation, inspired by jQuery validation](https://github.com/yuyang041060120/ng2-validation#readme)
- [ngx-errors, a declarative validation errors module for reactive forms](https://github.com/UltimateAngular/ngx-errors)

### Change detection

- [These 5 articles will make you an Angular Change Detection expert](https://blog.angularindepth.com/these-5-articles-will-make-you-an-angular-change-detection-expert-ed530d28930)
- [What every frond-end developer should know about change detection in Angular and React](https://medium.freecodecamp.org/what-every-front-end-developer-should-know-about-change-detection-in-angular-and-react-508f83f58c6a)
- [Triggering change detection manually in Angular](https://stackoverflow.com/questions/34827334/triggering-change-detection-manually-in-angular)
- [A Comprehensive Guide to Angular onPush Change Detection Strategy](https://netbasal.com/a-comprehensive-guide-to-angular-onpush-change-detection-strategy-5bac493074a4)
- Perforamce list
  - [44 tips to tune the performance](https://medium.com/@spp020/44-quick-tips-to-fine-tune-angular-performance-9f5768f5d945)
  - [Change detection strategy](https://blog.ninja-squad.com/2018/09/27/angular-performances-part-4/)
  - [Pure pipes, attribute decorator, smart-dumb separation](https://blog.ninja-squad.com/2018/10/04/angular-performances-part-5/?utm_campaign=Angular%20Ninja%20Newsletter&utm_medium=email&utm_source=Revue%20newsletter)
  - [Pipes vs function call](https://www.youtube.com/watch?v=I6ZvpdRM1eQ)
  
### Routing

- [Dynamic guard redirects with route data and CanActivate](http://www.kirjai.com/dynamic-guard-redirects-angular/)
- [Lazy Loading Angular - Code Splitting NgModules with Webpack](https://toddmotto.com/lazy-loading-angular-code-splitting-webpack)

### Ngrx

- [Comprehensive Introduction to @ngrx/store](https://gist.github.com/btroncone/a6e4347326749f938510)
- [@ngrx example application - Example application utilizing @ngrx libraries, showcasing common patterns and best practices](https://github.com/ngrx/platform/tree/master/example-app)
- [ngrx-store-effects course](https://platform.ultimateangular.com/courses/ngrx-store-effects)

### Migration from AngularJS

- [Bullet proof AngularJS migration using iframes](https://codecraft.tv/blog/2017/09/07/angularjs-to-angular-using-iframes/)
- [2 New Tools to help with AngularJS to Angular Migrations](https://blog.angular.io/migrating-to-angular-fc9618d6fb04)

### Books

- [Angular from theory to practice](https://codecraft.tv/assets/books/angular-from-theory-to-practice.pdf)

# Rxjs

### General

- [RxJS: observable, observer and operators intro](https://toddmotto.com/rxjs-observables-observers-operators#what-is-an-observable)
- [Subject and Observable](https://netbasal.com/understanding-subjects-in-rxjs-55102a190f3)
- [BehaviorSubject vs Observable](https://stackoverflow.com/questions/39494058/behaviorsubject-vs-observable)
- [On The Subject Of Subjects](https://medium.com/@benlesh/on-the-subject-of-subjects-in-rxjs-2b08b7198b93)
- [Playground](https://stackblitz.com/edit/rxjs-playground-oop?file=app/app.component.ts)
- [How to observe the object, rx-observe](https://blog.angularindepth.com/rxjs-how-to-observe-an-object-20c47cf51571)
- [How to observe handler, rx-handler](https://github.com/johnlindquist/rx-handler)
- [From promises to observales](https://juristr.com/blog/2018/10/journey-promises-to-rxjs/)

### Operators

- [A complete list of RxJS operators with clear explanations, relevant resources, and executable examples](https://www.learnrxjs.io/operators/)
- [RxJS marbles](http://rxmarbles.com)
- [Choose an operator](http://reactivex.io/rxjs/manual/overview.html#choose-an-operator)
- [Creating streams in RxJS](https://blog.angularindepth.com/the-extensive-guide-to-creating-streams-in-rxjs-aaa02baaff9a)
- [RxJS — Six Operators That you Must Know](https://netbasal.com/rxjs-six-operators-that-you-must-know-5ed3b6e238a0)
- [How to combine observables sequence with super diagrams](https://blog.angularindepth.com/learn-to-combine-rxjs-sequences-with-super-intuitive-interactive-diagrams-20fce8e6511)
- [RxJS: Understanding Lettable Operators](https://blog.angularindepth.com/rxjs-understanding-lettable-operators-fe74dda186d3)
- [Understanding hight order observables with mergeMap and switchMap](https://netbasal.com/understanding-mergemap-and-switchmap-in-rxjs-13cf9c57c885)
- [Pipeable Operators](https://github.com/ReactiveX/rxjs/blob/master/doc/pipeable-operators.md)
- [When to use asObservable](https://stackoverflow.com/questions/36986548/when-to-use-asobservable-in-rxjs)
- [Build your own pipeble operator](https://egghead.io/courses/build-your-own-rxjs-pipeable-operators)

### Debugging

- [rxjs-spy - A debugging library for RxJS](https://cartant.github.io/rxjs-spy/)

# React

### General

- [Life cycle hooks](http://projects.wojtekmaj.pl/react-lifecycle-methods-diagram/)
- [Immutable.js with React, Redux](https://www.fullstackreact.com/articles/using-immutablejs-with-react-and-redux/)
- [Context API](https://reactjs.org/docs/context.html)
- [Airbnb React/JSX Style Guide](https://github.com/airbnb/javascript/tree/master/react)
- [Styling](https://codeburst.io/styling-in-react-5aafecc5edd3)
- [Structuring and naming](https://hackernoon.com/structuring-projects-and-naming-components-in-react-1261b6e18d76)

### Patterns

- [Render props](https://reactjs.org/docs/render-props.html)
- [Update on async rendering](https://reactjs.org/blog/2018/03/27/update-on-async-rendering.html)
- [You probably don't need a derived state](https://reactjs.org/blog/2018/06/07/you-probably-dont-need-derived-state.html#recommendation-fully-controlled-component)

# CSS

### Flexbox

- [Solved by flexbox](https://philipwalton.github.io/solved-by-flexbox/)
- [Flexbox — The Animated Tutorial](https://medium.com/@js_tut/flexbox-the-animated-tutorial-8075cbe4c1b2)

# HTML

### General

- [15 HTML element methods you’ve potentially never heard of](https://hackernoon.com/15-html-element-methods-youve-potentially-never-heard-of-fc6863e41b2a)
- [Esential Image Optimization Book by Addy Osmani](https://images.guide/)

# Git

### Commands

- [Undo a local merge](https://stackoverflow.com/questions/2389361/undo-a-git-merge-that-hasnt-been-pushed-yet/6217372#6217372)
- [Undo a remote merge](https://stackoverflow.com/questions/6481575/undo-a-merge-by-pull-request)
- [Undo a multiple remote commits](https://stackoverflow.com/questions/10780228/how-can-i-revert-multiple-git-commits-already-pushed-to-a-published-repository)
- [merge --squash vs rebase](https://stackoverflow.com/questions/2427238/in-git-what-is-the-difference-between-merge-squash-and-rebase)

# Networking

### HTTP

- [HTTP Status codes](http://www.restapitutorial.com/httpstatuscodes.html)
- [HTTP Caching](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)
- [Using Preload and Prefetch in Your HTML to Load Assets](https://alligator.io/html/preload-prefetch/)
- [.htaccess](http://www.htaccess-guide.com/)
- [What happens when you type google.com into your browser and press enter?](https://github.com/alex/what-happens-when)
- [How browser engine works - behind the scenes](https://blog.logrocket.com/how-browser-rendering-works-behind-the-scenes-6782b0e8fb10)
- [OSI layers](https://www.lifewire.com/layers-of-the-osi-model-illustrated-818017)
- [Forward vs Reverse Proxy](https://stackoverflow.com/questions/224664/difference-between-proxy-server-and-reverse-proxy-server)

### REST

- [Guiding Principles of REST](https://restfulapi.net/)

### Security

- [A comprehensive XSS guide](https://excess-xss.com/)
- [An Introduction to Content Security Policy](https://www.html5rocks.com/en/tutorials/security/content-security-policy/)

### Docker

- [Docker for Web Developers on pluralsight](https://app.pluralsight.com/library/courses/docker-web-development/table-of-contents)
- [Jenkins with HTTPS using Nginx and Docker](https://medium.com/@weibeld/setting-up-https-for-jenkins-with-nginx-everything-in-docker-4a118dc29127)
- [Nginx Docker container with HTTPS protocol](http://scmquest.com/nginx-docker-container-with-https-protocol/)

### Books

- [Networking free books](https://proglib.io/p/computer-networks-books/)

# Alrorithms and data structure

- [Course (UA)](http://vo.ukraine.edu.ua/course/view.php?id=281)
- [Big O cheat sheet](http://bigocheatsheet.com/)
- [Sort algorithms video explanation](https://proglib.io/p/sort-algorithms/)
- [Interview Algorithm Questions in Javascript](https://github.com/kennymkchan/interview-questions-in-javascript)
- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms)

# DB

### SQL

- [Basic SQL](http://proselyte.net/tutorials/sql)
- [SQL practice](https://proglib.io/p/sql-practice-sites/)
- [SQL books](https://proglib.io/p/sql-digest/)
- [What is the difference between INNER and OUTER joins](https://stackoverflow.com/questions/38549/what-is-the-difference-between-inner-join-and-outer-join)

### DynamoDB

- [A Node.js wrapper of AWS DynamoDB Local](https://www.npmjs.com/package/local-dynamo)
- [Dynamoose](https://dynamoosejs.com/)
- [dynogels](https://github.com/clarkie/dynogels)

# CS

- [Concurrency vs Parallelism](http://qaru.site/questions/237/concurrency-vs-parallelism-what-is-the-difference)
- [Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/)
- [The Mistakes I Made As a Beginner Programmer](https://medium.com/@samerbuna/the-mistakes-i-made-as-a-beginner-programmer-ac8b3e54c312)
- [Flags and bitmasks](https://stackblitz.com/edit/flags-and-bitmasks?file=index.ts)
- [Unicode vs UTF](http://qaru.site/questions/16613/whats-the-difference-between-unicode-and-utf-8)

# Arhitecture

### General

- [Event-Driven arhitecture](https://martinfowler.com/articles/201701-event-driven.html)
- [CQRS expalined](https://blog.risingstack.com/cqrs-explained-node-js-at-scale/)
- [Event Sourcing](https://blog.risingstack.com/event-sourcing-with-examples-node-js-at-scale/)
- [Presentatuin Domain Data layering](https://martinfowler.com/bliki/PresentationDomainDataLayering.html)

### Security

- [How to safety store a password](https://codahale.com/how-to-safely-store-a-password/)
- [Bcrypt and password secutrity](https://www.youtube.com/watch?v=O6cmuiTBZVs)
- [OAuth flow diagram](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2)
- [OpenID vs OAuth](https://stackoverflow.com/questions/1087031/whats-the-difference-between-openid-and-oauth)
- [JWT vs OAuth](https://stackoverflow.com/questions/39909419/jwt-vs-oauth-authentication)
- [JWT vs cookies](https://stackoverflow.com/questions/37582444/jwt-vs-cookies-for-token-based-authentication)

### Serverless

- [Serverless arhitecture](https://martinfowler.com/articles/serverless.html)
- [Architecture overview monolith vs microservices vs serverless](https://codeguida.com/post/1466)
- [10 Things You Need To Know When Building Serverless Applications](https://www.jeremydaly.com/10-things-to-know-when-building-serverless/?utm_source=sidebar)
- [How long does AWS Lambda keep your idle functions around before a cold start?](https://read.acloud.guru/how-long-does-aws-lambda-keep-your-idle-functions-around-before-a-cold-start-bf715d3b810)
- [Serverless video course](https://www.youtube.com/playlist?list=PLzvRQMJ9HDiT5b4OsmIBiMbsPjfp4kfg3)
- [A crash course on Serverless with Node.js](https://hackernoon.com/a-crash-course-on-serverless-with-node-js-632b37d58b44)
- [Organizing Serverless Projects](https://serverless-stack.com/chapters/organizing-serverless-projects.htmlhttps://serverless-stack.com/chapters/organizing-serverless-projects.html)
- [AWS lambda + Serverless + TS](https://blog.shovonhasan.com/deploying-a-typescript-node-aws-lambda-function-with-serverless/)
- [Building a Serverless REST API with Node.js and MongoDB](https://hackernoon.com/building-a-serverless-rest-api-with-node-js-and-mongodb-2e0ed0638f47)
- [How to Handle AWS Lambda Errors Like a Pro](https://blog.epsagon.com/how-to-handle-aws-lambda-errors-like-a-pro)
- [Keeping Functions Warm - How To Fix AWS Lambda Cold Start Issues](https://serverless.com/blog/keep-your-lambdas-warm/)
- [Strategies for implementing user authentication in serverless apps](https://serverless.com/blog/strategies-implementing-user-authentication-serverless-applications/)
- [AWS all sercices overview](https://academind.com/learn/aws/aws-all-services-overview/)
- [Patterns for distributet transaction within a microservice architecture](https://developers.redhat.com/blog/2018/10/01/patterns-for-distributed-transactions-within-a-microservices-architecture/)
- [Desing patterns for microservices](https://dzone.com/articles/design-patterns-for-microservices)

### Books

- [Three best books about software arhitecture](https://proglib.io/p/computer-architecture-books/)

# OS

### MacOS

- [Modificate PATH](https://coolestguidesontheplanet.com/add-shell-path-osx/)
- [Create simlink](https://apple.stackexchange.com/questions/115646/how-can-i-create-a-symbolic-link-in-terminal)

# Interview

### General

- [Faster Coding Interview Preparation using Interactive Visualizations](https://www.educative.io/collection/page/5642554087309312/5679846214598656/240002)
- [JS tasks](https://habr.com/post/351874)
- [7 Hardest Node.js Interview Questions & Answers](https://dev.to/aershov24/7-hardest-nodejs-interview-questions--answers-3lje?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more)
- [22 Angular interview question](https://www.fullstack.cafe/blog/21-expert-angular-interview-questions)
