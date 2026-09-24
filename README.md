# 菲比 Codex 桌宠

给 Codex 桌面版准备的两个菲比桌宠版本。动作灵感来自 `鸣潮·致予新世界动态表情包` 中菲比的「坐好了」表情包。

## 动作预览

| 版本 | 常态 | 鼠标悬停 | 工作中 |
| :---: | :---: | :---: | :---: |
| 原版 | ![原版常态：坐姿](assets/original-idle.webp) | ![原版悬停：起身跳跃](assets/original-hover.webp) | ![原版工作动作](assets/original-coding.webp) |
| 分镜版 | ![分镜版常态：坐姿眨眼、歪头](assets/storyboard-idle.webp) | ![分镜版悬停：坐姿回应](assets/storyboard-hover.webp) | ![分镜版工作：坐着敲电脑](assets/storyboard-coding.webp) |

分镜版的常态、悬停和工作动作都保持坐姿；原版悬停时会起身跳。左右拖动的奔跑动作在两个版本中相同。

## 安装

在仓库根目录运行。只装一个版本的话，运行对应的 `cp` 命令即可。

```bash
mkdir -p ~/.codex/pets
cp -R pets/phoebe-evidence ~/.codex/pets/
cp -R pets/phoebe-storyboard ~/.codex/pets/
```

然后在 Codex 的宠物选择界面选择“菲比”或“菲比·分镜版”。两个版本可以同时安装。
