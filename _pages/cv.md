---
layout: single
title: "Résumé"
description: "Pengyu Chang’s education, software engineering experience, research, projects, and technical skills."
permalink: /cv/
author_profile: false
portfolio_cv: true
redirect_from:
  - /resume
---

<div class="portfolio-cv">
  <header class="cv-intro">
    <div>
      <p class="cv-kicker">Software engineering · Machine learning research</p>
      <h1>Pengyu Chang</h1>
      <p>CMU M.S. Information Networking student with experience in machine learning research and software engineering.</p>
    </div>
    <div class="cv-actions">
      <button type="button" class="cv-print" onclick="window.print()">Print / save PDF</button>
      <a href="mailto:pengyuch@andrew.cmu.edu">Email</a>
      <a href="https://www.linkedin.com/in/pengyuch/">LinkedIn</a>
      <a href="https://github.com/jmueducn">GitHub</a>
    </div>
  </header>

  <section class="cv-section" aria-labelledby="cv-education">
    <h2 id="cv-education">Education</h2>
    <div class="cv-entry">
      <div class="cv-date">Aug 2025—May 2027</div>
      <div>
        <h3>Carnegie Mellon University</h3>
        <p class="cv-subtitle">M.S. in Information Networking · Pittsburgh, PA</p>
        <ul>
          <li>GPA: 4.0/4.0.</li>
          <li>Teaching Assistant, Introduction to Deep Learning: mentored final projects, led recitations, and held office hours.</li>
        </ul>
      </div>
    </div>
    <div class="cv-entry">
      <div class="cv-date">Aug 2021—Jun 2025</div>
      <div>
        <h3>Shanghai Jiao Tong University</h3>
        <p class="cv-subtitle">B.E. in Software Engineering · Shanghai, China</p>
      </div>
    </div>
  </section>

  <section class="cv-section" aria-labelledby="cv-experience">
    <h2 id="cv-experience">Experience</h2>
    <div class="cv-entry">
      <div class="cv-date">May—Aug 2026</div>
      <div>
        <h3>Google</h3>
        <p class="cv-subtitle">Software Engineering Intern · San Francisco, CA</p>
        <ul>
          <li>Built an end-to-end synthetic-data generation pipeline for Gemini content safety across multiple policy areas.</li>
          <li>Designed a two-stage approach using structured policy taxonomies and conditional generation.</li>
          <li>Evaluated downstream safety classifiers using accuracy, F1, and PR-AUC and iterated on both pipeline stages.</li>
        </ul>
      </div>
    </div>
    <div class="cv-entry">
      <div class="cv-date">Jul—Aug 2024</div>
      <div>
        <h3>Electronic Arts</h3>
        <p class="cv-subtitle">Software Engineer Intern · Shanghai, China</p>
        <ul>
          <li>Integrated Kiali service-mesh visualization into a Grafana and Prometheus monitoring stack and reduced Kiali data volume by 85%, resolving memory bottlenecks.</li>
        </ul>
      </div>
    </div>
    <div class="cv-entry">
      <div class="cv-date">Jun 2024—Jun 2025</div>
      <div>
        <h3>Shanghai Jiao Tong University</h3>
        <p class="cv-subtitle">Research Assistant · Shanghai, China</p>
        <ul>
          <li>Contributed to <a href="https://arxiv.org/abs/2508.14723">LMTransplant</a>, identifying data-scarce downstream tasks, engineering synthetic-data prompts, and evaluating realistic few-shot NLP scenarios.</li>
          <li>Designed and implemented <a href="https://arxiv.org/abs/2602.08146">AdverTest</a>, a first-author multi-agent LLM framework for Java unit-test generation.</li>
          <li>Evaluated fault detection, line coverage, and branch coverage against LLM-based methods and EvoSuite.</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="cv-section" aria-labelledby="cv-projects">
    <h2 id="cv-projects">Selected projects</h2>
    <div class="cv-entry">
      <div class="cv-date">Oct 2025—Mar 2026</div>
      <div>
        <h3><a href="https://arxiv.org/abs/2603.28021">CoLMbo-DF</a></h3>
        <p class="cv-subtitle">Audio-language-model research for deepfake detection</p>
        <ul>
          <li>Led construction of FakeReason, an approximately 133K-pair audio dataset with acoustic chain-of-thought annotations.</li>
          <li>Built a pipeline combining ASVspoof 2019 LA and VoxCeleb2 with approximately 20K synthesized deepfakes and acoustically grounded reasoning annotations.</li>
          <li>A 1B-parameter model trained with the dataset reached a reported 98.7% accuracy on ASVspoof 2019.</li>
        </ul>
      </div>
    </div>
    <div class="cv-entry">
      <div class="cv-date">Apr—Jun 2024</div>
      <div>
        <h3>Minik8s</h3>
        <p class="cv-subtitle">Mini container orchestration system · Go</p>
        <ul>
          <li>Implemented API-object management, deployment and autoscaling control loops, and NFS-backed persistent volumes and claims.</li>
        </ul>
      </div>
    </div>
    <div class="cv-entry">
      <div class="cv-date">Apr—May 2023</div>
      <div>
        <h3><a href="https://github.com/jmueducn/LSM-KV">LSM-KV</a></h3>
        <p class="cv-subtitle">Log-structured key-value store · C++</p>
        <ul>
          <li>Built memory and disk structures with skip lists and Bloom filters, then tuned throughput across LSM-tree configurations.</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="cv-section cv-skills" aria-labelledby="cv-skills">
    <h2 id="cv-skills">Skills</h2>
    <p><strong>Languages</strong> Python, C++, C, Java, Go, JavaScript, TypeScript</p>
    <p><strong>ML tools</strong> PyTorch, LangChain, LLM APIs</p>
    <p><strong>Research areas</strong> Synthetic data, model evaluation, NLP, speech and deepfake detection</p>
    <p><strong>Systems / Data</strong> Kafka, Redis, MySQL, MongoDB, Prometheus, Grafana, Istio, NFS, storage engines</p>
  </section>
</div>
