# Axial Current

## Setting-up
1. Signature of Metric: $(-,+,+,+)$;
2. Definition of Levi-Civita Symbol: $$\varepsilon^{0123} = +1$$ for Space-time indexes; $$\varepsilon_{123} = \varepsilon^{123} = +1$$ for spatial indexes.
**Note:** $$\varepsilon^{i_1 \cdots i_n}\equiv (-1)^t \, \varepsilon_{i_1 , \cdots i_n} \, ,$$ 
Where $t$ is the number of negative eigenvalues of the metric $g_{\mu\nu}$. Hence $\varepsilon_{0123} = -1$.
3. $F^{0 i} = E^i ; \quad F^{ij} = \varepsilon^{ijk} B_k$, where $E^i \equiv \{E_x,E_y,E_z\}; \; B_i \equiv \{ B_x , B_y , B_z \}$
$$
F_{\mu \nu} =\begin{bmatrix}
0 & -E_x & -E_y & -E_z \\
E_x & 0 & B_z & -B_y \\
E_y & -B_z & 0 & B_x \\
E_z & B_y & -B_x & 0 \\
\end{bmatrix} ;\qquad 
F^{\mu \nu} =\begin{bmatrix}
0 & E_x & E_y & E_z \\
-E_x & 0 & B_z & -B_y \\
-E_y & -B_z & 0 & B_x \\
-E_z & B_y & -B_x & 0 \\
\end{bmatrix}
$$
4. Hodge Star Operator
$$
^\star F^{\mu\nu} \equiv \frac{1}{2} \varepsilon^{\mu\nu\alpha\beta} F_{\alpha\beta} = 
\begin{bmatrix}
0 & B_x & B_y & B_z \\
-B_x & 0 & -E_z & E_y \\
-B_y & E_z & 0 & -E_x \\
-B_z & -E_y & E_x & 0 
\end{bmatrix}
$$
    Some Cases: 
    * **01**23: $\varepsilon^{0123} F_{23} = F^{23} = \varepsilon^{231} B_1 = B_x$
    * **02**13: $\varepsilon^{0213} F_{13} = - F_{13} = -F^{13} = - \varepsilon^{132} B_2 = B_2 = B_y$
    * **10**23: $\varepsilon^{1023} F_{23} = - F_{23} = - F^{23} = - \varepsilon^{231} B_1 = - B_1 = - B_x$
    * **12**03: $\varepsilon^{1203} F_{03} = F_{03} = - F^{03} = - E_z$
    * **13**02: $\varepsilon^{1302} F_{02} = - F_{02} = F^{02} = E_y$
    * **23**01: $\varepsilon^{2301} F_{01} = F_{01} = - F^{01} = - E_x$ 

## Expression of Chiral Anomaly 

 Therefore, we have the topological term:
$$
 ^\star F_{\mu\nu} F^{\mu\nu} = - 4 \, \vec{B} \cdot \vec{E}
$$
 And, the axial current can be written as
$$
\begin{align}
 \partial_\mu J_A^\mu &= - \frac{g^2}{16 \, \pi^2} \varepsilon^{\mu\nu \rho\sigma} F_{\mu\nu} F_{\rho\sigma} \\
  &= - \frac{g^2}{8 \, \pi^2} \, ^\star F^{\rho\sigma} F_{\rho \sigma} = - \frac{g^2}{8 \, \pi^2} \, (-4) \, \vec{B} \cdot \vec{E} \\
  &= \frac{g^2}{2 \, \pi^2} \, \vec{E} \cdot \vec{B}
 \end{align}
$$
