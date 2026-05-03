<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dr. Julio Tatis — 3 Variaciones de Diseño Web</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,400;0,9..144,500;1,9..144,400&family=DM+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html, body { width: 100%; min-height: 100vh; background: #0a1830; font-family: 'DM Sans', sans-serif; color: #0a1830; }
  .page {
    min-height: 100vh;
    background: linear-gradient(180deg, #fafbfc 0%, #eef2f8 100%);
    padding: 80px 56px;
  }
  .container { max-width: 1280px; margin: 0 auto; }
  .header {
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
    margin-bottom: 64px;
    gap: 40px;
    border-bottom: 1px solid #d4dce8;
    padding-bottom: 40px;
  }
  .header-left {
    flex: 1;
  }
  .eyebrow {
    font-size: 12px;
    letter-spacing: 0.22em;
    color: #1a3a6e;
    text-transform: uppercase;
    margin-bottom: 16px;
    font-weight: 600;
  }
  h1 {
    font-family: 'Fraunces', serif;
    font-size: 56px;
    font-weight: 400;
    color: #0a1830;
    letter-spacing: -0.025em;
    line-height: 1.05;
    margin-bottom: 16px;
  }
  h1 em {
    font-style: italic;
    font-weight: 300;
    color: #1a3a6e;
  }
  .subtitle {
    font-size: 17px;
    color: #5a7090;
    line-height: 1.6;
    max-width: 560px;
  }
  .header-right {
    text-align: right;
    font-size: 13px;
    color: #5a7090;
    line-height: 1.5;
  }
  .header-right .doctor {
    font-family: 'Fraunces', serif;
    font-size: 18px;
    color: #0a1830;
    font-weight: 500;
    margin-bottom: 4px;
  }
  .header-right .spec {
    font-size: 11px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: #5a7090;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 32px;
  }

  .card {
    background: #fff;
    border: 1px solid #e4e9f0;
    overflow: hidden;
    text-decoration: none;
    color: inherit;
    display: flex;
    flex-direction: column;
    transition: all 0.25s ease;
    position: relative;
  }
  .card:hover {
    transform: translateY(-4px);
    box-shadow: 0 24px 48px -12px rgba(20,40,80,0.18);
    border-color: #1a3a6e;
  }

  .card-thumb {
    aspect-ratio: 16 / 11;
    overflow: hidden;
    position: relative;
    background: #0a1830;
  }

  .thumb-inner {
    position: absolute;
    inset: 0;
    transform-origin: top left;
  }

  .card-body {
    padding: 28px 28px 32px;
    display: flex;
    flex-direction: column;
    gap: 12px;
    flex: 1;
  }
  .card-num {
    font-family: 'Fraunces', serif;
    font-size: 12px;
    color: #a8b8d4;
    letter-spacing: 0.1em;
  }
  .card-title {
    font-family: 'Fraunces', serif;
    font-size: 28px;
    color: #0a1830;
    font-weight: 500;
    letter-spacing: -0.02em;
    line-height: 1.1;
  }
  .card-desc {
    font-size: 14px;
    color: #5a7090;
    line-height: 1.55;
    flex: 1;
  }
  .card-tags {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    margin-top: 8px;
  }
  .tag {
    font-size: 10px;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: #1a3a6e;
    background: #eaf0fa;
    padding: 5px 10px;
    border-radius: 999px;
    font-weight: 600;
  }
  .card-cta {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 16px;
    padding-top: 16px;
    border-top: 1px solid #e4e9f0;
  }
  .cta-text {
    font-size: 12px;
    letter-spacing: 0.1em;
    color: #1a3a6e;
    font-weight: 600;
    text-transform: uppercase;
  }
  .arrow {
    width: 32px;
    height: 32px;
    border-radius: 50%;
    background: #1a3a6e;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 14px;
    transition: transform 0.2s;
  }
  .card:hover .arrow {
    transform: translateX(4px);
  }

  /* Mini preview thumb */
  .thumb-canvas {
    position: absolute;
    inset: 0;
    display: flex;
    flex-direction: column;
    overflow: hidden;
  }
  /* V1 thumb */
  .thumb-v1 {
    background: #fafbfc;
  }
  .thumb-v1 .v1-top {
    background: #0a1830; height: 14%; display: flex; align-items: center; padding: 0 16px; gap: 8px;
    <!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dr. Julio Tatis — Variante 3: Trust & Recovery</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,400&family=Fraunces:ital,opsz,wght@0,9..144,300;0,9..144,400;0,9..144,500;0,9..144,600;1,9..144,400&family=DM+Sans:wght@300;400;500;600&family=Manrope:wght@300;400;500;600;700&family=Instrument+Serif:ital@0;1&display=swap" rel="stylesheet">
<script src="https://unpkg.com/react@18.3.1/umd/react.development.js" integrity="sha384-hD6/rw4ppMLGNu3tX5cjIb+uRZ7UkRJ6BPkLpg4hAu/6onKUg4lLsHAs9EBPT82L" crossorigin="anonymous"></script>
<script src="https://unpkg.com/react-dom@18.3.1/umd/react-dom.development.js" integrity="sha384-u6aeetuaXnQ38mYT8rp6sbXaQe3NL9t+IBXmnYxwkUI2Hw4bsp2Wvmx4yRQF1uAm" crossorigin="anonymous"></script>
<script src="https://unpkg.com/@babel/standalone@7.29.0/babel.min.js" integrity="sha384-m08KidiNqLdpJqLq95G/LEi8Qvjl/xUYll3QILypMoQ65QorJ9Lvtp2RXYGBFj1y" crossorigin="anonymous"></script>
<script type="text/babel" src="shared.jsx"></script>
<script type="text/babel" src="variant-trust.jsx"></script>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  html, body { width: 100%; min-height: 100%; background: #fff; }
  #root { width: 100%; min-height: 100%; }
  button { font-family: inherit; }
  input, textarea, select { font-family: inherit; }
  .back-link {
    position: fixed; top: 12px; right: 12px; z-index: 1000;
    padding: 8px 14px; background: rgba(255,255,255,0.95);
    border: 1px solid rgba(20,40,80,0.1); border-radius: 999px;
    font-size: 12px; color: #1a3a6e; font-weight: 600;
    text-decoration: none;
    box-shadow: 0 4px 12px rgba(20,40,80,0.08);
    font-family: 'DM Sans', sans-serif;
  }
</style>
</head>
<body>
<a href="index.html" class="back-link">← Ver todas las variantes</a>
<div id="root"></div>

<script type="text/babel">
const App = () => {
  const [lang, setLang] = React.useState('es');
  return (
    <>
      <LangToggle lang={lang} setLang={setLang} />
      <TrustRecovery lang={lang} />
    </>
  );
};
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<App />);
</script>

<template id="__bundler_thumbnail">
<svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100" height="100" fill="#1a3a6e"/>
  <circle cx="50" cy="38" r="14" fill="#fff"/>
  <rect x="32" y="56" width="36" height="20" rx="2" fill="#fff"/>
</svg>
</template>
</body>
</html>
  }
  .thumb-v1 .v1-top .lg { font-family: 'Fraunces', serif; color: #fff; font-size: 13px; font-style: italic; }
  .thumb-v1 .v1-body { flex: 1; display: grid; grid-template-columns: 1.1fr 1fr; }
  .thumb-v1 .v1-l { padding: 16px; display: flex; flex-direction: column; gap: 6px; }
  .thumb-v1 .v1-l .h { font-family: 'Fraunces', serif; color: #0a1830; font-size: 22px; line-height: 0.95; letter-spacing: -0.02em; }
  .thumb-v1 .v1-l .h em { font-style: italic; color: #1a3a6e; font-weight: 300; }
  .thumb-v1 .v1-l .p { font-size: 8px; color: #5a7090; line-height: 1.4; }
  .thumb-v1 .v1-l .btn { background: #25D366; color: #fff; font-size: 8px; padding: 5px 8px; align-self: flex-start; margin-top: 4px; font-weight: 600; }
  .thumb-v1 .v1-r { background: #0a1830; padding: 16px; display: flex; align-items: center; justify-content: center; }
  .thumb-v1 .v1-r .q { color: #fff; font-family: 'Fraunces', serif; font-style: italic; font-size: 11px; line-height: 1.3; }

  /* V2 thumb */
  .thumb-v2 { background: linear-gradient(135deg, #fcfcfd 0%, #eaf0fa 100%); position: relative; }
  .thumb-v2 .v2-nav { display: flex; justify-content: space-between; padding: 8px 16px; align-items: center; }
  .thumb-v2 .v2-nav .lg { font-weight: 700; font-size: 11px; color: #0a1220; letter-spacing: -0.01em; }
  .thumb-v2 .v2-nav .pill { background: #25D366; color: #fff; padding: 4px 10px; border-radius: 999px; font-size: 8px; font-weight: 600; }
  .thumb-v2 .v2-body { padding: 14px 16px; }
  .thumb-v2 .v2-body .h { font-size: 26px; font-weight: 700; letter-spacing: -0.04em; line-height: 0.9; color: #0a1220; }
  .thumb-v2 .v2-body .h em { color: #1a3a6e; font-family: 'Instrument Serif', serif; font-style: italic; font-weight: 400; }
  .thumb-v2 .v2-body .p { font-size: 8px; color: #5a7090; margin-top: 6px; max-width: 60%; }
  .thumb-v2 .spine { position: absolute; top: 30px; left: 50%; transform: translateX(-50%); opacity: 0.18; font-size: 80px; color: #1a3a6e; }
  .thumb-v2 .doc-card { position: absolute; right: 14px; bottom: 14px; width: 35%; background: #fff; border-radius: 8px; padding: 6px; box-shadow: 0 8px 16px rgba(20,40,80,0.15); }
  .thumb-v2 .doc-card .ph { aspect-ratio: 5/4; background: #d4dce8; border-radius: 4px; }
  .thumb-v2 .doc-card .nm { font-size: 8px; font-weight: 700; color: #0a1220; margin-top: 4px; letter-spacing: -0.01em; }

  /* V3 thumb */
  .thumb-v3 { background: #fff; }
  .thumb-v3 .v3-nav { padding: 8px 16px; border-bottom: 1px solid #e8edf3; display: flex; justify-content: space-between; align-items: center; }
  .thumb-v3 .v3-nav .lg { display: flex; align-items: center; gap: 5px; font-size: 10px; color: #0a1830; font-weight: 600; }
  .thumb-v3 .v3-nav .lg .b { width: 14px; height: 14px; border-radius: 50%; background: #1a3a6e; color: #fff; display: flex; align-items: center; justify-content: center; font-family: 'Fraunces', serif; font-size: 9px; font-style: italic; }
  .thumb-v3 .v3-nav .pill { background: #25D366; color: #fff; padding: 3px 8px; border-radius: 4px; font-size: 8px; font-weight: 600; }
  .thumb-v3 .v3-body { display: grid; grid-template-columns: 1.05fr 1fr; flex: 1; min-height: 0; }
  .thumb-v3 .v3-l { padding: 14px; background: #f4f6fa; }
  .thumb-v3 .v3-l .e { font-size: 7px; color: #1a3a6e; font-weight: 700; letter-spacing: 0.18em; text-transform: uppercase; }
  .thumb-v3 .v3-l .h { font-family: 'Cormorant Garamond', serif; font-size: 22px; line-height: 0.95; color: #0a1830; margin-top: 6px; }
  .thumb-v3 .v3-l .h em { font-style: italic; color: #1a3a6e; }
  .thumb-v3 .v3-l .ck { background: #fff; padding: 6px 8px; border-left: 2px solid #1a3a6e; font-size: 7px; color: #5a7090; line-height: 1.3; margin-top: 8px; }
  .thumb-v3 .v3-r { background: #d4dce8; position: relative; overflow: hidden; }
  .thumb-v3 .v3-r .ph { position: absolute; inset: 0; background: linear-gradient(135deg, #5a7090 0%, #1a3a6e 100%); }
  .thumb-v3 .v3-r .ov { position: absolute; bottom: 8px; left: 8px; right: 8px; background: rgba(10,24,48,0.93); padding: 6px 8px; border-radius: 4px; color: #fff; font-size: 7px; font-family: 'Cormorant Garamond', serif; }

  .footer {
    margin-top: 64px;
    padding-top: 40px;
    border-top: 1px solid #d4dce8;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 24px;
    font-size: 12px;
    color: #5a7090;
  }
  .footer a {
    color: #1a3a6e;
    text-decoration: none;
    font-weight: 600;
  }

  @media (max-width: 900px) {
    .grid { grid-template-columns: 1fr; }
    h1 { font-size: 40px; }
    .header { flex-direction: column; align-items: flex-start; }
    .header-right { text-align: left; }
  }
</style>
</head>
<body>
<div class="page">
  <div class="container">
    <header class="header">
      <div class="header-left">
        <div class="eyebrow">Propuestas de diseño web</div>
        <h1>Tres direcciones para<br /><em>el sitio del Dr. Julio Tatis</em></h1>
        <p class="subtitle">Cada variante explora una personalidad visual distinta para conectar con pacientes de columna. Haz clic para ver la propuesta completa, navegable y bilingüe.</p>
      </div>
      <div class="header-right">
        <div class="doctor">Dr. Guillermo Julio Tatis</div>
        <div class="spec">Especialista en Columna · Panamá</div>
      </div>
    </header>

    <div class="grid">

      <a class="card" href="Variante 1 - Clinical Authority.html">
        <div class="card-thumb">
          <div class="thumb-canvas thumb-v1">
            <div class="v1-top"><span class="lg">G  Dr. Julio Tatis</span></div>
            <div class="v1-body">
              <div class="v1-l">
                <div class="h">Recupera<br /><em>tu calidad</em><br />de vida.</div>
                <div class="p">Especialista en columna<br />vertebral con formación<br />internacional.</div>
                <div class="btn">Agendar WhatsApp</div>
              </div>
              <div class="v1-r"><div class="q">"La cirugía debe ser el último recurso, no el primero."</div></div>
            </div>
          </div>
        </div>
        <div class="card-body">
          <div class="card-num">VARIANTE 01</div>
          <div class="card-title">Clinical Authority</div>
          <div class="card-desc">Editorial médica con tipografía serif. Transmite autoridad académica y prestigio internacional. Paleta navy + marfil con detalles dorados.</div>
          <div class="card-tags">
            <span class="tag">Serif · Fraunces</span>
            <span class="tag">Editorial</span>
            <span class="tag">Autoridad</span>
          </div>
          <div class="card-cta">
            <span class="cta-text">Ver propuesta</span>
            <span class="arrow">→</span>
          </div>
        </div>
      </a>

      <a class="card" href="Variante 2 - Modern Spine.html">
        <div class="card-thumb">
          <div class="thumb-canvas thumb-v2">
            <div class="v2-nav">
              <span class="lg">JULIO·TATIS</span>
              <span class="pill">WhatsApp</span>
            </div>
            <div class="spine">|||</div>
            <div class="v2-body">
              <div class="h">Vive sin<br /><em>dolor de espalda.</em></div>
              <div class="p">Cirugía mínimamente invasiva. Diagnóstico preciso, recuperación rápida.</div>
            </div>
            <div class="doc-card">
              <div class="ph"></div>
              <div class="nm">Dr. Julio Tatis</div>
            </div>
          </div>
        </div>
        <div class="card-body">
          <div class="card-num">VARIANTE 02</div>
          <div class="card-title">Modern Spine</div>
          <div class="card-desc">Diseño contemporáneo asimétrico con motivo anatómico de columna como protagonista. Sans serif limpio, mezcla con cursiva editorial. Más juvenil y técnico.</div>
          <div class="card-tags">
            <span class="tag">Sans · Manrope</span>
            <span class="tag">Asimétrico</span>
            <span class="tag">Anatómico</span>
          </div>
          <div class="card-cta">
            <span class="cta-text">Ver propuesta</span>
            <span class="arrow">→</span>
          </div>
        </div>
      </a>

      <a class="card" href="Variante 3 - Trust & Recovery.html">
        <div class="card-thumb">
          <div class="thumb-canvas thumb-v3">
            <div class="v3-nav">
              <span class="lg"><span class="b">G</span> Dr. Julio Tatis</span>
              <span class="pill">💬 WhatsApp</span>
            </div>
            <div class="v3-body">
              <div class="v3-l">
                <div class="e">Especialista · Panamá</div>
                <div class="h">Tu espalda<br />no debería<br /><em>limitarte.</em></div>
                <div class="ck">¿Te sientes identificado?<br />✓ Dolor lumbar persistente<br />✓ Hormigueo en piernas</div>
              </div>
              <div class="v3-r">
                <div class="ph"></div>
                <div class="ov">Dr. Guillermo Julio Tatis<br />★★★★★ 4.9</div>
              </div>
            </div>
          </div>
        </div>
        <div class="card-body">
          <div class="card-num">VARIANTE 03</div>
          <div class="card-title">Trust &amp; Recovery</div>
          <div class="card-desc">Foto-protagonista con tono cálido clínico. Enfoque en empatía, identificación de síntomas y testimonios reales. Cormorant serif elegante.</div>
          <div class="card-tags">
            <span class="tag">Serif · Cormorant</span>
            <span class="tag">Foto-led</span>
            <span class="tag">Empatía</span>
          </div>
          <div class="card-cta">
            <span class="cta-text">Ver propuesta</span>
            <span class="arrow">→</span>
          </div>
        </div>
      </a>

    </div>

    <footer class="footer">
      <div>Cada variante es navegable y bilingüe (ES/EN). Haz clic para abrirla.</div>
      <a href="Dr Juliot - Diseño Web.html">Ver las 3 en un solo canvas →</a>
    </footer>
  </div>
</div>

<template id="__bundler_thumbnail">
<svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <rect width="100" height="100" fill="#fafbfc"/>
  <rect x="14" y="20" width="22" height="60" fill="#0a1830"/>
  <rect x="40" y="20" width="22" height="60" fill="#1a3a6e"/>
  <rect x="66" y="20" width="22" height="60" fill="#5a8acc"/>
</svg>
</template>
</body>
</html>
