# FE-learning

结合个人经历总结的前端入门方法，总结从零基础到具备前端基本技能的道路、学习方法、资料。由于能力有限，不能保证面面俱到，只是作为入门参考，面向初学者，让初学者少走弯路。

互联网的快速发展和激烈竞争，用户体验成为一个重要的关注点，导致专业前端工程师成为热门职业，各大公司对前端工程师的需求量都很大，要求也越来越高，优秀的前端工程师更是稀缺。个人感觉前端入门相对容易，在打好基础后坚持学习，成为优秀前端工程师也只是时间问题。

学习任何知识最重要的都是**兴趣**，如果经过一段时间的学习感觉不喜欢，那可能强迫自己学习是很痛苦的，效果也不会好，毕竟这很可能就是以后很多年生存的技能。不过随着互联网行业的发展，前端必然是Web开发人员需要学习的知识，有时候是没有专业前端工程师一起合作的，所以即使不做专门的前端工程师，掌握基本的前端技能为工作带来方便。

后期邀请了一些同学分享学习经历。如果有同学愿意分享，[请联系我](mailto:qiu_deqing@126.com)

## 必备基础技能

[前端技能汇总](https://github.com/JacksonTian/fks)这个项目详细记录
了前端工程师牵涉到的各方面知识。在具备基本技能之后可以在里面找到学习
的方向，完善技能和知识面。

以下是个人觉得入门阶段应该熟练掌握的基础技能：

- [HTML4](http://www.w3.org/TR/html401/cover.html#minitoc)，[HTML5](http://www.w3.org/TR/html5/#contents)语法、标签、语义
- [CSS2.1](http://www.w3.org/TR/CSS2/#minitoc)，[CSS3](http://www.w3.org/TR/2001/WD-css3-roadmap-20010523/#table)规范，与HTML结合实现各种布局、效果
- [Ecma-262](http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf)定义的javascript的语言核心，原生[客户端javascript](https://developer.mozilla.org/en-US/docs/Web/API)，[DOM操作](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model)，[HTML5新增功能](https://developer.mozilla.org/en/docs/web/Guide/HTML/HTML5)
- 一个成熟的客户端javascript库，推荐[jquery](http://jquery.com/)
- 一门服务器端语言：如果有服务器端开发经验，使用已经会的语言即可，如果没有服务器端开发经验，熟悉Java可以选择Servlet，不熟悉的可以选PHP，能实现简单登陆注册功能就足够支持前端开发了，后续可能需要继续学习，最基本要求是实现简单的功能模拟，
- [HTTP](http://www.w3.org/Protocols/rfc2616/rfc2616.html)

在掌握以上基础技能之后，工作中遇到需要的技术也能快速学习。

## 基本开发工具

恰当的工具能有效提高学习效率，将重点放在知识本身，在出现问题时能快速定位并
解决问题，以下是个人觉得必备的前端开发工具：

- **文本编辑器**：推荐[Sublime Text](http://www.sublimetext.com/)，支持各种插件、主题、设置，使用方便
- **浏览器**：推荐[Google Chrome](http://www.google.cn/chrome/?hl=zh-CN&standalone=1)，更新快，对前端各种标准提供了非常好的支持
- **调试工具**：推荐Chrome自带的[Chrome develop tools](https://developer.chrome.com/devtools)，可以轻松查看DOM结构、样式，通过控制台输出调试信息，调试javascript，查看网络等
- **辅助工具**：PhotoShop编辑图片、取色，fireworks量尺寸，AlloDesigner对比尺寸，以及前面的到的Chrome develop tools，这里是一个[简单教程](http://qiu-deqing.github.io/toolpage/front-end-develop-tools.html)
- **翻墙工具**：使用goagent + chrome很方便。遇到问题时找不到合适的中文资料，可以考虑Google搜索对应的英文资料。

## 学习方法和学习目标

方法：

1. 入门阶段反复阅读**经典书籍的中文版**，书籍中的每一个例子都动手实现并在浏览器中查看效果
2. 在具备一定基础之后可以上网搜各种教程、demo，了解各种功能的实际用法和常见功能的实现方法
3. 阅读HTML，CSS，Javascript标准全面完善知识点
4. 阅读前端牛人的博客、文章提升对知识的理解
5. 善用搜索引擎

目标：

1. 熟记前面知识点部分的重要概念，结合学习经历得到自己的理解
2. 熟悉常见功能的实现方法，如常见CSS布局，Tab控件等。

## 入门之路

以下是入门阶段不错的书籍和资料

1. HTML方面[《HTML5 the missing manual》](http://www.amazon.com/HTML5-Missing-Manual-Manuals/dp/1449302394/ref=sr_1_3?s=books&ie=UTF8&qid=1410096659&sr=1-3&keywords=html5+the+missing+manual)，个人感觉非常不错，现在已经出了第二版，推荐这本书作为HTML入门
2. CSS方面[《CSS: The Definitive Guide（css权威指南）》](http://www.amazon.com/CSS-Definitive-Guide-Eric-Meyer/dp/0596527330/ref=sr_1_1?s=books&ie=UTF8&qid=1410097105&sr=1-1&keywords=css+definitive+guide)是需要反复学习的CSS书籍，对CSS2.1规范中重要的内容进行了详细介绍，可以考虑看中文版方便理解
3. javascript先看几遍[《Professional JavaScript for Web Developers（javascript高级程序设计）》](http://www.amazon.com/Professional-JavaScript-Developers-Nicholas-Zakas/dp/1118026691/ref=sr_1_1?s=books&ie=UTF8&qid=undefined&sr=1-1&keywords=javascript+professional)然后[《JavaScript: The Definitive Guide（javascript权威指南）》](http://www.amazon.com/JavaScript-Definitive-Guide-Activate-Guides/dp/0596805527/ref=sr_1_3?s=books&ie=UTF8&qid=1410097105&sr=1-3&keywords=css+definitive+guide)
4. HTTP自然就是看[HTTP权威指南](http://www.amazon.com/HTTP-Definitive-Guide-Guides/dp/1565925092/ref=sr_1_1?s=books&ie=UTF8&qid=1410097965&sr=1-1&keywords=http+the+definitive+guide)
5. 在整个学习过程中HTML CSS JavaScript会有很多地方需要互相结合，实际工作中也是这样，一个简单的功能模块都需要三者结合才能实现。
6. 动手是学习的重要组成部分，书籍重点讲解知识点，例子可能不是很充足，这就需要利用搜索引擎寻找一些简单教程，照着教程实现功能。以下是一些比较好的教程网址
    - CSS各种布局[http://blog.html.it/layoutgala/](http://blog.html.it/layoutgala/)
    - 可以搜索各大公司前端校招笔试面试题作为练习题或者他人总结的[前端面试题](https://github.com/darcyclarke/Front-end-Developer-Interview-Questions/tree/master/Translations/Chinese)还有[个人总结的面试题](https://github.com/qiu-deqing/FE-interview)（带参考答案）
    - [http://code.tutsplus.com](http://code.tutsplus.com/categories/javascript)有各种各样的教程
    - [MDN](https://developer.mozilla.org/en-US/docs/Web)也有很多教程，更重要的是里面有详细的文档，需要查找某个功能时在Google搜索：xxx site:https://developer.mozilla.org
    - [www.html5rocks.com](http://www.html5rocks.com/zh/tutorials/?page=1)也有很多优质教程
    - [www.sitepoint.com](http://www.sitepoint.com/javascript/)
    - [http://alistapart.com/](http://alistapart.com/)
7. 原生javascript是学习前端需要重点掌握的技能，在掌握原生javascript的基础上推荐熟练掌握jQuery，在实际工作中用处很大，这方面的书籍有[《Pro jQuery》](http://www.amazon.com/Pro-jQuery-Experts-Voice-Development/dp/1430263881/ref=sr_1_1?s=books&ie=UTF8&qid=1410099103&sr=1-1&keywords=pro+jquery)和[《Learning jQuery》](http://www.amazon.com/Learning-jQuery-Fourth-Jonathan-Chaffer/dp/178216314X/ref=sr_1_1?s=books&ie=UTF8&qid=1410099243&sr=1-1&keywords=learning+jquery)
8. 建一个[https://github.com/](https://github.com/)账号，保存平时学习中的各种代码和项目。
9. 有了一定基础之后可以搭建一个个人博客，记录学习过程中遇到的问题和解决方法，方便自己查阅也为其他人提供了帮助。也可以去[http://www.cnblogs.com/](http://www.cnblogs.com/)或者[http://www.csdn.net/](http://www.csdn.net/)这样的网站注册账号，方便实用
10. 经常实用Google搜索英文资料应该经常找到来自[http://stackoverflow.com/](http://stackoverflow.com/)的高质量答案，与到问题可以直接在这里搜索，如果有精力，注册一个账号为别人解答问题也能极大提高个人能力。
11. 经典书籍熟读之后，可以打开前面必备基础技能部分的链接。认真读对应标准，全面掌握知识

## 继续提高

有了前面的基础之后，前端基本算是入门了，这时候可能每个人心中都有了一些学习方向，如果还是没有。
可以参考前面必备技能部分提到的那个项目，从里面选一些进行发展学习。以下是一些不错的方面：

- [Grunt](http://gruntjs.com/)：前端自动化工具，提高工作效率
- [less css](http://lesscss.org/)：优秀的CSS预处理器
- [bootstrap](http://getbootstrap.com/)：优秀的CSS框架，对没有设计师的团队很不错，与less结合使用效果完美
- [requirejs](http://requirejs.org/)：AMD规范的模块加载器，前端模块化趋势的必备工具
- [Node.js](http://nodejs.org/)：JavaScript也可以做后台，前端工程师地位更上一步
- [AngularJS](https://angularjs.org/)：做Single Page Application的好工具
- [移动端web开发](https://developer.mozilla.org/en-US/docs/Web/Guide/Mobile)：智能手机的普及让移动端的流量正在逐步赶超PC端
- [Javascript内存管理](https://developer.chrome.com/devtools/docs/javascript-memory-profiling?hl=figoogle)：SPA长期运行需要注意内存泄露的问题
- [High Performance JavaScript(Build Faster Web Application Interfaces)](http://www.amazon.com/Performance-JavaScript-Faster-Application-Interfaces/dp/059680279X/ref=sr_1_1?s=books&ie=UTF8&qid=undefined&sr=1-1&keywords=high+performance+javascript)
- [Best Practices for Speeding Up Your Web Site](https://developer.yahoo.com/performance/rules.html)：重要技能
- 读jQuery源码


## 书籍推荐

以下是一些不错的书籍、网站、教程。

- [《Ajax完全手册》](http://www.amazon.cn/Ajax%E5%AE%8C%E5%85%A8%E6%89%8B%E5%86%8C-%E6%B3%A2%E7%BB%B4%E5%B0%94/dp/B001N6R0Q2/ref=sr_1_2?ie=UTF8&qid=1410104972&sr=8-2&keywords=ajax%E5%AE%8C%E5%85%A8%E6%89%8B%E5%86%8C)：一本Ajax很不错的书，例子多，实现了一个Ajax库
- [《Pro AngularJS》](http://www.amazon.com/Pro-AngularJS-Experts-Voice-Development/dp/1430264489/ref=sr_1_1?s=books&ie=UTF8&qid=1410105152&sr=1-1&keywords=pro+angularjs)：AngularJS很好的书籍
- [《Pro jQuery》](http://www.amazon.com/Pro-jQuery-Experts-Voice-Development/dp/1430263881/ref=sr_1_1?s=books&ie=UTF8&qid=1410099103&sr=1-1&keywords=pro+jquery)和[Learning jQuery](http://www.amazon.com/Learning-jQuery-Fourth-Jonathan-Chaffer/dp/178216314X/ref=sr_1_1?s=books&ie=UTF8&qid=1410099243&sr=1-1&keywords=learning+jquery)：两本jQuery书籍
- [《精通CSS：高级web标准解决方法》](http://www.amazon.com/CSS-Mastery-Advanced-Standards-Solutions/dp/1430223979/ref=sr_1_1?ie=UTF8&qid=1410137090&sr=8-1&keywords=css+mastery+advanced+web+standards+solutions)：CSS实用技能
- [JavaScript Memory Profiling](https://developer.chrome.com/devtools/docs/javascript-memory-profiling?hl=figoogle)
- [《HTML5 canvas》](http://www.amazon.com/HTML5-Canvas-Steve-Fulton/dp/1449334989/ref=sr_1_1?ie=UTF8&qid=undefined&sr=8-1&keywords=html5+canvas)：canvas是HTML5带来的一个很棒的特性，可以做很多事情
- [《Pro Node.js for Developers》](http://www.amazon.com/Pro-Node-js-Developers-Colin-Ihrig/dp/1430258608/ref=sr_1_1?ie=UTF8&qid=undefined&sr=8-1&keywords=pro+nodejs+for+developers)：node发展太快。里面很多API都过时了，尽量参考官方API，不过还是值得一看
- [《Node.js in Action》](http://www.amazon.com/Node-js-Action-Mike-Cantelon/dp/1617290572/ref=sr_1_1?ie=UTF8&qid=1410138522&sr=8-1&keywords=node+js+in+action)：很不错的Node入门书籍
- [《Single Page Web Applications: JavaScript end-to-end》](http://www.amazon.com/Single-Page-Applications-end---end/dp/1617290750/ref=sr_1_1?s=books&ie=UTF8&qid=1410138650&sr=1-1&keywords=single+page+application)：一步步完成简单SPA
- [天镶大神的博客](http://lingyu.wang/#/home)


## 一些个人经历

### [qiu-deqing](https://github.com/qiu-deqing)的学习经历

### [asd123freedom](https://github.com/asd123freedom)的学习经历

### [sue891206](https://github.com/sue891206)的学习经历

### [Sheetaa](https://github.com/Sheetaa)的学习经历

### [suikaxin](https://github.com/suikaxin)的学习经历

### [quanxi613](https://github.com/quanxi613)的学习经历

### [LingyuCoder](https://github.com/LingyuCoder)的学习经历

### [zwl4488](https://github.com/zwl4488)的学习经历

### [MrRaindrop](https://github.com/MrRaindrop)的学习经历

### [zyr2014](https://github.com/zyr2014)的学习经历