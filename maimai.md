# 🎰 舞萌 DX 专项 (Maimai)

> 查分、查歌与排队服务。

<br>

<!-- 核心板块 (Query) -->
<div style="display: flex; flex-wrap: wrap; gap: 15px;">

  <div style="flex: 1; min-width: 300px; background: #fffbe6; border-left: 5px solid #faad14; padding: 20px; border-radius: 12px;">
    <h3 style="margin-top: 0; color: #faad14;">📊 核心查询</h3>
    <table style="width: 100%; font-size: 13px;">
      <tr><td width="35%"><code>今日舞萌</code></td><td>运势与推荐</td></tr>
      <tr><td><code>b50</code></td><td>查B50成绩</td></tr>
      <tr><td><code>随个 [难度]</code></td><td>随机歌 (例: <code>随个紫</code>)</td></tr>
      <tr><td><code>查歌 [关键词]</code></td><td>查曲目信息</td></tr>
      <tr><td><code>定数查歌 [范围]</code></td><td>例: <code>定数查歌 13.5 13.9</code></td></tr>
    </table>
  </div>

  <div style="flex: 1; min-width: 300px; background: #f6ffed; border-left: 5px solid #52c41a; padding: 20px; border-radius: 12px;">
    <h3 style="margin-top: 0; color: #52c41a;">🏅 牌子与进度</h3>
    <table style="width: 100%; font-size: 13px;">
      <tr><td width="35%"><code>[牌子]进度</code></td><td>例: <code>霸者进度</code></td></tr>
      <tr><td><code>[等级]进度</code></td><td>例: <code>13+进度</code></td></tr>
      <tr><td><code>完成表 [等级]</code></td><td>生成完成度表格</td></tr>
      <tr><td><code>分数线 [曲ID]</code></td><td>查分数线详情</td></tr>
    </table>
  </div>

</div>

<br>

<!-- 状态与服务器 (新增板块) -->
<div style="background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 10px rgba(0,0,0,0.05);">
  <h3 style="margin-top: 0; color: #1890ff;">📡 舞萌服务器状态 (Milk/Chongxi)</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: center;">
    <div style="flex: 1; min-width: 200px;">
      <p style="font-size: 13px; color: #555; line-height: 1.6;">
        同时获取 Milk 与 Chongxi 代理服务器的实时状态页。<br>
        <strong>指令：</strong> <code>看看mai</code> 或 <code>舞萌状态</code> 或 <code>mai状态</code>
      </p>
    </div>
    <div style="flex: 1; min-width: 200px; text-align: center;">
      <!-- 请确保 Picture 文件夹有 maimai_status.jpg -->
      <img src="Picture/maimai_status.jpg" style="max-height: 100px; border-radius: 8px; border: 2px solid #1890ff;">
    </div>
  </div>
</div>

<br>

<!-- 娱乐/别名 -->
<div style="display: flex; flex-wrap: wrap; gap: 15px;">
  <div style="flex: 1; min-width: 300px; background: #fff7e6; border: 2px solid #ffc069; padding: 20px; border-radius: 12px;">
    <h3 style="margin-top: 0; color: #fa8c16;">🗣️ 骚话模式</h3>
    <ul style="columns: 2; color: #555; font-size: 13px;">
      <li>“xxmai什么” (例: <code>柚子mai什么</code>)</li>
      <li>“我要在 [难度] 上 [分数] 分”</li>
      <li>“今天mai出勤打什么上分”</li>
      <li>“[等级] [评价] 进度”</li>
    </ul>
  </div>
  
  <div style="flex: 1; min-width: 300px; background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 12px;">
    <h3 style="margin-top: 0; color: #1890ff;">🏷️ 别名与娱乐</h3>
    <table style="width: 100%; font-size: 13px;">
      <tr><td width="35%"><code>是什么歌</code></td><td>查别名对应曲</td></tr>
      <tr><td><code>添加别名 [ID] [名]</code></td><td>添加新别名</td></tr>
      <tr><td><code>mai猜歌</code></td><td>开启猜歌游戏</td></tr>
    </table>
  </div>
</div>