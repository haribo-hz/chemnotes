#further #chem
linked to [[transition metal properties]], [[2.3.1 and 2.3.2 metallic bond]]

ligand field theory
- includes covalent aspects of bonding between metals and ligand

CFT
- assumes that the metal-ligand bond is ionic
- assumed that the ligands are negative point charges
i.e. the lone pairs on the ligands are essentially points at which there is a concentration of negative charge
- the structure or the specific atoms in the ligands are not considered

- consider the repulsion between negative point charges and d-orbitals

d-electron count: number of d electrons in d orbitals

coordinate covalent bonds forms between transition metal ion (Lewis acid) and ligand (lewis base)
#### crystal field splitting

spherical crystal field describes a situation where the transition metal is surrounded completely, equally by ligands, so all the orbitals are destabilised by the same amount, and experience the same amount of repulsion, and all go up to the same energy

as ligands approach from different directions, the degenerate $d$-orbitals interact differently. this causes a splitting of the energy level with the $t_{2g}$ set (triply degenerate) and $e_{g}$ set (doubly degenerate) behaving differently

![[cftsplitting.jpg]]

distributing a charge of −6 uniformly over a spherical surface surrounding a metal ion causes the energy of all five d orbitals to increase due to electrostatic repulsions, but the five d orbitals remain degenerate. 

this is also known as the **isotropic field**

Placing a charge of −1 at each vertex of an octahedron causes the d orbitals to split into two groups with different energies:

- $e_{g}$ set most direct repulsion: $d_{z^{2}}$ and $d_{x^{2}-y^{2}}$
- $t_{2g}$ set less repulsion: $d_{xy}$, $d_{xz}$, $d_{yz}$

- average energy of 5 $d$-orbitals are still the same as the spherical distribution

the energy between the two sets is known as $\Delta _{oct}$ for octahedral complexes

- according to the Aufbau principle, electrons are filled from lower to higher energy orbitals
- following Hund's rule, electrons are filled to have the highest number of unpaired electrons
	- the pairing of the electrons requires spin pairing energy
	- if the pairing energy is less than $\Delta_{o}$, then the higher energy orbital can fill
	- otherwise, the electron will go into the higher energy orbital due to stability

strong field ligands produce a large crystal field splitting
![[high spin vs low spin.png]]
splitting for a $d^{4}$ complex
left: low spin, strong field ligand, $\Delta _{o}>P$
right: high spin, weak field ligand, $\Delta_{o}<P$

spectrochemical series gives strength of ligands
![[spectrochemical-series.png]]

generally, the oxidation state and strength of ligands determine splitting

![[octahedral spatial consideration of d orbital interactions with negative point charges.png]]

the amount of energy the electrons have to gain determines the wavelength of electromagnetic radiation the complex will absorb

the spin state determines if the complex is paramagnetic or diamagnetic
- high-spin complexes are paramagnetic (many unpaired electrons)
- low-spin complexes are diamagnetic (few unpaired electrons)
##### tetrahedral complexes
![[comparison of cfse of octahedral and tetrahedral.png]]
note: $\Delta_{t}<\Delta_{o}$ because of weaker d-orbital-ligand interaction and decreased electrostatic interactions


calculating the magnetic moment of a given TM complex
$$\mu=\sqrt{ n(n+2) }\mu_{\text{B}}$$
where:
- $n$ is the number of unpaired electrons
- $\mu$ is the magnetic moment in units of $\mu_{\text{B}}$
- $\mu_{\text{B}}$ is a physical constant $9.274\times 10^{-24}\pu{ JT^{-1}}$

![[creation of square planar transition metal complex.png]]


square planar structures are okay for $d^{8}$ complexes, since the most energetic orbital is left empty, and all electrons are concentrated in lowest energy orbitals
- maximises CFSE
- okay for strong-field ligands
- disfavoured because of steric effect



crystal field splitting energy is the energy difference
$$
\Delta O_{\text{geometry}}
$$

- increasing central metal ion charge increase crystal field splitting energy because the lower energy set of d-orbitals is stabilised more than the higher energy set since they are closer to the nucleus


crystal field stabilisation energy is the overall energetic advantage from splitting
$$
CFSE=\Delta E=\Delta E_{\text{ligand field}}-E_{\text{isotropic field}}
$$

pairing energy is represented as $P$

depends on geometry, number of d-electrons, spin pairing energy, ligand character

for an octahedral complex:
- electrons in the more stable $t_{2g}$ subset is treated as contributing $-\frac{2}{5}\Delta_{o}$
- electrons in the higher energy $e_{g}$ subset is treated as contributing $+\frac{3}{5}\Delta_{o}$

the final answer is expressed as a multiple of the crystal field splitting parameter $\Delta_{o}$

for a tetrahedral complex:
- electrons in the less stable $t_{2g}$ subset is treated as contributing $+\frac{2}{5}\Delta_{o}$
- electrons in the more stable $e_{g}$ subset is treated as contributing $-\frac{3}{5}\Delta_{o}$

opposite of however many orbitals out of total is coefficient

high spin example:
What is the Crystal Field Stabilisation Energy for a high spin $d^{7}$ octahedral complex?
![[high spin d7 example.png]]

$$
\begin{flalign}
E_{\text{isotropic field}}&=7\times 0+2P=P\\
E_{\text{ligand field}}&= \left( 5\times-\frac{2}{5}\Delta_{o} \right)+\left( 2 \times \frac{3}{5}\Delta_{o} \right)+2P \\
&=-\frac{4}{5}\Delta_{o}+2P\\
CFSE&=-\frac{4}{5}\Delta_{o}&
\end{flalign}
$$

note that the pairing energy does not need to be calculated for high spin complexes since it is the same in the ligand field as well as the isotropic field

low spin example:
![[low spin d7 example.png]]

$$
\begin{flalign}
E_{\text{isotropic field}}&=7\times0+2P=P\\
E_{\text{ligand field}}&=\left( 6\times-\frac{2}{5}\Delta_{o} \right)+\left( 1\times \frac{3}{5}\Delta_{o} \right)+3P\\
&=-\frac{9}{5}\Delta_{o}+3P\\
CFSE&=-\frac{9}{5}\Delta_{o}+P
\end{flalign}
$$

pairing energy $P$ depends on the metal
varies between $200-400\pu{ kJ mol^{-1}}$


octahedral preference:
CFSE values can be calculated for non-octahedral ligand field geometries once d-orbital splitting is known and the electron configuration of the orbitals are known


the energies of these geometries can be compared to octahedral CFSE. this is called the octahedral site preference energy

e.g. for a tetrahedral complex, the ospe would be
$$
\begin{equation}
OSPE=CFSE_{(oct)}-CFSE_{(tet)}
\end{equation}
$$




hard acid-base interaction: mostly electrostatic
$$
\ce{F- > Cl- > Br- > I-}
$$
charge dense

soft acid-base interaction: mostly covalent
$$
\ce{I- > Br- > Cl- > F-}
$$
largest orbitals/most overlap


comment on the fact that $\ce{CuI(s)}$ ($\ce{Cu+}$ is a soft Lewis acid) and $\ce{CuF_{2}(s)}$ ($\ce{Cu^{2}+}$ is a hard Lewis acid) are stable compounds, whereas $\ce{CuF(s)}$ and $\ce{CuI_{2}(s)}$ are unknown

hard acids like hard bases, soft acids like soft bases