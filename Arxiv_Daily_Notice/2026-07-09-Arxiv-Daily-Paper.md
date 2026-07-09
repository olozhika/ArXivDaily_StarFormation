# Showing new listings for Thursday, 9 July 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['star formation', 'star-forming', 'molecular cloud', 'interstellar medium', 'cloud', 'clump', 'core', 'filament', 'atomic gas', 'N-PDF']


Excluded: ['galaxies', 'galaxy cluster', ' AGN ', 'standard candle', 'X-ray binar', 'solar corona']


### Today: 16papers 
#### Fast Graph-based Higher-Order Clustering Statistics on the GPU
 - **Authors:** Cristiano G. Sabiu
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.06604

 - **Pdf link:** https://arxiv.org/pdf/2607.06604

 - **Abstract**
 We present a significant update to GRAMSCI (GRAph Made Statistics for Cosmological Information; Sabiu this http URL 2019), an algorithm for the fast computation of the general $N$-point spatial correlation function of any discrete point set embedded in $\mathbb{R}^n$. Utilizing the concepts of kd-trees and graph databases, we count all possible $N$-tuples in binned configurations within a given length scale. In this {\em Version 2 update} we describe several additions to the original code. We replace the binary-search inner loop, which cost $O(m\log m)$ per hub--spoke pair, where $m$ is the mean neighbor count, with a merge-walk algorithm that reduces the inner loop to $O(m)$. We implement a parity-decomposed 4pCF that separates the signal into even and odd channels, enabling direct tests of parity violation in the galaxy distribution. We estimate the disconnected 4pCF internally on the same graph to return the connected 4pCF. We provide a Python interface so the Fortran engine can be called directly from NumPy arrays. Finally, and principally, we present a GPU port of the full query engine (OpenACC): the 3pCF, 4pCF, and parity-decomposed 4pCF kernels run on a single consumer GPU with measured speedups of $2.6\times$ (3pCF) to $9\times$ (4pCF) over a 64-thread CPU node, and an out-of-core tiling scheme allows graphs far exceeding device memory. We measure a $9\times10^9$-edge BAO-scale 3pCF on a 24\,GB card with ${\sim}20\%$ overhead. We validate the code against its CPU reference, against analytic injection tests, and demonstrate BAO-scale applications on the DESI DR1 LRG sample compared against the EZmock ensemble.
#### Effects of Rotation on 3D Core-Collapse Supernova Models for Low-Mass Progenitors
 - **Authors:** Adam Burrows, Tianshu Wang, David Vartanyan
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.06664

 - **Pdf link:** https://arxiv.org/pdf/2607.06664

 - **Abstract**
 We explore the dependence upon rotation rate alone of various supernova observables simulated to their saturation for the explosion of a 9-$M_{\odot}$ progenitor. We find that the explosion energy is non-monotonic with, and weakly dependent upon, spin across a broad range of initial spins. The asymmetries of the blast depend weakly on spin, with faster spins leading to only slightly greater asymmetries. There is little significant pole-equator neutrino heating asymmetry during explosion, even for rapid rotation, and only for the fastest rotator does the neutrino heating rate diminish noticeably. Hence, the effects of rotation alone on all salient aspects of supernova dynamics are not large. We find that the recoil kick and spin are clearly aligned only for the most rapidly rotating model. Interestingly, for the fastest rotator, we witness a $T/|W|$ corotation instabilities near a value of 0.05 and spiral arm modes emerge. We find that the nucleosynthetic yields depend little upon the rotation rate and determine that the ratio of initial to final core spin period is near $\sim$4000, implying, given the modest inferred radio pulsar periods at birth, that the initial spin periods of most supernova cores are likely quite long. However, we focus on only one progenitor and do not include magnetic fields. Nevertheless, at least for low-mass progenitors which explode early, we find muted consequences of rotation in most major particulars across a wide range of initial spins.
