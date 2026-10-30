# Showing new listings for Friday, 30 October 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['star formation', 'star-forming', 'molecular cloud', 'interstellar medium', 'cloud', 'clump', 'core', 'filament', 'atomic gas', 'N-PDF']


Excluded: ['galaxies', 'galaxy cluster', ' AGN ', 'standard candle', 'X-ray binar', 'solar corona']


### Today: 26papers 
#### Resolving the thermal component of stellar feedback with the "anchor-and-refine" scheme in galactic simulations
 - **Authors:** Chengzhe Li, Hui Li, Wei Cui, Federico Marinacci, Laura Sales, Mark Vogelsberger, Paul Torrey
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.37767

 - **Pdf link:** https://arxiv.org/pdf/2610.37767

 - **Abstract**
 (abridged) Stellar feedback regulates galactic baryon cycles, but galaxy-scale simulations often cannot resolve supernova cooling radii. Momentum-based subgrid models can consequently underresolve the hot gas around young stars. We develop an "anchor-and-refine" feedback scheme that anchors a host cell near each star particle, preventing its displacement and preserving a thermal-feedback reservoir. When the cooling radius is resolved, all supernova energy is injected into the host cell as thermal energy; otherwise, the host cell is refined and terminal momentum is deposited into surrounding gas cells. Idealized tests agree with high-resolution simulations, yielding consistent superbubble properties and preserving hot interiors without artificial cooling. In an isolated Milky Way-mass galaxy, the scheme captures finer X-ray-emitting structures and a sharply defined, X-ray-bright central mid-plane. It also produces a smoother star formation history than pure hybrid feedback. Hot gas dominates outflow mass loading, with the mass-loading factor plateauing at approximately 0.2 at heights z>1 kpc. Phase decomposition indicates that hot gas sustains a steady, energy-driven wind, whereas cooler outflows decline with height because of radiative cooling and gravitational fallback. These results highlight the role of thermal feedback in driving galactic winds. By preserving hot superbubble interiors and the partition of thermal and kinetic energy, anchor-and-refine improves the treatment of hot gas, star formation, and feedback at limited resolution, supporting future applications to galaxy-scale and cosmological zoom-in simulations.
#### NORI: a GPU-accelerated code for simulating self-gravitating and self-interacting dark matter
 - **Authors:** Oliver Zier, Ruediger Pakmor, Xuejian Shen, Rongrong Liu, Lucas Schleuss, Mark Vogelsberger, Lars Hernquist
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.37768

 - **Pdf link:** https://arxiv.org/pdf/2610.37768

 - **Abstract**
 Self-interacting dark matter (SIDM) can form cores in dark matter haloes and later drive their gravothermal collapse, raising their central densities far above those of NFW haloes. Simulating this collapse is computationally demanding, requiring increasingly short time-steps and a large particle number to resolve the shrinking core. We present NORI, an $N$-body code that runs on CPUs and GPUs and simulates isolated self-gravitating systems with elastic, isotropic self-interactions using a Monte-Carlo method. To avoid MPI communication in the tree walks, each compute node in CPU mode, and each GPU or group of GPUs in GPU mode, holds a copy of all particles and its own Morton-ordered tree. A fixed evaluation order makes the results bitwise identical on CPUs and GPUs. Applying scattering events sequentially conserves the momentum and energy of each pair to round-off and allows multiple scatterings per particle per step. With global time-steps in both codes, NORI is several times faster on CPUs than our AREPO-2 implementation. One four-A100 GPU node is up to 60 times faster per time-step than AREPO-2 on a 112-core CPU node. For a full core-collapse simulation, where AREPO-2 uses individual time-steps, the speed-up is $\sim 30$ for the central density to reach $10^3$--$10^4$ times the NFW scale density, $\rho_{\rm s}$. We follow a halo with $10^8$ particles within $r_{200}$ to a central density of $10^4\,\rho_{\rm s}$. Within the limit of about $2\times10^9$ particles set by data replication, NORI provides an efficient tool for isolated SIDM simulations, including gravothermal collapse and cluster collisions.
#### Revisiting Sub-Neptune Population Synthesis: The Role of Core Luminosity in Boil-off, Photoevaporation, and the Radius Distribution
 - **Authors:** Yao Tang, Jonathan J. Fortney, Natalie Batalha, Ruth Murray-Clay
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2610.37789

 - **Pdf link:** https://arxiv.org/pdf/2610.37789

 - **Abstract**
 The observed bimodal radius distribution of close-in small planets provides important constraints on their formation and evolution. Two atmospheric escape mechanisms, photoevaporation and core-powered mass loss, have been widely invoked to explain this distribution. In this work, we revisit the physical assumptions underlying these models and investigate the role of core luminosity in driving outflows and shaping the radius distribution. We develop a population synthesis framework based on the SEAMIST evolution model, which self-consistently couples the two mass-loss mechanisms while accounting for envelope metallicity. We find that envelope metallicity strongly affects the resulting radius distribution, with 50-100$\times$ solar metallicity providing a good match to the observed population. Boil-off generally dominates atmospheric mass loss, while photoevaporation typically removes at most 3 wt\% of the envelope mass. We find that core luminosity contributes only $\sim$10-20\% of the thermal energy available for envelope re-equilibration during boil-off, producing an absolute mass-loss enhancement of only $\sim$0.4wt\%. Its effect is larger during photoevaporation, where the longer mass-loss timescale allows core heating to accumulate. Nevertheless, core luminosity has little impact on the long-term planetary radius distribution. These results suggest that core-powered mass loss is better understood as a modification to atmospheric escape through its lower-boundary conditions rather than as a distinct mass-loss mechanism. In our best-fit model, the radiative atmosphere contributes a significant $\sim$20\% of the total optical radius. Consequently, we highlight the need for improved radiative-atmosphere modeling in sub-Neptune evolution models to better understand the observed population distribution.
