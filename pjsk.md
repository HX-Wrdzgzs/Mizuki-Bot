# 🎵 PJSK 相关功能

> 包含查分、查榜、组卡计算器及娱乐功能。

<br>

<!-- 玩家数据 (蓝) -->
<div style="background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 10px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #1890ff;">📊 玩家数据查询</h3>
  <p style="font-size: 13px; color: #666; margin-bottom: 10px;"><code>绑定 [ID]</code> (ID在游戏个人信息查看)</p>
  <table style="width: 100%; font-size: 13px;">
    <tr><td width="30%"><code>pjsk b30</code></td><td>生成 Best 30 成绩图</td></tr>
    <tr><td><code>pjsk进度</code></td><td>查询完成情况 (FC/AP)</td></tr>
    <tr><td><code>视奸</code>/<code>逮捕</code></td><td>查队伍综合力 / 查高难谱面</td></tr>
    <tr><td><code>rk</code>/<code>b39</code></td><td>[需上传] 查排位 / 39首最高分</td></tr>
  </table>
</div>

<!-- 歌曲 (粉) -->
<div style="background: #fff0f6; border-left: 5px solid #E97EB3; padding: 20px; border-radius: 10px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #E97EB3;">🎵 查歌与谱面</h3>
  <div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <div style="flex: 1; min-width: 200px;">
      <ul style="font-size: 13px; color: #555; padding-left: 20px; margin: 0;">
        <li><code>sk [曲名]</code>：查歌曲详情</li>
        <li><code>pinfo [曲名]</code>：查详细信息</li>
        <li><code>查bpm [条件]</code>：查指定BPM</li>
      </ul>
    </div>
    <div style="flex: 1; min-width: 200px;">
      <ul style="font-size: 13px; color: #555; padding-left: 20px; margin: 0;">
        <li><code>谱面预览 [曲名]</code>：看Master谱面</li>
        <li><code>分数线</code>：获取当前档线</li>
        <li><code>ss</code>：获取当前时速</li>
      </ul>
    </div>
  </div>
</div>

<!-- 组卡 (橙) -->
<div style="background: #fff7e6; border-left: 5px solid #fa8c16; padding: 20px; border-radius: 10px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #fa8c16;">🧮 组卡计算器</h3>
  <table style="width: 100%; font-size: 13px;">
    <tr><td width="30%"><code>组卡 [队名] [属性]</code></td><td>指定箱活最佳卡组 (例: <code>组卡 ln 橙</code>)</td></tr>
    <tr><td><code>活动组卡 [曲名]</code></td><td>当前活动最佳卡组 (例: <code>活动组卡 独瑞</code>)</td></tr>
    <tr><td><code>挑战组卡 [角色]</code></td><td>每日挑战最佳卡组 (例: <code>挑战组卡 miku</code>)</td></tr>
  </table>
</div>

<!-- 卡面 (紫) -->
<div style="background: #f9f0ff; border-left: 5px solid #722ed1; padding: 20px; border-radius: 10px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #722ed1;">🃏 卡面与活动</h3>
  <details>
    <summary style="cursor: pointer; color: #722ed1; font-weight: bold; font-size: 13px;">🔎 查卡功能 (点击展开)</summary>
    <div style="margin-top: 10px; font-size: 13px; color: #555; background: #fff; padding: 10px; border-radius: 8px;">
      <p><code>findcard [条件]</code> (例: <code>findcard miku 4 限定</code>)</p>
      <p><code>card [编号]</code> - 查看大图</p>
      <p><code>pjskcard</code> - 个人卡牌图鉴</p>
    </div>
  </details>
  <p style="font-size: 13px; margin-top: 10px; color: #555;"><code>pjskevent</code> (查排名记录) / <code>findevent</code> (查活动)</p>
</div>

<!-- 娱乐 (绿) -->
<div style="background: #f6ffed; border-left: 5px solid #52c41a; padding: 20px; border-radius: 10px;">
  <h3 style="margin-top: 0; color: #52c41a;">🎉 娱乐功能</h3>
  <p style="font-size: 13px; color: #555;">
    <code>pjsk听歌识曲</code> / <code>pjsk猜卡面</code> / <code>pjsk抽卡</code><br>
    <code>随个 [组合]</code> / <code>看 [角色]</code> / <code>葱什么</code>
  </p>
</div>