#### Mitigating Charge Migration in JWST NIRISS Reveals That KELT-7 b is a Metal-enriched Ultra-hot Jupiter Orbiting a Young Metal-rich Star
 - **Authors:** Stephen P. Schmidt, Erin M. May, Joshua D. Lothringer, Patrick McCreery, Mei Ting Mak, Myles Pope, Harry Baskett, Sagnick Mukherjee, David K. Sing, Katherine A. Bennett, Arika Egan, Guangwei Fu, Daniel P. Thorngren, Duncan A. Christie, Carlos Gascón, Le-Chris Wang, Lakeisha M. Ramos Rosado, Nathan J. Mayne, Natalie H. Allen, Zafar Rustamkulov, Mercedes López-Morales, Kevin C. Schlaufman
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.06708

 - **Pdf link:** https://arxiv.org/pdf/2607.06708

 - **Abstract**
 We present the first panchromatic JWST transmission spectrum of an ultra-hot Jupiter, combining NIRISS and NIRSpec observations to constrain KELT-7\,b's atmospheric properties. We show evidence for charge migration in our NIRISS SOSS observation between 1--1.5~$\mu$m, a wavelength range crucial to test for enhanced H$^-$ previously inferred from HST WFC3/IR G141 observations. We mitigate charge migration by fitting the ramp after extracting 1D stellar spectra at the group level. This ``late-ramp-fit'' method accurately calculates KELT-7\,b's transmission spectrum between 1--1.5~$\mu$m at higher signal-to-noise. Using the transit-derived stellar mean density during stellar property inference reveals that KELT-7 is a $640\pm100$ Myr-old, $[\text{Fe}/\text{H}]=0.46\pm0.02$ star. Combined with NIRSpec and re-reduced WFC3/UVIS G280 data, our free retrieval analysis shows strong evidence for H$_2$O, CO$_2$, and TiO among high-temperature species, but not H$^-$ or clouds. Unaccounted-for systematics may therefore bias longer-wavelength WFC3/IR G141 transit depths shallower. Our free retrieval, two equilibrium retrievals, and self-consistent grid fit all prefer a high metallicity but find discrepant C/O ratios. Agglomerated together, we constrain a super-stellar $\text{M/H}=92^{+24}_{-23}\times$~Solar and C/O~$\leq0.9$, suggesting enhanced metal accretion in the later stages of KELT-7\,b's formation. Our GCMs explain the observed lack of limb asymmetry with superrotating jet-driven efficient horizontal mixing. The stark contrast between our panchromatic analysis and prior analyses on subsets of these data demonstrates the value of broad wavelength coverage for the comprehensive study of exoplanet atmospheres.
#### The nature of Cloud-9: a compact core embedded in a diffuse envelope
 - **Authors:** Ruilei Zhou, Ming Zhu, Chuan-Peng Zhang, Jinlong Xu
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.06712

 - **Pdf link:** https://arxiv.org/pdf/2607.06712

 - **Abstract**
 We present new HI observations of Cloud-9 with the Five-hundred-meter Aperture Spherical Telescope (FAST), measuringvtotal flux of 0.35 +- 0.03 Jy km/s. Combined with Very Large Array (VLA) data, the HI shows a two-component structure: a compact, kinematically quiescent core and an extended envelope. The outer component exhibits a coherent velocity gradientvof ~25 km/s across ~7 kpc. The position-velocity structure does not support rotation; instead, the gradient is consistent with ordered large-scale motion, induced by environmental interaction with M94. The coexistence of a compact, kinematically quiescent core and an extended structured envelope is difficult to reconcile with a unbound or purely gaseous system. While the extended component is more naturally interpreted as environmentally shaped gas, the compact core suggests gravitational confinement beyond that provided by the observed baryonic content, without requiring strict long-term dynamical equilibrium. Deep optical limits further rule out a significant stellar component. Taken together, our results indicate that Cloud-9 is most naturally interpreted as a dark matter-dominated system undergoing environmental interaction. The observed morphology and kinematics are consistent with a stripped RELHIC scenario, in which a compact gas-rich core is embedded within an extended envelope shaped by ram-pressure interaction with the circumgalactic medium of M94.
