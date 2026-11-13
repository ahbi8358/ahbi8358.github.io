---
title: Home
description: "Ahmed H. Biby, Ph.D. in materials science and engineering. Computational materials thermodynamics and inverse materials design: phase stability from first principles, predictive synthesis, and building phase diagrams faster from calorimetry, with the uncertainty stated."
permalink: /
---

<section class="hero-band band">
  <div class="hero">
    <div class="intro">
      <p class="eyebrow"><b>{{ site.data.profile.name }}</b> {{ site.data.profile.tagline }}{% if site.data.profile.location != "" %} · {{ site.data.profile.location }}{% endif %}</p>
      <h1>Discovering new materials is not the bottleneck anymore. Realizing them is!</h1>
      <p class="lead">Computation now proposes stable compounds far faster than laboratories can make them. In my Ph.D. (materials science and engineering, University of Colorado Boulder, May 2026) I used first-principles thermodynamics to determine which proposed battery materials are stable and which can be made, and performed DFT for experimental collaborators. I am now interested in the map that guides a synthesis, the phase diagram, built faster, more efficiently and smarter by combining computation with experiment, for rapid, scalable crystal-growth screening.</p>
      <p class="cta"><a class="button" href="{{ '/publications/' | relative_url }}"><span>Publications</span></a> <a class="button ghost" href="{{ '/research/' | relative_url }}"><span>Research</span></a> <a class="button ghost" href="{{ site.data.profile.cv_pdf | relative_url }}"><span>CV (PDF)</span></a></p>
      <ul class="link-row">
        {% for l in site.data.profile.links %}<li><a href="{{ l.url }}" rel="me">{{ l.label }}</a></li>{% endfor %}
        {% if site.data.profile.email != "" %}<li><a href="mailto:{{ site.data.profile.email }}">Email</a></li>{% endif %}
      </ul>
    </div>
    <span class="photo-frame portrait"><picture><source srcset="{{ '/assets/img/ahmed-biby-portrait.webp' | relative_url }}" type="image/webp"><img src="{{ '/assets/img/ahmed-biby-portrait.jpg' | relative_url }}" alt="{{ site.data.profile.photo_alt }}" width="900" height="1200"></picture></span>
  </div>
</section>
<section class="stats-band band" aria-label="In numbers">
  <ul class="stats">
    <li><b>15</b><span>refereed papers</span></li>
    <li><b>5</b><span>as first author</span></li>
  </ul>
</section>

<section class="section wide">
<p class="eyebrow num">01</p>
<h2>Three questions</h2>

<ul class="tiles">
  <li class="tile">{% include illus/hull.svg %}<h3>Is it stable?</h3><p>Formation energies from density functional theory, and the convex hull that decides which compositions survive.</p></li>
  <li class="tile">{% include illus/loop.svg %}<h3>Can it be made, and what should be made?</h3><p>From a target property to the compositions that could deliver it, with the stability checks that rule candidates in or out.</p></li>
  <li class="tile">{% include illus/phasediagram.svg %}<h3>Where are the phase boundaries?</h3><p>My current interest: phase diagrams from fewer, better-chosen calorimetry runs, with the uncertainty stated.</p></li>
</ul>
</section>

<section class="section wide">
<p class="eyebrow num">02</p>
<h2>Selected work</h2>

