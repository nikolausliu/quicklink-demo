[quicklink](https://www.npmjs.com/package/quicklink) 通过在空闲时间加载视口内链接来加快后续页面加载速度。

可以监听整个页面，也可以监听页面中的某个 Element，当有链接进入视口范围，就会去 prefetch。

主要原理是动态插入 `<link rel="prefetch">` 标签。
