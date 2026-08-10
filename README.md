# 光鸭云盘助手
当前版本：**v1.0**

正式仓库：`https://github.com/liheng-lk/guangya-helper`

## 功能

- 光鸭云盘 App 扫码授权登录
- 手机号短信验证码登录
- Token 自动刷新
- 文件浏览、上传、下载、删除、重命名、新建目录
- MoviePilot 外部存储挂载与整理上传
- 可开关的上传进度监控
- 临时 DNS / OSS 上传异常自动重试
- HTTP Range 流式代理
- WebDAV
- Vue Federation Page / Config 管理界面
- PC / 平板 / 手机响应式界面

## 安装

MoviePilot 自定义插件源：

```text
https://github.com/liheng-lk/guangya-helper
```

刷新插件市场后安装 **光鸭云盘助手**。

## 版本体系

本独立项目从 **v1.0** 开始重新计版本。v1.0 以迁移前 Guangyadisk 当前稳定开发成果为功能基线，不继承上游历史版本号。

## 致谢与参考

本项目整合和参考了开源社区的既有实现与研究成果，包括：

- ShukeBta / Guangyadisk：早期 GuangYaDisk / MoviePilot 存储实现与历史代码基础；
- KoWming / MoviePilot-Plugins：光鸭云盘扫码授权流程参考；
- DDSRem-Dev / guangyaclient：光鸭认证、短信登录及接口行为参考；
- jxxghp / MoviePilot-Plugins：MoviePilot V2 插件及 Vue Federation 开发规范参考。

感谢上述项目作者及其他历史贡献者。具体代码继续遵守对应开源许可证及版权声明。

## License

MIT。详见 LICENSE。