#### Core-collapse universality for inelastic self-interacting dark matter halos
 - **Authors:** Evan Batteas, Alexander Brisebois, Maheen Hemani, Maximilian Heyne, J. Leo Kim, Lukas Lehmann, Laura Sagunski, Aster Schnell, Sean Tulin
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2610.37852

 - **Pdf link:** https://arxiv.org/pdf/2610.37852

 - **Abstract**
 We study the gravothermal collapse of inelastic dark matter halos with velocity-dependent elastic and dissipative self-interactions. Within the gravothermal fluid framework, we derive the effective cooling rate for dark matter upscattering to an excited state followed by decay back to the ground state, with emitted states carrying off energy from the halo. We solve the gravothermal fluid equations numerically to simulate spherically symmetric halos over the core-growing and collapse phases of their evolution. While halos with purely elastic self-interactions have universal evolution trajectories, inelastic dark matter halos exhibit much more diversity in their evolution. Nevertheless, inelastic halo dynamics contain a hidden parametric universality from which we derive a semi-analytic formula for calculating the halo collapse time for arbitrary velocity-dependent elastic and inelastic cross sections without the need for simulations.
#### Simulating and Characterizing Non-Gaussian Small-Scale Polarized Emission
 - **Authors:** Mark A. Bishop, Brandon S. Hensley, Krzysztof M. Gorski, Charles Lawrence, Graça Rocha
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.37942

 - **Pdf link:** https://arxiv.org/pdf/2610.37942

 - **Abstract**
 Galactic foregrounds present a major challenge for cosmic microwave background (CMB) cosmology as their amplitudes exceed the target primordial $B$-mode signal. While small-scale interstellar medium (ISM) emission is expected to be highly complex, current foreground simulations cannot reproduce the filamentary, non-Gaussian features of ISM structure in a stochastic way. To address this gap, we introduce a framework for generating stochastic small-scale foreground emission, using polarized synchrotron observations as an example use case. This method is capable of producing many independent realizations that additionally inherit morphological information from large angular scales. The underlying structural complexity incorporates anisotropic, multifractal, and advected non-Gaussian features that are tunable with a small number of parameters that carry physical interpretations. Because standard power spectra do not describe the complex phase coherence required for the structural complexity, we evaluate the synthetic fields using higher-order statistics, demonstrating that the Minkowski functionals and structure functions partially capture varying degrees of non-Gaussianity. This work lays the necessary foundation for new foreground simulation suites with stochastic realizations of possible non-Gaussian structure.
#### The Carousel Lens III: Joint lens convergence and source kinematic modeling
 - **Authors:** William Sheu, Xiaosheng Huang, Tania M. Barone, Fuyan Bian, Aleksandar Cikota, Karl Glazebrook, Tesla Jeltema, Evan Odell, Jackson H. O'Donnell, Linus Upson, Felipe Urcelay, Sean Xu
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2610.37971

 - **Pdf link:** https://arxiv.org/pdf/2610.37971

 - **Abstract**
 We introduce a new, independent modeling component to the Carousel Lens series by exploiting the spatially-resolved kinematics contained within the lensed arcs, which so far has remained rather underexplored in strong-lensing analyses. We present an end-to-end forward-modeling framework that reconstructs an integral-field spectroscopic datacube from a parameterization of the lens convergence profile together with the line-of-sight velocity, velocity dispersion, and surface brightness profiles of the unlensed source. The kinematic structure of the source acts as an additional set of ray-traceable markers distributed across every lensed image, inaccessible from imaging data alone. Furthermore, by generating an [OII] emission-line datacube, we isolate a single source redshift and remove lens and line-of-sight light contamination. We apply this framework to deep VLT/MUSE observations of the Carousel Lens, modeling the [OII] emission of the quadruply-imaged star-forming galaxy at $z_{\rm s} = 1.432$ that anchors the system's cosmography constraints. We measure an Einstein radius $\theta_{\rm E} = 12.816''^{+0.005}_{-0.007}$ and a logarithmic slope $\gamma = 1.412^{+0.002}_{-0.002}$, tightening the statistical uncertainties on both by roughly a factor of $2-2.5$ relative to the corresponding flat emission-line map model. We find that the source galaxy exhibits a strong rotation, lies confidently along the star-forming main sequence, and has an inferred central black hole mass of $\log M_{\rm BH}/M_{\odot} = 7.89 \pm 0.51$. These results establish datacube-level forward modeling as a practical and independent route to traditional image-based lens models in the current systematics-limited regime, and one that extends naturally to this system's other lensed sources and to other lens systems.
#### Evolutionary Demographics of Molecular Ice Mantles in Young Stars with SPHEREx
 - **Authors:** J. Serna, S. P. Matt, M. McClure, M. Kounkel, C. G. Roman-Zuñiga
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.38043

 - **Pdf link:** https://arxiv.org/pdf/2610.38043

 - **Abstract**
 Molecular ices are a primary reservoir of volatile C, O, and N in star-forming environments, tracing the chemical pathway from molecular clouds to planet-forming disks. SPHEREx provides contiguous 0.75--5~$\mu$m all-sky spectrophotometry for vastly larger samples than are accessible to JWST, enabling population-scale ice demographics for the first time. We present a search for ice signatures in SPHEREx spectra of 20{,}292 young stellar objects (age $<20$~Myr) drawn from the Gaia-based kinematic catalog of Kounkel \& Covey 2019. Using laboratory templates for the spectral signatures of H$_2$O (3.05~$\mu$m), CO$_2$ (4.27~$\mu$m), and CO (4.67~$\mu$m), we identify 746 H$_2$O ice candidates, including 131 high-confidence H$_2$O+CO$_2$ detections and 22 with additional corroborating CO absorption. When binning by age, we find that the H$_2$O$+$CO$_2$ detection rate declines by an order of magnitude between $\lesssim$3~Myr and $\sim$5~Myr, suggesting a chemical or physical evolutionary trend. Candidates concentrate toward high-extinction sightlines ($A_G \gtrsim 2.5$~mag) and embedded SED morphologies, consistent with the idea of envelope dispersal and photodesorption depleting detectable ice mantles within the first few million years of pre-main-sequence evolution. This catalog provides a homogeneous demographic baseline and a prioritized target list for JWST follow-up.
