---
layout: default
title: Scientific Computing and Machine Learning
description: Research in scientific computing, machine learning, dynamical systems, optimal transport, and state space models.
---

<div class="intro">
  <h1>About</h1>
  <p>My research lies at the intersection of scientific computing and machine learning, with mathematical structure as the unifying theme. I use machine learning to discover and preserve structure in stochastic scientific models, and ideas from scientific computing, probability, and dynamical systems to make modern AI more scalable and reliable.</p>
  <p class="intro-links"><a href="#research">Research</a><span aria-hidden="true">·</span><a href="{{ site.scholar_url }}">Google Scholar</a></p>
</div>

<section class="page-section" id="research">
  <div class="section-heading">
    <h2>Research areas</h2>
  </div>

  <div class="research-list">
    <article>
      <h3>Data-driven nonlinear model reduction</h3>
      <p>Learning low-dimensional dynamics from high-dimensional, multiscale stochastic systems while preserving the geometry and structure that make long-time prediction trustworthy.</p>
    </article>

    <article>
      <h3>Optimal transport at accelerator scale</h3>
      <p>Connecting entropic optimal transport with attention to develop analytic sensitivity methods and IO-aware GPU kernels for large-scale Sinkhorn computation.</p>
    </article>

    <article>
      <h3>Long-context inference and state space models</h3>
      <p>Building probabilistic and dynamical foundations for memory, stability, discretization, and quantization in selective state space models and long-context inference.</p>
    </article>

    <article>
      <h3>Multimodal AI</h3>
      <p>Collaborative work on fine-grained audio-visual reasoning, video moment retrieval, efficient token selection, and multimodal generative modeling.</p>
    </article>
  </div>
</section>

<section class="page-section" id="funding">
  <div class="section-heading">
    <h2>Current &amp; awarded support</h2>
    <p>Awarded support for research in nonlinear model reduction, optimal transport, and state space models.</p>
  </div>

  <div class="funding-grid">
    <article class="funding-card funding-card-featured">
      <div class="card-meta">
        <span class="status status-awarded">Awarded</span>
        <span>NSF CDS&amp;E-MSS · Award #2603785</span>
      </div>
      <h3><a href="https://www.nsf.gov/awardsearch/show-award/?AWD_ID=2603785">Data-Driven Nonlinear Model Reduction for High-dimensional Multi-scale Stochastic Dynamical Systems</a></h3>
      <p class="funding-details"><strong>$200,000</strong> · September 2026–August 2029</p>
      <p>PI: Felix X.-F. Ye · Co-PI: Barbara Giunti</p>
    </article>

    <article class="funding-card">
      <div class="card-meta">
        <span class="status status-active">Active</span>
        <span>IBM Center for Emerging Artificial Intelligence Systems</span>
      </div>
      <h3>BayesianMamba: Probabilistic Perspective of Generalization of State Space Models</h3>
      <p class="funding-details"><strong>$170,265 total</strong> · January 2025–December 2026</p>
      <p>Single PI · Includes an approved extension through December 31, 2026</p>
    </article>

    <article class="funding-card">
      <div class="card-meta">
        <span class="status status-active">Active</span>
        <span>Simons Foundation</span>
      </div>
      <h3>Data-driven Model Reduction in Stochastic Dynamical Systems</h3>
      <p class="funding-details"><strong>$42,000</strong> · 2023–2028</p>
      <p>Single PI · Travel Support for Mathematicians</p>
    </article>

    <article class="funding-card">
      <div class="card-meta">
        <span class="status status-active">Active</span>
        <span>SUNY AI Platform · Google Cloud Platform</span>
      </div>
      <h3>Block-Semiseparable 1-SS for Certain Type of Linear Attention</h3>
      <p class="funding-details"><strong>$10,000 in cloud compute</strong> · December 2025–December 2026</p>
      <p>Single PI</p>
    </article>
  </div>

  <p class="section-note"><strong>Prior support:</strong> AMS–Simons Travel Grant, $5,000, 2020–2023.</p>
