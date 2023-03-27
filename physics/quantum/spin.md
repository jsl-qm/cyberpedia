## nature of spin
Spin can be thought of as the intrinsic [[angular momentum]] of a particle which is independent of the orbital degree of freedom. Spin variable live in a two-dimensional Hilbert space different than the Hilbert space describing the orbital degrees of freedom.
A particle can have spin $s\in\{0,\frac{1}{2},1,\frac{3}{2},2,...\}$.

Spin is angular momentum since its operator respect $$[\hat{S}_{i},\hat{S}_{j}]=i\hbar\varepsilon_{ijk}\hat{S}_{k}$$
where $i,j,k\in \{x,y,z\}$.
$\hat{\mathbf{S}}=(\hat{S}_{x},\hat{S}_{y},\hat{S}_{z})$

##### derivation commutation relation
Such commutation relations are found from applying a general infinitesimal rotation according to the law of combinations of rotations resulting in finding $\mathbf{J}=i\hbar\mathbf{J}\times \mathbf{J}$, thus $[\hat{J}_{i},\hat{J}_{j}]=i\hbar\varepsilon_{ijk}\hat{J}_{k}$. Then we find that the eigenvalues of $\mathbf{J}^{2}$ are $\{0,\frac{1}{2},1,\frac{3}{2},2,...\}$ whereas it is found that the eigenvalues of $\mathbf{L}^{2}$ are integral values. We conclude that there is another form of angular momentum different than the orbital angular momentum associated with the transformation of the components of a vector field. 
It follows that the eigenvectors of spin are characterized by the value of the magnitude of spin, $s$, and its projection on a direction of space (usually on the z-axis), $m$.
$$\hat{\mathbf{S}}^{2}\ket{sm}=\hbar^{2}s(s+1)\ket{sm}$$
$$\hat{S_{z}}\ket{sm}=m\ket{sm}$$
where $m\in\{-s,-s+1,...,s-1,s\}$.

It is a property of a particle in the same way that mass and charge are, so the spin, to be precise the magnitude of its spin, of a particle cannot change when an external field is applied on the particle.



The spin of a particle indicates the number of components of the wavefunction and specifies the transformation of its components under rotation of the coordinate system.

##### matrix representation of spin components
same as for [[angular momentum]]
Note that a basis needs to be chosen.

## rotation
The transformation of the components of the wavefuntion is equivalent to a rotation of the coordinate system (active and passive transformation).

The rotation operator about some angle $\mathbf{\theta}=\theta \mathbf{\hat{n}}$ : $U([R(\mathbf{\theta})])=e^{\frac{-i\mathbf{\theta}\cdot\mathbf{S}}{\hbar}}$

transformation matrix of a rotation of the coordinate system

##### Isolate the rotation of the coordinate system
take the coordinate of the wavefunction of a particle to be at the origin implying that the angular momentum of the particle is 0, then rotate the coordinate system, the coordinates of the particle remain unchanged and only the component of the wave function are transformed.


## dynamics of spin
spin, magnetic field interaction
spin coupling

## spin 1/2

$$\braket{\mathbf{n},\pm|\hat{\mathbf{S}}|\mathbf{n},\pm}=\pm\frac{\hbar^{2}}{2}\mathbf{n}$$
every spinor with spin-1/2 $\ket{\chi}$ in $V_{S}$ is some eigenket of $\hat{\mathbf{S}}\cdot\mathbf{n}$ with eigenvalue $\pm\frac{\hbar}{2}$.