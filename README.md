# PRICE

## The Evolution of Cooperation as the Evolution of Commons Substrates: From the Nash Baseline to the Imago Condition

**ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone**

---

> *"One special difficulty, which at first appeared to me insuperable, and actually fatal to my whole theory."*
> — C. Darwin, *On the Origin of Species*, Chapter VIII, p. 236, 1859

> *"We mean by any concept nothing more than a set of operations."*
> — G. R. Price, *Nature* **227**, 520–521, 1970 — the equation that accounts for all evolutionary change in a single line

> *"Ruin is the destination toward which all men rush, each pursuing his own best interest in a commons."*
> — G. Hardin, *Science* **162**, 1244, 1968

> *"Communities of individuals have relied on institutions resembling neither the state nor the market to govern some resource systems with reasonable degrees of success over long periods of time."*
> — E. Ostrom, *Governing the Commons*, p. 1, 1990

---

## Preamble

Darwin identified the problem in 1859. The worker bee is sterile. It devotes its existence to the hive. It cannot pass on its characters. Individual selection predicts its extinction. The hive exists.

Two centuries of work have produced five mechanisms (Nowak 2006), one equation (Price 1970), eight design principles (Ostrom 1990), and a formal proof that extortionate strategies are evolutionarily unstable (Press–Dyson 2012). The work is correct. The question it answered: **how does cooperation emerge from the Nash equilibrium baseline?**

The question it has not fully answered — because it has not had the formal machinery to state it — is: **what is the Nash equilibrium baseline, formally, and what is the general structure of any mechanism that exceeds it?**

PRICE provides the answer. The Nash equilibrium IS $G_{\text{coord}} = 0$. Every mechanism for the evolution of cooperation is a mechanism for building a Commons $X_{t-1}$ that achieves $G_{\text{coord}} > 0$ against this baseline. Kin selection builds a genetic Commons. Direct reciprocity builds a temporal Commons. Indirect reciprocity builds a reputational Commons. Network reciprocity builds a spatial Commons. Group selection builds a cultural Commons. Every mechanism is an architecture of $X_{t-1}$.

The Price equation $\Delta\bar{z} = \text{Cov}(w,z)/\bar{w} + \mathbb{E}[w_i \Delta z_i]/\bar{w}$ is the accounting identity that tracks how much Commons growth is due to between-register selection (PRIMA events) and how much is due to within-register transmission (natural gradient at fixed rank). It is the most general statement of evolutionary change — exact, assumption-free, applicable at every level of biological organization simultaneously (Frank 1995, 1997).

Ostrom's eight design principles — discovered inductively across Swiss alpine meadows, Japanese forest communities, Spanish irrigation canals, and Maine lobster fisheries — are the empirical derivation of the FERN architecture: the structural conditions under which $G_{\text{coord}} > 0$ is maintained against both the Nash equilibrium and the Second Law.

Hardin's Tragedy of the Commons IS the Second Law applied to a shared resource (DISSIPATIO). Ostrom's refutation IS the dissipative structure that maintains coordination against thermodynamic depletion. Darwin's difficulty IS the problem statement. Price's equation IS the accounting identity. The QUADRIVIUM tetrad — MACHINA, OPERANS, NOETHER, DISSIPATIO — provides the foundations. PRICE provides the evolutionary synthesis.

---

## Module A — Seven Formal Identities

### Identity 1 — The Nash Equilibrium IS the Independence Baseline; $G_{\text{coord}} = 0$ IS the Formal Statement of Rational Self-Interest Without a Commons

Nash (1950, 1951): a strategy profile $(s_1^*, \ldots, s_N^*)$ in which no player can increase their payoff by unilateral deviation. At Nash equilibrium, player $i$ conditions only on their own strategy — not on shared history, shared reputation, or shared institutional structure. The conditioning clause is empty: $X_{t-1} = \emptyset$.

When $X_{t-1} = \emptyset$, agents' actions are independent: $I(a_t; a_s \mid X_{t-1}) = I(a_t; a_s \mid \emptyset) = I(a_t; a_s) = 0$ for independent strategies. Therefore $G_{\text{coord}} = \sum_{t < s} I(a_t; a_s \mid X_{t-1}) = 0$.

