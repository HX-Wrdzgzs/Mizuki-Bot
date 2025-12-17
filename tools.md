# 🛠️ 通用工具与娱乐 (Tools)

> 包含表情包管理、群发言统计、游戏工具及 AI 语音。

<br>

<!-- =================================================
     1. 图片与表情系统 (Meme Random V21 + Stickers)
     ================================================= -->
<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 25px;">

<!-- 1.1 Meme 随机 V21.0 (紫色面板) -->
<div style="flex: 1; min-width: 300px; background: #f9f0ff; border: 2px solid #b37feb; padding: 20px; border-radius: 15px; box-shadow: 0 4px 15px rgba(179, 127, 235, 0.1);">
<h3 style="margin-top: 0; color: #722ed1; display:flex; align-items:center; justify-content:space-between;">
<span>🖼️ Meme 随机</span>
<span style="font-size:12px; background:#722ed1; color:#fff; padding:2px 8px; border-radius:10px;">V21.0</span>
</h3>
<p style="font-size: 13px; color: #666;">全能表情管理：对接 Superuser、溯源报表、压缩包审核。</p>

<div style="margin-top: 15px;">
<h4 style="color: #531dab; margin-bottom: 8px; border-bottom: 1px dashed #d3adf7;">✨ 基础功能 (全员)</h4>
<ul style="font-size: 13px; line-height: 1.6; color: #555; padding-left: 20px; margin: 0;">
<li><code>[关键词]</code>：随机发送 (智能防重复)</li>
<li><code>看所有[关键词]</code>：生成九宫格预览图</li>
<li><code>查看 [文件名]</code>：精准查看单张图片</li>
<li><code>[关键词] 上传 [图]</code>：申请投稿 (需审核)</li>
</ul>
</div>

<div style="margin-top: 15px;">
<h4 style="color: #531dab; margin-bottom: 8px; border-bottom: 1px dashed #d3adf7;">⚡ 快捷操作 (引用回复)</h4>
<ul style="font-size: 13px; line-height: 1.6; color: #555; padding-left: 20px; margin: 0;">
<li>回复 <code>溯源</code>：查询该图上传者信息</li>
<li>回复 <code>删除</code>：(管理员) 删掉这张图</li>
<li>回复 <code>同意</code> / <code>拒绝</code>：(审核群) 处理投稿</li>
</ul>
</div>

<details style="margin-top: 10px;">
<summary style="cursor: pointer; color: #b37feb; font-size: 12px; font-weight: bold;">🔐 管理员指令 (Superuser)</summary>
<div style="background: #fff; padding: 10px; border-radius: 8px; margin-top: 5px; font-size: 12px; border: 1px dashed #d3adf7;">
<p><code>最近上传</code>：生成最近10条上传报表</p>
<p><code>[关键词] 压缩包上传</code>：引用ZIP解压审核</p>
<p><code>锁定/解锁 [关键词]</code>：隐藏或公开分类</p>
<p><code>[关键词] 强制上传</code>：忽略重复强制提交</p>
</div>
</details>
</div>

<!-- 1.2 Meme-stickers PJSK表情 (粉色入口) -->
<div style="flex: 1; min-width: 300px; background: #fff0f6; border: 2px solid #ffadd2; padding: 20px; border-radius: 15px; box-shadow: 0 4px 15px rgba(255, 173, 210, 0.1);">
<h3 style="margin-top: 0; color: #eb2f96;">🎨 PJSK 表情制作</h3>
<p style="font-size: 13px; color: #666;">一键生成 PJSK / Arcaea 风格对话贴纸。</p>
<p style="font-size: 13px; color: #555; margin-top: 15px;">
<strong>常用指令：</strong><br>
<code>pjsk [角色] [文本]</code><br>
<code>arc [角色] [文本]</code>
</p>
<div style="background: #fff; padding: 10px; border-radius: 8px; margin-top: 10px; border: 1px dashed #ffadd2;">
<code style="color: #eb2f96;">pjsk 瑞希 还是不知道</code>
</div>
<br>
<a href="#/meme" style="display: block; text-align: center; background: #eb2f96; color: white; padding: 8px; border-radius: 20px; text-decoration: none; font-weight: bold; font-size: 13px;">
👉 点击查看完整教程与角色列表
</a>
</div>

