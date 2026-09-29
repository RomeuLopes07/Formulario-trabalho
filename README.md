<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Espaço de Beleza Nana Lopes | Sobrancelhas, Maquiagem e Depilação em Fortaleza</title>
<meta name="description" content="Há 5 anos elevando autoestimas. Design de sobrancelhas, maquiagem e depilação em Fortaleza - CE. Agende seu horário.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,500;0,600;1,500&family=Jost:wght@300;400;500&display=swap" rel="stylesheet">
<style>
:root{
  --green:#1B5745;
  --deep:#123D30;
  --gold:#C9A45C;
  --gold-soft:#E6D3A6;
  --cream:#FBF7EE;
  --sand:#F1E9D6;
  --ink:#1F2A26;
  --serif:'Cormorant Garamond',Georgia,serif;
  --sans:'Jost',system-ui,sans-serif;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:var(--sans);font-weight:300;font-size:17px;line-height:1.65;color:var(--ink);background:var(--cream)}
a{color:inherit}
:focus-visible{outline:2px solid var(--gold);outline-offset:3px}
.wrap{max-width:1040px;margin:0 auto;padding:0 24px}
h1,h2,h3{font-family:var(--serif);font-weight:500;line-height:1.1;color:var(--green)}
h2{font-size:clamp(2rem,5vw,3rem);margin-bottom:16px}
h3{font-size:1.55rem;margin-bottom:8px}
section{padding:88px 0}

.btn{display:inline-block;padding:15px 32px;border-radius:4px;background:var(--gold);color:var(--deep);text-decoration:none;font-weight:500;letter-spacing:.03em;transition:background .2s}
.btn:hover{background:var(--gold-soft)}
.btn.line{background:transparent;color:var(--gold-soft);border:1px solid var(--gold)}
.btn.line:hover{background:var(--gold);color:var(--deep)}

