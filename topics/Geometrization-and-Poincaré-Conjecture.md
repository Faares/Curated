# Geometrization and Poincaré Conjecture
The path toward the Poincaré Conjecture proof was initially "started" by the work of Thurston's project, in which he aimed to classify and study in-depth low-dimensional manifolds.

The path can be seen as: 

* Studying 2-dimensional manifolds and trying to go deep into 3-dimensional manifolds by using it.
* Discovering decomposability of 3-manifolds.
* The Geometrization Conjecture stated.
* The Elliptization conjecture stated, which is a special case of the Geometrization Conjecture.
* Poincaré Conjecture is a trivial case of the Elliptization conjecture.

## *Loosely & Roughly Speaking*[^ss]
Any closed, orientable *2-dimensional* manifold is known to hold one of the three geometric structures: Euclidean $\mathbb{E}$, Spherical $\mathbb{S}$, Hyperbolic $\mathbb{H}$, but what about *3-dimensional* manifolds? What type of geometry they can hold?

Well, the process to deduce the answer is complicated, however, it can be simplified as follow:

* *3-dimensional* manifolds can be decomposed into sums of prime 3-manifolds, as [The Prime Decomposition Theorem](https://en.wikipedia.org/wiki/Prime_decomposition_of_3-manifolds) states.
* Which means, *3-manifolds* can be *decomposed* into *connected sum*.
* **The Geometrization Conjecture:** Thurston conjectured that *all* the components of the *connected sum* holds a geometric structure. So, any *3-manifold* has exactly one of these geometric structures:
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

## About The Proof
The proof was done by Grisha Perelman in three papers that appeared on Arxiv [[1]][[2]][[3]], using surgery technique with Ricci Flow. To take an overview of the proof, you can read [Tao](https://terrytao.files.wordpress.com/2009/09/poincare.pdf) presentation.

[^ct]: Remember, the circle is a special kind of ellipse. 
[^ss]: Trying to simplify the topic in somehow technical language without being too strict.



[1]: https://arxiv.org/abs/math/0211159
[2]: https://arxiv.org/abs/math/0303109
[3]: https://arxiv.org/abs/math/0307245
