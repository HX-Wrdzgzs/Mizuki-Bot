# 🎵 PJSK 相关功能 (Project Sekai)

> 包含查分、查榜、组卡计算器、活动预测及各类娱乐功能。
> <br><small>*大部分指令支持添加 `cn` (国服) 或 `tw` (台服) 前缀来查询对应服务器数据。*</small>

<br>

<!-- =================================================
     1. 玩家数据与绑定 (蓝色)
     ================================================= -->
<div style="background: #e6f7ff; border-left: 5px solid #1890ff; padding: 20px; border-radius: 10px; margin-bottom: 20px; box-shadow: 0 4px 10px rgba(24, 144, 255, 0.1);">
  <h3 style="margin-top: 0; color: #1890ff;">📊 玩家数据查询</h3>
  <p style="font-size: 13px; color: #666; margin-bottom: 15px;">
    部分高级功能（如 rk, b39）需要上传数据后才能使用。
    <br><strong>基础绑定：</strong><code>绑定 [ID]</code> (ID在游戏内个人信息查看)
  </p>

  <table style="width: 100%; font-size: 13px;">
    <tr>
      <td width="30%"><code>pjskprofile</code></td>
      <td>获取个人信息卡片 (类似旧版 Profile)</td>
    </tr>
    <tr>
      <td><code>pjsk b30</code></td>
      <td>生成 Best 30 成绩图 (计算 Rating)</td>
    </tr>
    <tr>
      <td><code>pjsk进度</code></td>
      <td>查询 Master/Expert 完成情况 (FC/AP/Clear)</td>
    </tr>
    <tr>
      <td><code>视奸</code> / <code>逮捕</code></td>
      <td>查看当前队伍综合力 / 查询高难谱面 AP 进度</td>
    </tr>
    <tr>
      <td><code>rk</code> / <code>b39</code></td>
      <td><span style="color:#ff4d4f; font-size:12px;">[需上传数据]</span> 查询排位信息 / 39首最高分统计</td>
    </tr>
  </table>
</div>

<!-- =================================================
     2. 歌曲与谱面信息 (粉色)
     ================================================= -->
<div style="background: #fff0f6; border-left: 5px solid #E97EB3; padding: 20px; border-radius: 10px; margin-bottom: 20px; box-shadow: 0 4px 10px rgba(233, 126, 179, 0.1);">
  <h3 style="margin-top: 0; color: #E97EB3;">🎵 查歌与谱面工具</h3>
  
  <div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <!-- 左侧：基础 -->
    <div style="flex: 1; min-width: 240px;">
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px;">
        <li><code>sk [曲名/ID]</code>：查询歌曲详情与指定档线</li>
        <li><code>pinfo [曲名]</code>：查询详细歌曲信息 (可设置别名)</li>
        <li><code>查bpm [条件]</code>：查询指定 BPM 的歌曲</li>
        <li><code>查物量</code>：查询歌曲物量与难度详情</li>
      </ul>
    </div>
    <!-- 右侧：进阶 -->
    <div style="flex: 1; min-width: 240px;">
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px;">
        <li><code>谱面预览 [曲名]</code>：查看 Master 难度谱面 (可加 ex/apd)</li>
        <li><code>技能预览 [曲名]</code>：查看谱面技能分布及分数占比</li>
        <li><code>分数线</code> / <code>sk线</code>：获取当前档线分数 (5分钟延迟)</li>
        <li><code>ss</code> / <code>wlss</code>：获取当前/单榜档线时速</li>
      </ul>
    </div>
  </div>
</div>

<!-- =================================================
     3. 组卡计算器 (橙色 - 重点功能)
     ================================================= -->
