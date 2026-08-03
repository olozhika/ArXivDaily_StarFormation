# Showing new listings for Monday, 3 August 2026
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['star formation', 'star-forming', 'molecular cloud', 'interstellar medium', 'cloud', 'clump', 'core', 'filament', 'atomic gas', 'N-PDF']


Excluded: ['galaxies', 'galaxy cluster', ' AGN ', 'standard candle', 'X-ray binar', 'solar corona']


### Today: 7papers 
#### Single Frequency CMB Foreground Removal with Inter-scale Machine Learning
 - **Authors:** Helen Shao, Fiona McCarthy, Blake D. Sherwin, Miles Cranmer, Carlos Hervias-Caimapo
 - **Subjects:** Subjects:
Cosmology and Nongalactic Astrophysics (astro-ph.CO)
 - **Arxiv link:** https://arxiv.org/abs/2607.28712

 - **Pdf link:** https://arxiv.org/pdf/2607.28712

 - **Abstract**
 Accurate measurements of Cosmic Microwave Background (CMB) B-mode polarization, a key probe of inflationary physics, are hindered by complex Galactic dust foregrounds. Traditional foreground removal with Internal Linear Combination (ILC) fully preserves the primordial signal but requires multi-frequency data and is limited to two-point statistics. We present a novel way to estimate and remove foregrounds at single frequency using signal-preserving machine learning that leverages inter-scale correlations. Using the DustFilaments simulations, we train CNNs to reconstruct large-scale foregrounds ($\ell < 200$) from small-scales ($\ell > 200$). We quantify the effectiveness of foreground removal with the residual foreground power, $f_{\rm{resid}}$, which gives the fraction of foreground power remaining after removal. Predictions using only small-scale $B$-modes achieve $f_{\rm{resid}}\simeq 0.704$, while adding temperature and $E$-modes decreases it to $f_{\rm{resid}} \simeq 0.376$. These results are still higher than the spatial ILC, which leverages multi-frequency data at Simons-Observatory-like frequencies. However, a hybrid network that uses both multi-frequency and inter-scale correlations attains $f_{\rm{resid}}=4.71\times10^{-4}$ when using $B$-mode inputs alone, and $3.62\times10^{-4}$ when using temperature and $E/B$-mode inputs. This network achieves a residual power of $\sim 7\times$ lower than ILC, while inheriting ILC's signal-preserving property. This is $\sim 2$--$3\times$ lower than a network that only uses multi-frequency inputs, demonstrating that correlations across scale are not redundant with correlations across frequency and that our techniques are complementary to multi-frequency foreground removal. However, this is achieved only for DustFilments and network generalization across simulations remains a key challenge for robust ML-based foreground removal. (abridged)
