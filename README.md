# nd-tab

[![spm version](http://spmjs.io/badge/nd-tab)](http://spmjs.io/package/nd-tab)

> 提供了简单的tab标签页的切换

## 安装

```
$ spm install nd-tab --save
```

## 使用

```js
var Tab = require('nd-tab');

new Tab({
      itemTab:'.tab',
      tabs:'.tabs',
      itemPanel:'.panel',
      panels:'.panels',
      initIndex:0
    });

    或者
    
 new Tab({
      itemTab:'.tab',
      itemPanel:'.panel'
    });    
    
// use Tab
```
