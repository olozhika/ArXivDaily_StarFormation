# Showing new listings for Friday, 10 July 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['star formation', 'star-forming', 'molecular cloud', 'interstellar medium', 'cloud', 'clump', 'core', 'filament', 'atomic gas', 'N-PDF']


Excluded: ['galaxies', 'galaxy cluster', ' AGN ', 'standard candle', 'X-ray binar', 'solar corona']


### Today: 14papers 
#### Boötes III is a Tidally Disrupting Ultra-Faint Dwarf Galaxy on an Eccentric Polar Orbit
 - **Authors:** Ting S. Li, Denis Erkal, Andrew B. Pace, Jiaxun Yang, Sergey E. Koposov, Jo Bovy, Nathan R. Sandford, Andrew P. Li, Gustavo E. Medina, Lara R. Cullinane, Gary S. Da Costa, Alexander P. Ji, Kyler Kuehn, Geraint F. Lewis, Guilherme Limberg, Sarah L. Martell, Aldo Mura-Guzmán, Nora Shipp, Yong Yang, Daniel B. Zucker, Kaia R. Atzberger, Joss Bland-Hawthorn, John D. Dixon (the S5 Collaboration)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.07803

 - **Pdf link:** https://arxiv.org/pdf/2607.07803

 - **Abstract**
 We present updated systemic properties of the ultra-faint dwarf galaxy Boötes III from the Southern Stellar Stream Spectroscopic Survey (S$^5$). We identify 21 high-probability members and measure a velocity dispersion of $\sigma_{v} = 1.69^{+1.03}_{-0.85}$ km s$^{-1}$, about six times smaller than the previously reported $10.7 \pm 3.5$ km s$^{-1}$, and a mean metallicity of [Fe/H] $= -2.34 \pm 0.11$. The revised dispersion brings Boötes III in line with other tidally disrupting dwarfs such as Antlia II and Crater II. Orbit integrations in a Milky Way (MW) + Large Magellanic Cloud (LMC) potential confirm a highly eccentric ($e \approx 0.8$), polar ($i \approx 89.5^\circ$) orbit with a recent pericentric passage $\sim 0.14$ Gyr ago at $r_{\rm peri} \approx 9.5$ kpc. Boötes III is thus likely actively tidally disrupting, as its tidal radius at pericenter, $r_t \approx 164$ pc, is only $\sim 0.35$ of its half-light radius. The unusually low dispersion also implies that Boötes III has either lost most of its dark matter to tides or hosts a cored inner density profile, making it a probe of the nature of dark matter. Simulated tidal streams are broadly consistent with the Styx stellar stream, though the predicted track and kinematics are sensitive to the MW halo mass, LMC mass, and solar velocity. Boötes III overlaps the Typhon stream in integrals-of-motion space but has a much lower mean metallicity, suggesting the two are not the same system but may have had a common group infall origin. Sagittarius-stream contamination prevents a direct tidal-tail detection, so deep spectroscopic follow-up remains essential, both to confirm Styx as a genuine stream and to establish it as Boötes III's tidal tail.
#### Cluster-Weighted Training of Deep Surrogate Models for Subgrid Turbulent Transport
 - **Authors:** Rimsha Hameed Syeda, Dustin Kempton, Viacheslav Sadykov, Irina Kitiashvili, Rafal Angryk
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Fluid Dynamics (physics.flu-dyn)
 - **Arxiv link:** https://arxiv.org/abs/2607.07925

 - **Pdf link:** https://arxiv.org/pdf/2607.07925

 - **Abstract**
 Turbulence in the solar interior and atmosphere plays a crucial role in energy transport, yet modeling its subgrid-scale effects remains a major challenge. This study leverages machine learning (ML) models to predict components of the Reynolds stress tensor using high-resolution StellarBox simulations of the quiet Sun. Previously, we have compared a Multi-Layer Perceptron (MLP) and a 3D Convolutional Neural Network (CNN) against physics-based baselines to achieve a lower Mean Squared Error (MSE) and better generalization across various heights and depths in the solar atmosphere. To enhance learning, in this work, we investigate cluster-weighted training using K-Means and Hierarchical Agglomerative Clustering (HAC). By weighing the loss function based on cluster-specific prediction errors, we direct the model's attention to high-error regions. It significantly improves CNN performance, achieving 34% lower MSE and a significantly higher R2 score indicating that integrating deterministic clustering with ML is a promising technique for modeling subgrid turbulence, in particular, and regression in diverse environments, in general.
