---
permalink: /
author_profile: false
portfolio_home: true
redirect_from:
  - /about/
  - /about.html
---

<div class="portfolio-home">
  <section class="home-hero" aria-labelledby="intro-title">
    <div class="hero-signal" aria-label="Current status">
      <span class="signal-dot" aria-hidden="true"></span>
      CMU · Pittsburgh, PA · M.S. 2027
    </div>

    <p class="hero-kicker">Software engineer · AI systems researcher</p>
    <h1 id="intro-title">AI systems,<br><em>measured.</em></h1>
    <p class="hero-summary">
      I’m Pengyu Chang, a CMU graduate student building dependable AI and
      software systems across synthetic data, LLM safety, speech,
      observability, and storage.
    </p>

    <div class="hero-actions" aria-label="Primary links">
      <a class="portfolio-button portfolio-button--primary" href="#work">Explore my work <span aria-hidden="true">↘</span></a>
      <a class="portfolio-button" href="/cv/">View résumé <span aria-hidden="true">↗</span></a>
      <a class="portfolio-text-link" href="https://github.com/jmueducn">GitHub <span aria-hidden="true">↗</span></a>
    </div>

    <div class="hero-proof" aria-label="Profile highlights">
      <div class="proof-item">
        <strong>4.0</strong>
        <span>CMU GPA</span>
      </div>
      <div class="proof-item">
        <strong>85%</strong>
        <span>Less observability data</span>
      </div>
      <div class="proof-item">
        <strong>~133K</strong>
        <span>Annotated audio pairs</span>
      </div>
      <div class="proof-item">
        <strong>TA</strong>
        <span>CMU deep learning</span>
      </div>
    </div>
  </section>

  <section class="home-section" id="work" aria-labelledby="work-title">
    <header class="section-heading">
      <p class="section-index">01 / Selected work</p>
      <h2 id="work-title">Research that makes model behavior inspectable.</h2>
    </header>

    <article class="spotlight-card">
      <div class="spotlight-meta">
        <span>Speech · Trustworthy AI</span>
        <span>2025—26</span>
      </div>
      <div class="spotlight-body">
        <div>
          <p class="card-label">Featured research</p>
          <h3>CoLMbo-DF</h3>
          <p class="card-copy">
            An audio-language-model approach to interpretable deepfake speech
            detection, built on a large acoustic reasoning dataset.
          </p>
          <a class="card-link" href="https://arxiv.org/abs/2603.28021">Read the preprint <span aria-hidden="true">↗</span></a>
        </div>
        <dl class="metric-list">
          <div>
            <dt>~133K</dt>
            <dd>annotated audio pairs</dd>
          </div>
          <div>
            <dt>98.7%</dt>
            <dd>reported ASVspoof accuracy</dd>
          </div>
          <div>
            <dt>1B</dt>
            <dd>parameter model</dd>
          </div>
        </dl>
      </div>
    </article>

    <div class="project-grid">
      <article class="project-card">
        <div class="project-topline">
          <span>02</span>
          <span>Multi-agent LLMs · Java</span>
        </div>
        <h3>AdverTest</h3>
        <p>
          A multi-agent framework that generates Java unit tests to expose
          real faults—not just increase surface-level coverage.
        </p>
        <div class="project-result">
          <strong>+8.56%</strong>
          <span>reported fault detection vs. the strongest cited LLM method</span>
        </div>
        <a class="card-link" href="https://arxiv.org/abs/2602.08146">Read the preprint <span aria-hidden="true">↗</span></a>
      </article>

      <article class="project-card project-card--dark">
        <div class="project-topline">
          <span>03</span>
          <span>Few-shot NLP · Synthetic data</span>
        </div>
        <h3>LMTransplant</h3>
        <p>
          Data augmentation for few-shot language tasks, shaped through prompt
          engineering and evaluated in realistic, data-scarce settings.
        </p>
        <div class="project-result">
          <strong>Data → signal</strong>
          <span>task selection, generation prompts, and evaluation</span>
        </div>
        <a class="card-link" href="https://arxiv.org/abs/2508.14723">Read the preprint <span aria-hidden="true">↗</span></a>
      </article>
    </div>

    <div class="systems-intro">
      <p class="section-index">Systems work</p>
      <p>Small enough to understand end to end. Deep enough to reveal the tradeoffs.</p>
    </div>

    <div class="systems-grid">
      <article class="system-card">
        <span class="system-number">A / 02</span>
        <div>
          <h3>Minik8s</h3>
          <p>Go control loops, horizontal autoscaling, API-object management, and NFS-backed persistent storage.</p>
          <ul class="tag-list" aria-label="Minik8s technologies">
            <li>Go</li><li>Control loops</li><li>NFS</li>
          </ul>
        </div>
      </article>

      <article class="system-card">
        <span class="system-number">B / 02</span>
        <div>
          <h3>LSM-KV</h3>
          <p>A C++ key-value store spanning memory and disk, with skip lists, Bloom filters, and tuned LSM-tree configurations.</p>
          <ul class="tag-list" aria-label="LSM-KV technologies">
            <li>C++</li><li>Storage</li><li>Performance</li>
          </ul>
          <a class="card-link" href="https://github.com/jmueducn/LSM-KV">View code <span aria-hidden="true">↗</span></a>
        </div>
      </article>
    </div>
  </section>

  <section class="home-section" id="experience" aria-labelledby="experience-title">
    <header class="section-heading">
      <p class="section-index">02 / Experience</p>
      <h2 id="experience-title">From model evaluation to production observability.</h2>
    </header>

    <div class="experience-list">
      <article class="experience-item">
        <p class="experience-time">May—Aug 2026</p>
        <div class="experience-body">
          <div class="experience-heading">
            <h3>Google</h3>
            <p>Software Engineering Intern · San Francisco</p>
          </div>
          <p>
            Built an end-to-end synthetic-data pipeline for Gemini content
            safety. Designed structured policy taxonomies and conditional
            generation for broader coverage and fine-grained distribution
            control, then evaluated downstream classifiers with accuracy,
            F1, and PR-AUC.
          </p>
        </div>
      </article>

      <article class="experience-item">
        <p class="experience-time">Jul—Aug 2024</p>
        <div class="experience-body">
          <div class="experience-heading">
            <h3>Electronic Arts</h3>
            <p>Software Engineer Intern · Shanghai</p>
          </div>
          <p>
            Integrated service-mesh visualization into a Grafana and
            Prometheus monitoring stack, reducing its data volume by 85% to
            resolve memory bottlenecks and speed up error identification.
          </p>
        </div>
      </article>

      <article class="experience-item">
        <p class="experience-time">Jun 2024—Jun 2025</p>
        <div class="experience-body">
          <div class="experience-heading">
            <h3>Shanghai Jiao Tong University</h3>
            <p>Research Assistant · Shanghai</p>
          </div>
          <p>
            Worked across few-shot NLP data augmentation and multi-agent LLM
            testing, from finding meaningful downstream tasks to designing
            generation frameworks and evaluating fault-detection capability.
          </p>
        </div>
      </article>
    </div>
  </section>

  <section class="home-section" id="about" aria-labelledby="about-title">
    <header class="section-heading">
      <p class="section-index">03 / About</p>
      <h2 id="about-title">An engineer who follows evidence across boundaries.</h2>
    </header>

    <div class="about-grid">
      <div class="portrait-frame">
        <img src="/images/picture_1.jpg" alt="Portrait of Pengyu Chang" loading="lazy" width="600" height="600" />
      </div>
      <div class="about-copy">
        <p class="about-lead">
          I’m pursuing an M.S. in Information Networking at Carnegie Mellon,
          where I also serve as a teaching assistant for Introduction to Deep
          Learning. Before CMU, I earned a B.E. in Software Engineering from
          Shanghai Jiao Tong University.
        </p>
        <p>
          My work moves between AI research and systems engineering because
          reliable models need both: careful data and evaluation, plus the
          infrastructure to make results observable and repeatable.
        </p>
        <div class="education-grid" aria-label="Education">
          <div>
            <span>2025—2027</span>
            <strong>Carnegie Mellon University</strong>
            <p>M.S. Information Networking · GPA 4.0/4.0</p>
          </div>
          <div>
            <span>2021—2025</span>
            <strong>Shanghai Jiao Tong University</strong>
            <p>B.E. Software Engineering</p>
          </div>
        </div>
      </div>
    </div>

    <div class="skills-rail" aria-label="Technical skills">
      <span>Python</span><span>C++</span><span>Java</span><span>Go</span><span>PyTorch</span><span>LangChain</span><span>Kafka</span><span>Redis</span><span>Prometheus</span><span>Grafana</span>
    </div>
  </section>

  <section class="contact-section" id="contact" aria-labelledby="contact-title">
    <p class="section-index">04 / Contact</p>
    <h2 id="contact-title">Have a hard problem?<br><em>Let’s make it measurable.</em></h2>
    <div class="contact-links">
      <a class="portfolio-button portfolio-button--primary" href="mailto:pengyuch@andrew.cmu.edu">Email me <span aria-hidden="true">↗</span></a>
      <a class="portfolio-button" href="https://www.linkedin.com/in/pengyuch/">LinkedIn <span aria-hidden="true">↗</span></a>
      <a class="portfolio-button" href="https://github.com/jmueducn">GitHub <span aria-hidden="true">↗</span></a>
    </div>
  </section>
</div>
