# 光鸭云盘助手

**Guangya Helper** 是由 `liheng-lk` 维护的 MoviePilot V2 光鸭云盘存储插件。

当前正式版本：**v1.0**  
正式仓库：`https://github.com/liheng-lk/guangya-helper`

## 功能
- 光鸭云盘 App 扫码授权登录 / 手机号短信登录
- Token 自动刷新
- 文件浏览、上传、下载、删除、重命名、新建目录
- MoviePilot 外部存储与整理上传
- 可开关的实时上传进度日志
- DNS / OSS 临时故障自动重试
- 上传完成目标文件可见性兜底确认
- HTTP Range 流式代理与 WebDAV
- Vue Federation Page / Config，适配 PC、平板、手机

## 安装
MoviePilot 自定义插件源：
```text
https://github.com/liheng-lk/guangya-helper
```

## 版本
本独立项目从 **v1.0** 重新开始版本体系；v1.0 以迁移时 `Guangyadisk/main` 的最新稳定代码为功能基线。

## 致谢与参考
- ShukeBta / Guangyadisk：早期存储实现与历史代码基础
- KoWming / MoviePilot-Plugins：扫码授权流程参考
- DDSRem-Dev / guangyaclient：认证、短信登录及接口行为参考
- jxxghp / MoviePilot-Plugins：MoviePilot V2 与 Vue Federation 开发规范参考

## License
MIT。原版权声明依许可证要求继续保留。