#### The s-process at Subsolar Metallicity: Insights from High-Resolution Infrared Spectroscopy of Magellanic Cloud Planetary Nebulae
 - **Authors:** N. C. Sterling (1), M. G. Stephenson (1, 2), Harriet L. Dinerstein (2), A. Yagüe-López (3), Kyle F. Kaplan (2), J. Beaumont (1), Maria Lugaro (4, 5, 6), Amanda I. Karakas (6), Umberto Battino (7, 8, 9), J. García-Rojas (10, 11), Samuel M. H. Erben (12) ((1) University of West Georgia, (2) University of Texas at Austin, (3) Los Alamos National Laboratory, (4) Konkoly Observatory, (5) ELTE Eötvös Loránd University, (6) Monash University, (7) University of Naples, (8) INAF Observatory Astronomico d'Abruzzo, (9) The NuGrid Collaboration, (10) Instituto de Astrofísica de Canarias, (11) Universidad de La Laguna, (12) Georgia Institute of Technology)
 - **Subjects:** Subjects:
Solar and Stellar Astrophysics (astro-ph.SR); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.28729

 - **Pdf link:** https://arxiv.org/pdf/2607.28729

 - **Abstract**
 We present observations of 12 Magellanic Cloud planetary nebulae (PNe) obtained with the high-resolution near-infrared spectrometer IGRINS on Gemini South. In 10 targets we detect multiple neutron(n)-capture elements that can be synthesized by the s-process during the preceding asymptotic giant branch (AGB) phase, including the widely-observed species Se and Kr, and first detections of Rb, Cd, and Te in extragalactic PNe. The derived abundances significantly expand the inventory of trans-iron element abundance determinations from PNe in subsolar metallicity stellar populations. Seven targets exhibit s-process enrichments relative to the metallicity references O and Ar, with abundances elevated by factors of up to ~40-50 for Te and Kr. We compare these results with AGB nucleosynthesis predictions, using a machine-learning algorithm to find the best-fitting Monash, FRUITY, and NuGrid models. For five of the PNe, Monash and FRUITY models with 2-4 solar masses and metallicities from 1/3 solar to near-solar match the observations well, although the Monash models more successfully fit the largest Kr enhancements. NuGrid models predict smaller s-process enrichments than observed, but the limited number of available models makes it difficult to assess their ability to reproduce the observed abundances. We were unable to find models that provide good fits to three other enriched PNe, including the most metal-poor objects in our sample. These comparisons address uncertainties in mass loss, convection, and other mixing mechanisms during the late evolution of low- and intermediate-mass stars, and improve the accuracy of s-process yields of AGB stars, which are key parameters for modeling galactic chemical evolution.
#### Optical and acoustic ground effects simulations from terminal defense asteroid disruption via the PI method
 - **Authors:** Brin Bailey, Alexander N. Cohen, Philip Lubin, Darrel K. Robertson, Mark Boslough, Sasha Egan, Elizabeth A. Silber, Dharv Patel
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP); Instrumentation and Methods for Astrophysics (astro-ph.IM)
 - **Arxiv link:** https://arxiv.org/abs/2607.28850

 - **Pdf link:** https://arxiv.org/pdf/2607.28850

 - **Abstract**
 Our simulations suggest that PI ("Pulverize It"), a NASA Phase II NIAC study, is an effective multi-modal approach for planetary defense that can operate in extremely short interdiction modes (with intercepts as short as hours prior to atmospheric entry) as well as long interdiction time scales with months to years of warning. The basic process is complete disruption of the threat via fragmentation. In scenarios with sufficiently long warning time, the fragment cloud spreads enough to miss Earth, resulting in no ground effects. In "worst-case" scenarios, when the warning time is short, the fragments (typically <10 m in diameter) will enter Earth's atmosphere, where their energy is dissipated in a series of ground-level optical pulses and de-correlated shock waves, mitigating any significant damage. We investigate the optical and acoustic ground effects through a set of simulation codes that model the interaction of asteroid fragments with Earth's atmosphere following terminal threat interception. Even in short-warning time cases where fragments enter the atmosphere, our simulations suggest that threats mitigated by the PI method produce vastly less damage on the ground when compared to the same unfragmented case, yielding optical energy deposition below 200 kJ/m$^2$ and shock wave over-pressures under 3 kPa. Our simulations support the proposition that threats like 2023 PDC, the hypothetical 800 m diameter asteroid from the 2023 Planetary Defense Conference impact exercise, can be effectively mitigated through fragmentation. We find that a terminal defense mitigation scenario that disrupts 2023 PDC into 1 million fragments with an intercept of 60 days before ground impact results in minimal ground effects.
#### A Physically Driven Parameterisation of Multidimensional Atmospheres: Application to the JWST Phase Curve of WASP-121b
 - **Authors:** Yuanheng Yang, Guo Chen, Xianyu Tan, Thaddeus D. Komacek, Xi Zhang, Thomas M. Evans-Soma, Fei Yan, Chengzi Jiang, Fei Dai
 - **Subjects:** Subjects:
Earth and Planetary Astrophysics (astro-ph.EP)
 - **Arxiv link:** https://arxiv.org/abs/2607.29057

 - **Pdf link:** https://arxiv.org/pdf/2607.29057

 - **Abstract**
 Understanding the multidimensional structure of strongly irradiated exoplanets is essential for interpreting their atmospheric dynamics, chemistry and energy transport, yet current analyses remain limited by the difficulty of extracting reliable phase-resolved spectra and by the lack of physically interpretable parameterisations for retrievals. We combine a data-driven eclipse-normalisation method with an analytical three-dimensional temperature parameterisation derived from radiative, advective and diffusive energy balance and controlled by a few characteristic timescales. Applied to JWST/NIRSpec G395H observations of WASP-121b, the method yields spectra consistent with conventional phase-curve fitting, while the parameterisation reproduces the large-scale thermal structures predicted by general circulation models. The preferred retrieval reveals a pronounced day--night contrast, a dayside thermal inversion extending to both limbs, an inversion over part of the nightside, and limb temperatures differing by several hundred kelvin. Dynamical transport strengthens with pressure, and the hotspot offset increases from $\sim4^\circ$ to $\sim9^\circ$ across the pressures probed by G395H. The confined dayside hot region and the small, pressure-dependent offsets lie closer to the $\sim$3~G GCM than to its non-magnetic counterpart, although Rayleigh drag cannot be excluded. The spectra also favour distinct dayside and nightside chemical states, with more nightside CH$_4$ than the cooler temperatures alone can explain, pointing to disequilibrium chemistry. The retrieved thermal structure further implies an inhomogeneous cloud distribution, with condensation favoured on the nightside and cooler morning limb. The framework provides a computationally efficient, physically interpretable path from spectroscopic phase curves to multidimensional atmospheric structure.
#### Gamma-ray emission from particle illumination and shock-cloud interaction in the W51 Complex
 - **Authors:** Alan Sunny, Martina Cardillo
 - **Subjects:** Subjects:
High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2607.29488

 - **Pdf link:** https://arxiv.org/pdf/2607.29488

 - **Abstract**
 In the current era of very-high-energy (VHE) and ultra-high-energy (UHE) $\gamma$-ray astronomy, understanding Galactic PeVatrons and their acceleration mechanisms remains a primary objective. Recent LHAASO observations of the W51 Complex make it an ideal laboratory for investigating the origin of UHE emission, particularly due to the presence of massive and dense molecular environment surrounding multiple potential particle accelerators. In this work, we study two hadronic scenarios for the W51 Complex. First, we model the direct interaction between the SNR W51C and the nearby clouds in W51B, incorporating fresh particle acceleration, shock-driven adiabatic compression, and reacceleration of permeating Galactic cosmic rays. Second, we explore an accelerator-independent illumination scenario in which the W51B cloud acts as a long-term confinement region for high-energy particles injected during an earlier epoch. We find that the direct shock-cloud interaction scenario successfully reproduces the GeV emission observed by Fermi-LAT, but fails to account for the UHE emission detected by LHAASO. In contrast, the illumination scenario naturally explains the UHE spectrum, indicating that dense molecular clouds can efficiently confine and sustain energetic hadronic populations over long timescales. Although the inferred injection history is compatible with a young SNR origin, the source-independent nature of the illumination framework also permits other accelerators within the W51 Complex. Our results therefore identify dense molecular environments as the key structures sustaining historical PeVatron activity and shaping the observed UHE $\gamma$-ray emission.
