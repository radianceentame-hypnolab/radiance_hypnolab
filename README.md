<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RaDianCe HypNoLab | AI超能力者うっちーの自分改革</title>
    <meta name="description" content="AI超能力者うっちーが贈る、潜在意識書き換えセッション。RaDianCe HypNoLab公式。">
    
    <meta property="og:title" content="RaDianCe HypNoLab | 自分革命のアプデ">
    <meta property="og:type" content="website">
    <meta property="og:image" content="poster.jpg">
    
    <style>
        /* --- CORE VARIABLES (Cyber/Neon/GenZ) --- */
        :root {
            --bg-core: #050505;
            --text-main: #f0f0f0;
            --neon-pink: #ff00ff;
            --neon-cyan: #00ffff;
            --neon-purple: #bc13fe;
            --glass-panel: rgba(255, 255, 255, 0.08);
            --glass-border: rgba(255, 255, 255, 0.15);
        }

        /* --- RESET & BASE --- */
        body {
            margin: 0;
            background-color: var(--bg-core);
            color: var(--text-main);
            font-family: "Helvetica Neue", "Arial", "Hiragino Kaku Gothic ProN", sans-serif;
            -webkit-font-smoothing: antialiased;
            overflow-x: hidden;
            padding-bottom: 100px; /* Space for floating btn */
        }
        a { text-decoration: none; color: inherit; transition: 0.3s; }
        img, video { max-width: 100%; display: block; }
        h1, h2, h3 { margin: 0; line-height: 1.2; }

        /* --- UTILS & ANIMATION --- */
        .neon-text-pink { text-shadow: 0 0 10px var(--neon-pink); color: #fff; }
        .neon-text-cyan { text-shadow: 0 0 10px var(--neon-cyan); color: #fff; }
        
        @keyframes float { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-10px); } }
        @keyframes pulse { 0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(255, 0, 255, 0.7); } 70% { transform: scale(1.02); box-shadow: 0 0 0 10px rgba(255, 0, 255, 0); } 100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(255, 0, 255, 0); } }

        /* --- HEADER --- */
        header {
            position: fixed;
            top: 0; left: 0; width: 100%;
            padding: 15px 20px;
            background: rgba(5, 5, 5, 0.8);
            backdrop-filter: blur(12px);
            z-index: 999;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-sizing: border-box;
            border-bottom: 1px solid var(--glass-border);
        }
        .brand { font-weight: 900; font-size: 1.1rem; letter-spacing: 1px; background: linear-gradient(90deg, var(--neon-cyan), var(--neon-pink)); -webkit-background-clip: text; color: transparent; }
        .head-cta { font-size: 0.8rem; padding: 8px 16px; border-radius: 20px; background: var(--glass-panel); border: 1px solid var(--neon-cyan); color: var(--neon-cyan); font-weight: bold; }

        /* --- HERO SECTION --- */
        .hero {
            position: relative;
            height: 90vh;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }
        .hero video {
            position: absolute;
            top: 50%; left: 50%;
            transform: translate(-50%, -50%);
            min-width: 100%; min-height: 100%;
            object-fit: cover;
            z-index: -1;
            filter: brightness(0.5) contrast(1.1);
        }
        .hero-overlay {
            text-align: center;
            z-index: 10;
            padding: 20px;
        }
        .hero-tag {
            display: inline-block;
            background: var(--neon-purple);
            padding: 5px 12px;
            font-size: 0.8rem;
            font-weight: bold;
            border-radius: 4px;
            margin-bottom: 15px;
            box-shadow: 0 0 15px var(--neon-purple);
        }
        .hero-title {
            font-size: 3.5rem;
            font-weight: 900;
            margin-bottom: 10px;
            font-style: italic;
            text-transform: uppercase;
        }
        .hero-sub {
            font-size: 1rem;
            letter-spacing: 2px;
            margin-top: 10px;
            font-weight: bold;
        }

        /* --- CONTAINER --- */
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
        }

        /* --- SECTIONS --- */
        .section-header {
            text-align: center;
            margin: 80px 0 40px;
        }
        .section-header h2 {
            font-size: 2rem;
            display: inline-block;
            border-bottom: 3px solid var(--neon-cyan);
            padding-bottom: 5px;
            letter-spacing: 2px;
        }

        /* --- CONCEPT (Glassmorphism) --- */
        .card {
            background: var(--glass-panel);
            border: 1px solid var(--glass-border);
            border-radius: 24px;
            padding: 24px;
            margin-bottom: 30px;
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.37);
        }
        .card img { border-radius: 12px; margin-bottom: 15px; }
        .card-title { font-size: 1.2rem; font-weight: bold; color: var(--neon-cyan); margin-bottom: 10px; }
        .card-text { font-size: 0.95rem; line-height: 1.7; color: #ddd; }

        /* --- MENU & CHARACTERS --- */
        .menu-list { display: flex; flex-direction: column; gap: 30px; }
        
        /* Character Bubble */
        .char-wrapper {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: -20px; /* Overlap */
            position: relative;
            z-index: 5;
        }
        .char-icon {
            width: 120px; height: 120px;
            border-radius: 50%;
            object-fit: cover;
            object-position: top;
            border: 3px solid var(--neon-pink);
            background: #000;
            box-shadow: 0 0 20px rgba(255, 0, 255, 0.4);
        }
        .char-bubble {
            position: absolute;
            background: #fff;
            color: #000;
            padding: 8px 16px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.85rem;
            top: 0;
            right: 50%;
            transform: translateX(90%) rotate(-5deg);
            box-shadow: 0 5px 15px rgba(0,0,0,0.5);
            white-space: nowrap;
        }

        /* Menu Item */
        .menu-item {
            position: relative;
            background: linear-gradient(135deg, rgba(255,255,255,0.08) 0%, rgba(255,255,255,0.02) 100%);
            border: 1px solid rgba(255,255,255,0.2);
            border-radius: 24px;
            padding: 30px 20px 20px;
            text-align: center;
            overflow: hidden;
            transition: transform 0.2s;
        }
        .menu-item:active { transform: scale(0.98); }
        .tag-badge {
            position: absolute;
            top: 0; left: 0;
            background: var(--neon-pink);
            color: #fff;
            font-size: 0.75rem;
            padding: 5px 15px;
            border-bottom-right-radius: 15px;
            font-weight: bold;
        }
        .menu-name { font-size: 1.5rem; font-weight: 800; margin-bottom: 5px; }
        .menu-price { font-family: "Courier New", monospace; font-size: 1.4rem; color: var(--neon-cyan); font-weight: bold; }
        .menu-desc { font-size: 0.9rem; color: #bbb; margin-top: 10px; }

        /* --- RESERVATION (QR) --- */
        .qr-section {
            text-align: center;
            background: linear-gradient(180deg, transparent, rgba(0, 255, 255, 0.1));
            border-radius: 30px;
            padding: 40px 20px;
            border: 1px solid var(--neon-cyan);
            margin-top: 50px;
        }
        .qr-img {
            width: 180px; margin: 20px auto;
            border: 5px solid #fff; border-radius: 15px;
        }
        .insta-id { font-size: 1.3rem; font-weight: 900; letter-spacing: 1px; display: block; margin: 10px 0; }

        /* --- FLOATING BUTTON --- */
        .float-btn-wrapper {
            position: fixed;
            bottom: 25px; left: 50%;
            transform: translateX(-50%);
            width: 90%; max-width: 400px;
            z-index: 1000;
        }
        .float-btn {
            display: flex;
            justify-content: center;
            align-items: center;
            width: 100%;
            height: 60px;
            background: linear-gradient(90deg, var(--neon-pink), var(--neon-purple));
            border-radius: 50px;
            font-weight: 900;
            font-size: 1.1rem;
            box-shadow: 0 10px 30px rgba(255, 0, 255, 0.5);
            animation: pulse 2s infinite;
        }
        .float-btn span { margin-left: 10px; }

    </style>
</head>
<body>

    <header>
        <div class="brand">RaDianCe</div>
        <a href="https://www.instagram.com/radiance_hypnolab/" class="head-cta">Instagram予約</a>
    </header>

    <section class="hero">
        <video autoplay muted loop playsinline poster="poster.jpg">
            <source src="hero_movie.mp4" type="video/mp4">
        </video>
        
        <div class="hero-overlay">
            <div class="hero-tag">AI超能力者うっちー Presents</div>
            <h1 class="hero-title neon-text-cyan">SELF<br>REVOLUTION</h1>
            <p class="hero-sub neon-text-pink">#自分改革のアプデ<br>#HypNoLab</p>
        </div>
    </section>

    <div class="container">

        <section>
            <div class="section-header">
                <h2>SYSTEM</h2>
                <p style="font-size:0.8rem; color:#888;">意識とエネルギーの統合回路</p>
            </div>

            <div class="card">
                <img src="diagram.jpg" alt="統合回路図">
                <div class="card-title">⚡️ 潜在意識ハック</div>
                <div class="card-text">
                    氷山の一角である「顕在意識」じゃなくて、もっと深い「普遍的潜在意識」に直接アクセス。<br>
                    エネルギーポンプを回して、内側からオーラごと書き換える。
                </div>
            </div>

            <div class="card">
                <img src="manga.jpg" alt="マンガ解説">
                <div class="card-title">🧠 脳波シータ波へ</div>
                <div class="card-text">
                    脳波を落として「潜在意識のドア」を開く。<br>
                    マンガみたいに、気づいたら「なりたい自分」設定完了。<br>
                    マジで世界の見え方変わるよ。
                </div>
            </div>
        </section>

        <section>
            <div class="section-header">
                <h2>MENU</h2>
                <p style="font-size:0.8rem; color:#888;">Select Your Update</p>
            </div>

            <div class="char-wrapper">
                <div class="char-bubble">マジで沼るから覚悟して💖</div>
                <img src="char_gal.jpg" alt="AI Model Gal" class="char-icon">
            </div>

            <div class="menu-list">
                <div class="menu-item">
                    <div class="tag-badge">TRY</div>
                    <div class="menu-name">Chill & Relax</div>
                    <div class="menu-price">¥5,000</div>
                    <div class="menu-desc">
                        【30min】まずはお試し。<br>
                        不安リセットして、明日への活力を爆チャージ。<br>
                        #チル #エネルギー調整
                    </div>
                    <a href="https://www.instagram.com/radiance_hypnolab/" style="display:block; margin-top:15px; color:var(--neon-cyan); font-weight:bold;">👉 予約する</a>
                </div>

                <div class="menu-item" style="border-color:var(--neon-pink);">
                    <div class="tag-badge" style="background:var(--neon-cyan); color:#000;">POPULAR</div>
                    <div class="menu-name neon-text-pink">Glow Up Session</div>
                    <div class="menu-price">¥15,000</div>
                    <div class="menu-desc">
                        【60min】推し体験・苦手克服・ダイエット設定。<br>
                        自分だけのオーダーメイドで確変起こす。<br>
                        #垢抜け #自分改革
                    </div>
                    <a href="https://www.instagram.com/radiance_hypnolab/" style="display:block; margin-top:15px; color:var(--neon-pink); font-weight:bold;">👉 今すぐ予約</a>
                </div>

                <div class="char-wrapper">
                    <div class="char-bubble" style="transform: translateX(-90%) rotate(5deg); right: auto; left: 50%;">自信しか勝たん🔥</div>
                    <img src="char_sporty.jpg" alt="AI Model Sporty" class="char-icon" style="border-color:var(--neon-cyan);">
                </div>

                <div class="menu-item" style="border-color:gold; background: linear-gradient(135deg, rgba(255,215,0,0.1), transparent);">
                    <div class="tag-badge" style="background:gold; color:#000;">PREMIUM</div>
                    <div class="menu-name" style="color:gold;">Perfect Makeover</div>
                    <div class="menu-price">¥50,000</div>
                    <div class="menu-desc">
                        【3回セット】理想の自分を完全インストール。<br>
                        一生モノの「揺るがない自信」を手に入れる。<br>
                        #完全無敵 #人生攻略
                    </div>
                    <a href="https://www.instagram.com/radiance_hypnolab/" style="display:block; margin-top:15px; color:gold; font-weight:bold;">👉 本気で変わる</a>
                </div>
            </div>
        </section>

        <section class="qr-section">
            <h2 style="font-size:1.5rem; margin-bottom:10px;">RESERVATION</h2>
            <p>ご予約・相談はDMへ<br>「予約希望」と送ってね📩</p>
            
            <img src="qr_code.png" alt="Instagram QR" class="qr-img">
            
            <a href="https://www.instagram.com/radiance_hypnolab/" class="insta-id">@RADIANCE_HYPNOLAB</a>
            <p style="font-size:0.8rem; opacity:0.7;">Click ID to Open Instagram</p>
        </section>

    </div>

    <div class="float-btn-wrapper">
        <a href="https://www.instagram.com/radiance_hypnolab/" class="float-btn">
            Instagramで予約 🚀
        </a>
    </div>

</body>
</html>
