Collision triangle geometry:
 * Target with velocity $V_T$
 * Range vector between pursuer $P$ and target $T$ . LOS vector along range vector.
 * **Heading angle** $A$ subtended by $V_T$ and range vector. **Lead angle** $L$ subtended by $V_P$ and range vector
 * Pursuer velocity $V_P$

 Assumptions resulting in a geometric relationship:
  * Constant $V_T$, $V_P$
  * Pursuer leads target

Relative velocity vector $V_R = V_T - V_P$

Relationship between velocity ratio and lead angle derived as follows:
$$
\frac{V_P}{\text{sin}(A)} = \frac{V_T}{\text{sin}(L)}
$$
$$
A = \text{sin}^{-1}\bigg[ \frac{V_P}{V_T} \text{sin}(L) \bigg]
$$
Additionally, the look angle $X_b$ is the angle subtended by orientation of the pursuer body and $V_P$ . When pursuer body is aligned with $V_P$, $X_b = L$ .

 ****=> As lead angle increases, $\frac{V_P}{V_T}$ must decrease.
 => As lead angle decreases, $\frac{V_P}{V_T}$ must increase.

