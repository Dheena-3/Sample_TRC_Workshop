# Derivation of Hawking Radiation in the Lemaître-Tolman-Bondi (LTB) Model

This document provides a comprehensive mathematical derivation tracing the formation of Hawking radiation from a dynamically collapsing shell described by the inhomogeneous Lemaître-Tolman-Bondi (LTB) metric.

---

## 1. The Starting LTB Spacetime Metric

The spherically symmetric, inhomogeneous LTB metric in comoving coordinates $(t, r, \theta, \phi)$ is given by:
$$ds^2 = -dt^2 + \frac{(\mathcal{R}_{,r})^2}{1 + f(r)} dr^2 + \mathcal{R}^2 d\Omega^2$$

where:
* $\mathcal{R}(t,r)$ is the physical areal radius.
* $\mathcal{R}_{,r} = \frac{\partial \mathcal{R}}{\partial r}$ is the radial spatial gradient.
* $f(r)$ represents the local spatial geometry curvature profile.
* $d\Omega^2 = d\theta^2 + \sin^2\theta d\phi^2$ is the standard line element on a 2-sphere.

The local dynamics are governed by the localized field equation:
$$\left(\frac{\partial \mathcal{R}}{\partial t}\right)^2 = \frac{F(r)}{\mathcal{R}} + f(r)$$
where $F(r)$ denotes the Misner-Sharp mass enclosed inside the comoving shell radius $r$.

---

## 2. Transformation to Ingoing Null Coordinates

To trace light rays crossing the dynamically forming black hole event horizon, we transform to an advanced/ingoing null coordinate frame. 

Radial light rays satisfy the null path condition $ds^2 = 0$ along with $d\Omega^2 = 0$:
$$0 = -dt^2 + \frac{(\mathcal{R}_{,r})^2}{1 + f(r)} dr^2 \implies dt = \pm \frac{\mathcal{R}_{,r}}{\sqrt{1 + f(r)}} dr$$

For an **ingoing** null geodesic traveling toward the center, we adopt the negative sign:
$$dt = - \frac{\mathcal{R}_{,r}}{\sqrt{1 + f(r)}} dr$$

We introduce a new advanced time null coordinate $u(t,r)$ along with an integrating structure function $g(u,r)$ to yield:
$$dt = g(u,r) du - \frac{\mathcal{R}_{,r}}{\sqrt{1 + f(r)}} dr$$

### Verification of the Null Metric Structure
Substituting our expression for $dt$ back directly into the original LTB metric:
$$ds^2 = -\left( g(u,r) du - \frac{\mathcal{R}_{,r}}{\sqrt{1 + f(r)}} dr \right)^2 + \frac{(\mathcal{R}_{,r})^2}{1 + f(r)} dr^2 + \mathcal{R}^2 d\Omega^2$$

Expanding out the leading squared binomial term:
$$ds^2 = -\left[ g(u,r)^2 du^2 - \frac{2 g(u,r) \mathcal{R}_{,r}}{\sqrt{1 + f(r)}} du \, dr + \frac{(\mathcal{R}_{,r})^2}{1 + f(r)} dr^2 \right] + \frac{(\mathcal{R}_{,r})^2}{1 + f(r)} dr^2 + \mathcal{R}^2 d\Omega^2$$

Notice the pure radial $dr^2$ spatial structural parameters perfectly cancel out:
$$ds^2 = -g(u,r)^2 du^2 + \frac{2 g(u,r) \mathcal{R}_{,r}}{\sqrt{1 + f(r)}} du \, dr + \mathcal{R}^2 d\Omega^2$$

Defining the metric shorthand components $\Phi(u,r) = g(u,r)^2$ and $\Psi(u,r) = \frac{g(u,r) \mathcal{R}_{,r}}{\sqrt{1 + f(r)}}$, we obtain the finished characteristic null metric expression:
$$ds^2 = -\Phi(u,r) du^2 + 2\Psi(u,r) du \, dr + \mathcal{R}(u,r)^2 d\Omega^2$$

Since the structural component preceding $dr^2$ is exactly zero ($g_{rr} = 0$), holding $u$ constant ($du=0$) yields a total interval $ds^2 = 0$. This confirms the radial coordinate frame is cleanly configured as **null**.

---

## 3. Ray Tracing and the Logarithmic Shift

The apparent horizon boundary layer forms exactly when the localized gravitational energy traps outgoing information streams:
$$\mathcal{R}(t,r) = F(r) \iff \Phi(u,r) = 0$$

