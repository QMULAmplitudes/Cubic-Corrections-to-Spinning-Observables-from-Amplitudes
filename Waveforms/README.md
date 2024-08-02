This is the companion repository to "Spinning waveforms in cubic effective field theories of gravity", 2408.00587, where we provide the scalar and spinning waveforms for both G3 and I1 interactions. These correspond to equations (4.21) and (4.30) in the paper. The parity-odd waveforms can be easily obtained from their parity-even counterparts by multiplying by $i$.

See the file "LoadingWaveforms.nb" for instructions on getting the waveforms. The notation used is quoted in the Mathematica file and here for convenience.

Notation:\
*`m1` and `m2` are the masses of the two black holes\
*`U` is the retarded time\
*`\[CapitalKappa]` $= \sqrt{32\pi G}$\
*`\[Sigma]` is the Lorentz factor $\sigma=u_1\cdot u_2$\
*`a1` and `a2` are the ring radii of the two black holes\
*`u1` and `u2` are the velocities of the two black holes\
*`k` denotes a unit vector in the direction of the radiation, denoted $\hat{k}$ in the paper\
*`sp[A, B]` represents the scalar product of $A$ and $B$, $A\cdot B$\
*`\[Epsilon][A,B,C,D]` is the 4 dimensional Levi-Civita tensor fully contracted, $\epsilon^{\mu\nu\rho\sigma} A_\mu B_\nu C_\rho D_\sigma$\
*`ksq[A,B]` is the spinor trace $[k|A \hspace{2pt} B|k]$. Note that $X^\mu$ in the paper corresponds to `ksq[v1,\[Mu]]`
