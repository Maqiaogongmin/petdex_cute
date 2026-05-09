# Codex Pet Collection

这是一个 Codex 桌面宠物合集。当前仓库保存最终可安装的桌宠包。

## 当前桌宠

### Aka Pilot

一个 chibi / pixel-adjacent 风格的红色驾驶员桌宠。

宠物包位于：

```text
pets/aka-pilot/
├── pet.json
└── spritesheet.webp
```

### Homelander

一个以“阿祖”为方向制作的桌宠：金发、深蓝制服、红白披风、金色肩甲和腰带，整体气质更冷峻、有压迫感，同时保留桌宠的小型像素风比例。

宠物包位于：

```text
pets/homelander/
├── pet.json
└── spritesheet.webp
```

## 项目结构

```text
pets/aka-pilot/
├── pet.json
└── spritesheet.webp

pets/homelander/
├── pet.json
└── spritesheet.webp
```

## Petdex 上传

上传到 Petdex 时，请上传对应的 `pets/<pet-name>` 文件夹，或上传一个根目录直接包含 `pet.json` 和 `spritesheet.webp` 的 zip 包。

## 安装
请访问：https://petdex.crafter.run/pets/aka-pilot

把对应桌宠文件夹复制到 Codex 自定义宠物目录：

```text
${CODEX_HOME:-$HOME/.codex}/pets/<pet-name>/
```

然后重启 Codex，在 Settings -> Appearance -> Pets -> Custom pets 中选择对应桌宠。

## 说明

本仓库主要保留最终可安装的宠物包，不保留完整生成过程、参考图、抽帧记录或 QA 临时产物。

本项目仅出于个人兴趣爱好和本地自用目的保存，不用于商业用途，也不主张任何官方关联、授权或法律影响。
