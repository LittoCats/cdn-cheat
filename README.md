# cdn-cheat

这是一个假的CDN，只是日常使用的一引起小工具


## Macdown 流程图插件

在 macdown 源文件中引入该文件

```
<script src="http://cdn.jsdelivr.net/gh/LittoCats/cdn-cheat/macdown-flowchart.js"></script>
```

声名为 `flowchart` 的代码块

```flowchart

```

将渲染为流程图，自动替换掉对应的代码块

这个功能不支持导出为 pdf,因为需要在显示时运行 javascript 脚本