#### Experimental Demonstration of Double-Fourier Interferometer Imaging for Future Space-Based Far-Infrared Observatories
 - **Authors:** Jeremy P. Scott, Locke D. Spencer, Chris Benson, David Naylor, Berke Ricketti, Dinula De Silva, Vince Weiler
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.38105

 - **Pdf link:** https://arxiv.org/pdf/2610.38105

 - **Abstract**
 Far-infrared (FIR) astronomy is crucial for observing star formation, active galactic nuclei, and protoplanetary systems, but its effectiveness is severely limited by poor diffraction-limited spatial resolution. To overcome this limitation, a double-Fourier interferometer (DFI), which couples a spatial interferometer with a Fourier transform spectrometer, has been proposed to deliver high-resolution broadband spectral imaging. Despite various conceptual and prototype studies, a comprehensive demonstration of DFI capabilities has been lacking. In this study, we present the validation of key DFI observing techniques using a laboratory testbed operating in the 0.3 to 2.1 THz optical bandwidth. We detail the instrument's ideal response alongside necessary calibrations for intensity imbalances, non-linear phase errors, and phase-center offsets. Our experimental results successfully demonstrate aperture synthesis for both one- and two-dimensional targets, accurately recovering source geometries. Furthermore, we prove the instrument's sensitivity to spatially dependent spectral variations by utilizing a low-pass optical filter on extended sources. Finally, we validate wide-field imaging capabilities by combining data from independent pixels in a detector array, each sensitive to different regions of the source plane. The experimental data show significant agreement with theoretical predictions, with minor deviations attributed to optical aberrations and perspective effects. These laboratory demonstrations validate the DFI architecture as a highly capable and mature technology for future space-based FIR observatories.
#### Asteroseismic properties of young pulsators in the Perseus Molecular Cloud. Discovery of period-spacing patterns in HD 281229
 - **Authors:** Saakshi Wadhwa, Dario J. Fritzewski, Gang Li, Simon J. Murphy
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.38264

 - **Pdf link:** https://arxiv.org/pdf/2610.38264

 - **Abstract**
 Very young pulsating stars, including pre-main sequence pulsators, provide a rare opportunity to probe stellar interiors and investigate rotation during the earliest phases of stellar evolution. However, they remain relatively unexplored, particularly in the intermediate-mass regime. We aim to identify and characterise young pulsating stars in the Perseus Molecular Cloud using photometric data from the Transiting Exoplanet Survey Satellite (TESS). We compiled Gaia-based membership catalogues for the Perseus Molecular Cloud, applied selection criteria to isolate young intermediate-mass stars, and extracted light curves from TESS full-frame images. Variability classification was performed using Lomb-Scargle periodograms and iterative pre-whitening. For confirmed pressure-mode pulsators, we estimated the frequency of maximum pulsation power, $\nu_{\mathrm{max}}$. For gravity-mode candidates, we searched for period-spacing patterns and fit them using the traditional approximation of rotation. From 148 membership-selected targets, we identified eight pressure-mode pulsators and two objects showing possible gravity-mode pulsations. We analysed the previously known $\delta$ Sct star V705 Per, bringing the total sample to 149 targets. One of the gravity-mode pulsators, HD 281229, is the youngest star known to date with a detected and modelled period-spacing pattern. By simultaneously fitting the dipole and quadrupole period-spacing patterns, we estimate an asymptotic period spacing of $\Pi_0=4776\pm400$ s and a near-core rotation frequency of $f_{\mathrm{rot}}=1.317\pm0.05$ $\mathrm{d}^{-1}$. These results highlight the potential of asteroseismology to probe the internal structure and rotation of very young stars. The detected period-spacing pattern in HD 281229 shows that gravity-mode asteroseismology can provide meaningful constraints on the properties of stars at early evolutionary stages.
#### NSF-DOE Vera C. Rubin Observatory's First View of the Neptune Trojan L5 (Trailing) Cloud: Two New Long-Term Stable Trojans
 - **Authors:** Megan E. Schwamb, Pedro H. Bernardinelli, Kathryn Volk, Joseph Murtagh, Hsing Wen Lin, Andrew S. Rivkin, Colin Orion Chandler, R. Lynne Jones, Susan D. Benecchi, Mario Jurić, Jacob A. Kurlander, Sarah Greenstreet, Adam Wilson, Maxine West, Ryan R. Lyttle
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2610.38309

 - **Pdf link:** https://arxiv.org/pdf/2610.38309

 - **Abstract**
 The NSF-DOE Vera C. Rubin Observatory's combination of survey speed, sky coverage, and depth provides a unique opportunity to study the distant Trans-Neptunian region, including the Neptune Trojans. The Neptune Trojans are small bodies on orbits with Neptune's semimajor axis that are locked in the 1:1 mean motion resonance librating about the ice giant's stable Lagrange points, L4 (leading) and L5 (trailing), located 60$^{\circ}$ ahead of or behind the planet. For more than 15 years, the on-sky location of the L5 Neptune Trojan cloud has been coincident with the Galactic plane and Galactic center; the high stellar density has significantly hindered the discovery of L5 Neptune Trojans. In 2025, the L5 cloud has now moved sufficiently out of the galactic plane to overlap with the sky covered by Rubin Observatory's Science Validation (SV) survey that was executed during the Observatory's commissioning phase. We report on two new confirmed long-term stable (primordial) members of the Neptune L5 Trojan cloud (2025 MH348 and 2025 NN80), doubling the known sample, and one candidate (2025 MD138) that have been found in a preliminary search of the SV survey observations. We present our study to characterize the physical and dynamical properties of these objects and compare the L5 sample to the well-studied L4 cloud. This work also presents the first characterization of objects discovered by Rubin Observatory's moving object discovery pipelines using observations taken in an LSST-like cadence and as such, provides a blueprint for LSST-era analyses.
