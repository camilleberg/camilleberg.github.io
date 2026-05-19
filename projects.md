---
title: Projects
layout: projects-page
---

<hr class="projects-divider">

<!-- ── PROJECT 1 ─────────────────────────────────────────────── -->
<div class="project-card">
  <div class="project-number">Project 01</div>
  <h2>Kernel-Based Survival Methods
for Estimating Returns to Female Schooling</h2>
  <div class="project-subtitle">2026</div>
  <p class="project-abstract">
    I seek to examine the returns to female education across ten countries using a survival function estimated via kernel methods, relaxing the linearity assumptions embedded in standard human capital models. Existing approaches impose separability between education and experience and assume a fixed, linear rate of return for every year of schooling — assumptions that are particularly restrictive when modeling female educational trajectories, where family-level selection and time-varying treatment are prevalent. I seek to estimate female school enrollment and dropout dynamics using survey-weighted logistic regression calibrated to national data, correcting for censoring and omitted variable bias. My approach will yields dynamic and bias-corrected estimates of educational attainment that outperform standard linear and Cox regression benchmarks. 
  </p>
  <div class="project-footer">
    <div class="project-tags">
      <span class="project-tag">labour economics</span>
      <span class="project-tag">causal inference</span>
      <span class="project-tag">development</span>
      <span class="project-tag">gender economics</span>
      <span class="project-tag">kernel estimation</span>
      <span class="project-tag">Python</span>
    </div>
    <a class="project-pdf" href="{{ site.url }}/assets/docs/Bergeron_kernel_estimation_idea.pdf" target="_blank">
      Download the slides
    </a>
  </div>
</div>

<!-- ── PROJECT 2 ─────────────────────────────────────────────── -->
<div class="project-card">
  <div class="project-number">Project 02</div>
  <h2>A Household in Transition: A Study on Dynamics</h2>
  <div class="project-subtitle">2025</div>
  <p class="project-abstract">
    Intra-household bargaining power has been shown to increase with a positive non-labor income shock to women. I propose a new method to study female empowerment as a result of the receipt of a cash transfer. Previous research on dynamics has relied solely on cross-sectional analysis. Using data from a cash transfer experiment in Malawi and Liberia, I analyze the dynamics using impulse response function estimation and dynamic multipliers. This paper would therefore be the first to estimate impulse response functions of intra-household bargaining power using high-frequency experimental panel data. 
  </p>
  <div class="project-footer">
    <div class="project-tags">
      <span class="project-tag">collective household</span>
      <span class="project-tag">dynamic causal effect</span>
      <span class="project-tag">intra-household bargaining</span>
      <span class="project-tag">local projections</span>
      <span class="project-tag">household dynamics</span>
    </div>
    <a class="project-pdf" href="{{ site.url }}/assets/docs/Bergeron_Proposal_Household_Dynamics.pdf" target="_blank">
      Download the proposal
    </a>
  </div>
</div>

<!-- ── PROJECT 3 ─────────────────────────────────────────────── -->
<div class="project-card">
  <div class="project-number">Project 03</div>
  <h2>Kernel Ridge Regression for PDEs</h2>
  <div class="project-subtitle">2026</div>
  <p class="project-abstract">
    I consider the Lotka-Volterra predator-prey system, a classical system of ODEs governing population dynamics. Rather than assuming knowledge of the governing equations, we treat the system as a black box and attempt to learn its dynamics purely from observations of the state trajectory. Specifically, given 50 observations of the prey and predator populations at times $t_n = 0.4n$, $n = 0, \ldots, 49$, I design a two-stage kernel regression pipeline to recover the unknown vector field $f = (f_1, f_2)$ driving the system. In the first stage, I smooth the observed trajectories using an RBF kernel and differentiate analytically to obtain derivative estimates. In the second stage, I learn the map from state space to derivatives using a second kernel $\Gamma$, comparing three kernel families: RBF, polynomial, and exponential. We find that the degree-2 polynomial kernel achieves the lowest error across all metrics, with a mean absolute error of $0.1564$ for $f_1$ and $0.1232$ for $f_2$.  
  </p>
  <div class="project-footer">
    <div class="project-tags">
      <span class="project-tag">kernel estimation</span>
      <span class="project-tag">PDE</span>
      <span class="project-tag">Kernel Ridge Regression</span>
    </div>
    <a class="project-pdf" href="{{ site.url }}/assets/docs/Bergeron_kernel_PDE.pdf" target="_blank">
      Download the report
    </a>
  </div>
</div>

<!-- ── PROJECT 4 ─────────────────────────────────────────────── -->
<div class="project-card">
  <div class="project-number">Project 04</div>
  <h2>Mapping Diversity in Boston</h2>
  <div class="project-subtitle">2023</div>
  <p class="project-abstract">
    The Boston Planning and Development Agency has created a mapping tool to visualize multidimensional diversity throughout the city. In the tool, each geography is given a Diversity Index score to indicate its diversity across a certain dimension in comparison to other geographies. This tool is meant to investigate the concept of "diversity" and explore the city as whole. 
  </p>
  <div class="project-footer">
    <div class="project-tags">
      <span class="project-tag">ArcGIS</span>
      <span class="project-tag">Census Data</span>
      <span class="project-tag">Data Visualization</span>
    </div>
    <a class="project-pdf" href="https://storymaps.arcgis.com/stories/bd384a8649094d2e80afeca6da90b92a" target="_blank">
      View the tool
    </a>
  </div>
</div>

