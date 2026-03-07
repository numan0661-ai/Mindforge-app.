#   
<!DOCTYPE html>  
<html lang="tr">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">  
    <meta name="theme-color" content="#0f0f23">  
    <meta name="apple-mobile-web-app-capable" content="yes">  
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">  
    <meta name="apple-mobile-web-app-title" content="MindForge">  
    <title>MindForge AI</title>  
    <style>  
        *{margin:0;padding:0;box-sizing:border-box;-webkit-tap-highlight-color:transparent}  
        :root{--primary:#6366f1;--secondary:#8b5cf6;--accent:#06b6d4;--bg:#0f0f23;--surface:#1a1a2e;--surface-light:#252542;--text:#f8fafc;--text-muted:#94a3b8;--success:#10b981;--warning:#f59e0b;--danger:#ef4444}  
        body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,sans-serif;background:var(--bg);color:var(--text);min-height:100vh;overflow-x:hidden;-webkit-font-smoothing:antialiased}  
        .app-container{max-width:430px;margin:0 auto;min-height:100vh;position:relative;padding-bottom:100px}  
        .header{padding:20px;background:linear-gradient(180deg,var(--bg) 0%,transparent 100%);position:sticky;top:0;z-index:100;backdrop-filter:blur(10px)}  
        .header-top{display:flex;justify-content:space-between;align-items:center;margin-bottom:20px}  
        .logo{font-size:24px;font-weight:800;background:linear-gradient(135deg,var(--primary),var(--accent));-webkit-background-clip:text;-webkit-text-fill-color:transparent}  
        .streak{display:flex;align-items:center;gap:5px;background:var(--surface);padding:8px 16px;border-radius:20px;font-size:14px;font-weight:600}  
        .stats-container{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;padding:0 20px;margin-bottom:30px}  
        .stat-card{background:var(--surface);border-radius:16px;padding:16px;border:1px solid rgba(255,255,255,0.05)}  
        .stat-icon{width:40px;height:40px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:20px;margin-bottom:10px}  
        .stat-card:nth-child(1) .stat-icon{background:rgba(239,68,68,0.2)}  
        .stat-card:nth-child(2) .stat-icon{background:rgba(245,158,11,0.2)}  
        .stat-card:nth-child(3) .stat-icon{background:rgba(16,185,129,0.2)}  
        .stat-card:nth-child(4) .stat-icon{background:rgba(99,102,241,0.2)}  
        .stat-label{font-size:12px;color:var(--text-muted);margin-bottom:4px}  
        .stat-value{font-size:20px;font-weight:700}  
        .section-title{padding:0 20px;font-size:20px;font-weight:700;margin-bottom:15px;display:flex;align-items:center;justify-content:space-between}  
        .view-all{font-size:14px;color:var(--primary);font-weight:500}  
        .modules-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px;padding:0 20px;margin-bottom:30px}  
        .module-card{background:var(--surface);border-radius:20px;padding:20px;border:1px solid rgba(255,255,255,0.05);position:relative;overflow:hidden;cursor:pointer;transition:all 0.3s;min-height:160px;display:flex;flex-direction:column}  
        .module-icon{width:50px;height:50px;border-radius:14px;display:flex;align-items:center;justify-content:center;font-size:24px;margin-bottom:12px}  
        .module-card.fitness .module-icon{background:linear-gradient(135deg,#f093fb 0%,#f5576c 100%)}  
        .module-card.voice .module-icon{background:linear-gradient(135deg,#4facfe 0%,#00f2fe 100%)}  
        .module-card.mind .module-icon{background:linear-gradient(135deg,#43e97b 0%,#38f9d7 100%)}  
        .module-card.logic .module-icon{background:linear-gradient(135deg,#fa709a 0%,#fee140 100%)}  
        .module-title{font-size:16px;font-weight:700;margin-bottom:4px}  
        .module-desc{font-size:12px;color:var(--text-muted);line-height:1.4;flex:1}  
        .module-progress{margin-top:12px;height:4px;background:rgba(255,255,255,0.1);border-radius:2px;overflow:hidden}  
        .module-progress-bar{height:100%;background:linear-gradient(90deg,var(--primary),var(--secondary));border-radius:2px;transition:width 0.5s ease}  
        .challenges-container{padding:0 20px;margin-bottom:30px}  
        .challenge-card{background:var(--surface);border-radius:16px;padding:16px;margin-bottom:12px;border:1px solid rgba(255,255,255,0.05);display:flex;align-items:center;gap:15px;cursor:pointer}  
        .challenge-icon{width:50px;height:50px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:24px;flex-shrink:0}  
        .challenge-info{flex:1}  
        .challenge-title{font-size:15px;font-weight:600;margin-bottom:4px}  
        .challenge-meta{font-size:12px;color:var(--text-muted)}  
        .challenge-btn{width:36px;height:36px;border-radius:50%;border:2px solid var(--primary);background:transparent;color:var(--primary);display:flex;align-items:center;justify-content:center;font-size:16px;cursor:pointer}  
        .bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:430px;background:rgba(26,26,46,0.95);backdrop-filter:blur(20px);border-top:1px solid rgba(255,255,255,0.05);display:flex;justify-content:space-around;padding:12px 0 30px;z-index:1000}  
        .nav-item{display:flex;flex-direction:column;align-items:center;gap:4px;padding:8px 16px;cursor:pointer;border:none;background:none;color:var(--text-muted)}  
        .nav-item.active{color:var(--primary)}  
        .nav-icon{font-size:24px}  
        .nav-label{font-size:11px;font-weight:500}  
        .screen{display:none;min-height:100vh;padding-bottom:100px}  
        .screen.active{display:block;animation:fadeIn 0.3s ease}  
        @keyframes fadeIn{from{opacity:0;transform:translateX(20px)}to{opacity:1;transform:translateX(0)}}  
        .screen-header{padding:60px 20px 20px;background:var(--surface);border-radius:0 0 30px 30px;margin-bottom:20px}  
        .back-btn{background:none;border:none;color:var(--text);font-size:24px;cursor:pointer;margin-bottom:20px;padding:0}  
        .screen-title{font-size:28px;font-weight:800;margin-bottom:8px}  
        .screen-subtitle{color:var(--text-muted);font-size:16px}  
        .exercise-list{padding:0 20px}  
        .exercise-card{background:var(--surface);border-radius:16px;padding:20px;margin-bottom:12px;border:1px solid rgba(255,255,255,0.05)}  
        .exercise-header{display:flex;justify-content:space-between;align-items:start;margin-bottom:15px}  
        .exercise-name{font-size:18px;font-weight:700;margin-bottom:4px}  
        .exercise-duration{font-size:13px;color:var(--text-muted)}  
        .difficulty{padding:4px 10px;border-radius:20px;font-size:11px;font-weight:600;text-transform:uppercase}  
        .difficulty.easy{background:rgba(16,185,129,0.2);color:var(--success)}  
        .difficulty.medium{background:rgba(245,158,11,0.2);color:var(--warning)}  
        .difficulty.hard{background:rgba(239,68,68,0.2);color:var(--danger)}  
        .exercise-btn{width:100%;padding:14px;border-radius:12px;border:none;background:linear-gradient(135deg,var(--primary),var(--secondary));color:white;font-size:15px;font-weight:600;cursor:pointer}  
        .game-container{padding:20px;text-align:center}  
        .timer-display{font-size:72px;font-weight:800;font-variant-numeric:tabular-nums;margin:40px 0;font-family:'Courier New',monospace;text-shadow:0 0 30px rgba(99,102,241,0.5)}  
        .game-controls{display:flex;gap:15px;justify-content:center;margin-top:30px}  
        .control-btn{padding:16px 32px;border-radius:16px;border:none;font-size:16px;font-weight:600;cursor:pointer}  
        .control-btn.primary{background:linear-gradient(135deg,var(--primary),var(--secondary));color:white}  
        .control-btn.secondary{background:var(--surface-light);color:var(--text)}  
        .toast{position:fixed;bottom:100px;left:50%;transform:translateX(-50%) translateY(100px);background:var(--surface);color:white;padding:16px 24px;border-radius:12px;font-size:14px;font-weight:500;box-shadow:0 10px 40px rgba(0,0,0,0.3);opacity:0;transition:all 0.3s;z-index:10002;border:1px solid rgba(255,255,255,0.1)}  
        .toast.show{transform:translateX(-50%) translateY(0);opacity:1}  
        .install-prompt{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,0.95);z-index:10000;display:none;align-items:center;justify-content:center;padding:20px;backdrop-filter:blur(10px)}  
        .install-content{background:var(--surface);border-radius:24px;padding:40px 30px;text-align:center;max-width:350px;border:1px solid rgba(255,255,255,0.1);animation:slideUp 0.5s ease}  
        @keyframes slideUp{from{transform:translateY(50px);opacity:0}to{transform:translateY(0);opacity:1}}  
        .install-icon{width:80px;height:80px;background:linear-gradient(135deg,var(--primary),var(--secondary));border-radius:20px;margin:0 auto 20px;display:flex;align-items:center;justify-content:center;font-size:40px;box-shadow:0 10px 40px rgba(99,102,241,0.3)}  
        .install-btn{background:linear-gradient(135deg,var(--primary),var(--secondary));color:white;border:none;padding:16px 32px;border-radius:12px;font-size:16px;font-weight:600;cursor:pointer;width:100%;margin-top:20px}  
        .skip-install{color:var(--text-muted);margin-top:15px;font-size:14px;cursor:pointer}  
    </style>  
</head>  
<body>  
    <div class="install-prompt" id="installPrompt">  
        <div class="install-content">  
            <div class="install-icon">🧠</div>  
            <h2>MindForge AI</h2>  
            <p style="color:var(--text-muted);margin:10px 0 20px;line-height:1.5">Daha iyi bir deneyim için uygulamayı ana ekranınıza ekleyin!</p>  
            <div style="background:var(--surface-light);padding:15px;border-radius:12px;margin-bottom:20px;text-align:left;font-size:14px">  
                <div style="margin-bottom:8px">📱 <strong>iOS:</strong></div>  
                <div style="color:var(--text-muted)">Safari'de paylaş butonuna tıklayın → "Ana Ekrana Ekle"</div>  
            </div>  
            <button class="install-btn" onclick="dismissInstall()">Anladım</button>  
            <div class="skip-install" onclick="dismissInstall()">Şimdi Değil</div>  
        </div>  
    </div>  
  
    <div class="app-container">  
        <div class="screen active" id="homeScreen">  
            <div class="header">  
                <div class="header-top">  
                    <div class="logo">MindForge</div>  
                    <div class="streak"><span>🔥</span><span id="streakCount">12</span></div>  
                </div>  
            </div>  
            <div class="stats-container">  
                <div class="stat-card"><div class="stat-icon">💪</div><div class="stat-label">Fitness</div><div class="stat-value" id="fitnessStat">85%</div></div>  
                <div class="stat-card"><div class="stat-icon">🗣️</div><div class="stat-label">Diksiyon</div><div class="stat-value" id="voiceStat">62%</div></div>  
                <div class="stat-card"><div class="stat-icon">⚡</div><div class="stat-label">Hızlı Düşünme</div><div class="stat-value" id="mindStat">45%</div></div>  
                <div class="stat-card"><div class="stat-icon">🧩</div><div class="stat-label">Pratik Zeka</div><div class="stat-value" id="logicStat">70%</div></div>  
            </div>  
            <div class="section-title">Modüller<span class="view-all">Tümü</span></div>  
            <div class="modules-grid">  
                <div class="module-card fitness" onclick="openModule('fitness')"><div class="module-icon">💪</div><div class="module-title">FitForge</div><div class="module-desc">AI destekli vücut geliştirme</div><div class="module-progress"><div class="module-progress-bar" style="width:85%"></div></div></div>  
                <div class="module-card voice" onclick="openModule('voice')"><div class="module-icon">🗣️</div><div class="module-title">VoiceForge</div><div class="module-desc">Diksiyon ve konuşma</div><div class="module-progress"><div class="module-progress-bar" style="width:62%"></div></div></div>  
                <div class="module-card mind" onclick="openModule('mind')"><div class="module-icon">⚡</div><div class="module-title">MindForge</div><div class="module-desc">Hızlı düşünme oyunları</div><div class="module-progress"><div class="module-progress-bar" style="width:45%"></div></div></div>  
                <div class="module-card logic" onclick="openModule('logic')"><div class="module-icon">🧩</div><div class="module-title">LogicForge</div><div class="module-desc">Pratik zeka soruları</div><div class="module-progress"><div class="module-progress-bar" style="width:70%"></div></div></div>  
            </div>  
            <div class="section-title">Günlük Görevler<span class="view-all">Takvim</span></div>  
            <div class="challenges-container" id="challengesList"></div>  
        </div>  
  
        <div class="screen" id="fitnessScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">FitForge</div><div class="screen-subtitle">Bugünkü antrenman</div></div>  
            <div class="exercise-list" id="fitnessList"></div>  
        </div>  
  
        <div class="screen" id="voiceScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">VoiceForge</div><div class="screen-subtitle">Diksiyon egzersizleri</div></div>  
            <div class="exercise-list" id="voiceList"></div>  
        </div>  
  
        <div class="screen" id="mindScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">MindForge</div><div class="screen-subtitle">Refleks oyunu</div></div>  
            <div class="game-container">  
                <div class="timer-display" id="reactionTimer">00:00</div>  
                <div style="color:var(--text-muted);margin-bottom:30px">Yeşil ışık yanınca hemen dokun!</div>  
                <div class="game-controls">  
                    <button class="control-btn primary" onclick="startReactionGame()">Başla</button>  
                    <button class="control-btn secondary" onclick="showStats()">Skorlar</button>  
                </div>  
                <div id="gameResult" style="margin-top:30px;font-size:18px;font-weight:600"></div>  
            </div>  
        </div>  
  
        <div class="screen" id="logicScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">LogicForge</div><div class="screen-subtitle">Bulmacalar</div></div>  
            <div class="exercise-list" id="logicList"></div>  
        </div>  
  
        <nav class="bottom-nav">  
            <button class="nav-item active" onclick="goHome()"><span class="nav-icon">🏠</span><span class="nav-label">Ana Sayfa</span></button>  
            <button class="nav-item" onclick="showToast('İlerleme raporu hazırlanıyor...')"><span class="nav-icon">📊</span><span class="nav-label">İlerleme</span></button>  
            <button class="nav-item" onclick="showToast('AI Koç: Bugün ne çalışalım?')"><span class="nav-icon">🤖</span><span class="nav-label">AI Koç</span></button>  
            <button class="nav-item" onclick="showToast('Profil yakında!')"><span class="nav-icon">👤</span><span class="nav-label">Profil</span></button>  
        </nav>  
    </div>  
  
    <div class="toast" id="toast"></div>  
  
    <script>  
        const defaultData={  
            challenges:[  
                {id:1,icon:'💪',title:'20 Push-up',module:'fitness',duration:'5 dk',color:'#f5576c',completed:false},  
                {id:2,icon:'🗣️',title:'Diksiyon',module:'voice',duration:'10 dk',color:'#4facfe',completed:false},  
                {id:3,icon:'⚡',title:'Refleks Testi',module:'mind',duration:'3 dk',color:'#43e97b',completed:false},  
                {id:4,icon:'🧩',title:'Bulmaca',module:'logic',duration:'15 dk',color:'#fa709a',completed:false}  
            ],  
            fitness:[  
                {id:'f1',name:'Isınma - Jumping Jacks',duration:'3 dk',difficulty:'easy',completed:false},  
                {id:'f2',name:'Push-up (3x12)',duration:'10 dk',difficulty:'medium',completed:false},  
                {id:'f3',name:'Squat (3x15)',duration:'10 dk',difficulty:'medium',completed:false},  
                {id:'f4',name:'Plank (3x45sn)',duration:'5 dk',difficulty:'hard',completed:false}  
            ],  
            voice:[  
                {id:'v1',name:'Diyafram Nefesi',duration:'3 dk',difficulty:'easy',completed:false},  
                {id:'v2',name:'"R" Sesi Pratiği',duration:'5 dk',difficulty:'medium',completed:false},  
                {id:'v3',name:'Hızlı Konuşma',duration:'5 dk',difficulty:'medium',completed:false}  
            ],  
            logic:[  
                {id:'l1',name:'Sudoku Kolay',duration:'10 dk',difficulty:'easy',completed:false},  
                {id:'l2',name:'Mantık Sorusu',duration:'5 dk',difficulty:'medium',completed:false},  
                {id:'l3',name:'Sayı Dizisi',duration:'5 dk',difficulty:'medium',completed:false}  
            ]  
        };  
  
        function showToast(msg){  
            const t=document.getElementById('toast');  
            t.textContent=msg;  
            t.classList.add('show');  
            setTimeout(()=>t.classList.remove('show'),3000);  
        }  
  
        function dismissInstall(){  
            document.getElementById('installPrompt').style.display='none';  
            localStorage.setItem('installPromptDismissed','true');  
        }  
  
        function goHome(){  
            document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));  
            document.getElementById('homeScreen').classList.add('active');  
            document.querySelectorAll('.nav-item').forEach((item,i)=>item.classList.toggle('active',i===0));  
        }  
  
        function openModule(module){  
            document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));  
            document.getElementById(module+'Screen').classList.add('active');  
            if(module==='fitness')renderList('fitnessList',defaultData.fitness,'fitness');  
            else if(module==='voice')renderList('voiceList',defaultData.voice,'voice');  
            else if(module==='logic')renderList('logicList',defaultData.logic,'logic');  
        }  
  
        function renderList(containerId,items,type){  
            const container=document.getElementById(containerId);  
            container.innerHTML=items.map(item=>`  
                <div class="exercise-card">  
                    <div class="exercise-header">  
                        <div>  
                            transition:all 0.3s;min-height:160px;display:flex;flex-direction:column}  
        .module-icon{width:50px;height:50px;border-radius:14px;display:flex;align-items:center;justify-content:center;font-size:24px;margin-bottom:12px}  
        .module-card.fitness .module-icon{background:linear-gradient(135deg,#f093fb 0%,#f5576c 100%)}  
        .module-card.voice .module-icon{background:linear-gradient(135deg,#4facfe 0%,#00f2fe 100%)}  
        .module-card.mind .module-icon{background:linear-gradient(135deg,#43e97b 0%,#38f9d7 100%)}  
        .module-card.logic .module-icon{background:linear-gradient(135deg,#fa709a 0%,#fee140 100%)}  
        .module-title{font-size:16px;font-weight:700;margin-bottom:4px}  
        .module-desc{font-size:12px;color:var(--text-muted);line-height:1.4;flex:1}  
        .module-progress{margin-top:12px;height:4px;background:rgba(255,255,255,0.1);border-radius:2px;overflow:hidden}  
        .module-progress-bar{height:100%;background:linear-gradient(90deg,var(--primary),var(--secondary));border-radius:2px;transition:width 0.5s ease}  
        .challenges-container{padding:0 20px;margin-bottom:30px}  
        .challenge-card{background:var(--surface);border-radius:16px;padding:16px;margin-bottom:12px;border:1px solid rgba(255,255,255,0.05);display:flex;align-items:center;gap:15px;cursor:pointer}  
        .challenge-icon{width:50px;height:50px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:24px;flex-shrink:0}  
        .challenge-info{flex:1}  
        .challenge-title{font-size:15px;font-weight:600;margin-bottom:4px}  
        .challenge-meta{font-size:12px;color:var(--text-muted)}  
        .challenge-btn{width:36px;height:36px;border-radius:50%;border:2px solid var(--primary);background:transparent;color:var(--primary);display:flex;align-items:center;justify-content:center;font-size:16px;cursor:pointer}  
        .bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:430px;background:rgba(26,26,46,0.95);backdrop-filter:blur(20px);border-top:1px solid rgba(255,255,255,0.05);display:flex;justify-content:space-around;padding:12px 0 30px;z-index:1000}  
        .nav-item{display:flex;flex-direction:column;align-items:center;gap:4px;padding:8px 16px;cursor:pointer;border:none;background:none;color:var(--text-muted)}  
        .nav-item.active{color:var(--primary)}  
        .nav-icon{font-size:24px}  
        .nav-label{font-size:11px;font-weight:500}  
        .screen{display:none;min-height:100vh;padding-bottom:100px}  
        .screen.active{display:block;animation:fadeIn 0.3s ease}  
        @keyframes fadeIn{from{opacity:0;transform:translateX(20px)}to{opacity:1;transform:translateX(0)}}  
        .screen-header{padding:60px 20px 20px;background:var(--surface);border-radius:0 0 30px 30px;margin-bottom:20px}  
        .back-btn{background:none;border:none;color:var(--text);font-size:24px;cursor:pointer;margin-bottom:20px;padding:0}  
        .screen-title{font-size:28px;font-weight:800;margin-bottom:8px}  
        .screen-subtitle{color:var(--text-muted);font-size:16px}  
        .exercise-list{padding:0 20px}  
        .exercise-card{background:var(--surface);border-radius:16px;padding:20px;margin-bottom:12px;border:1px solid rgba(255,255,255,0.05)}  
        .exercise-header{display:flex;justify-content:space-between;align-items:start;margin-bottom:15px}  
        .exercise-name{font-size:18px;font-weight:700;margin-bottom:4px}  
        .exercise-duration{font-size:13px;color:var(--text-muted)}  
        .difficulty{padding:4px 10px;border-radius:20px;font-size:11px;font-weight:600;text-transform:uppercase}  
        .difficulty.easy{background:rgba(16,185,129,0.2);color:var(--success)}  
        .difficulty.medium{background:rgba(245,158,11,0.2);color:var(--warning)}  
        .difficulty.hard{background:rgba(239,68,68,0.2);color:var(--danger)}  
        .exercise-btn{width:100%;padding:14px;border-radius:12px;border:none;background:linear-gradient(135deg,var(--primary),var(--secondary));color:white;font-size:15px;font-weight:600;cursor:pointer}  
        .game-container{padding:20px;text-align:center}  
        .timer-display{font-size:72px;font-weight:800;font-variant-numeric:tabular-nums;margin:40px 0;font-family:'Courier New',monospace;text-shadow:0 0 30px rgba(99,102,241,0.5)}  
        .game-controls{display:flex;gap:15px;justify-content:center;margin-top:30px}  
        .control-btn{padding:16px 32px;border-radius:16px;border:none;font-size:16px;font-weight:600;cursor:pointer}  
        .control-btn.primary{background:linear-gradient(135deg,var(--primary),var(--secondary));color:white}  
        .control-btn.secondary{background:var(--surface-light);color:var(--text)}  
        .toast{position:fixed;bottom:100px;left:50%;transform:translateX(-50%) translateY(100px);background:var(--surface);color:white;padding:16px 24px;border-radius:12px;font-size:14px;font-weight:500;box-shadow:0 10px 40px rgba(0,0,0,0.3);opacity:0;transition:all 0.3s;z-index:10002;border:1px solid rgba(255,255,255,0.1)}  
        .toast.show{transform:translateX(-50%) translateY(0);opacity:1}  
        .install-prompt{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,0.95);z-index:10000;display:none;align-items:center;justify-content:center;padding:20px;backdrop-filter:blur(10px)}  
        .install-content{background:var(--surface);border-radius:24px;padding:40px 30px;text-align:center;max-width:350px;border:1px solid rgba(255,255,255,0.1);animation:slideUp 0.5s ease}  
        @keyframes slideUp{from{transform:translateY(50px);opacity:0}to{transform:translateY(0);opacity:1}}  
        .install-icon{width:80px;height:80px;background:linear-gradient(135deg,var(--primary),var(--secondary));border-radius:20px;margin:0 auto 20px;display:flex;align-items:center;justify-content:center;font-size:40px;box-shadow:0 10px 40px rgba(99,102,241,0.3)}  
        .install-btn{background:linear-gradient(135deg,var(--primary),var(--secondary));color:white;border:none;padding:16px 32px;border-radius:12px;font-size:16px;font-weight:600;cursor:pointer;width:100%;margin-top:20px}  
        .skip-install{color:var(--text-muted);margin-top:15px;font-size:14px;cursor:pointer}  
    </style>  
</head>  
<body>  
    <div class="install-prompt" id="installPrompt">  
        <div class="install-content">  
            <div class="install-icon">🧠</div>  
            <h2>MindForge AI</h2>  
            <p style="color:var(--text-muted);margin:10px 0 20px;line-height:1.5">Daha iyi bir deneyim için uygulamayı ana ekranınıza ekleyin!</p>  
            <div style="background:var(--surface-light);padding:15px;border-radius:12px;margin-bottom:20px;text-align:left;font-size:14px">  
                <div style="margin-bottom:8px">📱 <strong>iOS:</strong></div>  
                <div style="color:var(--text-muted)">Safari'de paylaş butonuna tıklayın → "Ana Ekrana Ekle"</div>  
            </div>  
            <button class="install-btn" onclick="dismissInstall()">Anladım</button>  
            <div class="skip-install" onclick="dismissInstall()">Şimdi Değil</div>  
        </div>  
    </div>  
  
    <div class="app-container">  
        <div class="screen active" id="homeScreen">  
            <div class="header">  
                <div class="header-top">  
                    <div class="logo">MindForge</div>  
                    <div class="streak"><span>🔥</span><span id="streakCount">12</span></div>  
                </div>  
            </div>  
            <div class="stats-container">  
                <div class="stat-card"><div class="stat-icon">💪</div><div class="stat-label">Fitness</div><div class="stat-value" id="fitnessStat">85%</div></div>  
                <div class="stat-card"><div class="stat-icon">🗣️</div><div class="stat-label">Diksiyon</div><div class="stat-value" id="voiceStat">62%</div></div>  
                <div class="stat-card"><div class="stat-icon">⚡</div><div class="stat-label">Hızlı Düşünme</div><div class="stat-value" id="mindStat">45%</div></div>  
                <div class="stat-card"><div class="stat-icon">🧩</div><div class="stat-label">Pratik Zeka</div><div class="stat-value" id="logicStat">70%</div></div>  
            </div>  
            <div class="section-title">Modüller<span class="view-all">Tümü</span></div>  
            <div class="modules-grid">  
                <div class="module-card fitness" onclick="openModule('fitness')"><div class="module-icon">💪</div><div class="module-title">FitForge</div><div class="module-desc">AI destekli vücut geliştirme</div><div class="module-progress"><div class="module-progress-bar" style="width:85%"></div></div></div>  
                <div class="module-card voice" onclick="openModule('voice')"><div class="module-icon">🗣️</div><div class="module-title">VoiceForge</div><div class="module-desc">Diksiyon ve konuşma</div><div class="module-progress"><div class="module-progress-bar" style="width:62%"></div></div></div>  
                <div class="module-card mind" onclick="openModule('mind')"><div class="module-icon">⚡</div><div class="module-title">MindForge</div><div class="module-desc">Hızlı düşünme oyunları</div><div class="module-progress"><div class="module-progress-bar" style="width:45%"></div></div></div>  
                <div class="module-card logic" onclick="openModule('logic')"><div class="module-icon">🧩</div><div class="module-title">LogicForge</div><div class="module-desc">Pratik zeka soruları</div><div class="module-progress"><div class="module-progress-bar" style="width:70%"></div></div></div>  
            </div>  
            <div class="section-title">Günlük Görevler<span class="view-all">Takvim</span></div>  
            <div class="challenges-container" id="challengesList"></div>  
        </div>  
  
        <div class="screen" id="fitnessScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">FitForge</div><div class="screen-subtitle">Bugünkü antrenman</div></div>  
            <div class="exercise-list" id="fitnessList"></div>  
        </div>  
  
        <div class="screen" id="voiceScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">VoiceForge</div><div class="screen-subtitle">Diksiyon egzersizleri</div></div>  
            <div class="exercise-list" id="voiceList"></div>  
        </div>  
  
        <div class="screen" id="mindScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">MindForge</div><div class="screen-subtitle">Refleks oyunu</div></div>  
            <div class="game-container">  
                <div class="timer-display" id="reactionTimer">00:00</div>  
                <div style="color:var(--text-muted);margin-bottom:30px">Yeşil ışık yanınca hemen dokun!</div>  
                <div class="game-controls">  
                    <button class="control-btn primary" onclick="startReactionGame()">Başla</button>  
                    <button class="control-btn secondary" onclick="showStats()">Skorlar</button>  
                </div>  
                <div id="gameResult" style="margin-top:30px;font-size:18px;font-weight:600"></div>  
            </div>  
        </div>  
  
        <div class="screen" id="logicScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">LogicForge</div><div class="screen-subtitle">Bulmacalar</div></div>  
            <div class="exercise-list" id="logicList"></div>  
        </div>  
  
        <nav class="bottom-nav">  
            <button class="nav-item active" onclick="goHome()"><span class="nav-icon">🏠</span><span class="nav-label">Ana Sayfa</span></button>  
            <button class="nav-item" onclick="showToast('İlerleme raporu hazırlanıyor...')"><span class="nav-icon">📊</span><span class="nav-label">İlerleme</span></button>  
            <button class="nav-item" onclick="showToast('AI Koç: Bugün ne çalışalım?')"><span class="nav-icon">🤖</span><span class="nav-label">AI Koç</span></button>  
            <button class="nav-item" onclick="showToast('Profil yakında!')"><span class="nav-icon">👤</span><span class="nav-label">Profil</span></button>  
        </nav>  
    </div>  
  
    <div class="toast" id="toast"></div>  
  
    <script>  
        const defaultData={  
            challenges:[  
                {id:1,icon:'💪',title:'20 Push-up',module:'fitness',duration:'5 dk',color:'#f5576c',completed:false},  
                {id:2,icon:'🗣️',title:'Diksiyon',module:'voice',duration:'10 dk',color:'#4facfe',completed:false},  
                {id:3,icon:'⚡',title:'Refleks Testi',module:'mind',duration:'3 dk',color:'#43e97b',completed:false},  
                {id:4,icon:'🧩',title:'Bulmaca',module:'logic',duration:'15 dk',color:'#fa709a',completed:false}  
            ],  
            fitness:[  
                {id:'f1',name:'Isınma - Jumping Jacks',duration:'3 dk',difficulty:'easy',completed:false},  
                {id:'f2',name:'Push-up (3x12)',duration:'10 dk',difficulty:'medium',completed:false},  
                {id:'f3',name:'Squat (3x15)',duration:'10 dk',difficulty:'medium',completed:false},  
                {id:'f4',name:'Plank (3x45sn)',duration:'5 dk',difficulty:'hard',completed:false}  
            ],  
            voice:[  
                {id:'v1',name:'Diyafram Nefesi',duration:'3 dk',difficulty:'easy',completed:false},  
                {id:'v2',name:'"R" Sesi Pratiği',duration:'5 dk',difficulty:'medium',completed:false},  
                {id:'v3',name:'Hızlı Konuşma',duration:'5 dk',difficulty:'medium',completed:false}  
            ],  
            logic:[  
                {id:'l1',name:'Sudoku Kolay',duration:'10 dk',difficulty:'easy',completed:false},  
                {id:'l2',name:'Mantık Sorusu',duration:'5 dk',difficulty:'medium',completed:false},  
                {id:'l3',name:'Sayı Dizisi',duration:'5 dk',difficulty:'medium',completed:false}  
            ]  
        };  
  
        function showToast(msg){  
            const t=document.getElementById('toast');  
            t.textContent=msg;  
            t.classList.add('show');  
            setTimeout(()=>t.classList.remove('show'),3000);  
        }  
  
        function dismissInstall(){  
            document.getElementById('installPrompt').style.display='none';  
            localStorage.setItem('installPromptDismissed','true');  
        }  
  
        function goHome(){  
            document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));  
            document.getElementById('homeScreen').classList.add('active');  
            document.querySelectorAll('.nav-item').forEach((item,i)=>item.classList.toggle('active',i===0));  
        }  
  
        function openModule(module){  
            document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));  
            document.getElementById(module+'Screen').classList.add('active');  
            if(module==='fitness')renderList('fitnessList',defaultData.fitness,'fitness');  
            else if(module==='voice')renderList('voiceList',defaultData.voice,'voice');  
            else if(module==='logic')renderList('logicList',defaultData.logic,'logic');  
        }  
  
        function renderList(containerId,items,type){  
            const container=document.getElementById(containerId);  
            container.innerHTML=items.map(item=>`  
                <div class="exercise-card">  
                    <div class="exercise-header">  
                        <div>  
                            <div class="exercise-name">${item.name}</div>  
                            <div class="exercise-duration">⏱️ ${item.duration}</div>  
                        </div>  
                        <span class="difficulty ${item.difficulty}">${item.difficulty}</span>  
                    </div>  
                    <button class="exercise-btn" onclick="toggleComplete('${type}','${item.id}',this)">  
                        ${item.completed?'✓ Tamamlandı':'Başla'}  
                    </button>  
                </div>  
            `).join('');  
        }  
  
        function toggleComplete(type,id,btn){  
            const item=defaultData[type].find(i=>i.id===id);  
            if(item){  
                item.completed=!item.completed;  
                btn.textContent=item.completed?'✓ Tamamlandı':'Başla';  
                showToast(item.completed?'Tebrikler!':'Sıfırlandı');  
                const statKey=type==='fitness'?'fitnessStat':type==='voice'?'voiceStat':type==='logic'?'logicStat':null;  
                if(statKey&&item.completed){  
                    const current=parseInt(document.getElementById(statKey).textContent);  
                    document.getElementById(statKey).textContent=Math.min(100,current+2)+'%';  
                }  
            }  
        }  
  
        function renderChallenges(){  
            const container=document.getElementById('challengesList');  
            container.innerHTML=defaultData.challenges.map(c=>`  
                <div class="challenge-card" onclick="openModule('${c.module}')">  
                    <div class="challenge-icon" style="background:${c.color}20">${c.icon}</div>  
                    <div class="challenge-info">  
                        <div class="challenge-title">${c.title}</div>  
                        <div class="challenge-meta">${c.duration}</div>  
                    </div>  
                    <button class="challenge-btn" onclick="event.stopPropagation();completeChallenge(${c.id},this)">  
                        ${c.completed?'✓':'▶'}  
                    </button>  
                </div>  
            `).join('');  
        }  
  
transition:all 0.3s;min-height:160px;display:flex;flex-direction:column}  
        .module-icon{width:50px;height:50px;border-radius:14px;display:flex;align-items:center;justify-content:center;font-size:24px;margin-bottom:12px}  
        .module-card.fitness .module-icon{background:linear-gradient(135deg,#f093fb 0%,#f5576c 100%)}  
        .module-card.voice .module-icon{background:linear-gradient(135deg,#4facfe 0%,#00f2fe 100%)}  
        .module-card.mind .module-icon{background:linear-gradient(135deg,#43e97b 0%,#38f9d7 100%)}  
        .module-card.logic .module-icon{background:linear-gradient(135deg,#fa709a 0%,#fee140 100%)}  
        .module-title{font-size:16px;font-weight:700;margin-bottom:4px}  
        .module-desc{font-size:12px;color:var(--text-muted);line-height:1.4;flex:1}  
        .module-progress{margin-top:12px;height:4px;background:rgba(255,255,255,0.1);border-radius:2px;overflow:hidden}  
        .module-progress-bar{height:100%;background:linear-gradient(90deg,var(--primary),var(--secondary));border-radius:2px;transition:width 0.5s ease}  
        .challenges-container{padding:0 20px;margin-bottom:30px}  
        .challenge-card{background:var(--surface);border-radius:16px;padding:16px;margin-bottom:12px;border:1px solid rgba(255,255,255,0.05);display:flex;align-items:center;gap:15px;cursor:pointer}  
        .challenge-icon{width:50px;height:50px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:24px;flex-shrink:0}  
        .challenge-info{flex:1}  
        .challenge-title{font-size:15px;font-weight:600;margin-bottom:4px}  
        .challenge-meta{font-size:12px;color:var(--text-muted)}  
        .challenge-btn{width:36px;height:36px;border-radius:50%;border:2px solid var(--primary);background:transparent;color:var(--primary);display:flex;align-items:center;justify-content:center;font-size:16px;cursor:pointer}  
        .bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:430px;background:rgba(26,26,46,0.95);backdrop-filter:blur(20px);border-top:1px solid rgba(255,255,255,0.05);display:flex;justify-content:space-around;padding:12px 0 30px;z-index:1000}  
        .nav-item{display:flex;flex-direction:column;align-items:center;gap:4px;padding:8px 16px;cursor:pointer;border:none;background:none;color:var(--text-muted)}  
        .nav-item.active{color:var(--primary)}  
        .nav-icon{font-size:24px}  
        .nav-label{font-size:11px;font-weight:500}  
        .screen{display:none;min-height:100vh;padding-bottom:100px}  
        .screen.active{display:block;animation:fadeIn 0.3s ease}  
        @keyframes fadeIn{from{opacity:0;transform:translateX(20px)}to{opacity:1;transform:translateX(0)}}  
        .screen-header{padding:60px 20px 20px;background:var(--surface);border-radius:0 0 30px 30px;margin-bottom:20px}  
        .back-btn{background:none;border:none;color:var(--text);font-size:24px;cursor:pointer;margin-bottom:20px;padding:0}  
        .screen-title{font-size:28px;font-weight:800;margin-bottom:8px}  
        .screen-subtitle{color:var(--text-muted);font-size:16px}  
        .exercise-list{padding:0 20px}  
        .exercise-card{background:var(--surface);border-radius:16px;padding:20px;margin-bottom:12px;border:1px solid rgba(255,255,255,0.05)}  
        .exercise-header{display:flex;justify-content:space-between;align-items:start;margin-bottom:15px}  
        .exercise-name{font-size:18px;font-weight:700;margin-bottom:4px}  
        .exercise-duration{font-size:13px;color:var(--text-muted)}  
        .difficulty{padding:4px 10px;border-radius:20px;font-size:11px;font-weight:600;text-transform:uppercase}  
        .difficulty.easy{background:rgba(16,185,129,0.2);color:var(--success)}  
        .difficulty.medium{background:rgba(245,158,11,0.2);color:var(--warning)}  
        .difficulty.hard{background:rgba(239,68,68,0.2);color:var(--danger)}  
        .exercise-btn{width:100%;padding:14px;border-radius:12px;border:none;background:linear-gradient(135deg,var(--primary),var(--secondary));color:white;font-size:15px;font-weight:600;cursor:pointer}  
        .game-container{padding:20px;text-align:center}  
        .timer-display{font-size:72px;font-weight:800;font-variant-numeric:tabular-nums;margin:40px 0;font-family:'Courier New',monospace;text-shadow:0 0 30px rgba(99,102,241,0.5)}  
        .game-controls{display:flex;gap:15px;justify-content:center;margin-top:30px}  
        .control-btn{padding:16px 32px;border-radius:16px;border:none;font-size:16px;font-weight:600;cursor:pointer}  
        .control-btn.primary{background:linear-gradient(135deg,var(--primary),var(--secondary));color:white}  
        .control-btn.secondary{background:var(--surface-light);color:var(--text)}  
        .toast{position:fixed;bottom:100px;left:50%;transform:translateX(-50%) translateY(100px);background:var(--surface);color:white;padding:16px 24px;border-radius:12px;font-size:14px;font-weight:500;box-shadow:0 10px 40px rgba(0,0,0,0.3);opacity:0;transition:all 0.3s;z-index:10002;border:1px solid rgba(255,255,255,0.1)}  
        .toast.show{transform:translateX(-50%) translateY(0);opacity:1}  
        .install-prompt{position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,0.95);z-index:10000;display:none;align-items:center;justify-content:center;padding:20px;backdrop-filter:blur(10px)}  
        .install-content{background:var(--surface);border-radius:24px;padding:40px 30px;text-align:center;max-width:350px;border:1px solid rgba(255,255,255,0.1);animation:slideUp 0.5s ease}  
        @keyframes slideUp{from{transform:translateY(50px);opacity:0}to{transform:translateY(0);opacity:1}}  
        .install-icon{width:80px;height:80px;background:linear-gradient(135deg,var(--primary),var(--secondary));border-radius:20px;margin:0 auto 20px;display:flex;align-items:center;justify-content:center;font-size:40px;box-shadow:0 10px 40px rgba(99,102,241,0.3)}  
        .install-btn{background:linear-gradient(135deg,var(--primary),var(--secondary));color:white;border:none;padding:16px 32px;border-radius:12px;font-size:16px;font-weight:600;cursor:pointer;width:100%;margin-top:20px}  
        .skip-install{color:var(--text-muted);margin-top:15px;font-size:14px;cursor:pointer}  
    </style>  
</head>  
<body>  
    <div class="install-prompt" id="installPrompt">  
        <div class="install-content">  
            <div class="install-icon">🧠</div>  
            <h2>MindForge AI</h2>  
            <p style="color:var(--text-muted);margin:10px 0 20px;line-height:1.5">Daha iyi bir deneyim için uygulamayı ana ekranınıza ekleyin!</p>  
            <div style="background:var(--surface-light);padding:15px;border-radius:12px;margin-bottom:20px;text-align:left;font-size:14px">  
                <div style="margin-bottom:8px">📱 <strong>iOS:</strong></div>  
                <div style="color:var(--text-muted)">Safari'de paylaş butonuna tıklayın → "Ana Ekrana Ekle"</div>  
            </div>  
            <button class="install-btn" onclick="dismissInstall()">Anladım</button>  
            <div class="skip-install" onclick="dismissInstall()">Şimdi Değil</div>  
        </div>  
    </div>  
  
    <div class="app-container">  
        <div class="screen active" id="homeScreen">  
            <div class="header">  
                <div class="header-top">  
                    <div class="logo">MindForge</div>  
                    <div class="streak"><span>🔥</span><span id="streakCount">12</span></div>  
                </div>  
            </div>  
            <div class="stats-container">  
                <div class="stat-card"><div class="stat-icon">💪</div><div class="stat-label">Fitness</div><div class="stat-value" id="fitnessStat">85%</div></div>  
                <div class="stat-card"><div class="stat-icon">🗣️</div><div class="stat-label">Diksiyon</div><div class="stat-value" id="voiceStat">62%</div></div>  
                <div class="stat-card"><div class="stat-icon">⚡</div><div class="stat-label">Hızlı Düşünme</div><div class="stat-value" id="mindStat">45%</div></div>  
                <div class="stat-card"><div class="stat-icon">🧩</div><div class="stat-label">Pratik Zeka</div><div class="stat-value" id="logicStat">70%</div></div>  
            </div>  
            <div class="section-title">Modüller<span class="view-all">Tümü</span></div>  
            <div class="modules-grid">  
                <div class="module-card fitness" onclick="openModule('fitness')"><div class="module-icon">💪</div><div class="module-title">FitForge</div><div class="module-desc">AI destekli vücut geliştirme</div><div class="module-progress"><div class="module-progress-bar" style="width:85%"></div></div></div>  
                <div class="module-card voice" onclick="openModule('voice')"><div class="module-icon">🗣️</div><div class="module-title">VoiceForge</div><div class="module-desc">Diksiyon ve konuşma</div><div class="module-progress"><div class="module-progress-bar" style="width:62%"></div></div></div>  
                <div class="module-card mind" onclick="openModule('mind')"><div class="module-icon">⚡</div><div class="module-title">MindForge</div><div class="module-desc">Hızlı düşünme oyunları</div><div class="module-progress"><div class="module-progress-bar" style="width:45%"></div></div></div>  
                <div class="module-card logic" onclick="openModule('logic')"><div class="module-icon">🧩</div><div class="module-title">LogicForge</div><div class="module-desc">Pratik zeka soruları</div><div class="module-progress"><div class="module-progress-bar" style="width:70%"></div></div></div>  
            </div>  
            <div class="section-title">Günlük Görevler<span class="view-all">Takvim</span></div>  
            <div class="challenges-container" id="challengesList"></div>  
        </div>  
  
        <div class="screen" id="fitnessScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">FitForge</div><div class="screen-subtitle">Bugünkü antrenman</div></div>  
            <div class="exercise-list" id="fitnessList"></div>  
        </div>  
  
        <div class="screen" id="voiceScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">VoiceForge</div><div class="screen-subtitle">Diksiyon egzersizleri</div></div>  
            <div class="exercise-list" id="voiceList"></div>  
        </div>  
  
        <div class="screen" id="mindScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">MindForge</div><div class="screen-subtitle">Refleks oyunu</div></div>  
            <div class="game-container">  
                <div class="timer-display" id="reactionTimer">00:00</div>  
                <div style="color:var(--text-muted);margin-bottom:30px">Yeşil ışık yanınca hemen dokun!</div>  
                <div class="game-controls">  
                    <button class="control-btn primary" onclick="startReactionGame()">Başla</button>  
                    <button class="control-btn secondary" onclick="showStats()">Skorlar</button>  
                </div>  
                <div id="gameResult" style="margin-top:30px;font-size:18px;font-weight:600"></div>  
            </div>  
        </div>  
  
        <div class="screen" id="logicScreen">  
            <div class="screen-header"><button class="back-btn" onclick="goHome()">←</button><div class="screen-title">LogicForge</div><div class="screen-subtitle">Bulmacalar</div></div>  
            <div class="exercise-list" id="logicList"></div>  
        </div>  
  
        <nav class="bottom-nav">  
            <button class="nav-item active" onclick="goHome()"><span class="nav-icon">🏠</span><span class="nav-label">Ana Sayfa</span></button>  
            <button class="nav-item" onclick="showToast('İlerleme raporu hazırlanıyor...')"><span class="nav-icon">📊</span><span class="nav-label">İlerleme</span></button>  
            <button class="nav-item" onclick="showToast('AI Koç: Bugün ne çalışalım?')"><span class="nav-icon">🤖</span><span class="nav-label">AI Koç</span></button>  
            <button class="nav-item" onclick="showToast('Profil yakında!')"><span class="nav-icon">👤</span><span class="nav-label">Profil</span></button>  
        </nav>  
    </div>  
  
    <div class="toast" id="toast"></div>  
  
    <script>  
        const defaultData={  
            challenges:[  
                {id:1,icon:'💪',title:'20 Push-up',module:'fitness',duration:'5 dk',color:'#f5576c',completed:false},  
                {id:2,icon:'🗣️',title:'Diksiyon',module:'voice',duration:'10 dk',color:'#4facfe',completed:false},  
                {id:3,icon:'⚡',title:'Refleks Testi',module:'mind',duration:'3 dk',color:'#43e97b',completed:false},  
                {id:4,icon:'🧩',title:'Bulmaca',module:'logic',duration:'15 dk',color:'#fa709a',completed:false}  
            ],  
            fitness:[  
                {id:'f1',name:'Isınma - Jumping Jacks',duration:'3 dk',difficulty:'easy',completed:false},  
                {id:'f2',name:'Push-up (3x12)',duration:'10 dk',difficulty:'medium',completed:false},  
                {id:'f3',name:'Squat (3x15)',duration:'10 dk',difficulty:'medium',completed:false},  
                {id:'f4',name:'Plank (3x45sn)',duration:'5 dk',difficulty:'hard',completed:false}  
            ],  
            voice:[  
                {id:'v1',name:'Diyafram Nefesi',duration:'3 dk',difficulty:'easy',completed:false},  
                {id:'v2',name:'"R" Sesi Pratiği',duration:'5 dk',difficulty:'medium',completed:false},  
                {id:'v3',name:'Hızlı Konuşma',duration:'5 dk',difficulty:'medium',completed:false}  
            ],  
            logic:[  
                {id:'l1',name:'Sudoku Kolay',duration:'10 dk',difficulty:'easy',completed:false},  
                {id:'l2',name:'Mantık Sorusu',duration:'5 dk',difficulty:'medium',completed:false},  
                {id:'l3',name:'Sayı Dizisi',duration:'5 dk',difficulty:'medium',completed:false}  
            ]  
        };  
  
        function showToast(msg){  
            const t=document.getElementById('toast');  
            t.textContent=msg;  
            t.classList.add('show');  
            setTimeout(()=>t.classList.remove('show'),3000);  
        }  
  
        function dismissInstall(){  
            document.getElementById('installPrompt').style.display='none';  
            localStorage.setItem('installPromptDismissed','true');  
        }  
  
        function goHome(){  
            document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));  
            document.getElementById('homeScreen').classList.add('active');  
            document.querySelectorAll('.nav-item').forEach((item,i)=>item.classList.toggle('active',i===0));  
        }  
  
        function openModule(module){  
            document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));  
            document.getElementById(module+'Screen').classList.add('active');  
            if(module==='fitness')renderList('fitnessList',defaultData.fitness,'fitness');  
            else if(module==='voice')renderList('voiceList',defaultData.voice,'voice');  
            else if(module==='logic')renderList('logicList',defaultData.logic,'logic');  
        }  
  
        function renderList(containerId,items,type){  
            const container=document.getElementById(containerId);  
            container.innerHTML=items.map(item=>`  
                <div class="exercise-card">  
                    <div class="exercise-header">  
                        <div>  
                            <div class="exercise-name">${item.name}</div>  
                            <div class="exercise-duration">⏱️ ${item.duration}</div>  
                        </div>  
                        <span class="difficulty ${item.difficulty}">${item.difficulty}</span>  
                    </div>  
                    <button class="exercise-btn" onclick="toggleComplete('${type}','${item.id}',this)">  
                        ${item.completed?'✓ Tamamlandı':'Başla'}  
                    </button>  
                </div>  
            `).join('');  
        }  
  
        function toggleComplete(type,id,btn){  
            const item=defaultData[type].find(i=>i.id===id);  
            if(item){  
                item.completed=!item.completed;  
                btn.textContent=item.completed?'✓ Tamamlandı':'Başla';  
                showToast(item.completed?'Tebrikler!':'Sıfırlandı');  
                const statKey=type==='fitness'?'fitnessStat':type==='voice'?'voiceStat':type==='logic'?'logicStat':null;  
                if(statKey&&item.completed){  
                    const current=parseInt(document.getElementById(statKey).textContent);  
                    document.getElementById(statKey).textContent=Math.min(100,current+2)+'%';  
                }  
            }  
        }  
  
        function renderChallenges(){  
            const container=document.getElementById('challengesList');  
            container.innerHTML=defaultData.challenges.map(c=>`  
                <div class="challenge-card" onclick="openModule('${c.module}')">  
                    <div class="challenge-icon" style="background:${c.color}20">${c.icon}</div>  
                    <div class="challenge-info">  
                        <div class="challenge-title">${c.title}</div>  
                        <div class="challenge-meta">${c.duration}</div>  
                    </div>  
                    <button class="challenge-btn" onclick="event.stopPropagation();completeChallenge(${c.id},this)">  
                        ${c.completed?'✓':'▶'}  
                    </button>  
                </div>  
            `).join('');  
        }  
  
        function completeChallenge(id,btn){  
            const c=defaultData.challenges.find(x=>x.id===id);  
            if(c){  
                c.completed=!c.completed;  
                btn.innerHTML=c.completed?'✓':'▶';  
                showToast(c.completed?'Görev tamamlandı!':'Sıfırlandı');  
            }  
        }  
  
        let reactionStartTime,reactionTimeout,isWaiting=false;  
  
        function startReactionGame(){  
            const timer=document.getElementById('reactionTimer');  
            const result=document.getElementById('gameResult');  
            const btn=document.querySelector('.control-btn.primary');  
  
            if(isWaiting){  
                clearTimeout(reactionTimeout);  
                timer.textContent='Erken!';  
                timer.style.color='#ef4444';  
                result.textContent='Beklemeden bastınız!';  
                isWaiting=false;  
                btn.textContent='Tekrar Dene';  
                return;  
            }  
  
            if(btn.textContent==='Başla'||btn.textContent==='Tekrar Dene'){  
                timer.textContent='Bekle...';  
                timer.style.color='#f59e0b';  
                result.textContent='Yeşili bekle!';  
                btn.textContent='Bekliyor...';  
                isWaiting=true;  
                reactionTimeout=setTimeout(()=>{  
                    timer.textContent='ŞİMDİ!';  
                    timer.style.color='#10b981';  
                    reactionStartTime=Date.now();  
                    isWaiting=false;  
                    btn.textContent='Dokun!';  
                },Math.random()*3000+2000);  
            }else{  
                const reactionTime=Date.now()-reactionStartTime;  
                timer.textContent=reactionTime+'ms';  
                let msg=reactionTime<200?'İnanılmaz! ⚡':reactionTime<300?'Çok iyi! 🎯':reactionTime<400?'İyi! 👍':'Daha hızlı! 💪';  
                result.textContent=msg;  
                btn.textContent='Tekrar Dene';  
                const current=parseInt(document.getElementById('mindStat').textContent);  
                document.getElementById('mindStat').textContent=Math.min(100,current+1)+'%';  
            }  
        }  
  
        function showStats(){  
            showToast('Skor kaydedildi!');  
        }  
  
        document.addEventListener('DOMContentLoaded',()=>{  
            renderChallenges();  
            if(!localStorage.getItem('installPromptDismissed')&&!window.matchMedia('(display-mode:standalone)').matches){  
                setTimeout(()=>document.getElementById('installPrompt').style.display='flex',2000);  
            }  
        });  
    </script>  
</body>  
</html>  