</section>

<section class="page-section" id="publications">
  <div class="section-heading">
    <h2>Selected recent publications</h2>
    <p>Recent work spanning efficient optimal transport, multimodal AI, and scientific machine learning. See <a href="{{ site.scholar_url }}">Google Scholar</a> for the complete record.</p>
  </div>

  <div class="publication-list">
    <article class="publication-card publication-card-featured">
      <div class="card-meta">
        <span class="pub-year">2026</span>
        <span class="status status-oral">ICML Oral · Top 0.7%</span>
      </div>
      <h3><a href="https://arxiv.org/abs/2602.03067">FlashSinkhorn: IO-Aware Entropic Optimal Transport on GPU</a></h3>
      <p class="authors"><strong>Felix X.-F. Ye</strong>, Xingjie Li, An Yu, Ming-Ching Chang, Linsong Chu, and Davis Wertheimer</p>
      <p class="venue">Forty-third International Conference on Machine Learning (ICML 2026) · <a href="https://github.com/ot-triton-lab/flash-sinkhorn">Code</a></p>
    </article>

    <article class="publication-card">
      <div class="card-meta">
        <span class="pub-year">In press</span>
        <span class="status status-accepted">Accepted</span>
      </div>
      <h3><a href="https://arxiv.org/abs/2511.14143">SMART: Shot-Aware Multimodal Video Moment Retrieval with Audio-Enhanced MLLM</a></h3>
      <p class="authors">An Yu, Weiyu Lu, Jiazhi Li, Zhaorun Zhang, Yifan Shen, <strong>Felix X.-F. Ye</strong>, and Ming-Ching Chang</p>
      <p class="venue">IEEE Transactions on Multimedia</p>
    </article>

    <article class="publication-card">
      <div class="card-meta">
        <span class="pub-year">2026</span>
        <span class="status status-poster">CVPR Poster</span>
      </div>
      <h3>FAVE: A Structured Benchmark for Fine-Grained Audio-Visual Temporal Evaluation in Multimodal LLMs</h3>
      <p class="authors">Weiyu Lu, An Yu, Jiazhi Li, Zhaorun Zhang, <strong>Felix X.-F. Ye</strong>, and Ming-Ching Chang</p>
      <p class="venue">IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026)</p>
    </article>

    <article class="publication-card">
      <div class="card-meta">
        <span class="pub-year">2025</span>
        <span class="status status-poster">ICML Poster</span>
      </div>
      <h3><a href="https://openreview.net/forum?id=AjbiIcRt6q">Diffuse Everything: Multimodal Diffusion Models on Arbitrary State Spaces</a></h3>
      <p class="authors">Kevin Rojas, Yuchen Zhu, Sichen Zhu, <strong>Felix X.-F. Ye</strong>, and Molei Tao</p>
      <p class="venue">Forty-second International Conference on Machine Learning (ICML 2025)</p>
    </article>

    <article class="publication-card">
      <div class="card-meta">
        <span class="pub-year">2025</span>
        <span class="status status-journal">Journal</span>
      </div>
      <h3><a href="https://arxiv.org/abs/2407.02015">Robust First- and Second-Order Differentiation for Regularized Optimal Transport</a></h3>
      <p class="authors">Xingjie Li, Fei Lu, Molei Tao, and <strong>Felix X.-F. Ye</strong></p>
      <p class="venue"><em>SIAM Journal on Scientific Computing</em>, 47(3), C630–C654</p>
    </article>
  </div>

  <div class="publication-archive">
    <h3>Earlier publications</h3>
    <ol class="compact-publications" reversed>
      <li>
        <span class="pub-year">2024</span>
        <p><a href="https://arxiv.org/abs/2104.02120"><strong>Nonlinear Model Reduction for Slow-Fast Stochastic Systems Near Unknown Invariant Manifolds</strong></a><br><span>Felix X.-F. Ye, Sichen Yang, and Mauro Maggioni · <em>Journal of Nonlinear Science</em>, 34, Article 22.</span></p>
      </li>
      <li>
        <span class="pub-year">2024</span>
        <p><a href="https://arxiv.org/abs/1710.06078"><strong>Estimate Exponential Memory Decay in Hidden Markov Model and Its Applications to Inference</strong></a><br><span>Felix X.-F. Ye, Yi-an Ma, and Hong Qian · <em>Physica D: Nonlinear Phenomena</em>, 460, 134053.</span></p>
      </li>
      <li>
        <span class="pub-year">2023</span>
        <p><a href="https://arxiv.org/abs/2207.06012"><strong>NySALT: Nyström-type Inference-Based Schemes Adaptive to Large Time-Stepping</strong></a><br><span>Xingjie Li, Fei Lu, Molei Tao, and Felix X.-F. Ye · <em>Journal of Computational Physics</em>, 477, 111952.</span></p>
      </li>
      <li>
        <span class="pub-year">2022</span>
        <p><a href="https://arxiv.org/abs/2102.12669"><strong>ISALT: Inference-Based Schemes Adaptive to Large Time-Stepping for Locally Lipschitz Ergodic Systems</strong></a><br><span>Xingjie Li, Fei Lu, and Felix X.-F. Ye · <em>Discrete and Continuous Dynamical Systems - S</em>, 15(4), 747–771.</span></p>
      </li>
      <li>
        <span class="pub-year">2021</span>
        <p><strong>Quantifying Information Accumulation Encoded in the Dynamics of Biochemical Signaling</strong><br><span>Ying Tang, Adewunmi Adelaja, Felix X.-F. Ye, Eric J. Deeds, Roy Wollman, and Alexander Hoffmann · <em>Nature Communications</em>, 12(1), 1–10.</span></p>
      </li>
      <li>
        <span class="pub-year">2020</span>
        <p><a href="https://arxiv.org/abs/1910.11988"><strong>Synchronization in Discrete-Time, Discrete-State Random Dynamical Systems</strong></a><br><span>Wen Huang, Hong Qian, Shirou Wang, Felix X.-F. Ye, and Yingfei Yi · <em>SIAM Journal on Applied Dynamical Systems</em>, 19(1), 233–251.</span></p>
      </li>
      <li>
        <span class="pub-year">2019</span>
        <p><a href="https://arxiv.org/abs/1804.08174"><strong>Stochastic Dynamics II: Finite Random Dynamical Systems, Linear Representation, and Entropy Production</strong></a><br><span>Felix X.-F. Ye and Hong Qian · <em>Discrete and Continuous Dynamical Systems - B</em>, 24(8), 4341–4366.</span></p>
      </li>
      <li>
        <span class="pub-year">2019</span>
        <p><a href="https://arxiv.org/abs/1611.09542"><strong>Time-Dependent Saddle–Node Bifurcation: Breaking Time and the Point of No Return in a Non-Autonomous Model of Critical Transitions</strong></a><br><span>Jeremiah H. Li, Felix X.-F. Ye, Hong Qian, and Sui Huang · <em>Physica D: Nonlinear Phenomena</em>, 395, 7–14.</span></p>
      </li>
      <li>
        <span class="pub-year">2018</span>
        <p><a href="https://arxiv.org/abs/1704.04361"><strong>Dynamic Looping of a Free-Draining Polymer</strong></a><br><span>Felix X.-F. Ye, Panos Stinis, and Hong Qian · <em>SIAM Journal on Applied Mathematics</em>, 78(1), 104–123.</span></p>
      </li>
      <li>
        <span class="pub-year">2017</span>
        <p><strong>Stochastic Dynamics: Models for Intrinsic and Extrinsic Noises and Their Applications</strong><br><span>Yi-an Ma, Hong Qian, and Felix X.-F. Ye · <em>SCIENTIA SINICA Mathematica</em>, 47(12), 1693–1702.</span></p>
      </li>
      <li>
        <span class="pub-year">2016</span>
        <p><strong>Stochastic Dynamics: Markov Chains and Random Transformations</strong><br><span>Felix X.-F. Ye, Yue Wang, and Hong Qian · <em>Discrete and Continuous Dynamical Systems - B</em>, 21(7), 2337–2361.</span></p>
      </li>
      <li>
        <span class="pub-year">2013</span>
        <p><strong>Evolution of Recombination Rates in a Multi-Locus, Haploid-Selection, Symmetric-Viability Model</strong><br><span>J. R. Chasnov and Felix X.-F. Ye · <em>Theoretical Population Biology</em>, 83, 155–165.</span></p>
      </li>
    </ol>
  </div>
