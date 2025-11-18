<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Happy Princess Day — Ishika</title>
  <style>
    :root{--bg:#0b1630;--accent:#f8b6d2;--gold:#f6d365}
    html,body{height:100%;margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial}
    .page{
      min-height:100%;background: radial-gradient(ellipse at 10% 10%, rgba(255,255,255,0.02), transparent 10%), linear-gradient(180deg,var(--bg),#0a1730 60%);
      color:whitesmoke;display:flex;align-items:center;justify-content:center;padding:32px;box-sizing:border-box;overflow:hidden
    }
    .card{
      width:900px;max-width:96%;background:linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.01));border-radius:20px;box-shadow:0 20px 50px rgba(2,6,23,0.7);overflow:hidden;position:relative;padding:28px;
      backdrop-filter: blur(6px);
    }
    /* header */
    .top{display:flex;gap:20px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:50%;background:linear-gradient(135deg,var(--accent),#ffd9e8);flex-shrink:0;display:grid;place-items:center;font-weight:700;color:#3b1f3b;font-size:38px;box-shadow:0 8px 20px rgba(0,0,0,0.4);}
    .title{flex:1}
    h1{margin:0;font-size:28px;letter-spacing:0.6px}
    p.subtitle{margin:4px 0 0;opacity:0.9}/* main content */
.main{display:flex;gap:24px;margin-top:18px;align-items:stretch}
.left{flex:1;padding:18px}
.right{width:360px;max-width:40%;display:flex;flex-direction:column;align-items:center;justify-content:center}

.message{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));border-radius:14px;padding:18px;line-height:1.5}
.message h2{margin:0 0 8px;font-size:20px;color:var(--gold)}

