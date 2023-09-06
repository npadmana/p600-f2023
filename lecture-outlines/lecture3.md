#  Lecture 3 

## Outline

### Expanding $a(t)$

- Expanding $a(t)$ in a Taylor series
	- $z = H_0(t_0 - t_1) = H_0 t_{lookback}$
	- Definition of lookback time (see above)
	- Going beyond, definition of $q_{0}$

### Distances in Cosmology

#### Comoving radial distance

$$
d\chi = \frac{c dt}{a(t)}
$$
or 
$$
\chi = c \int  \, \frac{dt}{a(t)}
$$
or 
$$
\chi = c \int  \, \frac{dz}{H(z)}
$$

From the above, we see that measuring $\chi(z)$ allows us to infer $H(z)$ (or the reverse). And then one can get $a(t)$.

Also note 
$$
d_{M} = S_{k}(\chi)
$$

#### Luminosity Distance

$$
F = \frac{F}{4 \pi d_{L}^{2}}
$$
where
$$
d_{L} = (1+z) d_{M}
$$

This is the basis of the standard candle method to measuring the expansion of the Universe (Cepheids, SNe 1a, standard sirens)

#### Angular Diameter Distance

$$
D = d_{A} \theta
$$
where
$$
d_{A} = \frac{d_{M}}{1+z}
$$

Note that 
$$
d_{L} = d_{A} (1+z)^2
$$


### Dynamics

#### Friedmann and continuity equations

$$
\left( \frac{\dot{a}}{a} \right)^{2} = \frac{8 \pi G}{3} \rho  \, - \frac{\kappa}{R_{0}^{2} a^{2}}
$$
$$
\frac{\ddot{a}}{a} = - \frac{4 \pi G}{3} (\rho + 3P)
$$
$$
\dot{\rho} + 3 H (\rho + P) = 0
$$

These equations are not independent, one can follow from the others.

Define the critical density 
$$
\rho_{crit} = \frac{3H^{2}}{8 \pi G}
$$
and define 
$$
\Omega = \frac{\rho}{\rho_{{crit}}}
$$
Then, the first Friedmann equation is given by 
$$
1-\Omega = \frac{\kappa}{R_{0}^{2} a^{2} H^{2}}
$$
Note that $\Omega$ can be used to determine the geometry of the Universe. Finally, note that the physical density parameter is
$$
\omega = \Omega h^2
$$


## Reading

Huterer, Chaps 2 & 3 : The discussion of distances is in Chap. 3 towards the end, after the dynamics discussion.

Baumann: Chap. 2. This is also a good reference if you want to look at the full derivation of the Friedmann equations.

A reference that I return to time and time again for distance measures in the "Distance Measures in Cosmology" paper by David Hogg listed in the class bibliography.
