# selected.js
#### selected.js 这是一个可以选中一段文字，然后出现一个选择框，提示用那种搜索引擎去搜索该段文字。

##### 欢迎点击链接访问 https://xumengzi.github.io/selectedJs/selectedJs.html

搜索引擎支持自由配置，目前支持google,baidu,bing,yahoo,sougou。
使用也非常简单，在页面里添加如下代码即可：
```
//这是一个数组，可以设置的搜索引擎有google,baidu,bing,yahoo,sougo
selected.set({
    searchEngine:['baidu'],
    newTab: false,
    background: '#fff',
    zIndex: 9999,
});	
```
