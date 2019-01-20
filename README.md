JavaScript Use Global Package Demo
==================================

有的package太大或者每次都需要下载、编译很长时间的（如puppeteer），为了方便demo，
可以把它们安装为global，然后在demo中引用。这样只需要下载一次即可。

```
npm install -g lodash
npm run demo
```
