---
title: Research
description: "Phase stability and synthesizability from first principles, work with experimental groups, and a direction: phase diagrams from raw calorimetry curves, with uncertainty."
permalink: /research/
---
# Research

My training is in computational thermodynamics: deciding from first principles which phases are stable, and therefore which proposed materials can be made. Three parts: the Ph.D. work, the work with experimental groups, and the direction I am interested in now.

## 1. Phase stability and synthesizability from first principles

In my Ph.D. with Prof. Charles B. Musgrave (University of Colorado Boulder, 2021–2026) I evaluated the thermodynamic stability of battery cathodes and solid electrolytes with density functional theory, built high-throughput screening workflows, and assessed which candidates are likely to be synthesizable.

{% include figure.html wide=true src="jmca2025-workflow" width="1600" height="463" link="https://doi.org/10.1039/d5ta01405k" alt="Workflow banner: data acquisition, pairing of lithiated and delithiated phases, lithiation reaction type, reaction voltage and capacity, stability evaluation, quantum-mechanical modelling; below it, the decision tree from the Materials Project phases to intercalation or conversion pairs" caption="<b>Hybrid cathodes for metal-based batteries.</b> The inverse-design framework: pair lithiated and delithiated phases, classify the lithiation reaction, compute voltage, capacity and volume change, check chemical and electrochemical stability, then model the surviving candidates." credit="Fig. 1 of Biby, Rich and Musgrave, <i>J. Mater. Chem. A</i> 2025, CC BY 3.0." %}

<div class="figrow">
{% include figure.html src="jmca2025-funnel" width="1200" height="1190" link="https://doi.org/10.1039/d5ta01405k" alt="Flow chart: 11,668 lithiated phases narrowed step by step to one chemically stable delithiated phase" caption="From 11,668 lithiated phases to one candidate, LiCr₄GaS₈–Li₂S, with an average energy density above NMC333's theoretical maximum." credit="Fig. 4 of the same paper, CC BY 3.0." %}
{% include figure.html src="eesb2025-stability" width="1600" height="636" link="https://doi.org/10.1039/d5eb00089k" alt="Decomposition energy against potential for LLTO, LLZrO and LLHfO, and Li diffusion barriers for each composition" caption="<b>Solid electrolytes stable against lithium metal.</b> Replacing Ti with Zr or Hf in lithium lanthanum titanate keeps the perovskite metastable in contact with Li metal; the Hf compound is also mechanically stable, at the cost of higher Li diffusion barriers." credit="Fig. 2 of Biby, Ali and Musgrave, <i>EES Batteries</i> 2025, CC BY 3.0." %}
</div>