<ul class="cards figcards">
  <li class="card figcard">
    <a href="https://doi.org/10.1039/d5ta01405k" class="thumb tall"><picture><source srcset="{{ '/assets/img/papers/jmca2025-flow.webp' | relative_url }}" type="image/webp"><img src="{{ '/assets/img/papers/jmca2025-flow.jpg' | relative_url }}" alt="Top: the inverse-design workflow from data acquisition and pairing of lithiated and delithiated phases to stability evaluation and quantum-mechanical modelling. Bottom: flow chart narrowing 11,668 lithiated phases to one chemically stable candidate" width="1100" height="1240" loading="lazy"></picture></a>
    <div class="body">
      <h3><a href="https://doi.org/10.1039/d5ta01405k">Hybrid cathodes by inverse design</a></h3>
      <span class="venue">J. Mater. Chem. A, 2025 · first author</span>
      <p>A data-driven inverse-design framework that pairs lithiated and delithiated phases, classifies the lithiation reaction, computes voltage, capacity and volume change, and checks chemical and electrochemical stability. It narrowed 11,668 lithiated phases to one hybrid cathode, LiCr₄GaS₈–Li₂S, with an average energy density above NMC333's theoretical maximum.</p>
      <span class="credit">Figs. 1 and 4 of the paper, CC BY 3.0.</span>
    </div>
  </li>
  <li class="card figcard">
    <a href="https://doi.org/10.1039/d5eb00089k" class="thumb tall"><picture><source srcset="{{ '/assets/img/papers/eesb2025-fig12.webp' | relative_url }}" type="image/webp"><img src="{{ '/assets/img/papers/eesb2025-fig12.jpg' | relative_url }}" alt="Top: two-stage computational workflow, compositional screening of B-site, X-site and A-site species followed by diffusion-barrier, mechanical and bonding analysis. Bottom: decomposition energy against potential for LLTO, LLZrO and LLHfO, and Li diffusion barrier energies" width="1100" height="960" loading="lazy"></picture></a>
    <div class="body">
      <h3><a href="https://doi.org/10.1039/d5eb00089k">Perovskite electrolytes stable against lithium metal</a></h3>
      <span class="venue">EES Batteries, 2025 · first author</span>
      <p>First-principles stability analysis of lithium lanthanum titanate perovskites with Ti replaced by Zr or Hf. The Hf compound stays metastable in contact with lithium metal and is mechanically stable, at the cost of higher Li diffusion barriers.</p>
      <span class="credit">Figs. 1 and 2 of the paper, CC BY 3.0.</span>
    </div>
  </li>
  <li class="card figcard">
    <a href="https://arxiv.org/abs/2611.14687" class="thumb tall"><picture><source srcset="{{ '/assets/img/papers/mxene2026-bd.webp' | relative_url }}" type="image/webp"><img src="{{ '/assets/img/papers/mxene2026-bd.jpg' | relative_url }}" alt="Top: number of MXenes stabilized by temperature, pressure or carbon chemical potential in each category, carbides and nitrides. Bottom: map of the stabilizable out-of-plane ordered MXene compositions by inner and outer metal" width="1100" height="1794" loading="lazy"></picture></a>
    <div class="body">
      <h3><a href="https://arxiv.org/abs/2611.14687">Which MXenes can be made</a></h3>
      <span class="venue">arXiv preprint, 2026 · first author</span>
      <p>A dataset of 1,040 ordered binary and ternary MXene carbides and nitrides computed with r²SCAN DFT, with formation and decomposition Gibbs energies, decomposition products and energies above the hull. None is stable at equilibrium, but 115 become stable at 500–2000 K, 23 at 10 GPa, and three in the Mn–Fe–C space at experimentally feasible carbon chemical potentials: synthesis conditions to try first.</p>
      <span class="credit">Fig. 2(B) and 2(D) of the preprint.</span>
    </div>
  </li>
</ul>

<p>All 15 refereed papers, linked to the published versions, are on the <a href="{{ '/publications/' | relative_url }}">publications page</a>; the figures above are from my first-author papers and preprint.</p>
</section>

<section class="section">
<p class="eyebrow num">03</p>
<h2>Now</h2>

<ul class="now">
  <li><time datetime="2026-11">Nov 2026</time><span>First-author preprint with C. B. Musgrave: <a href="https://arxiv.org/abs/2611.14687"><em>High-Fidelity In Silico Dataset of Ordered Binary and Ternary MXenes with Predictive Synthesis Guidance</em></a> (arXiv).</span></li>
  <li><time datetime="2026-10">Oct 2026</time><span>Solo entry to the 2026 OSI Hackathon for the Physical Sciences &amp; Mathematics: <a href="{{ '/software/' | relative_url }}">Can AI read a DSC curve?</a></span></li>
  <li><time datetime="2026-05">May 2026</time><span>Ph.D., University of Colorado Boulder, with Prof. Charles B. Musgrave. Thesis: <em>In-Silico Design and Discovery of Next-Generation Battery Materials</em>.</span></li>
</ul>
</section>