#### Catching Disguised Transients with ASTRANet: Anomaly-Aware Spectroscopic Classification and Conformal Calibration
 - **Authors:** Argyro Sasli, Maojie Xu, Alexandra Junell, Hailey Markoff, Avyukt Raghuvanshi, Felipe F. Nunes, Theophile Jegou Du Laz, Jesper Sollerman, Christoffer Fremling, Drew Oldag, Antoine Le Calloch, Sushant Sharma Chaudhary, Sneha Maharjan, Maxine West, Benny Border, Nabeel Rehemtulla, Richard Dekany, Joahan Castaneda Jaimes, Russ R. Laher, Reed Riddle, Mansi M. Kasliwal, Matthew J. Graham, Ashish A. Mahabal, Michael W. Coughlin
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2607.08044

 - **Pdf link:** https://arxiv.org/pdf/2607.08044

 - **Abstract**
 Time-domain surveys discover thousands of transients per year, but the spectroscopic identification of rare and physically peculiar objects remains rate-limited by closed-set classifiers that confidently assign every input to a known class -- including spectra that genuinely belong to no known class. We present the \texttt{ASTRANet} framework, a confidence-aware infrastructure for spectroscopic transient classification built around three coupled modules: a hierarchical spectral classifier that operates directly on observer-frame spectra without requiring host-galaxy redshift or spectral phase as inputs; an anomaly detection layer (\texttt{ASTRANet-Sentinel}) that non-linearly combines $16$ embedding-space anomaly scores spanning four physically motivated families; and a conformal uncertainty quantification layer (\texttt{ASTRANet-CP}). We validate the framework on a held-out evaluation set of $289$ rare and out-of-taxonomy transients spanning $11$ classes deliberately excluded from training, chosen to span the full physical diversity of the rare-anomaly population: AGN-related outliers, GRB-related events, gap transients, novae, and peculiar supernovae. Through five astrophysically distinct failure modes of closed-set classifiers, we show that classifier-internal uncertainty and embedding-based anomaly detection are structurally complementary axes of confidence rather than alternative implementations of the same estimator. We further introduce AD-stratified Mondrian conformal prediction (AD-MCP) within \texttt{ASTRANet-CP}, achieving uniform conditional coverage across anomaly-score strata where vanilla Mondrian under-covers in the operational regime. This establishes the methodological infrastructure for confidence-aware spectroscopic discovery in the Vera C.\ Rubin Observatory era.
#### The Southern-sky MWA Rapid Two-metre (SMART) pulsar survey--IV. Survey update and an atlas of 205 non-recycled southern pulsars
 - **Authors:** N. D. R. Bhat, C. P. Lee, S. J. McSweeney, B. W. Meyers, C. M. Tan, M. Xue, Q. Fu, N. A. Swainston, S. M. Ord, G. J. Sleap, S. E. Tremblay, W. van Straten, A. Williams, C. Di Pientrantonio, C. J. Harris, P. J. Elahi
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.08106

 - **Pdf link:** https://arxiv.org/pdf/2607.08106

 - **Abstract**
 The SMART survey is an ambitious effort to conduct sensitive searches for pulsars and fast transients at 140-170 MHz. The novelty of voltage recording, long dwell times and the high-time and -frequency resolutions exchange a large survey speed for high computational cost. The survey covers the entire sky south of +30 degree in declination through a series of dedicated campaigns, accumulating 4 PB of data. The large volumes of data necessitate processing to be approached in multiple phases, and the initial searches focused on a shallow survey of parts of the skies, as reported in earlier papers. These data are also processed for re-detections of hundreds of known pulsars in the southern sky, many of which are also the first detections below 400 MHz. This paper is motivated by the need to address the inherent difficulties in handling large amounts of voltage data and software/processing challenges for routine pulsar detections, and also by the fast-evolving landscape of the SKA Observatory (SKAO). With the construction ramping up towards the full-scale SKA-Low, a low-frequency catalogue of detectable pulsars in the southern sky will prove to be a valuable reference for science verification. A growing sample of low-frequency detections and measurements will also prove invaluable in a variety of science applications including population studies, survey simulations and emission beam models, refining interstellar medium models for electron densities and the spatial distribution of turbulence, and also for forecasting the detection prospects and survey yield from pulsar surveys planned with SKA-Low. We present various data products, including pulse profiles, time series and multi-channel folded archives, along with the measurements of dispersion and rotation measures, and mean flux densities, and this will be periodically updated as more detections flow on from the ongoing data processing.