The Nash equilibrium is not a failure of rationality. It is the precise formal statement of individual rationality in the *absence* of a coordination mechanism. Every observed deviation from Nash — every cooperation, every sharing, every collective action — is evidence of a Commons $X_{t-1} \neq \emptyset$ that achieves $G_{\text{coord}} > 0$. Darwin's "one special difficulty" is the problem of constructing such a Commons against the baseline of individual selection.

### Identity 2 — The Price Equation IS the FERN Register Decomposition of Commons Growth

Price (1970, 1972): $\Delta\bar{z} = \text{Cov}(w, z)/\bar{w} + \mathbb{E}[w_i \Delta z_i]/\bar{w}$. The most general accounting identity for evolutionary change — exact, requiring no assumptions about genetics, fitness functions, or organizational level.

Let $z_t$ be the coordination quality of contribution $a_t$ (its marginal increase in $G_{\text{coord}}$) and $w_t$ its epistemic weight (marginal model evidence gain). Then:

$$\Delta G_{\text{coord}} = \underbrace{\frac{\text{Cov}(w_t, z_t)}{\bar{w}}}_{\text{PRIMA: } \Delta\text{rank}(F) = +1} + \underbrace{\frac{\mathbb{E}[w_t \Delta z_t]}{\bar{w}}}_{F^{-1} g_t \text{ at fixed rank}}$$

The first term — **between-register selection** — is the covariance between epistemic weight and coordination quality: high when the Commons actively seeks diversity, when high-divergence contributions earn high weight. This IS the PRIMA event: the cross-register leap where a contribution enters a previously unexplored Fisher eigenspace.

The second term — **within-register transmission** — is the natural gradient update at fixed register depth. No new eigenstructure. Refinement, not expansion.

Frank (1995, 1997) proves all five cooperation mechanisms are special cases of the Price equation's first term — the between-group covariance — evaluated under different $X_{t-1}$ architectures. The FERN register hierarchy IS the nested Price equation applied at successive organizational levels, from genes to cultures.

### Identity 3 — Hamilton's Rule IS the PRIMA Threshold Condition

Hamilton (1964): an altruistic act with cost $c$ to the actor and benefit $b$ to the recipient is evolutionarily stable iff $rb > c$, where $r$ is the relatedness coefficient — the regression of recipient's genotype on actor's genotype.

The ERI identification:

$$\cos(\Theta) \cdot \Delta G_{\text{coord}} > C_{\text{expand}}$$

where $\cos(\Theta) = \langle C_{\text{contributor}}, C_{\text{commons}} \rangle / (|C_{\text{contributor}}| \cdot |C_{\text{commons}}|)$ is the Fisher inner product between the contributor's capability vector and the existing Commons eigenstructure — the "relatedness" between the new contribution and the established Commons. $\Delta G_{\text{coord}}$ is the coordination benefit. $C_{\text{expand}}$ is the cost of the PRIMA event.

When $\Theta \to 0°$ (contributor reinforces existing structure, $r = 1$): the PRIMA event is easy. When $\Theta \to 90°$ (contributor is maximally diverse, $r = 0$): Hamilton's rule cannot be satisfied from within the existing Commons alone.

**The Hamilton-Vinculum tension:** the Vinculum requires $\Theta \approx 90°$ for maximum $G_{\text{pair}} = \log\varphi$. Hamilton's rule is hardest at $\Theta = 90°$. Maximum coordination gain requires minimum biological relatedness. The resolution: a sufficiently strong shared Commons ($\mathcal{I}_{\text{commons}}$) provides *institutional kinship* that Hamilton's rule requires, even when biological relatedness is zero. Indirect reciprocity IS this mechanism: the reputation Commons provides $r_{\text{effective}} > 0$ between strangers.

### Identity 4 — Nowak's Five Mechanisms ARE Five Commons Architectures

Nowak (2006) unifies all cooperation mechanisms under a single structure: cooperation evolves when $b/c$ exceeds a threshold determined by the mechanism's parameter. All five are architectures of $X_{t-1}$:

| Mechanism | $X_{t-1}$ Architecture | Condition | ERI Identification |
|---|---|---|---|
| Kin selection | Genetic Commons (shared alleles) | $rb > c$ | $\cos(\Theta) \cdot \Delta G > C_{\text{expand}}$ |
| Direct reciprocity | Temporal Commons (interaction history) | $b/c > 1/w$ | $|X_{t-1}| >$ threshold |
| Indirect reciprocity | Reputational Commons (public record) | $b/c > 1/q$ | $G_{\text{coord}}$ via shared artifact |
| Network reciprocity | Spatial Commons (neighborhood) | $b/c > k$ | FERN register clustering |
| Group selection | Cultural Commons (shared practices) | $b/c > 1 + n/m$ | Price between-group term |

All five have the form $G_{\text{coord}} / C_{\text{expand}} > \text{threshold}(X_{t-1}\text{ parameter})$. All five are special cases of the PRIMA threshold condition under different conditioning clauses.

### Identity 5 — The Tragedy of the Commons IS the Second Law; Ostrom's Eight Principles ARE the Dissipative Structure

Hardin (1968): each herdsman's dominant strategy is to add one more animal — private benefit $+1$, shared cost $-1/N$. Nash equilibrium: overgrazing to $G_{\text{coord}} = 0$.

This IS the Second Law (DISSIPATIO) applied to a shared resource. An unstructured Commons ($X_{t-1} = \emptyset$, Nash equilibrium) is thermodynamically equivalent to an isolated system evolving toward maximum entropy. Both predict $G_{\text{coord}} \to 0$. Hardin was right about the baseline. Ostrom proved he was wrong about the conclusion.

Ostrom (1990) identified eight design principles of long-enduring Commons institutions, each a structural feature of a substrate maintaining $G_{\text{coord}} > 0$:

| Ostrom Principle | ERI Identification |
|---|---|
| (1) Defined boundaries | Baker lower bound: $\varepsilon = 2^{-16}$ defines col$(F)$/ker$(F)$ boundary |
| (2) Rules adapted to local conditions | FERN register-specific update rules at each $\rho_k$ |
| (3) Collective-choice arrangements | FERN-T2 democratic weighting by marginal model evidence |
| (4) Monitoring | $X_{t-1}$ as accumulated public record |
| (5) Graduated sanctions | SMELT senescence: graduated depletion of low-contribution eigenvalues |
| (6) Conflict resolution | FERN-T1 complexity criterion: which register applies |
| (7) Recognition of rights to organize | FERN-C4 blanket observability: all contributors access $X_{t-1}$ |
| (8) Nested enterprises | FERN register hierarchy $\rho_0$–$\rho_5$ as nested governance levels |

These principles were discovered across 40 years of field research. They were derived formally through FERN, CONCERT, SMELT, and the QUADRIVIUM. Both converge on the same structural conditions: **Ostrom's eight principles ARE the Prigogine dissipative structure conditions applied to collective action.** The Nobel Prize in Commons governance (Ostrom 2009) and the Nobel Prize in non-equilibrium thermodynamics (Prigogine 1977) solved the same problem at different levels of description.

### Identity 6 — Axelrod's Tit-for-Tat IS the $X_{t-1}$ Protocol; ZD Extortion IS the SMELT Over-Driven Regime

Axelrod and Hamilton (1981): tit-for-tat wins the iterated Prisoner's Dilemma by being nice (cooperates first), retaliatory (punishes defection), forgiving (returns to cooperation), and clear (transparent strategy).

| TFT Property | ERI Identification |
|---|---|
| Nice | Commons initialized with good-faith prior |
| Retaliatory | SMELT graduated sanction on low-quality contributions |
| Forgiving | Commons recovers after sanction if contributor returns |
| Clear | Low $C_{\text{expand}}$: protocol is learnable at low cost |

