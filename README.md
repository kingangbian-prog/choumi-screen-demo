# 臭咪副屏
用于独立小屏的 AI 进度监控交互 Demo：原创萌宠、星空壁纸、半透明状态卡与底部 Dock。

所有任务、阶段与成果均为模拟数据。不连接真实账号，不读取真实文件。

支持任务筛选、确认/拒绝、暂停/继续、模拟重试、成果已读与独立验收、日夜与黑白造型、减少动态。状态仅保存在当前浏览器 localStorage。

## 本地启动
```sh
python3 -m http.server 4186 --bind 127.0.0.1
```
打开 http://127.0.0.1:4186/ 。无第三方依赖。

## 参考
视觉交互灵感来自 [Codila Grok Bot Wallpaper](https://0xcodila.com/grokbot-wallpaper/) 与其 [公开仓库](https://github.com/Bodila51/grokbot-wallpaper)。该仓库未发现项目级软件许可，因此本 Demo 的代码与 SVG 猫角色独立编写，未复制参考项目代码、角色或素材。

已检查 1280×800、1024×600、800×480、390×844 布局；尚未在实体副屏和所有浏览器上测试。