Let $u$ frame the retarded coordinate tracking outgoing rays departing towards future null infinity ($\mathscr{I}^+$), and $v$ represent the advanced coordinate tracing incoming test rays from past null infinity ($\mathscr{I}^-$). 

As a shell approaches the critical radius $\mathcal{R} \to F(r)$, we perform a localized linear Taylor series expansion of our metric control function $\Phi(u,r)$ adjacent to the horizon surface $r_H$:
$$\Phi(u,r) \approx \left. \frac{\partial \Phi}{\partial r} \right\vert_{H} (r - r_H)$$

Evaluating the geometric path trajectory of an outgoing ray trying to break loose from the horizon results in a differential relation:
$$\frac{du}{dv} \propto \frac{1}{v_H - v}$$

Integrating this relation reveals the hallmark **logarithmic relationship** mapping late-time outgoing coordinates to early advanced times:
$$u \approx -\frac{1}{\kappa} \ln(v_H - v)$$

where $v_H$ denotes the critical absolute threshold threshold cutoff ray, and $\kappa$ represents the localized surface gravity:
$$\kappa = \frac{1}{2\Psi(u,r_H)} \left. \frac{\partial \Phi}{\partial r} \right\vert_{H}$$

---

## 4. Bogoliubov Transformation and the Thermal Distribution

Quantum field mode expressions for a massless scalar field populated across past null infinity $\mathscr{I}^-$ (modes $\sim e^{-i\omega' v}$) transform into future modes reaching $\mathscr{I}^+$ (modes $\sim e^{-i\omega u}$). The conversion coupling is dictated by the secondary Bogoliubov calculation integral:
$$\beta_{\omega\omega'} = \frac{1}{2\pi} \sqrt{\frac{\omega}{\omega'}} \int_{-\infty}^{v_H} e^{-i\omega u(v)} e^{-i\omega' v} dv$$

Substituting the logarithmic geometric coordinate relation $u(v) = -\frac{1}{\kappa}\ln(v_H - v)$ into the integration profile:
$$\beta_{\omega\omega'} \propto \int_{-\infty}^{v_H} (v_H - v)^{\frac{i\omega}{\kappa}} e^{-i\omega' v} dv$$

Applying a coordinate change of variables $x = v_H - v$:
$$\beta_{\omega\omega'} \propto e^{-i\omega' v_H} \int_{0}^{\infty} x^{\frac{i\omega}{\kappa}} e^{i\omega' x} dx$$

This is a integral form related to the complex **Gamma Function** $\Gamma(z)$. Evaluating its absolute value square removes phase factors and reveals the underlying ratio:
$$\left| \beta_{\omega\omega'} \right|^2 = \left| \alpha_{\omega\omega'} \right|^2 e^{-\frac{2\pi\omega}{\kappa}}$$

Using the clean normalization property binding the transformation metrics ($\left|\alpha_{\omega\omega'}\right|^2 - \left|\beta_{\omega\omega'}\right|^2 = 1$ for localized wavepackets), we rearrange the structural balance to isolate particle density:
$$\left| \beta_{\omega\omega'} \right|^2 = \frac{1}{e^{\frac{2\pi\omega}{\kappa}} - 1}$$

---

## 5. Verification of the Thermal Nature

The expected particle number operator evaluation $N_\omega$ for an observer monitoring the black hole out at infinity yields:
$$\langle N_\omega \rangle = \int_0^\infty \left| \beta_{\omega\omega'} \right|^2 d\omega' = \frac{1}{e^{\frac{2\pi\omega}{\kappa}} - 1}$$

This precisely matches the universal mathematical profile of the **Planck Distribution Law** for blackbody thermal radiation:
$$\langle N_\omega \rangle = \frac{1}{e^{\frac{\hbar\omega}{k_B T}} - 1}$$

Equating the exponents directly extracts the final localized **Hawking Temperature** value:
$$T_H = \frac{\hbar \kappa}{2\pi k_B}$$

### Conclusion
By mapping the collapsing LTB metric into an advanced null coordinate framework, we verified that the geometric properties of a dynamic, inhomogeneous shell produce a purely **thermal spectrum** of outbound radiation. Unlike static vacuum solutions, the surface gravity parameter $\kappa$ changes across individual concentric layers, meaning the thermal radiation dynamically tracks the localized mass shell profile during collapse.