#### A Momentum-Regulated Model For Star Formation Efficiency in Giant Molecular Clouds
 - **Authors:** Erik Bertram
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.06727

 - **Pdf link:** https://arxiv.org/pdf/2607.06727

 - **Abstract**
 We present a minimal analytic framework to investigate the star formation efficiency per free-fall time, $\epsilon_{\rm ff}$, in giant molecular clouds (GMCs), focusing on the origin of the observed clustering around $\epsilon_{\rm ff} \sim 0.01$. We model the time evolution of the turbulent velocity dispersion through a momentum balance between stellar feedback and turbulent dissipation, and show that this generically leads to a stable low-efficiency equilibrium with only weak dependence on global cloud properties. We extend the framework by including a phenomenological contribution from gravity-driven turbulence and find that both feedback- and gravity-driven motions converge to similar equilibrium states under typical GMC conditions. The efficiency can be expressed as the ratio between a gravitational velocity scale and an effective feedback velocity scale, providing a physically transparent interpretation of self-regulated star formation. The model provides a simple, physically motivated interpretation of observed gas-star formation scaling relations, including a Schmidt-like scaling at cloud scales and a Kennicutt-like scaling when averaged over cloud populations. Comparison with observed GMC properties shows agreement within a factor of a few and highlights the weak sensitivity of $\epsilon_{\rm ff}$ to cloud parameters. Despite its simplicity, the framework captures the leading-order interplay between turbulence, gravity, and feedback, and provides a physically transparent explanation for the origin and robustness of low star formation efficiencies in GMCs.
#### Machine Learning Closure Audits for LSST Photometric Supernova Cosmology
 - **Authors:** Ayan Mitra
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.06734

 - **Pdf link:** https://arxiv.org/pdf/2607.06734

 - **Abstract**
 Modern and next generation supernova cosmology analyses rely on end to end simulations to train photometric classifiers, characterise selection effects, validate light curve models, and calibrate distance bias corrections. Standard closure tests based on global Hubble diagram summaries can miss multivariate structure that remains in post correction residuals. We introduce a supervised machine learning closure audit that tests whether measured observables can predict the bias corrected Hubble residuals $\Delta\mu$. We apply the audit to LSST Type Ia supernova simulations from two independent analyses: the M23 mock data sets of Mitra et al. (2023), with spectroscopic redshift and photometric redshift samples, and the predominantly photometric LSST like M25 simulation of Mitra et al. (2025). Standard one dimensional Redshift binned diagnostics explain <1% of the residual variance ($R^2 < 0.01$), suggesting apparent closure. In contrast, out of fold LightGBM models recover up to 98.2% of the variance in the simulated residuals ($R^2 = 0.982$), revealing structured residual predictability. Applying the same audit directly to the real Dark Energy Survey 5 Year (DES 5YR) spectroscopic sample yields a held out $R^2 = 0.725$. SHAP feature attribution rankings are highly consistent between independently trained M25 and DES models (Spearman $\rho = 0.802$), with apparent magnitudes, signal to noise ratios, and redshift dominating the shared predictive hierarchy. The resulting scorecard provides a diagnostic protocol for comparing mock ensembles and real observations, identifying residual non closure before cosmological parameters are unblinded.
#### The Generalization Gap in Machine Learning EoS Inference from Core-Collapse Supernova Gravitational Waves
 - **Authors:** Ayan Mitra
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Nuclear Theory (nucl-th)
 - **Arxiv link:** https://arxiv.org/abs/2607.06736

 - **Pdf link:** https://arxiv.org/pdf/2607.06736

 - **Abstract**
 Core-collapse supernova gravitational waves may carry information about the dense matter equation of state (EoS), which describes the relation between pressure, density, temperature, and composition. This work tests a crucial question for physical inference: can a machine learning model trained on a finite simulation catalogue predict EoS parameters for an EoS family that was absent during training? Under standard random cross-validation, a LightGBM regressor appears highly successful, yielding $R^2=(0.70,0.67,0.60)$ for the nuclear incompressibility, symmetry energy, and slope parameter $(K_0,J,L)$. However, under Leave-One-EoS-Out (LOEO) validation, where all waveforms from a single EoS are withheld, the model fails, yielding mean absolute errors of $(44.57,3.19,30.54)$ MeV and negative pooled $R^2$ scores, performing worse than a baseline mean predictor. This generalisation gap persists across linear models, random forests, neural networks, and gradient-boosted trees. Restricting inputs to physical features (bounce amplitude, bounce width, peak frequency) reduces template leakage, the memorisation of related templates shared across random splits, but does not restore reliable EoS extrapolation. In contrast, a progenitor mass case study shows that classification generalises to unseen rotation speeds, while continuous mass regression compresses predictions towards the catalogue interior. These results demonstrate that while machine learning successfully interpolates within current waveform catalogues, this does not imply robust physical inference for unseen EoS models. Future pipelines should adopt leave-family-out validation, wider simulation coverage, and physics-aware inference frameworks.
