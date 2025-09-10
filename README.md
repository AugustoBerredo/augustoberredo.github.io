<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Augusto Berredo • Business Intelligence</title>
  <style>
    :root{
      --bg:#0b0e14;--surface:#11151d;--text:#e6eaf2;--muted:#b8c0ce;--primary:#03dac6;--primary-2:#00bfa6;--accent:#7aa2f7;--radius:18px;--shadow:0 10px 30px rgba(0,0,0,.35);--shadow-soft:0 6px 18px rgba(0,0,0,.25);--maxw:1200px;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:var(--text);font-family:system-ui,Segoe UI,Roboto,Arial,sans-serif;line-height:1.6}
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block;border-radius:var(--radius)}
    .container{max-width:var(--maxw);margin:auto;padding:0 20px}
    header{position:sticky;top:0;z-index:50;background:rgba(11,14,20,.85);backdrop-filter:blur(8px);border-bottom:1px solid rgba(255,255,255,.06)}
    .navwrap{display:flex;justify-content:space-between;align-items:center;height:64px}
    .brand{font-weight:700;display:flex;align-items:center;gap:10px}
    .brand .logo{width:34px;height:34px;border-radius:10px;background:linear-gradient(135deg,var(--primary),var(--accent))}
    nav{display:flex;gap:16px}
    nav a{padding:8px 12px;border-radius:8px}
    nav a:hover{background:rgba(255,255,255,.08)}
    .nav-cta{padding:10px 16px;border-radius:12px;background:linear-gradient(135deg,var(--primary),var(--primary-2));color:#051c19;font-weight:700}
    section{padding:60px 0}
    h1,h2,h3{margin:10px 0}
    .lead{color:var(--muted)}
    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px}
    .shot{background:var(--surface);border:1px solid rgba(255,255,255,.08);padding:12px;border-radius:var(--radius)}
    .profile{display:grid;grid-template-columns:280px 1fr;gap:24px}
    footer{padding:28px 0;border-top:1px solid rgba(255,255,255,.06);color:var(--muted);text-align:center}
    @media(max-width:800px){.profile{grid-template-columns:1fr}}
  </style>
</head>
<body>
<header>
  <div class="container navwrap">
    <div class="brand"><span class="logo"></span> Augusto Berredo • Business Intelligence</div>
    <nav>
      <a href="#introducao">Introdução</a>
      <a href="#beneficios">Benefícios</a>
      <a href="#projetos">Projetos</a>
      <a href="#autor">Sobre o Autor</a>
    </nav>
    <a href="#autor" class="nav-cta">Contato</a>
  </div>
</header>

<main>
  <section id="introducao" class="container">
    <h2>Introdução</h2>
    <p>Dados só geram valor quando podem ser analisados com clareza e rapidez. O Business Intelligence (BI) transforma grandes volumes de informações em painéis práticos, que oferecem insights imediatos para gestores e equipes. Meu objetivo é usar BI para tornar decisões mais ágeis e seguras.</p>
  </section>

  <section id="beneficios" class="container">
    <h2>Benefícios do Power BI</h2>
    <ul>
      <li><strong>Ferramenta Microsoft:</strong> Interface familiar, integração com Excel, Word e PowerPoint.</li>
      <li><strong>Líder de mercado (Gartner 2021):</strong> Reconhecimento mundial em Analytics & BI.</li>
      <li><strong>Vantagens:</strong> Baixo custo, simplicidade de uso, conexões com várias fontes, relatórios interativos e compartilhamento rápido.</li>
    </ul>
  </section>

  <section id="projetos" class="container">
    <h2>Projetos Demonstrativos</h2>
    <div class="gallery">
      <div class="shot"><h3>Financeiro</h3><p>Margem Bruta com simulador para avaliar o Lucro Operacional.</p></div>
      <div class="shot"><h3>Vendas B2B</h3><p>Análise de margem por produto e métricas comerciais (dados fictícios).</p></div>
      <div class="shot"><h3>Compras</h3><p>Monitoramento de lead time de matérias-primas.</p></div>
      <div class="shot"><h3>Logística</h3><p>OTIF – acompanhamento de entregas completas e no prazo.</p></div>
      <div class="shot"><h3>Produção</h3><p>OEE – efetividade global dos equipamentos produtivos.</p></div>
      <div class="shot"><h3>Financeiro</h3><p>Títulos e DRE Gerencial consolidada.</p></div>
      <div class="shot"><h3>SAC / Help Desk</h3><p>Gestão de chamados com controle de SLA.</p></div>
      <div class="shot"><h3>Vendas</h3><p>Faturamento por localidade, consolidado por continentes.</p></div>
    </div>
  </section>

  <section id="autor" class="container">
    <h2>Sobre o Autor</h2>
    <div class="profile">
      <div>
        <img src="SGCAM_20241107_0602060500.PORTRAIT.jpg" alt="Foto de Augusto Berredo" />
      </div>
      <div>
        <h3>Augusto César Berredo Barbosa</h3>
        <p>Profissional de Logística e Business Intelligence com trajetória em empresas como Samsung, Whirlpool, Envision, Tellescom e Amazonaço. Experiência em materiais, shipping/recebimento de bobinas e logística marítima. Desenvolve dashboards em Power BI, DAX, Power Query e Excel Avançado, integrando diferentes fontes para insights executivos e operacionais.</p>
        <ul>
          <li>Projetos com Navios Recebidos, Bobinas em Recebimento, Toneladas em Trânsito e Doc.Import/IMP codes.</li>
          <li>Criação de tabelas calendário, medidas DAX e rotinas em M para unificação de dados.</li>
          <li>Dashboards com ícones de status 🚢 📦 ✅ e indicadores OTIF, SLA e Lead Time.</li>
          <li>Portfólio: <a href="https://github.com/AugustoBerredo/augustoberredo.github.io">augustoberredo.github.io</a></li>
          <li>LinkedIn: <a href="https://www.linkedin.com/in/augusto-berredo/">/in/augusto-berredo</a></li>
        </ul>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="container">
    <small>© <span id="year"></span> Augusto Berredo • Business Intelligence</small>
  </div>
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>
</body>
</html>