#### Coupled evolution of Earth's H2-rich proto-atmosphere and oxidized magma ocean: Efficient H2O production through dissolved H2 transport and atmospheric buffering of the magma ocean redox state
 - **Authors:** Tatsuya Yoshida, Kirara Arima, Naoki Terada, Takeshi Kuroda, Kiyoshi Kuramoto
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2610.38503

 - **Pdf link:** https://arxiv.org/pdf/2610.38503

 - **Abstract**
 Giant impacts during Earth's final accretion likely generated global magma oceans, where the disproportionation of Fe^2+ at lower-mantle pressures and segregation of the resulting metallic iron into the core could have oxidized the magma ocean. Earth may nevertheless have had an H2-rich proto-atmosphere in chemical disequilibrium with the magma ocean, but the chemical coupling between this atmosphere and an oxidized magma ocean remains poorly constrained. Here we develop a coupled atmosphere-interior evolution model that includes diffusive transport in the boundary layer between the magma ocean and atmosphere, redox reactions in the melt, partitioning of oxide components and H2O among coexisting phases, and planetary cooling through a proto-atmosphere, with metallic iron produced by Fe^2+ disproportionation removed into the core as it forms. Atmospheric H2 transport into the magma ocean and subsequent H2O production become more efficient with increasingly frequent boundary layer renewal driven by buoyant overturn of dense melt cooled at the surface, allowing the atmosphere and magma ocean to chemically equilibrate within ~10^4 yr when the magma ocean is sufficiently deep and hot to extend into the lower mantle. Redox exchange with the atmosphere buffers the solidification-driven redox evolution of the magma ocean, preventing extreme oxidation or reduction of the coupled system. These results suggest that the coupled evolution could have contributed to early Earth's water inventory while maintaining a reducing H2-rich atmosphere.
#### The nature of the Norma arm as a bar-driven star-forming shock front
 - **Authors:** Hillary Davis, Joss Bland-Hawthorn, Thor Tepper-Garcia, Oscar Agertz, Elizabeth Iles
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.38607

 - **Pdf link:** https://arxiv.org/pdf/2610.38607

 - **Abstract**
 The Milky Way is commonly depicted as having four major spiral arms, including the Norma-Outer arm, and a central stellar bar whose properties remain debated. Masers associated with young high-mass stars have been used to trace a segment of the "Norma arm" extending from one end of the Galaxy's central stellar bar. Recent work suggests that these masers may reside along a spiral arm or occupy the dominant x1 stellar orbits that give the bar its shape. We now use a new generation of N-body, hydrodynamic simulations to argue that these million-year old masers instead trace the Galactic bar's Quadrant I shock front or, equivalently, its dust lane. This implies that the bar dust-lane is star-forming, shedding new light on our understanding of star formation processes in the Milky Way. By associating the masers with the simulated shock front, we determine the bar's parameters to be: a ~ 4.3 +/- 0.2 kpc, b ~ 2.3 +/- 0.2 kpc, phi = 20 (+5/-2) deg, Omega_p <~ 40 km s^-1 kpc^-1, representing the bar's semi-major and semi-minor half-lengths, inclination angle and pattern speed, respectively. This raises questions about the Milky Way's spiral structure and suggests that the Galactic bar is long, slow and star-forming.
#### Episodic Plasma Flows and Coronal Brightenings in an Arch Filament System Observed with SUNRISE III
 - **Authors:** Sergio Javier González Manrique, Juan Carlos Trelles Arjona, Christoph Kuckein, Azaymi L. Siu-Tapia, Fernando Moreno-Insertis, Samrat Sen, Sami K. Solanki, Adur Pastor Yabar, Andrés Asensio Ramos, Daniel Nóbrega-Siverio, Manuel Collados, David Orozco Suárez, María Helena Rivero González, Sara Esteban Pozuelo, Jose Carlos del Toro Iniesta, Maria Balaguer Jiménez, Esteban Sanchis Kilders, Ignacio Torralbo, Yukio Katsukawa, Yusuke Kawabata, Hirohisa Hara, Toshifumi Shimizu, Takayoshi Oba, Andreas Lagg, Achim Gandorfer, Pietro Bernasconi, Thomas Berkefeld, Alex Feller, Tino L. Riethmüller, Alberto Álvarez-Herrero, Masahito Kubo, H. N. Smitha, Bianca Grauf, Michael Carpenter, Alexander Bell, Valentín Martínez Pillet, Francisco Javier Bailén, Julian Blanco Rodríguez, Juan Sebastián Castellanos Durán, Edvarda Harnes, Johannes Hoelken, Francisco A. Iglesias, Ryohtaroh T. Ishikawa, Takuma Matsumoto, Hanna Strecker, Dušan Vukadinović
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.38652

 - **Pdf link:** https://arxiv.org/pdf/2610.38652

 - **Abstract**
 Emerging flux regions (EFRs) transport magnetic flux and release energy in the solar atmosphere, often hosting arch filament systems (AFSs). We present high-resolution observations of an EFR obtained with Sunrise III, combining the Tunable Magnetograph (TuMag), the Sunrise Chromospheric Infrared Spectro-Polarimeter (SCIP), and the Solar Dynamics Observatory (SDO). The dataset follows an AFS continuously for nearly four hours. Line-of-sight (LOS) velocities derived from the Mg I b$_2$ line reveal three episodic plasma-flow events, with downflows reaching approximately 17 km s$^{-1}$ at the footpoints and enhanced upflows near the loop tops. Although this pattern agrees with the classical emergence and draining scenario, the strongest upflows and downflows occur nearly simultaneously. Atmospheric Imaging Assembly (AIA) observations at 304 and 171 Angstrom reveal transient extreme-ultraviolet (EUV) brightenings in the surrounding emerging system. Some occur during enhanced-flow episodes, while others do not, indicating that the temporal correspondence is not systematic. Multiline spectropolarimetric inversions reveal temperatures between approximately 4000 and 10,000 K and a smooth variation of magnetic field inclination along a representative AFS loop. Non-force-free-field extrapolations provide the large-scale magnetic context of the low-lying AFS loops and surrounding coronal structures. Together, the observations reveal a spatially and temporally complex evolution without establishing a direct causal connection between local plasma-flow enhancements and EUV brightenings.
