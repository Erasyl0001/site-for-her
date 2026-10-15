<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Как прошёл твой день</title>
<link href="https://fonts.googleapis.com/css2?family=Underdog&family=Marck+Script&display=swap" rel="stylesheet">
<style>
:root{
  --bg1:#f3dfc4; --bg2:#d9a46c; --ink:#4a2c17; --gold:#b8862f; --wine:#8c3b3b;
  box-sizing:border-box; padding-top:env(safe-area-inset-top,0px); padding-bottom:env(safe-area-inset-bottom,0px);
}
@media (prefers-color-scheme: dark){
  :root:not([data-theme="light"]){ --bg1:#3a2314; --bg2:#1c0f08; }
}
:root[data-theme="dark"]{ --bg1:#3a2314; --bg2:#1c0f08; }
*{box-sizing:border-box}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{
  margin:0; min-height:100vh; display:flex; align-items:center; justify-content:center; padding:28px 14px;
  background:radial-gradient(ellipse at 50% 30%, var(--bg1), var(--bg2)); color:var(--ink);
  font-family:'Marck Script', Georgia, serif; overflow-x:hidden;
}
.fly{position:fixed; width:6px; height:6px; border-radius:50%; background:#ffd479; box-shadow:0 0 12px 4px #ffc85a99; opacity:0; animation:fly 9s ease-in-out infinite; pointer-events:none}
@keyframes fly{0%{opacity:0; transform:translateY(0)}20%{opacity:.9}80%{opacity:.7}100%{opacity:0; transform:translateY(-120px) translateX(30px)}}

.scroll{width:min(560px,100%); position:relative}
.rod{height:16px; border-radius:10px; background:linear-gradient(#e8c97a,#b8862f 55%,#7a5518); box-shadow:0 4px 10px #0005; position:relative; z-index:2}
.rod::before,.rod::after{content:""; position:absolute; top:-3px; width:14px; height:22px; border-radius:6px; background:linear-gradient(#e8c97a,#8a6420)}
.rod::before{left:-8px}.rod::after{right:-8px}
.paper{
  max-height:0; overflow:hidden; margin:0 12px; transition:max-height 2.6s cubic-bezier(.3,.7,.2,1);
  background:
    radial-gradient(circle at 12% 18%, #c99a5a33 0 8%, transparent 9%),
    radial-gradient(circle at 85% 70%, #a8733a2e 0 10%, transparent 11%),
    linear-gradient(100deg,#e9cf9c,#f4e3bd 30%,#ecd3a0 70%,#dcb97c);
  box-shadow:inset 0 0 40px #8a5a2a66, 0 10px 24px #0004; color:var(--ink);
}
.open .paper{max-height:1800px}
.inner{padding:30px 26px 34px; opacity:0; transition:opacity 1.4s ease 1.6s}
.open .inner{opacity:1}
h1{font-family:'Underdog',Georgia,serif; font-weight:400; font-size:clamp(24px,6vw,32px); line-height:1.25; text-align:center; margin:0 0 6px; color:var(--wine)}
.sub{text-align:center; font-size:19px; margin:0 0 18px; opacity:.85}
.orn{text-align:center; color:var(--gold); letter-spacing:.4em; margin:0 0 14px}
textarea{
  width:100%; min-height:260px; resize:vertical; padding:16px 18px; font:inherit; font-size:21px; line-height:1.55; color:var(--ink);
  background:repeating-linear-gradient(transparent 0 31px, #8a5a2a40 31px 32px); background-attachment:local;
  border:2px solid #8a5a2a88; border-radius:6px; outline:none;
}
textarea:focus-visible,button:focus-visible{outline:3px solid var(--wine); outline-offset:2px}
textarea.shake{animation:shake .4s}
@keyframes shake{25%{transform:translateX(-6px)}75%{transform:translateX(6px)}}
button{font-family:'Underdog',Georgia,serif; font-size:19px; cursor:pointer; border:2px solid #6b4a14; border-radius:8px; padding:11px 26px; color:#fff6e0;
  background:linear-gradient(#b8862f,#8a5f1c); box-shadow:0 3px 0 #5a3d0e, 0 6px 12px #0003; transition:transform .12s}
button:active{transform:translateY(2px)}
.row{display:flex; justify-content:center; margin-top:16px}
#ask{display:none; margin-top:26px; padding-top:22px; border-top:2px dashed #8a5a2a77; text-align:center}
#ask.show{display:block; animation:pop .8s cubic-bezier(.3,1.5,.5,1)}
@keyframes pop{from{opacity:0; transform:scale(.85) translateY(14px)}to{opacity:1; transform:none}}
.q{font-size:clamp(25px,7vw,34px); color:var(--wine); margin:0 0 18px; line-height:1.3}
.choices{display:flex; flex-wrap:wrap; gap:12px; justify-content:center}
.choice{background:#fff6e0; color:var(--ink); border-color:#a8733a; box-shadow:0 3px 0 #a8733a}
.choice.on{background:var(--wine); color:#fff6e0; border-color:#5a2020; box-shadow:0 3px 0 #5a2020}
#send{display:none; margin-top:20px}
#send.show{display:inline-block; animation:pop .6s}
.note{font-size:16px; margin-top:12px; min-height:22px; opacity:.85}
@media (prefers-reduced-motion:reduce){.paper,.inner{transition:none}.fly{display:none}}
</style>
</head>
<body>
<div class="scroll" id="scroll">
  <div class="rod"></div>
  <div class="paper">
    <div class="inner">
      <h1>Как прошёл сегодня Форум?</h1>
      <p class="sub">Расскажи мне всё-всё, не торопись</p>
      <div class="orn">❦ ❦ ❦</div>
      <textarea id="answer" placeholder="Что было самым интересным? Кого встретила? Что запомнилось, понравилось, устала ли ты..."></textarea>
      <div class="row"><button id="save">Сохранить</button></div>

      <div id="ask">
        <p class="q">I'm embarrassed to say this...but can i hug you tomoroow? 🥹</p>
        <div class="choices">
          <button class="choice" data-v="Давай ">Давай </button>
          <button class="choice" data-v="Я бы отказалась ">Я бы отказалась </button>
        </div>
        <button id="send">Отправить</button>
        <div class="note" id="note"></div>
      </div>
    </div>
  </div>
  <div class="rod"></div>
</div>

<script>
// Номер WhatsApp в международном формате, только цифры (например "77011234567").
// Если оставить пустым, WhatsApp откроется с выбором контакта.
const PHONE = "";
const QUESTION = "Как прошёл сегодня Форум?";
const HUG = "I'm embarrassed to say this...but can i hug you tomoroow? 🥹";

for(let i=0;i<14;i++){
  const f=document.createElement('div'); f.className='fly';
  f.style.left=Math.random()*100+'vw'; f.style.top=(30+Math.random()*65)+'vh';
  f.style.animationDelay=(Math.random()*9)+'s'; f.style.animationDuration=(7+Math.random()*5)+'s';
  document.body.appendChild(f);
}
setTimeout(()=>document.getElementById('scroll').classList.add('open'),500);

const $=id=>document.getElementById(id);
let choice="";
try{ const s=localStorage.getItem('forum_answer'); if(s) $('answer').value=s; }catch(e){}

$('save').onclick=()=>{
  const t=$('answer').value.trim();
  if(!t){ const a=$('answer'); a.classList.remove('shake'); void a.offsetWidth; a.classList.add('shake'); a.focus(); return; }
  try{ localStorage.setItem('forum_answer',t); }catch(e){}
  $('ask').classList.add('show');
  $('ask').scrollIntoView({behavior:'smooth',block:'center'});
};

document.querySelectorAll('.choice').forEach(b=>b.onclick=()=>{
  document.querySelectorAll('.choice').forEach(x=>x.classList.remove('on'));
  b.classList.add('on'); choice=b.dataset.v;
  $('send').classList.add('show');
});

async function copy(text){
  try{ await navigator.clipboard.writeText(text); return true; }catch(e){
    try{ const t=document.createElement('textarea'); t.value=text; document.body.appendChild(t); t.select(); const ok=document.execCommand('copy'); t.remove(); return ok; }catch(_){ return false; }
  }
}

$('send').onclick=()=>{
  if(!choice) return;
  const text = "❓ "+QUESTION+"\n💬 Мой ответ: "+$('answer').value.trim()+"\n\n❓ "+HUG+"\n💬 Мой ответ: "+choice;
  copy(text);
  const url="https://wa.me/"+PHONE+"?text="+encodeURIComponent(text);
  const a=document.createElement('a'); a.href=url; a.target="_blank"; a.rel="noopener";
  document.body.appendChild(a); a.click(); a.remove();
  $('note').textContent="Текст скопирован и уже ждёт тебя в WhatsApp 💌";
};
</script>
</body>
</html>
