<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="author" content="Kalina Ivanova"/>
  <title>Kalina Ivanova - SEO Translator & Marketing Specialist (EN-BG)</title>
  <meta name="description" content="Professional English to Bulgarian translator & localization specialist | SEO content, e-commerce emails, Google Maps & review growth, Data Entry & System Accuracy, International Customer Support & Operations | Sofia, Bulgaria">
  <style>
    :root {
      --primary: #2c5282;
      --dark: #1f2937;
      --light: #f9fafb;
      --gray: #6b7280;
      --star: #f59e0b;
      --success: #10b981;
      --error: #ef4444;
    }
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      font-family: system-ui, -apple-system, sans-serif;
      line-height: 1.6;
      color: var(--dark);
      background: var(--light);
      transition: opacity 0.6s ease;
    }
    body.fade { opacity: 0.35; pointer-events: none; user-select: none; }
    .container { max-width: 1100px; margin: 0 auto; padding: 0 20px; }
    header {
      background: linear-gradient(135deg, #1e40af, #3b82f6);
      color: white;
      text-align: center;
      padding: 160px 20px 100px;
    }
    header h1 {
      font-size: 4rem;
      margin-bottom: 0.3rem;
      animation: fadeInUp 1.6s ease-out;
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(60px); }
      to { opacity: 1; transform: translateY(0); }
    }
    header .tagline {
      font-size: 1.6rem;
      opacity: 0.92;
      max-width: 780px;
      margin: 0 auto;
    }
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      background: rgba(255,255,255,0.96);
      backdrop-filter: blur(12px);
      box-shadow: 0 3px 14px rgba(0,0,0,0.08);
      z-index: 999;
    }
    nav .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 18px 20px;
      flex-wrap: wrap;
    }
    nav a {
      color: var(--dark);
      text-decoration: none;
      margin: 0 18px;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover { color: var(--primary); }
    .lang-switcher button {
      background: none;
      border: none;
      font-size: 1.15rem;
      cursor: pointer;
      padding: 6px 10px;
      margin-left: 12px;
    }
    .lang-switcher button.active {
      font-weight: bold;
      color: var(--primary);
      border-bottom: 2px solid var(--primary);
    }
    section { padding: 100px 0; }
    h2 {
      text-align: center;
      font-size: 2.9rem;
      margin-bottom: 60px;
    }
    section:not(#contact) h2,
    section:not(#contact) .card h2,
    section:not(#contact) .card h3 {
      color: var(--dark);
    }
    #contact h2 { color: white; }
    .card {
      background: white;
      padding: 45px;
      border-radius: 14px;
      box-shadow: 0 8px 28px rgba(0,0,0,0.09);
      margin: 35px auto;
      max-width: 960px;
      opacity: 0;
      transform: translateY(40px);
      transition: all 0.9s ease-out;
    }
    .card.visible {
      opacity: 1 !important;
      transform: translateY(0) !important;
    }
    .services-grid, .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 32px;
    }
    .service-item, .project-item {
      padding: 28px;
      background: var(--light);
      border-radius: 12px;
      border: 1px solid #e5e7eb;
      transition: all 0.35s ease;
    }
    .service-item:hover, .project-item:hover {
      transform: translateY(-10px) scale(1.035);
      box-shadow: 0 16px 36px rgba(0,0,0,0.14);
    }
    .project-item img {
      width: 100%;
      border-radius: 10px;
      margin: 18px 0;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }
    .testimonial-item {
      margin-bottom: 40px;
      padding: 24px 30px 24px 55px;
      background: var(--light);
      border-left: 6px solid var(--primary);
      border-radius: 10px;
      position: relative;
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.9s ease-out;
    }
    .testimonial-item.visible { opacity: 1; transform: translateY(0); }
    .testimonial-item:nth-child(1) { transition-delay: 0.15s; }
    .testimonial-item:nth-child(2) { transition-delay: 0.35s; }
    .testimonial-item:nth-child(3) { transition-delay: 0.55s; }
    .testimonial-item::before {
      content: '“';
      position: absolute;
      left: 18px;
      top: -8px;
      font-size: 6rem;
      color: var(--primary);
      opacity: 0.12;
      line-height: 1;
    }
    .stars {
      font-size: 1.6rem;
      color: var(--star);
      letter-spacing: 4px;
      margin-bottom: 12px;
    }
    .testimonial-author {
      display: block;
      margin-top: 14px;
      font-weight: 600;
      color: var(--primary);
      font-style: normal;
    }
    .btn {
      background: var(--primary);
      color: white;
      padding: 14px 36px;
      border-radius: 999px;
      text-decoration: none;
      font-weight: 500;
      display: inline-block;
      transition: all 0.35s ease;
      position: relative;
      overflow: hidden;
    }
    .btn:hover {
      background: #1e40af;
      transform: translateY(-3px);
      box-shadow: 0 10px 24px rgba(44,82,130,0.35);
    }
    .mailto-info {
      text-align: center;
      margin: 40px 0;
      font-size: 1.2rem;
    }
    .mailto-info a {
      color: white;
      font-weight: 600;
      text-decoration: underline;
    }
    .mailto-info a:hover {
      color: #e0f2fe;
    }
    footer {
      text-align: center;
      padding: 60px 20px;
      background: var(--dark);
      color: white;
    }
    .experience-item {
      margin-bottom: 2.5rem;
      opacity: 0;
      transform: translateY(30px);
      transition: all 0.9s ease-out;
    }
    .experience-item.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .experience-item:nth-child(1) { transition-delay: 0.2s; }
    .experience-item:nth-child(2) { transition-delay: 0.4s; }
    .experience-item h3 {
      margin-bottom: 0.4rem;
    }
    .experience-item .date {
      display: block;
      color: var(--gray);
      font-style: italic;
      margin-bottom: 1rem;
    }
    .social a {
      margin-right: 1.5rem;
      color: var(--primary);
      text-decoration: none;
      font-weight: 500;
    }
    .social a:hover { text-decoration: underline; }

    @media (max-width: 768px) {
      header h1 { font-size: 3rem; }
      nav .container { flex-direction: column; gap: 14px; padding: 14px 20px; }
      nav a { margin: 6px 14px; }
    }
  </style>
</head>
<body>
<nav>
  <div class="container">
    <div data-i18n="name">Kalina Ivanova</div>
    <div>
      <a href="#services" data-i18n="nav.services">Services</a>
      <a href="#about" data-i18n="nav.about">About</a>
      <a href="#testimonials" data-i18n="nav.testimonials">Testimonials</a>
      <a href="#projects" data-i18n="nav.projects">Projects</a>
      <a href="#experience" data-i18n="nav.experience">Experience</a>
      <a href="#contact" data-i18n="nav.contact">Contact</a>
      <span class="lang-switcher">
        <button data-lang="en" class="active">EN</button>
        <button data-lang="bg">BG</button>
      </span>
    </div>
  </div>
</nav>

<header id="home">
  <div class="container">
    <h1 data-i18n="hero.name">Kalina Ivanova</h1>
    <p class="tagline" data-i18n="hero.tagline">SEO Content Translator & Localization Specialist (EN → BG)<br>E-commerce Emails • Google Maps & Review Growth • Data Entry & System Accuracy • International Customer Support & Operations</p>
  </div>
</header>

<section id="services">
  <div class="container">
    <h2 data-i18n="services.title">My Services</h2>
    <div class="services-grid">
      <div class="service-item">
        <h3 data-i18n="services.trans">EN to BG Translation & Localization</h3>
        <p data-i18n="services.trans_desc">SEO-optimized, culturally adapted content for the Bulgarian market – websites, blogs, product descriptions.</p>
      </div>
      <div class="service-item">
        <h3 data-i18n="services.emails">E-commerce Marketing Emails</h3>
        <p data-i18n="services.emails_desc">High-converting campaigns: promotions, newsletters, abandoned cart sequences – translated & optimized.</p>
      </div>
      <div class="service-item">
        <h3 data-i18n="services.wix">Wix Website Building & Optimization</h3>
        <p data-i18n="services.wix_desc">Professional, fast, mobile-friendly Wix sites with basic SEO and content population.</p>
      </div>
      <div class="service-item">
        <h3 data-i18n="services.maps">Google Maps & Review Management</h3>
        <p data-i18n="services.maps_desc">Business profile optimization, custom links, review strategies to increase ratings & visibility.</p>
      </div>
      <div class="service-item">
        <h3 data-i18n="services.customer">International customer Support & Operations</h3>
        <p data-i18n="services.customer_desc">Professional e-commerce support: customer enquiries, order processing, returns, refunds, and issue resolution.</p>
      </div>
      <div class="service-item">
        <h3 data-i18n="services.data">Data Entry & System Accuracy</h3>
        <p data-i18n="services.data_desc">Accurate entry and maintenance of orders, product data, customer records, and operational information.</p>
      </div>
    </div>
  </div>
</section>

<section id="about">
  <div class="container">
    <h2 data-i18n="about.title">About Me</h2>
    <div class="card">
      <p data-i18n="about.p1">Marketing & Localisation Specialist with 11+ years of experience in customer service, order fulfilment, operations, and direct communication with international clients and teams.</p>
      <p data-i18n="about.p2">Detail-oriented and results-driven, I support brands entering and growing in the Bulgarian market through accurate EN→BG translation, SEO-focused localisation, marketing content, and practical digital solutions (Wix, Google Maps, review strategies).</p>
      <p data-i18n="about.languages">Languages: Bulgarian (Native), English, Italian</p>
      <div style="margin-top:35px;" class="social">
        <a href="https://www.linkedin.com/in/kalina-ivan-42a8a6143/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        <a href="https://www.upwork.com/freelancers/~0162981d3b8fac628e?viewMode=1" target="_blank" rel="noopener noreferrer">Upwork</a>
      </div>
    </div>
  </div>
</section>

<section id="testimonials" style="background:#f8f9fa;">
  <div class="container">
    <h2 data-i18n="testimonials.title">Testimonials</h2>
    <div class="card">
      <div class="testimonial-item">
        <div class="stars">★★★★★</div>
        <p>“Kalina consistently delivers Bulgarian localisation that reads naturally and aligns with brand tone. Her work is precise, well-structured, and ready to publish.”</p>
        <span class="testimonial-author">— Marketing Manager, E-commerce</span>
      </div>
      <div class="testimonial-item">
        <div class="stars">★★★★★</div>
        <p>“Professional and dependable. Kalina communicates clearly, handles customer cases with confidence, and keeps a calm, solution-focused tone.”</p>
        <span class="testimonial-author">— Customer Support Lead</span>
      </div>
      <div class="testimonial-item">
        <div class="stars">★★★★★</div>
        <p>“Excellent attention to detail. Kalina manages purchase order workflows accurately, documents processes clearly, and follows through reliably on deadlines.”</p>
        <span class="testimonial-author">— Operations Coordinator</span>
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="container">
    <h2 data-i18n="projects.title">Real Examples & Projects</h2>
    <div class="projects-grid">
      <div class="project-item">
        <h3 data-i18n="projects.wix">Wix Website: Bobi's Cars (UK)</h3>
        <p>Professional Wix site built for a Nottingham car body repair business – services, contact & clean design.</p>
        <img loading="lazy" src="bobiswebsite.jpg" alt="Bobi's Cars Wix website screenshot">
        <a href="https://kalina2005kalina20.wixsite.com/bobicars" class="btn" target="_blank" rel="noopener noreferrer">View Live Site</a>
      </div>
      <div class="project-item">
        <h3 data-i18n="projects.maps">Google Maps & Review Growth: Bobi's Cars</h3>
        <p>Optimized Google Business Profile + review strategy – increased visibility and ratings.</p>
        <img loading="lazy" src="bobisreviews.jpg" alt="Google reviews screenshot for Bobi's Cars">
        <img loading="lazy" src="bobisseo.jpg" alt="SEO & review improvements screenshot" style="margin-top:1.4rem;">
      </div>
      <div class="project-item">
        <h3 data-i18n="projects.trans">Translation Example: EN → BG</h3>
        <p>Sample from current e-commerce/marketing project – natural, SEO-friendly localization.</p>
        <img loading="lazy" src="translationexample.jpg" alt="EN to BG translation example – part 1">
        <img loading="lazy" src="translationexample1.jpg" alt="EN to BG translation example – part 2" style="margin-top:1.4rem;">
      </div>
    </div>
  </div>
</section>

<section id="experience">
  <div class="container">
    <h2 data-i18n="experience.title">Professional Experience</h2>
    <div class="card">
      <div class="experience-item">
        <h3 data-i18n="experience.freelance">Freelance SEO Marketing Translator & Localisation Specialist</h3>
        <span class="date" data-i18n="experience.freelance_date">EU-based E-commerce Projects | Remote – Sofia, Bulgaria</span>
        <ul>
          <li data-i18n="experience.freelance_li1">Led SEO-driven localisation for product, category, and campaign content in the Bulgarian market</li>
          <li data-i18n="experience.freelance_li2">Defined keyword strategy and search intent alignment to improve search visibility and performance</li>
          <li data-i18n="experience.freelance_li3">Optimised content for brand consistency, linguistic accuracy, and conversion</li>
          <li data-i18n="experience.freelance_li4">Partnered with global marketing teams to deliver localised campaigns on time</li>
        </ul>
      </div>
      <div class="experience-item">
        <h3 data-i18n="experience.amazon">Customer Operations Specialist</h3>
        <span class="date" data-i18n="experience.amazon_date">Amazon Fulfilment Centre, UK • Feb 2020 – Jul 2025</span>
        <ul>
          <li data-i18n="experience.amazon_li1">Managed inbound operations and inventory discrepancies</li>
          <li data-i18n="experience.amazon_li2">Resolved customer claims related to deliveries, damages, and order discrepancies</li>
          <li data-i18n="experience.amazon_li3">Analysed data and drove process improvements</li>
          <li data-i18n="experience.amazon_li4">Investigated system vs. physical stock variances to support loss prevention</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section id="contact" style="background:var(--primary); color:white;">
  <div class="container">
    <h2 data-i18n="contact.title">Get In Touch</h2>
    <div class="card" style="background:rgba(255,255,255,0.14); border:none; backdrop-filter:blur(12px); color:white; text-align:center;">
      <p style="margin-bottom: 2rem; font-size: 1.15rem;">
        <span data-i18n="contact.intro">Want to discuss a project or have a question?</span><br>
        <span data-i18n="contact.click">Click the button below</span>
      </p>
      
      <a href="mailto:kivanova.mail@gmail.com?subject=Запитване%20от%20сайта&body=Здравейте%20Калина%2C%0D%0A%0D%0AИме%3A%20%0D%0AИмейл%3A%20%0D%0A%0D%0AСъобщение%3A%20%0D%0A%0D%0AБлагодаря!" class="btn" data-i18n="contact.button">
        Изпрати съобщение
      </a>
      
      <p style="margin-top: 2.5rem; font-size: 1.1rem;">
        <span data-i18n="contact.or">or directly to:</span> 
        <a href="mailto:kivanova.mail@gmail.com" style="color:#dbeafe; text-decoration:underline;">kivanova.mail@gmail.com</a>
      </p>
    </div>
  </div>
</section>

<footer>
  <p data-i18n="footer">© 2026 Kalina Ivanova. All rights reserved. | Freelance Translator & Marketing Specialist – Sofia, Bulgaria</p>
</footer>

<script>
  const translations = {
    en: {
      name: "Kalina Ivanova",
      nav: {
        services: "Services",
        about: "About",
        testimonials: "Testimonials",
        projects: "Projects",
        experience: "Experience",
        contact: "Contact"
      },
      hero: {
        name: "Kalina Ivanova",
        tagline: "SEO Content Translator & Localization Specialist (EN-BG)<br>E-commerce Emails • Google Maps & Review Growth • Data Entry & System Accuracy • International Customer Support & Operations"
      },
      services: {
        title: "My Services",
        trans: "EN to BG Translation & Localization",
        trans_desc: "SEO-optimized, culturally adapted content for the Bulgarian market – websites, blogs, product descriptions.",
        emails: "E-commerce Marketing Emails",
        emails_desc: "High-converting campaigns: promotions, newsletters, abandoned cart sequences – translated & optimized.",
        wix: "Wix Website Building & Optimization",
        wix_desc: "Professional, fast, mobile-friendly Wix sites with basic SEO and content population.",
        maps: "Google Maps & Review Management",
        maps_desc: "Business profile optimization, custom links, review strategies to increase ratings & visibility.",
        customer: "International customer Support & Operations",
        customer_desc: "Professional e-commerce support: customer enquiries, order processing, returns, refunds, and issue resolution.",
        data: "Data Entry & System Accuracy",
        data_desc: "Accurate entry and maintenance of orders, product data, customer records, and operational information."
      },
      about: {
        title: "About Me",
        p1: "Marketing & Localization Specialist with 11+ years of experience in customer service, order fulfilment, operations, and direct communication with international clients and teams.",
        p2: "Detail-oriented and results-driven, I support brands entering and growing in the Bulgarian market through accurate EN→BG translation, SEO-focused localization, marketing content, and practical digital solutions (Wix, Google Maps, review strategies).",
        languages: "Languages: Bulgarian (Native), English, Italian"
      },
      testimonials: { title: "Testimonials" },
      projects: {
        title: "Real Examples & Projects",
        wix: "Wix Website: Bobi's Cars (UK)",
        maps: "Google Maps & Review Growth: Bobi's Cars",
        trans: "Translation Example: EN → BG"
      },
      experience: {
        title: "Professional Experience",
        freelance: "Freelance SEO Marketing Translator & Localisation Specialist",
        freelance_date: "EU-based E-commerce Projects | Remote – Sofia, Bulgaria",
        freelance_li1: "Led SEO-driven localisation for product, category, and campaign content in the Bulgarian market",
        freelance_li2: "Defined keyword strategy and search intent alignment to improve search visibility and performance",
        freelance_li3: "Optimised content for brand consistency, linguistic accuracy, and conversion",
        freelance_li4: "Partnered with global marketing teams to deliver localised campaigns on time",
        amazon: "Customer Operations Specialist",
        amazon_date: "Amazon Fulfilment Centre, UK • Feb 2020 – Jul 2025",
        amazon_li1: "Managed inbound operations and inventory discrepancies",
        amazon_li2: "Resolved customer claims related to deliveries, damages, and order discrepancies",
        amazon_li3: "Analysed data and drove process improvements",
        amazon_li4: "Investigated system vs. physical stock variances to support loss prevention"
      },
      contact: {
        title: "Get In Touch",
        intro: "Want to discuss a project or have a question?",
        click: "Click the button below",
        button: "Send Message",
        or: "or directly to:"
      },
      footer: "© 2026 Kalina Ivanova. All rights reserved. | Freelance Translator & Marketing Specialist – Sofia, Bulgaria"
    },
    bg: {
      name: "Калина Иванова",
      nav: {
        services: "Услуги",
        about: "За мен",
        testimonials: "Отзиви",
        projects: "Проекти",
        experience: "Опит",
        contact: "Контакт"
      },
      hero: {
        name: "Калина Иванова",
        tagline: "SEO преводач и специалист по локализация (EN → BG)<br>Имейл кампании за онлайн търговия • Оптимизация на Google Maps и онлайн отзиви • Обработка и управление на данни • Обслужване на клиенти и бизнес операции "
      },
      services: {
        title: "Услуги",
        trans: "Превод и локализация EN → BG",
        trans_desc: "SEO-оптимизирано, културно адаптирано съдържание за българския пазар – уебсайтове, блогове, продуктови описания.",
        emails: "Маркетинг имейли за електронна търговия",
        emails_desc: "Висококонвертиращи кампании: промоции, бюлетини, последователности за изоставени колички – превод и оптимизация.",
        wix: "Създаване и оптимизация на Wix сайтове",
        wix_desc: "Професионални, бързи, мобилно-адаптивни Wix сайтове с основен SEO и попълване на съдържание.",
        maps: "Google Maps и управление на ревюта",
        maps_desc: "Оптимизация на бизнес профил, персонализирани линкове, стратегии за увеличаване на рейтинга и видимост в София/България.",
        customer: "Международно обслужване на клиенти и бизнес операции",
        customer_desc: "Професионална поддръжка за онлайн търговия: запитвания, обработка на поръчки, връщания, възстановявания и разрешаване на проблеми.",
        data: "Въвеждане и точност на данни",
        data_desc: "Прецизно въвеждане и поддръжка на поръчки, продуктови данни, клиентски записи и оперативна информация."
      },
      about: {
        title: "За мен",
        p1: "Специалист по маркетинг и локализация с над 11 години опит в обслужване на клиенти, изпълнение на поръчки, операции и пряка комуникация с международни клиенти и екипи.",
        p2: "Детайлно ориентирана и фокусирана върху резултати, подпомагам марки при навлизане и растеж на българския пазар чрез точен превод EN→BG, SEO локализация, маркетингово съдържание и практически цифрови решения (Wix, Google Maps, стратегии за ревюта).",
        languages: "Езици: Български (майчин), Английски, Италиански"
      },
      testimonials: { title: "Отзиви" },
      projects: {
        title: "Реални примери и проекти",
        wix: "Wix сайт: Bobi's Cars (Великобритания)",
        maps: "Google Maps и растеж на ревюта: Bobi's Cars",
        trans: "Пример за превод EN → BG"
      },
      experience: {
        title: "Професионален опит",
        freelance: "SEO маркетинг преводач и специалист по локализация",
        freelance_date: "E-commerce проекти за ЕС | Дистанционна работа – София, България",
        freelance_li1: "Отговорност за локализацията и SEO адаптацията на продуктово, категорийно и кампанийно съдържание за българския пазар",
        freelance_li2: "Изграждане и прилагане на ключова стратегия според търсенето и потребителското намерение с цел по-добра видимост в търсачките",
        freelance_li3: "Оптимизация на съдържанието за яснота, последователност на бранда и по-висока конверсия",
        freelance_li4: "Координация с международни маркетинг и съдържателни екипи за навременно реализиране на локализирани кампании",
        amazon: "Специалист „Оперативни процеси и обслужване на клиенти“",
        amazon_date: "Amazon Fulfilment Centre, Великобритания | февруари 2020 – юли 2025",
        amazon_li1: "Управление на входящи складови операции и обработка на несъответствия в наличностите",
        amazon_li2: "Работа по клиентски казуси, свързани с доставки, повредени пратки и разлики в поръчките",
        amazon_li3: "Анализ на оперативни данни и участие в подобряване на вътрешни процеси",
        amazon_li4: "Проверка и разследване на разлики между системни и реални складови наличности с цел предотвратяване на загуби"
      },
      contact: {
        title: "Свържете се",
        intro: "Искате да обсъдим проект или имате въпрос?",
        click: "Кликнете бутона по-долу",
        button: "Изпрати съобщение",
        or: "или директно на:"
      },
      footer: "© 2026 Калина Иванова. Всички права запазени. | Преводач и маркетинг специалист – София, България"
    }
  };

  function setLanguage(lang) {
    document.body.classList.add('fade');
    setTimeout(() => {
      localStorage.setItem('lang', lang);
      document.querySelectorAll('[data-i18n]').forEach(el => {
        const keys = el.getAttribute('data-i18n').split('.');
        let val = translations[lang];
        keys.forEach(k => val = val?.[k] ?? el.innerHTML); // fallback to current if missing
        if (val) el.innerHTML = val;
      });
      document.querySelectorAll('.lang-switcher button').forEach(b => 
        b.classList.toggle('active', b.dataset.lang === lang)
      );
      document.documentElement.lang = lang === 'bg' ? 'bg' : 'en';
      document.body.classList.remove('fade');
    }, 600);
  }

  let currentLang = localStorage.getItem('lang') || (navigator.language.startsWith('bg') ? 'bg' : 'en');
  setLanguage(currentLang);

  document.querySelectorAll('.lang-switcher button').forEach(btn => {
    btn.addEventListener('click', () => {
      const lng = btn.dataset.lang;
      if (lng !== currentLang) {
        currentLang = lng;
        setLanguage(lng);
      }
    });
  });

  // Scroll animations – improved
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, {
    threshold: 0.1,
    rootMargin: "0px 0px -80px 0px"
  });

  document.querySelectorAll('.card, .testimonial-item, .project-item, .experience-item').forEach(el => {
    observer.observe(el);
  });

  // Force visibility for near-top sections on load
  window.addEventListener('load', () => {
    setTimeout(() => {
      document.querySelectorAll('section').forEach(sec => {
        if (sec.getBoundingClientRect().top < window.innerHeight * 0.6) {
          const card = sec.querySelector('.card');
          if (card) card.classList.add('visible');
        }
      });
    }, 300);
  });
</script>
</body>
</html>
