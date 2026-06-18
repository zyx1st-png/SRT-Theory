# Fisher geometry, energy landscapes, and the FEP in SRT

> A careful note for readers familiar with information geometry and active inference. It clarifies a mapping that is easy to get wrong: can energy landscapes / the Free Energy Principle (FEP) be read directly as `L2`? Can Fisher space be read directly as `L1`? Can `Ψf ≡ Fisher metric` be used as a strict identity?
>
> **Short answer:** these correspondences work as heuristic analogies or local formal projections, but should not be treated as bare identities. `L0 / L1 / L2` are SRT's *ontological domains*; Fisher geometry, energy landscapes, and FEP are *geometric or dynamical interfaces* describing the processes between those domains.

## 1. Core clarification (shortest version)

Not recommended as bare identities:

- `Fisher space = L1`
- `energy landscape = L2`
- `FEP = L2`
- `Ψf ≡ g_F` (read as a bare identity between a scalar cost and a metric tensor)

More accurate:

- **Fisher geometry** — characterizes the local distinguishability / selection-friction geometry of `L0 → L1`.
- **`L1`** — the actually manifested events, trajectories, and current reality-slice.
- **`L2`** — the stable constraint domain deposited by historical selection.
- **energy / free-energy landscape** — an effective projection (a low-dimensional expression) of `L2`.
- **FEP** — a self-maintaining update law for certain organized systems within `L1`, under `L2` constraints.
- **`Ψf` and the Fisher–Rao metric** — the local information-geometric projection of `Ψf` is *induced by* the Fisher–Rao metric; write it as a second-order form or a path functional, not as a bare `Ψf = g_F`.

In one line:

> Fisher belongs to the `L0 → L1` generative geometry; landscapes to `L2`'s constraint projection onto `L1`; FEP to `L1`'s self-maintaining dynamics under `L2`; the Fisher reading of `Ψf` is a local second-order projection, not a bare identity.

## 2. Why they cannot be directly identified

**Ontological levels and descriptive interfaces are not the same kind of object.** `L0 / L1 / L2` answer *what* the latent, manifest, and deposited-stable domains are (ontology). Fisher / landscape / FEP answer *how hard* a step from possibility to actuality is locally, how stable constraints pull subsequent updates, and why some systems maintain themselves along a local rule (geometry / dynamics). The difference is categorical, not a matter of size.

**`L1` is not the geometry itself, but what actually happens on it.** The Fisher metric gives

$$ds^2 = d\theta^\top g_F(\theta)\, d\theta,$$

i.e. the local distinguishability between neighboring selectable states — which directions, perturbed slightly, change the manifestation a lot, and which change much with little effect. That is closer to *the local selection geometry presented as `L0` tends toward actualizing into `L1`*. `L1` itself is the event that has occurred, the trajectory that has manifested, the landing point of current reality. So: **`L1` is "the step you actually took"; Fisher is "the sense of the path and the resistance structure near that step."**

**`Ψf` is not the Fisher tensor itself, but a local cost / path functional induced by it.** The Fisher–Rao metric is a metric tensor $g_F$; in SRT, `Ψf` is a payability burden — a local scalar cost or path functional. The categories differ, so they cannot be written as a strict bare identity. On a differentiable statistical manifold $p(x\mid\theta)$, the KL divergence has the local second-order expansion

$$D_{KL}(p_\theta \parallel p_{\theta+d\theta}) = \tfrac{1}{2}\, d\theta^\top g_F(\theta)\, d\theta + O(\lVert d\theta\rVert^3),$$

so the most stable Fisher expression in SRT is

$$\delta\Psi_f^{\text{geom}} = \tfrac{1}{2}\, d\theta^\top g_F(\theta)\, d\theta + O(\lVert d\theta\rVert^3),$$

or, in path form,

$$\Psi_f^{\text{geom}}[\gamma] = \int_\gamma \sqrt{g^F_{ij}(\theta)\, \dot\theta^i \dot\theta^j}\; dt.$$

That is: **the Fisher metric is not `Ψf` itself, but the local second-order geometry of `Ψf` projected onto the statistical manifold.**

