#chem #further
$+e=1.602\times{1}0^{-19}\pu{ C}$ represents charge on a nucleus
$-e$ is charge on electron
coulomb's law
$$
F=K \frac{q_{1}q_{2}}{r^{2}}
$$
where $K=\frac{1}{4\pi\epsilon_{0}}$, $q$ represents the charges of the objects, $r$ represents the distance
and $\epsilon_{0}$ is the electric constant

if the charges are $+e$ and $-e$ 

force between a proton and an electron

$$
F=\frac{e^{2}}{4\pi\epsilon_{0}r^{2}}
$$
potential energy of the electron
$$
V(r)=-\frac{dF}{dr}=-\frac{e^{2}}{4\pi\epsilon_{0}r}
$$

negative because it is bound to the proton

$$
\hat{H}\psi(x,y,z)=E\psi(x,y,z)
$$

the schrodinger equation cannot be solved in cartesian coordinates, as the variables cannot be separated

SE for hydrogen atom

$$
\left( -\frac{\bar{h}}{2m}\nabla ^{2}-\frac{e^{2}}{4\pi\epsilon_{0}\sqrt{ x^{2}+y^{2}+z^{2} }} \right)\Psi(x,y,z)=E\Psi(x,y,z)
$$
change of variables $\to$ spherical polar coordinates
$$
\begin{gather}
x=r\sin \theta \cos\phi \\
y=r\sin\theta \sin\phi \\
z=r\cos\theta
\end{gather}
$$

$$
\hat{H}\Psi(r,\theta,\phi)=E\Psi(r,\theta,\phi)
$$

can separate variables

solution:
$$
\Psi(r,\theta,\phi)=\overset{ \text{contains n \& l} }{ \underset{\text{radial}}{ R(r) } }\times \overset{ \text{contains l and ml} }{ \underset{\text{angular}}{ y(\theta,\phi) } }
$$

3 quantum numbers will be generated instead of 1 for [[particle in a box - solutions to the SE]]

$$
\begin{gather}
n=1,2,3,\dots&&\text{principle}\\
l=0,1,2,\dots,(n-1)&&\text{orbital angular momentum}\\
m_{l}=-l,-l+1,\dots,l-1,l&&\text{magnetic quantum number}
\end{gather}
$$

principle $\to$ main shell
orbital AM $\to$ subshell
magnetic quantum number $\to$ which orbital

radial

$$
R(r)=K\cdot(\text{polynomial})^{n-l-1}\cdot r^{l}\cdot e^{-r/na_{0}}
$$
where $a_{0}$ is the Bohr radius (the most probable value of $r$)

e.g. for hydrogen 1s, $n=1,l=0$


$$R(r)=2\left( \frac{1}{a_{0}} \right)^{3/2}\cdot e^{-r/a_{0}}$$

![[wavefunction of hydrogen 1s.png]]

note, square modulus of wavefunction is the probability density, the wavefunction by itself doesn't really have much of a physical representation

e.g. for hydrogen 3s, $n=3,l=0$

$$
R(r)=\frac{2}{3}\left( \frac{1}{3a_{0}} \right)^{3/2}\cdot\left( 3-\frac{6r}{3a_{0}}+2\left( \frac{r}{3a_{0}} \right)^{2} \right)\cdot e^{-r/3a_{0}}
$$

notice the coefficient of the denominator in the exponential term
notice that the wavefunction has a quadratic, so we expect it to touch 2 twice

![[wavefunction of 3s.png]]

radial nodes are when the wavefunction touch 0, when the wavefunction changes sign

angular
$$
y(\theta,\phi)=K\cdot(\sin\theta\text{ and/or }\cos\theta)^{l}\cdot e^{im_{L}\theta}
$$

complex wavefunctions

e.g. 1s $l=0,m_{L}= 0$
$$
y(\theta,\phi)=\frac{1}{\sqrt{ 4\pi }}=\text{constant}
$$

this means that electrons in the 1s orbital of the hydrogen atom has an equal chance of being found at any angle

e.g. p2 $l=1,m_{L}=0$
$$
y(\theta,\phi)=\sqrt{ \frac{3}{4\pi} }\cos\theta
$$

![[wavefunction of hydrogen p2.png]]

no $\phi$ dependence means nothing to do on rotation about $z$

so almost like a volume of revolution around the $z$ axis

only works for $m_{L}\not=0$ because otherwise, there would be an imaginary term
taking linear combinations of complex $\Psi\overset{}\longrightarrow{}$ gives real functions
$$
e^{\pm i\phi}=\cos\phi\pm i\sin\phi
$$


1s $n=1,l=0,m_{L}=0$
$$
\Psi=R\times Y=2\left( \frac{1}{a_{0}} \right)^{3/2}e^{-r/a_{0}}\times \sqrt{ \frac{1}{4\pi} }
$$

energy levels

$$
\begin{gather}
E_{n}=-\frac{R}{n^{2}}&&R=13.6\pu{ eV}&&1\pu{ eV}=1.6\times_{1}0^{-19}\pu{ J}
\end{gather}
$$