</section>

<section class="page-section" id="preprints">
  <div class="section-heading">
    <h2>Preprints &amp; submitted work</h2>
  </div>

  <div class="submission-list">
    <article class="submission-card">
      <span class="status status-submitted">Submitted</span>
      <h3><a href="https://arxiv.org/abs/2603.24680">ReDiPrune: Relevance-Diversity Pre-Projection Token Pruning for Efficient Multimodal LLMs</a></h3>
      <p>An Yu, Ting Yu Tsai, Zhaorun Zhang, Weiyu Lu, <strong>Felix X.-F. Ye</strong>, and Ming-Ching Chang</p>
    </article>

    <article class="submission-card">
      <span class="status status-submitted">Submitted</span>
      <h3><a href="https://arxiv.org/abs/2603.26780">RatSeizure: A Benchmark and Saliency-Context Transformer for Rat Seizure Localization</a></h3>
      <p>Ting Yu Tsai, An Yu, Linda Lee, <strong>Felix X.-F. Ye</strong>, Daniel S. Shin, Tsang-Jiun Kao, Xingjie Li, and Ming-Ching Chang</p>
    </article>

    <article class="submission-card">
      <span class="status status-submitted">Submitted</span>
      <h3><a href="https://arxiv.org/abs/2604.16282">Geometric Regularization of Autoencoders via Observed Stochastic Dynamics</a></h3>
      <p>Sean Hill and <strong>Felix X.-F. Ye</strong></p>
    </article>

    <article class="submission-card">
      <span class="status status-submitted">Submitted</span>
      <h3><a href="https://icml.cc/virtual/2026/75265">DropKV: Decoupling Residual-Output Perturbation for Near-Optimal KV-Cache Eviction</a></h3>
      <p>Aozhong Zhang, Selcuk Gurses, Yanxia Deng, Naigang Wang, Chi-Chun Liu, Davis Wertheimer, Derrick Liu, Xin Li, Zi Yang, <strong>Felix X.-F. Ye</strong>, and Penghang Yin</p>
    </article>

    <article class="submission-card">
      <span class="status status-submitted">Submitted</span>
      <h3>Memory Along the Chain: Disentangling Dynamics from Discretization in Mamba</h3>
      <p><strong>Felix X.-F. Ye</strong>, Ting Yu Tsai, Ming-Ching Chang, and Davis Wertheimer</p>
    </article>

    <article class="submission-card">
      <span class="status status-submitted">Submitted</span>
      <h3><a href="https://arxiv.org/abs/2606.01548">Minimal Intersection Radius for <em>n</em> Growing, Non-Homogeneous Ellipsoids in R<sup>d</sup></a></h3>
      <p>Barbara Giunti, Sean Hill, and <strong>Felix X.-F. Ye</strong></p>
    </article>
  </div>
</section>

<section class="page-section" id="software">
  <div class="section-heading">
    <h2>Research software</h2>
  </div>
  <div class="software-links">
    <a href="https://github.com/ot-triton-lab/flash-sinkhorn"><strong>FlashSinkhorn</strong><span>IO-aware entropic optimal transport on GPU</span></a>
    <a href="https://github.com/yexf308/OTT-Hessian"><strong>OTT-Hessian</strong><span>Analytical differentiation for regularized optimal transport</span></a>
    <a href="https://github.com/yexf308/ATLAS"><strong>ATLAS</strong><span>Nonlinear reduction of stochastic dynamical systems</span></a>
  </div>
</section>
