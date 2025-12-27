---
layout: archive
title: "Resources for sharing"
permalink: /resources/
author_profile: false
---

<style>
  /* --- Global Layout Styles --- */
  
  /* Spacing utility to replace <br> stacks */
  .section-spacer {
    margin-top: 80px;
    margin-bottom: 40px;
    border-bottom: 1px solid #e0e0e0; /* Optional: adds a subtle separator line */
  }

  /* Navigation Styles */
  .table-of-contents {
    margin: 20px 0;
    font-size: 19px;
    text-align: center; /* Optional: Centers the links */
  }

  .table-of-contents a {
    margin: 0 15px;
    text-decoration: none;
    color: #0ea1c5;
    font-weight: bold;
    display: inline-block; /* Helps with spacing on mobile */
  }

  .table-of-contents a:hover {
    color: #ff00c8ab;
  }

  /* Responsive Images */
  .responsive-img {
    max-width: 100%;
    height: auto;
    border-radius: 4px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  }
  
  /* Software App Container */
  .software-item {
    margin-bottom: 30px;
  }

  /* Back to Top Button */
  #back-to-top {
    position: fixed;
    bottom: 40px; /* Adjusted to be less obtrusive */
    right: 20px;
    padding: 10px 15px;
    font-size: 14px;
    background-color: #2f7f93;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.2);
    z-index: 1000;
    transition: background-color 0.3s ease;
    display: none; /* Hidden by default, JS will show it */
  }

  #back-to-top:hover {
    background-color: #007bff;
  }
</style>

<nav class="table-of-contents">
  <a href="#plasmids">Plasmids</a>
  <a href="#software">Software</a>
  <a href="#protocols">Protocols</a>
</nav>

<div class="section-spacer"></div>

<h2 id="plasmids">🧬 Expression vector maps for biosensors</h2>

<p>For detailed usage of these biosensors in imaging, or for plasmid requests, please contact <a href="mailto:wangk@ion.ac.cn">Dr. Kui Wang</a>.</p>

| ID | Vector | Description | Reference |
|---|---|---|---|
| [K2](/files/plasmid/K140.dna) | pcDNA-GRIT | Tryptophan sensor expressed in mammalian cell | [Cell Disc, 2023](/publication/2023-10-31-Tryptophan-sensor) |
| [K3](/files/plasmid/K140.dna) | pcDNA-GRITol | Tryptophan control sensor expressed in mammalian cell | [Cell Disc, 2023](/publication/2023-10-31-Tryptophan-sensor) |
| [K4](/files/plasmid/K140.dna) | pcDNA-mito-GRIT | Mitochondrial Tryptophan sensor expressed in mammalian cell | [BMC Biol, 2024](/publication/2024-11-14-Tryptophan-imaging) |
| [K5](/files/plasmid/K140.dna) | pcDNA-mito-GRITol | Mitochondrial Tryptophan control sensor expressed in mammalian cell | [BMC Biol, 2024](/publication/2024-11-14-Tryptophan-imaging) |
| [K6](/files/plasmid/PLACEHOLDER.dna) | GEM<sub>CPPU</sub>1.0 Sensor | Ratiometric biosensor for detecting Forchlorfenuron (CPPU) | Manuscript in preparation |
| [K7](/files/plasmid/PLACEHOLDER.dna) | GEM<sub>TrpA</sub>1.0 Sensor | Novel sensor for monitoring Tryptamine dynamics *in vivo* | Under revision |


<div class="section-spacer"></div>


<h2 id="software">🖥️ Ratio Imaging Analyzer (RIA)</h2>

