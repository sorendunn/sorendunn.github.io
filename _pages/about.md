---
layout: home
permalink: /
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<div class="blurb">
  <p>I'm currently working on scaling autonomous discovery at <a href="https://www.intology.ai">Intology</a>.</p>
  <p>I graduated with a master's from the University of Illinois at Urbana-Champaign, supervised by Professor <a href="https://lingming.cs.illinois.edu/index.html">Lingming Zhang</a>. My prior work has demonstrated state of the art performance on PostTrainBench, RE-Bench, MLE-Bench Lite, SWE-Bench, and SWE-Bench Multimodal (among other benchmarks) and has been used by OpenAI and DeepSeek in evaluating their models' software engineering capabilities.</p>
</div>

<section id="news">
  <h2>News</h2>
  <ul class="news-list">
    <li class="featured"><span class="date">August 3rd, 2026</span><div class="body">One of four main contributors leading the results in <a href="https://intology.ai/blog/scaling-automated-post-training">Scaling Automated Post-Training</a>: Locus sets SOTA on PostTrainBench (44.7, <ins>2.9 points</ins> ahead of the next frontier agent), reaches <ins>51.6%</ins> on PostTrainBench+ surpassing the official human-tuned Qwen3-1.7B (49.4%), ranks 4th by peak average rank across all live prize-money Kaggle competitions, and ships a production Bubble model at ~2.8× lower error and 105× lower cost.</div></li>
    <li><span class="date">May 19th, 2026</span><div class="body">Led the release of <a href="https://www.intology.ai/blog/nanogpt-bench">NanoGPT-Bench</a>, an autonomous AI R&amp;D benchmark built on the NanoGPT Speedrun. Frontier coding agents (Claude Code, Codex, Autoresearch) given a 512 H100-hour budget recover <ins>less than 10%</ins> of 5 months of human world-record progress (top baseline 9.3%), spending the majority of their compute on hyperparameter tuning rather than the algorithmic research that drives 75.8% of human records.</div></li>
    <li><span class="date">November 19th, 2025</span><div class="body">Intology previewed <a href="https://www.intology.ai/blog/previewing-locus">Locus</a>, the first AI system to outperform human experts at AI R&amp;D - matching/beating METR's human expert baseline on RE-Bench (1.30 vs 1.27 over a continuous 64-hour run), setting SOTA on MLE-Bench Lite (medals in <ins>77% of competitions</ins> vs prior 68%), and achieving SOTA on KernelBench</div></li>
    <li><span class="date">May 27th, 2025</span><div class="body">Intology's artifical scientist Zochi published in ACL 2025, “Tempest: Automatic Multi-Turn Jailbreaking of Large Language Models with Tree Search” - the first <a href="https://www.intology.ai/blog/zochi-acl">fully autonomous publication</a> in a top scientific venue by an AI system.</div></li>
    <li><span class="date">March 14th, 2025</span><div class="body">Along with Intology, I debuted Zochi, an artificial scientist which produced papers averaging 7.67/10 on NeurIPS guidelines, 3 of which were accepted to <a href="https://www.intology.ai/blog/zochi-tech-report">ICLR 2025 workshops</a>.</div></li>
    <li><span class="date">February 26th, 2025</span><div class="body">Agentless Lite <ins>doubles state-of-the-art</ins> on SWE-bench Multimodal from 12.19% to 25.34% for 1/4th of the cost without even requiring a runtime environment!</div></li>
    <li><span class="date">February 14th, 2025</span><div class="body">I released <a href="https://github.com/sorendunn/Agentless-Lite">Agentless Lite</a> - a generalized, lightweight adaptation of the Agentless scaffold which is competitive with SOTA agents while only requiring sampling from a single RAG prompt.</div></li>
    <li><span class="date">January 31st, 2025</span><div class="body">Agentless used by both DeepSeek and OpenAI to evaluate their new reasoning models (r1 and o3-mini) on SWE-bench</div></li>
    <li><span class="date">Dec 2nd, 2024</span><div class="body">Integrated Agentless with <ins>Claude 3.5 Sonnet</ins> to achieve 40.7% solve rate on SWE-bench lite and 50.8% solve rate on SWE-bench verified</div></li>
    <li><span class="date">Oct 28th, 2024</span><div class="body">Released <ins>OpenAutoCoder-Agentless 1.5</ins> which increases Agentless performance from 27.3% to 32.00% on SWE-bench lite</div></li>
    <li><span class="date">September 26, 2024</span><div class="body">MedCalc-Bench was accepted as an <strong>oral presentation</strong> for the NeurIPS 2024 Datasets and Benchmark Track</div></li>
    <li><span class="date">September 12, 2024</span><div class="body">Agentess was used by OpenAI as their scaffold of choice for evalauting gpt-4o, o1-mini, and o1-preview's <ins>model autonomy</ins> as part of their preparedness framework</div></li>
    <li><span class="date">July 1st, 2024</span><div class="body">Released OpenAutoCoder-Agentless 1.0! Agentless currently is the <ins>best open-source approach</ins> on SWE-bench lite with 82 fixes (27.3%) and costing on average $0.34 per issue.</div></li>
  </ul>
