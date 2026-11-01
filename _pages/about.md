---
layout: single
title: "Matthew P. Maisonave"
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<link rel="stylesheet" href="{{ '/assets/css/portfolio.css' | relative_url }}">

<div class="mm-portfolio">
  <div class="mm-hero">
    <p class="mm-kicker">COMPUTER SCIENCE · GPU COMPUTING · RESEARCH</p>
    <p class="mm-lead">I am a graduate computer science student and published researcher at <strong>Old Dominion University</strong>, focused on GPU-accelerated software, high-performance computing, and computer architecture.</p>
    <p>I develop and evaluate CUDA and Triton kernels, study performance through careful benchmarking, and build low-level C++ systems tools. My interests span GPU memory hierarchies, parallel algorithms, performance engineering, and reproducible research.</p>
    <div class="mm-actions">
      <a class="mm-button mm-button-primary" href="{{ '/files/Matthew_Maisonave_Resume.pdf' | relative_url }}">View résumé (PDF)</a>
      <a class="mm-button mm-button-secondary" href="https://github.com/MatthewMaisonave">GitHub projects</a>
      <a class="mm-button mm-button-secondary" href="https://www.linkedin.com/in/matthew-maisonave-442633282/">LinkedIn</a>
    </div>
    <p class="mm-note">M.S. Computer Science, expected December 2026 · Chesapeake, Virginia</p>
  </div>

  <section id="projects" class="mm-section">
    <div class="mm-section-heading">
      <h2>Selected technical projects</h2>
      <p>Correctness, measured performance, and hardware-aware design.</p>
    </div>
    <div class="mm-grid">
      <article class="mm-card">
        <p class="mm-label">CUDA · TRITON · C++</p>
        <h3>GPU-Accelerated Fused GEMM</h3>
        <p>Implemented and validated CPU, naive CUDA, tiled, register-blocked, fused, and Triton versions of <code>C = ReLU(αAB + bias)</code>, including square and rectangular workloads.</p>
        <p class="mm-result"><strong>Up to 7.00×</strong> faster than the naive fused CUDA kernel in the measured workloads.</p>
      </article>
      <article class="mm-card">
        <p class="mm-label">C++ · COMPUTER ARCHITECTURE</p>
        <h3>GPU Cache Simulator</h3>
        <p>Developed a configurable set-associative cache simulator with address decomposition, LRU replacement, dirty-line tracking, write-back behavior, and deterministic tests.</p>
        <p class="mm-result">Focus: <strong>memory hierarchy and architecture reasoning</strong>.</p>
      </article>
      <article class="mm-card">
        <p class="mm-label">TRITON · PYTORCH · SCIPY</p>
        <h3>Sparse Matrix–Vector Multiplication</h3>
        <p>Created a Triton CSR SpMV kernel and GPU-resident benchmarking workflow, validating against CPU CSR, SciPy, and PyTorch implementations.</p>
        <p class="mm-result"><strong>7.29×</strong> speedup over SciPy CPU on a measured 1M-row, 8M-nonzero workload.</p>
      </article>
      <article class="mm-card">
        <p class="mm-label">CUDA · MEMORY OPTIMIZATION</p>
        <h3>CUDA Stencil Experiments</h3>
        <p>Implemented naive and shared-memory 1D/2D stencil kernels and ran a reproducible 35-configuration sweep across radii, block sizes, and problem sizes.</p>
        <p class="mm-result">Finding: shared memory was <strong>slower on all 15 measured 2D configurations</strong>—an instructive performance tradeoff.</p>
      </article>
    </div>
    <p class="mm-section-link">Explore additional code and experiments on <a href="https://github.com/MatthewMaisonave">my GitHub profile</a>. Individual project repository links can be added as projects are published.</p>
  </section>

  <section id="experience" class="mm-section">
    <h2>Research experience</h2>
    <div class="mm-entry">
      <div><h3>U-RISE Trainee · Bioinformatics Research</h3><span>Old Dominion University Research Foundation</span></div>
      <span class="mm-date">May 2024 – May 2025</span>
    </div>
    <p>Built a reproducible Python pipeline integrating genomic, transcriptomic, and proteomic data, automating ingestion, validation, annotation, and dataset creation for downstream analysis.</p>
    <div class="mm-entry">
      <div><h3>REU Intern · Scientific Claim Verification</h3><span>Old Dominion University Research Foundation</span></div>
      <span class="mm-date">May 2024 – August 2024</span>
    </div>
    <p>Developed experimental Python pipelines to evaluate language models on scientific news verification using ground-truth labels and precision, recall, and F1-score.</p>
    <div class="mm-entry">
      <div><h3>Undergraduate Research Assistant</h3><span>Old Dominion University · Department of Computer Science</span></div>
      <span class="mm-date">August 2023 – September 2024</span>
    </div>
    <p>Curated and validated datasets for benchmarking multimodal retrieval of scientific patent figures, collaborating on annotation consistency and reproducibility.</p>
  </section>

  <section id="publications" class="mm-section">
    <h2>Selected publications</h2>
    <ol class="mm-publications">
      <li><a href="https://doi.org/10.1038/s41598-026-56104-5">Comparative analysis of six new chloroplast genomes in <em>Platanthera</em> (Orchidaceae) enhances understanding of its diversification</a>. <em>Scientific Reports</em> 16, 24675 (2026).</li>
      <li><a href="https://doi.org/10.1007/978-3-032-05409-8_7">SciTableQA: A Question-Answering Benchmark for Complex Scientific Tables</a>. <em>TPDL 2025</em>.</li>
      <li><a href="https://ceur-ws.org/Vol-4161/paper1.pdf">Humans vs. LLMs on Open Domain Scientific Claim Verification: A Baseline Study</a>. <em>AI4SciSci 2025</em>.</li>
    </ol>
  </section>

  <section id="education" class="mm-section">
    <h2>Education & skills</h2>
    <div class="mm-entry">
      <div><h3>Old Dominion University</h3><span>M.S., Computer Science</span></div>
      <span class="mm-date">Expected December 2026</span>
    </div>
    <div class="mm-entry">
      <div><h3>Old Dominion University</h3><span>B.S., Computer Science</span></div>
      <span class="mm-date">December 2025</span>
    </div>
    <p><strong>GPU & systems:</strong> CUDA, Triton, PyTorch, parallel computing, GPU performance analysis, PTX/SASS inspection, C++, Linux, Git, testing and debugging.</p>
    <p><strong>Programming & data:</strong> Python, Rust, SQL, Java, Bash, JavaScript, NumPy, pandas, SciPy, and scientific computing.</p>
  </section>

  <section id="contact" class="mm-section mm-contact">
    <h2>Connect</h2>
    <p>I'm interested in GPU architecture, kernel engineering, and systems software. You can reach me via <a href="mailto:matthewmaisonave@gmail.com">email</a>, <a href="https://www.linkedin.com/in/matthew-maisonave-442633282/">LinkedIn</a>, or <a href="https://github.com/MatthewMaisonave">GitHub</a>.</p>
    <p><a class="mm-button mm-button-primary" href="{{ '/files/Matthew_Maisonave_Resume.pdf' | relative_url }}">Download my résumé (PDF)</a></p>
  </section>
</div>
