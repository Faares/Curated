# Fermate Last Theorem
In 16-century Fermate stated a *conjecture* in number theory:


> For $(a,b,c,n) \in N\times N\times N \times N$ and $n \geq 3$. The equation $a^n+b^n=c^n$ has no solution.

And claimed he had the proof! Unfortunately, after nearly 3 decades, Wiles was finally able to prove the conjecture.

## *Loosely & Roughly Speaking*[^ss]

Using sophisticated language(=construction) and techniques from Algebraic Number Theory, Galois Representation, Elliptic Curves, and Complex Analysis.

The story of the proof begins with the "hypothetical" curve named by Gerhard Frey when he found a link between *Elliptic Curves* and *Diophantine Equation* as explained in his paper:
> [Links between stable elliptic curves and certain diophantine equations](https://github.com/FrancescaRossi/frey)

He observed a strong connection between **Fermate Last Theorem** and a conjecture called **Taniyama–Shimura conjecture**:
> All elliptic curves over $\mathbb{Q}$ field are related to modular form.

Roughly speaking, he stated that to counterexample **Fermate Last Theorem** you can create a hypothesized curve called later *Fray Curve*, such a curve *is not* modular. Equivalency and simply put, if the *Taniyama–Shimura conjecture* is true, the *Fermate Last Theorem* also is.

Later, Jean-Pierre Serre confirmed this fact and formulated the [Epsilon Conjecture](https://en.wikipedia.org/wiki/Ribet%27s_theorem) which proved by Ken Ribet.

> Ribet’s result *only requires* one to prove the conjecture for *semistable* elliptic curves in order to deduce Fermat’s Last Theorem - Quoted from Wiles paper.

So, it is enough to show that **all semistable elliptic curves over $\mathbb{Q}$ field are modular** to prove **Fermate Last Theorem**.


## About The Proof
The proof can be sketched in minor steps, but the technicality required ~110 pages to accomplish. The main breakthrough behind it is:

> A new and surprising link between two strong but distinct traditions in number theory, the relationship between **Galois representations and modular forms** on the one hand and **the interpretation of special values of L-functions** on the other.

So, how it was accomplished? 

* First, Wiles started to study **Elliptic Curves** using their **Associated Galois Representation**. In simple terms, if you proved that the **Associated Galois Representation** has a modular form, then the curve is. He picked $p = 3; G(E,3)$ initially, The Galois Representation of the elliptic curve $E$ on $p_3$ division points. Then for some technical reasons, picked $p = 5; G(E,5)$ also.

* The second is what he used to generalize his result for all semistable elliptic curves. The *Modular Lifting Theorem* in which he engaged **[Class Number Formula]** to conduct an induction over all elliptic curves, once proved for one curve it automatically extended to all subsequent curves.

[Class Number Formula]: https://en.wikipedia.org/wiki/Class_number_formula


[^ss]: Trying to simplify the topic in somehow technical language without being too strict.