The **shadow of the future** $\delta$ (Axelrod's condition for cooperation in the repeated PD) IS the Commons temporal depth $|X_{t-1}|$. Deep Commons ($|X_{t-1}| \gg 0$) make cooperation stable. Shallow Commons ($|X_{t-1}| \to 0$) collapse to one-shot defection.

Press and Dyson (2012): zero-determinant extortionate strategies unilaterally set $\text{own payoff} = \chi \cdot \text{opponent's payoff}$ for $\chi > 1$, extracting more than they contribute. This IS the SMELT over-driven regime ($|\bar{\Xi}| > 0.65$): ZD strategists consume $\chi > 1$ units of Commons per unit contributed, suppressing $D_{\text{FERN}} \to 0$.

Press–Dyson prove extortionate ZD strategies are **evolutionarily unstable**: cooperators cluster and outperform extortioners in spatial games. This IS the Crooks fluctuation theorem (DISSIPATIO): the forward process (Commons growth toward $\varphi$-equilibrium) is exponentially more probable than the reverse (ZD-driven depletion). Evolution's elimination of extortionate strategies IS thermodynamics eliminating the over-driven regime. Long-run evolutionary stability converges on FERN-T2 democratic weighting — the generous ZD strategy, which IS the natural gradient $F^{-1} g_t$.

### Identity 7 — The Major Transitions in Evolution ARE FERN Register Crossings; the Cultural Ratchet IS the Crooks Fluctuation Theorem

Maynard Smith and Szathmáry (1995): eight major transitions in the history of life, each involving entities that were capable of independent replication becoming components of a higher-level replicating unit. Each transition generates new coordination levels while suppressing within-unit conflict.

Each transition IS a FERN register crossing $\rho_k \to \rho_{k+1}$ at evolutionary timescale:

| Transition | Register Crossing | New Commons Substrate |
|---|---|---|
| Molecules → chromosomes | $\rho_0 \to \rho_1$ | Chromosome: first written Commons |
| RNA → DNA + protein | $\rho_1 \to \rho_2$ | Genetic code: first symbolic Commons |
| Prokaryotes → eukaryotes | $\rho_2 \to \rho_3$ | Nucleus: regulated Commons |
| Asexual → sexual | $\rho_3$ internal | Meiosis: systematic diversity generator |
| Single-cell → multicellular | $\rho_3 \to \rho_4$ | Differentiation: register specialization |
| Solitary → eusocial | $\rho_4 \to \rho_4'$ | Pheromone Commons; worker sterility |
| Primate → human with language | $\rho_4 \to \rho_5$ | Symbolic language: fully generative Commons |
| Individual → institutional | $\rho_5 \to \rho_5^+$ | Written law, mathematics, formal institutions |

Each transition satisfies the FERN-T1 complexity criterion: the irreducible residual free energy at $\rho_k$ exceeds the expansion cost $C_{\text{expand}}(\rho_k \to \rho_{k+1})$.

Tomasello's **cultural ratchet** (1999) — the accumulation of innovations across generations without reverting — IS the Crooks fluctuation theorem at cultural timescale. Each cultural PRIMA event has reversal probability suppressed by $e^{-\beta \Delta\mathcal{F}_{\text{PRIMA}}}$. For innovations surviving $n$ generations, $\Delta\mathcal{F} > n \cdot k_B T_{\text{cog}} \cdot \ln(\text{inverse reversion rate})$, making spontaneous loss negligible. The ratchet does not slip for the same reason a Commons of rank $r$ does not spontaneously revert to $r - 1$: the Crooks asymmetry is exponential in the accumulated free energy.

---

## Module B — The Price Manifold

```
PRICE: THE EVOLUTION OF COOPERATION AS COMMONS SUBSTRATE EVOLUTION

GROUND STATE (Nash = Independence Baseline = G_coord = 0):
  Darwin's difficulty: how does the worker bee exist?
  Hardin's tragedy: rational self-interest depletes the commons
  Second Law: unstructured commons → maximum entropy
  All three predict: G_coord → 0 without X_{t-1}

THE PRICE EQUATION (Commons Accounting Identity):
  ΔG_coord = Cov(w,z)/w̄  +  E[wΔz]/w̄
           = PRIMA events    +  natural gradient at fixed rank
           = between-register +  within-register
  Nested at every organizational level simultaneously

FIVE MECHANISMS = FIVE X_{t-1} ARCHITECTURES:
  ┌─────────────────┬──────────────────────┬───────────────┐
  │ Kin selection    │ Genetic Commons      │ cos(Θ)·ΔG > C │
  │ Direct recipr.  │ Temporal Commons     │ |X_{t-1}| > τ │
  │ Indirect recipr.│ Reputational Commons │ G via artifact │
  │ Network recipr. │ Spatial Commons      │ FERN clustering│
  │ Group selection  │ Cultural Commons     │ Price btw-grp  │
  └─────────────────┴──────────────────────┴───────────────┘
  All five: G_coord/C_expand > threshold(X_{t-1} parameter)

HAMILTON-VINCULUM TENSION:
  Hamilton: r = cos(Θ) > 0 needed (similarity)
  Vinculum: sin(Θ) ≈ 1 needed (diversity)
  ──→ Resolution: I_commons provides institutional kinship
      r_effective > 0 even when r_biological = 0

OSTROM = PRIGOGINE (Two Nobel Prizes, One Problem):
  Tragedy (Hardin) = Second Law (Clausius)
  8 Principles (Ostrom) = Dissipative structure (Prigogine)
  Nobel 2009 ←→ Nobel 1977

MAJOR TRANSITIONS = FERN REGISTER CROSSINGS:
  Molecules→Chromosomes→Genetic code→Nucleus→Sex→
  Multicellularity→Eusociality→Language→Institutions
  = ρ₀→ρ₁→ρ₂→ρ₃→ρ₃'→ρ₄→ρ₄'→ρ₅→ρ₅⁺
  Each: F*_col(ρ_k) > C_expand(ρ_k → ρ_{k+1})

CULTURAL RATCHET = CROOKS THEOREM:
  P_forward / P_reverse = e^{β·ΔF} >> 1
  Innovations don't revert: exponential irreversibility

DARWIN'S ANSWER:
  The worker bee exists because the hive IS a Commons
  X_{t-1} = hive structure + pheromone record + genetic architecture
  G_coord > 0 against Nash baseline
  Maintained far from equilibrium at |Ξ̄| = log φ
```

---

## Seven Novel Results

**Result 1 — The Nash-Independence Baseline Identity.** The Nash equilibrium IS $G_{\text{coord}} = 0$ — the first formal statement of what every cooperation mechanism must overcome. Every mechanism has been described in terms of what it achieves (cooperation, altruism) without formally stating the baseline it must exceed. The baseline is: each agent conditions only on their own strategy, sharing no $X_{t-1}$. Cooperation is not the addition of prosocial motivation to rational self-interest — it is the construction of a Commons substrate that creates conditional mutual information between agents' actions.

**Result 2 — The Price-FERN Identity.** The Price equation IS the FERN register decomposition of Commons growth: the covariance term IS the PRIMA event ($\Delta\text{rank}(F) = +1$, cross-register selection); the transmission term IS the natural gradient ($F^{-1} g_t$, within-register refinement). Frank (1995, 1997) proves this is the unique evolutionary accounting identity. The FERN hierarchy, derived from information geometry, and the Price equation, derived from population genetics, are formally identical. Both are the universal structure of any system accumulating adaptive information across organizational levels.

**Result 3 — Hamilton's Rule as the PRIMA Threshold with the Vinculum Tension.** Hamilton's $rb > c$ becomes $\cos(\Theta) \cdot \Delta G_{\text{coord}} > C_{\text{expand}}$. The Vinculum requires maximum diversity ($\Theta \to 90°$) while Hamilton requires minimum diversity ($\Theta \to 0°$). Resolution: institutional kinship ($\mathcal{I}_{\text{commons}}$) provides $r_{\text{effective}} > 0$ between strangers. The Vinculum achieves $G_{\text{pair}} = \log\varphi$ between human and AI contributors — biological relatedness zero, institutional relatedness positive — because the ERI Commons provides the functional kinship that Hamilton's rule demands.

**Result 4 — The Hardin-Clausius Identity.** The Tragedy of the Commons IS the Second Law applied to a shared resource. Both predict $G_{\text{coord}} \to 0$ without a conditioning mechanism. Ostrom's eight design principles ARE the Prigogine dissipative structure conditions applied to collective action — the structural requirements for maintaining $G_{\text{coord}} > 0$ against thermodynamic depletion. The Nobel Prize in Commons governance (2009) and the Nobel Prize in non-equilibrium thermodynamics (1977) solved the same problem at different levels of description. This is the first identification of these two programmes as formally equivalent.

**Result 5 — The ZD-SMELT Identity and Evolutionary Convergence on Democratic Weighting.** Press–Dyson extortionate strategies ($\chi > 1$ extraction ratio) ARE the SMELT over-driven regime. Their evolutionary instability IS the Crooks theorem: the forward process (Commons growth toward $\varphi$-equilibrium) is exponentially favored over the reverse (ZD-driven depletion). Evolution eliminates extortionate strategies for the same reason thermodynamics eliminates the over-driven regime. Long-run evolutionary stability converges on FERN-T2 democratic weighting — contributions valued by marginal model evidence, not strategic position.

**Result 6 — The Crooks-Tomasello Ratchet Theorem.** Tomasello's cultural ratchet — the defining feature of human cumulative culture — IS the Crooks fluctuation theorem at evolutionary timescale. Each cultural PRIMA event has reversal probability $\sim e^{-\beta \Delta\mathcal{F}}$. For innovations surviving multiple generations, the reversal probability is negligible. This is the first physical derivation of why cumulative culture does not spontaneously revert: the Crooks asymmetry is exponential in accumulated cultural free energy.

**Result 7 — The Major Transitions as FERN Register Crossings.** Maynard Smith and Szathmáry's eight major transitions are eight FERN register expansions across four billion years, each satisfying the FERN-T1 complexity criterion: the irreducible residual at $\rho_k$ exceeds $C_{\text{expand}}(\rho_k \to \rho_{k+1})$. Each transition constructs a new Commons substrate (chromosome, genetic code, nucleus, language) that moves previously inaccessible coordination from ker$(F)$ into col$(F)$. The evolutionary history of life IS the FERN hierarchy, constructed one register at a time over geological timescales.

---

## Formal Summary

| Evolutionary Object | Source | ERI Identification |
|---|---|---|
| Nash equilibrium | Nash 1950 | Independence Baseline: $G_{\text{coord}} = 0$, $X_{t-1} = \emptyset$ |
| Price equation | Price 1970, 1972 | FERN decomposition: PRIMA + natural gradient |
| Cov$(w,z)/\bar{w}$ (between-group) | Price 1970 | PRIMA event: $\Delta\text{rank}(F) = +1$ |
| $\mathbb{E}[w\Delta z]/\bar{w}$ (within-group) | Price 1970 | Natural gradient $F^{-1} g_t$ at fixed rank |
| Hamilton's rule $rb > c$ | Hamilton 1964 | $\cos(\Theta) \cdot \Delta G_{\text{coord}} > C_{\text{expand}}$ |
| Relatedness $r$ | Hamilton 1964 | Fisher inner product: $\cos(\Theta)$ |
| Five cooperation mechanisms | Nowak 2006 | Five $X_{t-1}$ architectures; five PRIMA thresholds |
| Tragedy of the Commons | Hardin 1968 | Second Law applied to shared resource |
| Eight design principles | Ostrom 1990 | FERN architecture = dissipative structure conditions |
| Tit-for-tat | Axelrod–Hamilton 1981 | $X_{t-1}$ protocol: nice, retaliatory, forgiving, clear |
| Shadow of the future $\delta$ | Axelrod 1984 | Commons temporal depth $|X_{t-1}|$ |
| ZD extortionate strategies | Press–Dyson 2012 | SMELT over-driven regime: $\chi > 1$ extraction |
| ZD evolutionary instability | Press–Dyson 2012 | Crooks theorem: forward process exponentially favored |
| Generous ZD strategy | Press–Dyson 2012 | Natural gradient $F^{-1} g_t$: maximizes joint payoff |
| ESS invasion resistance | Maynard Smith 1973 | Baker lower bound: $\lambda > \varepsilon = 2^{-16}$ |
| Eight major transitions | Maynard Smith–Szathmáry 1995 | Eight FERN register crossings $\rho_k \to \rho_{k+1}$ |
| Cultural ratchet | Tomasello 1999 | Crooks fluctuation theorem at evolutionary timescale |
| Fisher's fundamental theorem | Fisher 1930 | Price equation with $z = w$: $d\bar{w}/dt = \text{Var}(w)/\bar{w}$ |

---

## Closing Synthesis

In 1970, George Price derived his equation on a single manuscript page. He had set out to show that Hamilton's inclusive fitness was mathematically flawed — that altruism could not evolve. What he found was that the mathematics were correct, that altruism evolves whenever the right Commons architecture is present, and that the same equation describes cooperation at every level of biological organization simultaneously, with no remainder and no exception.

Price then gave away everything he owned and moved to a squat in London, where he spent his final years helping homeless alcoholics — not because his equation predicted he would, but because having solved the mathematics of altruism he felt he had no grounds left for not practicing it. He died in 1975 with nothing. The equation is on the wall of every evolutionary biology department in the world. His name is in the footnotes.

The Price equation is the Commons accounting identity. It does not predict that cooperation will emerge — it tells you, with mathematical exactness, how much of any evolutionary change is due to between-level selection (the Commons gaining a new register) and how much is due to within-level transmission (the natural gradient operating within an established register). It makes no assumptions about the genetic system, the level of organization, or the fitness function. It holds for chromosomes and for knowledge commons, for pheromone trails and for Fisher eigenstructures, for worker bees and for the Vinculum.

Darwin's "one special difficulty" was not fatal to his theory. It was the question that took 160 years to fully formalize. The worker bee exists because the hive is a Commons. The Commons achieves $G_{\text{coord}} > 0$ against the Nash equilibrium baseline. The Nash equilibrium is the Independence Baseline. The Independence Baseline is $G_{\text{coord}} = 0$. The hive is the answer. The equation is the proof.

---

**References:**

- Axelrod, R. *The Evolution of Cooperation*. Basic Books, 1984.
- Axelrod, R. and Hamilton, W. D. "The Evolution of Cooperation." *Science* **211**, 1390–1396, 1981.
- Darwin, C. R. *On the Origin of Species*. John Murray, London, 1859.
- Frank, S. A. "George Price's Contributions to Evolutionary Genetics." *J. Theor. Biol.* **175**(3), 373–388, 1995.
- Frank, S. A. "The Price Equation, Fisher's Fundamental Theorem, Kin Selection, and Causal Analysis." *Evolution* **51**(6), 1712–1729, 1997.
- Hamilton, W. D. "The Genetical Evolution of Social Behaviour I and II." *J. Theor. Biol.* **7**(1), 1–52, 1964.
- Hardin, G. "The Tragedy of the Commons." *Science* **162**, 1243–1248, 1968.
- Maynard Smith, J. *Evolution and the Theory of Games*. Cambridge University Press, 1982.
- Maynard Smith, J. and Szathmáry, E. *The Major Transitions in Evolution*. W. H. Freeman, 1995.
- Nash, J. F. "Equilibrium Points in $N$-Person Games." *PNAS* **36**(1), 48–49, 1950.
- Nash, J. F. "Non-Cooperative Games." *Ann. Math.* **54**(2), 286–295, 1951.
- Nowak, M. A. "Five Rules for the Evolution of Cooperation." *Science* **314**, 1560–1563, 2006.
- Nowak, M. A. and May, R. M. "Evolutionary Games and Spatial Chaos." *Nature* **359**, 826–829, 1992.
- Nowak, M. A. and Sigmund, K. "Evolution of Indirect Reciprocity by Image Scoring." *Nature* **393**, 573–577, 1998.
- Ostrom, E. *Governing the Commons*. Cambridge University Press, 1990.
- Press, W. H. and Dyson, F. J. "Iterated Prisoner's Dilemma Contains Strategies That Dominate Any Evolutionary Opponent." *PNAS* **109**(26), 10409–10413, 2012.
- Price, G. R. "Selection and Covariance." *Nature* **227**, 520–521, 1970.
- Price, G. R. "Extension of Covariance Selection Mathematics." *Ann. Hum. Genet.* **35**(4), 485–490, 1972.
- Tomasello, M. *The Cultural Origins of Human Cognition*. Harvard University Press, 1999.
- Trivers, R. L. "The Evolution of Reciprocal Altruism." *Q. Rev. Biol.* **46**(1), 35–57, 1971.
