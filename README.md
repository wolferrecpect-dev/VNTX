<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Team VNTX — الموقع الرسمي</title>
<style>
:root{
    --purple1:#4b0082; 
    --purple2:#8a2be2; 
    --purple3:#b794ff; 
    --surface:rgba(255,255,255,.08); 
    --surface2:rgba(255,255,255,.14);
    --dark-purple:#2a0055;
}
*{box-sizing:border-box}
body{
    margin:0;
    font-family:'Cairo',system-ui,sans-serif;
    color:#fff;
    background: linear-gradient(120deg,var(--purple1),var(--purple2) 50%,var(--purple3));
    text-align:center;
    scroll-behavior: smooth;
}
header{
    position:sticky;
    top:0;
    z-index:50;
    background:rgba(0,0,0,.45);
    backdrop-filter:blur(10px);
    padding:14px 6vw;
    display:flex;
    align-items:center;
    justify-content:space-between;
    border-bottom:1px solid rgba(255,255,255,.08)
}
header h1{margin:0;font-size:1.25rem;letter-spacing:.5px}
.btn{
    display:inline-block;
    padding:10px 18px;
    border-radius:999px;
    background:var(--purple2);
    color:#fff;
    text-decoration:none;
    font-weight:800;
    transition:.25s;
}
.btn:hover{
    transform:translateY(-2px);
    box-shadow:0 10px 30px rgba(138,43,226,.35);
}
section{
    padding:70px 6vw; 
    opacity:0; 
    transform: translateY(20px); 
    transition: all 0.6s ease-out;
}
section.show{opacity:1; transform: translateY(0);}
.title{font-size:2rem;margin-bottom:8px}
.subtitle{opacity:.9;color:#e9ddff;margin:0 0 24px}
.stats{display:flex;gap:18px;justify-content:center;flex-wrap:wrap}
.stat{min-width:200px;background:var(--surface);border:1px solid rgba(255,255,255,.08);border-radius:16px;padding:16px}
.stat .num{font-size:2.2rem;font-weight:900;color:var(--dark-purple)}
.grid{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(220px,1fr))}
.card{background:var(--surface);border:1px solid rgba(255,255,255,.08);border-radius:50%;padding:14px;transition:.25s;min-height:300px; display:flex; flex-direction:column; justify-content:flex-start;}
.card:hover{transform:translateY(-4px);background:var(--surface2);box-shadow:0 10px 24px rgba(138,43,226,.2)}
.card img{
    width: 100%;
    height: 100%;
    aspect-ratio: 1/1;
    object-fit: cover;
    border-radius: 50%;
    background:#3a2a6a;
    display:block;
}
.role{color:#cdb8ff;font-weight:700;margin-top:6px}
.name{font-weight:900;font-size:1.1rem;margin:6px 0 2px}
.tiktok{display:inline-flex;align-items:center;gap:8px;color:#fff;text-decoration:none;font-weight:800;opacity:.9;margin-top:auto}
.tiktok:hover{opacity:1}
iframe{width:100%;height:310px;border:none;border-radius:16px;box-shadow:0 10px 24px rgba(0,0,0,.25)}
.videos{display:grid;gap:18px;grid-template-columns:repeat(auto-fit,minmax(300px,1fr))}
.socials{display:flex;justify-content:center;gap:14px;flex-wrap:wrap}
.socials a{
    width:auto;
    min-width:160px;
    padding:10px 14px;
    border-radius:12px;
    display:grid;
    place-items:center;
    background:var(--surface);
    border:1px solid rgba(255,255,255,.08);
    color:#fff;
    text-decoration:none;
    transition:.2s;
    font-weight:800;
}
.socials a:hover{transform:translateY(-2px);background:var(--surface2)}
footer{padding:26px 6vw;border-top:1px solid rgba(255,255,255,.08);background:rgba(0,0,0,.35)}
@media(max-width:600px){iframe{height:220px}}
</style>
</head>
<body>

<audio autoplay loop src="https://www.youtube.com/watch?v=nY6a8yPaaP4"></audio>

<header>
    <h1>Team VNTX</h1>
    <a class="btn" href="https://discord.gg/vxtm" target="_blank">انضم للديسكورد</a>
</header>

<section id="welcome">
    <h2 class="title">مرحبًا بكم في الموقع الرسمي لفريق VNTX</h2>
</section>

<section id="stats">
    <h3 class="title">الإحصاءات</h3>
    <div class="stats">
        <div class="stat">
            <div id="members" class="num">0</div>
            <div>عدد الأعضاء</div>
        </div>
        <div class="stat">
            <div id="designers" class="num">0</div>
            <div>عدد المصممين</div>
        </div>
    </div>
</section>

<section id="owner">
    <h3 class="title">الأونر</h3>
    <div class="grid">
        <div class="card">
            <img src="https://i.postimg.cc/tCq5Dzyw/Screenshot-20250821-174424-com-zhiliaoapp-musically-Enlarge-Avatar-Activity.jpg" alt="ZDX">
            <div class="name">ZDX</div>
            <div class="role">Owner</div>
            <a class="tiktok" href="https://www.tiktok.com/@2zdx_?_t=ZS-8z3z41XY9hQ&_r=1" target="_blank">TikTok</a>
        </div>
    </div>
</section>

<section id="admins">
    <h3 class="title">المسؤولون</h3>
    <div class="grid">
        <div class="card"><img src="https://i.postimg.cc/4xMQfktR/Screenshot-20250821-174941-com-zhiliaoapp-musically-Enlarge-Avatar-Activity-edit-109884048851779.jpg"><div class="name">D7S</div><div class="role">مسؤول</div><a class="tiktok" href="https://www.tiktok.com/@.d7s6?_t=ZS-8z3z1WHUjEQ&_r=1">TikTok</a></div>
        <div class="card"><img src="https://i.postimg.cc/vB7rt4KG/Screenshot-20250821-175709-com-zhiliaoapp-musically-Enlarge-Avatar-Activity.jpg"><div class="name">A7N</div><div class="role">مسؤول</div><a class="tiktok" href="https://www.tiktok.com/@a7ns2?_t=ZS-8z3z2dCchRX&_r=1">TikTok</a></div>
        <div class="card"><img src="https://i.postimg.cc/htrhs9Dy/Screenshot-20250821-175030-com-zhiliaoapp-musically-Enlarge-Avatar-Activity.jpg"><div class="name">TKZ</div><div class="role">مسؤول</div><a class="tiktok" href="https://www.tiktok.com/@vdrb77hv?_t=ZS-8z3zD55YDxq&_r=1">TikTok</a></div>
    </div>
</section>

<section id="designers">
    <h3 class="title">المصممون</h3>
    <div class="grid">
        <div class="card"><img src="https://i.postimg.cc/NjGz9c5y/Screenshot-20250820-180635-com-zhiliaoapp-musically-Detail-Activity-edit-109896218536774.jpg"><div class="name">Wolfer</div><div class="role">مصمم</div><a class="tiktok" href="https://www.tiktok.com/@k2.wolfer?_t=ZS-8z3ywEYAvZa&_r=1">TikTok</a></div>
        <div class="card"><img src="https://i.postimg.cc/fRBYH3DK/Screenshot-20250821-175347-com-zhiliaoapp-musically-Enlarge-Avatar-Activit.jpg"><div class="name">MBR</div><div class="role">مصمم</div><a class="tiktok" href="https://www.tiktok.com/@ma13rt?_t=ZS-8z3zB9RqVgm&_r=1">TikTok</a></div>
        <div class="card"><img src="https://i.postimg.cc/sDC8zLSL/Screenshot-20250821-175415-com-zhiliaoapp-musically-Enlarge-Avatar-Activity.jpg"><div class="name">NSJ</div><div class="role">مصمم</div><a class="tiktok" href="https://www.tiktok.com/@.nsj__?_t=ZS-8z3zFSFMN6t&_r=1">TikTok</a></div>
        <div class="card"><img src="https://i.postimg.cc/8kjXLSd9/Screenshot-20250824-115852-com-zhiliaoapp-musically-Enlarge-Avatar-Activity.jpg"><div class="name">M7A</div><div class="role">مصمم</div><a class="tiktok" href="https://www.tiktok.com/@m7a.7lm?_t=ZS-8z8nFWfRAet&_r=1">TikTok</a></div>
        <div class="card"><img src="https://i.postimg.cc/mZCXmSqy/Screenshot-20250824-120427-com-zhiliaoapp-musically-Enlarge-Avatar-Activity.jpg"><div class="name">E7A</div><div class="role">مصمم</div><a class="tiktok" href="https://www.tiktok.com/@3mk.ark906?_t=ZS-8z8nGx1mqxz&_r=1">TikTok</a></div>
    </div>
</section>

<section id="videos">
    <h3 class="title">فيديوهات التصاميم</h3>
    <div class="videos">
        <iframe title="Design 1" src="https://www.youtube.com/embed/VVGyPEJR4N0" allowfullscreen></iframe>
        <iframe title="Design 2" src="https://www.youtube.com/embed/waxAvuCEQuk" allowfullscreen></iframe>
        <iframe title="Design 3" src="https://www.youtube.com/embed/aNvn0H4qsIM" allowfullscreen></iframe>
        <iframe title="Intro" src="https://www.youtube.com/embed/K5K0RIaLwKk" allowfullscreen></iframe>
    </div>
</section>

<section id="contact">
    <h3 class="title">تابعنا على حساباتنا</h3>
    <div class="socials">
        <a title="TikTok" href="https://www.tiktok.com/@teamvx1top" target="_blank">TikTok: teamvx1top</a>
        <a title="X" href="https://x.com/VntxT36007" target="_blank">X: VntxT36007</a>
        <a title="Telegram" href="https://t.me/teamvx1" target="_blank">Telegram: teamvx1</a>
        <a title="Discord" href="https://discord.gg/vxtm" target="_blank">Discord: https://discord.gg/vxtm</a>
    </div>
</section>

<footer>حقوق Team VNTX - فريق فنتكس</footer>

<script>
function animateCounter(id, end, duration){
    const el = document.getElementById(id);
    let n=0; 
    const step = Math.max(10, Math.floor(duration/Math.max(end,1)));
    const timer = setInterval(()=>{
        n++; 
        el.textContent=n; 
        if(n>=end) clearInterval(timer); 
    }, step);
}
animateCounter('members', 700, 1200);
animateCounter('designers', 100, 1200);

window.addEventListener('scroll', ()=>{
    document.querySelectorAll('section').forEach(sec=>{
        const top = sec.getBoundingClientRect().top;
        if(top < window.innerHeight - 50) sec.classList.add('show');
    });
});
</script>

</body>
</html>