#### UnEZ: A Fully Unsupervised Self-Templating Neural Network for Redshift and Line Strength Estimation
 - **Authors:** Asha Abd, Karl Glazebrook, Colin Jacobs
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Astrophysics of Galaxies (astro-ph.GA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2610.38816

 - **Pdf link:** https://arxiv.org/pdf/2610.38816

 - **Abstract**
 As spectroscopic surveys grow, estimating galaxy properties such as metallicity, star formation rate, and redshift becomes computationally cumbersome. Methods of estimating such properties rely on template spectra or curated redshift catalogs, which fail to represent the diversity of objects seen in large-scale surveys. We present UnEZ, a fully unsupervised, physics-informed machine learning model that can predict spectroscopic redshifts and line strengths with no prior redshift or line strength labels. An encoder predicts emission and absorption line amplitudes/widths, and a fixed deterministic decoder constructs a unique template, estimated redshift, redshift confidence curve, and spectral model. UnEZ was tested on the Sloan Digital Sky Survey (SDSS) Data Release 18 due to its large dataset and thoroughly vetted redshift catalog which serves as an independent benchmark. Despite the lack of templates, line strength labels, or redshift labels, UnEZ's performance competes with modern redshift estimation algorithms. At SNR > 10, UnEZ achieves an outlier fraction of 0.459% and a normalized median absolute deviation (NMAD) of $1.237 \times 10^{-4}$. At SNR > 3, UnEZ achieves an outlier fraction of 3.89% and an NMAD of $1.471 \times 10^{-4}$. Furthermore, we demonstrate how UnEZ's line strength and redshift predictions can be utilized for various purposes such as constructing template spectra required in traditional redshift estimation algorithms. UnEZ illustrates how a fully unsupervised neural network can allow redshift, among other galaxy properties, to emerge naturally from the spectra themselves, providing a template-free, label-free approach that scales to the demands of future surveys.
#### 3-Methoxy-1-propanol Rotational Spectroscopy and Radio Astronomical Search toward NGC 6334I
 - **Authors:** D. Archie Stewart, Laurent Margulès, Roman A. Motiyenko, Brett A. McGuire
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.38934

 - **Pdf link:** https://arxiv.org/pdf/2610.38934

 - **Abstract**
 The methoxy functionalized alcohol species methoxymethanol and 2-methoxyethanol have recently been identified toward the MM1 protostellar source in the NGC 6334I massive star-forming region. Here we report measurements of portions of the centimeter, millimeter, and sub-millimeter regions of the rotational spectrum of the most stable conformer of 3-methoxy-1-propanol in order to probe the presence of even larger methoxylated alcohols toward the source. The experimental rotational parameters determined from these spectra were used to simulate the rotational spectrum of 3-methoxy-1-propanol under the physical conditions of the MM1 source and compared to the same ALMA observational dataset of the source in which 2-methoxyethanol was first discovered. No 3-methoxy-1-propanol transitions are identified in the data, and an upper limit on its column density toward the source was determined to be $7.5 \cdot 10^{15} \text{ cm}^{-2}$. When considering the series of these three methoxy alcohols, the decrease in column density going from 2-methoxyethanol to 3-methoxy-1-propanol is consistent with how the column density of 2-methoxyethanol decreases compared to methoxymethanol.
#### The Korean Space Telescope (KST): A Dedicated Space Observatory for the Dark Universe
 - **Authors:** M. James Jee, Ho Seong Hwang, Dongwook Lim, Minjin Kim, Myungshin Im, Sungwook E. Hong, Ho-Gyu Lee, Soung-Chul Yang, David Parkinson, Arman Shafieloo, Jun-Qian Jiang, Haeng Pal Heo, Dongok Ryu, Hagyong Kihm, Hyung Yun Noh, Wooyong Kang, Youngsun Kim
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM); Cosmology and Nongalactic Astrophysics (astro-ph.CO); Earth and Planetary Astrophysics (astro-ph.EP); Astrophysics of Galaxies (astro-ph.GA); High Energy Physics - Experiment (hep-ex)
 - **Arxiv link:** https://arxiv.org/abs/2610.39094

 - **Pdf link:** https://arxiv.org/pdf/2610.39094

 - **Abstract**
 The Korean Space Telescope (KST) is a next-generation 1.4-meter wide-field space observatory, a dedicated probe of the dark sector. Its single instrument provides diffraction-limited visible imaging (~0.15 arcsec in the optical) together with simultaneous near-infrared (R ~ 100) slitless spectrophotometry, so that every detected source is observed in the NIR by the survey itself, with spectral information delivered at a resolution set by its brightness (full R ~ 100 typing at the bright end, synthetic medium-band or broadband photometry below it) and with no separate follow-up, a capability decisive for time-domain science. With it, KST addresses the three outstanding questions of dark physics in concert: the dynamics of dark energy, the nature of dark matter, and gravitational-wave dark sirens as independent cosmological rulers. KST combines measurements of expansion and structure growth to test dark-energy models. A two-tiered "Wedding Cake" strategy (2,000 deg^2 Wide plus 10 deg^2 cluster-targeted Deep Survey) combines weak lensing, baryon acoustic oscillations, and a near-infrared-standardized Type Ia supernova Hubble diagram to constrain dark energy at its pivot redshift (sigma(w_p) ~ 0.03); maps dark matter from cluster cores to galactic substructure to test cold dark matter against warm and self-interacting alternatives; and builds a deep near-infrared host catalog for a distance-ladder-independent H_0 from dark sirens. The same data yield a Legacy Science portfolio (galaxy evolution, active galactic nuclei, exoplanets, and the Milky Way) at no additional observing cost. As Korea's first dedicated astrophysics space mission, KST occupies a niche complementary to the Vera C. Rubin Observatory, Euclid, and Roman.
