---
title: "Research"
layout: gridlay
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

# Current Research Projects

<!-- ### Projects -->

- [Data-driven, Learning-based, Adaptive Control of Solid Fuel Ramjet](#sfrj)
- [State-Constrained Control](#state-constrained-control)
- [Active Vibration Suppression in Flexible Structures](#active-vibration-suppression-in-flexible-structures)


<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<!-- <h4>SFRJ</h4> -->


### Data-driven, Learning-based, Adaptive Control of Solid Fuel Ramjet {#sfrj}

The project aims to develop a learning-based adaptive control system for regulating the thrust of solid-fuel ramjets (SFRJs) under realistic flight conditions and in the presence of model uncertainties. By combining multi-fidelity computational modeling, adaptive control synthesis, and integrated multi-physics simulation, the research seeks to enable real-time thrust regulation and prevent engine unstart events. A simplified quasi-steady SFRJ model, derived from analytical ramjet theory and NASA’s chemical equilibrium analysis, is being validated against experimental data from China Lake and embedded within a Retrospective Cost Adaptive Control (RCAC) framework to demonstrate model-free, learning-based thrust regulation. An integrated simulation environment couples the SFRJ dynamics with flight and control system models to emulate realistic flight scenarios, while benchmark controllers such as LQG and reduced-order models provide performance baselines. Ultimately, the work aims to demonstrate that a controller trained on simplified models can adapt online to high-fidelity, dynamically coupled simulations, thereby paving the way for robust, learning-based propulsion control in next-generation hypersonic systems.

#### Team
- Principal Investigator – Dr. Ankit Goel, Assistant Professor, University of Maryland, Baltimore County
- Co-Principal Investigator – Dr. Kyle Hanquist, Assistant Professor, Purdue University
- Co-Principal Investigator – Dr. Brian Reitz, NAWCWD, China Lake, CA
- Co-Principal Investigator – Dr. Alireza Farahmandi, NAWCWD, China Lake, CA
- **Student Members**
  - Parham Oveissi, PhD Candidate, University of Maryland, Baltimore County
  - Alex Dorsey, Undergraduate Research Assistant, University of Maryland, Baltimore County
  - Alex Boueri, PhD Candidate, Purdue University
- **Past Team Members**
  - Joshua McBeth, PhD Candidate, University of Arizona
  - Avery White, PhD Candidate, University of Arizona
  - Dr. Raghava Davuluri, Postdoctoral Research Fellow, University of Arizona
  - Dr. Gohar T. Khokhar, Postdoctoral Research Fellow, University of Arizona
  - Dr. Ozgur Tumuklu, Assistant Professor, RPI

#### Publications
- Oveissi, P., Trivedi, A., Goel, A., Tumuklu, O., Hanquist, K. M., Farahmandi, A., and Philbrick, D., “Learning-Based Adaptive Thrust Regulation of Solid Fuel Ramjet,” AIAA SciTech 2023 Forum, AIAA Paper 2023-2533, January 2023. DOI: [https://doi.org/10.2514/6.2023-2533](https://doi.org/10.2514/6.2023-2533)
- Oveissi, P., Goel, A., Tumuklu, O., and Hanquist, K. M., “Adaptive Combustion Regulation in Solid Fuel Ramjet,” AIAA SciTech 2024 Forum, AIAA Paper 2024-0743, January 2024. DOI: [https://doi.org/10.2514/6.2024-0743](https://doi.org/10.2514/6.2024-0743)
- Oveissi, P., Dorsey, A., Khokhar, G. T., Hanquist, K. M., and Goel, A., “Adaptive Combustion Regulation in High-Fidelity Computational Model of Solid Fuel Ramjet,” AIAA SciTech 2025 Forum, AIAA Paper 2025-0352, January 2025. DOI: [https://doi.org/10.2514/6.2025-0352](https://doi.org/10.2514/6.2025-0352)
- Khokhar, G. T., McBeth, J., Hanquist, K. M., Oveissi, P., and Goel, A., “Investigation of Solid Fuel Ramjets Using Analytical Theory and Computational Fluid Dynamics,” AIAA SciTech 2025 Forum, AIAA Paper 2025-0392, January 2025. DOI: [https://doi.org/10.2514/6.2025-0392](https://doi.org/10.2514/6.2025-0392)
- Oveissi, P., Dorsey, A., McBeth, J., Hanquist, K. M., and Goel, A., “Learning-Based Thrust Regulation of Solid-Fuel Ramjet in Flight Conditions,” AIAA SciTech 2025 Forum, AIAA Paper 2025-2805, January 2025. DOI: [https://doi.org/10.2514/6.2025-2805](https://doi.org/10.2514/6.2025-2805)
- DeBoskey, R., Oveissi, P., Narayanaswamy, V., and Goel, A., “An In-Situ Solid Fuel Ramjet Thrust Monitoring and Regulation Framework Using Neural Networks and Adaptive Control,” 2025 IEEE Conference on Control Technology and Applications (CCTA), IEEE, August 2025, pp. 377–382. DOI: [10.1109/CCTA53793.2025.11151497](10.1109/CCTA53793.2025.11151497)
- [Accepted] Dorsey, A., Oveissi, P., Barton, J. D., and Goel, A., “Swarm-optimized Adaptive Augmentation of Missile Autopilot,” AIAA SciTech 2026 Forum, January 2026.
- [Accepted] Dorsey, A., and Goel, A., “Feedback Linearization-based Guidance Law for Guaranteed Interception,” AIAA SciTech 2026 Forum, January 2026.
- [Accepted] Oveissi, P., Khokhar, G. T., Hanquist, K. M., and Goel, A., “Thrust Regulation in a Solid Fuel Ramjet using Dynamic Mode Adaptive Control,” AIAA SciTech 2026 Forum, January 2026.
- [Accepted] McBeth, J., Hanquist, K. M., Oveissi, P., and Goel, A., “RANS-Fidelity Modeling and Control of Solid Fuel Ramjets,” AIAA SciTech 2026 Forum, January 2026.
- [Under review] Khokhar, G. T., Hanquist, K. M., Oveissi, P., and Goel, A., “Computational Modeling and Learning-Based Adaptive Control of Solid-Fuel Ramjets,” AIAA Journal.
- [Under review] DeBoskey, R., Oveissi, P., Narayanaswamy, V., and Goel, A., “Evaluation of In-situ Adaptive Thrust Monitoring and Regulation Framework for Solid-Fuel Ramjets,” AIAA Journal.
- [In preparation] Dorsey, A., and Goel, A., “A Generalized Guidance Law for Missile Interception,” Journal of Guidance, Navigation, & Control.

</div>
</div>

<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<!-- <h4>SFRJ</h4> -->


### State-Constrained Control {#state-constrained-control}

Real-world systems such as drones and robots must operate safely within strict physical limits. Enforcing these state constraints while maintaining stability is a core challenge in control design.

Our lab develops real-time control laws that guarantee both safety (forward invariance of a safe set) and stability (convergence to the desired state).
Traditional methods like Control Barrier Functions (CBFs) and Model Predictive Control (MPC) require solving optimization problems at each step—often too slow for practical use.

We introduce a constraint-lifting framework that transforms constrained dynamics into an unconstrained space using smooth, sigmoid-based mappings. This eliminates numerical issues near constraint boundaries and enables explicit, optimization-free controllers.

We also explore convex discrete-time CBF formulations and sigmoid-integral Lyapunov functions for fast, safety-preserving control. These techniques have been demonstrated on nonlinear systems, including bi-copters and attitude-control problems, achieving safe and stable performance in real time.

#### Team
- Principal Investigator – Dr. Ankit Goel, Assistant Professor, University of Maryland, Baltimore County
- Co-Principal Investigator – Dr. James Usevitch, Assistant Professor, BYU
- Co-Principal Investigator – Dr. Juan Paredes, Postdoctoral Research Fellow, University of Maryland, Baltimore County
- **Student Members**
  - Jhon Portella, PhD Candidate, University of Maryland, Baltimore County
  - Alex Dorsey, Undergraduate Research Assistant, University of Maryland, Baltimore County


#### Publications
- Usevitch, J., Salazar, J.A.P. and Goel, A., 2025. Computing Safe Control Inputs using Discrete-Time Matrix Control Barrier Functions via Convex Optimization. arXiv preprint arXiv:2510.09925.
- Delgado, J.M.P. and Goel, A., 2025. Stability Preserving Safe Control of a Bicopter. arXiv preprint arXiv:2510.07145.
- Salazar, J.A.P., Usevitch, J. and Goel, A., 2025. Predictive Control Barrier Functions for Discrete-Time Linear Systems with Unmodeled Delays. arXiv preprint arXiv:2510.01059.
- Delgado, J.M.P. and Goel, A., 2025. A Constraint-Lifting Framework for Safe and Stable Nonlinear Control. Submitted to IEEE ITAC.
</div>
</div>



<div class="jumbotron">
<div class="col-md-12 col-sm-12">
<!-- <h4>SFRJ</h4> -->


### Active Vibration Suppression in Flexible Structures {#active-vibration-suppression-in-flexible-structures}

Flexible structures in aerospace, energy, and mechanical systems, such as wings, blades, panels, and beams, are highly susceptible to vibrations induced by aerodynamic loading, external disturbances, and structural nonlinearities. These vibrations degrade performance, accelerate fatigue, and can trigger instabilities such as flutter. Despite decades of work, practical vibration suppression remains challenging due to modeling uncertainty, actuator/sensor placement constraints, spillover effects, and limited sensing.

Classical vibration control approaches often rely on either high-fidelity physics-based models or fully model-free heuristics, each with clear limitations. High-order models are difficult to identify and control in practice, while purely adaptive schemes must carefully manage robustness and spillover. A key open challenge is developing low-complexity, output-feedback vibration controllers that (i) target dominant vibration modes, (ii) tolerate modeling uncertainty, and (iii) interface naturally with experimentally realizable sensing and actuation.

Our recent work investigates two complementary control paradigms for vibration suppression in cantilevered flexible structures. 

- **Robust low-order optimal control**. We developed a frequency-weighted H₂/H∞ output-feedback controller using a low-order linear model identified from high-fidelity finite-element simulations. Frequency-weighting filters are used to explicitly emphasize dominant vibration modes, enabling targeted suppression while maintaining robustness to parameter variations and actuator placement uncertainty. The controller is designed without direct access to the full nonlinear model and is suitable for experimental implementation.

- **Model-free adaptive output feedback control**. We implemented Retrospective Cost Adaptive Control (RCAC) to suppress vibrations caused by unknown disturbances using only measured outputs. Both displacement and acceleration feedback are considered. To mitigate spillover effects commonly associated with acceleration sensing, we design signal-conditioning filters that extract displacement-relevant information while suppressing high-frequency amplification. The resulting controller adapts online without requiring a plant model.

#### Team
- Principal Investigator – Dr. Ankit Goel, Assistant Professor, University of Maryland, Baltimore County
- Co-Principal Investigator – Dr. Juan Paredes, Postdoctoral Research Fellow, University of Maryland, Baltimore County
- **Student Members**
  - Olvin Moran, Undergraduate Research Assistant, University of Maryland, Baltimore County
  - Maximillian Moody, Undergraduate Research Assistant, University of Maryland, Baltimore County


#### Publications
- Paredes Salazar, J.A. and Goel, A., "Model-Free Adaptive Output Feedback Vibration Suppression in a Cantilever Beam," AIAA 2026-1845. AIAA SCITECH 2026 Forum. January 2026. DOI: [https://doi.org/10.2514/6.2026-1845](https://doi.org/10.2514/6.2026-1845)
- Mirtaba, M., Paredes Salazar, J.A., Huang, D. and Goel, A., 2026. Low-Order H2/H-infinity Controller Design for Aeroelastic Vibration Suppression. AIAA 2026-1846. AIAA SCITECH 2026 Forum. January 2026. DOI: [https://doi.org/10.2514/6.2026-1846](https://doi.org/10.2514/6.2026-1846)
</div>
</div>
