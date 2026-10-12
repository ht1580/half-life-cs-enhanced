# Half-Life 拓展

当前正式版：2026.10.11-performance2。已完成本轮完整安装组合的 Steam 前台全屏、输入和人工画面验收。

[当前正式版下载](https://github.com/ht1580/half-life-cs-enhanced/releases/latest)

固定下载地址，ZIP 内含安装 EXE、中文说明与校验文件：

[Performance2 安装包](https://github.com/ht1580/half-life-cs-enhanced/releases/download/v2026.10.11-performance2/HalfLife-Expansion-2026.10.11-Performance2.zip)

包含 30 把 TF 武器、17 把 CS 武器、28 把命名近战武器、三套运动预设、剧情与社区地图、分层地图、训练场、AI 对战和原生拓展选项。完整用法与按键见包内中文说明。

本轮优化各类着色器缓存文件选择、GPU 环形缓冲重复 fence 查询、原生设置每帧重复预处理，以及准心顶点数组分配；保持现有画质与功能。有限本机加载对照未见明显回退，尚未证明整体加载提速或 FPS 提升，不保证所有场景和硬件获得相同效果。

先保存并退出游戏，运行安装 EXE，选择 Steam Half-Life 目录。安装器自动备份，保留存档、设置、旧文件和回滚备份；从 Steam 游戏库 Half-Life“开始”进入。需要已登录且拥有 Half-Life 的 Steam；安装包不含原版游戏或用户存档。ZIP 另含中文使用说明与 SHA256。

实际检查包括六项私有流程回归、Steam 原游戏入口、旧存档、原生设置应用/取消与开镜恢复。1920×1200 的 16:10 画面拉伸至 2560×1440 的 16:9 屏幕，人工确认无黑边；自动输入检查中四方向移动正常，鼠标累计转向660.27度。测试后的个人设置及122个本机存档已核对保留。

网络协议及相关网络 DLL 保持 training-bots 的 `cw_20261011_net7`，沿用该版同机双客户端证据；performance2 未重复联机测试。不同物理电脑与公网穿透仍未实机验证。

资源署名与源码、插件许可随包提供。