#### Insights into the Kinematic Evolution of Filament-Induced Jets: Coupling of Interchange and Flare Reconnection
 - **Authors:** Zehao Tang, Xiaoli Yan, Zhike Xue, Jincheng Wang, Zhe Xu, Yadan Duan
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.39253

 - **Pdf link:** https://arxiv.org/pdf/2610.39253

 - **Abstract**
 Jets are ubiquitous eruptive activities in the solar atmosphere, playing an important role in mass transport, atmospheric heating, and energy supply. However, the triggering mechanism remains elusive. To reveal the fine process of jet evolution, we study a jet associated with a B-class flare that involves in two distinct stages. Analyzing the complete evolution of a solar jet captured by the Solar Dynamics Observatory (SDO), we clearly identify its dual-stage kinematics, evolving from interchange to flare reconnection. This dual-stage jet is characterized by distinct dual-stage signatures in magnetic morphology, H$\alpha$ profile, jet speed, jet height, X-ray flux, loop-top source, and temperature. These differences are naturally unified by a physical picture coupling interchange and flare reconnection, offering new insights into understanding of the physical process of filament-induced jets.
#### The origin of UV emission in extremely low-mass satellite galaxies: Insights from Leo T
 - **Authors:** S Amrutha, Mousumi Das, Daniel Vaz, Jarle Brinchmann
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.39390

 - **Pdf link:** https://arxiv.org/pdf/2610.39390

 - **Abstract**
 Leo T, a Milky Way (MW) satellite, is the lowest-mass gas-rich galaxy known to show recent star formation, making it an excellent laboratory for investigating star formation in the ultraviolet (UV) regime within a low-density, metal-poor environment. We present a far-UV (FUV) study using Ultraviolet Imaging Telescope (UVIT) data, aiming to characterize FUV star-forming clusters (SFCs), identify FUV-emitting stars, constrain their properties, and explore star formation in an extremely low-mass, metal-poor galaxy. We examined the galaxy's FUV extent and compared it with the H I distribution. We extracted thirty SFCs and derived their properties, including area, luminosity, and star formation rate (SFR), and compared them with previous studies. FUV-emitting stars and their stellar parameters were identified through cross-matching with catalogs from the Hubble Space Telescope and the Multi Unit Spectroscopic Explorer (MUSE). We also estimated the global SFR and star formation efficiencies (SFEs) associated with previously identified CO clouds. The FUV luminosities of the SFCs confirm the absence of massive O and B-type stars in Leo T. The FUV-emitting stellar population consists of main-sequence (MS) stars, blue loop (BL) stars, horizontal branch stars, and emission-line (EM) stars. The upper MS and EM stars are concentrated near the optical center, whereas the lower MS and BL stars are more spatially extended. We find that five out of the six FUV-emitting stars with MUSE spectroscopy are extremely metal-poor ([Fe/H] $\leq$ -3). The (NUV - r) color profile indicates that the UV emission is dominated by stellar populations younger than 1 Gyr out to a radius $\lt$ 185 pc. Despite the recent detection of CO(1-0) emission, no SFCs are associated with the molecular clouds, which exhibit extremely low SFEs. The spatial distribution of the SFCs suggests a directional interaction with the MW.
#### The Peculiar Astrometric Behaviour and Radio Structure of the Quasar 1524-136 Revealed with Very Long Baseline Interferometry
 - **Authors:** Angelina Osetrova, Sándor Frey, Oleg Titov, Alexey Melnikov, Panna Gelle
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.39603

 - **Pdf link:** https://arxiv.org/pdf/2610.39603

 - **Abstract**
 According to astrometric very long baseline interferometry (VLBI) observations accurate to sub-milliarcsecond levels, the radio quasar 1524-136 (J1526-1351) exhibited an exceptionally large shift, more than 0.1", between the 1990s and 2010s. This luminous quasar is known for its extended (~0.4"), highly asymmetric and non-collinear jet structure. Here we analyse historical VLBI astrometric and imaging data, as well as Gaia optical astrometric information, to find the cause of the sudden apparent change in the position. At the X band (~8.4 GHz frequency), where radio positions are conventionally measured, the core region brightened substantially relative to the hotspot at the end of the northern jet. As a result, the brightness peak shifted from the hotspot to the core, causing the VLBI position to shift accordingly. Similar changes could affect the astrometric positions of other radio sources. A better understanding of the astrophysical reasons behind them is important for maintaining the stability of the VLBI-based celestial reference frame.
