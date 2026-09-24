# 菲比 / Phoebe · Codex 桌宠

**中文** · [English README](README_EN.md)

基于《鸣潮》（Wuthering Waves）菲比（Phoebe）形象制作的非官方 Codex desktop pet。仓库提供两套 Codex v2 spritesheet 桌宠：**菲比·蹦一下**与**菲比·坐好了**。动作灵感来自「鸣潮·致予新世界动态表情包」中的菲比「坐好了」表情包。

![菲比 Codex 桌宠横版预览：蹦一下与坐好了](assets/social-preview.png)

## 两个版本

| 版本 | 安装目录 | 动作特点 |
| --- | --- | --- |
| 菲比·蹦一下 | `pets/phoebe-evidence/` | 平时坐着；悬停时起身跳一下；工作时播放专属动作。 |
| 菲比·坐好了 | `pets/phoebe-storyboard/` | 常态眨眼、歪头；悬停时保持坐姿回应；工作时坐着敲电脑。 |

两个版本左右拖动时使用相同的奔跑动作。以下预览复用仓库现有的动画 WebP。

| 版本 | 常态 | 鼠标悬停 | 工作中 |
| :---: | :---: | :---: | :---: |
| 菲比·蹦一下 | ![蹦一下：坐姿常态](assets/original-idle.webp) | ![蹦一下：起身跳跃](assets/original-hover.webp) | ![蹦一下：工作动作](assets/original-coding.webp) |
| 菲比·坐好了 | ![坐好了：眨眼、歪头](assets/storyboard-idle.webp) | ![坐好了：坐姿回应悬停](assets/storyboard-hover.webp) | ![坐好了：坐着敲电脑](assets/storyboard-coding.webp) |

## 安装

在克隆或下载的仓库根目录运行下列命令。只安装一个版本时，只运行对应的 `cp` 命令。

```bash
mkdir -p ~/.codex/pets
cp -R pets/phoebe-evidence ~/.codex/pets/
cp -R pets/phoebe-storyboard ~/.codex/pets/
```

然后在 Codex 桌面版的宠物选择界面选择「菲比·蹦一下」或「菲比·坐好了」。两个版本可以同时安装。

## Codex v2 素材格式

每个版本都包含 `pet.json` 和 `spritesheet.webp`。两份配置的 `spriteVersionNumber` 均为 `2`，`spritesheetPath` 均指向同目录下的 `spritesheet.webp`。上表展示了常态、悬停和工作中的动画；拖动奔跑动作也包含在两套桌宠素材中。

## 目录结构

```text
.
├── README.md                    中文说明
├── README_EN.md                 English README
├── assets/
│   ├── social-preview.png       GitHub Social Preview 封面
│   ├── original-*.webp          「蹦一下」动作预览（idle / hover / coding）
│   └── storyboard-*.webp        「坐好了」动作预览（idle / hover / coding）
└── pets/
    ├── phoebe-evidence/
    │   ├── pet.json
    │   └── spritesheet.webp
    └── phoebe-storyboard/
        ├── pet.json
        └── spritesheet.webp
```

## 设置 GitHub Social Preview

仓库维护者可在 GitHub 仓库页面依次进入 **Settings → General → Social preview → Edit → Upload an image…**，选择本地仓库中的 `assets/social-preview.png` 上传。GitHub 界面位置或按钮文案可能略有变化；如果没有看到 **General**，可在 **Settings** 页面直接寻找 **Social preview**。将图片加入仓库本身不会自动设为社交预览。

## 版权与免责声明

© 2026 IraCyoee。本声明仅涉及本项目中有权主张的原创贡献。

《鸣潮》、菲比及相关原作内容的权利归库洛游戏及相应权利人所有。本项目为非官方二创，与《鸣潮》官方无关；本声明不授予原作内容的使用许可。
