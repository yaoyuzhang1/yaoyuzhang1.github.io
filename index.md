---
layout: page
description: Yaoyu Zhang is an associate professor working on the theoretical foundations of deep learning.
home_style: true
body_class: "site-surface academic-surface home-surface"
---

<div class="home-page" markdown="1">

<section class="home-hero" aria-labelledby="home-title">
  <p class="home-eyebrow">About Me</p>
  <h1 id="home-title">Yaoyu Zhang <span>张耀宇</span></h1>
  <figure class="home-portrait">
    <img src="{{ '/images/head.jpg' | relative_url }}" width="295" height="413" alt="Portrait of Yaoyu Zhang">
  </figure>
  <p class="home-hero__bio">I am a Tenure-track Associate Professor at the Institute of Natural Sciences and School of Mathematical Sciences of Shanghai Jiao Tong University. I earned my Bachelor's degree in Physics (minor in mathematics) in 2012, and Ph.D. in Mathematics in 2016 from Shanghai Jiao Tong University adviced by David Cai and Douglas Zhou. From 2016 to 2020, I conducted postdoctoral research at New York University Abu Dhabi &amp; Courant Institute, as well as the Institute for Advanced Study in Princeton. My research focuses on the theoretical foundation of deep learning, particularly the nonlinear training dynamics and condensation phenomenon of deep learning.</p>
  <nav class="home-actions" aria-label="Profile links">
    <a href="mailto:zhyy.sjtu@sjtu.edu.cn">Email</a>
    <a href="{{ '/file/CV.pdf' | relative_url }}">My CV</a>
    <a href="https://scholar.google.com/citations?hl=en&amp;user=ZSZ0TkIAAAAJ">Google Scholar</a>
    <a href="https://github.com/yaoyuzhang1">Github</a>
  </nav>
</section>

<section class="home-section home-research" aria-labelledby="research-title">
  <header class="home-section__header">
    <p class="home-eyebrow">Research</p>
    <h2 id="research-title">Research Interests</h2>
  </header>
  <div class="home-research__grid">
    <div class="home-focus">
      <h3>Deep Learning Theory</h3>
      <ul>
        <li>Nonlinear training dynamics and implicit bias</li>
        <li>Condensation phenomenon and theory</li>
        <li>Loss landscape structure</li>
      </ul>
    </div>
    <p class="home-research__statement">My research focuses on the theoretical foundation of deep learning. Since 2020, I have been particularly interested in analyzing the nonlinear training dynamics of neural networks, with a focus on the condensation phenomenon. We have made exciting progress in recent years, including identifying the dynamical regime of condensation, proving condensation at the initial training stage, discovering condensed critical points and manifolds (Embedding Principle), revealing condensation dynamics near the global minima, and quantifying the enhancement of sample efficiency through condensation (Optimistic Estimate). I am expecting to establish a unified theory of condensation in the coming years.</p>
  </div>
</section>

<section class="home-section home-work" aria-labelledby="work-title">
  <header class="home-section__header home-section__header--with-link">
    <div>
      <p class="home-eyebrow">Publications</p>
      <h2 id="work-title">Recent Work</h2>
    </div>
    <a class="home-text-link" href="{{ '/publications/' | relative_url }}">All publications <span aria-hidden="true">→</span></a>
  </header>

  <div class="home-work__list">
    <article class="home-work__item">
      <p class="home-work__meta">ICML 2026</p>
      <div>
        <h3><a href="https://arxiv.org/abs/2506.04805">Adaptive Preconditioners Trigger Loss Spikes in Adam</a></h3>
        <p>Zhiwei Bai, Zhangchen Zhou, Jiajie Zhao, Xiaolong Li, Zhiyu Li, Feiyu Xiong, Hongkang Yang, Yaoyu Zhang, Zhi-Qin John Xu.</p>
      </div>
    </article>
    <article class="home-work__item">
      <p class="home-work__meta">ICML 2026 Spotlight</p>
      <div>
        <h3><a href="{{ '/file/E/Towards%20Understanding%20Adam%20Convergence%20on%20Highly%20Degenerate%20Polynomials.pdf' | relative_url }}">Towards Understanding Adam Convergence on Highly Degenerate Polynomials</a></h3>
        <p>Zhiwei Bai, Jiajie Zhao, Zhangchen Zhou, Zhi-Qin John Xu, Yaoyu Zhang.</p>
      </div>
    </article>
    <article class="home-work__item">
      <p class="home-work__meta">ICML 2026</p>
      <div>
        <h3><a href="{{ '/file/A4/14474_Gradient_Flow_Dynamics_a.pdf' | relative_url }}">Gradient Flow Dynamics and Implicit Bias of Diagonal Linear Networks under Infinitesimal Initialization</a></h3>
        <p>Jiajie Zhao, Jianxing Wang, Junjie Yang, Zhiwei Bai, Yaoyu Zhang.</p>
      </div>
    </article>
    <article class="home-work__item home-work__item--new">
      <p class="home-work__meta">M3AS 2026</p>
      <div>
        <h3><a href="{{ '/file/A4/Architecture%20Induces%20Structural%20Invariant%20Manifolds%20of%20Neural%20Network%20Training%20Dynamics.pdf' | relative_url }}">Architecture Induces Structural Invariant Manifolds of Neural Network Training Dynamics</a></h3>
        <p>Jiajie Zhao, Tao Luo, Yaoyu Zhang.</p>
      </div>
    </article>
  </div>
