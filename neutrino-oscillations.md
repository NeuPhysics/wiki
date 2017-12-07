<!-- TITLE: Neutrino Oscillations -->
<!-- SUBTITLE: A quick summary of Neutrino Oscillations -->

# Neutrino Oscillations in Vacuum

Vacuum Oscillation
==================

Schrodinger equation is

$$i\partial_t \ket{\Psi} = \mathbf H \ket{\Psi},$$

where for relativistic neutrinos, the energy is

$$\mathbf H^{vm} &= \begin{pmatrix}\sqrt{p^2 + m_1^2} & 0 & 0 \\ 0& \sqrt{p^2 + m_2^2} & 0 \\ 0 & 0 & \sqrt{p^2 + m_3^2}  \end{pmatrix},$$

in which the energy terms are simplified using the relativistic
condition

$$\sqrt{p^2+m_i^2} & = p\sqrt{1 + \frac{m_i^2}{p^2}} \\
&\approx  p(1 + \frac{1}{2} \frac{m_i^2}{p^2}).$$

::: {.admonition}
So Called Decoherence

Here we assume that they all have the same energy but different mass.
The thing is we assume they have the same velocity since the mass is
very small. To have an idea of the velocity difference, we can calculate
the distance travelled by another neutrino in the frame of one neutrino.

Assuming the mass of a neutrino is 1eV with energy 10MeV, we will get a
speed of $1-10^{-14}$ c. This $10^{-14}$ c will make a difference about
$3\mu\mathrm{ m}$ in 1s.

Will decoherence happen due to this? For high energy neutrinos this
won\'t be a problem however for low energy neutrinos this will
definitely cause a problem for the wave function approach. Because the
different mass eigenstates will become decoherent gradually along the
path.

Nussinov (1976) discussed that solar neutrino wave packet coherence
length is about $10^{-6}\mathrm{cm}$.

A estimation of the decoherence length is

$$l_{\mathrm{coh}}=\frac{v_g}{\Delta v_g}\sigma.$$

To obtain the relation,

$$\Delta x &= \lvert v_1 - v_2 \rvert t_{\mathrm{coh}}\\
\frac{\hbar c}{\Delta E} & = \lvert \frac{m_1^2}{2E_1^2} - \frac{m_2^2}{2E_2^2} \rvert t_{\mathrm{coh}} \\
\frac{\hbar c}{\Delta E} & = \frac{1}{2E}\lvert \Delta m_{12}^2 \rvert t_{\mathrm{coh}}$$

**It should be made clear that this is not really decoherence but in the
view of wave packet formalism different propagation eigenstates will be
far away from each other. As long as we put them together again we can
overlap and oscillate again. No quantum decoherence is happening at
all.**
:::

In general the flavor eigenstates are the mixing of the mass eigenstates
with a unitary matrix $\mathbf U$, that is

$$\ket{\nu_{\alpha}} =  U_{\alpha i} \ket{\nu_i},$$

where the $\alpha$ s are indices for flavor states while the *i* s are
indices for mass eigenstates.

To find out the equation of motion for flavor states, plugin in the
initary tranformation,

$$i  U_{\alpha i} \partial_t \ket{\nu_i} =  U_{\alpha i}  H^m_{ij} \ket{\nu_j}.$$

We use index ${}^{vm}$ for representation of Hamiltonian in mass
eigenstates in vacuum oscillations. Applying the unitary condition of
the transformation,

$$\mathbf I = \mathbf {U^\dagger} \mathbf U,$$

I get

$$i U_{\alpha i} \partial_t \ket{\nu_i} =  U_{\alpha i} H^m_{i j}  {U^\dagger_{j\beta}}  U_{\beta k} \ket{\nu$$