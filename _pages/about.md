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
      Carnegie Mellon University · Pittsburgh, PA
    </div>

    <p class="hero-kicker">M.S. Information Networking · 2027</p>
    <h1 id="intro-title">Pengyu Chang</h1>
    <p class="hero-summary">
      I’m a master’s student at Carnegie Mellon University working on machine
      learning and software systems. My interests include synthetic data,
      model evaluation, speech, and systems infrastructure.
    </p>

    <div class="hero-actions" aria-label="Primary links">
      <a class="portfolio-button portfolio-button--primary" href="#work">Selected work <span aria-hidden="true">↓</span></a>
      <a class="portfolio-button" href="/cv/">Résumé <span aria-hidden="true">↗</span></a>
      <a class="portfolio-text-link" href="https://github.com/jmueducn">GitHub <span aria-hidden="true">↗</span></a>
    </div>

  </section>

  <section class="home-section" id="work" aria-labelledby="work-title">
    <header class="section-heading">
      <p class="section-index">01 / Selected work</p>
      <h2 id="work-title">Research and projects</h2>
    </header>

    <article class="spotlight-card">
      <div class="spotlight-meta">
        <span>Speech · Deepfake detection</span>
        <span>2025—26</span>
      </div>
      <div class="spotlight-body">
        <div>
          <p class="card-label">Research project</p>
          <h3>CoLMbo-DF</h3>
          <p class="card-copy">
            CoLMbo-DF studies interpretable deepfake speech detection with
            audio-language models. I led the construction of FakeReason, a
            dataset with acoustic reasoning annotations.
          </p>
          <a class="card-link" href="https://arxiv.org/abs/2603.28021">Read the preprint <span aria-hidden="true">↗</span></a>
        </div>
        <dl class="metric-list">
          <div>
            <dt>~133K</dt>
            <dd>audio pairs in FakeReason</dd>
          </div>
          <div>
            <dt>98.7%</dt>
            <dd>reported accuracy on ASVspoof 2019</dd>
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
          A multi-agent framework for generating Java unit tests. The study
          compares fault detection and code coverage with LLM-based and
          search-based baselines.
        </p>
        <a class="card-link" href="https://arxiv.org/abs/2602.08146">Read the preprint <span aria-hidden="true">↗</span></a>
      </article>

      <article class="project-card project-card--dark">
        <div class="project-topline">
          <span>03</span>
          <span>Few-shot NLP · Synthetic data</span>
        </div>
        <h3>LMTransplant</h3>
        <p>
          Research on synthetic data augmentation for few-shot NLP tasks. I
          worked on task selection, prompt design, and evaluation.
        </p>
        <a class="card-link" href="https://arxiv.org/abs/2508.14723">Read the preprint <span aria-hidden="true">↗</span></a>
      </article>
    </div>

    <div class="systems-intro">
      <p class="section-index">Systems work</p>
      <p>Projects in Go and C++ covering orchestration and storage.</p>
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
      <h2 id="experience-title">Experience</h2>
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
            generation, then evaluated downstream classifiers with accuracy,
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
            Prometheus monitoring stack. Reduced Kiali data volume by 85%,
            resolving memory bottlenecks in the monitoring stack.
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
            testing, from identifying data-scarce downstream tasks to
            designing generation frameworks and evaluating fault detection.
          </p>
        </div>
      </article>
    </div>
  </section>

  <section class="home-section" id="about" aria-labelledby="about-title">
    <header class="section-heading">
      <p class="section-index">03 / About</p>
      <h2 id="about-title">About</h2>
    </header>

    <div class="about-grid">
      <div class="portrait-frame">
        <img src="/images/picture_1.jpg" alt="Portrait of Pengyu Chang" loading="lazy" width="600" height="600" />
      </div>
      <div class="about-copy">
        <p class="about-lead">
          I’m an M.S. Information Networking student at Carnegie Mellon
          University and a teaching assistant for Introduction to Deep
          Learning. Before CMU, I studied Software Engineering at Shanghai
          Jiao Tong University.
        </p>
        <p>
          I’m interested in both machine learning research and software
          engineering, especially data generation, evaluation, speech, and
          systems infrastructure.
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
    <h2 id="contact-title">Contact</h2>
    <div class="contact-links">
      <a class="portfolio-button portfolio-button--primary" href="mailto:pengyuch@andrew.cmu.edu">Email me <span aria-hidden="true">↗</span></a>
      <a class="portfolio-button" href="https://www.linkedin.com/in/pengyuch/">LinkedIn <span aria-hidden="true">↗</span></a>
      <a class="portfolio-button" href="https://github.com/jmueducn">GitHub <span aria-hidden="true">↗</span></a>
    </div>
  </section>
</div>
