<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <title>Mizuki Bot</title>
  <link rel="icon" href="Picture/avatar.jpg">
  <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, user-scalable=no">
  
  <link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify@4/lib/themes/vue.css">

  <style>
    /* --- 🎀 全局样式 --- */
    :root { --theme-color: #E97EB3; }
    
    body {
      background-color: #f5f7fa !important;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    }

    .markdown-section {
      background-color: #fff;
      margin: 20px auto;
      padding: 30px 40px !important;
      border-radius: 20px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.03);
      max-width: 900px;
    }

    .markdown-section a { color: #E97EB3; font-weight: bold; text-decoration: none; }
    .markdown-section img { border-radius: 12px; }

    .sidebar { background-color: #fff; border-right: none; }
    .sidebar-nav li.active > a {
      border-right: 3px solid #E97EB3; color: #E97EB3;
      background-color: #fff0f6; border-radius: 8px 0 0 8px;
    }

    .sidebar-toggle {
      position: fixed !important; bottom: 30px !important; right: 30px !important;
      top: auto !important; left: auto !important;
      width: 50px !important; height: 50px !important;
      background: #E97EB3 !important; border-radius: 50% !important;
      box-shadow: 0 4px 15px rgba(233, 126, 179, 0.4) !important;
      display: flex !important; align-items: center !important; justify-content: center !important;
      z-index: 99999 !important;
    }
    .sidebar-toggle span { background-color: #fff !important; }

    /* 侧边栏 Logo */
    .sidebar-logo-container {
      display: flex; flex-direction: column; align-items: center; padding: 30px 0 10px 0;
    }
    .sidebar-logo {
      width: 80px; height: 80px; 
      border-radius: 50%; 
      object-fit: cover; 
      border: 3px solid #E97EB3; 
      box-shadow: 0 4px 15px rgba(233, 126, 179, 0.3);
    }
    .sidebar-title-text {
      /* ✨✨✨ 这里加粗了 ✨✨✨ */
      font-size: 1.2rem; 
      font-weight: 900; 
      color: #E97EB3; 
      margin-top: 10px;
    }
  </style>
</head>

<body>
  <div id="app"></div>

  <script>
    const quotes = [
      "「 ボクは……ボクでいたいだけ 」<br>我只是……想做我自己罢了",
      "「 秘密って、なんだかワクワクしない？ 」<br>所谓秘密，不觉得令人有些兴奋吗？",
      "「 25時、ナイトコードで。 」<br>25时，在 Nightcord 见。",
      "「 かわいいは正義！だよね？ 」<br>可爱即正义！对吧？",
      "「 ボクのこと、知りたい？ 」<br>想知道，关于我的事吗？",
      "「 逃げ続けるのも、悪くないかもね 」<br>一直逃避下去，或许也不坏呢",
      "「 君も、こっち側に来る？ 」<br>你也要，来这边吗？"
    ];

    window.$docsify = {
      name: `
        <div class="sidebar-logo-container">
          <img src="Picture/avatar.jpg" class="sidebar-logo">
          <span class="sidebar-title-text">Mizuki Bot</span>
        </div>
      `,
      repo: '', 
      loadSidebar: true,
      subMaxLevel: 3,
      auto2top: true,
      themeColor: '#E97EB3',
      
      pagination: {
        previousText: '← 上一章',
        nextText: '下一章 →',
        crossChapter: true,
      },

      plugins: [
        function(hook, vm) {
          hook.doneEach(function() {
            var links = document.querySelectorAll('.sidebar-nav a');
            links.forEach(function(link) {
              link.addEventListener('click', function(e) {
                if (document.body.clientWidth <= 768) {
                  document.body.classList.remove('close');
                  document.body.classList.add('close');
                }
              });
            });

            var quoteBox = document.getElementById('mizuki-quote');
            if (quoteBox) {
              var randomQ = quotes[Math.floor(Math.random() * quotes.length)];
              quoteBox.innerHTML = randomQ;
            }
          });
        }
      ]
    }
  </script>

  <script src="//cdn.jsdelivr.net/npm/docsify@4/lib/docsify.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/zoom-image.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify-copy-code/dist/docsify-copy-code.min.js"></script>
  <script src="//cdn.jsdelivr.net/npm/docsify-pagination/dist/docsify-pagination.min.js"></script>
</body>
</html>