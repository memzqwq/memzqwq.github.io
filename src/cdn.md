# cdn.koishi514.ml

类似jsdelivr的内容分发网络

## /npm

引用npm中的资源

示例：

请求
```
GET /npm/js-cookie
```

响应
```
Content-Type: application/json

TL;DR
```

## /gh

引用github中的资源

示例：

请求
```
GET /gh/octocat/Hello-World@master/README
```

响应
```
Hello World!
```

## /combine

结合多个文件

示例：

请求
```
GET /combine/gh/MSKNET/Url-Shorten-Worker@main/API.js,npm/tieba-api/index.js
```

响应
```
=== Content of the first file ===

=== Content of the second file ===
```
