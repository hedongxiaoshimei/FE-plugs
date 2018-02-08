# Web 前端常用插件

## <a name="tool">工具类</a>
* 方便操作对象，数组等的工具库
    * [underscore.js](http://underscorejs.org/)
    * [lo-dash](https://lodash.com/) 与underscore.js的api基本一致。与underscore比其优势是，效率高；可自定义构建
    * [Sugar](https://github.com/andrewplummer/Sugar/) 在原生对象上增加一些工具方法
    * [functional.js](https://github.com/leecrossley/functional-js/) 提够了一些Curry的支持
    * [bacon.js](https://github.com/baconjs/bacon.js/) 函数式编程，cool
    * [streamjs](https://github.com/winterbe/streamjs) 用流的方式来对数组，对象进行系列操作
* 数据类型
    * 字符串
        * [strman](https://github.com/dleitee/strman) 字符串操作库。它为各种实用程序、格式选项和字符串转换，提供了超过 60 种实用的方法。
    * 数字
        * [BigDecimal.js](https://github.com/dtrebbien/BigDecimal.js) 提高精度的数字操作
    * 对象
        * [Watch.js](https://github.com/melanke/Watch.JS) 监视对象或属性的变化
    * 时间
        * [moment](http://momentjs.com/)
        * [datejs](http://www.datejs.com/)
    * 正则
        * [rewrap](https://github.com/taijiweb/rewrap) 正则工具库。相关插件[regexp-frequent](https://github.com/taijiweb/regexp-frequent),[rewrap-patch](https://github.com/taijiweb/rewrap-patch)
    * [parameter](https://github.com/node-modules/parameter) 验证参数的格式
* 异步流程控制
    * 发布订阅
        * [eventproxy](https://github.com/JacksonTian/eventproxy) 朴灵出品
        * [Arbiter.js](http://arbiterjs.com/) [详细](detail/Arbiter)
    * [q](https://github.com/kriskowal/q/) Promise风格的
    * [Async.js](https://github.com/caolan/async/)
* 加载器
    * [little-loader](https://github.com/walmartlabs/little-loader) JS 加载器。Webpack 不支持加载外部js，可用这个。
* mock
    * [Mock.js](https://github.com/nuysoft/Mock) 生成随机数据和mock Ajax 请求
    * [jquery-mockjax](https://github.com/jakerella/jquery-mockjax) [mock](http://baike.baidu.com/view/2445748.htm) ajax请求
* 浏览器探测
    * [Bowser](https://github.com/ded/bowser) 探测具体浏览器和版本
    * [ua-parser-js](https://github.com/faisalman/ua-parser-js) 探测具体浏览器和版本，操作系统，设备类型等
* 调试
    * [vConsole](https://github.com/WechatFE/vConsole) 轻量、可拓展、针对手机网页的前端开发者调试面板插件。微信前端做。
    * [console-polyfill](https://github.com/paulmillr/console-polyfill/) 能放心的使用 console.log()之类的console方法
    * [log](https://github.com/adamschwartz/log) 让控制台输出的log有样式
* [uri.js](https://github.com/medialize/URI.js) uri操作
* [Cookie](https://github.com/ScottHamper/Cookies) 增删改cookie的工具库
* [store.js](https://github.com/marcuswestin/store.js/) 对 localStorage 的封装。兼容 IE6+。
* [director](https://github.com/flatiron/director) 前端路由库 [详细](detail/director)
* [JSDoc](http://usejsdoc.org/) 根据javascript文件中注释的信息，生成API文档 [详细](detail/JSDoc)
* [hotkeys](http://jslite.io/hotkeys/) 键盘事件的封装
* [MD5](https://github.com/pvorb/node-md5) 用 MD5 的方式加密文件的库
* [Exif.js](https://github.com/exif-js/exif-js) 读取 JPEG 图片的拍摄信息。可以通过拍摄信息中的 Orientation 来解决 ios 手机上传竖拍照片会逆时针旋转90度的问题。
* [download](https://github.com/kevva/download) 实现下载的库。支持 url 和流。 [详细](detail/download)
* 模板引擎
  * [Handlebar](http://handlebarsjs.com/installation.html)
  * [Ejs](http://www.embeddedjs.com/)
  * [Jade](http://jade-lang.com/)
* 生成pdf
  * [jsPDF](https://github.com/MrRio/jsPDF) 在浏览器端生成 pdf。
  * [pdfkit](http://pdfkit.org/)
* [compass.js](http://ai.github.io/compass.js/) 指南针。只有在手机浏览器上才能用。
* [中国行政区域数据](https://github.com/airyland/china-area-data)

## <a name="browser-strong">浏览器增强类</a>
### 让一些旧浏览器变牛逼的库
* [Selectivizr](https://github.com/keithclark/selectivizr)  让IE 6-8一些的css3选择器
* [ieBetter](https://github.com/zhangxinxu/ieBetter.js) 让ie6-8有高级浏览器的特性
* [ExplorerCanvas](https://github.com/arv/ExplorerCanvas) 让IE8-的浏览器支持canvas
* [CSS3 Pie](http://css3pie.com/) 让IE6-9支持border-radious,box-shadow,linear-gradient。 可以使用.htc文件（注意Mine type）或.js文件。在用Pie.js时，box-radious的元素有背景色时，不显示背景色。。。
* [formFive](http://etiennetalbot.github.io/formFive/) 让旧的浏览器支持HTML5表单的一些特性，如 placeholder,autofocus
* [https://github.com/anselmh/object-fit](https://github.com/anselmh/object-fit) 让浏览器支持`object-fit`这css规则
* [HTML5 Cross Browser Polyfills](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills) 一堆Polyfills
* [flexibility](https://github.com/jonathantneal/flexibility) 让旧的 IE 也支持 Flexbox

### 选择器增强
* [Lining.js](https://github.com/zmmbreeze/lining.js) 让浏览器实现类似`::nth-line(), ::nth-last-line()`的效果

### CSS 兼容性
* [prefixfree](https://github.com/LeaVerou/prefixfree/) 根据 caniuse.com 数据库自动补全 CSS 私有前缀

## <a name="form">表单类</a>
* [jquery-file-upload](https://github.com/blueimp/jQuery-File-Upload) 上传文件组件 [详细](detail/fileUpload)
* [zTree](http://www.treejs.cn/v3/main.php) 文件树形视图控件 [详细](detail/ztree)
* [Treed](http://colorify.rocks/index.html) 树编辑器。感觉展示的感觉很像思维导图
* [FileAPI](https://github.com/mailru/FileAPI) 对文件选择框内的文件的一些处理

### 表单验证
* [.Validate](https://github.com/jzaefferer/jquery-validation) [详细](detail/validate)
* [jQuery-Validation-Engine](http://posabsolute.github.io/jQuery-Validation-Engine/)


## <a name="img">图片类</a>
* [holderjs](http://imsky.github.io/holder/) 生成占位图片
* lazyload
* [imagesLoaded](http://desandro.github.io/imagesloaded/) 选取的图片都加载好后执行调回
* [CSSgram](https://github.com/una/CSSgram) 用CSS3的Filter实现Instagram滤镜的库

## <a name="icon">图标类</a>
* [Icon Font汇总](https://github.com/lvwzhen/iconpark)
* SVG做的图标
    * [svgicons](http://svgicons.sparkk.fr/)
    * [iconic](https://useiconic.com/icons/)
    * [hybicon.js](http://hybicon.softwaretailoring.net/documentation.html) 带交互效果。如 hover, click。 [详细](detail/hybicon)
* HTML字符实体图标
    * http://www.amp-what.com/
* [transformicons](http://www.transformicons.com/) 图标点击时，会有一些变换效果。如，加号变成叉号
* [css3patterns](http://lea.verou.me/css3patterns/) css3 做的可平铺纹理。浏览器兼容性不好。

## <a name="ui">UI 组件类</a>
### 拖拽
* [dragula](https://github.com/bevacqua/dragula) 支持Draggable，Dropable和Sortable。感觉比jqueryUI的轻量级，好用的样子

### 时间选取组件
* [foundation-datepicker](http://foundation-datepicker.peterbeno.com/example.html)
* [DatePicker](https://github.com/foxrunsoftware/DatePicker/) 一个简单的日历 [详细](detail/datepicker)
* [full calendar](http://fullcalendar.io/) 支持脱放的方式来改变待办事宜的时间
* [Simple Events Calendar](http://preview.codecanyon.net/item/simple-events-calendar-js/full_screen_preview/462149?ref=themespotters) 外观很喜欢。收费 5$
* [jQuery ui datepicker](http://jqueryui.com/datepicker/) 经典，不是很好看
* [pickadate](http://amsul.ca/pickadate.js/) 轻量级，手机友好的，漂亮。但貌似只能在弹出层中显示，而没有下拉这种方式显示。
* [zebra-datepicker](http://stefangabos.ro/jquery/zebra-datepicker/) 可配置性很强。但貌似只能在弹出在右上方。。。
* [bootstrap-datepicker](http://www.eyecon.ro/bootstrap-datepicker/) bootstrap风格。
* [dateRangePicker](https://github.com/dangrossman/bootstrap-daterangepicker) 选取时间段。bootstrap风格。该组件依赖Twitter Bootstrap, Moment.js和jQuery.

### 滚动无限加载
* [vue-recyclerview](https://github.com/hilongjw/vue-recyclerview) 高性能的滚动无限列表加载。为了提高性能，代码有重复利用 DOM。

### 自定义滚动条
* [perfect scrollbar](https://github.com/noraesae/perfect-scrollbar) 轻量级的滚动条。外观与mac上chrome的滚动条一样。
* [iscroll](http://iscrolljs.com) 在移动设备上用不错

### 加载(Loding)效果
* [CSS Spinners](https://github.com/jlong/css-spinners) CSS做的
* [Loaders.css](https://connoratherton.com/loaders) CSS做的


### HTML5播放器
* [jwplayer](https://www.jwplayer.com/) 被大量网站使用
* [html5media](https://html5media.info/) 简单的h5player，轻量级
* [jplayer](http://jplayer.org/) 功能强大，可换肤


### 弹出框
* [Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup) 兼容PC，Mobile。还不错，有5k+的star
* [layer](https://github.com/sentsin/layer) 国人开发的，兼容ie6+。不喜欢其调用方式。

### 二维码
* [QR Code Generator](https://github.com/kazuhikoarase/qrcode-generator/tree/master/js)
* [jquery-qrcode](https://github.com/jeromeetienne/jquery-qrcode) 生成二维码图片的jQuery 插件，很好用。该插件是基于 QR Code Generator 开发的。


### 分享到SNS
* [JiaThis](http://www.jiathis.com/) 生成分享代码。



