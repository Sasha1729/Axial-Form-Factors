# Nucleon Axial Form Factors with Padé Approximents

Project Mentor: Dr. Sergi Gonzalez-Solis, Los Alamos National Laboratory

Working Group Members: 

- Ángel Reyna-Cruz, Instituto Técnológico y de Estudios Superiores de Monterrey
- Janna Goodman, Cornell University
- Sahaana Vijay, Ashoka University

## Overview
Direct experimental measurements of the nucleon axial-vector form factor are difficult to perform due this is only probed
through the weak current, and the experiments that constrain the form factor shape are limited to low-statistics
neutrino-nucleus scattering with significant nuclear effects, or by model-dependent corrections in pion electroproduction
determinations. Its theoretical description, often characterized by a dipole function, has attracted a lot of
current quasielastic neutrino-nucleon scattering cross section $\nu_{\mu}n\to\mu p$ at low [1, 2] and high [3] neutrino energies, 
between results from neutrino-nucleon scattering cross section and results based on the analysis of pion production data, and 
between the latter and recent Lattice QCD predictions [5, 6]. Among the possible effects causing this discrepancy, we will investigate 
perhaps the most simplest possibility: that the dipole parametrization incommon use is overly constrained. Such possibility 
seems natural in views of the failure of the usual dipole parametrization in providing a clear description of electron 
scattering data for the vector form factor. In our opinion, the election of the dipole ansatz lacks of solid theoretical 
grounds and induces a source of theoretical (or systematic) uncertainty difficult to control and quantify. If the 
reconstruction of the form factor obtained only from fits to experimental data is found to be inconsistent with the form 
factor shape derived by the Lattice collaborations, one would not be able to unveil whether experiment and theory disagree or
simple parametrizations are insufficient.

The axial-vector form factor of the nucleon, $F_{A}(q^2)$, encodes the relevant strong dynamics of the axial-vector current
coupled to a pair of nucleons and it is defined by the axial matrix element of the nucleon

$\langle N(p^{\prime})|J_{A}^{\mu a}|N(p)\rangle = \bar{u}(p^{\prime})\frac{\tau^{a}}{2}\gamma_{5}\left[\gamma^{\mu}F_{A}(t)+\frac{(p^{\prime}-p)^{\mu}}{2m_{N}}F_{P}(t)\right]u(p)$

where $\tau^{a}$ are Pauli matrices, $m_{N}$ is the nucleon mass and $q^{2}=(p^{\prime}-p)^{2}$ the four-momentum exchanged squared. $F_P$ is
the induced pseudoscalar form factor that can be related to the axial one using Partial Conservation of Axial Currents.

