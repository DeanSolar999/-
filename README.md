<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>2026 木曜修仙鬥法年終賽 - 元氣規程</title>
    <style>
        :root {
            --bg-color: #f0f9ff;
            --primary-blue: #0ea5e9;
            --primary-yellow: #fde047;
            --accent-orange: #fb923c;
            --defend-color: #334155;
            --attack-color: #ffffff;
            --text-dark: #334155;
            --white: #ffffff;
            --card-soft-bg: #f8fafc;
        }

        body {
            font-family: 'Quicksand', 'PingFang TC', 'Microsoft JhengHei', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-dark);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .container {
            max-width: 800px;
            width: 100%;
            background: var(--white);
            border-radius: 30px;
            padding: 40px;
            box-shadow: 0 20px 50px rgba(0,0,0,0.05);
            border: 8px solid var(--primary-yellow);
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        h1 {
            color: var(--primary-blue);
            font-size: 2.2em;
            margin: 0;
            background: linear-gradient(transparent 60%, var(--primary-yellow) 0%);
            display: inline-block;
        }

        .subtitle {
            font-weight: bold;
            color: var(--accent-orange);
            margin-top: 10px;
            letter-spacing: 2px;
        }

        .section-title {
            font-size: 1.3em;
            font-weight: bold;
            color: var(--primary-blue);
            margin-top: 40px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            border-bottom: 2px solid var(--primary-yellow);
            padding-bottom: 5px;
        }

        /* 輪動圖解 CSS */
        .rotation-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }

        .rotation-card {
            background: #fff;
            border: 2px solid #e2e8f0;
            border-radius: 15px;
            padding: 15px;
            text-align: center;
            transition: transform 0.2s;
        }

        .rotation-card:hover { transform: translateY(-5px); }

        .circle-ui {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            border: 3px dashed var(--primary-blue);
            margin: 0 auto 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: var(--primary-blue);
            font-size: 1.2em;
        }

        /* 列表與卡片 */
        .battle-layout {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 20px;
        }

        .team-tag {
            padding: 20px;
            border-radius: 20px;
            text-align: center;
            font-weight: bold;
        }

        .defend { background-color: var(--defend-color); color: white; }
        .attack { background-color: var(--attack-color); color: var(--text-dark); border: 2px solid #e2e8f0; }

        .info-card {
            background: var(--card-soft-bg);
            padding: 20px;
            border-radius: 20px;
            border: 2px dashed #cbd5e1;
        }

        /* 按鈕樣式 */
        .btn-submit {
            display: block;
            width: 100%;
            max-width: 300px;
            margin: 40px auto;
            background: var(--primary-blue);
            color: white;
            text-align: center;
            padding: 18px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.2em;
            box-shadow: 0 10px 20px rgba(14, 165, 233, 0.3);
            transition: 0.3s;
        }

        .btn-submit:hover {
            background: #0284c7;
            transform: scale(1.05);
        }

        .footer-warning {
            background: #fff1f2;
            color: #be123c;
            padding: 15px;
            border-radius: 15px;
            text-align: center;
            font-size: 0.9em;
            margin-top: 30px;
        }

        @media (max-width: 600px) {
            .battle-layout { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <h1>2026 木曜修仙鬥法年終賽</h1>
        <div class="subtitle">☀️ 年度全循環賽 ‧ 攻城大對抗 ☀️</div>
    </header>

    <div class="section-title">⚔️ 攻守分組與建議</div>
    <div class="battle-layout">
        <div class="team-tag defend">
            🏰 守城組 (1, 2, 3, 4)<br>
            <small>固定場不輪動</small><br>
            <span style="background:white; color:black; padding:2px 8px; border-radius:5px; font-size:0.75em;">穿深色服裝</span>
        </div>
        <div class="team-tag attack">
            ⚔️ 攻城組 (A, B, C, D)<br>
            <small>各場次輪流進攻</small><br>
            <span style="background:black; color:white; padding:2px 8px; border-radius:5px; font-size:0.75em;">穿淺色服裝</span>
        </div>
    </div>

    <div class="section-title">🔄 選手輪動圖解</div>
    <div class="rotation-grid">
        <div class="rotation-card">
            <div class="circle-ui">1 & 2</div>
            <div style="font-weight: bold;">第一階段</div>
            <small>0 - 10 分</small>
        </div>
        <div class="rotation-card">
            <div class="circle-ui" style="border-color: var(--accent-orange); color: var(--accent-orange);">2 & 3</div>
            <div style="font-weight: bold;">第二階段</div>
            <small>11 - 20 分</small>
        </div>
        <div class="rotation-card">
            <div class="circle-ui">3 & 4</div>
            <div style="font-weight: bold;">第三階段</div>
            <small>21 - 30 分</small>
        </div>
        <div class="rotation-card">
            <div class="circle-ui" style="border-color: var(--accent-orange); color: var(--accent-orange);">4 & 1</div>
            <div style="font-weight: bold;">第四階段</div>
            <small>31 - 40 分</small>
        </div>
    </div>

    <div class="section-title">⚖️ 審判與工作分配</div>
    <div class="info-card">
        <p>🚩 <b>線審：</b>各派一名隊員負責監線。</p>
        <p>👨‍⚖️ <b>主審：</b>每隊各負責 20 分之判決與控場。</p>
        <p>📝 <b>成績：</b>請守城組於賽後統一登錄至系統。</p>
    </div>

    <a href="https://deansolar999.github.io/battle/" class="btn-submit">
        📝 賽後請守城方進入系統登錄成績
    </a>

    <div class="footer-warning">
        🌈 提醒您：修仙鬥法意在聯絡感情，開心第一！
    </div>
</div>

<script>
    /* Firebase 初始化區塊 (若未來需直接整合)
       Firebase Project ID: muyao-battle
    */
    // const firebaseConfig = { ... };
</script>

</body>
</html>
