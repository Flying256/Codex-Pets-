# Codex-Pets-正儿八经的陈老师
小小萌萌的真正儿八经的陈老师，比平常正儿八经多了嘿嘿嘿

## 使用

这个仓库包含一个 Codex 自定义宠物包：

```text
pets/cb/
├── pet.json
└── spritesheet.webp
```

安装时，把 `pets/cb` 文件夹复制到本机的 Codex 自定义宠物目录：

```text
~/.codex/pets/cb
```

## 文件说明

- `pets/cb/`：Codex 可加载的宠物包。
- `source-sprites/`：制作宠物用的原始精灵图素材。
- `previews/`：contact sheet 和 GIF 动作预览。

当前动作映射：

- 待机 `idle`：蹲起动作。
- 向右拖动 `running-right`：`cb侧面2 走路`。
- 向左拖动 `running-left`：`cb侧面1 走路`。
- 鼠标放上去/attention：正面走路动作，映射到 `waving` 行。

## 授权协议

本仓库的宠物精灵图素材采用 **CC BY-NC-ND 4.0** 授权。

你可以在署名、非商业、且不修改的前提下原样分享这些素材。

不允许商业使用。不允许二创、改色、改图、重绘、生成变体、改编后再发布，或把这些素材用于商品、广告、付费产品等商业项目。

完整说明见 [LICENSE.md](LICENSE.md)。
