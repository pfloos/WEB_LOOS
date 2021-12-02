---
title: "Presentations"
date: 2020-12-02 09:06
draft: false
---

# Keynote speakers

### David Gontier (CEREMADE, Paris)

**DFT for two-dimensional homogeneous slabs**

In this talk, we study DFT models for homogeneous 2-d slabs in the 3-d space, and derive reduced equations in the direction orthogonal to the slab. We show in particular that the Pauli principle is replaced by a penalization term in the energy. We show how to solve these new equations, and we provide some properties for the minimizer, such as the decay of the density away from the slab. 
This is joint work with Salma Lahbabi and Abdallah Maichine 

### Antoine Levitt (CERMICS, Paris)

**Numerical methods for scattering and resonance properties in molecules and solids**

### Xavier Blase (Institut Neel, Grenoble)

**Space-time formalisms for efficient cubic scaling GW calculations : physics and chemistry taking parallel paths**

### Vittorio Somà  (CEA, Saclay)

**Ab initio description of doubly open-shell nuclei via a novel multi-reference perturbation theory**

Recent developments in many-body theory and in the modelling of nuclear Hamiltonians have enabled the ab initio description of a considerable fraction of atomic nuclei up to mass A~100. In this context, one of the main challenges consists in devising a method that can tackle doubly open-shell systems and at the same time scales gently with mass number. This would allow both to access all systems below A~100 and to open up perspectives for extending ab initio calculations to the whole nuclear chart.
Here I present a recently proposed many-body approach that aims towards this objective. After introducing the formalism based on a multi-reference perturbation theory [1], I will discuss the first numerical applications [2,3] together with considerations on the state of the art and future perspective in ab initio nuclear structure.

[1] M. Frosini et al., arXiv:2110.15737
[2] M. Frosini et al., arXiv:2111.00797
[3] M. Frosini et al., arXiv:2111.01461

### Elisa Rebolini (Institut Laue Langevin, Grenoble)

`Ab initio calculation of low-lying excitations in strongly-correlated systems: RelaxSE`

Strongly-correlated systems present the peculiar characteristic that their low- energy physical and chemical properties are not driven by the kinetic energy of their Fermi-level electrons. In these systems, the electron-electron correlation, sub-dominant or even negligible in most systems, is much larger than the kinetic energy. As a consequence, they cannot be properly described by a single Slater determinant and such methods usually give poor results for the ground state as well as the low-lying magnetic states.
Accurate calculation of this kind of excitation requires specifically-designed methods. The CAS+DDCI (Complete Active Space + Difference Dedicated Con- figurations Interaction) [1] method has been proved successful for systems with a small number of magnetic orbitals per atom. However it quickly reaches a com- putational wall when the number of magnetic orbitals increases. The SAS+S (Selected Active Space + Single) [2] method which has been developed in our group a few years ago, is able to go beyond the CAS+DDCI limitations. After a brief introduction on the problem at stake, I will recall the principle of the SAS+S method and present the new RelaxSE [3] software which we developed in order to treat these excitations.

