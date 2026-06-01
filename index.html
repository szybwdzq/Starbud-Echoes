<!doctype html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Starbud Echoes | Mario + Metroidvania Demo</title>
  <style>

:root {
  color-scheme: dark;
  --bg: #070416;
  --bg-2: #120b2f;
  --panel: rgba(255, 255, 255, 0.10);
  --panel-strong: rgba(255, 255, 255, 0.16);
  --line: rgba(255, 255, 255, 0.18);
  --text: #fff7d6;
  --muted: #c8c3ff;
  --accent: #52ffd0;
  --accent-2: #ff7be5;
  --gold: #ffe75d;
  --blue: #80a7ff;
  --danger: #ff5f6d;
  --shadow: 0 28px 90px rgba(0,0,0,.46);
}

* { box-sizing: border-box; }

html {
  min-height: 100%;
  background:
    radial-gradient(circle at 12% 8%, rgba(128,167,255,.35), transparent 30%),
    radial-gradient(circle at 86% 12%, rgba(255,123,229,.26), transparent 26%),
    radial-gradient(circle at 50% 105%, rgba(82,255,208,.18), transparent 32%),
    linear-gradient(145deg, #08041a 0%, #120b2f 48%, #070416 100%);
}

body {
  margin: 0;
  min-height: 100%;
  color: var(--text);
  font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
  overflow-x: hidden;
}

body::before {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  background-image:
    linear-gradient(rgba(255,255,255,.035) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,.035) 1px, transparent 1px);
  background-size: 48px 48px;
  mask-image: radial-gradient(circle at center, black, transparent 78%);
}

.shell {
  width: min(1180px, calc(100vw - 32px));
  margin: 0 auto;
  padding: 28px 0 38px;
}

.hero {
  display: grid;
  grid-template-columns: minmax(0, 1.25fr) minmax(290px, .75fr);
  gap: 22px;
  align-items: stretch;
  margin-bottom: 18px;
}

.hero-card,
.command-card,
.notes,
.canvas-wrap {
  border: 1px solid var(--line);
  background: linear-gradient(145deg, rgba(255,255,255,.12), rgba(255,255,255,.045));
  box-shadow: var(--shadow);
  backdrop-filter: blur(18px);
}

.hero-card {
  position: relative;
  overflow: hidden;
  border-radius: 30px;
  padding: clamp(22px, 4vw, 34px);
}

.hero-card::after {
  content: "";
  position: absolute;
  width: 260px;
  height: 260px;
  right: -90px;
  top: -90px;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(82,255,208,.34), transparent 68%);
  filter: blur(2px);
}

.eyebrow {
  position: relative;
  z-index: 1;
  display: inline-flex;
  align-items: center;
  gap: 8px;
  margin: 0 0 12px;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: var(--accent);
  font-size: 12px;
  font-weight: 900;
}

.eyebrow::before {
  content: "";
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--accent);
  box-shadow: 0 0 22px var(--accent);
}

h1 {
  position: relative;
  z-index: 1;
  margin: 0;
  font-size: clamp(44px, 8vw, 86px);
  line-height: .88;
  letter-spacing: -0.06em;
  text-shadow: 0 12px 32px rgba(0,0,0,.48);
}

.sub {
  position: relative;
  z-index: 1;
  margin: 18px 0 0;
  color: var(--muted);
  font-size: 16px;
  max-width: 760px;
  line-height: 1.75;
}

.meta-row {
  position: relative;
  z-index: 1;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 20px;
}

.meta-row span,
.controls span {
  border: 1px solid rgba(255,255,255,.16);
  background: rgba(255,255,255,.08);
  border-radius: 999px;
  padding: 8px 11px;
  font-size: 13px;
  color: #f7f1ff;
  box-shadow: inset 0 0 20px rgba(255,255,255,.04);
}

.command-card {
  border-radius: 30px;
  padding: 18px;
  display: grid;
  align-content: space-between;
  gap: 16px;
}

.status-bar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  border: 1px solid rgba(255,255,255,.12);
  border-radius: 22px;
  padding: 12px;
  background: rgba(0,0,0,.16);
}

.status-light {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  color: #e9e4ff;
  font-size: 13px;
  font-weight: 800;
}

.status-light::before {
  content: "";
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: var(--accent);
  box-shadow: 0 0 18px var(--accent);
}

.toolbar {
  display: flex;
  gap: 8px;
}

.ghost-btn,
button {
  appearance: none;
  border: 0;
  cursor: pointer;
  font: inherit;
}

.ghost-btn {
  border: 1px solid rgba(255,255,255,.16);
  background: rgba(255,255,255,.08);
  color: #fff7d6;
  border-radius: 999px;
  padding: 8px 12px;
  font-weight: 900;
  transition: transform .18s ease, background .18s ease;
}

.ghost-btn:hover,
.touch button:hover,
button:hover {
  transform: translateY(-1px);
}

.controls {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.objectives {
  margin: 0;
  padding: 14px 14px 14px 30px;
  border-radius: 22px;
  color: #e9e4ff;
  background: rgba(255,255,255,.07);
  line-height: 1.75;
}

.canvas-wrap {
  position: relative;
  border-radius: 32px;
  overflow: hidden;
  background: #111;
}

.canvas-wrap::before {
  content: "";
  position: absolute;
  inset: 0;
  z-index: 2;
  pointer-events: none;
  background:
    linear-gradient(90deg, rgba(255,255,255,.08), transparent 16%, transparent 84%, rgba(255,255,255,.08)),
    radial-gradient(circle at 50% 50%, transparent 58%, rgba(0,0,0,.25));
  mix-blend-mode: screen;
}

canvas {
  display: block;
  width: 100%;
  height: auto;
  image-rendering: pixelated;
  background: #6be2ff;
}

.overlay {
  position: absolute;
  inset: 0;
  z-index: 5;
  display: grid;
  place-content: center;
  text-align: center;
  padding: 28px;
  background:
    radial-gradient(circle at 50% 38%, rgba(82,255,208,.18), transparent 28%),
    linear-gradient(135deg, rgba(8,4,26,.70), rgba(33,17,91,.78));
  backdrop-filter: blur(10px);
}

.overlay.hidden { display: none; }

.overlay-panel {
  width: min(720px, calc(100vw - 44px));
  border: 1px solid rgba(255,255,255,.18);
  border-radius: 34px;
  padding: clamp(24px, 5vw, 42px);
  background: linear-gradient(145deg, rgba(255,255,255,.16), rgba(255,255,255,.07));
  box-shadow: 0 30px 90px rgba(0,0,0,.42);
}

.overlay h2 {
  font-size: clamp(34px, 6vw, 64px);
  margin: 0 0 12px;
  letter-spacing: -0.05em;
}

.overlay p {
  max-width: 620px;
  margin: 0 auto 22px;
  color: #e4e0ff;
  line-height: 1.8;
}

.primary-btn {
  border-radius: 999px;
  padding: 14px 30px;
  font-weight: 1000;
  font-size: 16px;
  color: #21115b;
  background: linear-gradient(90deg, #ffe45c, #52ffd0, #80a7ff);
  box-shadow: 0 12px 36px rgba(82,255,208,.26);
}

.tips {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
  margin: 22px 0 0;
}

.tips span {
  border-radius: 18px;
  padding: 11px;
  background: rgba(0,0,0,.18);
  color: #fff7d6;
  font-size: 13px;
}

.touch {
  position: absolute;
  inset: auto 14px 14px 14px;
  z-index: 4;
  display: none;
  justify-content: space-between;
  pointer-events: none;
}

.touch-cluster {
  display: flex;
  gap: 9px;
  pointer-events: auto;
}

.touch button {
  width: 54px;
  height: 54px;
  border-radius: 18px;
  border: 1px solid rgba(255,255,255,.24);
  background: rgba(18,11,47,.54);
  color: #fff7d6;
  font-weight: 1000;
  box-shadow: 0 12px 28px rgba(0,0,0,.28);
  backdrop-filter: blur(10px);
}

.notes {
  margin-top: 18px;
  border-radius: 28px;
  padding: 20px;
  color: #e9e4ff;
}

.notes-grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 14px;
}

.notes h2,
.notes h3 {
  margin: 0 0 8px;
}

.notes p {
  margin: 0;
  line-height: 1.75;
}

@media (max-width: 860px) {
  .hero { grid-template-columns: 1fr; }
  .notes-grid { grid-template-columns: 1fr; }
  .tips { grid-template-columns: 1fr; }
}

@media (hover: none), (pointer: coarse), (max-width: 760px) {
  .touch { display: flex; }
}

@media (max-width: 600px) {
  .shell { width: min(100vw - 20px, 1180px); padding-top: 12px; }
  .hero-card, .command-card, .notes, .canvas-wrap { border-radius: 22px; }
  .controls span { font-size: 12px; }
  .touch button { width: 48px; height: 48px; border-radius: 16px; }
}

@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after { scroll-behavior: auto !important; transition: none !important; animation: none !important; }
}

