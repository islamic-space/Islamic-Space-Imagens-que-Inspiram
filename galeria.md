# Galeria "Imagens que Inspiram"

Esta galeria apresenta um mosaico dinâmico das referências visuais que influenciam o Islamic Passport. Explore cada obra passando o cursor sobre as molduras: efeitos de luz, parallax suave e legendas contextualizadas ajudam a perceber nuances históricas e arquitetônicas.

👉 [Repositório oficial das imagens](https://github.com/Islamic-Works/Islamic-Passport-workspace/tree/main/sites/Imagens-que-Inspiram)

<style>
  :root {
    color-scheme: light dark;
  }

  .gallery-wrapper {
    margin: 2rem auto;
    max-width: min(1200px, 95vw);
    font-family: "Inter", "Segoe UI", system-ui, sans-serif;
  }

  .gallery-grid {
    display: grid;
    gap: 2.4rem;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    padding: 0;
    list-style: none;
  }

  .gallery-card {
    position: relative;
    overflow: hidden;
    border-radius: 24px;
    background: linear-gradient(135deg, rgba(15, 23, 42, 0.85), rgba(99, 102, 241, 0.65));
    box-shadow: 0 18px 45px rgba(15, 23, 42, 0.35);
    min-height: 320px;
    transition: transform 320ms ease, box-shadow 320ms ease;
  }

  .gallery-card::before {
    content: "";
    position: absolute;
    inset: 0;
    border-radius: inherit;
    padding: 3px;
    background: linear-gradient(135deg, rgba(244, 114, 182, 0.65), rgba(56, 189, 248, 0.8));
    mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
    mask-composite: exclude;
    -webkit-mask-composite: xor;
    pointer-events: none;
    opacity: 0.9;
  }

  .gallery-card:hover {
    transform: translateY(-12px) scale(1.015);
    box-shadow: 0 24px 60px rgba(15, 23, 42, 0.45);
  }

  .gallery-card figure {
    margin: 0;
    height: 100%;
    display: grid;
    grid-template-rows: minmax(180px, 1fr) auto;
  }

  .gallery-card img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    filter: saturate(108%) contrast(102%);
    transition: transform 600ms ease;
  }

  .gallery-card:hover img {
    transform: scale(1.08);
  }

  .gallery-caption {
    padding: 1.4rem 1.6rem 1.8rem;
    color: rgba(248, 250, 252, 0.92);
    backdrop-filter: blur(12px);
    background: linear-gradient(180deg, rgba(15, 23, 42, 0.05) 0%, rgba(15, 23, 42, 0.85) 100%);
  }

  .gallery-caption h3 {
    font-size: 1.1rem;
    margin: 0 0 0.35rem;
    letter-spacing: 0.015em;
  }

  .gallery-caption p {
    margin: 0;
    font-size: 0.92rem;
    line-height: 1.5;
    color: rgba(226, 232, 240, 0.92);
  }

  @media (prefers-reduced-motion: reduce) {
    .gallery-card,
    .gallery-card img {
      transition: none;
    }
  }
</style>

<div class="gallery-wrapper">
  <ul class="gallery-grid">
    <li class="gallery-card">
      <figure>
        <img src="./1.png" alt="Padrões geométricos com contraste dourado e azul" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Geometria Cerimonial</h3>
          <p>Formas geométricas entrelaçadas evocam tesselações islâmicas e inspiram a linguagem visual do passaporte.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./28325957427_f94bfee3d2_o-1.jpg" alt="Painéis ornamentados com arabescos dourados" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Arabescos Dourados</h3>
          <p>Referência para texturas premium e certificados digitais com acabamento metálico.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./31536000.jpg" alt="Motivo circular com estrela octogonal central" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Estrela de Oito Pontas</h3>
          <p>Simboliza equilíbrio e continuidade, servindo como guia para ícones e selos oficiais.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./3ca0d686-72cc-4da0-8ff0-407dcbcc6b96-isfahan3.jpg" alt="Vista de cúpulas azul turquesa em Isfahan" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Céus de Isfahan</h3>
          <p>Os domos azuis inspiram a paleta institucional e a iconografia espiritual da jornada.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./48ae328e-69bb-4cfc-8c8a-c8ac479c9375-Tiled Facade, The Dome of the Rock, c. 1545-1552 (photo by Andrew Shiva, CC BY-SA 4.0).jpeg" alt="Mosaico colorido da Cúpula da Rocha" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Mosaico da Cúpula</h3>
          <p>Retrabalhado como padrão repetível para capas digitais e backgrounds responsivos.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./Arabischer_Maler_um_690_002.jpg" alt="Manuscrito árabe iluminado" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Manuscrito Iluminado</h3>
          <p>Tipografia manuscrita estabelece o tom para certificados e narrativas históricas.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./DRExterior_1024x1024@2x.webp" alt="Detalhe exterior dourado com padrões triangulares" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Reflexos Dourados</h3>
          <p>Padrões facetados sugerem segurança de dados por camadas e brilhos controlados.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./Dome-of-the-Rock-Jerusalem.webp" alt="Cúpula dourada iluminada ao pôr do sol" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Luz da Cúpula</h3>
          <p>Contraste entre dourado e azul guia gradientes e iluminação em interfaces.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./DomeoftheRockUp-scaled.jpg" alt="Detalhe dos azulejos azuis da Cúpula da Rocha" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Azulejaria Celestial</h3>
          <p>Matizes cerúleos modelam bordas e elementos de navegação do sistema.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./Jama_Masjid_Agra.jpg" alt="Fachada da Mesquita Jama Masjid em Agra" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Portais de Agra</h3>
          <p>Arcos emolduram experiências autenticadas para distintos perfis de usuários.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./default.jpg" alt="Textura ornamental abstrata" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Textura Essencial</h3>
          <p>Camada base para placeholders e telas de carregamento com estética refinada.</p>
        </figcaption>
      </figure>
    </li>
    <li class="gallery-card">
      <figure>
        <img src="./مسجد_السهلة.jpg" alt="Mesquita Al-Sahla com cúpula iluminada" loading="lazy" />
        <figcaption class="gallery-caption">
          <h3>Serenidade de Al-Sahla</h3>
          <p>Atmosfera noturna inspira o modo escuro e microinterações de brilho suave.</p>
        </figcaption>
      </figure>
    </li>
  </ul>
</div>