/* animated lanterns */
.scene{position:relative;height:300px;border-radius:12px;overflow:hidden;margin-top:14px;background:linear-gradient(180deg,#06102a 0%, #0b1630 60%);box-shadow:inset 0 30px 80px rgba(0,0,0,0.4)}
.lantern{position:absolute;width:18px;height:28px;border-radius:10px;background:linear-gradient(180deg,#ffd4a6,#ffb380);left:50%;transform:translateX(-50%);bottom:-60px;filter:drop-shadow(0 6px 12px rgba(0,0,0,0.3));animation:rise var(--t,10s) linear infinite}
.lantern::after{content:'';position:absolute;left:50%;top:-8px;width:2px;height:8px;background:rgba(255,255,255,0.2);transform:translateX(-50%)}
@keyframes rise{0%{transform:translateX(-50%) translateY(0) scale(0.9)}50%{transform:translateX(-40%) translateY(-140%) scale(1.02)}100%{transform:translateX(-60%) translateY(-280%) scale(0.95)} }

/* castle silhouette */
.castle{position:absolute;left:0;right:0;bottom:0;height:140px;background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));mask-image:linear-gradient(black,transparent);display:flex;align-items:flex-end;justify-content:center}
.castle svg{width:100%;height:140px;opacity:0.9}

/* QR box */
.qrbox{background:rgba(255,255,255,0.02);padding:14px;border-radius:12px;margin-top:8px;text-align:center}
button{background:linear-gradient(90deg,var(--accent),#ffd9e8);border:0;padding:10px 14px;border-radius:10px;font-weight:700;cursor:pointer;color:#3b1f3b}
.small{font-size:13px;opacity:0.95}

/* floating sparkles */
.sparkle{position:absolute;width:6px;height:6px;border-radius:50%;background:radial-gradient(circle,#fff,rgba(255,255,255,0.2));opacity:0.9;filter:blur(0.6px);animation:float 6s linear infinite}
@keyframes float{0%{transform:translateY(0) scale(0.9)}50%{transform:translateY(-30px) scale(1.1)}100%{transform:translateY(0) scale(0.9)} }

/* responsive */
@media (max-width:880px){.main{flex-direction:column}.right{max-width:none;width:100%}}

  </style>
</head>
<body>
  <div class="page">
    <div class="card" role="main">
      <div class="top">
        <div class="avatar">I</div>
        <div class="title">
          <h1>Happy Princess Day, Ishika ✨</h1>
          <p class="subtitle">A special message — crafted with a little magic and a lot of heart.</p>
        </div>
        <div style="text-align:right">
          <div class="small">Age: <strong>17</strong></div>
          <div class="small">From: <strong>Your best friend</strong></div>
        </div>
      </div><div class="main">
    <div class="left">
      <div class="message">
        <h2>To Ishika — my favourite princess</h2>
        <p>Hey Ishika,</p>
        <p>This little corner of the internet is for you — to celebrate the sunlight in your smile, the kindness in your heart, and the quiet courage you show every day. At 17, you already shine like a storybook princess: adventurous, warm, and endlessly curious. But more than that — you are my best friend, my confidante, and someone I adore deeply.</p>
        <p>We are more than friends — and in this gentle truth I find the happiest kind of magic. Thank you for every laugh, every late-night talk, every small moment that made me feel at home with you. Today I wish you a day full of sparkles, soft songs, and a thousand tiny wonders.</p>
        <p style="margin-top:10px;font-weight:700">With all my love — always,</p>
        <p style="margin:0.25em 0 0;font-weight:800">❤️ (yours)</p>
      </div>

      <div class="scene" aria-hidden="true">
        <!-- animated lanterns -->
        <div class="lantern" style="left:12%;--t:13s"></div>
        <div class="lantern" style="left:30%;--t:10s"></div>
        <div class="lantern" style="left:48%;--t:12s"></div>
        <div class="lantern" style="left:68%;--t:11s"></div>
        <div class="lantern" style="left:84%;--t:14s"></div>

        <!-- sparkle dots -->
        <div class="sparkle" style="left:14%;bottom:120px;animation-duration:5s"></div>
        <div class="sparkle" style="left:32%;bottom:60px;animation-duration:6s"></div>
        <div class="sparkle" style="left:62%;bottom:150px;animation-duration:4.5s"></div>
        <div class="sparkle" style="left:78%;bottom:90px;animation-duration:6.2s"></div>

        <div class="castle">
          <!-- simple silhouette castle (Rapunzel-inspired tall towers, but original) -->
          <svg viewBox="0 0 1600 300" preserveAspectRatio="xMidYMax slice" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
            <defs>
              <linearGradient id="g1" x1="0" x2="0" y1="0" y2="1">
                <stop offset="0" stop-color="#ffe6c6" stop-opacity="0.06"></stop>
                <stop offset="1" stop-color="#ffd9e8" stop-opacity="0.02"></stop>
              </linearGradient>
            </defs>
            <rect width="1600" height="300" fill="url(#g1)"></rect>
            <g fill="#0b2a4d">
              <rect x="120" y="80" width="120" height="220" rx="6"></rect>
              <polygon points="160,40 120,80 200,80"/>
              <rect x="320" y="110" width="80" height="190" rx="4"></rect>
              <polygon points="360,60 320,110 400,110"/>
              <rect x="460" y="40" width="180" height="260" rx="8"></rect>
              <polygon points="540,8 490,40 590,40"/>
              <rect x="700" y="100" width="60" height="150" rx="4"></rect>
              <rect x="820" y="80" width="140" height="170" rx="6"></rect>
              <rect x="1020" y="120" width="100" height="130" rx="4"></rect>
              <polygon points="1100,70 1040,120 1160,120"/>
              <rect x="1260" y="90" width="200" height="160" rx="6"></rect>
            </g>
          </svg>
        </div>

      </div>
    </div>

    <div class="right">
      <div style="width:100%;text-align:center">
        <div style="font-weight:800;margin-bottom:8px">A little royal keepsake</div>
        <div class="qrbox">
          <img id="qr" alt="QR code" style="width:180px;height:180px;border-radius:8px;background:#fff;padding:8px;display:block;margin:0 auto 8px" src="data:,"/>
          <div class="small">Scan to open this message (when hosted online)</div>
          <div style="height:8px"></div>
          <button id="makeQR">Generate QR for this page</button>
          <div style="height:12px"></div>
          <button id="downloadPNG">Download card as PNG</button>
          <div style="height:10px"></div>
          <div class="small" style="opacity:0.85;margin-top:8px">Tip: host this file (GitHub Pages / Netlify) — then regenerate QR to point visitors to the hosted URL.</div>
        </div>
      </div>
    </div>
  </div>

</div>

  </div>  <script>
    // Generate QR image using qrserver API (works if page is hosted online)
    document.getElementById('makeQR').addEventListener('click', function(){
      const url = location.href;
      const api = 'https://api.qrserver.com/v1/create-qr-code/?size=400x400&data=' + encodeURIComponent(url);
      document.getElementById('qr').src = api;
      this.textContent = 'QR generated for this URL';
    });

    // Download PNG snapshot of the card using HTMLCanvas
    document.getElementById('downloadPNG').addEventListener('click', async function(){
      const card = document.querySelector('.card');
      const rect = card.getBoundingClientRect();
      // Create a canvas scaled for high DPI
      const scale = 2;
      const canvas = document.createElement('canvas');
      canvas.width = Math.round(rect.width * scale);
      canvas.height = Math.round(rect.height * scale);
      const ctx = canvas.getContext('2d');

      // Inline render: use foreignObject to draw the card's HTML into an SVG, then into canvas.
      const svg = `<?xml version="1.0" encoding="utf-8"?>
        <svg xmlns='http://www.w3.org/2000/svg' width='${rect.width}' height='${rect.height}'>
          <foreignObject width='100%' height='100%'>
            ${new XMLSerializer().serializeToString(card.cloneNode(true)).replace(/#/g,'%23')}
          </foreignObject>
        </svg>`;

      // Note: Some browsers restrict cross-origin fonts/styles; this produces a reasonable result in modern browsers.
      const img = new Image();
      const svgBlob = new Blob([svg], {type: 'image/svg+xml;charset=utf-8'});
      const url = URL.createObjectURL(svgBlob);
      img.onload = function(){
        ctx.scale(scale, scale);
        ctx.drawImage(img, 0, 0);
        URL.revokeObjectURL(url);
        canvas.toBlob(function(blob){
          const a = document.createElement('a');
          a.download = 'PrincessDay_Ishika.png';
          a.href = URL.createObjectURL(blob);
          a.click();
          URL.revokeObjectURL(a.href);
        });
      };
      img.onerror = function(){
        alert('Snapshot failed in this browser. Try using Chrome or Firefox, or take a screenshot as fallback.');
      };
      img.src = url;
    });

    // soft automatic QR attempt (if hosted)
    window.addEventListener('load', function(){
      // only auto-gen if url looks like http(s)
      if(location.protocol.startsWith('http')){
        document.getElementById('makeQR').click();
      } else {
        // show placeholder QR with short note
        document.getElementById('qr').alt = 'Generate QR after hosting this page';
      }
    });
  </script></body>
</html>
