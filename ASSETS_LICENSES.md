# 资源与许可证

车库、路面、标线、动态车轮和力箭头由本工程的 Godot 原生几何及脚本生成；发动机、轮胎、换挡和悬挂声音由 `scripts/telemetry/vehicle_audio.gd` 根据物理状态实时合成。未导入第三方音乐或音效。

## 1990 Honda NSX 三维模型

- 作品：**1990 Honda NSX**
- 作者：**lilModels**（Sketchfab 用户 `gaelgiraudo10`）
- 原始页面：https://sketchfab.com/3d-models/1990-honda-nsx-b9c541ef47004870868bb3a2f767b85d
- 许可：Creative Commons Attribution 4.0 International（CC BY 4.0）
- 许可正文：https://creativecommons.org/licenses/by/4.0/
- 本地文件：`assets/vehicles/nsx_na1/1990_honda_nsx.glb`
- 本项目处理：按公开轴距统一缩放、绕 Y 轴旋转并对齐物理轮心；运行时隐藏模型自带固定轮组，改用四轮物理状态驱动的动态轮组。原始 GLB 文件内容未重写。

模型由用户通过 Sketchfab 的正常登录下载流程取得，原始 GLB 自带的 `asset.extras` 也记录了同一作者、来源、作品名和 `CC-BY-4.0` 许可。文件哈希及接入尺寸记录见 `assets/vehicles/nsx_na1/README.md`。

项目自写 GDScript、场景文件与程序化资源版权由项目所有者保留。本仓库未提交引擎二进制或导出模板；Windows 便携包中的 EXE 包含 Godot 4.6.3 引擎，PCK 为本项目内容及上述 CC BY 4.0 模型。

Godot Engine 为 MIT 许可，版权归 Godot Engine contributors 及 Juan Linietsky、Ariel Manzur；许可与版权声明见 [Godot 官方许可页](https://godotengine.org/license/)。引擎集成的 Jolt Physics 源项目亦为 [MIT 许可](https://github.com/jrouwe/JoltPhysics/blob/master/LICENSE)。便携包随附本文件以提供归属和许可入口。