#### CARPP: Parametric Radiative-Transfer Fitting of Molecular Cores from Dust Continuum Data
 - **Authors:** Yuchen Xing, Di Li, Nannan Yue, Zhiyuan Ren, Qizhou Zhang, Sihan Jiao, Xin Lyu, Jiawei Liu
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.08192

 - **Pdf link:** https://arxiv.org/pdf/2607.08192

 - **Abstract**
 The density profiles of dense molecular cores are important indicators of their physical and evolutionary states. Multi-wavelength dust continuum data offers excellent constraints on the density profile of cores. Here we introduce CARPP (Core Analysis via Radiative Transfer and Profile Parameters), a publicly available fitting package that generates optimized core density and temperature profiles based on parameterized radiative transfer calculations. CARPP assumes spherical symmetry and adopts physically motivated parametric forms for the density and temperature profiles, and uses dust continuum data for fitting. Tests on synthetic data show that CARPP achieves high accuracy, namely averaged relative errors of CARPP's seven parameters being $<20\%$, when the data quality satisfies $\frac{\rm RMS \,\, noise}{[\rm peak \,\, flux]} < 0.025\times \frac{[r_0]}{\rm resolution} +0.05$, where $r_0$ is the core's characteristic radius. We select the low-mass core TMC-1C and the high-mass core Ori2-2 to demonstrate CARPP's performance on real data. It classifies TMC-1C as a Bonnor-Ebert sphere in near-hydrostatic equilibrium, while Ori2-2 exhibits a power-law-dominated profile indicative of a collapsing envelope. This capability establishes CARPP as a powerful and versatile tool to classify the dynamical states of individual cores. It offers an optimal balance between physical fidelity and computational efficiency, serving as a practical, standardized alternative to both over-simplified SED analyses and complex, time-intensive 3D radiative-transfer modeling.
#### A search for circumstellar gas in pre-main-sequence debris discs using absorption spectroscopy
 - **Authors:** Karolina M. Szewczyk, Daniela P. Iglesias, Olja Panić
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2607.08263

 - **Pdf link:** https://arxiv.org/pdf/2607.08263

 - **Abstract**
 Gas in debris discs is thought to be either inherited from the protoplanetary stage or released from the solid, rocky content of planetesimal belts. Its presence can impact planetary atmospheres and their potential for habitability, which stresses the need to ascertain its origin and composition. Most detections to date are around main-sequence stars, with only a few gas-bearing debris discs identified around pre-main-sequence stars, mainly through millimetre CO line searches. We investigate narrow gas absorption features superimposed on the photospheric Ca II K & H and Na I D1 & D2 lines in a sample of 125 pre-main sequence and 5 relatively young (<17Myr) stars. All stars are associated with IR excess emission indicative of presence of a debris disc. By comparing their residual spectra (photosphere-subtracted) to those of nearby stars, interstellar cloud velocities, and stellar radial velocities, we test whether interstellar absorption is the culprit and ascertain circumstellar gas origin. Using these methods, out of the 130 targets, we identified two new gas-bearing debris discs: TYC7879-1373-1, which exhibits stable absorption, and HIP30414, which shows variable gas absorption features linked likely to ongoing accretion. Both these systems are pre-main-sequence stars younger than 5Myr. TYC6822-283-1 has absorption features of inconclusive origin. This study increases the number of currently known very young (<10Myr) debris discs with circumstellar gas to eight, paving the path to future systematic studies of objects caught in transition from protoplanetary to debris disc stages.
