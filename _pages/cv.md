---
layout: single
title: "Résumé"
description: "Pengyu Chang’s education, software engineering experience, research, projects, and technical skills."
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<div class="simple-cv">
  <p class="cv-actions">
    <button type="button" class="simple-print" onclick="window.print()">Print / save PDF</button>
  </p>

  <section aria-labelledby="cv-education">
    <h2 id="cv-education">Education</h2>

    <article class="simple-entry">
      <p class="entry-year">2025–27</p>
      <div>
        <h3>Carnegie Mellon University</h3>
        <p class="entry-subtitle">M.S. in Information Networking · Pittsburgh, PA</p>
        <ul>
          <li>GPA: 4.0/4.0.</li>
          <li>Teaching Assistant, Introduction to Deep Learning.</li>
        </ul>
      </div>
    </article>

    <article class="simple-entry">
      <p class="entry-year">2021–25</p>
      <div>
        <h3>Shanghai Jiao Tong University</h3>
        <p class="entry-subtitle">B.E. in Software Engineering · Shanghai, China</p>
      </div>
    </article>
  </section>

  <section aria-labelledby="cv-experience">
    <h2 id="cv-experience">Experience</h2>

    <article class="simple-entry">
      <p class="entry-year">2026</p>
      <div>
        <h3>Google</h3>
        <p class="entry-subtitle">Software Engineering Intern · San Francisco, CA</p>
        <ul>
          <li>Built an end-to-end synthetic-data generation pipeline for Gemini content safety across multiple policy areas.</li>
          <li>Designed a two-stage approach using structured policy taxonomies and conditional generation.</li>
          <li>Evaluated downstream safety classifiers using accuracy, F1, and PR-AUC and iterated on both pipeline stages.</li>
        </ul>
      </div>
    </article>

    <article class="simple-entry">
      <p class="entry-year">2024</p>
      <div>
        <h3>Electronic Arts</h3>
        <p class="entry-subtitle">Software Engineer Intern · Shanghai, China</p>
        <ul>
          <li>Integrated Kiali into a Grafana and Prometheus monitoring stack and reduced Kiali data volume by 85%, resolving memory bottlenecks.</li>
        </ul>
      </div>
    </article>

    <article class="simple-entry">
      <p class="entry-year">2024–25</p>
      <div>
        <h3>Shanghai Jiao Tong University</h3>
        <p class="entry-subtitle">Research Assistant · Shanghai, China</p>
        <ul>
          <li>Contributed to <a href="https://arxiv.org/abs/2508.14723">LMTransplant</a>, including task selection, synthetic-data prompt design, and evaluation.</li>
          <li>Designed and implemented <a href="https://arxiv.org/abs/2602.08146">AdverTest</a>, a first-author multi-agent framework for Java unit-test generation.</li>
        </ul>
      </div>
    </article>
  </section>

  <section aria-labelledby="cv-projects">
    <h2 id="cv-projects">Selected projects</h2>

    <article class="simple-entry">
      <p class="entry-year">2025–26</p>
      <div>
        <h3><a href="https://arxiv.org/abs/2603.28021">CoLMbo-DF</a></h3>
        <p>Led construction of FakeReason, an approximately 133K-pair audio dataset with acoustic reasoning annotations. A 1B-parameter model trained with the dataset reached a reported 98.7% accuracy on ASVspoof 2019.</p>
      </div>
    </article>

    <article class="simple-entry">
      <p class="entry-year">2024</p>
      <div>
        <h3>Minik8s</h3>
        <p>A container orchestration system in Go with control loops, horizontal autoscaling, and NFS-backed persistent storage.</p>
      </div>
    </article>

    <article class="simple-entry">
      <p class="entry-year">2023</p>
      <div>
        <h3><a href="https://github.com/jmueducn/LSM-KV">LSM-KV</a></h3>
        <p>A C++ key-value store using skip lists, Bloom filters, and an LSM-tree design.</p>
      </div>
    </article>
  </section>

  <section class="cv-skills" aria-labelledby="cv-skills">
    <h2 id="cv-skills">Skills</h2>
    <p><strong>Languages:</strong> Python, C++, C, Java, Go, JavaScript, TypeScript</p>
    <p><strong>ML tools:</strong> PyTorch, LangChain, LLM APIs</p>
    <p><strong>Systems and data:</strong> Kafka, Redis, MySQL, MongoDB, Prometheus, Grafana, Istio, NFS</p>
  </section>
</div>