[1] J. Miralles, J. P. Daudey and R. Caballol, Chem. Phys. Lett., 198, 555, (1992) ; V. M. Garc`ıa et al., Chem. Phys. Lett., 238, 222 (1995) ; Garcıa, V. M., Reguero, M. and Caballol, R., Theor. Chem. Acc., 98, 50, (1997).
[2] A. Gelle, J. Varignon and M.-B. Lepetit, EPL, 88, 37003 (2009).
[3] E. Rebolini and M.-B. Lepetit, J. Chem. Phys., 154, 164116 (2021).

### Francesco Sottile (Laboratoire des Solides Irradies, Palaiseau)

**Excitonic effects in electronic structure calculations: spectra and beyond.**

ABSTRACT: Excitonic effects have proved to be crucial for the quantitative description of 
optical absorption [1]. This picture has been confirmed for core excitations [2]. 
The description of excitons can be conducted, within the many-body Green's 
functions formalism, via the solution of the Bethe-Salpeter equation (BSE), which 
takes the electron-hole interaction, in the presence of all the
other electrons, automatically into account. More recently, we have put a lot of 
effort into extending the applicability of the BSE towards: i) different 
spectroscopies (like electron and photon scattering [3-5]), ii) unconventional picture
(excitonic band-structure [6]), and iii) pictorial tools (of the electron density 
evolution). In this seminar I will illustrate the achievements and problems 
of the BSE in tackling these new spectroscopies and tools.

[1] Rev. Mod. Phys. 74, 601 (2002)
[2] Phys. Rev. B 95, 155121 (2017)
[3] Phys. Rev. B 92, 165122 (2015)
[4] Phys. Rev. Research 2, 042003 (2020)
[5] Phys. Rev. Research 1, 032010 (2019)
[6] Electronic Structure 3, 014005 (2021)

# Contributed talks

### Derk Kooi (Vrije Universiteit, Amsterdam)

**London dispersion forces without density distortion: The Fixed Diagonal Matrices method**

The development of Density Functional Theory (DFT) has allowed for the routine use of calculations to support and explain experimental findings in chemistry at a reasonable computational cost. DFT, however, is not without its limitations. In particular there are two phenomena that remain its Achilles heel, strong correlation and London dispersion interactions. The difficulty in describing strong correlation is shared with the competing (post-Hartree-Fock) wavefunction methods, but the difficulty in describing dispersion interactions is rather specific to DFT. 

Attempts at building non-local functionals to capture dispersion have been somewhat successful[1,2], especially in calculations on solids[3], but they are outcompeted in practical calculations on molecules by empirical corrections based on pairwise atomic dispersion coefficients derived from free atoms[4] ¬or on free atomic polarizabilities combined with dipole moments of the exchange hole[5]. However, these empirical corrections are only able to take into account effects of the chemical environment of the atom in a limited way and cannot model anisotropy in the dispersion coefficients.

In our recent work[6-8] we have introduced a class of variational wavefunctions that capture the long-range interaction between neutral systems (atoms and molecules) without changing the diagonal of the density matrix of each monomer.  As the individual monomer densities are kept fixed, we can also unambiguously assess the effect of the density distortion on London dispersion interactions: for example, we obtain virtually exact dispersion coefficients between two hydrogen atoms up to C10, and relative errors below 0.2% in the case of two helium atoms.[6]  From a theoretical perspective the method raises interesting questions regarding the Hohenberg-Kohn, Virial and Hellmann-Feynman Theorems, which we have answered, together with providing a solid mathematical basis for the theory.[7] 

In benchmarks our so called Fixed Diagonal Matrices (FDM) method performs satisfactorily for closed-shell atoms and molecules when used with accurate (CCSD) pair densities, producing a Mean Average Percentage Error (MAPE) and Max Absolute Error (AMAX) of 7.1% and 18.2% for isotropic dispersion coefficients C6, respectively.[8] The method performs as well for anisotropic dispersion coefficients and can in principle be incorporated self-consistently.[7] For open-shell atoms improvements must still be made, by improving the wavefunction and/or the dispersal basisset. 

[1] D.C. Langreth, M. Dion, H. Rydberg, E. Schroder, P. Hyldgaard, and B.I. Lundqvist, Int. J. Quantum Chem. 2005, 101, 599
[2] O.A. Vydrov and T. Van Voorhis, Phys. Rev. Lett. 2009, 103, 063004
[3] T. Björkman, Phys. Rev. B. 2012, 86, 165109
[4] L.A. Burns, A.V. Mayagoitia, B.G. Sumpter, and C.D. Sherrill, J. Chem. Phys. 2011, 134(8), 084107.
[5] A.D. Becke, E.R. Johnson, J. Chem. Phys. 2007, 127, 154108.
[6] D.P. Kooi, P. Gori-Giorgi, J. Phys. Chem. Lett. 2019, 10, 7, 1537-1541
[7] D.P. Kooi, P. Gori-Giorgi, Faraday Discuss. 2020, 224, 145-165
[8] D.P. Kooi, T. Weckman, P. Gori-Giorgi, J. Chem. Theo. Comput., 2021, 17, 4, 2283-2293

### Gabriele Riva (LCPQ, Toulouse)

**Photoemission spectroscopy from the three-body Green’s function**

We present an original approach for the calculation of direct and inverse photo-emission spectra from first principles. The main goal is to go beyond the standard Green’s function approaches, such as the GW method, in order to find a good description not only of the quasiparticles but also of the satellite structures, which are of particular importance in strongly correlated materials. Our method uses as a key quantity the three-body Green’s function, or, more precisely, its hole-hole- electron and electron-electron-hole parts. We show that, contrary to the one-body Green’s function, satellites are already present in the corresponding non-interacting Green’s function. Therefore, simple approximations to the three-body self-energy, which is defined by the Dyson equation for the three-body Green’s function and which contains many-body effects, can still yield accurate spectral functions. In particular, the self-energy can be chosen to be static which could simplify a self-consistent solution of the Dyson equation. We also show how the one-body Green’s function can be retrieved from the three-body Green’s function. We illustrate our approach by applying it to the symmetric Hubbard dimer.

### Miguel Escobar Azor (LCPQ, Toulouse)

**Wigner localization in two and three dimensions: an ab initio approach**

We investigate Wigner localization at very low densities by means of the exact diagonalization of the Hamiltonian. This yields numerically exact results. In particular, we study a system of two electrons in one, two and three dimensions. Our approach consists of three main principles: (i) the creation of a supercell that has the topology of a d-dimensional Clifford torus, which is a flat, finite, and borderless manifold; (ii) the renormalization of the distance between two points on the Clifford torus by defining it as the Euclidean distance in the embedding space of the d- Clifford torus; (iii) we use a grid of equidistant spherical gaussians as a basis for the Hamiltonian.[1] We have extended the approach to two and three dimensions by using the translational symmetry of the system to efficiently calculate the electronic wave function. We have validated our approach by comparing our results to a semi-classical model that becomes exact in the low-density limit. With our approach we are able to observe the Wigner localization by means of the two-body reduced density matrix without ambiguity.[2] We have recently generalised our approach to electron gases with more than 2 electrons and we have obtained promising preliminary results.

[1] M. Escobar Azor, L. Brooke, S. Evangelisti, T. Leininger, P.-F. Loos, N. Suaud, and J. A. Berger, A wigner molecule at extremely low densities: a numerically exact study, SciPost Phys. Core 1, 001 (2019).
[2] M. Escobar Azor, E. Alves, S. Evangelisti, and J. A. Berger, Wigner localization in two and three dimensions: An ab initio approach, The Journal of Chemical Physics 155, 124114 (2021).


### Gaspard Kemlin (CERMICS, Paris)

**Practical error bounds for electronic structure calculations: energy, density matrices and forces**

 In the field of quantum chemistry, solving electronic structure problems gives rise to a certain number of approximations so that in practice, only approximations of quantities that are of interest (QoI) can be computed. Being able to estimate the error between the exact and the approximate quantities is thus crucial, as this information can be used to reduce the high computational cost of numerical methods by an optimization of the approximation parameters, together, and maybe more importantly, to add error bars to QoI calculated from the approximate solution. In our context, such QoI are typically the total energy of the system and the forces on the atoms in the system.
While such error bounds have been developed already some time ago for boundary value problems, the developments of such error bounds in electronic structure are still recent and incomplete. So far, no error bound has been proposed for the error estimation of QoI in electronic structure calculations, in particular for the forces of the system. This is what we are trying to achieve in this contribution, by developing new error estimators for nonlinear models, nonguaranted but valid asymptotically.
These bounds are based on an estimation of the error in terms of the residual of the solved equations, which is then efficiently approximated with computable terms. We numerically show how accurate these bounds are on a few representative materials systems, namely silicon, gallium arsenide and titanium dioxide.

### Wilken Misael (PhLAM, Lille)

**Recent Progress in the Development of Eco-Friendly Processed Organic Solar Cells: Experiments and Theory**

Synergic effects concerning electronic structure and morphology in the PTB7-Th polymer and the non-fullerene acceptor ITIC molecule has resulted in state-of-art systems for organic solar cells (OSCs), achieving over 12% PCE values [1]. Furthermore, the substitution of harmful halogenated solvents to environmentally friendly solvents that do not compromise PCE values has become a subject of great interest in the literature [2].
In this work, we employed sulfur K-edge Angle-Resolved Near-Edge X-ray Absorption Fine Structure (NEXAFS), Resonant Auger (RAS), and the Core-Hole Clock spectroscopies in an attempt to gain information on the effect of different processing methods on the elec- tronic and morphological properties of these systems. These spectroscopic measurements (NEXAFS, RAES and XPS) were carried out at the SXS beamline of the Brazilian Syn- chrotron Light Laboratory (LNLS).
In order to compare the use of an conventional acceptor molecule, we have performed Steady State and Time-Resolved Photoluminescence (TRPL) experiments for neat PTB7- Th and blends with ITIC and PCBM. TRPL measurements were carried at the Swansea’s Material Research Centre.
To a better comprehension of the sulfur excited states involved in the electronic tran- sitions probed by the synchrotron-based-spectroscopic methods, theoretical calculations were performed utilizing Restricted-Excitation-Window Time-Dependent Density Functional Theory (REW-TD-DFT). In order to probe the extent of relativistic effects present in these transitions, we employed different Hamiltonians (ZORA, DKH, X2C) in our calculations.
We also explored different chemical descriptors (the Donor-Acceptor and Aromatic- Quinoid approaches) to obtain information at valence level in both ground and low-lying excited states. All calculations were performed in NWChem 7.0, Gaussian16 and Amsterdam Density Functional (ADF).

[1] Jianhui Hou et al. “Organic solar cells based on non-fullerene acceptors”. In: Nature materials 17.2 (2018), pp. 119–128.
[2] Jingbo Zhao et al. “Efficient organic solar cells processed from hydrocarbon solvents”. In: Nature Energy 1.2 (2016), pp. 1–7.

### Mauricio Rodríguez-Mayorga (VU University, Amsterdam)

**Introducing Relativistic Reduced Density Matrix Functional Theory**

The applicability of reduced density matrix functional theory (RDMFT) is increasing among the chemists and physicist communities. Recent studies using the Hubbard model have proven that some RDMFT functional approximations are suitable for studying systems where strong electron correlation effects are dominant[1-2]. Moreover, as another example, RDMFT has been recently adapted as an alternative methodology to study superconductivity[3].
To further extend RDMFT applicability, we introduce in this work its relativistic version. Relativistic RDMFT is presented using the Dirac 4-component Hamiltonian and including the effects of creation and annihilation of electron-positron pairs. To this end, we have properly adapted the recent work of Toulouse[4], where relativistic density functional theory including effective quantum electron dynamics was established. Then, considering the so-called no-pair approximation[4] we also present the relativistic version of some of the most accurate RDMFT functional approximations[6-7]. Finally, we analyze some properties of these functional approximations.

[1] Mitxelena, I., & Piris, M. (2020). An efficient method for strongly correlated electrons in one dimension. Journal of Physics: Condensed Matter,
32(17), 17LT01.
[2] Mitxelena, I., & Piris, M. (2020). An efficient method for strongly correlated electrons in two-dimensions. The Journal of chemical physics,
152(6), 064108.
[3] Schmidt, J., Benavides-Riveros, C. L., & Marques, M. A. (2019). Reduced density matrix functional theory for superconductors. Physical Review
B, 99(22), 224502.
[4] Toulouse, J. (2021). Relativistic density-functional theory based on effective quantum electrodynamics. arXiv preprint arXiv:2102.10465.
[5] Mittleman, M. H. (1981). Theory of relativistic effects on atoms: Configuration-space Hamiltonian. Physical Review A, 24(3), 1167.
[6] Piris, M. (2013). Interpair electron correlation by second-order perturbative corrections to PNOF5. The Journal of chemical physics, 139(6), 064111.
[7] Piris, M. (2017). Global method for electron correlation. Physical review letters, 119(6), 063002.

### Guillaume Thiam (iLM, Lyon)

**Multi-basis-set TDDFT methods for predicting electron attachment energies**

 Understanding the interaction of low-energy electron collisions with molecules constitutes a key subject in a large area of fundamental research as well as modern applications in various fields of science such as astrochemistry, radiation-induced damage of biological tissue, selective chemistry, or chemical synthesis at nanoscale.
Collision of a low energy electron with a molecule can induce various phenomenon such as dissociation, ionization, isomerization, reactivity, etc, through the formation of a transient negative anion composed of the target molecule and the projectile electron, that can evolve toward a dissociative state through selective phenomenon.
A complete theoretical characterization of the temporary anion, which would describe the electron attachment, the relaxation of electronic and vibrational degrees of freedom, and possible fragmentation processes, is still challenging. Limitations come from the difficulty to treat the electron correlation in an anionic system, the need to combine continuum and discrete states, and the high number of degrees of freedom, which make the numerical calculation very cumbersome.
Among the most popular computational methods for describing temporary anions , one can find a broad class of methods that compute the electron attachment energies, such as the R-matrix , the so-called empirical correlation method , the Schwinger multichannel method , or the stabilization method . Although these methods provide valuable results, they rely either on cumbersome
calculations or on empirical methods.
Here, we propose an efficient approach to predict the resonance energies of the electron attachment using a TDDFT calculation and two different atomic basis sets6: a large basis set to compute the vertical electron affinity, and a smaller one to calculate the excitation energy of the anion. Doing so one computes the relevant resonant attachment energies of the electron without intruder states from the continuum discretized due to the finite size of the simulation box. Benchmarks have been performed over 18 molecules and 53 resonances and show good agreement with experimental data.

[1] Sommerfeld T. et al, J. Phys. Chem. A 115 6675-6682 (2011) 
[2] Gorfinkiel J. D. et al, J. Phys. B. 35 543 (2002)
[3] Modelli A. et al, Chem. Phys. 286 165-172 (2003)
[4] Takatsuka K. et al, Phys. Rev. A 24 2473 (1981)
[5] Falcetta M. F. et al, Chem. Phys. 482 239-243 (2017)
[6] Thiam G., Rabilloud F., J. Phys. Chem. Lett, 12, 41, 9995–10001(2021)


### Benoit Braida (LCT, Paris) 

**Valence Bond alternative yielding compact and accurate wave functions for challenging excited states. Application to ethylene, ozone and sulfur dioxide**

Calculating excited states properties and transition energies can be a tough task even for small molecules. If the ground and excited states are of different symmetries, state-specific calculations can be performed, but it is essential that the correlation energies be calculated in a balanced way for both states. This can be difficult when the two states have very different demands of dynamic electron correlation, for instance with ionic excited states displaying a lot of dynamic charge fluctuation. If the two states are of like symmetry, a state-averaged treatment can be used, but the accuracy is penalized by the necessity for both states to share the same orbital set, which is a compromise that cannot be optimal for either of the two states. 
It will be shown that these two difficulties can be resolved by the breathing-orbital valence bond method (BOVB), which exerts a direct approach to both static and dynamic electron correlations, made possible by the freedom to deal with non-orthogonal orbitals. The dynamic correlation is fully included right at the orbital optimization step, by allowing each VB structure to have its specific set of orbitals, and, in the newly developed state-averaged BOVB method, by also having the unique advantage to be free from the constraint for the different states to share the same unique set of orbitals. 
This approach is tested on the challenging 11B1u ionic state of ethylene, and to the five lowest-lying singlet states of ozone and sulfur dioxide, among which the challenging 11B2 and 21A1 states. In all cases, it will be shown that the calculated vertical energies are close to the experimental values when available, and at par with the most sophisticated calculations in the molecular orbital framework, despite the extreme compactness of the BOVB wave functions (no more than 4-9 valence bond structures in all cases). Finally, the description of the excited states also come out to be insightful, and displays some important, albeit unexpected, Lewis structures. 


### Pepijn Demol (KU Leuven, Leuven)

**Bogoliubov coupled cluster theory for open-shell nuclei**

The objective of the so-called ab initio approach to nuclear structure is to provide an accurate and universal description of nuclear systems from first principles [1]. In this context, solving the many-body Schrödinger equation requires systematically improvable many-body methods. Over the past 20 years, the development of novel expansion methods displaying a mild computational scaling with systems size have allowed access to mid-mass closed-shell nuclei. Such methods typically expand the exact ground-state wave-function around a reference/unperturbed Slater determinant and include correlations through elementary particle-hole excitations. This can be obtained from perturbative techniques [2] or from non-perturbative approaches such as coupled-cluster (CC) theory [3]. While closed-shell nuclei are well under control, the extension to open-shell nuclei remains a major challenge. 
Only very recently, a novel many-body method coined as Bogoliubov coupled cluster (BCC) theory [4] has been formulated that extends the standard coupled cluster scheme to singly open-shell nuclei. This is achieved by breaking particle-number symmetry of the unperturbed state as a way to already incorporate crucial static correlations into it. In my talk I will present recent results obtained for the ground-state of oxygen isotopes based on nuclear interaction models derived from chiral effective field theory. 
Once fully implemented, the non-perturbative (equation-of-motion) BCC method will allow for high-precision ab initio calculations of ground and excited states in medium-mass nuclei. 

[1] H. Hergert, Front. Phys. 8, 379 (2020)
[2] A. Tichai, R. Roth, T. Duguet, Front Phys. 8, 164 (2020)
[3] G. Hagen, T. Papenbrock, M. Hjort-Jensen, D. J. Dean, Rep. Prog. Phys. 77, 9 (2014)
[4] A. Signoracci, T. Duguet, G. Hagen, G. Jansen, Phys. Rev. C 91, 064320 (2015)


### David Lauvergnat (ICP, Orsay)

**Quantum Dynamics with a Smolyak scheme: numerical developments and applications**

When solving the time-dependent or time-independent Schrödinger equations associated to the atomic motions, the major bottleneck is the size of the direct-product basis set or grid which increases exponentially as a function of the number of degrees of freedom, n. All the usual numerical techniques (use of symmetry, clever selection of coordinates, separation of motions, basis set and grids adapted to model Hamiltonians, contraction of basis set and grids ...) fail to attenuate this exponential scaling. A way to overcome this difficulty is to perform a multidimensional basis function selection in terms of excitations as for vibrational-SCF or VSCF methods. However, when a multidimensional grid is required, the exponential scaling is still present.
In quantum dynamics, Avila and Carrington [2-5] and ourselves [6-9] were pioneers in developing efficient implementations to study the vibrational energy levels of molecules [6- 9] or reactive collisions. [9] Here, we will show that it is possible to apply this Smolyak scheme to large molecule (n>20) and also to extend it to wave packet propagation. Furthermore, with a system/bath separation, one can deal with about 100 degrees of freedom.

[1] S. A. Smolyak Soviet Mathematics Doklady, 4 (1963) 240
[2] G. Avila and T. Carrington, J. Chem. Phys., 131 (2009) 174103
[3] G. Avila and T. Carrington, J. Chem. Phys. 134 (2011) 054126
[4] G. Avila and T. Carrington, J. Chem. Phys. 135 (2011) 064101
[5] G. Avila and T. Carrington, J. Chem. Phys. 139 (2013) 134114
[6] D. Lauvergnat and A. Nauts, PCCP 12 (2010) 8405
[7] D. Lauvergnat and A. Nauts, Spectrochim. Acta Part A 119 (2014) 18
[8] A. Powers, Y. Scribano, D. Lauvergnat, E. Mebe, D.M. Benoit, Z. Bačić, J. Chem. Phys. 148 (2018).
[9] Lucien Dupuy, David Lauvergnat, and Yohann Scribano, Chem. Phys. Letter, to be published

### Antoine Bienvenu (LCT, Paris) 

**Partition Monte-Carlo : Reducing Fluctuation Scaling in Large Systems**

 For an ab-initio calculation on a N-particle electronic system, Variational Monte Carlo methods provide a result with a time scaling O(N³). However, they suffer from numerical uncertainties increasing with system size, caracterised by their variance which generally scales as O(N). The traditional compensation method transfers the uncertainties onto the simulation time, in order to obtain a given level of accuracy, resulting in an effective O(N⁴) scaling. We present a new control variate method employing the zero-variance principle and a partition of the system which allows us to reduce the variance for a limited increase in computation time, by O(N) on metallic systems and up to O(N²) on systems with a finite correlation length, and will present results on the example of the Hubbard model.

### Fabris Kossoski (LCPQ, Toulouse)

**Exploiting the seniority number in calculations of molecular excited states**

In electronic structure theory, configuration interaction and coupled 
cluster methods are usually built hierarchically based on the truncation 
of the excitation degree from a given reference determinant. However, 
one can devise new truncation schemes that further incorporates the 
concept of seniority (number of unpaired electrons of a determinant). In 
the first part of this contribution, I will present our recently 
developed state-specific orbital-optimized pair coupled cluster doubles 
model, where the excitation operator is restricted to double excitations 
with seniority zero. Instead of relying on the equation-of-motion 
formalism, this approach targets both ground and excited states within 
the coupled cluster formalism, thus promising a more balanced 
description of correlation effects. Its accuracy has been assessed 
against alternative methodologies and full configuration interaction 
results, for a set of doubly-excited states of small molecules. Our 
model provided very reliable excitation energies, at a fraction of the 
computational cost of alternative methodologies. I will further 
illustrate how it compares with the much more expensive doubly-occupied 
configuration interaction method, the crucial role of orbital 
optimization, and the differences between projective and variational 
formulations. In the second part of the contribution, I will present a 
new hierarchy of configuration interaction methods which are based on 
both the excitation degree and the seniority number, as well as initial 
results for ground state potential energy curves and excitation 
energies.

### Timothy Daas (Vrije Universiteit, Amsterdam)

**Noncovalent interactions from models for the Møller-Plesset adiabatic connection**

The adiabatic connection (AC) that has as weak-interaction expansion the Møller-Plesset (MP) perturbation series has been recently shown to have a large coupling-strength expansion in terms of functionals of the Hartree-Fock density [1,2]. Based on these findings, in this work [3] we introduce a new class of functionals that approximate directly the MP AC by interpolating between MP2 and the large-coupling strength limit, which is size consistent for fragments with a non-degenerate ground state [4]. These functionals have the same cost as double hybrids and greatly reduce the large MP2 errors for typical pi-stacking complexes (e.g., benzene-pyridine dimers) and for the L7 dataset. Furthermore, they are also competitive with state-of-the-art dispersion enhanced functionals and can even significantly outperform them for a variety of datasets, such as CT7, DI6 and L7.

[1]M. Seidl, S. Giarrusso, S. Vuckovic, E. Fabiano, P. Gori-Giorgi, J. Chem. Phys., 149, 241101 (2018)
[2]T. Daas, J. Grossi, S. Vuckovic, Z. Musslimani, D. Kooi, M. Seidl, K. Giesbertz, P. Gori-Giorgi, J. Chem. Phys., 153, 214112 (2020)
[3]T. Daas, E. Fabiano, F. Della Sala, P. Gori-Giorgi, S. Vuckovic, J. Phys. Chem. Lett., 12, 4867-4875 (2021)
[4]S. Vuckovic, P. Gori-Giorgi, F. Della Sala, E. Fabiano, J. Phys. Chem. Lett., 9, 3137-3142 (2018)

### Diata Traore (LCT, Paris)

**Density-based basis set correction method for molecular properties**

The density-based basis-set correction method [1], consisting in correcting the basis-set incompleteness error of wave-function calculations using a density functional, has proved its efficiency to speed up the convergence of ground-state energies [2, 3]. Here, we extend the basis-set correction method to calculations of molecular properties, starting with dipole moments. We develop two strategies: (1) configuration-interaction calculations where the basis-set correction is included self-consistently [4], and (2) coupled-cluster calculations where the basis-set correction is estimated non-self-consistently using numerical differentiation of the energy with respect to an electric field. Systematic tests have been performed on a set of molecules.

[1] E. Giner, B. Pradines, A. Ferte, R. Assaraf, A. Savin and J. Toulouse, J. Chem. Phys. 149, 194301 (2018).
[2] P.-F. Loos, B. Pradines, A. Scemama, J. Toulouse and E. Giner, The Journal of Physical Chemistry Letters 10, 2931 (2019). [3] E. Giner, A. Scemama, P.-F. Loos and J. Toulouse, The Journal of Chemical Physics 152, 174104 (2020).
[4] E. Giner, D. Traore, B. Pradines and J. Toulouse, The Journal of Chemical Physics 155, 044109 (2021).

### Jonas Feldt (LCT, Paris)

**Efficient Quantum Monte Carlo Simulations with Large Atomic Numbers**

Quantum Monte Carlo (QMC) methods use a stochastic approach to solve the Schrödinger
equation. Their scaling with the system size considering the computational costs is very
favourable and a great flexibility in the choice of the wave function allows to efficiently treat
both dynamical as well as static correlation. This makes QMC methods for instance particu-
larly useful for the description of excited states.1;2
However, the steep scaling with the atomic number Z is a remaining challenge. Different
regions in space exhibit different time scales and contribute to a varying degree to the overall
variance in a Variational Monte Carlo algorithm. This leads to large inefficiencies as the
same computational effort is spend on all regions. We propose a Monte Carlo scheme which
exploits that core regions are physically independent in a molecule to almost remove their high
variance contribution to the numerical cost.3 The method relies on efficiently subsampling the
core regions using independent sidewalks which can be understood as constructing on the fly
an exact stochastic effective core potential. Results are presented on atoms, alkane chains and
clusters of silicons which display a gain in numerical efficiency between one and two orders of
magnitude.
The extension to more advanced projector Monte Carlo methods is being explored.

[1] J. Feldt, C. Filippi in Quantum chemistry and dynamics of excited states methods and applications, Wiley 2020, 247276.
[2] M. Dash, J. Feldt, M. Saverio, A. Scemama, C. Filippi, JCTC 2020, 15, 48964906.
[3] J. Feldt, R. Assaraf, JCTC 2021, 17, 13801389.

### Leo Chaussy (iSm2, Marseille)

**Benchmark on cobalt systems relevant for reactivity**

The high cost and low availability of second- and third-row transition metals push more and more researchers to explore the chemistry of the first-row transition metals. Their use in catalysis needs a fine understanding of their electron properties, which could be achieved by theoretical approaches. Nevertheless, the computational study of first-row transition complexes and their reactivity rises nu- merous questions, as several electronic states could be accessible.
Among known reactivities, cobalt complexes have been used for more than ten years to perform cycloaddition reactions. Recently, in our group, a [CpCo] mediated chemodivergent cycloaddition has been studied.[1] General mechanisms proposed for this kind of reactivity usually rely on den- sity functional theory calculations (employing hybrid functionals) and involve a two-state reactivity. However, and as expected, for some of the key intermediates, a pure density functional would predict a more stable singlet state, while a hybrid functional, such as B3LYP, would predict a more stable triplet state. We used wavefunction based methods on a series of model cobalt and rhodium sys- tems to compute singlet-triplet splittings in order to benchmark the performances of common density functionals in our mechanistic studies. This also represents an opportunity to gain methodological insights on the computational treatment of organometallic catalysts. Using correlated wavefunction methods such as MRCI and CASPT2/RASPT2 on systems of increasing size, we assess the influence of basis set selection, active space and restrictions to the CI expansion or semi-core correlation on the relative spin state energetics.[2, 3] CCSD(T) and BCCD(T) calculations were also performed to check the extent of their reliability in treating transition metal complexes with a possibly multicon- figurational wavefunction. [4, 5] In the process, we aim at finding a suitable cost/accuracy balance to treat systems of chemical interest, select the appropriate density functional and assess the validity of proposed mechanisms.

[1] M. Delorme, A. Punter, R. Oliveira, C. Aubert, Y. Carissan, J.-L. Parrain, M. Amatore, P. Nava and L. Commeiras, Dalton Trans., 2019, 48, 15767–15771.
[2] K. Pierloot, Q. M. Phung and A. Domingo, J. Chem. Theory Comput., 2017, 13, 537–553.
[3] Q. M. Phung, M. Feldt, J. N. Harvey and K. Pierloot, J. Chem. Theory Comput., 2018, 14, 2446–2455.
[4] M. Radon ́, Phys. Chem. Chem. Phys., 2019, 21, 4854–4870.
[5] G. Drabik, J. Szklarzewicz and M. Radon ́, Phys. Chem. Chem. Phys., 2021, 23, 151–172.

### Leo Gaspard (LCPQ, Toulouse)

**Timescale of local moment screening across and above the Mott transition**

In a material’s phase diagram the types of realized long-range orders typically correspond to instabilities in static response functions. In correlated systems, however, key phenomena crucially depend on dynamical processes too: In a Mott insulator, the electrons’ spin moment fluctuates in time, while it is dynamically screened in Kondo systems. Here, we introduce a timescale tm characteristic for the screening of the local spin moment and demonstrate that it fully characterizes the dynamical mean-field phase diagram of the Hubbard model: The retarded magnetic response delineates the Mott transition and provides a new perspective on its signatures in the supercritical region above. We show that tm has knowledge of the Widom line and that it can be used to demarcate the Fermi liquid from the bad metal regime. Additionally, it reveals new structures inside the Fermi liquid phase: First, we identify a region with preformed local moments that we suggest to have a thermodynamic signature. Second, approaching the Mott transition from weak coupling, we discover a regime in which the spin dynamics becomes adiabatic, in the sense that it is much slower than valence fluctuations. Our findings provide resolution limits for magnetic measurements and may build a bridge to the relaxation dynamics of non-equilibrium states 

### Louis Garrigue (CERMICS, Paris)

**The inverse problem of Density Functional Theory**

 The map from electric potentials to the one-body density of the ground state is important in the quantum many-body theory, because of its injectivity. Considering Density Functional Theory as an inverse problem, we will present the mathematical specificities of its dual formulation, and show how to construct potentials producing some target one-body density, in ground and excited states cases.[1]

[1] https://arxiv.org/abs/2101.01127


### Michael Herbst (Aachen, Germany)

**A robust and efficient line search for self-consistent field iterations**

In state-of-the-art self-consistent field algorithms a sizeable number
of computational parameters, such as damping, mixing/preconditioning
strategy or acceleration methods, need to be chosen. This is usually
done empirically, which bears the risk to choose parameters
non-optimally. As a result algorithms can feature a limited reliability
for challenging systems, which implies an increased failure rate and
thus an elevated requirement in human time to setup and supervise
calculations for such systems.

With respect to the setting of plane-wave discretisations and Kohn-Sham
density-functional theory we propose a novel adaptive damping algorithm
in this work, which uses a backtracking line search to automatically
adjust the damping in each SCF step. This line search is based on a
theoretically sound, accurate and inexpensive model for the energy as a
function of the damping parameter. In contrast to usual SCF schemes, the
resulting algorithm is fully automatic and does not require the user to
select a damping. We successfully apply it to a wide range of
challenging systems, including elongated supercells, surfaces and
transition-metal alloys. This includes cases where we deliberately
select algorithmic parameters in a suboptimal way demonstrating our
adaptive damping approach to overall increase SCF robustness.

### Robinson Outerovitch (CEA/DAM/DIF, Arpajon)

**Calculation and effect of interaction parameters on oxygen p orbitals in oxides, examples of UO2 and TiO2**

The standard method for solid state physics ab initio calculation is the Density Functional Theory (DFT). However, the most used functionals such as LDA or GGA fail to give a correct description of the density of states and structural parameters of strongly correlated systems. The DFT+U improves this description by explicitly applying electronic interaction inside specific orbitals.
This method is extensively used in f and d orbitals of transition metals, lanthanides, actinides and their oxides compounds. However, the interaction effects occurring in the p orbitals of the oxide have been shown to play an important role in the density of states and structural parameters of some of those systems. [1, 2, 3]
In this presentation, we use our generalized cRPA implementation (as described in [4] and based on [5]), to calculate the screened interaction on both metal (d or f) and oxygen (p) orbitals . We also discuss the influence of those interactions on density of state and structural parameters on two widely studied systems, UO2 and TiO2. We show that due to the hybridization of p electrons the electronic occupations have to be carefully calculated in order to ensure physical results.

[1] I. A. Nekrasov, M. A. Korotin, and V. I. Anisimov, “Coulomb interaction in oxygen p-shell in LDA+U method and its influence on calculated spectral and magnetic properties of transition metal oxides,” arxiv, 2000.
[2] L. A. Agapito, S. Curtarolo, and M. Buongiorno Nardelli, “Reformulation of DFT + U as a Pseudohybrid Hubbard Density Functional for Accelerated Mate- rials Discovery,” Phys. Rev. X, vol. 5, p. 011006, Jan. 2015.
[3] O. K. Orhan and D. D. O’Regan, “First-principles Hubbard U and Hund’s J cor- rected approximate density functional theory predicts an accurate fundamental gap in rutile and anatase TiO2,” Phys. Rev. B, vol. 101, p. 245137, June 2020.
[4] J.-B. Mor ́ee, R. Outerovitch, and B. Amadon, “First-principles calculation of the Coulomb interaction parameters U and J for actinide dioxides,” Phys. Rev. B, vol. 103, p. 045113, Jan. 2021.
[5] P. Seth, P. Hansmann, A. van Roekeghem, L. Vaugier, and S. Biermann, “Towards a First-Principles Determination of Effective Coulomb Interactions in Correlated Elec- tron Materials: Role of Intershell Interactions,” Phys. Rev. Lett., vol. 119, p. 056401, Aug. 2017.

### Tan Nguyen  (ISCR, Rennes)

**Many-body perturbative calculations for multi-excitons in perovskite nanocrystals**

Perovskite nanocrystals (NCs) are among the most fashionable names nowadays in the field of colloidal synthesis owing to their superior photoluminescence quantum yield and blinking-free properties, which make them promising materials for both classical [1,2] and quantum light sources [3,4]. Their brightness and sub-nanosecond radiative decay originates from the inherent correlation effects [5,6]. The many-body Coulomb interaction has generally been studied for semiconductor quantum dots [7,8]. Perovskites, as a consequence of the unique properties of their dielectric functions, possess enhanced Coulomb interaction between the charge carriers [9]. This leads to large binding energies of multi-exciton systems such as trion and biexciton in these NCs or the sizable splitting in the fine structure of single exciton states. Considering each NC as an artificial atom under the envelope function approximation, this problem of correlation effects can be approached at first by using second-order many-body techniques as outlined in Ref. [10]. This offers an elegant and efficient method that provides qualitative results for the trion and biexciton binding energies [11]. In going beyond the second-order description, configuration interaction can be employed to include the correlation energies between the various charge carriers in a more holistic manner.

[1] Kovalenko et al., Properties and potential optoelectronic applications of lead halide perovskite nanocrystals.  Science 358, 6364, 745-750, 2017.
[2] Raino et al., Single Cesium Lead Halide Perovskite Nanocrystals at Low Temperature: Fast Single-Photon Emission, Reduced Blinking, and Exciton Fine Structure. ACS Nano 10, 2, 2485–2490, 2016.
[3] Utzat et al., Coherent single-photon emission from colloidal lead halide perovskite quantum dots. Science, 363(6431):1068–1072, 2019.
[4] Tamarat et al., The dark exciton ground state promotes photon-pair emission in individual perovskite nanocrystals. Nature Communications. 11, 6001, 2020.
[5] Becker et al., Bright triplet excitons in caesium lead halide perovskites. Nature, 553(1):189–193, 2018.
[6] Tamarat et al., The ground exciton state of formamidinium lead bromide perovskite nanocrystals is a singlet dark state. Nature Materials 18, 717–724, 2019.
[7] M. Combescot and R. Combescot, Optical stark effect of the exciton: Biexcitonic origin of the shift. Phys. Rev. B, 40:3788–3801, 1989.
[8] Rontani et al., Coulomb correlation effects in semiconductor quantum dots: The role of dimensionali-ty. Phys. Rev. B 59, 10165, 1999.
[9] Even et al., Analysis of Multivalley and Multibandgap Absorption and Enhancement of Free Carriers Related to Exciton Screening in Hybrid Perovskites. J. Phys. Chem. C, 118, 11566−11572, 2014.
[10] I. Lindgren and J. Morrison, Atomic Many-Body Theory. Springer-Verlag, 1982.
[11] Nguyen et al., Calculation of the biexciton shift in nanocrystals of inorganic perovskites. Phys. Rev. B, 101. 125424, 2020.

### Abdallah Ammar (LCPQ, Toulouse)

**Iterative CI wavefunction optimization using a similarity-transformed Hamiltonian and Variational Monte Carlo** 

Realizing full Configuration Interaction (CI) for a one-electron basis sets is, in general, not possible
in practice. One needs to truncate the CI wavefunction according to some protocol. To recover the
remaining correlation energy, one can explicitly include correlations in the wavefunction or in the
Hamiltonian.
In the framework of the transcorrelated approach, the similarity-transformed Hamiltonian is given
by eH
  J 􀀀1HJ where J is a correlation operator. Although eH
is not Hermitian, it allows to
e ectively incorporate dynamical correlation e ects, with relatively small one-electron basis sets.
Formally, we can write the wavefunction as     J   where   =
PNdet
I=1 DI . The Schrdinger
equation in this case is written as
In this work, we develop an iterative method to optimize large CI wavefunctions in the presence
of a Jastrow correlation factor, optimized at the Hartree-Fock level. The Slater-determinant part   is
modi ed at each iteration by a symmetric dressing of H with the dressing elements
Moreover, the non-hermeticity of the transcorrelated Hamiltonian is dressed by applying a symmetric
dressing of the Hamiltonian. The dressing elements, which contain two- and three-electrons integrals,
are sampled in a Variational Monte Carlo (VMC) calculation.

### Saad Yalouz (LCQ, Strasbourg)

**Describing conical intersections with near term quantum computers**

In quantum computing, solving the electronic structure problem is considered as the “killer application” for near term quantum computers. To treat this problem, a great focus has been paid to hybrid-classical-quantum algorithms such as the well-known “Variational-Quantum-Eigensolver” (VQE). While VQE has been proficiently applied to find electronic eigenstates/energies of various small molecules, using this approach on more complex systems is still a genuine challenge especially when peculiar spectral features such as conical intersections are present.
In nature, conical intersections play a keyrole in many prominent reactions. For instance, in the process of vision: the retinal molecule is known to undergo a photoisomerisation mediated by a non-radiative relaxation through a conical intersection. In such a situation, characterizing the phenomenon requires to precisely describe the shape of the conical intersection, with both qualitative and quantitative high-level treatments. This makes it a difficult target to current quantum algorithms, such as VQE.
Motivated by this problem, we recently introduced a new quantum algorithm [1] called the “State-Averaged Orbital-Optimized VQE” (SA-OO-VQE) designed to treat on an equal footing degenerate states on near term quantum computers. In this talk, we introduce the theory of SA- OO-VQE and illustrate how it works on the formaldimine molecule (a minimal model for the retinal with a similar conical intersection). Furthermore, we will introduce new extensions to the SA-OO- VQE algorithm recently developed to estimate nuclear gradients and non-adiabatic couplings out of the quantum algorithm [2]. We show that SA-OO-VQE is able to qualitatively and quantitatively reproduce the molecule’s conical intersection. We will also show that the algorithm can be used in a geometry optimization process to find the minimal energy conical intersection of the molecule.

[1] S. Yalouz, B. Senjean, J. Gu ̈nther, F. Buda, T. E. O’Brien, and L. Visscher, A state-averaged orbital- optimized hybrid quantum–classical algorithm for a democratic description of ground and excited states, Quantum Science and Technology 6, 024004 (2021).
[2] S. Yalouz, E. Koridon, B. Senjean, B. Lasorne, F. Buda, and L. Visscher, Analytical nonadiabatic couplings and gradients within the state-averaged orbital-optimized variational quantum eigensolver, arXiv preprint arXiv:2109.04576 (2021).

### Thierry Deutsch (CEA, Grenoble)

**New formalism for the exact calculation of total energies and associated electronic state of many-body interactions with complexity n^4**

In this talk, I intend to show a new formalism that solves the famous many-body problem of quantum mechanics with a complexity varying as a function of n⁴ where n is the number of states. There was already an object, the reduced two-body density matrix (2-RDM) that had this complexity but for it to be a quantum state with N electrons, a gigantic number of conditions must be taken into account.
This formalism should considerably reduce the computation time avoiding the exponential complexity of the current exact methods.

Based on anti-commutativity relations, we show that we can construct a class of mathematical objects that are isomorphic to many-body wavefunctions but have the advantage of being compactable. Thanks to this new formalism, we show that the 2-RDM of the wavefunctions solutions of a two-body interaction Hamiltonian can be represented exactly thanks to this new set of mathematical objects. We will give also a new geometric interpretation of the 2-RDM in the space of these new mathematical objects.
We will develop the Lagrangian, the corresponding Euler-Lagrange equations and illustrate with numerical examples.

[1] Exact solution of the many-body problem with a O(n6) complexity, arXiv:2111.15281 [quant-ph]


### Xiang Yuan (PhLAM, Lille) 

**Assessing MP2 frozen natural orbitals in relativistic correlated electronic structure**

The O(N6) high computational cost is a bottleneck preventing performing Coupled-Cluster (CC) on large systems, particularly when employing 4-component based relativistic Hamiltonians, for which in practice one often uses uncontracted basis set generating large virtual molecular orbital (VMO) spaces.
The canonical Hartree-Fock (HF) orbitals are not the most compact representation for post HF method. Alternative, using natural orbitals is an efficient way to reduce the orbital space while retaining accuracy. We therefore implemented the MP2 frozen natural orbital (FNO) method [1] in the Exacorr code [2], with the particularity that our implementation can generate both complex and quaternion FNOs, and also express these in AO basis. It also allows us to obtain CCSD natural orbitals on AO basis, which can be subsequently used in analysis.
We have investigated the orbital truncation errors for both correlation energy (at CCSD(T) level) and molecular properties (at CCSD level) such as the electric field gradients at the nuclei (EFGs ), dipole and quadrupole moments for hydrogen halides HX (X=F, Cl, Br, I, At, Ts), and parity violation energy shift for the H2X2 systems (X= O, S, Se, Te, Po). We find that using FNOs accelerates the convergence of the correlation energy in a roughly uniform manner across the periodic table and that, with VMO spaces truncated to around half of the complete ones, we obtain reliable estimates for both energies and molecular properties in the complete VMO spaces.

[1] T. L. Barr, E. R. Davidson, Phys. Rev. A 1970, 1, 644; A. G. Taube, R. J. Bartlett, J. Chem. Phys. 2008, 128, 164101
[2] J. V. Pototschnig, A. Papadopoulos, D. I. Lyakh, M. Repisky, L. Halbert, A. S. P. Gomes, H- J Aa. Jensen, L. Visscher, J. Chem. Theory. Comput. 2021, 17, 5509