/* hero */
.hero{background:radial-gradient(120% 90% at 50% 0%,#2A7259 0%,var(--green) 45%,var(--deep) 100%);color:var(--cream);text-align:center;padding:64px 0 96px;position:relative;overflow:hidden}
.hero::before,.hero::after{content:"";position:absolute;top:-40px;width:180px;height:320px;border:1px solid rgba(201,164,92,.35);border-radius:0 100% 0 100%}
.hero::before{left:-70px;transform:rotate(-10deg)}
.hero::after{right:-70px;transform:scaleX(-1) rotate(-10deg)}
.tree{width:84px;height:auto;margin-bottom:10px}
.tree *{stroke:var(--gold);fill:none;stroke-width:2;stroke-linecap:round}
.tree .leaf{fill:var(--gold);stroke:none}
.brand{font-family:var(--serif);color:var(--gold);font-size:clamp(4rem,15vw,8rem);font-weight:500;line-height:.9;letter-spacing:.02em}
.brand span{display:block;font-size:.62em;margin-left:.9em}
.sub{margin-top:18px;letter-spacing:.42em;font-size:.85rem;color:var(--gold-soft);font-weight:400}
.hero h1{font-size:clamp(1.6rem,4vw,2.3rem);color:var(--cream);max-width:620px;margin:44px auto 30px;font-style:italic;font-weight:500}
.actions{display:flex;flex-wrap:wrap;gap:14px;justify-content:center}

/* serviços */
.lead{max-width:520px;margin-bottom:44px}
.list{border-top:1px solid var(--gold)}
.item{display:grid;grid-template-columns:.9fr 1.4fr;gap:24px;padding:32px 0;border-bottom:1px solid var(--gold-soft)}
.item p{max-width:480px}
@media(max-width:720px){.item{grid-template-columns:1fr;gap:6px}}

/* sobre */
.about{background:var(--sand)}
.about .wrap{display:grid;grid-template-columns:1fr 1fr;gap:56px;align-items:center}
.about p+p{margin-top:16px}
.years{background:var(--green);color:var(--cream);padding:44px 32px;text-align:center;border-radius:200px 200px 8px 8px}
.years strong{display:block;font-family:var(--serif);font-size:5.5rem;line-height:1;color:var(--gold);font-weight:500}
.years span{font-family:var(--serif);font-size:1.5rem;font-style:italic}
@media(max-width:820px){.about .wrap{grid-template-columns:1fr}}

/* cosméticos + diferenciais */
.points{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:36px;margin-top:36px}
.points div{border-left:2px solid var(--gold);padding-left:20px}
.points p{font-size:.98rem}

/* onde */
.where{background:var(--deep);color:var(--gold-soft)}
.where h2{color:var(--gold)}
.where .wrap{display:grid;grid-template-columns:1fr 1fr;gap:48px}
.where address{font-style:normal;font-size:1.15rem;margin:8px 0 26px;color:var(--cream)}
.where ul{list-style:none;display:grid;gap:10px}
.where a{color:var(--gold)}
@media(max-width:820px){.where .wrap{grid-template-columns:1fr}}

/* cta */
.cta{text-align:center}
.cta p{max-width:480px;margin:0 auto 30px}
.cta .btn{background:var(--green);color:var(--cream)}
.cta .btn:hover{background:var(--deep)}

footer{background:var(--deep);color:var(--gold-soft);border-top:1px solid rgba(201,164,92,.3);padding:32px 0 calc(32px + env(safe-area-inset-bottom,0px));font-size:.92rem;text-align:center}
footer a{color:var(--gold)}

.float{position:fixed;right:16px;bottom:calc(16px + env(safe-area-inset-bottom,0px));z-index:9;background:var(--gold);color:var(--deep);text-decoration:none;font-weight:500;padding:13px 22px;border-radius:999px;box-shadow:0 6px 18px rgba(0,0,0,.25)}
@media(prefers-reduced-motion:no-preference){.hero .tree{animation:rise 1.2s ease both}@keyframes rise{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:none}}}
</style>
</head>
<body>

<main>
<section class="hero">
  <div class="wrap">
    <svg class="tree" viewBox="0 0 80 90" aria-hidden="true">
      <path d="M40 88 V48"/><path d="M40 70 C30 66 24 60 20 54"/><path d="M40 70 C50 66 56 60 60 54"/>
      <path d="M40 58 C34 50 32 42 34 34"/><path d="M40 58 C46 50 48 42 46 34"/><path d="M40 48 V22"/>
      <path d="M30 88 C34 82 38 82 40 78 C42 82 46 82 50 88"/>
      <circle class="leaf" cx="40" cy="14" r="5"/><circle class="leaf" cx="28" cy="24" r="5"/><circle class="leaf" cx="52" cy="24" r="5"/>
      <circle class="leaf" cx="18" cy="42" r="5"/><circle class="leaf" cx="62" cy="42" r="5"/><circle class="leaf" cx="34" cy="30" r="4"/><circle class="leaf" cx="46" cy="30" r="4"/>
      <circle class="leaf" cx="20" cy="52" r="4"/><circle class="leaf" cx="60" cy="52" r="4"/>
    </svg>
    <div class="brand" role="heading" aria-level="2">Nana<span>Lopes</span></div>
    <p class="sub">ESPAÇO DE BELEZA</p>
    <h1>Há 5 anos, elevando autoestimas.</h1>
    <div class="actions">
      <a class="btn" href="https://wa.me/558598501929?text=Ol%C3%A1!%20Vim%20pelo%20site%20e%20quero%20agendar%20um%20hor%C3%A1rio%20no%20Espa%C3%A7o%20Nana%20Lopes." target="_blank" rel="noopener">Agendar pelo WhatsApp</a>
      <a class="btn line" href="#servicos">Conhecer os serviços</a>
    </div>
  </div>
</section>

<section id="servicos">
  <div class="wrap">
    <h2>Excelência em cada detalhe</h2>
    <p class="lead">Atendimento com técnica, cuidado e o tempo que você merece.</p>
    <div class="list">
      <div class="item">
        <h3>Design de sobrancelhas</h3>
        <p>Desenho pensado para o formato do seu rosto, valorizando o olhar de forma natural e elegante.</p>
      </div>
      <div class="item">
        <h3>Maquiagem</h3>
        <p>Para o dia a dia e para ocasiões especiais, com acabamento que realça sua beleza e dura o evento inteiro.</p>
      </div>
      <div class="item">
        <h3>Depilações</h3>
        <p>Procedimento cuidadoso, com materiais higienizados e foco no seu conforto.</p>
      </div>
    </div>
  </div>
</section>

<section class="about" id="sobre">
  <div class="wrap">
    <div>
      <h2>Um espaço para se sentir bem</h2>
      <p>O Espaço de Beleza Nana Lopes é comandado por Francine Lopes, que há cinco anos transforma o momento de cuidado em experiência de autoestima.</p>
      <p>Aqui, cada cliente recebe atenção individual e sai com a confiança de quem se olha no espelho e gosta do que vê.</p>
    </div>
    <div class="years"><strong>5</strong><span>anos elevando autoestimas</span></div>
  </div>
</section>

<section>
  <div class="wrap">
    <h2>Por que escolher o Nana Lopes</h2>
    <div class="points">
      <div><h3>Atendimento próximo</h3><p>Você é ouvida antes de qualquer procedimento.</p></div>
      <div><h3>Higiene e segurança</h3><p>Materiais higienizados e técnica aplicada com responsabilidade.</p></div>
      <div><h3>Cosméticos selecionados</h3><p>Produtos para manter o resultado em casa por mais tempo.</p></div>
    </div>
  </div>
</section>

<section class="where" id="onde">
  <div class="wrap">
    <div>
      <h2>Venha nos visitar</h2>
      <address>R. J, 163 – Vila Velha<br>Fortaleza – CE</address>
      <a class="btn line" href="https://www.google.com/maps/search/?api=1&query=R.+J,+163+-+Vila+Velha,+Fortaleza+-+CE" target="_blank" rel="noopener">Ver no mapa</a>
    </div>
    <ul>
      <li>Mais contatos: <a href="https://linktr.ee/espaconanalopes" target="_blank" rel="noopener">linktr.ee/espaconanalopes</a></li>
      <li>Instagram: <a href="https://www.instagram.com/espaconanalopes/" target="_blank" rel="noopener">@espaconanalopes</a></li>
      <li>WhatsApp: <a href="https://wa.me/558598501929?text=Ol%C3%A1!%20Vim%20pelo%20site%20e%20quero%20agendar%20um%20hor%C3%A1rio%20no%20Espa%C3%A7o%20Nana%20Lopes." target="_blank" rel="noopener">(85) 9850-1929</a></li>
    </ul>
  </div>
</section>

<section class="cta">
  <div class="wrap">
    <h2>Reserve o seu momento</h2>
    <p>Escolha o serviço e agende seu horário direto pelo WhatsApp.</p>
    <a class="btn" href="https://wa.me/558598501929?text=Ol%C3%A1!%20Vim%20pelo%20site%20e%20quero%20agendar%20um%20hor%C3%A1rio%20no%20Espa%C3%A7o%20Nana%20Lopes." target="_blank" rel="noopener">Agendar pelo WhatsApp</a>
  </div>
</section>
</main>

<footer>
  <div class="wrap">
    Espaço de Beleza Nana Lopes · Fortaleza – CE ·
    <a href="https://www.instagram.com/espaconanalopes/" target="_blank" rel="noopener">@espaconanalopes</a>
  </div>
</footer>

<a class="float" href="https://wa.me/558598501929?text=Ol%C3%A1!%20Vim%20pelo%20site%20e%20quero%20agendar%20um%20hor%C3%A1rio%20no%20Espa%C3%A7o%20Nana%20Lopes." target="_blank" rel="noopener" aria-label="Agendar pelo WhatsApp">WhatsApp</a>
</body>
</html>
