# 🛠️ 通用工具与娱乐 (Tools)

> 包含 Meme 随机图、AI 语音、群管以及各类实用插件。

<br>

<!-- =================================================
     1. Meme 随机图 V15.0 (根据图片新增的重点板块)
     ================================================= -->
<div style="background: #f9f0ff; border: 2px solid #b37feb; padding: 20px; border-radius: 15px; margin-bottom: 25px; box-shadow: 0 4px 15px rgba(179, 127, 235, 0.1);">
  <h3 style="margin-top: 0; color: #722ed1;">🖼️ Meme 随机图 (V15.0)</h3>
  <p style="font-size: 13px; color: #666;">一款集成审核、溯源、隐私控制的本地表情包管理系统。</p>

  <div style="display: flex; flex-wrap: wrap; gap: 20px; margin-top: 15px;">
    
    <!-- 基础功能 -->
    <div style="flex: 1; min-width: 240px;">
      <h4 style="color: #722ed1; margin-bottom: 10px;">✨ 基础功能 (全员)</h4>
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px;">
        <li><code>[关键词]</code>：随机发送一张该分类的图 (防重复)</li>
        <li><code>[关键词] 查看</code>：生成该分类的九宫格预览图</li>
        <li><code>[关键词] 上传 [图片]</code>：申请投稿 (需管理员审核)</li>
        <li><code>表情列表</code>：查看所有可用的关键词分类</li>
      </ul>
    </div>

    <!-- 快捷操作 -->
    <div style="flex: 1; min-width: 240px;">
      <h4 style="color: #722ed1; margin-bottom: 10px;">⚡ 快捷操作 (长按图片)</h4>
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px;">
        <li><strong>引用回复 "溯源"</strong>：查询该图片的上传者信息</li>
        <li><strong>引用回复 "删除"</strong>：(管理员) 直接删除该图</li>
        <li><strong>引用回复 "同意/拒绝"</strong>：(审核群) 处理投稿申请</li>
      </ul>
    </div>

  </div>

  <!-- 管理指令 (折叠) -->
  <details style="margin-top: 15px;">
    <summary style="cursor: pointer; color: #b37feb; font-size: 12px; font-weight: bold;">🔐 管理员指令 (点击展开)</summary>
    <div style="background: #fff; padding: 15px; border-radius: 8px; margin-top: 10px; font-size: 12px; border: 1px dashed #d3adf7;">
      <p><code>锁定/解锁 [关键词]</code> - 设置分类隐藏/公开</p>
      <p><code>[关键词] 强制上传</code> - 忽略重复检测强制提交</p>
      <p><code>删除 [文件名]</code> - 按文件名精确删除</p>
    </div>
  </details>
</div>

<!-- =================================================
     2. 娱乐与互动 (新增 AI 语音与签到)
     ================================================= -->
<div style="display: flex; flex-wrap: wrap; gap: 15px; margin-bottom: 20px;">

  <!-- AI 语音 -->
  <div style="flex: 1; min-width: 280px; background: #fff7e6; border-left: 5px solid #fa8c16; padding: 20px; border-radius: 10px;">
    <h3 style="margin-top: 0; color: #fa8c16;">🎙️ AI 语音与互动</h3>
    <table style="width: 100%;">
      <tr>
        <td><code>say [文本]</code></td>
        <td>让 Bot 用 AI 语音说出指定的话</td>
      </tr>
      <tr>
        <td><code>切换语音</code></td>
        <td>切换不同的 AI 音色 (开发中)</td>
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

  <!-- 游戏状态 -->
  <div style="flex: 1; min-width: 280px; background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 10px;">
    <h3 style="margin-top: 0; color: #1890ff;">🎮 游戏互通</h3>
    <table style="width: 100%;">
      <tr>
        <td><code>mc status</code></td>
        <td>查看 MC 服务器在线人数/状态</td>
      </tr>
      <tr>
        <td><code>steam user [ID]</code></td>
        <td>查询 Steam 玩家资料卡</td>
      </tr>
      <tr>
        <td><code>apex map</code></td>
        <td>查询 Apex 当前地图轮换</td>
      </tr>
    </table>
  </div>

</div>

<!-- =================================================
     3. 群管工具 (红色)
     ================================================= -->
<div style="background: #fff0f6; border-left: 5px solid #ff4d4f; padding: 20px; border-radius: 10px;">
  <h3 style="margin-top: 0; color: #ff4d4f;">🛡️ 群务管理</h3>
  <table style="width: 100%;">
    <tr>
      <th width="30%">功能</th>
      <th>指令示例</th>
    </tr>
    <tr>
      <td><b>禁言/踢出</b></td>
      <td><code>禁言 @用户 10分</code> / <code>踢 @用户</code></td>
    </tr>
    <tr>
      <td><b>全员禁言</b></td>
      <td><code>全员禁言</code> / <code>解除全员禁言</code></td>
    </tr>
    <tr>
      <td><b>今日词云</b></td>
      <td><code>今日词云</code> (查看群内热门话题)</td>
    </tr>
  </table>
</div>