# js规范
## 1 参考[汽车之家js规范](http://10.168.0.151/codeguide/es5/javascript-style-guide.html)
## 2 车商城部分
### 2.1 与UI相关的模块都封装到jQuery和zepto插件中使用
### 2.2 所有模块通过prototype的方式实现面向对象，通过暴露属性、方法、事件给后端开发人员使用，禁止模块内部混杂业务逻辑
### 2.3 每个模块一个js文件，发布时使用co.ashx合并
