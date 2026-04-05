---
layout: default
title: Research
permalink: /research/
---

<div class="content-page">
  <h1 class="page-heading">Research</h1>

  <p>
    Our research lies in fluid mechanics problems that are illuminated by a combination of theoretical modelling and computational mathematics. Much of this work is motivated by experiments on complex and biological fluids, with an emphasis on identifying the physical mechanisms that govern motion, transport, and interaction at small scales.
  </p>

  <h2>Complex Fluids and Electrohydrodynamics</h2>
  <p>
    Complex fluids are materials whose behaviour reflects an interplay between microstructure and flow, rather than a single constant viscosity. Examples include emulsions, suspensions, and biological media, where interfaces, particles, or internal structure influence macroscopic dynamics. A central goal is to understand how microscale physics feeds back into continuum-scale motion and transport.
  </p>
  <p>
    Building on this general framework, a major part of our research concerns the dynamics of dielectric particles and liquid drops suspended in another liquid medium and subjected to electric fields. These problems fall within electrohydrodynamics and are often described by the Melcher&ndash;Taylor leaky dielectric model. We are particularly interested in weakly conducting particles and drops in strong electric fields, where symmetry-breaking instabilities can lead to Quincke electrorotation. Using a combination of analysis and computation, We study how electric forcing, interfacial mechanics, and hydrodynamic interactions combine to produce nonlinear dynamics. This work has helped explain experimentally observed behaviour of particles and drops and reproduce it in simulations. It also connects naturally to active matter, since Quincke-driven particles provide a simple model system for self-propulsion and collective motion.
  </p>

  <div class="video-block">
    <div class="video-text">
      <h3>A three-dimensional small-deformation theory for electrohydrodynamics of dielectric drops</h3>
      <p>
        This paper develops a three-dimensional small-deformation theory for dielectric drops in electric fields within the full Melcher&ndash;Taylor leaky-dielectric framework. The theory captures both steady deformation in weak fields and the transition to Quincke rotation in stronger fields, where the drop spontaneously tilts and rotates. By retaining both the straining and rotational components of the flow in the surface charge dynamics, the model yields a criterion for the onset of Quincke rotation. The predictions agree well with experiments in the small-deformation regime.
      </p>
      <p class="small-note">
        D. Das and D. Saintillan, <em>Journal of Fluid Mechanics</em> <strong>914</strong>, A22 (2021).
      </p>
    </div>
    <div class="video-box">
      <video controls preload="metadata">
        <source src="{{ '/videos/2023_JFM_1.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Quincke rotation of a drop</div>
    </div>
  </div>

  <div class="video-block video-block-stacked">
    <div class="video-text video-text-full">
      <h3>Electrohydrodynamics of viscous drops in strong electric fields: numerical simulations</h3>
      <p>
        This paper develops a three-dimensional boundary element method for the full leaky-dielectric model to study the deformation and dynamics of viscous drops in strong electric fields. Unlike many earlier simulations, it includes interfacial charge convection and therefore captures non-axisymmetric behaviours in the Quincke regime, where drops undergo symmetry breaking and steady electrorotation. The simulations recover a wide range of dynamical responses and show excellent agreement with both experiments and small-deformation theory. The work provides a detailed numerical framework for understanding drop electrohydrodynamics beyond the weak-field and axisymmetric limits.
      </p>
      <p class="small-note">
        D. Das and D. Saintillan, <em>Journal of Fluid Mechanics</em> <strong>829</strong>, 127&ndash;152 (2017).
      </p>
    </div>

    <div class="video-pair-row">
      <div class="video-box">
        <video controls preload="metadata">
          <source src="{{ '/videos/2017_JFM_3_web.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <div class="video-caption">Taylor regime: weak electric fields</div>
      </div>

      <div class="video-box">
        <video controls preload="metadata">
          <source src="{{ '/videos/2017_JFM_4_web.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <div class="video-caption">Quincke regime: strong electric fields</div>
      </div>
    </div>
  </div>

  <div class="video-block video-block-stacked">
    <div class="video-text video-text-full">
      <h3>Active particles powered by Quincke rotation in a bulk fluid</h3>
      <p>
        This paper shows that spontaneous Quincke rotation can be converted into translational motion in a bulk fluid without relying on nearby surfaces. Using theory and numerical simulations, it demonstrates that geometric asymmetry alone is sufficient to break symmetry and produce self-propulsion in a plane perpendicular to the applied electric field. The work introduces a new route to electrically driven active particles in unbounded fluids. It also provides a simple model system for exploring active matter powered by Quincke rotation.
      </p>
      <p class="small-note">
        D. Das and E. Lauga, <em>Physical Review Letters</em> <strong>122</strong>, 194503 (2019).
      </p>
    </div>

    <div class="video-pair-row">
      <div class="video-box">
        <video controls preload="metadata">
          <source src="{{ '/videos/2019_PRL_1_web.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <div class="video-caption">A helix self-propels due to Quincke rotation, while a non-chiral cylinder does not.</div>
      </div>

      <div class="video-box">
        <video controls preload="metadata">
          <source src="{{ '/videos/2019_PRL_2_web.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support the video tag.
        </video>
        <div class="video-caption">There is an optimal thickness at which the swimming speed is maximised.</div>
      </div>
    </div>
  </div>

  <h2>Biological Fluids, Cilia, and Intracellular Flows</h2>
  <p>
    Biological flows arise when fluid motion is driven by living systems, such as cilia, flagella, or molecular motors. These flows typically occur at low Reynolds number, where viscous forces dominate inertia, and transport depends strongly on geometry, elasticity, and coordinated forcing. Understanding these systems requires linking microscale actuation to macroscopic transport and organisation.
  </p>
  <p>
    In this broader biological context, another strand of our research is concerned with fluid mechanics in biological systems, especially flows generated by cilia, flagella, and molecular motors at low Reynolds number. At these scales, viscous forces dominate inertia, so transport and propulsion depend on geometry, elasticity, and coordinated forcing. We develop mathematical models for microorganism locomotion, cilia-driven transport, and intracellular flows, using tools such as resistive-force theory, slender-body theory, and boundary element methods. These problems are motivated by questions in physiology and cell biology, but they also raise fundamental issues in microscale fluid mechanics. A recurring theme is to understand how microscale actuation generates larger-scale pumping, transport, and collective behaviour. This provides a framework for connecting molecular or filament-level activity to observable flow and transport.
  </p>

  <div class="video-block">
    <div class="video-text">
      <h3>Cilia dynamics create a dynamic barrier to penetration of the periciliary layer in human airway epithelia</h3>
      <p>
        The study develops a fluorescence-based method to measure fluid flow inside the periciliary layer of the human airway, where direct observation is usually very difficult. The experiments show that transport within this layer is vertically nonuniform and that cilia actively expel fluid near their tips, which may help protect the epithelium from pathogens. Numerical simulations support these observations and highlight the importance of cilia geometry and coordination in shaping respiratory fluid transport.
      </p>
      <p class="small-note">
        E. Causa, D. Das, L. Feriani, J. Kotar, and P. Cicuta, <em>Proceedings of the National Academy of Sciences</em> <strong>122</strong> (28), e2419032122 (2025).
      </p>
    </div>
    <div class="video-box">
      <video controls preload="metadata">
        <source src="{{ '/videos/2025_PNAS_1.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Flow above cilia</div>
    </div>
  </div>

  <h2>Bacterial Hydrodynamics and Microorganism Locomotion</h2>
  <p>
    We are also interested in the mechanics of swimming microorganisms, especially bacteria interacting with nearby boundaries. At low Reynolds number, hydrodynamic interactions with walls can strongly influence orientation, stability, and transport. My work studies how body shape, flagellar forcing, and near-surface flows determine bacterial trajectories and long-time behaviour. These questions are relevant both to the basic mechanics of locomotion and to processes such as confinement, surface accumulation, and the early stages of biofilm formation. They also provide a useful setting in which asymptotic modelling and numerical simulation can be compared directly. More broadly, this area connects microbial behaviour with the general fluid mechanics of active suspensions.
  </p>

  <div class="video-block">
    <div class="video-text">
      <h3>Hydrodynamic hovering of swimming bacteria above surfaces</h3>
      <p>
        Flagellated bacteria are hydrodynamically attracted to rigid walls, yet past work shows a hovering state where they swim stably at a finite height above surfaces. We use numerics and theory to reveal the physical origin of hovering. Simulations first show that hovering requires an elongated cell body and results from a tilt away from the wall. Theoretical models then identify two essential asymmetries: the response of width-asymmetric cells to active flows created by length-asymmetric cells. A minimal model reconciles near- and far-field hydrodynamics, capturing all key features of hovering.
      </p>
      <p class="small-note">
        P. H. Htet, D. Das, and E. Lauga, <em>Physical Review Research</em> <strong>6</strong> (3), L032070 (2024).
      </p>
    </div>
    <div class="video-box">
      <video controls preload="metadata">
        <source src="{{ '/videos/2024_PRR.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Bacteria hovering</div>
    </div>
  </div>

  <div class="video-gallery-row">
    <div class="video-gallery-item">
      <video controls preload="metadata">
        <source src="{{ '/videos/2024_PRR_2_web.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Ellipsoidal cell body: top view</div>
    </div>

    <div class="video-gallery-item">
      <video controls preload="metadata">
        <source src="{{ '/videos/2024_PRR_3_web.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Ellipsoidal cell body: side view</div>
    </div>

    <div class="video-gallery-item">
      <video controls preload="metadata">
        <source src="{{ '/videos/2024_PRR_5_web.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Spherical cell body: top view</div>
    </div>

    <div class="video-gallery-item">
      <video controls preload="metadata">
        <source src="{{ '/videos/2024_PRR_4_web.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <div class="video-caption">Spherical cell body: side view</div>
    </div>
  </div>

  <p class="small-note">
    Additional simulations from the same paper, showing representative hovering states and near-surface bacterial trajectories. Spherical-shaped bacterial cell bodies tend to get attracted all the way to the surface.
  </p>
</div>
