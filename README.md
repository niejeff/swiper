# Swiper Social

## 功能列表

### 公共模块

- [x] Json 接口处理
- [x] 日志处理
- [x] 统一错误处理
- [x] 短信 API 接入
- [x] Celery 异步任务处理
- [x] Redis 底层接口封装
- [x] 缓存处理

### 个人模块

- [x] 用户数据模型设计
- [x] 手机注册
- [x] 短信验证登录
- [x] 获取个人资料
- [x] 修改个人资料
- [x] 头像上传
  - 上传图片
  - 异步传入七牛云

### 交友模块

- [x] 数据模型设计
- [x] 获取推荐列表
- [x] 匹配检查
- [x] 喜欢
- [x] 超级喜欢
- [x] 不喜欢
- [x] 反悔
- [x] 查看喜欢过我的人

### 好友模块

- [x] 好友表结构设计
- [x] 查看好友列表
- [x] 查看好友信息

### VIP 模块

- [x] 权限数据模型设计
- [x] 权限检查逻辑处理
- [x] 权限详情接口
- [x] 权限: 超级喜欢 / 反悔 / 查看被喜欢

### 聊天模块

- [x] WebSocket 底层接口设计及封装
- [x] Tornado 加载 Django 模块处理
- [x] Tornado 与 Redis 的 Pub / Sub 结合处理消息收发
- [x] 发送消息
- [x] 接收消息
- [x] 拉取离线消息

### 运维、部署

- [x] 部署及维护脚本
  - 服务器部署脚本
  - 代码上线脚本
  - 服务启动、停止、重启
- [x] 异常日志打印
- [x] 日志自动切割
- [x] 异常邮件告警
- [ ] 进程监控

## TODO

### 爬虫模块

- [ ] Scrapy 加载 Django 模块处理
- [ ] “探探”数据抓取
  - 定义基本爬虫模型
  - 抓包工具抓取 App 接口数据
  - 模拟不同用户抓取全国各地用户
  - 接入 Django 数据模型, 数据入库
- [ ] 分布式爬虫处理

### 前端

- [ ] 个人页面
- [x] 滑动页面
- [ ] 陌生人信息页
- [ ] 好友列表页面
- [ ] 聊天页面

### 其他

- [ ] Docker 部署
- [ ] 好友推荐算法
