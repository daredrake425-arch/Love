<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Message For You</title>
<style>
  * { margin:0; padding:0; box-sizing:border-box; font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif; }
  html, body { height: 100%; overflow: hidden; }

  body {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #05060a;
    perspective: 1400px;
    color: #fff;
    font-weight: 400;
    -webkit-font-smoothing: antialiased;
  }

  .bg {
    position: fixed;
    inset: 0;
    z-index: 0;
    background:
      radial-gradient(ellipse 80% 60% at 50% 0%, rgba(108, 92, 231, 0.28), transparent 60%),
      radial-gradient(ellipse 70% 50% at 100% 100%, rgba(232, 67, 147, 0.22), transparent 60%),
      radial-gradient(ellipse 60% 50% at 0% 100%, rgba(9, 132, 227, 0.18), transparent 60%),
      linear-gradient(180deg, #05060a 0%, #0a0b14 100%);
  }

  .grid-floor {
    position: fixed;
    bottom: 0; left: 0; right: 0;
    height: 55vh;
    z-index: 1;
    background-image:
      linear-gradient(rgba(120, 130, 200, 0.18) 1px, transparent 1px),
      linear-gradient(90deg, rgba(120, 130, 200, 0.18) 1px, transparent 1px);
    background-size: 70px 70px;
    transform: perspective(500px) rotateX(65deg);
    transform-origin: bottom center;
    mask-image: linear-gradient(to top, black 0%, transparent 90%);
    -webkit-mask-image: linear-gradient(to top, black 0%, transparent 90%);
    animation: gridMove 20s linear infinite;
  }
  @keyframes gridMove {
    0% { background-position: 0 0, 0 0; }
    100% { background-position: 0 70px, 70px 0; }
  }

  .particle {
    position: fixed;
    width: 3px; height: 3px;
    border-radius: 50%;
    background: rgba(180, 190, 255, 0.7);
    box-shadow: 0 0 8px rgba(150, 160, 255, 0.9), 0 0 16px rgba(150, 160, 255, 0.4);
    z-index: 2;
    pointer-events: none;
    animation: particleFloat linear infinite;
  }
  @keyframes particleFloat {
    0% { transform: translateY(100vh); opacity: 0; }
    10% { opacity: 1; }
    90% { opacity: 1; }
    100% { transform: translateY(-80px); opacity: 0; }
  }

  .orb {
    position: fixed;
    border-radius: 50%;
    filter: blur(110px);
    opacity: 0.4;
    z-index: 1;
    pointer-events: none;
    animation: orbDrift 28s ease-in-out infinite;
  }
  .orb-1 { width: 480px; height: 480px; background: #6c5ce7; top: -140px; left: -120px; }
  .orb-2 { width: 420px; height: 420px; background: #e84393; bottom: -160px; right: -120px; animation-delay: -9s; }
  .orb-3 { width: 360px; height: 360px; background: #0984e3; top: 42%; right: 8%; animation-delay: -18s; }
  @keyframes orbDrift {
    0%, 100% { transform: translate(0, 0) scale(1); }
    33% { transform: translate(60px, -50px) scale(1.12); }
    66% { transform: translate(-50px, 60px) scale(0.92); }
  }

  .scene {
    position: relative;
    z-index: 10;
    transform-style: preserve-3d;
  }

  .card {
    position: relative;
    width: 92%;
    max-width: 520px;
    padding: 60px 48px;
    border-radius: 28px;
    background: linear-gradient(135deg, rgba(28, 30, 48, 0.85) 0%, rgba(18, 19, 30, 0.9) 100%);
    backdrop-filter: blur(30px) saturate(150%);
    -webkit-backdrop-filter: blur(30px) saturate(150%);
    border: 1px solid rgba(255, 255, 255, 0.09);
    text-align: center;
    transform-style: preserve-3d;
    transition: transform 0.4s cubic-bezier(.2,.8,.2,1), box-shadow 0.4s ease;
    animation: cardIn 1s cubic-bezier(.2,.8,.2,1);
    box-shadow:
      0 40px 100px -20px rgba(0, 0, 0, 0.9),
      0 20px 50px -10px rgba(108, 92, 231, 0.35),
      inset 0 1px 0 rgba(255, 255, 255, 0.1),
      inset 0 -1px 0 rgba(0, 0, 0, 0.4),
      0 0 0 1px rgba(255, 255, 255, 0.04);
  }

  @keyframes cardIn {
    0% { opacity: 0; transform: translateY(40px) rotateX(8deg) scale(0.94); }
    100% { opacity: 1; transform: translateY(0) rotateX(0) scale(1); }
  }

  .card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 45%;
    border-radius: 28px 28px 60% 60% / 28px 28px 30% 30%;
    background: linear-gradient(180deg, rgba(255, 255, 255, 0.08), transparent);
    pointer-events: none;
  }

  .card::after {
    content: '';
    position: absolute;
    top: -1px; left: 50%;
    transform: translateX(-50%);
    width: 100px; height: 1.5px;
    background: linear-gradient(90deg, transparent, #8b7eff, #fd79a8, transparent);
    border-radius: 2px;
    box-shadow: 0 0 20px rgba(139, 126, 255, 0.8);
  }

  .label, h1, p.subtitle, #nameInput, .buttons, .final-msg, .sent-msg {
    transform: translateZ(30px);
  }

  .label {
    display: inline-block;
    font-size: 10.5px;
    letter-spacing: 4px;
    text-transform: uppercase;
    color: rgba(255, 255, 255, 0.4);
    font-weight: 600;
    margin-bottom: 28px;
  }

  h1 {
    font-size: 30px;
    font-weight: 600;
    letter-spacing: -0.6px;
    line-height: 1.35;
    margin-bottom: 16px;
    color: #fff;
  }
  h1 .accent {
    background: linear-gradient(135deg, #a29bfe 0%, #fd79a8 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  p.subtitle {
    color: rgba(255, 255, 255, 0.55);
    font-size: 15px;
    line-height: 1.65;
    margin-bottom: 34px;
    font-weight: 400;
  }

  #nameInput {
    padding: 17px 24px;
    font-size: 15px;
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 14px;
    width: 100%;
    outline: none;
    text-align: center;
    margin-bottom: 22px;
    transition: all 0.3s ease;
    font-family: inherit;
    background: rgba(0, 0, 0, 0.35);
    color: #fff;
    letter-spacing: 0.3px;
    box-shadow:
      inset 0 2px 8px rgba(0, 0, 0, 0.6),
      0 1px 0 rgba(255, 255, 255, 0.05);
  }
  #nameInput::placeholder { color: rgba(255, 255, 255, 0.3); }
  #nameInput:focus {
    border-color: rgba(139, 126, 255, 0.6);
    background: rgba(0, 0, 0, 0.5);
    box-shadow:
      inset 0 2px 8px rgba(0, 0, 0, 0.6),
      0 0 0 4px rgba(139, 126, 255, 0.12),
      0 0 30px rgba(139, 126, 255, 0.35);
  }

  .buttons {
    display: flex;
    gap: 14px;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 8px;
  }

  button {
    padding: 16px 40px;
    font-size: 15px;
    font-weight: 600;
    letter-spacing: 0.3px;
    border: none;
    border-radius: 14px;
    cursor: pointer;
    transition: all 0.25s cubic-bezier(.2,.8,.2,1);
    font-family: inherit;
  }

  .yes-btn {
    background: linear-gradient(135deg, #6c5ce7 0%, #a29bfe 50%, #fd79a8 100%);
    color: white;
    box-shadow:
      0 6px 0 #4a3fb5,
      0 14px 30px -6px rgba(108, 92, 231, 0.7),
      0 25px 60px -10px rgba(253, 121, 168, 0.5),
      inset 0 1px 0 rgba(255, 255, 255, 0.3);
  }
  .yes-btn:hover {
    transform: translateY(-3px);
    box-shadow:
      0 9px 0 #4a3fb5,
      0 20px 40px -6px rgba(108, 92, 231, 0.9),
      0 35px 70px -10px rgba(253, 121, 168, 0.7);
  }
  .yes-btn:active {
    transform: translateY(4px);
    box-shadow: 0 2px 0 #4a3fb5, 0 6px 15px -4px rgba(108, 92, 231, 0.7);
  }

  .no-btn {
    background: rgba(255, 255, 255, 0.05);
    color: rgba(255, 255, 255, 0.65);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow:
      0 4px 0 rgba(0, 0, 0, 0.4),
      0 10px 25px -8px rgba(0, 0, 0, 0.6);
  }
  .no-btn:hover {
    color: white;
    background: rgba(255, 255, 255, 0.08);
    transform: translateY(-2px);
  }
  .no-btn:active {
    transform: translateY(3px);
    box-shadow: 0 1px 0 rgba(0, 0, 0, 0.4);
  }

  #typeText {
    color: rgba(255, 255, 255, 0.9);
    font-size: 17px;
    font-weight: 500;
    min-height: 70px;
    margin: 20px 0 24px;
    line-height: 1.7;
  }
  .cursor {
    display: inline-block;
    width: 2px;
    height: 20px;
    background: #a29bfe;
    animation: blink 1s infinite;
    vertical-align: middle;
    margin-left: 3px;
    box-shadow: 0 0 10px #a29bfe;
  }
  @keyframes blink { 50% { opacity: 0; } }

  .final-msg {
    font-size: 17px;
    font-weight: 500;
    margin-top: 20px;
    line-height: 1.9;
    color: rgba(255, 255, 255, 0.85);
  }
  .final-msg .highlight {
    background: linear-gradient(135deg, #a29bfe, #fd79a8);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    font-weight: 600;
  }

  .ig-icon {
    width: 84px;
    height: 84px;
    margin: 0 auto 24px;
    border-radius: 24px;
    background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow:
      0 20px 40px -10px rgba(220, 39, 67, 0.5),
      0 0 0 1px rgba(255, 255, 255, 0.1) inset;
    animation: igPulse 2s ease-in-out infinite;
  }
  @keyframes igPulse {
    0%, 100% { transform: scale(1); box-shadow: 0 20px 40px -10px rgba(220, 39, 67, 0.5); }
    50% { transform: scale(1.05); box-shadow: 0 25px 50px -10px rgba(220, 39, 67, 0.8); }
  }
  .ig-icon svg { width: 46px; height: 46px; fill: white; }

  .sent-msg {
    font-size: 15px;
    line-height: 1.8;
    color: rgba(255, 255, 255, 0.7);
    margin: 20px 0;
  }

  .copied-box {
    background: rgba(139, 126, 255, 0.12);
    border: 1px solid rgba(139, 126, 255, 0.3);
    border-radius: 12px;
    padding: 14px 18px;
    margin: 18px 0;
    font-size: 13.5px;
    color: rgba(255, 255, 255, 0.85);
    line-height: 1.7;
  }
  .copied-box strong { color: #a29bfe; font-weight: 600; }

  .hidden { display: none !important; }

  .confetti {
    position: fixed;
    width: 10px; height: 10px;
    top: -20px;
    z-index: 999;
    pointer-events: none;
    animation: confettiFall 3.2s linear forwards;
  }
  @keyframes confettiFall {
    0% { transform: translateY(0) rotate(0) scale(1); opacity: 1; }
    100% { transform: translateY(105vh) rotate(900deg) scale(0.6); opacity: 0; }
  }

  .music-btn {
    position: fixed;
    top: 24px; right: 24px;
    width: 48px; height: 48px;
    border-radius: 12px;
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(20px);
    color: rgba(255, 255, 255, 0.75);
    cursor: pointer;
    z-index: 100;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0;
    box-shadow: 0 8px 24px -8px rgba(0, 0, 0, 0.7);
  }
  .music-btn:hover {
    background: rgba(255, 255, 255, 0.09);
    color: white;
    border-color: rgba(139, 126, 255, 0.5);
  }
  .music-btn svg { width: 20px; height: 20px; fill: currentColor; }
  .wave { display: none; gap: 2px; align-items: flex-end; height: 18px; }
  .music-btn.playing .icon-mute { display: none; }
  .music-btn.playing .wave { display: flex; }
  .wave span {
    display: block; width: 3px;
    background: currentColor;
    border-radius: 1px;
    animation: waveAnim 0.9s ease-in-out infinite;
  }
  .wave span:nth-child(1) { animation-delay: 0s; height: 8px; }
  .wave span:nth-child(2) { animation-delay: 0.15s; height: 16px; }
  .wave span:nth-child(3) { animation-delay: 0.3s; height: 10px; }
  .wave span:nth-child(4) { animation-delay: 0.45s; height: 14px; }
  @keyframes waveAnim { 0%, 100% { transform: scaleY(0.5); } 50% { transform: scaleY(1); } }

  .spinner {
    width: 24px; height: 24px;
    border: 2px solid rgba(255,255,255,0.15);
    border-top-color: #a29bfe;
    border-radius: 50%;
    margin: 20px auto;
    animation: spin 0.8s linear infinite;
  }
  @keyframes spin { to { transform: rotate(360deg); } }

  @media (max-width: 480px) {
    .card { padding: 44px 26px; }
    h1 { font-size: 24px; }
    p.subtitle { font-size: 14px; }
    button { padding: 14px 30px; font-size: 14px; }
    .music-btn { width: 42px; height: 42px; top: 16px; right: 16px; }
  }
</style>
</head>
<body>

<div class="bg"></div>
<div class="grid-floor"></div>
<div class="orb orb-1"></div>
<div class="orb orb-2"></div>
<div class="orb orb-3"></div>

<button class="music-btn" id="musicBtn" onclick="toggleMusic()" title="Toggle music">
  <svg class="icon-mute" viewBox="0 0 24 24"><path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"/></svg>
  <div class="wave"><span></span><span></span><span></span><span></span></div>
</button>

<audio id="bgMusic" loop>
  <source src="song.mp3" type="audio/mpeg">
</audio>

<!-- Step 1 -->
<div class="scene" id="scene1">
  <div class="card" id="step1">
    <span class="label">A Personal Note</span>
    <h1>There's something<br>I want to tell you</h1>
    <p class="subtitle">Enter your name to continue.</p>
    <input type="text" id="nameInput" placeholder="Your name" maxlength="20" autocomplete="off">
    <div class="buttons">
      <button class="yes-btn" onclick="startSurprise()">Continue</button>
    </div>
  </div>
</div>

<!-- Step 2 -->
<div class="scene hidden" id="scene2">
  <div class="card" id="step2">
    <span class="label">For You</span>
    <h1>Hey <span class="accent" id="displayName"></span></h1>
    <p id="typeText"></p>
    <div class="buttons">
      <button class="yes-btn" onclick="sayYes()">Yes</button>
      <button class="no-btn" id="noBtn" onmouseover="moveNo()" onclick="moveNo()">No</button>
    </div>
  </div>
</div>

<!-- Step 3: YES -->
<div class="scene hidden" id="scene3">
  <div class="card" id="step3">
    <div class="ig-icon">
      <svg viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zm0 10.162a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
    </div>
    <span class="label">Opening Instagram</span>
    <h1>Thank you, <span class="accent" id="displayName2"></span></h1>
    <div class="copied-box">
      <strong>Message copied to clipboard.</strong><br>
      Instagram is opening. Just paste it in the chat and send.
    </div>
    <div class="spinner" id="spinner"></div>
    <div class="buttons">
      <button class="yes-btn" id="igBtn">Open Instagram</button>
    </div>
  </div>
</div>

<!-- Step 4: NO -->
<div class="scene hidden" id="scene4">
  <div class="card" id="step4">
    <div class="ig-icon" style="background: linear-gradient(135deg, #6b7280 0%, #374151 100%); box-shadow: 0 20px 40px -10px rgba(107, 114, 128, 0.5);">
      <svg viewBox="0 0 24 24"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zm0 10.162a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"/></svg>
    </div>
    <span class="label">Opening Instagram</span>
    <h1>Understood, <span class="accent" id="displayName3"></span></h1>
    <div class="copied-box">
      <strong>Message copied to clipboard.</strong><br>
      Instagram is opening. Just paste it in the chat and send.
    </div>
    <div class="spinner" id="spinner2"></div>
    <div class="buttons">
      <button class="yes-btn" id="igBtn2" style="background: linear-gradient(135deg, #6b7280 0%, #374151 100%); box-shadow: 0 6px 0 #1f2937, 0 14px 30px -6px rgba(107, 114, 128, 0.7);">Open Instagram</button>
    </div>
  </div>
</div>

<script>
  /* ============================================================
     ⚙️  CONFIG
     ============================================================ */
  const YOUR_INSTAGRAM_USERNAME = "gecko.exe"; // ✅ Tumhara username set hai

  /* ============================================================
     Messages — customize as you like
     ============================================================ */
  const MSG_YES = "She said YES! ❤️";
  const MSG_NO  = "She said No. 💔";
  /* ============================================================ */

  // Particles
  function createParticle() {
    const p = document.createElement('div');
    p.className = 'particle';
    p.style.left = Math.random() * 100 + 'vw';
    p.style.animationDuration = (Math.random() * 8 + 10) + 's';
    const size = Math.random() * 2.5 + 1;
    p.style.width = p.style.height = size + 'px';
    p.style.opacity = Math.random() * 0.5 + 0.3;
    document.body.appendChild(p);
    setTimeout(() => p.remove(), 18000);
  }
  for (let i = 0; i < 10; i++) setTimeout(createParticle, i * 300);
  setInterval(createParticle, 1400);

  // Music
  const music = document.getElementById('bgMusic');
  const musicBtn = document.getElementById('musicBtn');
  let musicPlaying = false;

  function toggleMusic() {
    if (musicPlaying) {
      music.pause();
      musicBtn.classList.remove('playing');
    } else {
      music.volume = 0.5;
      music.play().catch(() => {});
      musicBtn.classList.add('playing');
    }
    musicPlaying = !musicPlaying;
  }

  let started = false;
  document.addEventListener('click', () => {
    if (!started && music.src) {
      music.volume = 0.5;
      music.play().then(() => {
        musicBtn.classList.add('playing');
        musicPlaying = true;
        started = true;
      }).catch(() => {});
    }
  }, { once: true });

  function startSurprise() {
    const name = document.getElementById('nameInput').value.trim();
    if (!name) { alert('Please enter your name.'); return; }
    document.getElementById('displayName').textContent = name;
    document.getElementById('displayName2').textContent = name;
    document.getElementById('displayName3').textContent = name;
    document.getElementById('scene1').classList.add('hidden');
    document.getElementById('scene2').classList.remove('hidden');
    typeWriter('You are the best thing that ever happened to me. Will you be mine?');
  }

  function typeWriter(text) {
    const el = document.getElementById('typeText');
    el.innerHTML = '';
    let i = 0;
    const cursor = '<span class="cursor"></span>';
    const timer = setInterval(() => {
      if (i < text.length) {
        el.innerHTML = text.substring(0, i + 1) + cursor;
        i++;
      } else {
        clearInterval(timer);
        el.innerHTML = text + cursor;
      }
    }, 50);
  }

  function moveNo() {
    const btn = document.getElementById('noBtn');
    const x = (Math.random() - 0.5) * 380;
    const y = (Math.random() - 0.5) * 280;
    btn.style.transform = `translate(${x}px, ${y}px)`;
  }

  // ===== Instagram DM open =====
  function openInstagramDM(message) {
    copyToClipboard(message);
    const url = `https://ig.me/m/${YOUR_INSTAGRAM_USERNAME}`;
    window.open(url, '_bl