#### Unveiling the Nature of C/2023 A3 (Tsuchinshan-ATLAS): A Multi-Technique Observational Approach
 - **Authors:** Goldy Ahuja, Shashikiran Ganesh, Aravind Krishnakumar, Devendra K. Sahu, Thirupathi Sivarani, Vikrant K. Agnihotri
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2607.06769

 - **Pdf link:** https://arxiv.org/pdf/2607.06769

 - **Abstract**
 Comet C/2023 A3 (Tsuchinshan-ATLAS) is a non-periodic dynamically new Oort cloud comet that was discovered independently by Purple Mountain Observatory in China and Asteroid Terrestrial-impact Last Alert System (ATLAS) telescopes in South Africa. The comet passed perihelion at a distance of 0.39 AU on 27 September 2024. It was visible to the naked eye (the brightest since the comet C/1995 O1 (Hale-Bopp)) and was dubbed the great comet of 2024. In this work, we investigate the nature of this comet, which is moving in a hyperbolic orbit (e > 1), by analysing its composition using various observational techniques and tracing its orbital evolution through high-precision N-body simulations.
#### Unveiling the Milky Way with a Gaia DR3 census of OB-type stars within 2 kpc. I. Tracing local Galactic structure, massive star-forming regions and core-collapse supernova progenitors
 - **Authors:** Alexis L. Quintana, Kiril Maltsev, Eloisa Poggio, Emily L. Hunt, Nicholas J. Wright, Sara R. Berlanas, Laia Casamiquela, Abel de Burgos, Hanna Parul, Misha Haywood, Paola Di Matteo, Chervin Laporte, Juan Martínez García
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.07068

 - **Pdf link:** https://arxiv.org/pdf/2607.07068

 - **Abstract**
 O- and B-type stars are young and hot, thereby serving as vital tracers of the star formation and spiral arm structure of the Milky Way. At the dusk of the \textit{Gaia} DR3 era, a high-confidence and accurate catalogue appears timely. Here we have characterized a population of 105,971 OB-type stars (T$_{\rm eff} >$ 10,000 K; hereafter OB stars) within 2 kpc from the Sun, using an astro-photometric Bayesian inference tool. Our resulting map unveils a complex view of the young stellar populations across the thin disk, with prominent large-scale features such as the Cepheus Spur, the Giant Oval Cavity, and a segment of the Sagittarius-Carina spiral arm all visible. Their inhomogeneous spatial distribution implies that massive star formation has taken place clustered across a few highly concentrated regions. We find a correlation between the overdensities of OB stars and young open clusters ($<$20 Myr), although OB stars can be better detected in high-extinction regions. We identify over 4200 OB stars as core-collapse supernova (ccSN) or direct-collapse black hole (BH) progenitor candidates, and therefore targets of interest for spectroscopic follow-up. Furthermore, we find no OB-type star ccSN progenitor to explode within the next 1 Myr within 100 pc, at which such an event could be harmful to Earth's biosphere. Finally, we identify more BH progenitors to collapse within the next 1 Myr than ccSN to explode, despite the former's much scarcer number - which could be indicative of a recent massive star formation burst in the local Milky Way.
