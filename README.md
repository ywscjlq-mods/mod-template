# DSP Mod 脚手架 (通用模板)

## 用法

基于此模板创建新 MOD：

1. GitHub 上点 **Use this template** → 新仓库名 = MOD 名
2. 编辑 `Plugin.cs` 修改 GUID 和类名
3. 运行 `build.bat` 编译

## 文件说明

| 文件 | 作用 |
|------|------|
| `Plugin.cs` | BepInEx + Harmony 骨架 |
| `build.bat` | 一键编译 + 部署到 DSP |
| `.gitignore` | 排除 .bak / bin / obj |
| `README.md` | 模板说明 |

## 构建

```powershell
$env:DSP_DIR = "F:\SteamLibrary\steamapps\common\Dyson Sphere Program"
.\build.bat
```