#### Detection of HNCOH+ in the interstellar medium
 - **Authors:** M. Rey-Montejo (1 and 2), I. Jimenez-Serra (1), M. Sanz-Novo (3), V. Lattanzi (3), S. Thorwirth (4), V. M. Rivilla (1), S. Zeng (5), L. Colzi (1), D. San Andres (1 and 2), A. Megias (1), A. Martinez-Henares (5), M. A. Requena-Torres (6), S. Martin (7 and 8), B. Tercero (9 and 10), P. de Vicente (10) ((1) Centro de Astrobiologia (CAB), CSIC-INTA, Torrejon de Ardoz, Spain, (2) Departamento de Fisica de la Tierra y Astrofisica, Facultad de Ciencias Fisicas, Universidad Complutense de Madrid, Spain, (3) Center for Astrochemical Studies, Max-Planck-Institut fur extraterrestrische Physik, Germany, (4) I. Physikalisches Institut, Universitat zu Koln, Germany, (5) Star and Planet Formation Laboratory, RIKEN Pioneering Research Institute, Japan, (6) Department of Physics, Astronomy, and Geosciences, Towson University, USA, (7) European Southern Observatory, Alonso de Cordova, Chile, (8) Joint ALMA Observatory, Alonso de Cordova, Chile, (9) Observatorio Astronomico Nacional (OAN, IGN), Madrid, Spain, (10) Centro de Desarrollos Tecnologicos, Observatorio de Yebes (IGN), Guadalajara, Spain)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.39654

 - **Pdf link:** https://arxiv.org/pdf/2610.39654

 - **Abstract**
 Only five out of the $\sim$350 molecules detected in the interstellar medium (ISM) carry the isocyanate functional group (NCO), the essential substructure of peptide bonds in proteins. Among them are isocyanic acid (HNCO) and its most stable N-protonated isomer H$_2$NCO$^+$. Previous studies have predicted that the O-protonated isomer HNCOH$^+$ should be present in the ISM; yet this species has remained elusive. We search for the metastable HNCOH$^+$ towards the Galactic Center molecular cloud G+0.693-0.027, where H$_2$NCO$^+$ has already been detected. We use an ultra-deep broadband spectral survey carried out towards G+0.693-0.027 with the Yebes 40-m, IRAM 30-m and APEX telescopes covering nearly 150 GHz of bandwidth between 31 and 275 GHz. We report the first detection of HNCOH$^+$ in the ISM with a column density of $N$ = (9.9 $\pm$ 0.5)$\times$10$^{12}$ cm$^{-2}$, which corresponds to a molecular abundance relative to H$_2$ of (7.3$^{+1.3} _{-1.0}$)$\times$10$^{-11}$. With the measured H$_2$NCO$^+$ column density of $N$ = (2.6 $\pm$ 0.3) $\times 10^{12}$ cm$^{-2}$, this yields a HNCOH$^+$/H$_2$NCO$^+$ ratio of 3.8$^{+0.5} _{-0.4}$. This result is consistent with recent kinetic calculations that favour the formation of HNCOH$^+$ over H$_2$NCO$^+$. The detection of HNCOH$^+$ in the ISM broadens the inventory of molecules known to contain the isocyanate functional group and reinforces recent works showing that isomer abundances in the ISM do not necessarily correlate with thermodynamic stability.
#### Towards an Astronomical Use of New-Generation Geodetic Observations
 - **Authors:** Víctor Pérez-Díez
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.39656

 - **Pdf link:** https://arxiv.org/pdf/2610.39656

 - **Abstract**
 This thesis explores the astronomical use of observations from the VLBI Global Observing System (VGOS), a next-generation geodetic network designed to improve the precision of terrestrial and celestial reference frames and Earth orientation parameters. Although primarily conceived for geodesy, its wide frequency coverage and regular monitoring of compact active galactic nuclei (AGN) provide valuable opportunities for astrophysics. We develop a calibration pipeline that transforms VGOS correlator outputs into full-polarization, calibrated visibilities suitable for astronomical imaging. The procedure combines linear-to-circular polarization conversion, instrumental phase and amplitude calibration, and a new wideband global fringe-fitting algorithm that accounts for dispersive ionospheric effects. Regularized maximum likelihood imaging is then used to reconstruct multi-frequency intensity and polarimetric images. The pipeline is applied to the blazar 1803+784 and five additional AGN: 3C418, 0059+581, 0613+570, 1849+670, and 2229+695. We measure frequency-dependent core shifts, spectral indices, and Faraday rotation properties. For 1803+784, the fitted core-shift index is $k_r = 0.73^{+0.12}_{-0.19}$, suggesting departures from a simple conical jet in energy equipartition. Finally, we apply the reconstructed source models to correct structure-dependent effects in geodetic VLBI observables. The correction reduces closure-delay scatter and post-fit residuals for strongly structured sources, particularly 3C418, while its effectiveness depends on source variability and the temporal proximity of the imaging observations. These results demonstrate the dual scientific value of VGOS as a powerful multi-frequency astronomical VLBI instrument and as a means of improving geodetic measurements.
#### The first mass peak of merging black holes from core binding energies and jet-driven explosions
 - **Authors:** Nikki Yat Ning Wang, Dmitry Shishkin, Noam Soker
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE); Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2610.39801

 - **Pdf link:** https://arxiv.org/pdf/2610.39801

 - **Abstract**
 We show that the jittering-jets explosion mechanism (JJEM) can qualitatively reproduce the shape of the black hole (BH) mass distribution observed by LIGO-Virgo-KAGRA and quantitatively reproduce the peak around $M_{p1} \simeq 10 M_\odot$. To show this, we construct a toy model that captures the JJEM physics that explodes all massive stars, even when BHs form. According to the JJEM, BHs form when the star's binding energy is large, implying a massive progenitor with initial mass $M_i \gtrsim 25 M_\odot$, and when jets are launched along a fixed axis, implying a rapidly rotating pre-collapse stellar core. In this case, the jets are launched along the core's angular momentum and are inefficient at removing mass near the equatorial plane; when the stellar binding energy is large, a large fraction of the equatorial mass is accreted to form the BH. The toy model includes two parameters: the threshold binding energy in the core for BH formation and the jet opening angle along the poles. Although our finding is encouraging for the JJEM, future hydrodynamical simulations must determine the exact condition for BH formation in the JJEM and the BH mass.
#### Identifying narrow-band mutual coupling resonances in SKA-low stations using frequency-independent current basis functions
 - **Authors:** John Cumner, Oscar S.D. O'Hara, Quentin Gueuning, Anthony Brown, Fred Dulwich, Oskar Zetterstrom
 - **Subjects:** Subjects:
Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2610.40008

 - **Pdf link:** https://arxiv.org/pdf/2610.40008

 - **Abstract**
 Mutual coupling between closely spaced elements in aperture arrays introduces narrow-band spectral features in the Embedded Element Patterns (EEPs), threatening measurements of the 21-cm power spectrum with instruments such as SKA-low. We detail a method to identify such features through the construction of frequency-independent current basis functions, utilising a singular value decomposition of frequency-dependent basis functions. We demonstrate the method on a three-element linear array and full pseudo-random station of SKA log-periodic antennas and examine the current power induced by mutual coupling. For the pseudo-random layout station we note many narrow-band resonance features, including strong resonances at 50.8~MHz and 83.6~MHz, where the coupled power on the passive antennas can approach or exceed that of the excited antenna. Simulated delay power spectra for the SKA-low core show that observing in frequency bands including resonance features causes large foreground leakage within the delay power spectra, obscuring the EoR window. For the pseudo-random layout station with SKALA4.0 we identify two significant frequency bands from 59.2--76.2~MHz and 84.2--103.3~MHz which are free of contamination from current resonances, preserving the EoR window in these frequency ranges.