</style>
</head>
<body>

  <main class="shell">
    <section class="hero">
      <div class="hero-card">
        <p class="eyebrow">HTML5 Canvas Demo · Advanced Single File Edition</p>
        <h1>Starbud Echoes</h1>
        <p class="sub">明亮高饱和横版探索动作 Demo：在原有平台跳跃、能力解锁、区域回访与程序化音乐基础上，强化了视觉层次、HUD、反馈、暂停/静音、任务引导、移动端触控与作品集呈现。</p>
        <div class="meta-row">
          <span>无外部图片资源</span>
          <span>Canvas 2D</span>
          <span>程序化角色/敌人/音乐</span>
          <span>作品集增强版</span>
        </div>
      </div>

      <aside class="command-card" aria-label="游戏控制说明">
        <div class="status-bar">
          <span id="statusText" class="status-light">待启动</span>
          <div class="toolbar">
            <button id="pauseButton" class="ghost-btn" type="button">暂停 P</button>
            <button id="muteButton" class="ghost-btn" type="button">静音 M</button>
          </div>
        </div>
        <div class="controls">
          <span>A/D 或 ←/→ 移动</span>
          <span>W/↑/空格 跳跃</span>
          <span>J 攻击</span>
          <span>K 冲刺</span>
          <span>P 暂停</span>
          <span>R 重开</span>
        </div>
        <ol class="objectives">
          <li>收集金币，踩踏或攻击敌人。</li>
          <li>取得二段跳种子与流星冲刺。</li>
          <li>击败遗迹守卫，进入彩虹门。</li>
        </ol>
      </aside>
    </section>

    <div class="canvas-wrap">
      <canvas id="game" width="960" height="540" aria-label="Starbud Echoes game canvas"></canvas>
      <div id="overlay" class="overlay">
        <div class="overlay-panel">
          <h2>点击开始冒险</h2>
          <p>增强版加入任务提示、迷你地图、Boss 血条、连击奖励、屏幕震动、触控按钮、暂停/静音与更完整的视觉氛围。建议打开声音体验程序化音乐。</p>
          <button id="startButton" class="primary-btn" type="button">开始 / 开启音乐</button>
          <div class="tips" aria-label="游戏特色">
            <span>能力门槛路线</span>
            <span>连击与粒子反馈</span>
            <span>移动端可玩</span>
          </div>
        </div>
      </div>
      <div class="touch" aria-label="触屏控制">
        <div class="touch-cluster">
          <button type="button" data-key="ArrowLeft">←</button>
          <button type="button" data-key="ArrowRight">→</button>
        </div>
        <div class="touch-cluster">
          <button type="button" data-key="KeyJ">斩</button>
          <button type="button" data-key="KeyK">冲</button>
          <button type="button" data-key="Space">跳</button>
        </div>
      </div>
    </div>

    <section class="notes">
      <div class="notes-grid">
        <article>
          <h2>升级重点</h2>
          <p>从“可玩 Demo”升级到“作品集展示页”：英雄区、控制卡片、目标列表、玻璃拟态面板、Canvas 内 HUD 与通关反馈形成统一视觉系统。</p>
        </article>
        <article>
          <h3>玩法增强</h3>
          <p>新增暂停/静音、连击、Boss 血条、任务状态、迷你地图、屏幕震动、最佳时间记录与触控按钮，玩家能更清楚地理解探索目标。</p>
        </article>
        <article>
          <h3>工程优化</h3>
          <p>保持单 HTML、无外部素材依赖，适合直接部署到 GitHub Pages / GitLab Pages，也方便继续拆分成模块化工程。</p>
        </article>
      </div>
    </section>
  </main>

  <script>