</section>

<section class="home-section home-materials" aria-labelledby="materials-title">
  <header class="home-section__header">
    <p class="home-eyebrow">Resources</p>
    <h2 id="materials-title">Selected Materials</h2>
  </header>

  <article class="home-program" aria-labelledby="program-title">
    <div class="home-program__copy">
      <h3 id="program-title">Overview of Current Research Program</h3>
    </div>
    <figure class="home-program__visual">
      {% include condensation-overview.html %}
    </figure>
    <div class="home-program__copy">
      <p>An overview of our research efforts and future directions in understanding the condensation phenomenon of deep learning. By advancing our current research program, we anticipate developing a novel framework that establishes a rigorous mathematical foundation for deep learning. See <a href="{{ '/publications/' | relative_url }}">Publications</a> for details.</p>
    </div>
  </article>

  <div class="home-materials__grid">
    <article class="home-resource home-resource--course">
      <h3>Short Course</h3>
      <p><strong>Precourse Lecture at MLPDES25:</strong></p>
      <p>The condensation phenomenon of Deep Neural Networks (<a href="https://mod.fau.eu/wp-content/uploads/FAUMoD_MLPDES25_slides_zhangY_29apr2025.pdf">slides</a>, <a href="https://vp-cdn-balance.rrze.uni-erlangen.de/symlinks/bb5607d0-a8d3-41b1-b48e-4d06b1275b34.m4v">video</a>)</p>
      <p><strong>Towards a Mathematical Foundation of Deep Learning: From Phenomena to Theory.</strong> (<a href="https://mod.fau.eu/fau-mod-course-towards-a-mathematical-foundation-of-deep-learning-from-phenomena-to-theory/">web</a>)</p>
      <p>FAU MoD Course, Friedrich-Alexander-Universität Erlangen-Nürnberg, Germany, May 2-8, 2025.</p>
      <p class="home-resource__label">Session titles:</p>
      <ol class="home-session-list">
        <li><strong>Mysteries of Deep Learning</strong> (<a href="{{ '/file/Lectures/I.Mysteries%20of%20deep%20learning.pdf' | relative_url }}">slides</a>, <a href="https://youtu.be/twDeoSX1IRk?si=bSj1a1LWxM4kgsuJ">video</a>)</li>
        <li><strong>Frequency Principle/Spectral Bias</strong> (<a href="{{ '/file/Lectures/II.Frequency%20principle.pdf' | relative_url }}">slides</a>, <a href="https://youtu.be/lviWVkXlbSE?si=U78KCM4TPWKFsV8I">video</a>)</li>
        <li><strong>Condensation Phenomenon</strong> (<a href="{{ '/file/Lectures/III.Condensation%20phenomenon.pdf' | relative_url }}">slides</a>, <a href="https://youtu.be/O6ozmtC-ggs?si=0B8pXHVhGuQKTQBU">video</a>)</li>
        <li><strong>From Condensation to Loss Landscape Analysis</strong> (<a href="{{ '/file/Lectures/IV.From%20condensation%20to%20loss%20landscape%20analysis.pdf' | relative_url }}">slides</a>, <a href="https://youtu.be/9NqWWw6n6fQ?si=hjhqRghDK_EuM9pG">video</a>)</li>
        <li><strong>From Condensation to Generalization Theory</strong> (<a href="{{ '/file/Lectures/V.From%20condensation%20to%20generalization%20theory.pdf' | relative_url }}">slides</a>, <a href="https://youtu.be/D3PRkF3zC7M?si=knUXC_kJfu-vstwV">video</a>)</li>
      </ol>
    </article>

    <div class="home-materials__side">
      <article class="home-resource">
        <h3>Presentations</h3>
        <ul class="home-presentation-list">
          <li><strong>The Condensation Phenomenon of Deep Neural Networks.</strong> MaD Seminar, New York University, U.S.A., Feb. 13, 2025. (<a href="{{ '/file/Lectures/condensation_courant_0213.pdf' | relative_url }}">slides</a>)</li>
          <li><strong>Optimistic Sample Size Estimate for Deep Neural Networks.</strong> One World Seminar Series on the Mathematics of Machine Learning, Oct. 9, 2024. (<a href="{{ '/file/Lectures/Optimistic%20estimate.pdf' | relative_url }}">slides</a>, <a href="https://youtu.be/s2jNsXmga6A">video</a>)</li>
          <li><strong>Embedding Principle of Loss Landscape of Deep Neural Networks.</strong> Online, 机器学习联合研讨计划, Oct. 16, 2021. (<a href="{{ '/file/Lectures/E-Principle_slides.pdf' | relative_url }}">slides</a>, <a href="https://www.bilibili.com/video/BV1x44y1x7Qg">video</a>)</li>
          <li><strong>Dynamics of Deep Neural Networks--A Fourier Analysis Perspective.</strong> Institute for Advanced Study, Princeton, Oct. 4, 2019. (<a href="{{ '/file/Lectures/dynamics%20of%20DNN.pdf' | relative_url }}">slides</a>, <a href="https://www.ias.edu/video/postdoc/2019/1004-YaoyuZhang">video</a>)</li>
        </ul>
      </article>

      <article class="home-resource home-resource--textbook">
        <h3>Textbook</h3>
        <p><strong>深度学习现象导论（Introduction to Deep Learning Phenomena）</strong></p>
        <p><a href="{{ '/file/Lectures/Intro_DL_Phenomena.pdf' | relative_url }}">Chinese version</a> · <a href="https://github.com/xuzhiqin1990/understanding_dl">Git Repo</a> · <a href="https://book.douban.com/subject/38376760/">Douban</a></p>
      </article>
    </div>
  </div>