#### Successive Coronal Jets as Novel Facilitators for Filament Oscillation and Eruption
 - **Authors:** Chengrui Zhou, Chun Xia, Wentai Fu, Hechao Chen, Qiaoling Li
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.08390

 - **Pdf link:** https://arxiv.org/pdf/2607.08390

 - **Abstract**
 Solar filament eruptions are central to coronal mass ejections and space weather, yet their triggering mechanisms remain a fundamental open question. In particular, the early-stage that drives a magnetic flux rope toward instability and its observable signatures are poorly understood. Here, combining multi-instrument observations, we report successive coronal jets impacting a filament, causing its gradual rise and oscillations with growing amplitude and period. When the filament reaches the height where the decay index exceeds the torus instability threshold, the rapid filament eruption commences. This filament eruption is reproduced by magnetohydrodynamic simulations, in which successive thermal jets disturb a stable filament in a magnetic flux rope and excite oscillations together with the eruption of the filament. As the filament rises to erupt, the restoring forces for the oscillation progressively weaken, which naturally leads to an increase of the oscillation amplitude and period. Our results demonstrate the growing oscillations as one of the observable precursors for filament eruptions, enhancing our ability to predict solar eruptions.
#### Effects of low resolution on the column density PDF of molecular clouds
 - **Authors:** Yuping Tang, Q. Daniel Wang, Grant W. Wilson, Xing Lu, Jinhua He
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.08419

 - **Pdf link:** https://arxiv.org/pdf/2607.08419

 - **Abstract**
 Observational resolution significantly impacts the interpretation of column density probability distribution functions (N-PDFs) in molecular clouds, which are essential for understanding turbulent structures and star formation processes. This study quantifies how low spatial resolution truncates the high-density power-law tails of N-PDFs by simulating distant observations (2-10 kpc) of 17 local massive molecular clouds/regions using Herschel-based column density maps. We propose a parameter-free model, assuming proportional embedding of dense regions within lower-density gas, to predict the truncation column density where the survival function equals the beam-to-threshold area ratio. Comparisons with simulations show good agreement, with deviations up to 0.3 dex attributed to cloud multiplicity in large complexes and flatter power-law tails in coherent structures. Characteristic cloud scales, derived from Delta-variance spectra, indicate that global smearing dominates when beam sizes exceed these scales. We further develop a reverse method to recover the intrinsic high-density tail from low-resolution data. Our findings link N-PDF shapes to morphologies, suggesting that feedback-compressed extended structures resist smearing, while multiplicity accelerates truncation. These insights caution against biases in N-PDF decompositions and provide a framework for correcting resolution effects in distant cloud studies, enhancing constraints on star formation theories.
#### Exploring the effect of mixing in Low-Luminosity Type IIp Supernovae by modeling SN 2024abfl
 - **Authors:** Akshith Karri, Abigail Polin, Paul Duffell
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.08424

 - **Pdf link:** https://arxiv.org/pdf/2607.08424

 - **Abstract**
 Low-luminosity Type IIp supernovae (LLSNe) are SN IIps with peak magnitudes > -15.5 and plateau magnitudes between -13.5 and -15.5 in the V band. SN 2024abfl is an LLSN with a unique light curve, particularly the steep drop in luminosity observed after the plateau phase makes it an interesting candidate for modeling core-collapse supernova mechanisms. Using a custom pipeline involving MESA and STELLA, we investigate the possibility of suppressed ejecta mixing as a cause of the steep drop-off from the plateau phase. We find that turning off mixing mechanisms during shock breakout can mimic the distinct flat plateau and steep luminosity drop into the radioactive tail of the light curve while using previously proposed progenitor mass, radius and explosion energy parameters. Using these results as a proof-of-concept, exploring the effects of limited mixing in LLSNe candidates could give us better insight into how they differ from Typical Type IIp SNe.
