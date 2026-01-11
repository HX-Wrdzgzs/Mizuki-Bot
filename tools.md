# 🛠️ 通用工具与娱乐 (Tools)

> 包含表情包系统、Minecraft、Steam 及 AI 语音。

<br>

<!-- =================================================
     1. 表情包系统 (根据你的手册重写)
     ================================================= -->
<div style="background: #f9f0ff; border: 2px solid #b37feb; padding: 20px; border-radius: 15px; margin-bottom: 25px; box-shadow: 0 4px 15px rgba(179, 127, 235, 0.1);">
  <h3 style="margin-top: 0; color: #722ed1;">🖼️ 表情包系统 (Meme System)</h3>
  <p style="font-size: 13px; color: #666;">集成审核、溯源、压缩包批量上传的表情管理系统。</p>

  <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-top: 15px;">
    
    <!-- 基础指令 -->
    <div style="flex: 1; min-width: 240px;">
      <h4 style="color: #531dab; margin-bottom: 10px; border-bottom: 1px dashed #d3adf7;">✨ 基础指令</h4>
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px; margin: 0;">
        <li><code>表情帮助</code> / <code>表情列表</code></li>
        <li><code>发送 [文件夹名]</code> (例: <code>发送 mzk</code>)</li>
        <li><code>查看 [图片名]</code> (例: <code>查看 mzk1</code>)</li>
        <li><code>看所有 [文件夹名]</code> (生成预览图)</li>
      </ul>
    </div>

    <!-- 上传系统 -->
    <div style="flex: 1; min-width: 240px;">
      <h4 style="color: #531dab; margin-bottom: 10px; border-bottom: 1px dashed #d3adf7;">📤 上传系统</h4>
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px; margin: 0;">
        <li><code>[文件夹] 上传 [图片]</code> (申请投稿)</li>
        <li><code>[文件夹] 上传</code> (引用ZIP压缩包)</li>
        <li><code>[文件夹] pic上传 [图]</code> (仅管理员)</li>
      </ul>
    </div>

  </div>

  <!-- 管理员指令 (折叠) -->
  <details style="margin-top: 15px;">
    <summary style="cursor: pointer; color: #b37feb; font-size: 13px; font-weight: bold;">🔐 管理员指令 (点击展开)</summary>
    <div style="background: #fff; padding: 15px; border-radius: 8px; margin-top: 10px; font-size: 13px; border: 1px dashed #d3adf7; color: #555;">
      <p><code>最近上传</code> - 查看最近10条入库记录</p>
      <p><code>删除 [图片名]</code> - 删图+删库</p>
      <p><code>溯源 [图片名]</code> - 查询上传者信息</p>
      <p><code>锁定/解锁 [文件夹]</code> - 控制分类权限</p>
      <p><code>屏蔽群/解除屏蔽 [群号]</code> - 黑名单管理</p>
    </div>
  </details>

  <!-- PJSK 表情制作入口 -->
  <div style="margin-top: 15px; border-top: 1px dashed #d3adf7; padding-top: 10px;">
    <span style="font-size: 13px; color: #eb2f96; font-weight: bold;">🎨 PJSK 表情制作?</span>
    <span style="font-size: 13px; color: #666;">指令: <code>pjsk [ID] [文本]</code></span>
    <a href="#/meme" style="margin-left: 10px; font-size: 12px; color: #722ed1; text-decoration: underline;">查看制作教程 -></a>
  </div>
</div>

<!-- =================================================
     2. 群数据统计
     ================================================= -->
<div style="background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 10px; margin-bottom: 25px;">
  <h3 style="margin-top: 0; color: #1890ff;">📊 看看群U发言</h3>
  <p style="font-size: 13px; color: #555;">
    <code>今日发言</code> (看谁话最多) / <code>本月发言</code> / <code>今年发言</code><br>
    (管理) <code>全群统计</code> / <code>今日DAU</code>
  </p>
</div>

<!-- =================================================
     3. 游戏工具 (Minecraft & Steam)
     ================================================= -->
<div style="display: flex; flex-wrap: wrap; gap: 20px; margin-bottom: 25px;">

  <!-- Minecraft -->
  <div style="flex: 1; min-width: 300px; background: #f6ffed; border-left: 5px solid #52c41a; padding: 20px; border-radius: 10px;">
    <h3 style="margin-top: 0; color: #52c41a;">🌲 Minecraft 服务器</h3>
    <p style="font-size: 13px; color: #333; font-weight: bold;">版本：<span style="background:#e6f7ff; color:#1890ff; padding: 2px 6px; border-radius: 4px;">Fabric 1.21.4</span></p>
    <p style="font-size: 13px; color: #666;">IP地址与整合包请在群内获取。</p>
    <a href="https://qun.qq.com/universal-share/share?ac=1&authKey=OALb4lQ%2Fsp1xe87bvdbdRFs42JprELk5CZRzD4dz411gNvq3hCwb8p78EY9i9ds3&busi_data=eyJncm91cENvZGUiOiIxMDUzOTY0NDMxIiwidG9rZW4iOiJaQ2tVU0xyVmN5QzZ4TXVJV2lsU2lZT2NsK25ydG93SXQrdDBqNkh4TTZ3R3MzT3RoQWcwRUZVdWRFTFcxQnRlIiwidWluIjoiMjMzODY4MDE0OCJ9&data=e370_oIm3BFzkvBqcfheysbbZLuDTnIGtGMAdmDkMz2BDaXussDGZmKy7rw0DGLyounmO8jJMjiyTsXJJqhQLQ&svctype=4&tempid=h5_group_info" target="_blank" style="display: inline-block; background: #52c41a; color: white; padding: 6px 12px; border-radius: 15px; text-decoration: none; font-size: 12px; margin-top: 5px;">
      👉 点击加入 MC 服务器群
    </a>
    <p style="font-size: 13px; margin-top: 10px;"><code>mc status</code> (查在线状态)</p>
  </div>

  <!-- Steam -->
  <div style="flex: 1; min-width: 300px; background: #1b2838; color: #c7d5e0; padding: 20px; border-radius: 15px;">
    <h3 style="margin-top: 0; color: #66c0f4;">🚂 Steam 状态</h3>
    <div style="font-size: 13px; line-height: 1.8;">
      <code>steam绑定 [ID]</code> / <code>steam播报开启</code><br>
      <code>steam喜加一</code> (查免费游戏)
    </div>
  </div>

</div>

<!-- =================================================
     4. AI 语音与互动
     ================================================= -->
<div style="background: #fff7e6; border-left: 5px solid #fa8c16; padding: 20px; border-radius: 10px;">
  <h3 style="margin-top: 0; color: #fa8c16;">🎙️ AI 语音与互动</h3>
  <p style="font-size: 13px; color: #555;">
    <code>say [文本]</code> (AI说话) / <code>切换语音</code><br>
    <code>签到</code> (每日领积分) / <code>运势</code>
  </p>
</div>