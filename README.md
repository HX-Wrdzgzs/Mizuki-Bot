<!-- 顶部横排布局 -->
<div style="display: flex; align-items: center; justify-content: center; gap: 25px; margin-top: 40px; padding: 0 10px;">
  
  <!-- 头像：缩小到 100px -->
  <img src="Picture/avatar.jpg" style="width: 100px; height: 100px; border-radius: 50%; object-fit: cover; border: 3px solid #E97EB3; box-shadow: 0 4px 15px rgba(233, 126, 179, 0.3); flex-shrink: 0;">

  <!-- 文字区域 -->
  <div style="text-align: left;">
    <!-- 标题 -->
    <h1 style="background: linear-gradient(135deg, #E97EB3 0%, #8A66C2 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; margin: 0; font-size: 2rem; line-height: 1.2;">
      Mizuki Bot
    </h1>
    <span style="font-size: 1.2rem; color: #555; font-weight: bold;">帮助文档</span>
    
    <!-- 随机语录 (JS自动填充) -->
    <p id="mizuki-quote" style="color: #999; font-size: 13px; font-style: italic; margin-top: 8px; min-height: 20px;">
      Loading...
    </p>
  </div>

</div>

<!-- 徽章居中 -->
<div style="text-align: center; margin-top: 20px;">
  <img src="https://img.shields.io/badge/Version-2.0.0-E97EB3?style=flat-square&logo=github">
  <img src="https://img.shields.io/badge/Status-Running-8A66C2?style=flat-square">
</div>

<br>
<br>

<!-- 功能卡片区域 (保持不变) -->
<div style="display: flex; flex-wrap: wrap; gap: 15px; justify-content: center;">

  <a href="#/pjsk" style="text-decoration: none; width: 46%; min-width: 140px; flex-grow: 1;">
    <div style="background: #fff0f6; padding: 20px 10px; border-radius: 15px; border: 2px solid #E97EB3; text-align: center; transition: transform 0.2s;">
      <h3 style="margin: 0; color: #E97EB3; font-size: 1.1rem;">🎵 PJSK</h3>
      <p style="font-size: 11px; margin: 8px 0 0; color: #666; line-height: 1.4;">查分 · 查榜 · 3D家园<br>SK表情包制作</p>
    </div>
  </a>

  <a href="#/maimai" style="text-decoration: none; width: 46%; min-width: 140px; flex-grow: 1;">
    <div style="background: #fff; padding: 20px 10px; border-radius: 15px; border: 2px solid #ffcc00; text-align: center; transition: transform 0.2s;">
      <h3 style="margin: 0; color: #ffcc00; font-size: 1.1rem;">🎰 舞萌 DX</h3>
      <p style="font-size: 11px; margin: 8px 0 0; color: #666; line-height: 1.4;">B50 查分 · 牌子进度<br>机厅排队助手</p>
    </div>
  </a>

  <a href="#/meme" style="text-decoration: none; width: 46%; min-width: 140px; flex-grow: 1;">
    <div style="background: #fff; padding: 20px 10px; border-radius: 15px; border: 2px solid #66ccff; text-align: center; transition: transform 0.2s;">
      <h3 style="margin: 0; color: #66ccff; font-size: 1.1rem;">🎨 表情制作</h3>
      <p style="font-size: 11px; margin: 8px 0 0; color: #666; line-height: 1.4;">瑞希 · 奏 · 绘名<br>自定义对话生成</p>
    </div>
  </a>

  <a href="#/tools" style="text-decoration: none; width: 46%; min-width: 140px; flex-grow: 1;">
    <div style="background: #fff; padding: 20px 10px; border-radius: 15px; border: 2px solid #99cc99; text-align: center; transition: transform 0.2s;">
      <h3 style="margin: 0; color: #99cc99; font-size: 1.1rem;">🛠️ 通用工具</h3>
      <p style="font-size: 11px; margin: 8px 0 0; color: #666; line-height: 1.4;">群管 · 抽签 · 点歌<br>MC互通 · Steam</p>
    </div>
  </a>

  <a href="#/contribution" style="text-decoration: none; width: 94%; min-width: 140px; flex-grow: 1;">
    <div style="background: linear-gradient(to right, #fdfbfb, #ebedee); padding: 15px; border-radius: 15px; border: 2px solid #ccc; text-align: center;">
      <h3 style="margin: 0; color: #555; font-size: 1.1rem;">🏆 贡献者与鸣谢</h3>
      <p style="font-size: 11px; margin: 5px 0 0; color: #666;">查看开发团队名单</p>
    </div>
  </a>

</div>