#### Multi-Path Quasi-Periodic Fast-mode Propagating Magnetoacoustic Waves to Diagnose Coronal Magnetic Field and Flaring Core
 - **Authors:** Yuhu Miao
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2607.08487

 - **Pdf link:** https://arxiv.org/pdf/2607.08487

 - **Abstract**
 Quasi-periodic fast-mode magnetoacoustic waves are often detected during solar flare events, although they are not observed in every flare, due to observational signal-to-noise limits and differences in flare magnetic topology and energy release strength. These structures propagate along magnetic configurations and supply effective diagnostics for coronal magnetic environments and flaring regions. Periodic signatures seen in fast-mode QFP wave trains carry physical information about excitation processes and propagation conditions. These signatures support quantitative studies of flare cores and magnetic channel properties. This work focuses on a well-documented event involving two oppositely oriented QFP waves simultaneously excited by a GOES-class M6.0 solar flare that occurred in active region NOAA 11261 on August 3, 2011. These QFP waves can be categorized into broad and narrow wave trains, with the narrow one propagating along funnel-like loops and the broad one moving through the low corona. Observational results suggest that both broad-wave and narrow-wave QFP phenomena can be simultaneously triggered by a single flare eruption. This study also indicates that such multi-path QFP wave events can be utilized to diagnose the magnetic field and the flare's core, and demonstrates the capability of multi-path QFP waves for robust coronal magnetic field and flare core diagnostics.
#### Constraints on the properties of warm ionized gas from low-frequency hydrogen radio recombination lines
 - **Authors:** Pedro Salas, Kimberly L. Emig, Matteo Luisi, D. Anish Roshi, Loren Anderson
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.08542

 - **Pdf link:** https://arxiv.org/pdf/2607.08542

 - **Abstract**
 The ionized gas in the Milky Way is a major component of the interstellar medium. Observations of extinction free tracers, such as hydrogen radio recombination lines (HRRLs), have revealed the presence of a dense (electron density 1 to 100 cm$^{-3}$) warm ionized medium. Motivated by advances in radio instrumentation, the existence of fully sampled HRRL maps, and a better knowledge about the population of discrete HII regions in our Galaxy, we have acquired new low-frequency ($\nu\lesssim1$ GHz) observations of HRRLs to characterize the properties of this gas. We target three positions in the Galactic plane, with few or no known HII regions, using the 342 MHz and 800 MHz feeds of the Green Bank Telescope. We detect HRRL emission from all three positions. We combine these with the fully sampled HRRL 5.8 GHz cubes from the GBT Diffuse Ionized Gas Survey (GDIGS) to determine the gas properties using a forward modeling approach. From our analysis we find electron densities between 6 and 15 cm$^{-3}$, and that to determine the gas temperature and emission measure we require informative priors or higher signal-to-noise observations.
#### VAPOLA -- A multi-year, multi-band polarization survey of AGN and Sgr A* at mm wavelengths with ALMA I. Survey Overview and Science-Ready Archival Products
 - **Authors:** Alejandro Mus, Ciriaco Goddi, Douglas Carlos, Vincenzo Galluzzi, Ezequiel Albentosa-Ruiz, Ivan Martí-Vidal, Hugo Messias, Kazi L. J. Rygl, Geoffrey B. Crew, Lynn D. Matthews, Elisabetta Liuzzo, Nicola Marchili, Raphael P. Rolim, Mariafelicia De Laurentis, Rocco Lico, Cristiano Urban
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.08657

 - **Pdf link:** https://arxiv.org/pdf/2607.08657

 - **Abstract**
 The Atacama Large Millimeter/submillimeter Array (ALMA) is the most sensitive interferometric array at millimeter and submillimeter wavelengths. Through the ALMA Phasing System (APS), it can participate in global Very Long Baseline Interferometry (VLBI) arrays, enhancing their sensitivity and resolution. However, processing and analzing the ALMA data obtained in APS mode during VLBI observations remains a complex task, requiring specialized expertise and time-consuming calibration and imaging procedures. In this paper, we present VAPOLA-the first online, multi-epoch, multi-band repository of high-level data products from ALMA observations of active galactic nuclei (AGN) and Sgr A* during global VLBI campaigns. Built on an automated pipeline that processes fully calibrated ALMA (QA2) data, generates science-ready products with minimal user intervention. The repository includes fully calibrated interferometric visibilities, full-Stokes images across individual and combined spectral windows, polarimetric and spectral index maps, as well as tabulated polarimetric parameters from visibility-domain polarization fitting. By offering ready-to-use data through a user-friendly web portal, VAPOLA enables non-expert users to perform advanced science analyses without needing in-depth knowledge of ALMA procedures. This resource will facilitate a broad range of scientific investigations, including the characterization of magnetic field properties in accretion flows and relativistic jets, the structure and kinematics of dusty and molecular tori in AGN, and absorption studies of the interstellar medium toward the Galactic Center. In addition, the dataset provides source-integrated parameters and calibration metadata essential for refining VLBI calibration and imaging workflows as well as for placing robust observational constraints on theoretical models of supermassive black holes and their environments.
