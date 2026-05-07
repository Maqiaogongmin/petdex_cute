# Aka Pilot Codex Pet

这是一个本地自用的 Codex 桌面宠物项目。宠物名为 **Aka Pilot**，是基于用户提供的本地角色参考图提炼出的 chibi / pixel-adjacent 红色驾驶员风格桌宠。

## 当前版本

当前安装版本是 v2：

- 金棕 / 蜂蜜棕双马尾发色
- 蓝色眼睛
- 红色驾驶服
- 橙红胸部细节
- 绿色领口点缀
- 更可爱、更柔和的小骄傲表情

可直接安装的宠物包位于：

```text
pets/aka-pilot/
├── pet.json
└── spritesheet.webp
```

## 项目结构

```text
runs/aka-pilot/      # v1 生成记录，保留作对照
runs/aka-pilot-v2/   # v2 生成记录、最终图集、QA 和预览视频
pets/aka-pilot/      # 可直接放入 Codex 自定义宠物目录的成品包
```

v2 的主要验收文件：

```text
runs/aka-pilot-v2/final/validation.json
runs/aka-pilot-v2/qa/review.json
runs/aka-pilot-v2/qa/contact-sheet.png
runs/aka-pilot-v2/qa/videos/
```

## 安装

把 `pets/aka-pilot` 复制到 Codex 自定义宠物目录：

```text
${CODEX_HOME:-$HOME/.codex}/pets/aka-pilot/
```

然后重启 Codex，在 Settings -> Appearance -> Pets -> Custom pets 中选择 `Aka Pilot`。

## QA 状态

v2 已通过：

- `validation.json`: no errors / no warnings
- `review.json`: no errors / no warnings
- 9 个状态预览视频已生成
- contact sheet 已目视检查

## 说明

本项目中的参考图只用于提炼文字特征和视觉方向；最终 spritesheet 由 Codex pet 生成流程生成，并经过透明化、抽帧、合图和 QA。

本项目仅出于个人兴趣爱好和本地自用目的保存，不用于商业用途，也不主张任何官方关联、授权或法律影响。