</section>

<section class="home-section home-writing" aria-labelledby="writing-title">
  <header class="home-section__header home-section__header--with-link">
    <div>
      <p class="home-eyebrow">Blogs</p>
      <h2 id="writing-title">Latest Writing</h2>
    </div>
    <a class="home-text-link" href="{{ '/blogs/' | relative_url }}">All articles <span aria-hidden="true">→</span></a>
  </header>

  <div class="home-writing__grid">
    <article class="home-writing__card home-writing__card--featured">
      <a href="{{ '/blogs/evolution-of-understanding.html' | relative_url }}">
        <p class="home-writing__meta">理解与科学</p>
        <h3>理解——预测的终极武器</h3>
        <p>从路线与地图的隐喻出发，讨论理解为何昂贵、何时值得，以及科学如何成为共同体的制度化理解。</p>
        <span>阅读全文 <span aria-hidden="true">→</span></span>
      </a>
    </article>
    <article class="home-writing__card">
      <a href="{{ '/blogs/supercortex.html' | relative_url }}">
        <p class="home-writing__meta">AI × 个体</p>
        <h3>大模型如何成为 Supercortex</h3>
        <p>当文明尺度的能力进入每一个人的手中，个体的可能性空间会如何展开？</p>
        <span>阅读全文 <span aria-hidden="true">→</span></span>
      </a>
    </article>
  </div>
</section>

</div>