#### Microquasar Cygnus X-3 as the PeVatron powering the Cygnus Bubble
 - **Authors:** Zhaodong Shi, Guangwei Wang, Ruizhi Yang, Felix Aharonian
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2607.07100

 - **Pdf link:** https://arxiv.org/pdf/2607.07100

 - **Abstract**
 The recent discovery by the LHAASO collaboration of a variable ultra-high-energy (UHE; $E_\gamma \ge$ 100 TeV) $\gamma$-ray source associated with the microquasar Cygnus X-3, with a spectrum extending to several PeV, provides compelling evidence for a hadronic super-PeVatron operating within the binary system. Inside the binary, the accelerated protons lose only a small fraction of their energy; upon escaping into the interstellar medium, they propagate diffusively to form a vast gamma-ray ``halo" structure extended to hundreds of parsecs. We argue that this halo has already been detected and corresponds to the Cygnus Bubble, an extended UHE $\gamma$-ray source reported by the LHAASO collaboration -- which possesses an angular extension of $\approx 6^{\circ}$ and an energy spectrum reaching 1 PeV. While the Cygnus Bubble is generally attributed to the star-forming region Cygnus X (specifically the Cygnus OB2 association at 1.4 kpc), we demonstrate that an association with Cygnus X-3 is physically more natural at energies above 400 TeV. This is supported by the cosmic-ray radial distribution, derived from the $\gamma$-ray and gas distributions, which points to continuous injection from a point-like source. The energetic requirements of the central accelerator are reasonably affordable and feasible. This reassignment identifies the Cygnus Bubble as a member of the recently discovered population of microquasar UHE $\gamma$-ray halos.
#### Reconnection diagnostics for vortex tangles in Bose-condensed and superfluid dark matter halos
 - **Authors:** Kazım Yavuz Ekşi
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Quantum Gases (cond-mat.quant-gas); General Relativity and Quantum Cosmology (gr-qc)
 - **Arxiv link:** https://arxiv.org/abs/2607.07121

 - **Pdf link:** https://arxiv.org/pdf/2607.07121

 - **Abstract**
 Bose-Einstein-condensed (BEC) and superfluid dark-matter (SFDM) halos can contain coherent, wave-supported cores whose angular momentum is carried by quantized vortices. When vortices form a tangle, reconnections convert part of the vortex kinetic energy into dark phonons, density waves, Kelvin waves, and vortex loops, providing a microscopic channel by which SFDM vortex structure can affect halo-core evolution. We estimate the dynamical importance of this channel by combining the local Gross-Pitaevskii reconnection law with a halo-scale vortex-line density calibrated against Schrödinger-Poisson simulations. In the minimal model the released energy stays in the dark sector, and standard-model luminosity requires additional portal physics.
#### From 2D to 3D: Recovering Turbulent Density Dispersions from Noisy Data
 - **Authors:** Luz L. Jimenez Vela, Christoph Federrath, David C. Collins, Seth Davidovits
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM); Solar and Stellar Astrophysics (astro-ph.SR); Computational Physics (physics.comp-ph); Data Analysis, Statistics and Probability (physics.data-an)
 - **Arxiv link:** https://arxiv.org/abs/2607.07205

 - **Pdf link:** https://arxiv.org/pdf/2607.07205

 - **Abstract**
 Turbulence plays a central role in shaping the structure and dynamics of the interstellar medium (ISM), governing the star formation rate (SFR) and the initial mass function (IMF). A key consequence of turbulence is the generation of density fluctuations, which regulate the amount of dense gas available for star formation. Accurate measurements of the three-dimensional (3D) turbulent density dispersion are therefore essential for understanding molecular-cloud structure and star formation. However, observations typically provide only two-dimensional (2D) column densities and are often affected by measurement/detector noise. The Brunt method estimates the 3D density dispersion from 2D column-density maps, but it does not account for finite signal-to-noise ratio (SNR). Here, we extend the method to recover the 3D turbulent density dispersion from noise-contaminated observations. Using numerical simulations spanning a range of density perturbation amplitudes and noise types, we identify a characteristic noise wavenumber, k_noise, corresponding to the intersection of the signal and noise spectra. Restricting the Brunt reconstruction to wavenumbers below k_noise yields a denoised density-dispersion estimate that closely reproduces the noise-free result. We provide a practical prescription to determine k_noise directly from the measurement SNR and image resolution. Alternatively, if the noise spectrum is known, it can be subtracted directly from the observed spectrum, eliminating the need to estimate k_noise. The proposed correction recovers the noise-free density dispersion with errors of <~5% for SNR>=3 and <~15% for SNR>=1, enabling substantially more reliable estimates of turbulent density fluctuations from noisy column-density data.