</section>

<section id="publications">
  <h2>Publications</h2>
  <ul class="pubs">
    <li class="pub">
      <div class="pub-title"><a href="https://arxiv.org/pdf/2407.01489">Agentless: Demystifying LLM-based Software Engineering Agents</a></div>
      <div class="pub-authors">Chunqiu Steven Xia*, Yinlin Deng*, <strong>Soren Dunn</strong>, Lingming Zhang</div>
      <div class="pub-meta"><span class="venue">FSE 2025 Distinguished Paper</span> <span class="badge">Distinguished Paper</span> · July 2024 <span class="plinks"><a class="plink" href="https://arxiv.org/pdf/2407.01489">paper</a><span class="dot">·</span><a class="plink" href="https://github.com/OpenAutoCoder/Agentless">code</a></span></div>
    </li>
    <li class="pub">
      <div class="pub-title"><a href="https://openreview.net/pdf?id=VXohja0vrQ">MedCalc-Bench: Evaluating Large Language Models for Medical Calculations</a></div>
      <div class="pub-authors">Nikhil Khandekar*, Qiao Jin*, Guangzhi Xiong*, <strong>Soren Dunn</strong>, Serina S Applebaum, Zain Anwar, Maame Sarfo-Gyamfi, Conrad W Safranek, Abid Anwar, Andrew Jiaxing Zhang, Aidan Gilson, Maxwell B Singer, Amisha D Dave, R. Andrew Taylor, Aidong Zhang, Qingyu Chen, Zhiyong Lu</div>
      <div class="pub-meta"><span class="venue">NeurIPS 2024 Datasets and Benchmark Track Oral</span> <span class="badge">Oral</span> · June 2024 <span class="plinks"><a class="plink" href="https://openreview.net/pdf?id=VXohja0vrQ">paper</a><span class="dot">·</span><a class="plink" href="https://github.com/ncbi-nlp/MedCalc-Bench">code</a></span></div>
    </li>
    <li class="pub">
      <div class="pub-title"><a href="https://pubs.acs.org/doi/full/10.1021/jacs.0c11920">Rational Construction of an Artificial Binuclear Copper Monooxygenase in a Metal–Organic Framework</a></div>
      <div class="pub-authors">Xuanyu Feng, Yang Song, Justin Chen, Ziwan Xu, <strong>Soren Dunn</strong>, Wenbin Lin</div>
      <div class="pub-meta"><span class="venue">Journal of the American Chemical Society</span> · January 2021 <span class="plinks"><a class="plink" href="https://pubs.acs.org/doi/full/10.1021/jacs.0c11920">paper</a></span></div>
    </li>
  </ul>
</section>

<section id="resume">
  <h2>Resume</h2>
  <p class="resume-link"><a href="https://drive.google.com/file/d/1vkVBOFYVau3r3tdOwhPvnSWvygM0-r_w/view?usp=sharing">link</a></p>
</section>