- **MXene synthesizability dataset.** 1,040 ordered binary and ternary MXene carbides and nitrides computed with r²SCAN DFT: formation and decomposition Gibbs energies, decomposition products and energies above the hull, with finite-temperature Gibbs energies from the machine-learned descriptor of [Bartel et al. (2018)](https://doi.org/10.1038/s41467-018-06682-4). None is stable at equilibrium; 115 become stable at 500–2000 K, 23 at 10 GPa, and three in the Mn–Fe–C space at experimentally feasible carbon chemical potentials. Preprint on [arXiv](https://arxiv.org/abs/2611.14687) (2026), with C. B. Musgrave.

{% include figure.html wide=true src="mxene2026-structures" width="1600" height="933" link="https://arxiv.org/abs/2611.14687" alt="Side views of the ordered MXene families: mono-transition-metal M2X, M3X2 and M4X3; in-plane and out-of-plane ordered double-transition-metal MXenes; ordered divacancy MXenes" caption="<b>The ordered MXene space.</b> Mono-transition-metal, in-plane and out-of-plane ordered double-transition-metal, and ordered divacancy MXenes for n = 1 to 3." credit="Fig. 1 of Biby and Musgrave, arXiv:2611.14687 (2026)." %}
{% include figure.html src="mxene2026-stability" width="1400" height="1244" link="https://arxiv.org/abs/2611.14687" alt="Four panels: cumulative bandgap distribution; counts of temperature-, pressure- and chemical-potential-stabilized MXenes by category; maps of stabilizable mono- and out-of-plane ordered MXene compositions" caption="<b>Which MXenes can be stabilized, and how.</b> Bandgaps (A); MXenes stabilized by temperature, pressure or carbon chemical potential, by category (B); the stabilizable compositions (C, D)." credit="Fig. 2 of the same preprint." %}


Methods: convex-hull phase stability; temperature-, pressure- and chemical-potential-dependent phase diagrams; synthesizability and metastability analysis; VASP, JDFTx and pymatgen; automated high-throughput workflows.

## 2. With experimental groups

<div class="figrow side">
{% include figure.html src="mte2021-intercalation" width="900" height="1461" link="https://doi.org/10.1016/j.mtener.2021.100677" alt="Charge-density difference plots for H, Li, Na and K intercalated into 1T, 2H and 3R MoS2" caption="Where the charge goes when H⁺, Li⁺, Na⁺ or K⁺ enters 1T, 2H or 3R MoS₂: the basis for the quantum-capacitance results." credit="Fig. 2 of Biby, Ali and Allam, <i>Materials Today Energy</i> 2021, © 2021 Elsevier Ltd, author's reuse." %}
<div class="figtext" markdown="1">
Many of my papers were written with experimental groups, for which I performed the DFT calculations. With Prof. Chunmei Ban's group (CU Boulder), on stabilizing argyrodite solid-state lithium metal batteries ([<em>Energy Storage Materials</em> 2026](/publications/#p13)). With Prof. Jesús Velázquez's group (UC Davis), on Cu₂S/MoS₂ heterostructures ([<em>PRX Energy</em> 2026](/publications/#p15)) and on metastable Chevrel phases. With collaborators at King Fahd University of Petroleum and Minerals, on CO₂ reduction over copper nanocrystals ([<em>Appl. Catal. A</em> 2026](/publications/#p12)).

Before that, in Prof. Nageh Allam's Energy Materials Laboratory at The American University in Cairo (2015–2021): density functional theory for electrode and photoelectrode materials, from the quantum capacitance of MoS₂ and its alkali intercalation ([<em>Materials Today Energy</em> 2021](https://doi.org/10.1016/j.mtener.2021.100677), [<em>Materials Advances</em> 2021](/publications/#p5)) to carbon-defect states in ZrO₂ photoelectrodes ([<em>Int. J. Hydrogen Energy</em> 2021](/publications/#p7)).
</div>
</div>

## 3. My current interest: phase diagrams from raw calorimetry, with uncertainty

<ul class="tiles two">
  <li class="tile">{% include illus/dsc.svg %}<h3>The instrument blurs the signal</h3><p>Heat reaches the sample late, so the same transition appears later and broader as the heating rate rises. Standard practice keeps two or three temperatures from each curve.</p></li>
  <li class="tile">{% include illus/phasediagram.svg %}<h3>Boundaries with a stated uncertainty</h3><p>What a phase diagram should carry: each liquidus point with its error bar, and a band that says where the line is known and where it is guessed.</p></li>
</ul>

Synthesis is guided by a phase diagram: the map of which solid and liquid phases are stable at each temperature and composition. For most systems of three or more elements no assessed diagram exists, and the boundaries that have been drawn rarely carry a stated uncertainty. Differential scanning calorimetry (DSC) finds where an alloy melts from a milligram-scale sample, but the instrument blurs what it measures, and the reported liquidus and invariant temperatures rarely carry a stated uncertainty either.

My interest is a physics-based model of the calorimeter, fitted to the whole heat-flow curve at several heating rates, so that the liquidus and the invariant reactions come out with stated uncertainty, and so that the next run (heating rate, hold time, composition) can be chosen to shrink that uncertainty most. A first public step is my hackathon entry on the [software and data page](/software/).
