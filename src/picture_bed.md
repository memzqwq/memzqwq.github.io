# pic.koishi514.ml

图床

## /up

上传图片

示例：

请求
```
POST /up
Content-Type: multipart/form-data

------WebKitFormBoundarypKnYBwSDs9af5ObJ
Content-Disposition: form-data; name="file"; filename="Untitled.png"
Content-Type: image/png


------WebKitFormBoundarypKnYBwSDs9af5ObJ--
```

响应
```
{"error": 0, "message": "File uploaded successfully.", "hash": "d965c1680722739c02e11ddcd5cfd66367bffaa0d41bdee1a2232975", "type": "png"}
```

## /down

自动判断请求头，返回webp或jpg格式的图片

## /jpg

返回jpg格式的图片，若指定格式不存在且存在其他格式的图片，会自动转换

## /png

返回png格式的图片，若指定格式不存在且存在其他格式的图片，会自动转换

## /webp

返回webp格式的图片，若指定格式不存在且存在其他格式的图片，会自动转换
