[neon_kfc_link_xuanxuan_content (2).html](https://github.com/user-attachments/files/22402180/neon_kfc_link_xuanxuan_content.2.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KFC代付 · 霓虹动画</title>
  <style>
    :root{
      --bg:#0a0b0f;
      --neon1:#00fff0;
      --neon2:#ff3df5;
      --neon3:#00d1ff;
      --txt:#eaffff;
    }
    html,body{
      height:100%;
      margin:0;
      background: radial-gradient(1200px 800px at 50% 40%, #141729 0%, #0d0f1a 40%, var(--bg) 100%);
      color:var(--txt);
      font-family: "HarmonyOS Sans", "PingFang SC", "Segoe UI", Roboto, Helvetica, Arial, "Noto Sans SC", "Microsoft YaHei", sans-serif;
      overflow:hidden;
    }
    .wrap{
      position:relative;
      height:100%;
      display:grid;
      place-items:center;
      isolation:isolate;
    }
    .neon{
      font-size: clamp(36px, 10vw, 132px);
      font-weight: 800;
      letter-spacing: .05em;
      background: linear-gradient(130deg, var(--neon1), var(--neon2) 40%, var(--neon3));
      -webkit-background-clip:text;
      background-clip:text;
      color: transparent;
      text-shadow:
        0 0 6px rgba(255,255,255,.5),
        0 0 14px var(--neon1),
        0 0 26px var(--neon2),
        0 0 48px var(--neon2),
        0 0 84px var(--neon3);
      animation: glow 3.2s ease-in-out infinite, flicker 8s linear infinite;
      will-change: filter, text-shadow, transform;
      filter: drop-shadow(0 0 6px rgba(0,255,255,.35)) drop-shadow(0 0 14px rgba(255,61,245,.25));
    }
    .particles{
      position:absolute; inset:0;
      pointer-events:none;
      overflow:hidden;
      mix-blend-mode:screen;
    }
    .bubble{
      position:absolute;
      width: clamp(6px, 1.2vw, 14px);
      height: clamp(6px, 1.2vw, 14px);
      border-radius:50%;
      background: radial-gradient(circle at 30% 30%, #fff, var(--neon1) 60%, transparent 70%);
      opacity:.35;
      animation: rise linear infinite;
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="neon" aria-label="轩轩暴富暴美">轩轩暴富暴美</div>
    <div class="particles" id="particles"></div>
  </div>

  <script>
    const container = document.getElementById('particles');
    const W = window.innerWidth, H = window.innerHeight;
    const COUNT = Math.min(80, Math.floor((W*H)/18000));
    for(let i=0;i<COUNT;i++){
      const b = document.createElement('span');
      b.className='bubble';
      const size = 6 + Math.random()*12;
      b.style.width = size+'px';
      b.style.height = size+'px';
      b.style.left = (Math.random()*100)+'%';
      b.style.top = (70 + Math.random()*30)+'%';
      b.style.animationDuration = (8 + Math.random()*12)+'s';
      b.style.animationDelay = (-Math.random()*8)+'s';
      const hue = Math.random();
      const c1 = hue<.33? 'var(--neon1)': (hue<.66? 'var(--neon2)': 'var(--neon3)');
      b.style.background = `radial-gradient(circle at 30% 30%, #fff, ${c1} 60%, transparent 70%)`;
      container.appendChild(b);
    }
    const style = document.createElement('style');
    style.textContent = `
      @keyframes glow{
        0%,100%{
          text-shadow:
            0 0 6px rgba(255,255,255,.45),
            0 0 14px var(--neon1),
            0 0 26px var(--neon2),
            0 0 48px var(--neon2),
            0 0 84px var(--neon3);
          transform: translateY(0);
        }
        50%{
          text-shadow:
            0 0 10px rgba(255,255,255,.65),
            0 0 20px var(--neon1),
            0 0 40px var(--neon2),
            0 0 70px var(--neon2),
            0 0 120px var(--neon3);
          transform: translateY(-1px);
        }
      }
      @keyframes flicker{
        0%, 2%, 4%, 8%, 100% { opacity: 1; }
        1% { opacity: .92; }
        3% { opacity: .85; }
        5% { opacity: .96; }
        7% { opacity: .88; }
      }
      @keyframes rise{
        from { transform: translateY(0) translateX(0); opacity:.0; }
        10% { opacity:.4; }
        90% { opacity:.35; }
        to { transform: translateY(-120vh) translateX(8vw); opacity:0; }
      }
    `;
    document.head.appendChild(style);

    let t;
    window.addEventListener('pointerdown', ()=>{
      const el = document.querySelector('.neon');
      el.style.animation = 'glow .9s ease-in-out 1, flicker .9s linear 1';
      clearTimeout(t);
      t = setTimeout(()=>{
        el.style.animation = 'glow 3.2s ease-in-out infinite, flicker 8s linear infinite';
      }, 900);
    });
  </script>
</body>
</html>
