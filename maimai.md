# 🎰 舞萌 DX 专项 (Maimai)

> 基于 `maimaiDX` 插件，提供最全面的查分、查歌与排队服务。

<br>

<div style="display: flex; flex-wrap: wrap; gap: 15px;">

  <!-- 1. 核心查分与查询 (黄色) -->
  <div style="flex: 1; min-width: 300px; background: #fffbe6; border-left: 5px solid #faad14; padding: 20px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #faad14;">📊 核心查询</h3>
    <table style="width: 100%; font-size: 13px;">
      <tr>
        <td width="35%"><code>今日舞萌</code></td>
        <td>查看今天的运势与推荐歌曲</td>
      </tr>
      <tr>
        <td><code>b50</code></td>
        <td>查询 Best 50 成绩 (可加 @ 查询别人)</td>
      </tr>
      <tr>
        <td><code>随个 [难度]</code></td>
        <td>随机推荐一首歌 (例: <code>随个紫</code>)</td>
      </tr>
      <tr>
        <td><code>查歌 [关键词]</code></td>
        <td>查询曲目信息</td>
      </tr>
      <tr>
        <td><code>定数查歌 [范围]</code></td>
        <td>查询指定定数范围的歌 (例: <code>定数查歌 13.5 13.9</code>)</td>
      </tr>
      <tr>
        <td><code>分数列表 [等级]</code></td>
        <td>查看指定等级的所有分数列表</td>
      </tr>
      <tr>
        <td><code>查看排行</code></td>
        <td>查看群内或服务器 Rating 排行</td>
      </tr>
    </table>
  </div>

  <!-- 2. 进度与牌子 (绿色) -->
  <div style="flex: 1; min-width: 300px; background: #f6ffed; border-left: 5px solid #52c41a; padding: 20px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #52c41a;">🏅 牌子与进度</h3>
    <table style="width: 100%; font-size: 13px;">
      <tr>
        <td width="35%"><code>[牌子]进度</code></td>
        <td>查询牌子完成度 (例: <code>霸者进度</code>)</td>
      </tr>
      <tr>
        <td><code>[等级]进度</code></td>
        <td>查询等级完成表 (例: <code>13+进度</code>)</td>
      </tr>
      <tr>
        <td><code>完成表 [等级]</code></td>
        <td>生成详细的完成度表格</td>
      </tr>
      <tr>
        <td><code>分数线 [曲ID]</code></td>
        <td>查询指定歌曲的分数线详情</td>
      </tr>
    </table>
  </div>

  <!-- 3. 别名与猜歌 (蓝色) -->
  <div style="flex: 1; min-width: 300px; background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
    <h3 style="margin-top: 0; color: #1890ff;">🏷️ 别名与娱乐</h3>
    <table style="width: 100%; font-size: 13px;">
      <tr>
        <td width="35%"><code>是什么歌</code></td>
        <td>查询别名对应的歌曲</td>
      </tr>
      <tr>
        <td><code>添加别名 [ID] [名]</code></td>
        <td>给歌曲添加新别名 (需审核/投票)</td>
      </tr>
      <tr>
        <td><code>当前别名投票</code></td>
        <td>查看正在进行的别名投票</td>
      </tr>
      <tr>
        <td><code>mai猜歌</code></td>
        <td>开启猜歌小游戏 (<code>重置猜歌</code> 重开)</td>
      </tr>
    </table>
  </div>

</div>

<br>

<!-- 4. 自然语言快捷指令 (橙色) -->
<div style="background: #fff7e6; border: 2px solid #ffc069; padding: 20px; border-radius: 12px; margin-top: 10px;">
  <h3 style="margin-top: 0; color: #fa8c16;">🗣️ 骚话模式 (非常规指令)</h3>
  <p style="color: #666; font-size: 13px;">你可以直接像聊天一样发送以下内容，Bot 也能听懂哦！</p>
  
  <ul style="columns: 2; -webkit-columns: 2; -moz-columns: 2; color: #555; font-size: 13px;">
    <li>“xxmai什么” (例: <code>柚子mai什么</code>)</li>
    <li>“我要在 [难度] 上 [分数] 分”</li>
    <li>“今天mai出勤打什么上分”</li>
    <li>“[等级] [评价] 进度” (例: <code>13+ SSS 进度</code>)</li>
    <li>“[等级] 分数列表”</li>
  </ul>
</div>

<br>

<!-- 参数说明 -->
<details>
<summary style="cursor: pointer; color: #999; font-size: 12px;">📝 点击查看参数说明 (Parameters)</summary>
<div style="background: #fafafa; padding: 15px; border-radius: 8px; margin-top: 10px; font-size: 12px; color: #666;">
  <p><strong>&lt;必填参数&gt; [选填参数]</strong></p>
  <ul>
    <li><code>ver</code>: 版本 (dx/标准)</li>
    <li><code>diff</code>: 难度 (绿/黄/红/紫/白)</li>
    <li><code>level</code>: 等级 (1-15)</li>
    <li><code>id</code>: 歌曲 ID</li>
  </ul>
  <p style="text-align: right;">* 带有 # 的指令仅限 Bot 管理员私聊使用</p>
</div>
</details>

<div style="text-align: center; color: #ccc; font-size: 12px; margin-top: 20px;">
  Powered by project maimaiDX
</div>