#### Detection of the Polycyclic Aromatic Hydrocarbon Phenalene (C$_{13}$H$_{10}$) in the Very Low Luminosity Object (VeLLO) MC27/L1521F
 - **Authors:** Gabi Wenzel, Thomas H. Speak, Ci Xue, Edwin A. Bergin, Andrew M. Burkhardt, Martin A. Cordiner, Miya Duffy, Zachary T. P. Fried, Andrew Lipnicky, Christopher N. Shingledecker, Reace H. J. Willis, Anthony J. Remijan, Michael C. McCarthy, Brett A. McGuire, Ilsa R. Cooke
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR); Chemical Physics (physics.chem-ph); Space Physics (physics.space-ph)
 - **Arxiv link:** https://arxiv.org/abs/2607.08699

 - **Pdf link:** https://arxiv.org/pdf/2607.08699

 - **Abstract**
 To date, 14 polycyclic aromatic hydrocarbons (PAHs) ranging in size from two to seven (including five- and six-membered) carbon rings have been detected in the starless dense core TMC-1 CP within the Taurus molecular cloud. Their detection raises questions about the distribution of PAHs in the cold interstellar medium (ISM) and their evolution during star formation. Here, we present the first interstellar detection of a three-ring PAH outside of TMC-1 CP. We detect phenalene (C$_{13}$H$_{10}$), a compact, peri-fused PAH, in the dense core MC27/L1521F, a molecular cloud in Taurus containing a very low-luminosity object (VeLLO). We compare the abundances of phenalene in the two sources with respect to the single-ring aromatic benzonitrile, and find that it is enhanced by a factor of four in MC27/L1521F. We discuss the implications for possible formation and destruction pathways in the two sources. These findings further support the widespread abundance of PAHs throughout the cold ISM and are consistent with survival, inheritance, or replenishment during the earliest stages of star formation.
#### Force convergence in Monte Carlo Lyman-alpha radiative transfer
 - **Authors:** Joshua Kasiri (1), Aaron Smith (1), Kevin Lorinc (1), Olof Nebrin (2), Kazutaka Kimura (3) ((1) UT Dallas (2) Stockholm (3) Tohoku)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.08726

 - **Pdf link:** https://arxiv.org/pdf/2607.08726

 - **Abstract**
 Monte Carlo radiative transfer (MCRT) is widely used to model Lyman-alpha (Lya) resonant-line transport, but convergence is difficult to assess in optically thick media where photons undergo many scatterings before escape. This is especially important for internal quantities such as radiative acceleration and the force multiplier, which depend on momentum deposition throughout the gas rather than only on emergent spectra. We study the convergence of Lya MCRT momentum-transfer estimators in static spherical clouds. We first establish diffusion-limit benchmarks for radial acceleration profiles and integrated force multipliers, then develop a moment-based framework for diagnosing convergence from the photon-packet contribution distribution. This framework separates three distinct questions: whether the estimator converges to the correct mean, how large its finite-sampling uncertainty is, and whether the estimated uncertainty is itself stable. We apply this hierarchy to the direct event-based scattering estimator, a gradient-of-energy-density estimator, and a divergence-of-radiation-pressure estimator. Zeroth-order convergence is assessed with profile comparisons, integrated force-multiplier bias, and finite-group relative error. First-order convergence is quantified with fractional error, the photon number required to reach a target precision, and the corresponding runtime requirement. Second-order convergence is tested with the coefficient of variation of variance, which measures the reliability of the variance estimate used in the first-order diagnostics. Core-skipping prescriptions, source geometry, estimator construction, and spatial resolution enter this hierarchy in different ways. Our results provide a practical convergence framework for internal Lya MCRT force calculations and show why statistical precision, computational cost, and physical accuracy must be evaluated separately.


by olozhika (Xing Yuchen). 


2026-07-10
