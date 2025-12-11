# 🎨 PJSK 表情制作 (Meme Stickers)

> 一键生成 Project Sekai (PJSK) 风格的对话贴纸。

<br>

<!-- 快捷指令区域 -->
<div style="background: #fff0f6; border-left: 5px solid #E97EB3; padding: 20px; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
  <h3 style="margin-top: 0; color: #E97EB3;">⚡ 极速生成 (推荐)</h3>
  <p style="color: #666; font-size: 14px;">直接使用缩写指令，无需输入复杂的前缀。</p>
  
  <div style="background: #fff; padding: 15px; border-radius: 8px; border: 1px solid #ffcce0; margin-top: 10px;">
    <code style="color: #E97EB3; font-weight: bold; font-size: 1.1em;">pjsk [角色名] [文本]</code>
  </div>
  
  <p style="font-size: 13px; color: #888; margin-top: 10px;">
    <strong>举个栗子：</strong><br>
    <code>pjsk Mizuki 还是不知道</code><br>
    <code>pjsk Ena 笨蛋弟弟</code>
  </p>
</div>

<br>

## 📊 角色名称速查表

不知道角色名字用什么？请参考下图（支持图中的英文名或对应的中文名）：

<!-- 这里引用你上传的图片 -->
<div style="text-align: center; margin: 20px 0;">
  <img src="Picture/pjsk_all.jpg" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0,0,0,0.1); border: 3px solid #E97EB3; max-width: 100%;">
  <p style="font-size: 12px; color: #999;">▲ PJSK 常用角色列表 (点击图片可放大)</p>
</div>

<details>
<summary style="cursor: pointer; background: #f5f5f5; padding: 10px; border-radius: 8px; font-weight: bold; color: #666;">📝 点击展开可复制的文字列表</summary>
<div style="padding: 10px; line-height: 1.8; color: #555;">

| 组合 | 角色名 (建议使用图示英文) |
| :--- | :--- |
| **VS** | Miku, Rin, Len, Luka, MEIKO, KAITO |
| **L/N** | Ichika, Saki, Honami, Shiho |
| **MMJ** | Minori, Haruka, Airi, Shizuku |
| **VBS** | Kohane, An, Akito, Touya |
| **Wxs** | Tsukasa, Emu, Nene, Rui |
| **25h** | Kanade, Mafuyu, Ena, Mizuki |

</div>
</details>

<br>

## 🔍 查询指令与帮助

如果你想查看 Bot 内部更详细的列表或分类，可以使用原生指令：

| 指令 | 说明 |
| :--- | :--- |
| `meme-stickers ll` | **查看本地列表** (List Local)<br>显示所有可用的贴纸包分类 |
| `meme-stickers generate pjsk` | **生成引导**<br>查看 PJSK 包的详细制作参数和说明 |

<br>

## ⚙️ 进阶微调参数

在指令后面加上这些参数，可以让你的表情包更个性化。

> **示例**：`pjsk Mizuki 快跑 -x 20 -c red`

| 参数 | 说明 | 示例 |
| :--- | :--- | :--- |
| **-x** | 左右移动文字 | `-x 30` (右移) |
| **-y** | 上下移动文字 | `-y -20` (上移) |
| **-r** | 文字旋转角度 | `-r 15` (旋转) |
| **-c** | 文字颜色 | `-c red` 或 `-c #E97EB3` |
| **-s** | 字体大小 | `-s 80` |

<br>

<div style="text-align: center; color: #ccc; font-size: 12px; margin-top: 30px;">
  Powered by meme-stickers
</div>