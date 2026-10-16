# APK 逆向工程 Skill（Operit）

一份用于 **Operit** 的 APK 逆向通用流程 Skill（操作手册）。

## 这是什么

Skill 是给 AI 看的"说明书"，本身不执行命令。装上它之后，AI 就知道逆向 APK 该按什么流程走、每一步用什么工具。

## 核心流程

```
识别加固 →（有壳才脱壳）→ 反编译 → 定位目标 → 修改 → 产出到工作区 → 用户打包 → 验证
```

## 安装方法

1. 下载本仓库
2. 把整个文件夹放到：
   `/sdcard/Download/Operit/skills/apk-reverse-engineering/`
3. 确保该目录内有 `SKILL.md`
4. 在 Operit 里打开对应 Skill 开关

## 依赖工具包

| 工具 | 用途 |
|------|------|
| `mt` | 反编译/改 smali/重打包 |
| `apk_reverse` | inspect/decode/jadx/build/sign/search |
| `加固特征库` | 识别加固壳 |
| `56al_tuoke` | 在线脱壳 + dex 修复 |
| `logfox_toolkit` | 崩溃日志/冒烟测试 |

## 说明

仅供学习研究使用，请遵守当地法律法规。