#### ROLLIN': Rotating globular cluster simulations II. The complex morphology of globular clusters driven by multi-scale dynamics
 - **Authors:** Arn Marklund, Paolo Bianchini, Anna Lisa Varri, Katarina Kraljic, Giulia Pagnini
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.29499

 - **Pdf link:** https://arxiv.org/pdf/2607.29499

 - **Abstract**
 Globular clusters (GCs) are inherently non-spherical systems that in many cases show internal rotation. Typically, rotation is considered the main driver of GC morphology; however, the relationship between ellipticity and rotational support is not a simple one-to-one mapping, and other multi-scale dynamical processes may contribute. We investigate how morphology evolves in realistic models of rotating GCs, and how it correlates with key physical ingredients, including mass loss, stellar evolution, external tidal fields, and two-body relaxation. Using the \texttt{ROLLIN'} suite of direct N-body simulations, we measure the intrinsic ellipticity and triaxiality of our models using the second-moment tensor method, and explore their evolution and the physical mechanisms driving them. We find that early GC evolution can be dominated by dynamical instabilities driven by internal rotation and velocity anisotropy, leading to bar-like structures that rapidly erode due to collisional effects around the time of the first core collapse. These bars are stronger and longer-lived ($\lesssim 800,\mathrm{Myr}$) in strongly rotating clusters with longer relaxation times and subject to stellar evolution. In the long term, clusters evolve toward less flattened and gradually triaxial configurations, particularly when they experience stronger mass loss, are more tidally filling and isotropic, and have lower rotational support. Our models provide a physical explanation for the observational $V/\sigma$--ellipticity relation and demonstrate that morphology can serve as a reliable tracer of the dynamical state of GCs. Initially retrograde, dense, and inclined rotating models deviate from this relation, providing a physical explanation for observational outliers. This framework will aid the interpretation of GC evolution in upcoming large-scale photometric surveys.
#### The TOP-SCOPE Survey of Planck Galactic Cold Clumps: Molecular gas properties
 - **Authors:** Yuebin Yang, Jarken Esimbek, Tie Liu, Willem Baan, Xunchuan Liu, Kee-Tae Kim, Gang Wu, Xindi Tang, Jianjun Zhou, Dalei Li, Yuxin He, Sung-ju Kang, Yingxiu Ma, Dongdong Zhou
 - **Subjects:** Subjects:
Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2607.29512

 - **Pdf link:** https://arxiv.org/pdf/2607.29512

 - **Abstract**
 We surveyed 2008 Planck Galactic Cold Clumps (PGCCs) in $^{12}\mathrm{CO}$ and $^{13}\mathrm{CO}$ $J=1$--0 lines using the Taeduk Radio Astronomy Observatory (TRAO) 14 m telescope's multi-beam receiver. We detected 2784 ($^{12}\mathrm{CO}$) and 2291 ($^{13}\mathrm{CO}$) velocity components, their closely correlated centroid velocities suggest that $^{12}$CO and $^{13}$CO generally trace kinematically associated gas. PGCCs have low excitation temperatures (mean $\sim$10 K), mean $^{13}\mathrm{CO}$ optical depth $\sim$0.5, and mean $^{13}\mathrm{CO}$-derived H$_2$ column density $4.3\times10^{21}$~cm$^{-2}$. Gas--dust correlations are moderate, with $N_{^{13}\mathrm{CO}}$ more tightly correlated with the dust-derived H$_2$ column density from the PGCC catalog than $I_{^{12}\mathrm{CO}}$. Colder PGCCs tend to have higher CO-to-H$_2$ conversion factor ($X_{\mathrm{CO}}$) and $[\mathrm{H_{2}}]/[^{13}\mathrm{CO}]$ ratio. $X_{\mathrm{CO}}$ increases clearly with the dust-derived H$_2$ column density, consistent with enhanced CO freeze-out in high-column-density gas. Supersonic non-thermal motions are widespread: the Mach number derived from $^{13}\mathrm{CO}$ has a mean of 4.3 and a median of 3.6, increasing slightly with dust-derived H$_2$ column density. Overall, PGCCs are cold but dynamically active, serving as a valuable laboratory for studying the initial conditions of star formation.


by olozhika (Xing Yuchen). 


2026-08-03