#### Hubble Space Telescope survey of Magellanic Cloud star clusters. Binaries, mass functions, blue stragglers, and structural parameters
 - **Authors:** F. Muratore, M. V. Legnardi, A. P. Milone, G. Cordoni, A. Mastrobuono-Battisti, A. F. Marino, T. Ziliotto, E. Dondoglio, E. Bortolan, E. P. Lagioia
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.07266

 - **Pdf link:** https://arxiv.org/pdf/2607.07266

 - **Abstract**
 Binary stars are key tracers of the dynamical evolution of star clusters and provide important constraints on stellar populations and mass functions. The Magellanic Clouds host clusters spanning a wide range of ages and masses, offering an ideal laboratory to investigate these properties in regimes poorly sampled in the Milky Way. We aim to characterize the binary populations, mass functions, blue straggler content, and structural parameters of intermediate-age Magellanic Cloud clusters, and to explore their dependence on global cluster properties. We analyze HST photometry for 16 clusters obtained with ACS/WFC and WFC3/UVIS. Structural parameters are derived from stellar density profiles. Binary fractions are measured using the binary map technique, focusing on systems with mass ratios q > 0.7. We derive MFs accounting for unresolved binaries and identify candidate BS populations from color-magnitude diagrams. The fraction of binaries with q > 0.7 ranges from 5% in NGC 2121 up to 13% in NGC 2173, with a mass-ratio distribution that is consistent with being flat on average. By combining our results with literature data, we confirm a clear anti-correlation between the core binary fraction and cluster mass, while no significant dependence on cluster age is found. The clusters follow the established relation between age and core radius, although with substantial scatter at fixed age. Within the narrow age range explored here, clusters exhibiting steeper MFs are found to have smaller core radii. We find no evidence for a correlation between the fractions of binaries and BS fractions. These findings are consistent with a scenario in which dynamical evolution plays a primary role in the formation of binary populations. The connection between MF slope and structural parameters provides new constraints on cluster evolution and suggests a link between MF slope and structural evolution.
#### Divergent Evolution of Radial Metallicity Gradients in the Thin and Thick Disks of the Milky Way
 - **Authors:** Weixiang Sun, Gaohuan Long, Hui Li, Han Shen, Shu Wang, Xiaodian Chen, Biwei Jiang, Xiaowei Liu, Di Li
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.07394

 - **Pdf link:** https://arxiv.org/pdf/2607.07394

 - **Abstract**
 Using 200,388 red clump stars from LAMOST and APOGEE, we investigate the radial metallicity gradients of the Galactic disk as a function of vertical height and stellar age. The thin disk displays a pronounced negative radial metallicity gradient near the Galactic mid-plane that progressively flattens with increasing $|Z|$, following $\Delta \mathrm{[Fe/H]}/\Delta R$ = $-$0.0784 $+$ 0.0776 (1 $-$ exp ($-$ $|Z|$/1.4244)). The thin disk also exhibits a clear age dependence in radial metallicity gradients, evolving smoothly from a strong gradient regime for young stars to a weak gradient regime for old stars, following $\Delta \mathrm{[Fe/H]}/\Delta R$ = $-$0.0438 $+$ 0.0233 tanh (($\tau$ $-$ 11.2908)/4.2130). The thick disk shows weakly positive radial metallicity gradients that remain statistically invariant with respect to both vertical height and stellar age, following respectively, $\Delta \mathrm{[Fe/H]}/\Delta R$ = 0.0038 $+$ 0.0009 $|Z|$ and $\Delta \mathrm{[Fe/H]}/\Delta R$ = 0.0146 $-$ 0.0007 $\tau$. These results indicate that the thin disk retains radial metallicity gradients shaped by relatively ordered inside-out growth and long-term secular evolution processes. The thick disk exhibits spatially and temporally homogeneous radial metallicity gradients, supporting a picture in which it formed rapidly during an early phase when the disk was dynamically hot and efficiently mixed, potentially in chaotic mergers of gas-rich systems and/or the turbulent ISM.
