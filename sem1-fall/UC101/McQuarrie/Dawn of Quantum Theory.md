#### 1-1 Blackbody Radiation in Classical Physics
When a body is heated, its colour first turns red, then white then blue as its temperature continues to increase. The radiation emitted goes from a lower frequency to a higher frequency.
The exact frequency spectrum emitted by the body depends on the particular body itself, but an ideal body, which absorbes and emits all frequencies, is called a [[Blackbody|blackbody]] and serves as an idealisation for any radiating material. The ratiaion emitted by a blackbody is called blackbody radiation.

Plot of intensity of blackbody radiation vs frequency for several temperatures

###### [[Rayleigh-Jeans law]]
The expressions derived accoring to the laws of 19th century physics is (1.1) $$d\rho(\nu, T) = \rho_{\nu}(T)d\nu = \frac{8\pi k_BT}{c^3}\nu^2d\nu$$
where $\rho_\nu(T)d\nu$ is the radiant energy density between the frequencies $\nu$ and $\nu + d\nu$ and has units of joules per cubic meter (J.m$^{-3}$). 
T is absolute temperature
c is te speed of light
$k_B$ = Boltzmann constant = $R/N_A (J. K^-1)$

Rayleigh-Jeans law reproduces the experimental data at low frequencies. At high frequencies, however, the law predicts that the radiant energy density diverges as v^2. Because the frequency increases as the radiation enters the ultraviolet region, this divergence was termed the *ultraviolet catastrophe.*

#### 1-2 Blackbody Radiation with Quantum Physics

Rayleigh, Jeans and Planck assumed that radiation emitted by the blackbody was caused by the oscillations of the electrons in the constituent particles of the material body. 

These electrons were pictured as oscillating in an atom much like electrons oscillate in an antenna to give off radio waves.  However the oscillations occur at a much higher frequency; hence, we find frequencies in the visible, infrared and ultraviolet regions instead of the radio-wave region. 


###### [[Planck distribution law]] for blackbody radiation
In classical physics, variables that represent observables (position, momentum, energy) can take on a continuum of values. Planck made the revolutionar assumption that the energies of the oscillators were discrete and had to be proportional to an integral multiple of the frequency or, in equation form, that $E = nh\nu$, where E is energy of oscillator, n is an integer, h is a proportionality constant and $\nu$ is the frequency. Using this quantisation of energy, Plank derived equation (1.2) $$d\rho(\nu, T) = \rho_{\nu}(T)d\nu = \frac{8\pi h}{c^3}\frac{\nu^3d\nu}{e^{h\nu/k_BT} - 1}$$
We can express the Planck distribution law in terms of wavelength rather than frequency(1.3)  $$d\rho(\lambda, T) = \rho_{\lambda}(T)d\lambda = \frac{8\pi hc}{\lambda^5}\frac{d\lambda}{e^{hc/\lambda k_BT} - 1}$$
###### [[Wien Displacement law]]
If $\lambda_{max}$ is the wavelength at which  $\rho_\lambda(T)$ is a maximum, then (1.4) $$\lambda_{max}T=2.90\times 10^{-3}m.K$$
By differentiating $\rho_\lambda(T)$ with respect to $\lambda$, we can show that (1.5)$$\lambda_{max}T=\frac{hc}{4.965k_B}$$
#### 1-3 [[Photoelectric effect]] with a Quantum hypothesis

Experimentally, the kinetic energy of the ejected electrons is independent of the intensity of the incident. There is a threshold frequency, $\nu_0$, characteristic of the metallic surface, below which no electrons are ejected. Above it, the kinetic energy of the ejected electrons varies linearly with the frequency. Einstein proposed that radiation existed as small packets of energy, $E = h\nu$ now known as photons. 
KE = kinetic energy of an ejected electron
$h\nu$  = energy of incident photon
$\phi$ = work function, minimum energy required to remove an electron from the surface of the particular metal, analogous to ionisation energy of an isolated atom. (1.6) $$ KE = \frac{1}{2}mv^2 = h\nu - \phi$$
(1.7)$$h\nu_0 = \phi$$
(1.8)
$$KE = h\nu - h\nu_0$$

$1eV = (1.602 \times 10^{-19} C)(1 V)$

#### 1-4 Hydrogen [[Atomic Spectrum]]

Every atom, when subjected to high temperatures, or an electrical discharge, emits electromagnetic radiation of characteristic frequencies (each element has a characteristic emission spectra). Because it consists of only discrete frequencies, they are called line spectra. Hydrogen has the simplest.

Balmer showed that the frequencies of the emission lines in the visible region of the spectrum could be described by the equation $$\nu = 8.2202 \times 10^{14} \left(1 - \frac{4}{n^2} \right) Hz$$
where n = 3,4,5 ....

Reciprocal wavelength is called a wavenumber. $\bar{\nu} = 1/\lambda = \nu/c$ 

###### Balmer's Formula
(1.9)
$$\bar\nu = 109680 \left(\frac{1}{2^2} - \frac{1}{n^2}\right) cm^{-1}$$
n = 3,4, ....

