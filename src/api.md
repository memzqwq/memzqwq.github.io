# api.koishi514.ml

API接口

## /mc

检测minecraft服务器状态，支持java版与基岩版

示例1：

请求
```
GET /mc/je?ip=2b2t.org
```

响应
```
Content-Type: application/json

{"status": true, "online_player": 477, "max_player": 1}
```

示例2：

请求
```
GET /mc/be?ip=play.lbsg.net&port=19132
```

响应
```
Content-Type: application/json

{"status": true, "online_player": 7606, "max_player": 17606}
```
