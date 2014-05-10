#PUI

PUI是拍拍前端的UI组件框架，用于实现页面上的交互效果。

写这个框架的目的，是为了从代码层面上规范UI组件代码。让开发者不再关注插件如何生成，仅需要实现具体的业务逻辑，其他则交给PUI完成。

###Getting Started

####创建一个插件
```js
Pui.widget('pp.plugin',{
    //your code
})
```
调用方法：
```js
$('#ID').plugin();
```

非常简单吧。


###TODO

这仅仅是个开始，后续会逐步完善其功能。

1. 通过规范的代码注释，自动生成组件说明文档。
2. 加入组件模板及实用功能函数。

### Changelog
* v0.1 项目创建

### Other
[My Blog](http://www.ghugo.com)