[![Version](https://img.shields.io/badge/version-v1.7.5-blue)](https://github.com/Epivitae/RatioImagingAnalyzer) ![License](https://img.shields.io/badge/license-MIT-green) ![Python](https://img.shields.io/badge/python-3.8%2B-yellow)

**Ratio Imaging Analyzer (RIA)** is a lightweight, user-friendly tool designed for processing dual-channel ratiometric fluorescence data (e.g., Calcium, FRET, NADH). It features automated alignment, smart background subtraction, and real-time ROI plotting.

| **Automated Workflow** | **Interactive Analysis** |
| :---: | :---: |
| <img src="/images/resource/analysis.gif" class="responsive-img"> | <img src="/images/resource/live-plot.gif" class="responsive-img"> |
| *Auto-alignment & ratiometric heatmap generation* | *Real-time ROI monitoring & curve plotting* |
|[**View on GitHub**](https://github.com/Epivitae/RatioImagingAnalyzer)  |  [**Download Latest Release**](https://github.com/Epivitae/RatioImagingAnalyzer/releases)|


<div class="section-spacer"></div>

<h2>🖥️ Other Ready-to-Use Lab Softwares</h2>

<div class="software-item">
  <div style="font-size: 1.1em; margin-bottom: 8px;">
    <strong>1. mProcess:</strong> A self-developed tool for microplate data preprocessing
  </div>

  <div style="margin-bottom: 15px;">
    <a href="/files/app/mProcess%20V4.0.exe" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/Download-mProcess_V4.0-007bff" alt="Download mProcess">
    </a>
    <img src="https://img.shields.io/badge/license-Freeware-green" alt="License">
    <img src="https://img.shields.io/badge/python-3.8%2B-yellow" alt="Python">
  </div>

  <a href="/files/app/pic/mProcess.gif" target="_blank">
    <img src="/files/app/pic/mProcess.gif" alt="mProcess" class="responsive-img" style="max-width: 300px; width: 100%;">
  </a>
  
  <span style="display: block; color: #666; font-size: 14px; font-style: italic; margin-top: 5px;">
    Figure 1: Batch data processing interface for microplate readers.
  </span>
</div>

<br>

<div class="software-item">
  <div style="font-size: 1.1em; margin-bottom: 8px;">
    <strong>2. zGrating:</strong> A self-developed visual stimulus generator
  </div>

  <div style="margin-bottom: 15px;">
    <a href="/files/app/zGrating_V2.3.exe" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/Download-zGrating_V2.3-007bff" alt="Download zGrating">
    </a>
    <img src="https://img.shields.io/badge/license-Freeware-green" alt="License">
    <img src="https://img.shields.io/badge/python-3.8%2B-yellow" alt="Python">
  </div>

  <a href="/files/app/pic/zGrating.gif" target="_blank">
    <img src="/files/app/pic/zGrating.gif" alt="zGrating" class="responsive-img" style="max-width: 300px; width: 100%;">
  </a>

  <span style="display: block; color: #666; font-size: 14px; font-style: italic; margin-top: 5px;">
    Figure 2: Radial grating patterns generation and parameter adjustment.
  </span>
</div>

<br>

<div class="software-item">
  <div style="font-size: 1.1em; margin-bottom: 8px;">
    <strong>3. zStimuli:</strong> Controls Arduino via serial communication to deliver multimodal stimuli
  </div>

  <div style="margin-bottom: 15px;">
    <a href="/files/app/zStimuli4.0.exe" style="text-decoration: none;">
      <img src="https://img.shields.io/badge/Download-zStimuli_V4.0-007bff" alt="Download zStimuli">
    </a>
    <img src="https://img.shields.io/badge/license-Freeware-green" alt="License">
    <img src="https://img.shields.io/badge/python-3.8%2B-yellow" alt="Python">
  </div>

  <a href="/files/app/pic/zStimuli.png" target="_blank">
    <img src="/files/app/pic/zStimuli.png" alt="zStimuli" class="responsive-img" style="max-width: 300px; width: 100%;">
  </a>

  <span style="display: block; color: #666; font-size: 14px; font-style: italic; margin-top: 5px;">
    Figure 3: Control panel for setting up multimodal experimental stimuli.
  </span>
</div>


<div class="section-spacer"></div>


<h2 id="protocols">📋 Protocols in our hands</h2>

1. [High-throughput recombinant DNA preparation](/files/protocol/K.WANG Molecular cloning Methods in our hands (V1.0).pdf)
2. [*In vitro* transcription for mRNA preparation](/files/protocol/K.WANG%20Tol2%20mRNA%20IVT%20protocol.pdf)
3. Biosensor protein purification
4. Fluorescent biosensor screening and modification


<div class="section-spacer"></div>


## Useful codes

```bundle exec jekyll serve --livereload```

```jekyll clean```