Equation 1.9 predicts a series of lines as n takes on the values 3,4,5, and so on. This series of lines, is called the *Balmer Series*. As n increases, $1/n^2$ decreases and eventually we can ignore this term  compared with the 1/4 term and so in the limit n ->$\infty$ we have $$\bar{\nu} \rightarrow 109680 \left(\frac{1}{4}\right)cm^{-1} = 2.742 \times10^4 cm^{-1}$$
or $\lambda = 364.7 nm$. This value is essentially that for the last line in the Balmer series and is called the *series limit*.


##### 1-5 The Rydberg Formula
Rydberg accounted for all the lines in the hydrogen atomic spectrum by generalsing the Balmer formula to (1.10)
$$\bar{\nu} = \frac{1}{\lambda} = 109680 \left(\frac{1}{n_1^2} - \frac{1}{n_2^2} \right) cm^{-1}$$
$(n_2 > n_1)$
where both n_1 and n_2 are integers.

(1.11)
$$\bar{\nu} = \frac{1}{\lambda} = R_H \left(\frac{1}{n_1^2} - \frac{1}{n_2^2} \right) cm^{-1}$$

109 677.57 cm^-1

UV visible IR IR IR (lyman has the highest energy, with the lowest wavelength)

Lyman: n_1 = 1 (ultraviolet)
Balmer: n_2 = 2 (visible)
Paschen: n_3 = 3 (near infrared)
Bracket: n_4 = 4 (infrared)
Pfund: n_5 = 5


#### 1-6  de Broglie wavelength
Wave-particle duality of light, de Broglie showed that both light(photons) and matter obey this equation. (if light can be matter-like, matter can also be wavelike)
(1.12)
$$\lambda = \frac{h}{p}$$
$\lambda$ = de Broglie wavelength
p = momentum
h = planck constant

#### 1-8 The [[Bohr Theory]] from Rydberg Formula

Coulombic force of attraction between proton and electron in a Hydrogen atom: $$f = \frac{e^2}{4\pi \epsilon_0r^2}$$
$\epsilon_0 = 8.85419 \times 10^{-12} C^2.N^{-1}.m^{-2}$ (permittivity of free space)

The coulombic force is balanced by the centrifugal force  (1.13)$$f = \frac{m_ev^2}{r}$$ v = speed of the electron
m_e = mass of the electron

(1.14)

$$\frac{m_ev^2}{r} = \frac{e^2}{4\pi \epsilon_0r^2}$$

The electron must be in the **same phase** after completing one revolution around the orbit, or cancellation of amplitude occurs and the wave will disappear. So,
(1.15)$$ 2\pi r = n\lambda \space\space\space\space n = 1,2,3$$
If we substitute the de Broglie wavelength formula
$$m_e vr = \frac{nh}{2\pi}$$
or (1.16)
$$m_e vr = n\bar{h}$$
where $\bar{h} = h/2\pi$

If we solve (1.16) for v and substitute it into (1.14), we find that the radius must be

(1.17)
$$r = \frac{\epsilon_0 h^2 n^2}{\pi m_e e^2} = \frac{4\pi \epsilon_0 \bar{h}^2n^2}{m_ee^2}$$
When n = 1, smallest Bohr orbit $a_0$ = 52.92pm

In an electron,
Total Energy = Kinetic Energy + Potential Energy


Potential energy of an electron and proton separated by a distance r is given by Coulomb's law  (1.19)$$V(r) = -\frac{e^2}{4\pi \epsilon_0 r}$$
Negative sign means the proton and electron attract each other, (work must be performed against this electric field to increase distance between them), their energy is less than when they are infinitely separated $V(\infty) = 0$.
Total Energy of the electron in a hydrogen atom
(1.20)
$$E = KE + V(r) = \frac{1}{2}m_ev^2 - \frac{e^2}{4\pi \epsilon_0r}$$
Using (1.14), (1.20) becomes
(1.21)
$$E = \frac{1}{2}\left(\frac{e^2}{4\pi \epsilon_0r}\right) - \frac{e^2}{4\pi\epsilon_0r} = - \frac{e^2}{8\pi\epsilon_or}$$
(1.22)
$$E_n = - \frac{m_ee^4}{8\epsilon_0^2h^2}\frac{1}{n^2}$$
For n = 1,2,...
For n=1, (1.22) corresponds to the state of lowest energy. This energy is called the ground-state energy. 

Energy levels merge as n -> infty. Bohr assumed that the observed spectrum of the hydrogen atom is due to ttransitions from one alloewd energy state to another, and using (1.22), he predicted that the allowed energy differences are given by (1.23) $$\Delta E = \frac{m_ee^4}{8\epsilon_0^2h^2}\left(\frac{1}{n_1^2} - \frac{1}{n_2^2}\right)  = h\nu$$
$\Delta E = h\nu$ (Bohr Frequency Condition)
Lyman series occurs when electrons that are excited to higher levels relax to n=1 state
and so on. 
We can write (1.23) by substituting $h\nu = hc\bar\nu$: (1.24) $$\bar\nu = \frac{m_ee^4}{8\epsilon_0^2ch^3}\left(\frac{1}{n_1^2} - \frac{1}{n_2^2}\right) $$
If we combine 1.11 and 1.24, we conclude that (1.25) $$R_{\infty} = \frac{m_ee^4}{8\epsilon_0^2ch^3}$$
should be equal to the Rydberg constant

The theory could not be successfully extended to  a two-electron system such as helium