(() => {
  'use strict';

  const canvas = document.getElementById('game');
  const ctx = canvas.getContext('2d');
  const overlay = document.getElementById('overlay');
  const startButton = document.getElementById('startButton');
  const pauseButton = document.getElementById('pauseButton');
  const muteButton = document.getElementById('muteButton');
  const statusText = document.getElementById('statusText');

  const W = canvas.width;
  const H = canvas.height;
  const WORLD_W = 3900;
  const WORLD_H = 900;
  const GROUND_Y = 760;
  const GRAVITY = 2100;
  const MOVE_SPEED = 340;
  const JUMP_SPEED = 760;
  const FRICTION = 0.82;
  const REDUCE_MOTION = window.matchMedia('(prefers-reduced-motion: reduce)').matches;

  const keys = new Set();
  const justPressed = new Set();
  const clamp = (v, min, max) => Math.max(min, Math.min(max, v));
  const rand = (n) => Math.sin(n * 999) * 0.5 + 0.5;

  let audio = null;
  let musicTimer = 0;
  let running = false;
  let paused = false;
  let muted = false;
  let cameraShake = 0;
  let lastTime = performance.now();
  let camera = { x: 0, y: 250 };
  let state = null;
  let bestTime = Number(localStorage.getItem('starbud-best-time') || 0);

  function rectsOverlap(a, b) {
    return a.x < b.x + b.w && a.x + a.w > b.x && a.y < b.y + b.h && a.y + a.h > b.y;
  }

  function setStatus(text) {
    if (statusText) statusText.textContent = text;
  }

  function formatTime(seconds) {
    const s = Math.max(0, Math.floor(seconds));
    const mm = String(Math.floor(s / 60)).padStart(2, '0');
    const ss = String(s % 60).padStart(2, '0');
    return `${mm}:${ss}`;
  }

  function togglePause(force) {
    if (!running) return;
    paused = typeof force === 'boolean' ? force : !paused;
    if (pauseButton) pauseButton.textContent = paused ? '继续 P' : '暂停 P';
    setStatus(paused ? '已暂停' : '冒险中');
  }

  function toggleMute(force) {
    muted = typeof force === 'boolean' ? force : !muted;
    if (audio) audio.master.gain.value = muted ? 0 : 0.17;
    if (muteButton) muteButton.textContent = muted ? '开声音 M' : '静音 M';
  }

  function setMessage(text, duration = 2.7) {
    state.message = text;
    state.messageTimer = duration;
  }


  function makeAudio() {
    if (audio) return audio;
    const AudioContext = window.AudioContext || window.webkitAudioContext;
    const ac = new AudioContext();
    const master = ac.createGain();
    master.gain.value = muted ? 0 : 0.17;
    master.connect(ac.destination);
    audio = { ac, master, beat: 0 };
    return audio;
  }

  function playTone(freq, duration = 0.12, type = 'sine', gain = 0.18, delay = 0) {
    if (!audio) return;
    const { ac, master } = audio;
    const osc = ac.createOscillator();
    const g = ac.createGain();
    const t = ac.currentTime + delay;
    osc.type = type;
    osc.frequency.setValueAtTime(freq, t);
    g.gain.setValueAtTime(0, t);
    g.gain.linearRampToValueAtTime(gain, t + 0.012);
    g.gain.exponentialRampToValueAtTime(0.001, t + duration);
    osc.connect(g).connect(master);
    osc.start(t);
    osc.stop(t + duration + 0.02);
  }

  function sfx(name) {
    if (!audio) return;
    if (name === 'jump') { playTone(420, .08, 'square', .09); playTone(680, .12, 'triangle', .07, .04); }
    if (name === 'coin') { playTone(880, .08, 'triangle', .08); playTone(1320, .12, 'triangle', .06, .07); }
    if (name === 'hit') { playTone(120, .11, 'sawtooth', .13); playTone(75, .16, 'square', .08, .04); }
    if (name === 'power') { [523, 659, 784, 1046].forEach((f, i) => playTone(f, .18, 'triangle', .08, i * .08)); }
    if (name === 'dash') { playTone(260, .05, 'sawtooth', .08); playTone(520, .08, 'sawtooth', .06, .03); }
    if (name === 'win') { [523, 659, 784, 1046, 1318].forEach((f, i) => playTone(f, .22, 'triangle', .08, i * .11)); }
  }

  function tickMusic(dt) {
    if (!audio || !running) return;
    musicTimer -= dt;
    if (musicTimer > 0) return;
    musicTimer = 0.27;
    const scale = [261.63, 293.66, 329.63, 392, 440, 523.25, 587.33, 659.25];
    const bass = [130.81, 146.83, 164.81, 196];
    const b = audio.beat++;
    const zoneShift = camera.x > 2400 ? 1.18 : camera.x > 1300 ? 0.88 : 1;
    playTone(scale[(b * 3 + Math.floor(camera.x / 500)) % scale.length] * zoneShift, .11, 'triangle', .035);
    if (b % 2 === 0) playTone(bass[Math.floor(b / 2) % bass.length] * zoneShift, .18, 'sine', .05);
    if (b % 8 === 7) playTone(987.77 * zoneShift, .07, 'square', .025);
  }

  function reset() {
    state = {
      time: 0,
      won: false,
      pausedAtWin: false,
      message: '',
      messageTimer: 0,
      combo: 0,
      comboTimer: 0,
      deaths: 0,
      runTime: 0,
      player: {
        x: 80, y: 600, w: 42, h: 58,
        vx: 0, vy: 0, dir: 1,
        onGround: false, jumps: 0, hp: 6, inv: 0,
        attack: 0, dash: 0, dashCd: 0,
        coyote: 0, jumpBuffer: 0,
        hasDoubleJump: false, hasDash: false,
        coins: 0
      },
      particles: [],
      platforms: makePlatforms(),
      coins: makeCoins(),
      pickups: makePickups(),
      enemies: makeEnemies(),
      projectiles: [],
      checkpoints: [{ x: 145, y: 668 }]
    };
    camera.x = 0;
    camera.y = 240;
    cameraShake = 0;
    paused = false;
    if (pauseButton) pauseButton.textContent = '暂停 P';
    setStatus(running ? '冒险中' : '待启动');
  }

  function makePlatforms() {
    const p = [
      { x: 0, y: GROUND_Y, w: 3900, h: 140, kind: 'ground' },
      { x: 150, y: 630, w: 210, h: 34, kind: 'grass' },
      { x: 470, y: 550, w: 180, h: 30, kind: 'grass' },
      { x: 760, y: 470, w: 240, h: 30, kind: 'grass' },
      { x: 1080, y: 610, w: 270, h: 32, kind: 'grass' },
      { x: 1370, y: 500, w: 230, h: 30, kind: 'crystal' },
      { x: 1650, y: 410, w: 170, h: 28, kind: 'crystal', needDouble: true },
      { x: 1900, y: 610, w: 270, h: 34, kind: 'crystal' },
      { x: 2200, y: 535, w: 160, h: 30, kind: 'crystal' },
      { x: 2420, y: 450, w: 260, h: 30, kind: 'ruin', needDash: true },
      { x: 2740, y: 620, w: 260, h: 34, kind: 'ruin' },
      { x: 3080, y: 510, w: 220, h: 32, kind: 'ruin' },
      { x: 3380, y: 400, w: 180, h: 30, kind: 'ruin' },
      { x: 3650, y: 650, w: 180, h: 32, kind: 'finish' }
    ];
    for (let i = 0; i < 10; i++) p.push({ x: 1210 + i * 96, y: 720 - (i % 2) * 48, w: 52, h: 24, kind: 'stone' });
    return p;
  }

  function makeCoins() {
    const coins = [];
    const arcs = [
      [180, 580, 8], [520, 505, 6], [800, 430, 9], [1120, 560, 7],
      [1420, 455, 7], [1930, 560, 8], [2450, 405, 8], [2760, 575, 7], [3140, 465, 8], [3410, 355, 7]
    ];
    arcs.forEach(([x, y, n]) => {
      for (let i = 0; i < n; i++) coins.push({ x: x + i * 28, y: y - Math.sin(i / (n - 1) * Math.PI) * 60, r: 9, taken: false });
    });
    return coins;
  }

  function makePickups() {
    return [
      { x: 910, y: 405, w: 34, h: 34, type: 'double', taken: false, label: '二段跳种子' },
      { x: 2185, y: 478, w: 34, h: 34, type: 'dash', taken: false, label: '流星冲刺' },
      { x: 3550, y: 340, w: 36, h: 40, type: 'heart', taken: false, label: '星辉生命' }
    ];
  }

  function makeEnemies() {
    return [
      { type: 'slime', x: 540, y: 700, w: 46, h: 34, vx: 70, hp: 2, min: 480, max: 720, cd: 0 },
      { type: 'mush', x: 1140, y: 700, w: 44, h: 58, vx: 55, hp: 3, min: 1080, max: 1330, cd: 0 },
      { type: 'bat', x: 1520, y: 420, w: 46, h: 34, vx: 80, hp: 2, min: 1360, max: 1770, baseY: 420, cd: 0 },
      { type: 'turret', x: 2010, y: 560, w: 48, h: 50, vx: 0, hp: 3, min: 0, max: 0, cd: 1.2 },
      { type: 'crab', x: 2820, y: 570, w: 58, h: 38, vx: 95, hp: 3, min: 2700, max: 3030, cd: 0 },
      { type: 'bat', x: 3190, y: 430, w: 52, h: 38, vx: -90, hp: 3, min: 3060, max: 3350, baseY: 430, cd: 0 },
      { type: 'sentinel', x: 3650, y: 590, w: 88, h: 92, vx: 55, hp: 8, min: 3550, max: 3800, cd: 0.8 }
    ];
  }

  function spawnParticle(x, y, color, count = 8, spread = 260) {
    for (let i = 0; i < count; i++) {
      const a = (Math.PI * 2 * i) / count + rand(x + y + i) * .7;
      state.particles.push({ x, y, vx: Math.cos(a) * spread * (0.35 + rand(i) * 0.65), vy: Math.sin(a) * spread * (0.35 + rand(i + 8) * 0.65), life: .55 + rand(i + 2) * .3, color, size: 3 + rand(i + 4) * 5 });
    }
  }

  function inputDown(code) { return keys.has(code); }
  function pressed(...codes) { return codes.some((c) => justPressed.has(c)); }

  function applyPlatformCollisions(entity, dt) {
    entity.onGround = false;
    for (const p of state.platforms) {
      if (p.needDouble && !state.player.hasDoubleJump) continue;
      if (p.needDash && !state.player.hasDash) continue;
      const prev = { x: entity.x - entity.vx * dt, y: entity.y - entity.vy * dt, w: entity.w, h: entity.h };
      if (!rectsOverlap(entity, p)) continue;
      if (prev.y + prev.h <= p.y && entity.vy >= 0) {
        entity.y = p.y - entity.h;
        entity.vy = 0;
        entity.onGround = true;
        entity.jumps = 0;
      } else if (prev.y >= p.y + p.h && entity.vy < 0) {
        entity.y = p.y + p.h;
        entity.vy = 0;
      } else if (prev.x + prev.w <= p.x && entity.vx > 0) {
        entity.x = p.x - entity.w;
        entity.vx = 0;
      } else if (prev.x >= p.x + p.w && entity.vx < 0) {
        entity.x = p.x + p.w;
        entity.vx = 0;
      }
    }
  }

  function updatePlayer(dt) {
    const p = state.player;
    if (p.inv > 0) p.inv -= dt;
    if (p.attack > 0) p.attack -= dt;
    if (p.dash > 0) p.dash -= dt;
    if (p.dashCd > 0) p.dashCd -= dt;

    const left = inputDown('ArrowLeft') || inputDown('KeyA');
    const right = inputDown('ArrowRight') || inputDown('KeyD');
    if (left) { p.vx -= MOVE_SPEED * 5.2 * dt; p.dir = -1; }
    if (right) { p.vx += MOVE_SPEED * 5.2 * dt; p.dir = 1; }
    if (!left && !right && p.onGround) p.vx *= FRICTION;
    p.vx = clamp(p.vx, -MOVE_SPEED, MOVE_SPEED);

    if (p.onGround) p.coyote = 0.11;
    else p.coyote = Math.max(0, p.coyote - dt);

    if (pressed('Space', 'ArrowUp', 'KeyW')) p.jumpBuffer = 0.13;
    p.jumpBuffer = Math.max(0, p.jumpBuffer - dt);

    if (p.jumpBuffer > 0) {
      const canAirJump = p.hasDoubleJump && !p.onGround && p.jumps < 1;
      if (p.onGround || p.coyote > 0 || canAirJump) {
        const wasGrounded = p.onGround || p.coyote > 0;
        p.vy = -JUMP_SPEED;
        p.onGround = false;
        p.coyote = 0;
        p.jumpBuffer = 0;
        p.jumps = wasGrounded ? 0 : p.jumps + 1;
        spawnParticle(p.x + p.w / 2, p.y + p.h, '#fff176', 10, 210);
        sfx('jump');
      }
    }

    if (pressed('KeyJ')) {
      p.attack = .18;
      sfx('hit');
    }

    if (pressed('KeyK') && p.hasDash && p.dashCd <= 0) {
      p.dash = .18;
      p.dashCd = .65;
      p.vx = p.dir * 820;
      p.vy *= .25;
      spawnParticle(p.x + p.w / 2, p.y + p.h / 2, '#72f6ff', 18, 350);
      sfx('dash');
    }

    p.vy += GRAVITY * dt;
    if (p.dash > 0) p.vy *= .8;
    p.x += p.vx * dt;
    applyPlatformCollisions(p, dt);
    p.y += p.vy * dt;
    applyPlatformCollisions(p, dt);
    p.x = clamp(p.x, 0, WORLD_W - p.w);

    if (p.y > WORLD_H + 80 || p.hp <= 0) {
      state.deaths++;
      setMessage('被击倒，已从起点重生 · 小心敌人与深坑');
      p.x = 80; p.y = 600; p.vx = 0; p.vy = 0; p.hp = 6; p.inv = 1.4; p.coyote = 0; p.jumpBuffer = 0;
      cameraShake = Math.max(cameraShake, 16);
      sfx('hit');
    }

    const attackRect = { x: p.dir > 0 ? p.x + p.w - 3 : p.x - 48, y: p.y + 15, w: 51, h: 34 };
    if (p.attack > 0) {
      state.enemies.forEach((e) => {
        if (e.dead) return;
        if (rectsOverlap(attackRect, e)) {
          e.hp -= dt * 11;
          e.vx += p.dir * 85;
          spawnParticle(e.x + e.w / 2, e.y + e.h / 2, '#ff5ec4', 3, 180);
          if (e.hp <= 0) killEnemy(e);
        }
      });
    }
  }

  function damagePlayer(amount, fromX) {
    const p = state.player;
    if (p.inv > 0 || p.dash > 0) return;
    p.hp -= amount;
    p.inv = 0.9;
    p.vx = p.x < fromX ? -360 : 360;
    p.vy = -390;
    spawnParticle(p.x + p.w / 2, p.y + p.h / 2, '#ff5f6d', 22, 360);
    cameraShake = Math.max(cameraShake, 14);
    state.combo = 0;
    state.comboTimer = 0;
    sfx('hit');
  }

  function killEnemy(e) {
    e.dead = true;
    state.combo++;
    state.comboTimer = 2.6;
    const bonus = e.type === 'sentinel' ? 20 : 5 + Math.min(8, state.combo);
    spawnParticle(e.x + e.w / 2, e.y + e.h / 2, e.type === 'bat' ? '#b284ff' : '#74ff6b', 24, 390);
    sfx('coin');
    state.player.coins += bonus;
    cameraShake = Math.max(cameraShake, e.type === 'sentinel' ? 22 : 8);
    if (e.type === 'sentinel') setMessage('遗迹守卫已被击败，彩虹门开启！', 4.2);
    else if (state.combo > 1) setMessage(`连击 x${state.combo} · 奖励 +${bonus}`, 1.7);
  }

  function updateEnemies(dt) {
    const p = state.player;
    state.enemies.forEach((e) => {
      if (e.dead) return;
      e.cd -= dt;
      if (e.type === 'bat') {
        e.x += e.vx * dt;
        if (e.x < e.min || e.x > e.max) e.vx *= -1;
        e.y = e.baseY + Math.sin(state.time * 3 + e.x * .01) * 55;
      } else if (e.type === 'turret') {
        if (e.cd <= 0 && Math.abs(p.x - e.x) < 620) {
          e.cd = 1.45;
          const dir = p.x < e.x ? -1 : 1;
          state.projectiles.push({ x: e.x + 20, y: e.y + 18, w: 18, h: 18, vx: dir * 260, vy: -40, life: 3, color: '#ff8b3d' });
          playTone(170, .08, 'sawtooth', .035);
        }
      } else {
        e.x += e.vx * dt;
        if (e.x < e.min || e.x > e.max) e.vx *= -1;
        if (e.type === 'mush' && e.cd <= 0) { e.cd = 1.6; e.vy = -520; }
        e.vy = (e.vy || 0) + GRAVITY * dt;
        e.y += (e.vy || 0) * dt;
        applyEnemyPlatform(e, dt);
      }

      if (rectsOverlap(p, e)) {
        const stomp = p.vy > 170 && p.y + p.h < e.y + 20;
        if (stomp) {
          e.hp -= 2;
          p.vy = -540;
          spawnParticle(e.x + e.w / 2, e.y, '#fff176', 12, 260);
          sfx('hit');
          if (e.hp <= 0) killEnemy(e);
        } else {
          damagePlayer(e.type === 'sentinel' ? 2 : 1, e.x + e.w / 2);
        }
      }
    });

    state.projectiles.forEach((b) => {
      b.life -= dt;
      b.vy += 320 * dt;
      b.x += b.vx * dt;
      b.y += b.vy * dt;
      if (rectsOverlap(p, b)) { b.life = 0; damagePlayer(1, b.x); }
    });
    state.projectiles = state.projectiles.filter((b) => b.life > 0);
  }

  function applyEnemyPlatform(e, dt) {
    for (const pl of state.platforms) {
      if (pl.needDouble || pl.needDash) continue;
      if (!rectsOverlap(e, pl)) continue;
      const prevY = e.y - (e.vy || 0) * dt;
      if (prevY + e.h <= pl.y && e.vy >= 0) { e.y = pl.y - e.h; e.vy = 0; }
    }
  }

  function updateCollectibles(dt) {
    const p = state.player;
    state.coins.forEach((c) => {
      if (!c.taken && rectsOverlap(p, { x: c.x - c.r, y: c.y - c.r, w: c.r * 2, h: c.r * 2 })) {
        c.taken = true;
        p.coins++;
        spawnParticle(c.x, c.y, '#ffe75d', 8, 210);
        sfx('coin');
      }
    });

    state.pickups.forEach((item) => {
      if (item.taken || !rectsOverlap(p, item)) return;
      item.taken = true;
      if (item.type === 'double') { p.hasDoubleJump = true; setMessage('获得二段跳种子：可抵达更高平台', 4.0); }
      if (item.type === 'dash') { p.hasDash = true; setMessage('获得流星冲刺：按 K 穿越冲刺路线', 4.0); }
      if (item.type === 'heart') { p.hp = Math.min(8, p.hp + 2); setMessage('生命上限临时提升', 3.0); }
      spawnParticle(item.x + item.w / 2, item.y + item.h / 2, '#52ffd0', 28, 420);
      sfx('power');
    });

    const sentinelAlive = state.enemies.some((e) => e.type === 'sentinel' && !e.dead);
    if (!sentinelAlive && p.x > 3670 && p.y < 690 && !state.won) {
      state.won = true;
      if (!bestTime || state.runTime < bestTime) {
        bestTime = state.runTime;
        localStorage.setItem('starbud-best-time', String(bestTime));
      }
      setMessage('Demo 通关：你完成了能力解锁、区域回访与最终挑战！', 9.0);
      cameraShake = Math.max(cameraShake, 18);
      setStatus('已通关');
      sfx('win');
    }
  }

  function updateParticles(dt) {
    state.particles.forEach((pt) => { pt.life -= dt; pt.x += pt.vx * dt; pt.y += pt.vy * dt; pt.vy += 700 * dt; });
    state.particles = state.particles.filter((pt) => pt.life > 0);
  }

  function updateCamera(dt) {
    const p = state.player;
    const tx = clamp(p.x + p.w / 2 - W * 0.45, 0, WORLD_W - W);
    const ty = clamp(p.y + p.h / 2 - H * 0.58, 0, WORLD_H - H);
    camera.x += (tx - camera.x) * clamp(dt * 6, 0, 1);
    camera.y += (ty - camera.y) * clamp(dt * 6, 0, 1);
  }

  function update(dt) {
    state.time += dt;
    if (!state.won) state.runTime += dt;
    if (state.messageTimer > 0) {
      state.messageTimer -= dt;
      if (state.messageTimer <= 0) state.message = '';
    }
    if (state.comboTimer > 0) {
      state.comboTimer -= dt;
      if (state.comboTimer <= 0) state.combo = 0;
    }
    cameraShake = Math.max(0, cameraShake - dt * 34);
    if (pressed('KeyR')) reset();
    updatePlayer(dt);
    updateEnemies(dt);
    updateCollectibles(dt);
    updateParticles(dt);
    updateCamera(dt);
    tickMusic(dt);
    justPressed.clear();
  }

  function drawBackground() {
    const gx = camera.x;
    const grad = ctx.createLinearGradient(0, 0, 0, H);
    if (gx < 1250) { grad.addColorStop(0, '#6be2ff'); grad.addColorStop(.6, '#b8ff80'); grad.addColorStop(1, '#44bd6e'); }
    else if (gx < 2500) { grad.addColorStop(0, '#22115f'); grad.addColorStop(.5, '#635cff'); grad.addColorStop(1, '#1bd6c7'); }
    else { grad.addColorStop(0, '#ff9a54'); grad.addColorStop(.45, '#8340d8'); grad.addColorStop(1, '#2a123b'); }
    ctx.fillStyle = grad;
    ctx.fillRect(0, 0, W, H);

    ctx.save();
    ctx.translate(-camera.x * 0.18, -camera.y * 0.05);
    for (let i = 0; i < 24; i++) {
      ctx.fillStyle = i % 3 === 0 ? 'rgba(255,255,255,.55)' : 'rgba(255,255,255,.22)';
      const x = (i * 260 + 70) % (WORLD_W * .8);
      const y = 60 + (i % 5) * 38;
      drawCloud(x, y, 1 + (i % 4) * .18);
    }
    ctx.restore();

    ctx.save();
    ctx.translate(-camera.x * 0.38, -camera.y * 0.12);
    for (let i = 0; i < 15; i++) {
      const x = i * 310 - 80;
      const h = 180 + (i % 4) * 45;
      ctx.fillStyle = i % 2 ? 'rgba(61,35,124,.45)' : 'rgba(18,89,130,.34)';
      ctx.beginPath(); ctx.moveTo(x, GROUND_Y); ctx.lineTo(x + 170, GROUND_Y - h); ctx.lineTo(x + 340, GROUND_Y); ctx.closePath(); ctx.fill();
    }
    ctx.restore();
  }

  function drawCloud(x, y, s) {
    ctx.beginPath();
    ctx.ellipse(x, y, 38 * s, 18 * s, 0, 0, Math.PI * 2);
    ctx.ellipse(x + 31 * s, y - 10 * s, 45 * s, 24 * s, 0, 0, Math.PI * 2);
    ctx.ellipse(x + 70 * s, y, 36 * s, 17 * s, 0, 0, Math.PI * 2);
    ctx.fill();
  }

  function drawPlatforms() {
    state.platforms.forEach((p) => {
      if (p.x + p.w < camera.x - 60 || p.x > camera.x + W + 60) return;
      if (p.needDouble && !state.player.hasDoubleJump) drawGateHint(p, '#52ffd0', '二段跳路线');
      if (p.needDash && !state.player.hasDash) drawGateHint(p, '#80a7ff', '冲刺路线');
      if ((p.needDouble && !state.player.hasDoubleJump) || (p.needDash && !state.player.hasDash)) return;
      const x = p.x - camera.x, y = p.y - camera.y;
      let top = '#65e65c', side = '#238046';
      if (p.kind === 'crystal') { top = '#72f6ff'; side = '#4d3bd9'; }
      if (p.kind === 'ruin') { top = '#ffce5c'; side = '#9b4a2a'; }
      if (p.kind === 'stone') { top = '#d5dbff'; side = '#737aa8'; }
      if (p.kind === 'finish') { top = '#ff7be5'; side = '#6330ff'; }
      ctx.fillStyle = side; roundRect(x, y + 8, p.w, p.h, 8, true);
      ctx.fillStyle = top; roundRect(x, y, p.w, Math.max(16, p.h * .45), 8, true);
      for (let i = 8; i < p.w; i += 38) {
        ctx.fillStyle = 'rgba(255,255,255,.22)'; ctx.fillRect(x + i, y + 5, 16, 4);
      }
    });
  }

  function drawGateHint(p, color, text) {
    const x = p.x - camera.x, y = p.y - camera.y;
    ctx.strokeStyle = color;
    ctx.setLineDash([8, 8]);
    ctx.lineWidth = 3;
    ctx.strokeRect(x, y, p.w, p.h);
    ctx.setLineDash([]);
    ctx.fillStyle = color;
    ctx.font = 'bold 16px system-ui';
    ctx.fillText(text, x + 12, y - 10);
  }

  function roundRect(x, y, w, h, r, fill = false, stroke = false) {
    ctx.beginPath();
    ctx.moveTo(x + r, y);
    ctx.arcTo(x + w, y, x + w, y + h, r);
    ctx.arcTo(x + w, y + h, x, y + h, r);
    ctx.arcTo(x, y + h, x, y, r);
    ctx.arcTo(x, y, x + w, y, r);
    if (fill) ctx.fill();
    if (stroke) ctx.stroke();
  }

  function drawCollectibles() {
    state.coins.forEach((c) => {
      if (c.taken || c.x < camera.x - 40 || c.x > camera.x + W + 40) return;
      const bob = Math.sin(state.time * 5 + c.x * .03) * 4;
      ctx.save(); ctx.translate(c.x - camera.x, c.y - camera.y + bob); ctx.rotate(state.time * 2);
      ctx.fillStyle = '#ffe75d'; ctx.beginPath(); ctx.ellipse(0, 0, c.r, c.r * 1.25, 0, 0, Math.PI * 2); ctx.fill();
      ctx.strokeStyle = '#ff9c3d'; ctx.lineWidth = 3; ctx.stroke();
      ctx.fillStyle = 'rgba(255,255,255,.75)'; ctx.fillRect(-3, -8, 4, 16);
      ctx.restore();
    });
    state.pickups.forEach((it) => {
      if (it.taken) return;
      const x = it.x - camera.x, y = it.y - camera.y + Math.sin(state.time * 4 + it.x) * 7;
      ctx.save(); ctx.translate(x + it.w / 2, y + it.h / 2);
      const color = it.type === 'double' ? '#52ffd0' : it.type === 'dash' ? '#80a7ff' : '#ff5ec4';
      ctx.fillStyle = color; ctx.shadowColor = color; ctx.shadowBlur = 18;
      ctx.beginPath();
      for (let i = 0; i < 5; i++) {
        const a = -Math.PI / 2 + i * Math.PI * 2 / 5;
        ctx.lineTo(Math.cos(a) * 19, Math.sin(a) * 19);
        ctx.lineTo(Math.cos(a + Math.PI / 5) * 8, Math.sin(a + Math.PI / 5) * 8);
      }
      ctx.closePath(); ctx.fill(); ctx.shadowBlur = 0;
      ctx.fillStyle = '#fff'; ctx.font = 'bold 12px system-ui'; ctx.textAlign = 'center'; ctx.fillText(it.type === 'double' ? '2J' : it.type === 'dash' ? 'D' : '+', 0, 5);
      ctx.restore();
    });
  }

  function drawEnemies() {
    state.enemies.forEach((e) => {
      if (e.dead || e.x + e.w < camera.x - 60 || e.x > camera.x + W + 60) return;
      ctx.save(); ctx.translate(e.x - camera.x, e.y - camera.y);
      if (e.type === 'slime') drawSlime(e);
      if (e.type === 'mush') drawMush(e);
      if (e.type === 'bat') drawBat(e);
      if (e.type === 'turret') drawTurret(e);
      if (e.type === 'crab') drawCrab(e);
      if (e.type === 'sentinel') drawSentinel(e);
      ctx.restore();
    });
    state.projectiles.forEach((b) => {
      ctx.fillStyle = b.color;
      ctx.shadowColor = b.color; ctx.shadowBlur = 12;
      ctx.beginPath(); ctx.arc(b.x - camera.x + b.w / 2, b.y - camera.y + b.h / 2, b.w / 2, 0, Math.PI * 2); ctx.fill();
      ctx.shadowBlur = 0;
    });
  }

  function drawSlime(e) {
    ctx.fillStyle = '#5cff6d'; roundRect(0, 8, e.w, e.h - 8, 16, true);
    ctx.fillStyle = '#1f6b38'; ctx.beginPath(); ctx.arc(14, 19, 4, 0, Math.PI * 2); ctx.arc(32, 19, 4, 0, Math.PI * 2); ctx.fill();
  }
  function drawMush(e) {
    ctx.fillStyle = '#ffe7a8'; roundRect(13, 20, 18, 38, 8, true);
    ctx.fillStyle = '#ff4a7d'; ctx.beginPath(); ctx.ellipse(22, 17, 28, 18, 0, 0, Math.PI * 2); ctx.fill();
    ctx.fillStyle = '#fff'; ctx.beginPath(); ctx.arc(8, 12, 6, 0, Math.PI * 2); ctx.arc(30, 8, 7, 0, Math.PI * 2); ctx.fill();
    ctx.fillStyle = '#45283c'; ctx.fillRect(17, 35, 4, 5); ctx.fillRect(27, 35, 4, 5);
  }
  function drawBat(e) {
    ctx.fillStyle = '#4b2fbf';
    ctx.beginPath(); ctx.arc(e.w / 2, e.h / 2, 15, 0, Math.PI * 2); ctx.fill();
    ctx.fillStyle = '#b284ff';
    ctx.beginPath(); ctx.moveTo(20, 18); ctx.lineTo(-10, Math.sin(state.time * 9) * 12 + 14); ctx.lineTo(11, 30); ctx.closePath(); ctx.fill();
    ctx.beginPath(); ctx.moveTo(e.w - 20, 18); ctx.lineTo(e.w + 10, Math.sin(state.time * 9 + 1) * 12 + 14); ctx.lineTo(e.w - 11, 30); ctx.closePath(); ctx.fill();
    ctx.fillStyle = '#fff'; ctx.fillRect(19, 14, 5, 5); ctx.fillRect(29, 14, 5, 5);
  }
  function drawTurret(e) {
    ctx.fillStyle = '#ffb13d'; roundRect(2, 10, e.w - 4, e.h - 10, 10, true);
    ctx.fillStyle = '#7a3215'; ctx.fillRect(e.x > state.player.x ? -16 : e.w - 1, 22, 18, 9);
    ctx.fillStyle = '#fff176'; ctx.beginPath(); ctx.arc(e.w / 2, 22, 8, 0, Math.PI * 2); ctx.fill();
    ctx.fillStyle = '#3b1c14'; ctx.beginPath(); ctx.arc(e.w / 2, 22, 4, 0, Math.PI * 2); ctx.fill();
  }
  function drawCrab(e) {
    ctx.fillStyle = '#ff5f6d'; roundRect(8, 12, 42, 25, 10, true);
    ctx.fillStyle = '#ffd1d8'; ctx.fillRect(15, 5, 6, 10); ctx.fillRect(37, 5, 6, 10);
    ctx.fillStyle = '#341414'; ctx.fillRect(16, 4, 5, 5); ctx.fillRect(38, 4, 5, 5);
    ctx.strokeStyle = '#ffb3bd'; ctx.lineWidth = 5;
    ctx.beginPath(); ctx.moveTo(6, 24); ctx.lineTo(-8, 15); ctx.moveTo(52, 24); ctx.lineTo(66, 15); ctx.stroke();
  }
  function drawSentinel(e) {
    ctx.fillStyle = '#6330ff'; roundRect(5, 16, 78, 76, 16, true);
    ctx.fillStyle = '#ffce5c'; roundRect(18, 0, 52, 38, 16, true);
    ctx.fillStyle = '#52ffd0'; ctx.beginPath(); ctx.arc(36, 22, 7, 0, Math.PI * 2); ctx.arc(55, 22, 7, 0, Math.PI * 2); ctx.fill();
    ctx.strokeStyle = '#ff7be5'; ctx.lineWidth = 6; ctx.beginPath(); ctx.moveTo(0, 55); ctx.lineTo(-20, 75); ctx.moveTo(88, 55); ctx.lineTo(108, 75); ctx.stroke();
    ctx.fillStyle = '#fff'; ctx.font = 'bold 13px system-ui'; ctx.fillText(Math.ceil(e.hp), 40, -10);
  }

  function drawPlayer() {
    const p = state.player;
    const flash = p.inv > 0 && Math.floor(state.time * 18) % 2 === 0;
    ctx.save(); ctx.translate(p.x - camera.x + p.w / 2, p.y - camera.y + p.h / 2);
    ctx.scale(p.dir, 1);
    if (p.dash > 0) { ctx.fillStyle = 'rgba(82,255,208,.35)'; roundRect(-44, -20, 72, 40, 20, true); }
    if (!flash) {
      ctx.fillStyle = '#ff5ec4'; roundRect(-18, -23, 36, 45, 13, true);
      ctx.fillStyle = '#ffe75d'; roundRect(-14, -35, 28, 24, 12, true);
      ctx.fillStyle = '#4b2fbf'; ctx.fillRect(-19, 9, 38, 19);
      ctx.fillStyle = '#ffffff'; ctx.fillRect(3, -27, 5, 5); ctx.fillRect(13, -27, 5, 5);
      ctx.fillStyle = '#52ffd0'; ctx.fillRect(-6, 24, 10, 13); ctx.fillRect(10, 24, 10, 13);
      ctx.fillStyle = '#80a7ff'; ctx.beginPath(); ctx.moveTo(-17, -28); ctx.lineTo(-31, -44); ctx.lineTo(-9, -37); ctx.fill();
    }
    if (p.attack > 0) {
      ctx.strokeStyle = '#fff176'; ctx.lineWidth = 8; ctx.beginPath(); ctx.arc(20, 0, 42, -0.9, 0.9); ctx.stroke();
    }
    ctx.restore();
  }

  function drawParticles() {
    state.particles.forEach((pt) => {
      ctx.globalAlpha = clamp(pt.life * 2, 0, 1);
      ctx.fillStyle = pt.color;
      ctx.fillRect(pt.x - camera.x, pt.y - camera.y, pt.size, pt.size);
      ctx.globalAlpha = 1;
    });
  }

  function drawHUD() {
    const p = state.player;
    ctx.save();

    ctx.fillStyle = 'rgba(18, 11, 47, .62)';
    roundRect(18, 16, 418, 104, 22, true);
    ctx.strokeStyle = 'rgba(255,255,255,.16)';
    ctx.lineWidth = 1;
    roundRect(18, 16, 418, 104, 22, false, true);

    ctx.fillStyle = '#fff7d6';
    ctx.font = '900 19px system-ui';
    ctx.fillText('Starbud Echoes', 36, 44);

    ctx.fillStyle = '#c8c3ff';
    ctx.font = '12px system-ui';
    ctx.fillText(`时间 ${formatTime(state.runTime)} ${bestTime ? ` · 最佳 ${formatTime(bestTime)}` : ''}`, 206, 44);

    for (let i = 0; i < 8; i++) {
      ctx.fillStyle = i < p.hp ? '#ff5f6d' : 'rgba(255,255,255,.18)';
      ctx.beginPath();
      ctx.arc(42 + i * 24, 70, 9, 0, Math.PI * 2);
      ctx.fill();
      ctx.fillStyle = 'rgba(255,255,255,.55)';
      if (i < p.hp) {
        ctx.beginPath();
        ctx.arc(38 + i * 24, 66, 3, 0, Math.PI * 2);
        ctx.fill();
      }
    }

    ctx.fillStyle = '#ffe75d';
    ctx.font = '900 18px system-ui';
    ctx.fillText(`✦ ${p.coins}`, 260, 75);

    const skillY = 98;
    drawSkillPill(36, skillY, '二段跳', p.hasDoubleJump, '#52ffd0');
    drawSkillPill(112, skillY, '流星冲刺', p.hasDash, '#80a7ff');
    if (state.combo > 1) drawSkillPill(222, skillY, `连击 x${state.combo}`, true, '#ff7be5');

    drawQuestPanel();
    drawMiniMap();

    const sentinel = state.enemies.find((e) => e.type === 'sentinel');
    if (sentinel && !sentinel.dead && camera.x > 3100) {
      const bw = 430;
      const bx = W / 2 - bw / 2;
      const by = H - 52;
      ctx.fillStyle = 'rgba(18, 11, 47, .68)';
      roundRect(bx, by, bw, 26, 13, true);
      ctx.fillStyle = 'rgba(255,255,255,.18)';
      roundRect(bx + 10, by + 9, bw - 20, 8, 4, true);
      ctx.fillStyle = '#ff7be5';
      roundRect(bx + 10, by + 9, (bw - 20) * clamp(sentinel.hp / 8, 0, 1), 8, 4, true);
      ctx.fillStyle = '#fff7d6';
      ctx.font = '900 13px system-ui';
      ctx.textAlign = 'center';
      ctx.fillText('遗迹守卫 SENTINEL', W / 2, by - 5);
      ctx.textAlign = 'left';
    }

    if (state.message) {
      const alpha = state.messageTimer > 0 ? clamp(state.messageTimer, 0, 1) : 1;
      ctx.globalAlpha = alpha;
      ctx.fillStyle = 'rgba(0,0,0,.48)';
      roundRect(W / 2 - 300, 24, 600, 46, 20, true);
      ctx.fillStyle = '#fff7d6';
      ctx.font = '900 16px system-ui';
      ctx.textAlign = 'center';
      ctx.fillText(state.message, W / 2, 53);
      ctx.textAlign = 'left';
      ctx.globalAlpha = 1;
    }

    if (state.won) {
      ctx.fillStyle = 'rgba(18,11,47,.82)';
      roundRect(W / 2 - 282, H / 2 - 112, 564, 220, 32, true);
      ctx.strokeStyle = 'rgba(82,255,208,.46)';
      ctx.lineWidth = 2;
      roundRect(W / 2 - 282, H / 2 - 112, 564, 220, 32, false, true);
      ctx.fillStyle = '#52ffd0';
      ctx.font = '1000 44px system-ui';
      ctx.textAlign = 'center';
      ctx.fillText('Demo Clear!', W / 2, H / 2 - 42);
      ctx.fillStyle = '#fff7d6';
      ctx.font = '17px system-ui';
      ctx.fillText('你完成了跳跃、战斗、能力解锁和最终挑战', W / 2, H / 2 + 2);
      ctx.fillText(`通关时间 ${formatTime(state.runTime)} · 金币 ${p.coins} · 阵亡 ${state.deaths}`, W / 2, H / 2 + 34);
      ctx.fillText('按 R 可以重新开始', W / 2, H / 2 + 66);
      ctx.textAlign = 'left';
    }

    ctx.restore();
  }

  function drawSkillPill(x, y, text, active, color) {
    ctx.font = '900 13px system-ui';
    ctx.fillStyle = active ? color : 'rgba(255,255,255,.16)';
    roundRect(x, y - 17, ctx.measureText(text).width + 20, 24, 12, true);
    ctx.fillStyle = active ? '#120b2f' : 'rgba(255,255,255,.52)';
    ctx.fillText(text, x + 10, y);
  }

  function drawQuestPanel() {
    const p = state.player;
    const x = W - 292;
    const y = 92;
    ctx.fillStyle = 'rgba(18, 11, 47, .54)';
    roundRect(x, y, 254, 112, 20, true);
    ctx.strokeStyle = 'rgba(255,255,255,.13)';
    roundRect(x, y, 254, 112, 20, false, true);
    ctx.fillStyle = '#fff7d6';
    ctx.font = '900 15px system-ui';
    ctx.fillText('当前目标', x + 18, y + 28);
    const sentinelAlive = state.enemies.some((e) => e.type === 'sentinel' && !e.dead);
    const tasks = [
      [p.hasDoubleJump, '取得二段跳种子'],
      [p.hasDash, '取得流星冲刺'],
      [!sentinelAlive, '击败遗迹守卫']
    ];
    ctx.font = '13px system-ui';
    tasks.forEach(([done, text], i) => {
      ctx.fillStyle = done ? '#52ffd0' : '#c8c3ff';
      ctx.fillText(`${done ? '✓' : '○'} ${text}`, x + 20, y + 54 + i * 21);
    });
  }

  function drawMiniMap() {
    const p = state.player;
    const x = W - 292;
    const y = 18;
    const w = 254;
    const h = 56;
    ctx.fillStyle = 'rgba(18, 11, 47, .54)';
    roundRect(x, y, w, h, 18, true);
    ctx.fillStyle = '#c8c3ff';
    ctx.font = '13px system-ui';
    ctx.fillText('地图进度', x + 18, y + 24);
    ctx.fillStyle = 'rgba(255,255,255,.22)';
    roundRect(x + 18, y + 36, w - 36, 9, 5, true);
    ctx.fillStyle = '#52ffd0';
    roundRect(x + 18, y + 36, (w - 36) * (p.x / (WORLD_W - 120)), 9, 5, true);
    ctx.fillStyle = '#ffe75d';
    ctx.beginPath();
    ctx.arc(x + 18 + (w - 36) * (p.x / (WORLD_W - 120)), y + 40.5, 6, 0, Math.PI * 2);
    ctx.fill();
  }

  function drawWorldDecor() {
    ctx.save();
    ctx.translate(-camera.x, -camera.y);
    for (let i = 0; i < 9; i++) {
      const x = 340 + i * 420;
      const y = GROUND_Y - 55 - (i % 3) * 12;
      ctx.fillStyle = i % 2 ? 'rgba(82,255,208,.20)' : 'rgba(255,231,93,.18)';
      ctx.beginPath();
      ctx.moveTo(x, y);
      ctx.lineTo(x + 34, y + 55);
      ctx.lineTo(x - 34, y + 55);
      ctx.closePath();
      ctx.fill();
    }
    for (let i = 0; i < 12; i++) {
      const x = 90 + i * 330;
      const y = 130 + (i % 5) * 38;
      ctx.fillStyle = 'rgba(255,255,255,.18)';
      ctx.beginPath();
      ctx.arc(x, y, 2 + (i % 3), 0, Math.PI * 2);
      ctx.fill();
    }
    ctx.restore();
  }

  function drawPostFX() {
    const vignette = ctx.createRadialGradient(W / 2, H / 2, H * .18, W / 2, H / 2, W * .72);
    vignette.addColorStop(0, 'rgba(0,0,0,0)');
    vignette.addColorStop(1, 'rgba(0,0,0,.28)');
    ctx.fillStyle = vignette;
    ctx.fillRect(0, 0, W, H);

    ctx.globalAlpha = .08;
    ctx.fillStyle = '#fff';
    for (let y = 0; y < H; y += 4) ctx.fillRect(0, y, W, 1);
    ctx.globalAlpha = 1;
  }

  function drawPausePanel() {
    if (!paused) return;
    ctx.save();
    ctx.fillStyle = 'rgba(8,4,26,.58)';
    ctx.fillRect(0, 0, W, H);
    ctx.fillStyle = 'rgba(18,11,47,.82)';
    roundRect(W / 2 - 220, H / 2 - 88, 440, 176, 28, true);
    ctx.strokeStyle = 'rgba(255,255,255,.18)';
    roundRect(W / 2 - 220, H / 2 - 88, 440, 176, 28, false, true);
    ctx.fillStyle = '#fff7d6';
    ctx.font = '1000 38px system-ui';
    ctx.textAlign = 'center';
    ctx.fillText('Paused', W / 2, H / 2 - 24);
    ctx.fillStyle = '#c8c3ff';
    ctx.font = '16px system-ui';
    ctx.fillText('按 P 继续 · 按 M 静音 · 按 R 重开', W / 2, H / 2 + 22);
    ctx.textAlign = 'left';
    ctx.restore();
  }

  function render() {
    ctx.save();
    if (cameraShake > 0 && !REDUCE_MOTION) {
      const shakeX = (rand(state.time * 27.31) - 0.5) * cameraShake;
      const shakeY = (rand(state.time * 19.17 + 7) - 0.5) * cameraShake;
      ctx.translate(shakeX, shakeY);
    }
    drawBackground();
    drawWorldDecor();
    drawPlatforms();
    drawCollectibles();
    drawEnemies();
    drawPlayer();
    drawParticles();
    drawHUD();
    ctx.restore();
    drawPostFX();
    drawPausePanel();
  }

  function loop(now) {
    const dt = clamp((now - lastTime) / 1000, 0, 0.033);
    lastTime = now;
    if (running && !paused) update(dt);
    else justPressed.clear();
    render();
    requestAnimationFrame(loop);
  }

  window.addEventListener('keydown', (e) => {
    if (['ArrowLeft', 'ArrowRight', 'ArrowUp', 'Space'].includes(e.code)) e.preventDefault();
    if (e.code === 'KeyP') togglePause();
    if (e.code === 'KeyM') toggleMute();
    if (e.code === 'KeyR' && paused) reset();
    if (!keys.has(e.code)) justPressed.add(e.code);
    keys.add(e.code);
  });
  window.addEventListener('keyup', (e) => keys.delete(e.code));


  if (pauseButton) pauseButton.addEventListener('click', () => togglePause());
  if (muteButton) muteButton.addEventListener('click', () => toggleMute());

  function pressVirtualKey(code) {
    if (!keys.has(code)) justPressed.add(code);
    keys.add(code);
  }

  function releaseVirtualKey(code) {
    keys.delete(code);
  }

  document.querySelectorAll('[data-key]').forEach((button) => {
    const code = button.dataset.key;
    const down = (e) => {
      e.preventDefault();
      pressVirtualKey(code);
      button.setPointerCapture?.(e.pointerId);
    };
    const up = (e) => {
      e.preventDefault();
      releaseVirtualKey(code);
    };
    button.addEventListener('pointerdown', down);
    button.addEventListener('pointerup', up);
    button.addEventListener('pointercancel', up);
    button.addEventListener('pointerleave', up);
    button.addEventListener('contextmenu', (e) => e.preventDefault());
  });

  startButton.addEventListener('click', async () => {
    makeAudio();
    if (audio.ac.state !== 'running') await audio.ac.resume();
    running = true;
    paused = false;
    toggleMute(muted);
    setStatus('冒险中');
    overlay.classList.add('hidden');
  });

  reset();
  requestAnimationFrame(loop);
})();

</script>
</body>
</html>
