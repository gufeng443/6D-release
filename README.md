# 6D Release Public

本公开仓库只用于提供：

- `6D 桌面工作台` 的公开下载页
- `latest.json` 更新清单
- GitHub Releases 下载入口

公开主页：

- https://gufeng443.github.io/6D-release/

仓库中不应包含：

- 主程序源码
- 授权服务端或后台管理代码
- 激活码、机器码、密钥或任何私密配置
- 用户账号数据、日志、导出包或测试样本

使用说明：

- 下载发布 zip 后，请完整解压整个目录再运行 `gui.exe`
- 不要只复制单个 exe
- 下载完成后可使用页面展示的 SHA-256 核对安装包
- 发布包允许包含“批量同步好友”所需的设备侧辅助 APK；它不是 WhatsApp/WS 更新 APK，也不提供 APK 下载、安装或 APP 更新功能

发布页会优先读取根目录 `latest.json` 展示当前版本、文件大小和校验值；读取失败时回退到 GitHub Releases 最新页。
