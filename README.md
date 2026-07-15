# Bartholomew Codex Bear

一只可安装到 Codex 的 v2 动画毛绒小熊宠物，包含 9 组工作状态动画与 16 个观察方向。

> [!IMPORTANT]
> 这是非官方、非商业的粉丝项目，与 Jellycat Limited 没有隶属、合作、赞助或认可关系。角色形象灵感来自 Jellycat 的 **Bartholomew Bear**；Jellycat、Bartholomew Bear 及相关角色、商标和设计的权利归其各自权利人所有。

![巴塞罗小熊动作预览](preview/contact-sheet.png)

## 安装

将 `bartholomew-codex-bear` 文件夹复制到 Codex 的自定义宠物目录：

```bash
mkdir -p ~/.codex/pets
cp -R bartholomew-codex-bear ~/.codex/pets/
```

然后重启 Codex，并在宠物选择器中选择“巴塞罗小熊”。

仓库中可安装的目录结构：

```text
bartholomew-codex-bear/
├── pet.json
└── spritesheet.webp
```

## 兼容性

- Codex custom pet
- `spriteVersionNumber: 2`
- 8 × 11 atlas，单格 192 × 208 px
- 完整精灵图尺寸：1536 × 2288 px
- WebP RGBA 透明背景

## 来源与用途

- 形象来源／灵感：[Jellycat 官方 Bartholomew Bear 页面](https://eu.jellycat.com/bartholomew-bear/)
- 项目性质：非官方粉丝创作
- 使用范围：个人、学习、研究和其他非商业用途
- 禁止将本项目或其素材用于销售、广告、商品化或其他商业用途

公开此仓库不表示授予任何 Jellycat 角色、商标或设计的权利。详细说明见 [ATTRIBUTION.md](ATTRIBUTION.md) 和 [LICENSE](LICENSE)。

## 质量检查

当前精灵图已通过 Codex v2 结构校验：尺寸、行列、透明像素、已用／未用单元格和 chroma 残留检查均无错误或警告。`qa/validation.json` 保存了机器校验结果。

## Takedown / Rights holder contact

如果你是相关权利人，并认为此仓库中的内容需要修改或移除，请通过 GitHub Issue 联系仓库维护者；维护者会配合处理。