#### Milky Way Atlas: A radial-velocity-resolved, three-dimensional map of H I within 1.25 kpc
 - **Authors:** Lewis McCallum, Laurin Söding, Mareike Berkner, Philipp Frank, Matteo Guardiani, Jakob Roth, Juan D. Soler, Robert Benjamin, Torsten Enßlin, Philipp Mertsch, Konstantinos Tassis, Vasiliki Pavlidou
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.07451

 - **Pdf link:** https://arxiv.org/pdf/2607.07451

 - **Abstract**
 We present a velocity-resolved three-dimensional map of local atomic hydrogen (HI) within 1.25 kpc of the Sun, tackling the challenge of converting emission from position-position-velocity space into true 3D structure. Our method combines the HI4PI full-sky survey with the Edenhofer et al. (2024) 3D dust map in the framework of Information Field Theory, enabling a joint reconstruction of the local HI density, radial velocity field, and effective line width while also separating emission arising inside the mapped local volume from more distant Galactic HI. The inference is driven by morphological matching between dust and HI structures together with kinematic coherence in 3D space. Synthetic data tests show that the method recovers the local density and velocity structure, even in the presence of substantial contamination from distant emission. The resulting map reveals a smoother, more diffuse local HI distribution than the dust, a declining HI-to-dust ratio toward high dust column densities consistent with the atomic-to-molecular transition, and a velocity field that captures both large-scale Galactic rotation and local non-circular velocities. Independent comparisons with maser and young stellar cluster velocities agree with the recovered kinematics. This HI map provides a new three-dimensional, kinematically resolved view of the nearby atomic interstellar medium and a foundation for localising other velocity-resolved Galactic emission in physical space.
#### Chemical diversity of dense cores in Orion B: The role of the environment
 - **Authors:** Helena J. Mazurek, Maryvonne Gerin, Pierre Gratier, Jérôme Pety, Emeric Bron, Evelyne Roueff, Antoine Roueff, Ivana Bešlić, Lucas Einig, Jan H. Orkisz, Pierre Palud, Miriam G. Santa-Maria, Léontine Ségal, Antoine Zakardjian, Sébastien Bardeau, Pierre Chainais, Simon Coudé, Karine Demyk, Victor de Souza Magalhaes, Javier R. Goicoechea, Annie Hughes, David Languignon, François Levrier, Franck Le Petit, Dariusz C. Lis, Harvey S. Liszt, Nicolas Peretto, Albrecht Sievers, Pierre-Antoine Thouvenin
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.07489

 - **Pdf link:** https://arxiv.org/pdf/2607.07489

 - **Abstract**
 Prestellar cores are the sites of the earliest stages of star formation. Dust continuum observations are often used to identify and characterize their properties yet only a small fraction of them was observed and studied in terms of their composition and dynamical status. We explore the chemical diversity of prestellar cores and protostellar cores residing in the Orion B giant molecular cloud selected on their dust continuum emission to provide an unbiased view of their line emission properties and how they vary as function of the core parameters and environment. We make use of the large scale maps of Orion B in 25 molecular lines from which we extract information for a sample of 1001 cores selected using positions extracted from \textit{Herschel} dust continuum observations. The main properties of the core sample are derived using the Principal Component Analysis and additional maps of physical parameters: column density $N_{\rm{H_2}}$, far-ultraviolet (FUV) radiation field $G_0$ and mean volume gas density $n$. Additional high spectral resolution observations of $\rm C^{18}O(1-0)$ serve to evaluate the dynamical status of cores. The average line width of the cores is larger than what is typically expected for prestellar cores of closer star forming regions, which suggests that cores in Orion B are subjected to stronger turbulence affecting their stability. The first factor of the PCA analysis explaining the variation of the detected line intensities is the core column density of molecular gas. The second factor explains how the core chemical composition is strictly linked to their environment, which can be traced by the ratio of the external FUV radiation field over the core volume density, $G_0/n$. The third factor explaining the core chemical diversity is the mean density along the core line of sight, which is also associated with freeze-out and fractionation signatures.


by olozhika (Xing Yuchen). 


2026-07-09
