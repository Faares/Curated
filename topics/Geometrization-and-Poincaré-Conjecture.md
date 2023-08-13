# Geometrization and Poincaré Conjecture
The path toward the Poincaré Conjecture proof was initially "started" by the work of Thurston's project, in which he aims to classify and study in-depth low-dimensional manifolds.

The path can be seen as: 

* Studying 2-dimensional manifolds and trying to go deep into 3-dimensional manifolds by using it.
* Discovering decomposability of 3-manifolds.
* The Geometrization Conjecture stated.
* The Elliptization conjecture stated, which is a special case of the Geometrization Conjecture.
* Poincaré Conjecture is a trivial case of the Elliptization conjecture.

## *Loosely & Roughly speaking*[^ss]
Any closed, orientable *2-dimensional* manifold is known to hold one of the three geometric structure: Euclidean $\mathbb{E}$, Spherical $\mathbb{S}$, Hyperbolical $\mathbb{H}$, but what about *3-dimensional* manifolds? What type of geometry they can holds?

Well, the process to deduce the answer is complicated, however it can be simplified as follow:

* *3-dimensional* manifolds can be decomposed into sums of prime 3-manifolds, as [The Prime Decomposition Theorem](https://en.wikipedia.org/wiki/Prime_decomposition_of_3-manifolds) states.
* Which means, *3-manifolds* can be *decomposed* into *connected sum*.
* **The Geometrization Conjecture:** Thurston conjectured that *all* the components of the *connected sum* holds a geometric structure. So, any *3-manifold* has exacly one of these geometric structures:
  * Euclidean geometry $\mathbb{E}$.
  * Hyperbolic geometry $\mathbb{H}$.
  * Spherical geometry $\mathbb{S}$.
  * The geometry of $\mathbb{S}^2×\mathbb{R}$.
  * The geometry of $\mathbb{H}^2×\mathbb{R}$.
  * The geometry of the universal cover ${\displaystyle {\widetilde {\rm {SL}}}(2,\mathbf {R} )}$ of the Lie group $SL_2R$.
  * Nil geometry.
  * Sol geometry.
* The *geometric structure* of a *3-manifold* can be characterized by [the fundamental group](https://en.wikipedia.org/wiki/Fundamental_group).
* **The Elliptization Conjecture:** Thurston conjectured that a closed 3-manifold with ***finite** [fundamental group](https://en.wikipedia.org/wiki/Fundamental_group)* has $\mathbb{S}^3$ geometric structure.[^ct]
* **The Poincaré Conjecture:** Any closed simply connected (aka. with ***trivial** fundamental group*) 3-manifold has the $\mathbb{S}^3$ geometric structure.

As the path, **The Geometrization Conjecture** helps in proving **The Elliptization Conjecture**, using the fact that if the fundamental group is finite, then the geometric structure is $\mathbb{S}$.

Therefore, **The Poincaré Conjecture** follows immediately.


[^ct]: Remember, the circle is special kind of an ellipse. 
[^ss]: Trying to simplify the topic in somehow technical language without being too strict.
