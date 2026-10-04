---
permalink: /
title: "About me — Quang Dao"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a senior studying computer science at Rose-Hulman Institute of Technology. My research focuses on NLP, language models, and agent systems. I’m interested in making LLM agents more reliable through better tool use, communication, and memory.

My current interests include:

- **Multi-agent systems:** How LLM-based agents plan, use tools, and work together across multi-step tasks.
- **Latent communication:** Whether agents can exchange information through internal representations instead of relying only on natural-language conversations.
- **Memory in LLMs:** How models and agents retain, select, and manage information over long interactions, including KV-cache optimization and memory organization.
- **Training and inference methods:** Steering vectors, calibration, and other interventions to understand and guide model behavior.

In spring 2026, I joined the Georgia Tech Research Institute (GTRI), working with Kenneth Eaton on memory for long-horizon LLM agents. That summer, I was a research intern in Zhuang Liu’s lab at Princeton University, working on multi-agent systems for scientific reasoning and research feedback.

Previously, I was an undergraduate research intern in Notre Dame’s SROP program, advised by Dr. Meng Jiang and mentored by Hy Dang, where I worked on tool use and multi-agent systems.

I’m looking for PhD opportunities starting in Fall 2027 and would be happy to connect with potential advisors working on NLP and LLM agent systems.

## News

<ul class="news-list">
  <li class="news-item">
    <time class="news-item__date" datetime="2026-09">Sep, 2026</time>
    <div class="news-item__text"><em>Weighted Memory Tree: Remembering What Matters for Long-Horizon LLM Agents</em> was accepted to the <strong>REALM Workshop at EMNLP 2026</strong>.</div>
  </li>
  <li class="news-item">
    <time class="news-item__date" datetime="2026-08">Aug, 2026</time>
    <div class="news-item__text">Our OpenTools paper, <em>Open, Reliable, and Collective: A Community-Driven Framework for Tool-Using AI Agents</em>, was accepted to the <strong>System Demonstrations track at EMNLP 2026</strong>.</div>
  </li>
  <li class="news-item">
    <span class="news-item__date">Summer 2026</span>
    <div class="news-item__text">Presented our work on Weighted Memory Tree at <strong>GTRI</strong>.</div>
  </li>
  <li class="news-item">
    <span class="news-item__date">Summer 2026</span>
    <div class="news-item__text">Joined <strong>Zhuang Liu’s lab at Princeton University</strong> as a summer research intern.</div>
  </li>
  <li class="news-item">
    <span class="news-item__date">Spring 2026</span>
    <div class="news-item__text">Joined <strong>GTRI</strong> as a research intern, working on memory for long-horizon LLM agents.</div>
  </li>
  <li class="news-item">
    <time class="news-item__date" datetime="2025-07">Jul, 2025</time>
    <div class="news-item__text">Presented my summer research at <strong>Notre Dame’s Workshop Symposium</strong>.</div>
  </li>
  <li class="news-item">
    <time class="news-item__date" datetime="2025-05">May, 2025</time>
    <div class="news-item__text">Joined <strong>Notre Dame’s SROP program</strong> to work on language model agent systems with Dr. Meng Jiang and Hy Dang.</div>
  </li>
</ul>

## Publications

<article class="publication-card" aria-labelledby="wmt-title">
  <div class="publication-card__visual">
    <a href="{{ '/assets/archi_WMT.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
      <img src="{{ '/assets/archi_WMT.png' | relative_url }}" alt="Weighted Memory Tree architecture showing its status-driven memory workflow" loading="lazy">
    </a>
    <div class="publication-card__venue">REALM Workshop<br>EMNLP 2026</div>
  </div>
  <div class="publication-card__details">
    <h3 id="wmt-title" class="publication-card__title">
      <a href="{{ '/assets/WMT.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Weighted Memory Tree: Remembering What Matters for Long-Horizon LLM Agents</a>
    </h3>
    <p class="publication-card__authors">Quang Dao, Purvi Kathalkar, Kenneth Eaton</p>
    <div class="publication-card__links">
      <a href="{{ '/assets/WMT.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View Weighted Memory Tree paper">View Paper</a>
    </div>
  </div>
</article>

<article class="publication-card" aria-labelledby="opentools-title">
  <div class="publication-card__visual">
    <a href="{{ '/assets/architecture.png' | relative_url }}" target="_blank" rel="noopener noreferrer">
      <img src="{{ '/assets/architecture.png' | relative_url }}" alt="OpenTools architecture for tool discovery, evaluation, contribution, and use" loading="lazy">
    </a>
    <div class="publication-card__venue">System Demonstrations<br>EMNLP 2026</div>
  </div>
  <div class="publication-card__details">
    <h3 id="opentools-title" class="publication-card__title">
      <a href="{{ '/assets/OpenTools.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">Open, Reliable, and Collective: A Community-Driven Framework for Tool-Using AI Agents</a>
    </h3>
    <p class="publication-card__authors">Hy Dang, Quang Dao, Dr. Meng Jiang</p>
    <div class="publication-card__links">
      <a href="{{ '/assets/OpenTools.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer" aria-label="View OpenTools paper">View Paper</a>
      <a href="https://github.com/hydang99/opentools" target="_blank" rel="noopener noreferrer">Project Page</a>
    </div>
  </div>
</article>