<div style="background: #fff7e6; border-left: 5px solid #fa8c16; padding: 20px; border-radius: 10px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #fa8c16;">🧮 组卡计算器 (最优解)</h3>
  <p style="font-size: 13px; color: #666;">计算最佳队伍配置，支持活动、挑战及普通模式。</p>

  <table style="width: 100%; font-size: 13px;">
    <tr>
      <td width="30%"><code>组卡 [队名] [属性]</code></td>
      <td>
        返回指定箱活中推荐的最佳卡组 Top7<br>
        <span style="color:#999; font-size:12px;">例: <code>组卡 ln 橙</code> (属性: 绿/粉/橙/蓝/紫)</span>
      </td>
    </tr>
    <tr>
      <td><code>活动组卡 [曲名]</code></td>
      <td>
        返回当前活动中推荐的最佳卡组 Top7<br>
        <span style="color:#999; font-size:12px;">例: <code>活动组卡 独瑞 master</code></span>
      </td>
    </tr>
    <tr>
      <td><code>挑战组卡 [角色]</code></td>
      <td>
        每日挑战 Live 最佳卡组推荐<br>
        <span style="color:#999; font-size:12px;">例: <code>挑战组卡 miku 独瑞</code></span>
      </td>
    </tr>
  </table>
</div>

<!-- =================================================
     4. 卡面与活动 (紫色)
     ================================================= -->
<div style="background: #f9f0ff; border-left: 5px solid #722ed1; padding: 20px; border-radius: 10px; margin-bottom: 20px;">
  <h3 style="margin-top: 0; color: #722ed1;">🃏 卡面与活动查询</h3>
  
  <!-- 查卡功能 (折叠详情) -->
  <details>
    <summary style="cursor: pointer; color: #722ed1; font-weight: bold; font-size: 14px;">🔎 强大的查卡功能 (点击展开)</summary>
    <div style="margin-top: 10px; font-size: 13px; line-height: 1.6; color: #555; background: #fff; padding: 10px; border-radius: 8px;">
      <p><strong>指令：</strong><code>findcard [条件1] [条件2] ...</code></p>
      <p><strong>筛选条件支持：</strong></p>
      <ul>
        <li><strong>角色/队伍</strong>：miku, vs, 25时, ln...</li>
        <li><strong>属性</strong>：红, 蓝, 绿, 黄, 紫 (或 橙, 粉...)</li>
        <li><strong>稀有度</strong>：4, 3, 2, 1, birthday, 限定</li>
        <li><strong>示例</strong>：<code>findcard miku 4 限定</code> (查询初音未来的4星限定卡)</li>
      </ul>
      <p><strong>其他指令：</strong><br>
      <code>card [编号]</code> - 查看指定编号卡片大图<br>
      <code>pjskcard</code> - 获取个人卡牌图鉴</p>
    </div>
  </details>

  <div style="margin-top: 15px; font-size: 13px; color: #555;">
    <p><strong>活动相关：</strong></p>
    <ul>
      <li><code>pjskevent</code> - 获取个人前10次最高排名记录</li>
      <li><code>findevent</code> - 查询满足条件的所有活动</li>
      <li><code>sk预测</code> - 获取预测线信息 (仅日服)</li>
      <li><code>查房</code> - 获取当前/目标档线最近1小时活动情况</li>
    </ul>
  </div>
</div>

<!-- =================================================
     5. 娱乐功能 (绿色)
     ================================================= -->
<div style="background: #f6ffed; border-left: 5px solid #52c41a; padding: 20px; border-radius: 10px;">
  <h3 style="margin-top: 0; color: #52c41a;">🎉 娱乐与小游戏</h3>
  
  <div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <div style="flex: 1; min-width: 200px;">
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px;">
        <li><code>pjsk听歌识曲</code>：听截取片段猜歌名</li>
        <li><code>pjsk猜卡面</code>：看局部图猜角色卡面</li>
        <li><code>pjsk抽卡</code>：模拟10连抽卡 (支持反抽/指定池)</li>
      </ul>
    </div>
    <div style="flex: 1; min-width: 200px;">
      <ul style="font-size: 13px; line-height: 1.8; color: #555; padding-left: 20px;">
        <li><code>看 [角色名]</code>：随机发送一张该角色的卡面图</li>
        <li><code>随个 [组合]</code>：随机推荐一首歌</li>
        <li><code>葱什么</code>：随机一首 Miku 的歌</li>
        <li><a href="#/meme" style="color:#52c41a; text-decoration:underline;">表情制作</a>：点击查看制作教程</li>
      </ul>
    </div>
  </div>
</div>