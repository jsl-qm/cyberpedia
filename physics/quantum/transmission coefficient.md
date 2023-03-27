step potential ($L=\infty$), potential barrier ($L=a$), i.e. the potential is 0 until a potential step is reached of length $L$ at $x=0$

**Mental model: incident particle on potential step, reflection+transmission**
A free particle (described by a plane wave) with a given energy $E$ is moving to the right incident on a potential step with $V=V_{0}$ (assume $V_{0}$ to be constant and starting at $x=0$).
When the particle strikes the potential, the particle can either be reflected or transmitted (physical intuition following from cm).
No bound states exist hence we solve the transmission and reflection coefficients giving the probability for the particle to be transmitted or reflected given the energy of incident particle.

Reflection and transmission coefficients are defined as the ratio of [[probability current density]] of the reflected/transmitted wave over that of the incident wave:
$R=|\frac{j_{R}}{j_{I}}|$, $T=|\frac{j_{T}}{j_{I}}|$ where each probability current density is given by the one for a free particle with momentum $k$. Note $R+T=1$ this follows from [[conservation of probability]].
$R$ and $T$ give the probability for the incident particle to be reflected and transmitted, respectively.


Strategy:
1. Solve for the SE in each region of space+use the physical nature of the system to put some coefficients to zero ($\psi = Ae^{ikx}+Be^{-ikx}$ where $k=\frac{\sqrt{2m(E-V(x))}}{\hbar}$ over some region of space where $V(x)$ is constant)
2. Find the coefficients: use the continuity of the wavefunction and of its derivative
3. In both regimes of energy ($E\gt V_{0}$, $E\lt V_{0}$) Plot the transmission and reflection coefficients as fcn of $\frac{E}{V_{0}}$ 
	1. For $E \lt V_{0}$, the form of the wavefunction in the region where 

For particles incident on a potential step with energy $E \lt V_{0}$,  the wavefunction is exponentially decreasing, $\psi(x) \propto e^{-\beta x}$ where $\beta = \sqrt{\frac{2m}{\hbar^{2}}(V_{0}-E)}$, in the region $x\gt 0$ where $V=V_{0}$ so the particle has a non-zero probability of being found in this region. 
The transmission is complex, $Re(T)=0$, in this regime and $R=1\rightarrow T=1-R=0$, so there is no stready flow of probability current meaning that the particle cannot move to $x=\infty$, i.e. the particle cannot be found at large values of $x$. 
Since the current probability density in $x\gt 0$ is zero then it also has to 0 in $x\lt 0$, implying that the reflected current must cancel the incident current, $\mathbf{j}_{region\;I}= \mathbf{j}_{I} + \mathbf{j}_{R}=0$, resulting in $R=1$.
