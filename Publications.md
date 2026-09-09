- **Planar Embedding of Okamura-Seymour Quasimetrics in Polynomial Time with an Application to Distributed SSSP**
  <br>**Hung Le** and Hector Tierno and Shuang Yang.
  <br>[[PDF](https://arxiv.org/abs/2606.31192)]
  <br> Manuscript. 
  <details><summary style="color:#7C4700">Abstract</summary>
  <font color = "7C4700">
  A quasi-metric $(T,\delta_T)$ is an Okamura-Seymour quasimetric if there exists an edge-weighted planar embedded directed graph $G = (V,E,w)$ such that $T$ is  a set of terminals on the outerface of $G$ and $\delta_G(t,t') = \delta_T(t,t')$ for every pair $(t,t')\in T\times T$. If   $(T,\delta_T)$ is an Okamura-Seymour quasimetric, then $G$ is a planar embedding of $(T,\delta_T)$.<br><br>
  In a recent pioneering work, Chen and Tan gave a polynomial-time algorithm to test if a given quasi-metric $(T,\delta_T)$ is an Okamura-Seymour quasimetric. A key step in their proof is existential, which suffices for an efficient testing algorithm but does not imply an efficient embedding algorithm. Our paper closes this gap by giving an algorithmic implementation of their existential step via linear programming. As a result, we obtain the first polynomial-time algorithm for finding a planar embedding of any given Okamura-Seymour quasimetric $(T,\delta_T)$.  <br><br>
  As an application, we show how to use our planar embedding of Okamura-Seymour quasimetrics to compute a $(1+\epsilon)$-approximate single-source shortest path (SSSP) in planar directed graphs in the distributed \congest model in $\tilde{O}(D)$ rounds for any fixed $\epsilon\in (0,1)$, nearly matching a simple lower bound of $\Omega(D)$ and resolving a fundamental problem in this area. The best-known algorithm for this problem has round complexity $\tilde{O}(D^2)$. 
  
  </font>
  </details>
