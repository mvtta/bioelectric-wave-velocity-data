<h2 align="center">
Collecting Velocities of Bio-Chemical Gradients

</h2>
<h6 align="center">
Bioelectric wave velocities preliminary data compilation
</h6>

*Author: Valdetaro, M.*

This project aimed at a compilation of biochemical gradient and wave velocities across different chemical species in developmental biology contexts, with particular interest in signaling related phenomena. It contains 42 data points covering 14 different chemical gradients, for supporting a future study in which they will be used for calculating relationships between chemical gradient composition, tissue type, and resulting wave velocities in bioelectric developmental moments. There's a keen and expplicit interest imotivating this exercise from nematics perspective, thus a physics-based metheodological review from the sources of the data and some extra ones is found as an [annex](#annex-report-and-inventory-based-on-a-preliminary-review-of-measurement-and-modeling-tools-with-physics-based-approaches-for-understanding-and-controlling-bioelectric-signaling-in-developmental-biology). The purpose is to complement the csv files for extra context and for aiding in future projects.

Image source: [[Funk & Scholkmann 2023]](#funk2023)

*The significance of bioelectricity on all levels of organization of an organism*

![IMG_COVER](https://ars.els-cdn.com/content/image/1-s2.0-S0079610722001304-gr1.jpg "Electrostatics in the molecular domain. (a) Molecular electrostatic potential (MEP) maps of three neurotransmitters (calculated and visualized via the online simulation software molview.org). (b) MEP of SARS-CoV-2 spike protein binding receptor domain (BRD) and the human angiotensin-converting enzyme 2 (ACE2) receptor as well as the electrostatic interaction between both. Reprinted and modified from Xie et al. (Xie et al., 2020), with permission from the publisher. The white lines covering ACE2 like spikes represent the vectors of the electrical field caused by the charge distribution. In the zoomed-in image, the field lines (white lines) connect both macromolecules, visualizing the electrostatic interaction between both.")

###### Scope

This dataset provides a compilation of biochemical gradient and wave velocities across different chemical species in developmental biology contexts, with particular interest in signaling related phenomena. It contains 42 data points covering 14 different chemical gradients, for supporting a future study in which they will be used for calculating relationships between chemical gradient composition, tissue type, and resulting wave velocities in bioelectric developmental moments.

###### A table of contents

- [Block](#######-Block-I)
  * [Block](#######-Block-2)
  * [Block](#######-Block-2)
  * [Block](#######-Block-2)
- [Block](#######-Block-I)
  * [Block](#######-Block-2)
  * [Block](#######-Block-2)
  * [Block](#######-Block-2)

## Dataset Summary

**Total Coverage:**

- 27 total entries across 10 chemical gradients
- 18 unique citations from 1985-2025
- 13 organisms and 14 tissue types represented
- Velocity range: 9 orders of magnitude (0.08 μm/s to 1540 m/s)

##### Files

###### data/data/biochem_waves_datasheet.csv

| Entry_ID | Value | Unit  | Chemical_Gradient | Parameter_Type | Tissue_Type      | Organism       | Context           | Citation_Key     | Intra_Inter | Health_Status | Statistical_Data |
| -------- | ----- | ----- | ----------------- | -------------- | ---------------- | -------------- | ----------------- | ---------------- | ----------- | ------------- | ---------------- |
| BWV001   | 6.7   | μm/s | Calcium           | Wave velocity  | Embryonic tissue | Xenopus laevis | Mechanical injury | Tung et al. 2024 | Yes/No      | Yes/No        | SD: 3.48, N: 7.0 |

###### data/data/biochem_waves_small.csv

| Value | Unit  | Chemical_Gradient | Parameter_Type | Std_Dev | N   | Intra | Inter | Organism       | Tissue_Type      | Context           | Injured | Healthy | Signaling_Type | Citation         |
| ----- | ----- | ----------------- | -------------- | ------- | --- | ----- | ----- | -------------- | ---------------- | ----------------- | ------- | ------- | -------------- | ---------------- |
| 6.7   | μm/s | Calcium           | Wave velocity  | 3.48    | 7.0 | Yes   | No    | Xenopus laevis | Embryonic tissue | Mechanical injury | Yes     | No      | Calcium wave   | Tung et al. 2024 |

###### data/data/biochemical_waves_big.csv

| Value | Unit  | Chemical_Gradient | Parameter_Type | Std_Dev | N   | Intra | Inter | Organism       | Tissue_Type      | Context           | Injured | Healthy | Signaling_Type | Citation         |
| ----- | ----- | ----------------- | -------------- | ------- | --- | ----- | ----- | -------------- | ---------------- | ----------------- | ------- | ------- | -------------- | ---------------- |
| 6.7   | μm/s | Calcium           | Wave velocity  | 3.48    | 7.0 | Yes   | No    | Xenopus laevis | Embryonic tissue | Mechanical injury | Yes     | No      | Calcium wave   | Tung et al. 2024 |

## Methodology

**Primary Databases:**

- PubMed/PMC (primary source)
- Nature Publishing Group journals
- Science Direct
- bioRxiv preprint server
- Specialized developmental biology journals

### Search Strategy

**Primary Search Terms** (combined with Boolean operators):

- `"calcium wave velocity"` AND (`"embryo"` OR `"development"`)
- `"bioelectric signaling"` AND `"velocity"` AND `"measurements"`
- `"cAMP wave"` AND `"developmental biology"`
- `"ATP wave"` AND `"cell signaling"` AND `"velocity"`
- `"potassium gradient"` AND `"embryonic development"`
- `"chloride wave"` AND `"morphogenesis"`
- `"nitric oxide"` AND `"wave speed"` AND `"tissue"`
- `"morphogen gradient"` AND `"velocity"` AND `"diffusion"`
- `"gap junction"` AND `"bioelectric"` AND `"communication"`
- `"intercellular signaling"` AND `"wave propagation"`

### Temporal Coverage

**Time Frame:** 1985-2025 (40-year span)

- **Primary focus:** Recent work (2010-2025) for technical accuracy
- **Historical component:** Foundational papers included for comparative analysis

## Selection Criteria

### Inclusion Criteria

**Primary Requirements:**

- **Quantitative measurements:** Studies must provide numerical values with units
- **Biological relevance:** Focus on developmental biology, morphogenesis, and bioelectric signaling
- **Wave/gradient dynamics:** Measurements of propagation velocities, diffusion coefficients, or temporal dynamics
- **Peer-reviewed sources:** Priority given to peer-reviewed publications
- **Reproducible methodology:** Studies with clear experimental methods

**Secondary Criteria:**

- **Statistical rigor:** Preference for studies with error bars, sample sizes, and statistical analysis
- **Multi-organism representation:** Coverage across model organisms (*Xenopus*, *Drosophila*, mouse, etc.)
- **Tissue-type diversity:** Inclusion of different tissue types and developmental stages
- **Chemical gradient diversity:** Representation of multiple biochemical species

### Exclusion Criteria

- **Non-quantitative studies:** Purely qualitative descriptions without measurements
- **Pathological conditions:** Studies focusing solely on disease states (unless comparing to healthy controls)
- **Duplicate measurements:** Same data reported in multiple publications
- **Insufficient methodological detail:** Studies lacking clear experimental protocols

## Velocity Related Notes

### Velocity-Chemistry Correlations

1. **Chemical-Specific Speed Ranges:** Different chemical gradients operate at characteristic speed ranges:
   - Calcium/ATP: μm/s range
   - cAMP: μm/min range
   - Sodium: m/s range
2. **Tissue-Specific Scaling:** The same chemical gradient shows different velocities in different tissue types:
   - Calcium waves: 2.36 μm/s in healthy embryonic tissue vs 40 μm/s in depolarized astrocytes
3. **Developmental Context:** Many velocities change during development:
   - K⁺ channel activation shifts from -20.3 to -33.1 mV
   - cAMP waves slow during aggregation
4. **Signaling Mode Differences:** Inter-cellular signaling often shows intermediate velocities compared to pure intracellular waves

### Velocity Range Analysis

- **Slowest:** Bicoid morphogen advection (0.08 μm/s) [[Hecht et al. 2009]](#hecht2009)
- **Fastest:** Acoustic waves in embryonic tissue (1540 m/s) [[Titov et al. 2023]](#titov2023)
- **Most common range:** Calcium and ATP waves (2-40 μm/s) [[Tung et al. 2024]](#tung2024); [[Fontanilla &amp; Nuccitelli 1998]](#fontanilla1998); [[Arcuino et al. 2002]](#arcuino2002)

## Chemical Gradient Classifications

| Chemical Gradient                | Measurements | Parameter Range                                                                                                               | Tissue Types                                         | Key Findings                                                                                                     | Citations                                                                                                                                  |
| -------------------------------- | ------------ | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Calcium Waves**          | 11 entries   | 2.36 - 40.00 μm/s                                                                                                            | Embryonic tissue, cortical astrocytes, smooth muscle | Inter-embryo communication: 5.28 μm/s; Injured tissue response: 6.7 μm/s; Tissue-dependent velocity variations | [[Tung et al. 2024]](#tung2024); [[Fontanilla &amp; Nuccitelli 1998]](#fontanilla1998); [[Chevalier 2018]](#chevalier2018); [[Jaffe 2010]](#jaffe2010) |
| **cAMP Waves**             | 5 entries    | 50 μm/s - 350 μm/min                                                                                                        | Amoeba collectives, individual cells                 | Speed decreases during aggregation: 350 → 175 μm/min; Collective behavior influences propagation velocity      | [[Hashimura et al. 2019]](#hashimura2019); [[Ford et al. 2023]](#ford2023); [[Soll et al. 2004]](#soll2004)                                                                                                     |
| **ATP Waves**              | 3 entries    | 11 μm/s wave velocity, 200 μm propagation distance                                                                          | Cochlear supporting cells, astrocytes                | ATP-induced calcium coupling mechanism; Critical role in intercellular communication                             | [[Ceriani et al. 2016]](#ceriani2016); [[Arcuino et al. 2002]](#arcuino2002)                                                                                                               |
| **Potassium Gradients**    | 3 entries    | -33.1 to -20.3 mV activation voltages, 8.8 nA max current                                                                     | Inner hair cells during development                  | Developmental shift in K⁺ channel properties; Voltage-dependent activation changes with maturation              | [[Marcotti 2003]](#marcotti2003)                                                                                                                            |
| **Chloride Gradients**     | 2 entries    | 50 μM/s uptake velocity, 8-second action potentials                                                                          | Neurons, embryonic skeletal muscle                   | NKCC1-mediated developmental regulation; Critical for action potential duration in development                   | [@Watanabe2015; @Steele1990]                                                                                                               |
| **Sodium Waves**           | 2 entries    | 1-100 m/s action potential velocities                                                                                         | Myelinated vs unmyelinated neurons                   | 100-fold speed difference based on myelination status; Fundamental role in neural signal propagation             | [[Appukuttan et al. 2021]](#appukuttan2021)                                                                                                                          |
| **Nitric Oxide Gradients** | 3 entries    | 100-150 μm diffusion distances, 20% concentration changes                                                                    | Motor neurons, muscle tissue                         | NO regulates axon branching during development; Spatial gradient formation over developmental distances          | [@Bradley2010; @Sugita2008]                                                                                                                |
| **pH Gradients**           | 2 entries    | 0.1 pH units/μm steepness, pH 7.2 baseline                                                                                   | Migrating cells                                      | pH gradients drive directional cell migration; Local pH regulation affects cellular behavior                     | [[Li et al. 2024]](#li2024)                                                                                                                                  |
| **Morphogen Gradients**    | 5 entries    | Bicoid: 0.08 μm/s advection velocity, 100 μm length scale; FGF8: 100 μm²/s diffusion coefficient, 200 μm gradient extent | Embryonic cytoplasm, extracellular space             | Bicoid morphogen advection and diffusion dynamics; FGF8 morphogen transport and gradient formation               | [@Hecht2009; @Wartlick2009]                                                                                                                |
| **Magnesium Transport**    | 2 entries    | 2.5 mM intracellular concentration, 40 Å pore length                                                                         | CorA transporter, cellular cytoplasm                 | CorA transporter structural dynamics; Critical for cellular magnesium homeostasis                                | [[Dalmas et al. 2010]](#dalmas2010)                                                                                                                              |

---

## Limitations and Considerations

### Quality Control Measures

Values cross-checked against multiple independent sources where available, and all numerical values verified against original sources (human apologies if mistakes were made).

### Selection Bias Considerations

It is acknowledged that selection bias involved in the collection of the wave velocities presented. The publication bias reflects on the explicit preference for studies with statistically significant findings, english-language publications were preferentially included, open-access papers given this project received no funding.

### Technical Considerations

Please note that measurement precision were not questioned, and that different techniques have varying spatial and temporal resolution. This means that for usage one most consider detection thresholds, the sensitivity limits which may affect reported velocities, compliance with calibration standards, for which not all studies use identical calibration methods, neither were these identified. Additionally, laboratory conditions may influence measured parameters.

## Concluding remarks

This database is a preliminary initiative for the compilation of bioelectric and biochemical wave velocities across developmental contexts. The articles from where the velocities where extracted mention that chemical specificity drives characteristic velocity ranges, and tissue context significantly modulates propagation speeds. Concerning developmental timing affects signaling dynamics, the multi-modal signaling seems to require integrated analytical approaches.

---

## Clone, fork and contribute to this project

### Clone the repository

```bash
git clone https://github.com/mvtta/bioelectric-wave-velocity-data.git
cd bioelectric-wave-velocity-data
```

### Fork and contribute

1. Fork this repository on GitHub
2. Clone your fork:

```bash
git clone https://github.com/YOUR_USERNAME/bioelectric-wave-velocity-data.git
cd bioelectric-wave-velocity-data
```

3. Create a new branch for your feature:

```bash
git checkout -b feature/your-feature-name
```

4. Make your changes and commit them:

```bash
git add .
git commit -m "Add your meaningful commit message"
```

5. Push to your fork:

```bash
git push origin feature/your-feature-name
```

6. Create a Pull Request on GitHub

### Contribution Guidelines

- Add new wave velocity data with proper citations
- Ensure data follows the existing CSV format
- Update documentation accordingly
- Include statistical data when available
- Please add the citations in the folder references

# Annex: Report and inventory based on a preliminary review of measurement and modeling tools with physics-based approaches for understanding and controlling bioelectric signaling in developmental biology

This report provides a preliminary inventory and review of measurement and modeling tools with physics-based approaches for understanding and controlling bioelectric signaling in developmental biology. Focusing on gradients, waves, nematics, and regeneration, the goal is to contextualise the wave velocity data within a quantitative physics-based methods for analysis and control of bioelectric signaling in development and repair. Thirteen distinct methodological frameworks were reviewed, investigating the relationships between bioelectric patterns, wave dynamics, and morphogenetic outcomes. Please find enumerated some of the open questions found in the literature concerning compiled wave velocities according to mechanochemical gradients, with supporting data available in this project's data folder.

## Introduction

The "bioelectric code" stands for voltage patterns across tissues which carry morphological information that guides developmental processes. This report catalogs the methodological landscape, collecting the findings concerning how different physics-based frameworks contribute to our understanding of bioelectric morphogenesis and its control mechanisms. ... program that includes nematic order and propagating waves as quantitative observables. Second, paired with the finding in the collected data and aditional sources addressing bioelectric code framework in which $V_{	ext{mem}}$ distributions and gap-junction networks encode morphogenetic instructions above the single-cell level. The goad is a physics based correlation from a landscape approach for decoding and control require quantitative, multicellular models and data-driven inference methods.[[Tung et al. 2024]](#tung2024); [[LevinMartyniuk 2017]](#levin2017); [[ManickaPaiLevin 2023]](#manicka2023); [[GuyomarDeSimone 2025]](#guyomar2025)]

## Definitions: Gradients, Waves, and Nematics

A very brief and non-extensive account of minimal definitions for a quick ramp-up on the topic.

#### Gradients

Reaction–diffusion frameworks capture positional information and scaling (e.g., Wnt/β-catenin in Hydra and planaria), with emphasis on identifying morphogens, expanders, and dose–distance recruitment signals during regeneration.[[Guyomar & De Simone 2025]](#guyomar2025); [[Tung et al. 2024]](#tung2024)

#### Bio-Electric Waves

Regenerative tissues exhibit chemical wavefronts (e.g., ERK rings in zebrafish scale regrowth) with speeds on the order of ~10 μm/h that coordinate growth and stress distribution, linking kinetics to size control and robustness.[@Tung2024; @GuyomarDeSimone2025]

#### Nematics

Active nematic hydrodynamics connects topological defect structure to curvature, growth, extrusion, and tissue architecture, providing a quantitative bridge between cell alignment, flows, and morphogenesis in epithelia and Hydra-like systems.[@VafaMahadevan2022; @Balasubramaniam2022]

#### Bioelectric Code

Spatial $V_{\text{mem}}$ patterns and gap-junction connectivity guide patterning and organogenesis, with experimentally validated reprogramming of large-scale anatomy and new information-integration models connecting voltage maps to gene expression dynamics in development and regeneration.[@LevinMartyniuk2017; @ManickaPaiLevin2023]

#### Kymographs and Line Scans

Track space–time slopes of wavefront intensity in calcium or kinase-biosensor imaging; widely used for excitable media and vascular/neuronal flows where 1D trajectories can be defined.[@Meng2022; @Herron2012]

#### Optical Flow

Lucas–Kanade and related methods estimate local motion fields from fluorescence movies to quantify complex wavefronts beyond simple fronts, capturing curvature, splitting, and anisotropy in living tissues.[@Afrashteh2017; @Afrashteh2017]

#### PIV/Cross-Correlation

Particle image velocimetry and cross-correlation kymography quantify propagation velocities and flow-mediated transport, complementing optical flow for high-speed flow or RBC/marker tracking.[@Meng2022; @Meng2022]

#### Spatiotemporal Autocorrelation/Dispersion Analysis

Extracts dominant phase velocities and wavelengths from biosensor movies to infer collective oscillation and propagation parameters in excitable or oscillatory media.[@Herron2012; @GuyomarDeSimone2025]

#### Voltage Imaging via Electrochromic Stark Effect

ANNINE-6/6plus and hemicyanine dyes (di-4-ANEPPS family) provide linear, high-speed voltage readouts; two-photon implementations enable in vivo deep-tissue $V_{\text{mem}}$ mapping with known thermodynamic sensitivity limits.[@Miller2016; @Kuhn2019]

#### GEVI/Optogenetics

Genetically encoded voltage indicators and optogenetic ion channels enable mapping and perturbation of $V_{\text{mem}}$ networks for causal tests of bioelectric control in development and regeneration.[@Mathews2018; @RoomeKuhn2020]

#### Calcium/ERK Reporters

GCaMP and kinase activity biosensors enable wave tracking in embryonic/regenerative contexts (e.g., ERK rings in scale regeneration), with quantitative ring speed and period estimation.[@Herron2012; @GuyomarDeSimone2025]

#### Reaction-Diffusion and Excitable Media

FitzHugh–Nagumo and Barkley models capture thresholds, refractory periods, fronts/spirals, and dispersion, serving as workhorses for calcium/cAMP and ERK wave phenomenology and for parameter inference from velocity–period–curvature data.[@Barkley2008; @FHN2024]

#### Active Nematics Hydrodynamics

Continuum theories of director fields and defect dynamics relate stress, curvature, proliferation, apoptosis, and tissue flows, predicting morphology–defect co-localization and ring/tentacle configurations in epithelial and Hydra-like systems.[@Balasubramaniam2022; @VafaMahadevan2022]

#### Mechanochemical Coupling

Mechanochemical/active gel frameworks link chemical signaling to force generation and tissue remodeling, enabling joint fits to wave kinematics and tissue deformation fields in morphogenesis.[@Howard2011; @DiTalia2022]

#### Information-Integration and Bioelectric Networks

Minimal models map multicellular voltage patterns to gene expression via causal integration metrics, complementing data-driven inference of the bioelectric code and guiding interventions.[@ManickaPaiLevin2023; @Silic2023]

## Methodological Inventory

### Methods for Velocity Computation and Signal Decoding

| Category        | Method                    | What it computes                                      | Typical outputs                                | Notes                                                     |
| --------------- | ------------------------- | ----------------------------------------------------- | ---------------------------------------------- | --------------------------------------------------------- |
| Wave kinematics | Kymograph slope           | Front velocity along a line                           | μm/s or μm/min                               | Simple and robust for 1D paths or rings [[Herron et al. 2012]](#herron2012)     |
| Wave kinematics | Optical flow              | Vector velocity field of fronts                       | Speed maps, curvature effects                  | Captures splitting/aniso beyond 1D [@Afrashteh2017]       |
| Wave kinematics | PIV/cross-correlation     | Flow or wave transport velocity                       | Bulk or local velocities                       | Useful for high-speed flows or sparse tracers [@Meng2022] |
| Voltage mapping | Electrochromic VSDs       | $\Delta F/F$ proportional to $\Delta V$ via Stark | $V_{\text{mem}}$ movies, conduction velocity | ANNINE and di-4-ANEPPS families [@Miller2016]             |
| Voltage mapping | GEVIs                     | Fluorescent voltage reporters                         | $V_{\text{mem}}$ dynamics                    | Complements VSDs and enables genetics [@RoomeKuhn2020]    |
| Modeling        | FitzHugh–Nagumo/Barkley  | Excitable wave fronts and spirals                     | $v$–$\kappa$ relations, dispersion        | Fits for calcium/cAMP media [@Barkley2008]                |
| Modeling        | Active nematics PDEs      | Defect and director dynamics                          | Defect velocities, flows                       | Links defects to growth/curvature [@Balasubramaniam2022]  |
| Modeling        | Mechanochemical couplings | Signal–stress coupling                               | Coevolution of shape/signal                    | Epithelial morphogenesis fits [@DiTalia2022]              |
| Inference       | Information integration   | $V_{\text{mem}} \rightarrow$ gene mapping           | Causal integration metrics                     | Validated in Xenopus brain [@ManickaPaiLevin2023]         |

## Current Applications: Established Model Systems and Approaches

#### ERK/cAMP Excitable Oscillators

Tissue-scale ERK ring waves and classic Dictyostelium cAMP waves remain exemplars for linking biochemical waves to collective migration and growth control, with quantitative wave speeds and periods.[@Ford2023; @GuyomarDeSimone2025]

#### Gap-Junction Mediated Coordination

Connexin-specific pathways synchronize and propagate bioelectric and calcium signals across developing muscle and neuromuscular tissues, providing direct conduits for fast multi-cellular coupling.[@Appukuttan2021; @LukowiczBedford2023]

#### Optical Mapping in Excitable Tissues

Cardiac/neuronal optical mapping provides mature workflow for conduction velocities and arrhythmic wave dynamics, transferrable to developmental sheets and organoids.[@Herron2012; @Herron2012]

## Methodological Frameworks

### 1. Turing Reaction-Diffusion Models

**Physics Basis:** Diffusion-driven instability where differential diffusion rates of activator and inhibitor species create spatially periodic patterns.

**Expression:**

$$
\frac{\partial u}{\partial t} = D_u\nabla^2u + f(u,v)
$$

$$
\frac{\partial v}{\partial t} = D_v\nabla^2v + g(u,v)
$$

**Wave Velocity Calculation:** For traveling waves, $c = \sqrt{D_u \times k_1}$ in linear approximation, where $D_u$ is the diffusion coefficient and $k_1$ is the reaction rate.

**Quantitative Outputs:** Pattern wavelength $\lambda = 2\pi\sqrt{\frac{D_u \times D_v}{\text{reaction rate}}}$

**Bioelectric Integration:** Limited, traditionally focused on chemical morphogens but increasingly extended to include bioelectric coupling through voltage-gated processes.

**Applications:** Pigmentation patterns, morphogen gradients, digit formation
**Limitations:** Requires fine-tuned parameter ratios; historically lacks bioelectric coupling

### 2. Energy Landscape Methods

#### Waddington Landscape Quantification

**Physics Basis:** Statistical mechanics applied to cell state transitions, treating development as navigation through an energy landscape.

**Expression:**

$$
\frac{dX}{dt} = -\nabla U(X) + \xi(t)
$$

where $U(X)$ is the quasi-potential and $\xi(t)$ represents noise.

**Wave Velocity Calculation:** $v = \mu\nabla U$ where $\mu$ is the mobility coefficient

**Energy Landscape:** Quasi-potential $U = -\ln(P_{\text{steady state}})$, derived from steady-state probability distributions

**Quantitative Outputs:** Transition rates $k = \frac{\omega}{2\pi}\exp\left(-\frac{\Delta G}{kT}\right)$

**Bioelectric Integration:** $V_{\text{mem}}$ serves as a key control parameter that shapes the landscape topology, enabling bioelectric control of cell fate decisions.

### 3. Information Processing Approaches

#### Bioelectric Code Decoding

**Physics Basis:** Information theory applied to bioelectric patterns, treating voltage distributions as encoded morphological information.

**Mathematical Framework:** Boolean networks, information entropy measures, pattern recognition algorithms

**Wave Velocity Calculation:** $v = \sqrt{\frac{D_{\text{eff}}}{\tau_{\text{mem}}}}$ where $D_{\text{eff}}$ is effective diffusion and $\tau_{\text{mem}}$ is membrane time constant

**Energy Landscape:** Discrete state transitions based on voltage thresholds, creating digital-like processing capabilities

**Quantitative Outputs:** Information content $I = -\sum p_i \log(p_i)$ bits

**Bioelectric Integration:** Central focus of $V_{\text{mem}}$ patterns which seem to directly encode morphological outcomes through threshold-based cellular responses.

### 4. Computational Modeling Platforms

#### BETSE (BioElectric Tissue Simulation Engine)

**Physics Basis:** Electrodiffusion theory, Nernst-Planck equations for ion transport in biological media

**Expression used:** Finite volume method solving coupled partial differential equations:

$$
\frac{\partial c}{\partial t} = \nabla \cdot (D\nabla c + \mu cE\nabla\phi)
$$

**Wave Velocity Calculation:** Numerical solution of full electrodiffusion equations

**Energy Landscape:** Electrochemical potential landscapes $U = \mu c + zF\phi$

**Quantitative Outputs:** $V_{\text{mem}}$ maps, ion flux vectors, current density distributions

**Bioelectric Integration:** Full coupling of bioelectric and biochemical dynamics, predicting tissue-scale bioelectric patterns

### 5. Experimental Quantification Methods

#### Voltage-Sensitive Dye Fluorescence Lifetime Imaging (VSD-FLIM)

**Physics Basis:** Photoinduced electron transfer (PeT) mechanisms where membrane potential modulates fluorescence lifetime

**Mathematical Framework:** Exponential decay kinetics, Stark effect relationships

**Wave Velocity Calculation:** From spatiotemporal lifetime maps: $v = \frac{\Delta x}{\Delta t}$

**Energy Landscape:** Voltage-dependent fluorescence energy states

**Quantitative Outputs:** Absolute $V_{\text{mem}}$ values (±5mV accuracy), bioelectric wave velocities (μm/s resolution)

**Bioelectric Integration:** Direct, quantitative measurement of membrane potential with cellular resolution

### 6. Active Control Systems

#### Optogenetic Bioelectric Control

**Physics Basis:** Light-gated ion channel kinetics, providing precise spatiotemporal control of membrane potential

**Mathematical Framework:** Modified Hodgkin-Huxley equations with light-dependent terms:

$$
I_{\text{opto}} = g_{\max} \times m^p \times h^q \times (V - E_{\text{rev}}) \times \Phi(\lambda,t)
$$

**Wave Velocity Calculation:** $v \propto \sqrt{I \times D_{\text{channel}}}$ where $I$ is light intensity

**Energy Landscape:** Light-controlled energy barriers for ion transport

**Quantitative Outputs:** Controlled $V_{\text{mem}}$ changes $\Delta V = f(\text{light dose}, \text{duration})$

**Bioelectric Integration:** Enables precise manipulation of bioelectric patterns for morphogenetic control

### 7. Molecular-Scale Field Effects

#### Bioelectric Stark Effect

**Physics Basis:** Electric field-induced shifts in molecular vibrational frequencies and protein conformations

**Mathematical Framework:** Stark shift equations: $\Delta\nu = -\Delta\vec{\mu} \cdot \vec{E} \times f$

**Wave Velocity Calculation:** $v = \frac{\mu E}{\xi}$ where $\xi$ is friction coefficient

**Energy Landscape:** Field-dependent molecular energy states

**Quantitative Outputs:** Frequency shifts in cm⁻¹/(MV/cm), protein conformational changes

**Bioelectric Integration:** Local electric fields from $V_{\text{mem}}$ gradients directly affect molecular function and enzyme kinetics

### 8. Optimization Theory Applications

#### Morphogenetic Gradient Descent

**Physics Basis:** Steepest descent optimization in morphological parameter space

**Mathematical Framework:**

$$
\theta(t+1) = \theta(t) - \alpha\nabla J(\theta)
$$

where $J$ is a morphological cost function

**Wave Velocity Calculation:** $v = -\alpha\nabla J(\text{morphology})$

**Energy Landscape:** Cost function surfaces for morphological outcomes

**Quantitative Outputs:** Convergence rates, optimization trajectories

**Bioelectric Integration:** $V_{\text{mem}}$ patterns serve as optimization variables for achieving desired morphological outcomes

### 9. Active Matter Physics

#### Active Nematic Field Theory

Energy landsapes are a ubiqutous phenomena in Natue. It is preliminary found of interest that metasucrface engineering and liquid crystal experiemnt may extended to active biological systems, and agential matter.

Nematic order parameter $Q$ and velocity field $v$ coupled through active stress has calculation method

**Wave Velocity Calculation:** $v = \sqrt{\frac{\zeta}{\eta}}$ where $\zeta$ is activity parameter and $\eta$ is viscosity

One may calculate orientational / variational free energy with elastic and active contributions

**Expectation:** Nematic defect velocities, topological charge densities which can be layered for an experimental biological conbinatory event of bioelectric-gated operations in such bio-electric fields.

### 10. Machine Learning Approaches

Section in development. I need more time.

(needs citations and more methods, and a proper analysis of relevance and correlation of statistical methods with information geometry which I find of utmost importance)

## Open Questions and Actionable Methods

#### Fundamental Questions

**Decoding the Bioelectric Code:** Which $V_{\text{mem}}$ spatial basis functions and thresholds are read by downstream transcriptional machinery, and at what integration timescales—testable via spatially patterned optogenetic $V_{\text{mem}}$ inputs and causal integration analytics.[@LevinMartyniuk2017; @ManickaPaiLevin2023]

Aditionally:

- Bridging molecular-scale Stark effects to tissue-scale pattern formation. Connecting Stark-effect molecular changes to tissue-scale morphogenesis. Direct experimental measurement of morphogenetic energy landscapes.
- Current tools like BETSE are limited to 2D; 3D tissue architectures require new approaches. It would be nice to have a graphics engine and physics based software for the purpose. Inductiva could help (Scientifc Modeeling Project based in Oporto - Portugal)
- Mapping bioelectric patterns evolve over developmental timescales
- Why and how can voltage patterns can yield different outcomes depending on cellular context

**Noise and Robustness**: What is noise's role in developmental outcomes?

**Bio-Combinatronicts - Coupling Rules:** How do voltage, calcium/ERK waves, and nematic defects co-regulate stress, proliferation, and differentiation in vivo, and which coupling terms dominate in specific tissues and stages.[@Balasubramaniam2022; @GuyomarDeSimone2025]

**Control of Regeneration Endpoints:** What stops wave generation at correct sizes, and can controllers be designed to halt or reshape waves to achieve target morphologies in planaria/axolotl/Xenopus systems.[@GuyomarDeSimone2025; @Tung2024]

### Synthesis of relationships (preliminary)

### Wave Velocity Relationships

Different methodological approaches yield characteristic velocity scales:

- **Bioelectric waves:** 2-40 μm/s (from our velocity database)
- **Turing patterns:** $\frac{\lambda}{\tau}$ where $\lambda \sim 100$ μm, $\tau \sim$ hours → $\sim 10^{-2}$ μm/s
- **Phase waves:** $v \propto \frac{1}{\nabla\phi}$, typically 10-100 μm/s
- **Active nematic flows:** $\sqrt{\frac{\zeta}{\eta}} \sim 1-10$ μm/s for typical biological parameters

### Energy Scale Comparisons

- **Thermal energy:** $kT \sim 4 \times 10^{-21}$ J at 300K
- **Bioelectric energy:** $eV_{\text{mem}} \sim 10^{-20}$ J for $V_{\text{mem}} \sim 60$ mV
- **Stark shift energy:** $\mu E \sim 10^{-21}$ J for $\mu \sim 1$ D, $E \sim 10^6$ V/cm
- **Elastic deformation energy:** $\sim 10^{-18}$ J for cellular-scale deformations

### Information Content Analysis

The bioelectric code operates at information densities of:

- **Single cell:** ~1-10 bits per cell (based on voltage threshold divisions)
- **Tissue patch:** $10^2-10^3$ bits per mm² (from spatial voltage patterns)
- **Temporal dynamics:** Additional factor of 10-100 from time-varying patterns

## Future Direction for a Physics Extensions to Current Program

#### Energy Landscape Perspectives

**Nonequilibrium Energetics and Active Matter:** Bioelectric wave maintenance and nematic flows consume metabolic energy; active stress coefficients and energy injection rates can be inferred from defect motility statistics and flow spectra to constrain models.[@Zhan2025; @Balasubramaniam2022]

**Variational and Inverse Modeling:** Gradient-based or Bayesian inference on RD and active-nematic PDEs can fit parameters to measured wave velocities, dispersion curves, and defect kinetics, enabling predictive control policies for regeneration.[@FHN2024; @Herron2012]

**From Landscape Metaphors to Mechanisms:** Replace Waddington metaphors with quantitative potential-like functionals for excitable states and director fields, relating minima and saddles to stable morphogenetic programs and transition pathways under perturbations.[@DiTalia2022; @GuyomarDeSimone2025]

## Future Work Aim: Integrated Experimental and Computational Approach

#### Data Acquisition and Invariance Fitting (physics based)

$V_{\text{mem}}$ (VSD/GEVI) and biosensor movies (Ca²⁺/ERK), with calibration and simultaneous mechanics imaging for nematic director extraction and stress inference.[@Miller2016; @Herron2012]. Aditionally, after the manual collection for existing studies of wave velocities and catalog, experimenting with wave invariant and physics based approaches for numerical simulations in order to contribute to the open quations.

#### Kinematic Extraction & Ghosts

It is true one can use kymographs, optical flow, and PIV to compute velocity, curvature, and anisotropy fields, plus defect tracking from director maps in epithelia.[@Afrashteh2017; @Meng2022]. Yet, the reaction–diffusion/excitable media models already allow for plenty of numerical experimentation. For example wave speeds and dispersion, and active nematic PDEs to defect dynamics and flow–growth couplings, with cross-validation across perturbations.[@Barkley2008; @Balasubramaniam2022]. Aditionally, measusing the Ghost's of equilibrium and their role in communociation protocols and developental outcomes is of high interest.

#### Communication Protocols

Fate maps, closing the loop between code and phenotype.[@Silic2023; @ManickaPaiLevin2023]

## Conclusions

Based on the nematics–waves–regeneration framework, which appears both relevant and feasible according to the literature review, a physics-informed approach to velocity extraction and active-matter modeling of tissue organization shows significant promise in understanding the invariant-varience relationship that guides morphogentic outcomes. The kinematic extraction methods for mechanochemical/active-nematic and excitable-media systems, combined with information-integration modeling, provide a comprehensive framework that can quantitatively connect energy-consuming bioelectric and biochemical waves to regenerative outcomes and morphogenetic endpoints in vivo.[@ManickaPaiLevin2023; @Balasubramaniam2022; @GuyomarDeSimone2025; @LevinMartyniuk2017]

---

## References

`<a id="afrashteh2017"></a>`**Afrashteh et al. 2017**
Afrashteh, Navvab, et al. "Optical-flow analysis toolbox for characterization of spatiotemporal dynamics in mesoscale neural activity." *NeuroImage* 153 (2017): 58-74.

<a id="appukuttan2021"></a>**Appukuttan et al. 2021**  
Appukuttan, Shailesh, et al. "The KiloNeuro simulation environment: a scalable and reproducible solution for large-scale neural network modeling." *Frontiers in Neuroinformatics* 15 (2021): 639378.`<a id="arcuino2002"></a>`**Arcuino et al. 2002**
Arcuino, Gabriele, et al. "Intercellular calcium signaling mediated by point-source burst release of ATP." *Proceedings of the National Academy of Sciences* 99, no. 15 (2002): 9840-9845.

`<a id="balasubramaniam2022"></a>`**Balasubramaniam et al. 2022**
Balasubramaniam, Lakshmi, et al. "Investigating the nature of active forces in tissues reveals how contractile cells can form extensile monolayers." *Nature Materials* 21, no. 10 (2022): 1161-1169.

`<a id="barkley2008"></a>`**Barkley 2008**
Barkley, Dwight. "Barkley model." *Scholarpedia* 3, no. 11 (2008): 1877.

`<a id="bradley2010"></a>`**Bradley et al. 2010**
Bradley, Sarah A., et al. "Nitric oxide in development: perspectives and problems." *Nitric Oxide* 22, no. 1 (2010): 1-5.

Busa, Walter B., and Richard Nuccitelli. "Metabolic regulation via intracellular pH." *American Journal of Physiology-Regulatory, Integrative and Comparative Physiology* 246, no. 4 (1985): R409-R438.

<a id="ceriani2016"></a>**Ceriani et al. 2016**  
Ceriani, Federico, et al. "ATP-induced calcium waves in cochlear supporting cells: cellular mechanisms and developmental changes." *The Journal of Physiology* 594, no. 24 (2016): 7313-7333.

<a id="chevalier2018"></a>**Chevalier 2018**  
Chevalier, Nicolas R. "Calcium waves coordinate heart morphogenesis in the embryonic chick." *Development* 145, no. 7 (2018): dev159210.

<a id="dalmas2010"></a>**Dalmas et al. 2010**  
Dalmas, Olivier, et al. "The Mg2+ transporter CorA from Thermotoga maritima: crystallographic insights into polyamine and Mg2+ binding." *Journal of Biological Chemistry* 285, no. 20 (2010): 15294-15303.

DiTalia, Stefano, and Frederick R. Cross. "Waves in embryonic development." *Annual Review of Biophysics* 51 (2022): 327-353.

Duchen, Michael R. "Mitochondria and calcium: from cell signalling to cell death." *The Journal of Physiology* 529, no. 1 (2000): 57-68.

FHN. "FitzHugh-Nagumo model." *Scholarpedia* (2024).

`<a id="fontanilla1998"></a>`**Fontanilla & Nuccitelli 1998**
Fontanilla, Robert A., and Richard Nuccitelli. "Characterization of the sperm-induced calcium wave in Xenopus eggs using confocal microscopy." *Biophysical Journal* 75, no. 4 (1998): 2079-2087.

`<a id="ford2023"></a>`**Ford et al. 2023**
Ford, Robert M., et al. "Spiral wave dynamics in Dictyostelium discoideum cAMP signaling." *Physical Review E* 107, no. 1 (2023): 014402.

<a id="funk2023"></a>**Funk & Scholkmann 2023**  
Funk, Richard H. W., and Felix Scholkmann. "The significance of bioelectricity on all levels of organization of an organism. Part 1: From the subcellular level to cells." *Progress in Biophysics and Molecular Biology* 177 (2023): 185-201.

`<a id="guyomar2025"></a>`**Guyomar & De Simone 2025**
Guyomar, Celine, and Silvia De Simone. "Theoretical framework for morphogen gradients and active matter." *Nature Physics* 21 (2025): 123-134.

<a id="hashimura2019"></a>**Hashimura et al. 2019**  
Hashimura, Hidekazu, et al. "cAMP wave propagation in migrating Dictyostelium cells." *Proceedings of the National Academy of Sciences* 116, no. 10 (2019): 4650-4659.

`<a id="hecht2009"></a>`**Hecht et al. 2009**
Hecht, Ingmar, et al. "Determining the scale of the Bicoid morphogen gradient." *Proceedings of the National Academy of Sciences* 106, no. 5 (2009): 1301-1306.

<a id="herron2012"></a>**Herron et al. 2012**  
Herron, Todd J., et al. "Optical imaging of voltage and calcium in cardiac cells & tissues." *Circulation Research* 110, no. 4 (2012): 609-623.Howard, Jonathon. "Morphogen gradients in development." *Current Biology* 21, no. 23 (2011): R918-R920.

<a id="jaffe2010"></a>**Jaffe 2010**  
Jaffe, Lionel F. "Fast calcium waves." *Cell Calcium* 48, no. 2-3 (2010): 102-113.

Kuhn, Bernd, et al. "High sensitivity of Stark-shift voltage-sensing dyes by one- or two-photon excitation near the red spectral edge." *Biophysical Journal* 87, no. 1 (2019): 631-639.

Lee, Kang J., et al. "Calcium transients in the early chick embryo." *Developmental Biology* 501 (2024): 45-58.

`<a id="levin2017"></a>`**Levin & Pietak 2017**
Levin, Michael, and Alexis M. Pietak. "The bioelectric code: reprogramming cancer and aging from the interface of mechanical and informational biology." *Frontiers in Cell and Developmental Biology* 5 (2017): 21.

<a id="li2024"></a>**Li & Sun 2024**  
Li, Wei, and Jianping Sun. "pH gradients in cell migration and chemotaxis." *Cell* 187, no. 15 (2024): 3925-3940.

`<a id="machaty2024"></a>`**Machaty 2024**
Machaty, Zoltan. "Signal transduction during fertilization in mammals." *Theriogenology* 150 (2024): 526-533.

`<a id="manicka2023"></a>`**Manicka et al. 2023**
Manicka, Santosh, et al. "The cognitive lens: a primer on conceptual tools for analysing information processing in developmental and regenerative morphogenesis." *Philosophical Transactions of the Royal Society B* 374, no. 1774 (2023): 20180369.

<a id="marcotti2003"></a>**Marcotti et al. 2003**  
Marcotti, Walter, et al. "Developmental changes in the expression of potassium currents of embryonic, neonatal and mature mouse inner hair cells." *The Journal of Physiology* 548, no. 2 (2003): 383-400.

<a id="mathews2018"></a>**Mathews et al. 2018**  
Mathews, Paul J., et al. "Voltage imaging with genetically encoded indicators." *Current Opinion in Chemical Biology* 45 (2018): 114-123.

<a id="meng2022"></a>**Meng et al. 2022**  
Meng, Fanqing, et al. "Measuring velocities in biological systems using particle image velocimetry." *Methods in Cell Biology* 170 (2022): 45-78.

<a id="miller2016"></a>**Miller 2016**  
Miller, Eric W. "Small molecule fluorescent voltage indicators for studying membrane potential." *Current Opinion in Chemical Biology* 33 (2016): 74-80.

<a id="nuccitelli1993"></a>**Nuccitelli et al. 1993**  
Nuccitelli, Richard, et al. "The sperm entry point defines the orientation of the calcium-induced contraction wave that directs the first cleavage plane and establishes the embryonic axis." *Development* 118, no. 3 (1993): 981-990.

<a id="roome2020"></a>**Roome & Kuhn 2020**  
Roome, Christopher J., and Bernd Kuhn. "Simultaneous dendritic voltage and calcium imaging and somatic recording from Purkinje neurons in awake mice." *Nature Communications* 11, no. 1 (2020): 3388.

Silic, Masa R., and Michael Levin. "Bioelectric networks and the birth of mind." *BioEssays* 45, no. 8 (2023): 2300015.

<a id="soll2004"></a>**Soll et al. 2004**  
Soll, David R., et al. "Computer-assisted three-dimensional reconstruction and motion analysis of living, crawling cells." *Computerized Medical Imaging and Graphics* 28, no. 1-2 (2004): 13-21.

Steele, Patricia A. "Chloride action potentials in embryonic chick skeletal muscle." *The Journal of Physiology* 432 (1990): 235-254.

Sugita, Naoya, et al. "Nitric oxide measurement in biological systems by ultrasound." *Ultrasound in Medicine & Biology* 34, no. 8 (2008): 1324-1330.

`<a id="titov2023"></a>`**Titov et al. 2023**
Titov, Anton, et al. "Acoustic properties of embryonic tissues during zebrafish development." *Developmental Biology* 498 (2023): 45-56.

`<a id="tung2024"></a>`**Tung et al. 2024**
Tung, Cody K., et al. "Bioelectric signaling regulates size in zebrafish fins." *PLoS Genetics* 20, no. 4 (2024): e1011237.

Vafa, Farzan, and L. Mahadevan. "Active nematic flows over curved surfaces." *Physical Review Fluids* 7, no. 9 (2022): 094302.

Wartlick, Ortrud, et al. "Dynamics of Dpp signaling and proliferation control." *Science* 331, no. 6021 (2009): 1154-1159.

Watanabe, Miho, and Atsuo Fukuda. "Development and regulation of chloride homeostasis in the central nervous system." *Frontiers in Cellular Neuroscience* 9 (2015): 371.

Zhan, Meng, et al. "Metabolic waves in glycolysis." *Physical Review E* 111, no. 1 (2025): 012403.

###### Languages used (extended version)

![mark](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

![py](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)

[![GitHub Stars](https://img.shields.io/github/stars/IgorAntun/node-chat.svg)](https://github.com/m4r11/Template-Project)
[![GitHub Issues](https://img.shields.io/github/issues/IgorAntun/node-chat.svg)](https://github.com/m4r11/Template-Project/issues)
[![Current Version](https://img.shields.io/badge/version-1.0.7-green.svg)](https://github.com/m4r11/Template-Project)
[![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](https://github.com/m4r11/Template-Project)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://github.com/m4r11/Template-Project?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
![madebash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)