#### Can the $\sim 5$ kpc starburst ring in MW create eROSITA bubbles?
 - **Authors:** Mukesh Singh Bisht, Kartick C. Sarkar
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.40049

 - **Pdf link:** https://arxiv.org/pdf/2610.40049

 - **Abstract**
 eROSITA bubbles (eRBs) in our Galaxy are thought to be due to the energy injection by the central star-forming region or the central Super Massive Black Hole. Identifying the origin of these bubbles is crucial in constraining the origin of the Fermi Bubbles and the nature of the Galactic feedback. However, some recent opinions suggest that the eRBs may not even have been produced by any central source, but rather a result of a star-formation ring at $R\sim 5$ kpc. In this letter, we perform detailed hydrodynamic simulations to refute that claim and show that such a ring of star formation alone is not able to produce the symmetric eROSITA bubbles - one needs a compact energy injection from the Galactic Center to produce these bubbles. Our study, therefore, suggests that the eROSITA bubbles truly represent the nuclear outflow from our Galaxy.
#### A compact NH$_2$D source without NH$_3$ counterpart in the S187 high-mass star-forming region
 - **Authors:** E. A. Trofimova (1), I. I. Zinchenko (1), C. Henkel (2), A. G. Pazukhin (1), A. F. Punanova (3), P. M. Zemlyanukha (1) ((1) Institute of Applied Physics of the Russian Academy of Sciences, (2) Max-Planck-Institut für Radioastronomie, (3) Onsala Space Observatory)
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.40219

 - **Pdf link:** https://arxiv.org/pdf/2610.40219

 - **Abstract**
 Our goal is to investigate a so far only tentatively detected compact NH$_2$D source devoid of a notable NH$_3$ counterpart, located rather close to the luminous IRAS 01202+6133 source (the projected distance is $\lesssim$0.3 pc) in the S187 high-mass star-forming region. A high ammonia deuteration in such an environment is unusual. We performed observations of this area with the 20-m OSO radio telescope in several frequency ranges from $\sim$72 to $\sim$112 GHz. The area was mapped at the lower frequencies while at the higher frequencies only the position of the NH$_2$D emission peak was observed. The data were analyzed using non-LTE modeling. The data confirm a compact NH$_2$D source with a size of $\lesssim$0.2 pc. In addition, emission from about 20 molecules was detected, but only the DCO$^+$(1-0) peak coincides with the NH$_2$D clump. The clump is not associated with any known astronomical source or an NH$_3$ emission peak but the dust continuum map shows an enhancement at approximately the same position. The gas kinetic temperature derived from various indicators is $\sim$20-30 K, which possibly characterizes the surrounding material. The intrinsic NH$_2$D line width ($\sim$0.4 km/s) implies a clump with subsonic or transonic turbulence. The ortho/para NH$_2$D line intensity ratio is consistent with an abundance ratio of 3, expected from the spin statistics. The NH$_2$D/NH$_3$ abundance ratio may be $\sim$1. In general, the data hint at a compact cold gravitationally stable dense core within the warm environment, which may represent pristine material. However this picture still needs a verification with observations at a higher angular resolution.
#### Complex Organic Molecules in Protostars with ALMA Spectral Surveys (COMPASS) VIII. First interstellar detection of fully deuterated methyl cyanide
 - **Authors:** A. Belloche, J. K. Jørgensen, M. N. Drozdovskaya, S. Spezzano, A. Coutens, J.-E. Lee, F. Cruz-Sáenz de Miera, D. Harsono, J.-H. Jeong, S. Maret, B. A. McGuire, P. Nazari, A. L. Plunkett, Y.-L. Yang, H.-S. Yun
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2610.40365

 - **Pdf link:** https://arxiv.org/pdf/2610.40365

 - **Abstract**
 Deuteration is a powerful metric to gain insight into the formation pathways of interstellar molecules in star forming regions. Our primary goal is to search for the fully deuterated form of methyl cyanide, CD3CN, in the ISM. We used a sensitive imaging spectral survey of the protostellar system L1551 IRS5 in the Taurus molecular cloud performed as part of the Large Program carried out with the Atacama Large Millimeter/submillimeter Array (ALMA) called Complex Organic Molecules in Protostars with ALMA Spectral Surveys (COMPASS). We derived the column densities of methyl cyanide and several of its less abundant isotopologs, including deuterated ones, under the assumption of local thermodynamic equilibrium. All three deuterated isotopologs of methyl cyanide were detected toward the northern binary component of L1551 IRS5. In particular, we report the first interstellar detection of CD3CN. The measured D/H ratio increases by about half an order of magnitude from one deuterated isotopolog to the next, in a similar way as what was measured for methanol in several other low-mass protostars. This suggests that methyl cyanide predominantly forms like methanol on the surface of dust grains during the cold prestellar phase. However, the measured factor of 2 difference between the D/H ratios of methyl cyanide and methanol may either indicate that gas-phase processes during the warm-up stage contribute approximately equally to the production of methyl cyanide, or that methyl cyanide and its deuterated isotopologs are formed during the prestellar phase at a somewhat earlier time than methanol. Multiply deuterated isotopologs are crucial to understand the formation and inheritance of molecules in the ISM by coupling observations and astrochemical models. Unfortunately, no model has so far investigated the deuteration of methyl cyanide up to the fully deuterated form. [Abridged]


by olozhika (Xing Yuchen). 


2026-10-30
