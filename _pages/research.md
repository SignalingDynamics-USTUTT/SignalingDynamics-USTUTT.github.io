---
layout: default
title: "Research"
include_collection: research
permalink: /research
show_breadcrumb: true
breadcrumb_list:
  - label: Home
    url: /
---

<div id="main">

<h4>Background</h4>
<p>Cancer is a leading cause of death. While targeted therapies show promising results, cancer inevitably strikes back, typically via a few cells acquiring genetic mutations that bypass the oncogenic inhibition. Identifying <b>which</b> cells and <b>how</b> they acquire such resistance will greatly facilitate the development of higher-efficacy therapeutics.</p>

<p>Cancer therapeutic responses involve millions of heterogeneous cells across months or years. While profiling single cells at fixed timepoints can now be reliably performed with single-cell omics technologies, characterizing the <b>tempoeral dynamics</b> between the timepoints remains challenging. In my previous work, my colleagues and I addressed this limitation by developing innovative time-lapse microscopy and automated image-analysis algorithms (<a href="/publication">Yang <em>et al. Nat Commun</em> 2021; Tian <em>et al. Cell Rep</em> 2020</a>), allowing us to continuously monitor thousands of single drug-treated cancer cells in their native states over two weeks. This represents an order of magnitude improvement over the state-of-the-art in the number of monitored cells and the monitoring duration. Applying them to BRAF-driven melanoma cells, we identified a subpopulation ("escapees") that rapidly escaped the clinically approved BRAF inhibitors and entered a slow-cycling state via non-genetic mechanisms. These "escapees" naturally out-proliferated non-dividing cells, yet they harbored increased DNA damage and thus were more likely to acquire new genetic mutations. Our work suggests that escapees could represent the seed population driving the eventual acquisition of permanent drug resistance. Escapees have been observed across cancer and drug types, indicating the clinical relevance of our work.</p>
<img src="../images/research/escapee_nonescapee.gif" alt="Escapee vs Non-Escapee" style="max-width:100%;">

<h4>Current Research</h4>
<p>We want to expand our technologies to cover the <b>entire timeline of cancer recurrence</b>, from the time of drug addition to the formation of resistant colonies. If successful, our research will fundamentally shift our view of this critical process. We will conduct our research in three directions.</p>
<img src="../images/research/current_research.png" alt="Overview of Current Research" style="max-width:100%;"><br>

<p><b>Developing innovative time-lapse microscopy technologies.</b><br>
Factors such as the spectral overlap of live-cell reporters, phototoxicity, and the accuracy of cell tracking limits the performance of time-lapse microscopy, such that one can typically only measure a few signals over days. We will address them both experimentally (e.g., developing culturing models) and computationally (e.g., incorporating deep learning for cell tracking). Our goal is to reliably monitor single drug-treated cancer cells over months, both in 2D and 3D <em>in-vitro</em> settings.</p>

<p><b>Identifying the molecular mechanisms of drug escaping.</b><br>
Combining our time-lapse microscopy technologies that measure a few pathways' activities over time with single-cell omics technologies that measure thousands of genes at fixed timepoints, we will identify the signaling pathways driving the drug escaping at each characteristic timescale. Classical cell-biology and genetic approaches will then help dissect the detailed molecular mechanisms and identify novel therapeutic targets. Together, we aim to unravel the dynamics and sequences of events by which cancer recurrence emerges.</p>

<p><b>Quantifying impact of therapeutic scheduling on tumor progression.</b><br>
The dosages and timings of therapeutic administration strongly impact the clinical outcomes, yet these parameters are often determined empirically without understanding the underlying single-cell responses. We are optimally positioned to address this gap with our time-lapse microscopy technologies. Coupling them with computational modeling, we can quantify how these parameters impact the evolution of tumor sizes. Our work will serve as an important step towards model-guided optimal scheduling of therapy administration.</p>

</div>