</div>

<!-- =================================================
     2. 群数据统计 (看看群U发言) - 新增
     ================================================= -->
<div style="background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 10px; margin-bottom: 25px; box-shadow: 0 4px 10px rgba(24, 144, 255, 0.1);">
<h3 style="margin-top: 0; color: #1890ff;">📊 看看群U发言 (统计)</h3>
<p style="font-size: 13px; color: #666;">统计群友发言次数，看看谁是龙王 (纯文字版)。</p>

<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-top: 10px;">
<div style="flex: 1; min-width: 240px;">
<h4 style="color: #096dd9; margin-bottom: 8px;">👤 普通用户指令</h4>
<ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px; margin: 0;">
<li><code>今日发言</code> (别名: 今日排行榜)<br><span style="color:#999; font-size:12px;">查看本群今天谁话最多 (Top 10)</span></li>
<li><code>本月发言</code> (别名: 本月排行榜)<br><span style="color:#999; font-size:12px;">查看本月累计发言排行</span></li>
<li><code>今年发言</code> (别名: 今年排行榜)<br><span style="color:#999; font-size:12px;">查看今年累计发言排行</span></li>
</ul>
</div>
<div style="flex: 1; min-width: 240px;">
<h4 style="color: #096dd9; margin-bottom: 8px;">👑 管理员指令</h4>
<ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px; margin: 0;">
<li><code>全群统计</code><br><span style="color:#999; font-size:12px;">扫描Bot加入的所有群，按活跃度列出排名。</span></li>
<li><code>今日DAU</code> (别名: bot数据)<br><span style="color:#999; font-size:12px;">监控Bot今日共接收/处理了多少条消息。</span></li>
</ul>
</div>
</div>
</div>

<!-- =================================================
     3. 游戏工具 (Minecraft & Steam)
     ================================================= -->
<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 25px;">

<!-- Minecraft -->
<div style="flex: 1; min-width: 300px; background: #f6ffed; border-left: 5px solid #52c41a; padding: 20px; border-radius: 10px; box-shadow: 0 4px 10px rgba(82, 196, 26, 0.1);">
<h3 style="margin-top: 0; color: #52c41a;">🌲 Minecraft 服务器</h3>
<p style="margin: 5px 0; color: #333; font-weight: bold; font-size: 13px;">
版本：<span style="background:#e6f7ff; color:#1890ff; padding: 2px 6px; border-radius: 4px;">Fabric 1.21.4</span>
</p>
<div style="background: #fff; border: 1px dashed #52c41a; padding: 10px; border-radius: 6px; font-family: monospace; color: #555; font-size: 13px; margin: 10px 0;">
frp-oak.com:13902
</div>
<p style="font-size: 13px; color: #666;">
<strong>指令：</strong><code>mc status</code> (查看在线状态)
</p>
</div>

<!-- Steam -->
<div style="flex: 1; min-width: 300px; background: #1b2838; color: #c7d5e0; padding: 20px; border-radius: 15px; box-shadow: 0 4px 10px rgba(0,0,0,0.3);">
<h3 style="margin-top: 0; color: #66c0f4; font-size: 1.2em;">🚂 Steam 状态</h3>
<div style="font-size: 13px; line-height: 1.8;">
<p style="margin: 5px 0;"><code>steam绑定 [ID]</code> / <code>steam解绑</code></p>
<p style="margin: 5px 0;"><code>steam播报开启</code> / <code>关闭</code></p>
<p style="margin: 5px 0;"><code>steam喜加一</code> (查询免费游戏)</p>
</div>
</div>

</div>

<!-- =================================================
     4. AI 语音与互动
     ================================================= -->
<div style="background: #fff7e6; border-left: 5px solid #fa8c16; padding: 20px; border-radius: 10px;">
<h3 style="margin-top: 0; color: #fa8c16;">🎙️ AI 语音与日常</h3>
<table style="width: 100%;">
<tr>
<td width="30%"><code>say [文本]</code></td>
<td>让 Bot 用 AI 语音说出指定的话</td>
</tr>
<tr>
<td><code>签到</code></td>
<td>每日签到，获取积分/好感度</td>
</tr>
<tr>
<td><code>抽签</code> / <code>运势</code></td>
<td>查看今日运势与吉凶</td>
</tr>
</table>
</div>