**`L2` is thicker than a landscape; the landscape is only an effective slice.** In SRT, `L2` includes not just stability but historical deposition, hysteresis, normativity and institutionality, and the inertial structure left after multi-agent convergence. A typical energy / free-energy landscape gives only a scalar function $V(x)$ or $F(x)$ — which states are "lower," which basins are more stable, which directions are more easily pulled. So: **an energy landscape is not all of `L2`, but an effective projection of the `L2` constraint domain onto some state variables.**

**FEP is an update principle, not all of `L2`.** FEP describes how an already-organized system maintains itself under given constraints, and why it updates along a locally descending direction. That is a *local dynamical rule for an organized subject within `L1`, pulled by `L2`* — not `L2` itself. `L2` is closer to "the stable constraint field"; FEP is closer to "how a system keeps moving within that field."

## 3. The three-arrow structure (recommended fixed reading)

Rather than a static one-to-one correspondence, fix three steps:

- **A. `L0 → L1` — generation / actualization / local selection.** Best interface: Fisher geometry. It captures local distinguishability, the geometric projection of selection friction, which direction is more "natural," and how a small perturbation of selection parameters is amplified into a manifest difference. Recommended form: $\delta\Psi_f^{\text{geom}} = \tfrac{1}{2}\, d\theta^\top g_F(\theta)\, d\theta + O(\lVert d\theta\rVert^3)$.
- **B. `L1 → L2` — deposition / stabilization / hysteresis.** Best language: SRT's own account of historical deposition — how repeated selections become habits, norms, attractors, institutions, and how current reality hardens into a constraint on later reality. This step is SRT's native task and cannot be replaced by Fisher or FEP alone.
- **C. `L2 → L1` — pull-back / shaping / self-maintaining update.** Best interface: energy / free-energy landscape and FEP. It captures how stable constraints pull back new manifestations, which states are more easily maintained, and how organized systems keep updating within this constraint terrain.

## 4. A relation among the three (stated cautiously)

Where applicable, the following can help build intuition:

$$\dot\theta \;\sim\; -\, g_F^{-1}(\theta)\, \nabla_\theta F_{\text{eff}},$$

where $g_F(\theta)$ supplies the local Fisher geometry, $F_{\text{eff}}$ supplies the effective landscape or target terrain, and the update trajectory is the actual motion of an organized system. Read it as: **the landscape says "which way is lower," Fisher says "how to move naturally in this statistical space," and what is actually traced out is the update trajectory in `L1`.** This is a *bridge-level* expression for a local dynamical interface; it should not be turned around into a substitute for SRT's whole ontology, nor should $g_F$ be taken as the complete definition of `Ψf`.

## 5. The mapping, kept distinct

- **ontology:** `L0 / L1 / L2`
- **payability burden:** `Ψf`
- **local information geometry:** the Fisher–Rao-metric-induced projection of `Ψf`
- **effective constraint picture:** landscape
- **local update rule:** FEP

These five connect, but should not be flattened into one layer.

## 6. Four sentences worth fixing

1. Fisher mainly describes the local geometry of the reality-generating frontier.
2. The Fisher expression of `Ψf` is a local second-order information-geometric projection, not a bare `Ψf ≡ g_F`.
3. `L2` is not the landscape diagram itself, but the stable constraint domain that the landscape compresses.
4. FEP is not a universal ontology of selection itself, but the self-maintaining dynamics of certain organized systems within an existing constraint field.

## 7. Conclusion

On whether energy landscapes and FEP can be read as SRT's `L2`, whether Fisher space can be read as `L1`, and whether `Ψf ≡ Fisher metric` holds as a strict identity, the recommended answer is:

> Treat such statements as heuristic analogies or internal shorthand, but in formal writing rewrite them as: Fisher characterizes the local selection geometry of `L0 → L1`; the Fisher reading of `Ψf` is a local second-order information-geometric cost (or path functional) induced by the Fisher–Rao metric; the landscape characterizes the effective constraint projection of `L2` onto `L1`; and FEP characterizes the local update dynamics of organized systems under that constraint.

This keeps SRT's ontological levels clear, keeps `Ψf` read primarily as payability, and keeps Fisher (geometry), landscape (effective constraint), and FEP (local dynamics) in their distinct roles — avoiding the collapse of ontology, cost, metric, and dynamics into a single layer.
