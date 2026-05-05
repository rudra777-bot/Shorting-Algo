:root {
    --bg: #030303;
    --side-bg: #070707;
    --accent: #00f2ff;
    --error: #ff007a;
    --success: #39ff14;
    --border: #1a1a1a;
    --glass: rgba(255, 255, 255, 0.02);
}

* { box-sizing: border-box; margin: 0; padding: 0; }
body {
    font-family: 'Inter', sans-serif;
    background: var(--bg); color: #fff; overflow: hidden;
}

.app-canvas { display: flex; height: 100vh; }

.control-tower {
    width: 400px; background: var(--side-bg); border-right: 1px solid var(--border);
    padding: 30px; display: flex; flex-direction: column; gap: 20px;
}

.logo { font-size: 1.8rem; font-weight: 800; letter-spacing: -1px; }
.logo span { color: var(--accent); }
.engine-tag { font-size: 0.6rem; color: #555; letter-spacing: 2px; text-transform: uppercase; margin-top: -5px; }

.analytics-hub { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
.a-card, .a-card-long { background: var(--glass); padding: 15px; border-radius: 12px; border: 1px solid var(--border); }
.a-card-long { grid-column: span 2; }
.a-label { font-size: 0.6rem; color: #555; display: block; margin-bottom: 5px; font-weight: 800; }
.a-val { font-size: 1.4rem; font-family: 'JetBrains Mono'; font-weight: 600; color: #fff; }
.a-val-neon { color: var(--accent); font-family: 'JetBrains Mono'; font-size: 1.1rem; }

.section-title { font-size: 0.7rem; color: #444; font-weight: 800; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 1px; }

.nav-btn {
    width: 100%; padding: 12px; background: transparent; border: 1px solid var(--border);
    color: #666; border-radius: 10px; cursor: pointer; text-align: left; font-weight: 600; transition: 0.3s; margin-bottom: 8px;
}
.nav-btn.active, .nav-btn:hover { background: #111; color: var(--accent); border-color: var(--accent); }

.vault-content { background: #000; padding: 15px; border-radius: 10px; border: 1px solid var(--border); height: 120px; }
#logic-list { list-style: none; font-size: 0.75rem; color: #888; line-height: 1.6; }

.pointer-legend { background: var(--glass); padding: 15px; border-radius: 12px; border: 1px solid var(--border); margin-top: auto; }
.p-info { font-size: 0.7rem; color: #777; margin-bottom: 5px; }
.p-info strong { color: var(--accent); }

.workspace { flex: 1; padding: 40px; display: flex; flex-direction: column; background: radial-gradient(circle at top right, #0a0a0a, #030303); }
.header-bar { display: flex; justify-content: space-between; align-items: center; margin-bottom: 40px; }

.narrator-box { background: #080808; padding: 15px 30px; border-radius: 15px; border: 1px solid var(--border); min-width: 500px; }
#narrator-title { font-size: 0.65rem; color: var(--accent); font-weight: 800; display: block; margin-bottom: 4px; }
#narrator-txt { color: #eee; font-size: 0.9rem; font-family: 'JetBrains Mono'; line-height: 1.4; }

.p-btn { padding: 12px 25px; border-radius: 10px; border: none; font-weight: 700; cursor: pointer; transition: 0.3s; font-size: 0.85rem; }
.p-reset { background: var(--border); color: #fff; margin-right: 10px; }
.p-start { background: var(--accent); color: #000; }

.stage-area { display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 40px; flex: 1; }

#bar-plot { display: flex; align-items: flex-end; height: 150px; gap: 30px; }
.bar-unit { width: 80px; background: var(--accent); border-radius: 6px; opacity: 0.15; transition: 0.4s; }

#box-grid { display: flex; gap: 30px; }
.box-unit {
    width: 120px; height: 130px; background: rgba(255,255,255,0.02); 
    border: 1px solid var(--border); border-radius: 20px;
    display: flex; flex-direction: column; align-items: center; justify-content: center;
    position: relative; transition: 0.4s;
}
.unit-ptr { font-size: 10px; font-weight: 800; color: var(--accent); margin-bottom: 5px; }
.unit-val { font-size: 2.8rem; font-weight: 800; font-family: 'JetBrains Mono'; }

.math-op { position: absolute; right: -35px; font-size: 2rem; color: var(--error); font-weight: 800; opacity: 0; }
.op-active { opacity: 1; transform: scale(1.1); }

.box-active { border-color: var(--error); background: rgba(255, 0, 122, 0.05); transform: translateY(-8px); }
.box-pivot { border-color: #fff; background: rgba(255, 255, 255, 0.1); }
.box-done { border-color: var(--success); background: rgba(57, 255, 20, 0.05); }