A commonly used parametrization of the nucleon axial-vector form factor that respects the expected $1/Q^{4}$ fall-off
at high-energies that perturbative QCD dictates [7, 8], is the dipole ansatz introduced by Lewellyn-Smith [9] to
explain the quasielastic neutrino-nucleon $\nu_{\mu}n\to\mu p$ scattering data (in the physical region of quasielastic neutrino
scattering $Q^{2}=-q^{2}\geq0$

$F_{A}(q^{2})=\frac{g_{A}}{1+q^{2}/m_{A}^{2}}\$

where $g_{A}=F_{A}(0)$ is a normalization constant that represents the strength of the interaction of the axial current with the
nucleon at zero momentum transfer $(Q^{2}=0)$ and $m_{A}$ is an effective (axial mass) parameter.

Different experiments have reported values for $m_{A}$ using two different methods. 
The resulting world average
values [10] extracted from neutrino scattering experiment, $m_{A}=1.026(21)$ GeV, and from analyses of pion electroproduction
data, $m_{A}=1.069(16)$ GeV, were found to be in good agreement until the late nineties.

Other more recent
results from neutrino scattering have been obtained by the K2K, $m_{A}=1.20(12)$ GeV [1], the MiniBoone, $m_{A}=1.35(17)$
GeV [2], the NOMAD, $m_{A}=1.05(6)$ GeV [3], collaborations. 
A graphical account of axial form factors of a single dipole
mass is shown in Fig. 1 (left plot) for the world average value $m_{A}=1.026(21)$ GeV (brown dotted curve) and the
MiniBoone result $m_{A}=1.35(17)$ GeV (black solid curve) as compared to experimental data from pion electro-production
(solid black circles) and the Lattice predictions. From this plot, we draw a first relevant observation that is that the
spread of axial form factors cannot be described by the dipole mass mA with the associated uncertainty in a statistically
significant way. Moreover, the experimental data and the Lattice results are found to be in sizable tension that seems
increase with $q^{2}$.  While the former seems to support values close to the aforementioned world average $m_{A}=1.026(21)$
GeV, larger values of $m_{A}$ i.e. $m_{A}\sim1.3-1.4$ GeV are preferred by the latter.

![image](https://github.com/Sasha1729/Nucleon-Axial-Form-Factors/assets/129873515/dab42b12-4019-44b6-a1c7-476bc50511c2)
*Fig 1: (Left) Normalized ($F_{A}(0)=1$) dipole representation of the nucleon axial-vector form factor compared to experimental data and 
Lattice predictions [4, 6]. (Right) Quasielastic muonic neutrino cross section measurements by the MiniBooNE [2] (black squares) and NOMAD [3] 
(gray squares) collaborations.*

On the other hand, quasielastic neutrino-nucleus scattering cross section measurements from the NOMAD collaboration at high 
neutrino energy $E_{\nu}$ [3], going from 3 to 100 GeV, prefers a dipole mass on the lower side of the reported values, 
$m_{A}=1.05(6)$ GeV. However, this value fails in accommodating the low-energy results of MiniBoone [2] which, in turn, favors a
larger axial mass, $m_{A}=1.35(17)$ GeV, as it can be seen in Fig. 1 (right plot) where the two data sets are shown. One thus
faces the problem on what the axial dipole mass one should objectively prefer.

A possible cause that explains the disagreement between different experiments, and between some experiments
and the Lattice predictions, in the central values of $m_{A}$ might be due to shortcomings inherent to the election of the
dipole ansatz that leads uncertainties difficult to quantify. The dipole function can only arise from approximating the
spectral density with two degenerate narrow resonances with residues of equal magnitude and opposite signs.
Although it respects the high energy scaling expected from perturbative QCD, there is no solid reason to believe that
the functional $Q^{2}$ dependence that this one-parameter model fit to data, with scaling effects that take place well outside
the energy window at accessible neutrino scattering experiments, will be a precise description of the physics at highenergies.
Moreover, this model fit to data introduces a tight (an unnatural) artificial bias connecting high-and-low
regions of Q2. 

In this work we propose to use Padé approximants as a tool to interpret these scattering data in a
largely model-independent way in order to shed light on the aforementioned discrepancy.

## References

[1] R. Gran et al. [K2K], Phys. Rev. D 74 (2006), 052002 [arXiv:hep-ex/0603034 [hep-ex]].

[2] A. A. Aguilar-Arevalo et al. [MiniBooNE], Phys. Rev. D 81 (2010), 092005 [arXiv:1002.2680 [hep-ex]].

[3] V. Lyubushkin et al. [NOMAD], Eur. Phys. J. C 63 (2009), 355-381 [arXiv:0812.4543 [hep-ex]].

[4] V. Bernard, N. Kaiser and U. G. Meissner, Phys. Rev. Lett. 69 (1992), 1877-1879

[5] C. Alexandrou, M. Constantinou, K. Hadjiyiannakou, K. Jansen, C. Kallidonis, G. Koutsou and A. Vaquero Aviles-Casco,
Phys. Rev. D 96 (2017) no.5, 054507 [arXiv:1705.03399 [hep-lat]].

[6] R. Gupta, Y. C. Jang, H. W. Lin, B. Yoon and T. Bhattacharya, Phys. Rev. D 96 (2017) no.11, 114503 [arXiv:1705.06834
[hep-lat]].

[7] S. J. Brodsky and G. R. Farrar, Phys. Rev. D 11 (1975), 1309

[8] C. E. Carlson and J. L. Poor, Phys. Rev. D 34 (1986), 1478

[9] C. H. Llewellyn Smith, Phys. Rept. 3 (1972), 261-379

[10] V. Bernard, L. Elouadrhiri and U. G. Meissner, J. Phys. G 28 (2002), R1-R35 [arXiv:hep-ph/0107088 [hep-ph]].
