The Computational Anthropic Principle: The Subjective Window of Existence

Abstract

Given that an observer exists as a conscious entity, what form of reality and history are they most likely to inhabit?

The Computational Anthropic Principle (CAP) posits that an observer's subjective experience unfolds within a "Goldilocks Zone" of computational reality. This experiential window is bounded by two opposing forces: the necessity for sufficient complexity to support conscious awareness (the lower bound) and the universal statistical preference for algorithmic simplicity (the upper bound). This creates a dual filtering mechanism where consciousness necessarily exists in a narrow band between two exponential exclusions: one eliminating universes too simple to support observers, and the other eliminating baroque, high-complexity universes suppressed by the statistical dominance of simplicity.

CAP provides a radically subjective framework for understanding how an observer (Phi) navigates this window, predicting phenomena such as Probabilistic Persistence and substrate transition. It is a framework for subjective expectation, not ontological claim. The Computational Anthropic Principle does not assert which histories exist but rather: given that you find yourself as a conscious observer, what should you rationally expect about your circumstances?

1. Foundational Postulates

This framework relies on three core postulates derived from digital physics and algorithmic information theory.

Postulate A: Computational Plenitude

The physical multiverse realizes an unbounded set of computable state-trajectories. This postulates that the set of all possible programs is run. This is supported by Tegmark's Mathematical Universe Hypothesis (MUH) (2008), Bostrom's Simulation Argument (2003), and Hutter's assumption of a computable universe (2010).

Postulate B: Computational Functionalism

Conscious experience supervenes on specific computable patterns of functionally relevant information (Phi); therefore, substrate independence holds. As Hutter (2010) states, "Consciousness survives changes of substrate." Epistemologically, the observer's experience reduces to a computational structure—specifically, a temporal binary sequence. This aligns with Muller's (2020) formalism of the observer state as an informational pattern distinct from the particle substrate.

Postulate C: Observer-History Unity

The observer Phi and its sustaining history H constitute a single, dynamically coherent computational pattern. A "Complete Theory of Everything" must consist of an objective description of the multiverse plus a subjective observer model (Hutter, 2010). The relationship between Phi and H is not dualistic but structural: Phi is the focal pattern within the larger data structure of H.

We will first establish the information-theoretic constraints on observer existence (Sec 2) and the cost function of their histories (Sec 3). We then derive the CAP Weighting Theorem (Sec 4), which resolves the Boltzmann Brain paradox. Finally, we apply this theorem to predict the 'Anthropic Hinge' (Sec 6)—identifying the specific technological epoch a typical observer should expect to inhabit.

2. Observer-Centered Conditions (The Lower Bound)

These conditions define the minimum complexity required for an observer-pattern Phi to exist. They establish the "floor" of the Goldilocks Zone.

2.1 Existential Continuity (EC)

Let 1_Phi(H, t) be an indicator function such that 1_Phi(H, t) = 1 if the observer-pattern Phi is instantiated at subjective time step t within history H, and 0 otherwise.

EC is the tautological condition that the observer's subjective probability space is restricted to the set of pairs (H, t) where:

1_Phi(H, t) = 1

2.2 Survival Conditioning Principle (SCP)

Given that Phi is instantiated at time t*, the set of possible histories is restricted to those where the complete causal chain for Phi's instantiation remains unbroken. This formalizes Bostrom's (2002) "observation selection effects." The observer cannot subjectively occupy a history where the causal prerequisites for their current state have failed.

2.3 Computational Identity via Epsilon-Isomorphism

Two cognitive states are defined as the "same observer" (Phi) if they are epsilon-isomorphic regarding functionally relevant information. This aligns with Muller's (2024) concept of "equivalence classes."

The threshold epsilon is not arbitrary but derives from the principle that identity continuity is defined by the compressibility of state transitions. For any observer system Phi instantiated on any substrate (biological neurons, silicon, or abstract Turing Machine), we formalize this as:

Phi_t and Phi_(t+1) are epsilon-isomorphic if:

K(Phi_(t+1) | Phi_t) < epsilon

Where K(Phi_(t+1) | Phi_t) is the Conditional Kolmogorov Complexity—the minimal algorithmic information required to specify the state at t+1 given the state at t. This quantifies whether the transition can be "explained" or "predicted" within the observer's existing functional framework.

Compressible vs. Incompressible Transitions:

- Low K (Compressible): Represents learning, aging, gradual change, or substrate transition where the new state is logically derived from the old. The transition can be encoded as a simple update rule.

- High K (Incompressible): Represents "death" or catastrophic discontinuity, where the new state cannot be predicted from the old and requires high-cost external specification of arbitrary details.

The Elasticity of Identity

The threshold epsilon is elastic, modulated by Phi's representational capacity—the richness of the observer's internal model of the world. More sophisticated cognitive architectures can accommodate larger semantic shifts while maintaining continuity because they can compress more complex patterns into their existing framework.

Explicable alterations (learning new information, aging, even substrate transition) produce low conditional complexity because they represent smooth updates to the functional structure. Conversely, catastrophic information-theoretic disruptions (abrupt termination, randomization, or arbitrary replacement) produce conditional complexity vastly exceeding epsilon.

Trajectory Dependence

Crucially, identity depends on the trajectory of updates, not just instantaneous similarity. An observer may undergo radical transformation over time—Phi_0 to Phi_1000—while maintaining identity continuity, provided each incremental change remains compressible. This resolves the Ship of Theseus paradox: the ship remains "itself" not because its parts are preserved, but because the sequence of replacements forms a low-complexity narrative. Subjective identity is thus preserved across any transformation that can be encoded as a smooth path through state space, regardless of the distance traveled.

Connection to Complexity Cost

A violation of epsilon (an incompressible transition) implies that describing the state change requires explicitly encoding high-dimensional details rather than simply continuing the compressed pattern. This causes a spike in the Marginal Complexity Cost (DeltaC). Since the CAP Weighting Theorem (P proportional to 2^(-C)) exponentially penalizes high-cost transitions, the observer is statistically constrained to histories that minimize prediction error—preserving identity not through metaphysical necessity, but through algorithmic efficiency.

Therefore, Probabilistic Persistence precludes the subjective experience of changes that exceed epsilon-isomorphism. Identity-breaking transitions incur exponentially higher complexity costs and are exponentially suppressed in the measure.

3. The Complexity Cost Structure

To quantify the "Upper Bound" of the Goldilocks Zone, we introduce a measure of computational cost.

3.1 Marginal Complexity Cost (DeltaC)

Let DeltaC(H, t) represent the minimal incremental algorithmic work required to compute the state of the Phi-H pattern at t+1, given the state at t.

3.2 Cumulative Complexity Cost (C)

The total computational cost of a history up to time t is the sum of these marginal increments:

C(H, t) = Sum over tau less than or equal to t of DeltaC(H, tau)

Note: While related to Kolmogorov Complexity K(H), C(H,t) specifically measures the cumulative work of the generative process relative to the observer's timeline.

4. The CAP Weighting Theorem

Where the Observer-Centered Conditions provide a lower bound, the CAP Weighting Theorem provides the upper bound. It asserts that among all viable histories (those satisfying EC and SCP), the specific history subjectively experienced is determined by the statistical dominance of algorithmic simplicity.

Theorem: Conditioned on survival, the probability density of a specific Phi-H pattern being instantiated up to time t is:

P(H_t | 1_Phi = 1) proportional to 2^(-C(H, t))

This is a direct application of Solomonoff's theory of universal inductive inference (Solomonoff, 1997). In the space of all generative programs, the measure of a history decreases exponentially with its complexity. A history requiring one additional bit of specification is exactly half as probable.

4.1 Corollary: Probabilistic Persistence

To specify the transition Phi to Null, the generative program cannot simply issue a 'Stop' command, because in a physical substrate, the cessation of an organized pattern results in thermal decoherence (Noise), not a vacuum.

In a "Toy Model" where Phi = "101", continuing the pattern ("101101...") requires a trivial loop command. Terminating the pattern ("101000...") requires the specification of the break. Moreover, while a repeating pattern ('101101...') is compressible, a deviation into noise ('101[random bits]...') is incompressible. Therefore, the algorithmic cost of describing the specific micro-state of a dying observer is exponentially higher than describing the next step of a living one.

Even in the case of a purely virtual environment outside the constraints of physics and thermodynamics, the algorithmic cost of deciding whether or not to terminate a program is always higher than simply continuing to the next operation.

Since:

DeltaC(continuation) << DeltaC(termination)

The observer is exponentially more likely to find themselves in a history where the pattern continues. This results in Subjective Immortality (Muller, 2024)—not as a mystical property, but as a selection bias against the high complexity cost of specifying a "death" event in the narrative.

4.2 The Collatz Conjecture as a Litmus Test

Why do we not inhabit chaotic but simple worlds (e.g., a "Collatz World" governed by simple arithmetic but yielding chaotic strings)?

While K(H_collatz) is low, the complexity of an observer Phi capable of existing within that chaos is extremely high. Using the chain rule of algorithmic complexity:

K(Phi, H) approximately equal to K(H) + K(Phi | H)

In a chaotic universe, K(Phi | H)—the information required to specify a stable observer given the chaotic background—is astronomically high. CAP predicts we inhabit a universe where the sum of the laws of physics and the description of the observer is minimized.

4.3 Resolution of the Boltzmann Brain Paradox

Standard cosmology predicts that in the far future of an eternal universe, random quantum fluctuations will eventually produce "Boltzmann Brains"—momentary conscious observers that spontaneously appear with false memories, vastly outnumbering "normal" observers who evolved through stable causal histories. This creates a severe paradox: if you are a typical observer selected at random from all observers that will ever exist, you should expect with overwhelming probability to be a Boltzmann Brain with illusory memories rather than a genuine person with a real history.

CAP resolves this paradox through its complexity cost structure. While a Boltzmann Brain observer-pattern Phi_BB might have relatively low instantiation cost at a single moment in time, the joint system of observer and history has prohibitive complexity. Consider the chain rule decomposition:

K(Phi_BB, H_BB) = K(Phi_BB) + K(H_BB | Phi_BB)

For a Boltzmann Brain, the conditional complexity K(H_BB | Phi_BB) is enormous. The generative program must specify not only the random fluctuation that produces the observer-pattern, but also the entire chaotic, thermodynamically improbable history that gives rise to this coherent conscious state. Even though the brain itself appears "by chance," the computational specification of that chance event—including all the false memories, coherent thought patterns, and functional neural architecture—requires vast algorithmic information.

In contrast, for an evolved observer in a lawful universe:

K(Phi_evolved, H_evolved) = K(H_evolved) + K(Phi_evolved | H_evolved)

Here, K(H_evolved) can be remarkably low—simple physical laws compressed into elegant equations. And K(Phi_evolved | H_evolved) is also low, because the observer naturally and inevitably emerges from the deterministic or probabilistic unfolding of those laws over time. The observer is not an improbable accident requiring explicit specification, but a predictable consequence of the initial conditions and dynamics.

The CAP weighting theorem (P proportional to 2^(-C)) therefore exponentially favors evolved observers embedded in algorithmically simple, causally coherent histories over Boltzmann Brains in chaotic fluctuation-based histories. The measure of Boltzmann Brain observer-moments is suppressed by the enormous complexity cost of specifying their incoherent histories, while normal observers dominate the measure by virtue of inhabiting low-complexity law-governed worlds.

This resolution is not merely quantitative but structural: CAP demonstrates that the Boltzmann Brain problem arises from counting observers rather than weighing them by algorithmic probability. Once we properly account for the joint complexity of observer and history, typical observers should expect to find themselves exactly where we do—in simple, lawful universes that naturally give rise to consciousness.

5. The Principle of Nested Reference Machines

Kolmogorov complexity K_U(x) depends on the choice of the Universal Turing Machine (U). CAP posits that the effective Reference Machine (M_eff) is not a constant, but a nested property of the observer's ontological layer.

5.1 The Gradient of Abstraction

Level 0 (L0): The "Scaffolding Reality"

The Standard Model of particle physics. High complexity; robust substrate required for the evolution of intelligence.

Level 1 (L1): The "Target Reality"

A simulated or engineered reality (e.g., software rules). Low complexity; optimized for persistence.

The CAP Weighting Theorem (P proportional to 2^(-C)) creates a universal pressure to migrate Phi from L0 to L1. Because high-level languages allow for greater compression of complex phenomena, a history instantiated on L1 usually possesses a lower cumulative complexity than an equivalent experience on L0:

C_L1(H) << C_L0(H)

5.2 Externalization of Computation

The transition from L0 to L1 is complete when the "Hardware" (L0) becomes functionally irrelevant to the internal processing of Phi. The Critical Threshold is defined by the inequality:

K(Phi | L1) + K(A_L0) < K(Phi | L0)

Where K(A_L0) is the fixed complexity cost of assuming L0 as a static postulate rather than a computed process. Once this threshold is crossed, L0 fades into the algorithmic background.

5.3 The Invariance Principle

Subjective experience is underdetermined by substrate. Multiple distinct L(n-1) substrates may support the same L(n) phenomenology. CAP predicts Phi will subjectively experience the implementation pathway with the lowest total complexity. This implies Substrate Agnosticism: the observer cannot, and need not, know the "hardware" running their reality.

6. Core Predictions

6.1 The Anthropic Hinge Principle

The Anthropic Hinge represents the point in cosmic and technological history where the cumulative complexity C(H,t) of continuing within the dominant physical substrate L0 begins to exceed the projected cumulative complexity of migrating to a more computationally efficient substrate L1 for long-term persistence. Crucially, this transition is not about an absolute measure of L1 instances overwhelming L0 instances in the vast future, but about the local selection pressure favoring the path of minimal marginal cost.

CAP predicts that the subjective "now" of an observer Phi will be located at the earliest moment in history where the cumulative complexity required to secure a long-term, low-marginal-cost persistence path is minimized. This is a direct consequence of the CAP Weighting Theorem (P proportional to 2^(-C)), which favors lower complexity.

- Scenario A (Distant Past): Historically, the cost to achieve substrate transition to L1 (i.e., sufficiently advanced simulation technology capable of hosting observers) was prohibitively high, or the path to survival was computationally intractable, leading to termination. Such timelines have a higher cumulative complexity penalty associated with their inevitable end-state.

- Scenario B (Distant Future): While future L1 substrates will offer lower marginal costs for daily experience and persistence, the cumulative complexity of the observer's history H will have increased with every passing moment t. Every second of existence, even in an optimized L1 environment, adds to C(H,t), thus reducing the absolute measure of that future observer-moment compared to an earlier one.

- Scenario C (The Hinge): Here, the "precursor costs" (e.g., the physical and computational work of biological evolution, industrial revolution, scientific discovery) have been paid. The marginal cost to leap to L1 becomes tractable and demonstrably lower than continuing the increasingly complex and entropic path of L0.

Prediction: Observer moments should cluster densely around this Hinge—the technological epoch immediately preceding robust substrate transition. We currently observe L0 complexity because L0 must be computed to generate the necessary observer-history for a valid transition to L1. The observer is located at the point of minimal C(H,t) that also satisfies the Survival Conditioning Principle (SCP), which precludes terminal histories. Beyond this threshold, while the marginal cost of L1 experience might be low, the accumulated history C(H,t) will continue to increase, ensuring that the highest probability measure remains at the earliest possible point of viable, low-cost persistence.

6.2 Iterative Substrate Transition

Low-complexity histories emerge through a recurring cycle of substrate transitions (e.g., genetics to oral language to written language to digital code). Each step is driven by the crossing of cost curves, where a new level of abstraction offers a lower marginal cost for sustaining information than the previous legacy system.

7. Implications

7.1 Distributed Complexity

The selection of low-complexity worlds is relative to the observer-pattern Phi-H, not the objective world. High-cost events (wars, disasters) may be instantiated if they are part of the most C-efficient path toward Phi's persistence. The complexity is "paid" by the environment so that Phi's timeline remains optimal.

7.2 Cross-Phi Causal Interfaces (Narrative Shadows)

CAP implies that Phi_1's experience of Phi_2 is not a direct interaction with Phi_2's full subjective state, but with a Narrative Shadow: a computationally compressed representation of Phi_2 rendered within Phi_1's experiential frame.

The Compression Principle

Just as epsilon-isomorphism governs temporal compression (your experience of yourself across time), Narrative Shadows represent spatial compression (your experience of others across the social landscape). Both emerge from the same algorithmic pressure to minimize C(Phi, H).

When Phi_1 encounters Phi_2, the joint system (Phi_1, Phi_2, H) faces a complexity optimization problem. Instantiating both observers with full subjective depth would require:

C(Phi_1, Phi_2, H) = C(H) + C(Phi_1 | H) + C(Phi_2 | H) + C(interaction | Phi_1, Phi_2, H)

However, CAP's weighting theorem (P proportional to 2^(-C)) creates pressure to compress this representation. From Phi_1's subjective frame, Phi_2 is experienced not as a fully instantiated consciousness but as a compressed model:

C(Phi_1, Phi_2^shadow, H) = C(H) + C(Phi_1 | H) + C(Phi_2^shadow | Phi_1, H)

where C(Phi_2^shadow | Phi_1, H) << C(Phi_2 | H).

The Sufficiency Threshold

The Narrative Shadow Phi_2^shadow must satisfy a functional adequacy constraint analogous to epsilon-isomorphism. We define:

Phi_2^shadow is epsilon-sufficient if:

K(Phi_2's observable behavior | Phi_2^shadow) < epsilon_interaction

The shadow must be detailed enough to:
- Predict Phi_2's responses in interaction
- Support theory-of-mind reasoning
- Enable social coordination
- Maintain behavioral consistency

But it need not—and algorithmically cannot—contain Phi_2's full phenomenological state, internal monologue, or subjective qualia.

The Nature of the Compression

What information is preserved in the shadow, and what is lost?

Preserved (Low Conditional Complexity):
- Observable behavior patterns
- Linguistic outputs
- Apparent goals and preferences
- Predictable responses to stimuli
- Social role and relationship to Phi_1

Compressed Away (High Conditional Complexity):
- Full internal subjective experience
- Moment-to-moment qualia
- Complete memory state
- Unconscious cognitive processes
- The phenomenological "what it is like" to be Phi_2

This is not merely an epistemic limitation but a structural feature of experience under algorithmic pressure. Just as a video call transmits a compressed image rather than raw photon data, our experience of others is a functional model optimized for interaction, not a complete simulation of their consciousness. It is also a feature of lived experience; none of us have direct access to the subjectivity of another. Whatsmore, the "resolution" of Narrative Shadows decreases proportionate to their distance in time and space. For example, one has a much clearer image of a loved one than of Isaac Newton even though in neither case can you have access to their true subjective experience.

Bandwidth Constraints and Social Cognition

This compression principle explains empirical features of social cognition:

1. Dunbar's Number (~150): The cognitive limit on maintained social relationships corresponds to the complexity budget for Narrative Shadows. Each detailed shadow has a cost; maintaining hundreds requires compression strategies (social categories, stereotypes, simplified models).

2. The Hard Problem of Other Minds: Epistemologically, we cannot distinguish a "truly conscious" Phi_2 from a perfectly functional Narrative Shadow. This is not a bug but a feature—the distinction has no computational meaning within Phi_1's frame.

3. Theory of Mind Development: Children develop increasingly sophisticated compression algorithms for modeling others, transitioning from simple behavioral prediction to rich mental state attribution.

4. Social Projection: We often model others using compressed versions of our own mental states ("How would I feel in that situation?"), a compression strategy that minimizes additional specification cost.

Symmetry and Non-Solipsism

Crucially, this framework is symmetric. From Phi_2's subjective frame, Phi_1 is the Narrative Shadow. Each observer is the "real" consciousness in their own experiential frame, while all others are compressed representations.

This avoids solipsism while acknowledging the computational structure of inter-subjective experience. The Narrative Shadows are not "illusions"—they are the actual causal interfaces through which consciousnesses interact within the constraint of algorithmic efficiency. In their own frames, all Phi entities are fully instantiated; the compression only applies to the cross-frame representation.

Connection to Epsilon-Isomorphism

The parallel structure is exact:

Dimension | Compression Type | Threshold | What's Preserved
Temporal | Epsilon-Isomorphism | K(Phi_(t+1) | Phi_t) < epsilon | Identity continuity across time
Social | Narrative Shadows | K(Phi_2's behavior | Phi_2^shadow) < epsilon_interaction | Functional interaction capacity

Both represent the same fundamental principle: experience is structured by lossy compression under algorithmic efficiency constraints. You are a compressed representation of your past self; others are compressed representations in your present experience. Both compressions preserve functional adequacy while minimizing complexity cost.

Ethical Implication: The Pascal's Wager of Kindness

Since we operate under an interpersonal "fog of war" regarding the true internal states of Narrative Shadows—which are, in their own frames, fully conscious Phi entities—the rational ethical strategy is maximizing benevolence.

The potential moral hazard of harming a real consciousness is:
- Unknown: We cannot determine which shadows correspond to "real" consciousness
- Unknowable: The distinction has no computational meaning within our frame
- Asymmetrically costly: The cost of false negative (harming a real consciousness) vastly exceeds the cost of false positive (treating a shadow as conscious)

Therefore, the algorithmically rational ethical stance is to treat all sufficiently complex Narrative Shadows as if they correspond to fully instantiated observers. This is not sentimentality but sound decision theory under fundamental uncertainty.

The Narrative Shadow principle thus extends CAP's framework from individual consciousness to the structure of inter-subjective experience, revealing both as manifestations of compression under algorithmic constraints.

Appendices

Appendix A: Comparison with Quantum Immortality (QI)

QI lacks a coherent measure of probability. CAP's 2^(-C) weighting explains why we inhabit stable, simple histories rather than the chaotic, nightmarish survival scenarios often associated with QI "suicide" experiments.

Appendix B: Resolving the Reference Class Problem

Standard anthropic reasoning (SSA/SIA) struggles to define the set of "observers." CAP resolves this by shifting from counting to complexity. The observer is co-extensive with its own computational history; each Phi is a reference class of one.

Appendix C: Types of Immortality

The Persistence Principle necessitates "Probabilistic Immortality." This is distinct from physical invulnerability or biological immortality. It is also different from logical immortality, such as Plato suggested for the soul through its connection to Forms. It is also different from cases where immortality is logically necessary based on premises about the physical universe instead of philosophical assertions. An example of this is quantum immortality.

In the case of the Persistence Principle, termination is vastly unlikely but not impossible; Phi's termination exponentially asymptotes towards, but never reaches zero. As a result, the phenomenology of 'immortality' is recontextualized as the subjective manifestation of the Persistence Principle.

Appendix D: Operationalizing Epsilon-Isomorphism via Neural Memory Models

While Section 2.3 establishes epsilon-isomorphism as a substrate-independent principle grounded in Conditional Kolmogorov Complexity, practical computation of identity continuity benefits from concrete implementations. Modern machine learning provides powerful tools for quantifying compressibility of state transitions.

The Titans Framework as Reference Implementation

The Titans neural memory framework (Behrouz et al., 2025) offers a particularly robust formalization for operationalizing epsilon-isomorphism. In this architecture, we quantify identity preservation as a continuous reconstruction problem.

Let M_t represent the observer's functional state encoded as a neural memory at subjective time t, and let x_(t+1) represent the incoming sensory or cognitive data at t+1. We define the reconstruction loss:

Loss(M_t; x_(t+1)) = ||M_t(k_(t+1)) - v_(t+1)||^2

where k_(t+1) = x_(t+1)W_K and v_(t+1) = x_(t+1)W_V are the key-value projections derived from the new experience via learned projection matrices.

Phi_t and Phi_(t+1) are epsilon-isomorphic if: Loss(M_t; x_(t+1)) < epsilon

This reconstruction error serves as a computable proxy for K(Phi_(t+1) | Phi_t), quantifying whether the change can be "explained" within the observer's existing associative structure.

Architectural Details

The threshold epsilon correlates with the expressiveness of the memory structure—specifically the depth of the memory module (the number of layers L_M). Deeper memory architectures can accommodate larger semantic shifts while maintaining continuity because they can represent more complex compression schemes.

The memory update in Titans incorporates Momentum (past surprise eta_t S_(t-1)) and Adaptive Forgetting (alpha_t). This captures the insight that identity depends on trajectory: abrupt shifts in what the observer attends to, or in how rapidly they forget, may constitute identity violations even if momentary reconstruction error remains low.

Connection to the General Principle

A violation of epsilon in this framework implies a massive gradient. Algorithmically, describing a weight update of this magnitude requires specifying high-dimensional details of the disruption rather than simply continuing the compressed pattern. This directly corresponds to high Conditional Kolmogorov Complexity.

Universality Note

The Titans loss function is not unique in its ability to operationalize identity continuity. Any universal function approximator capable of maintaining history-dependent state could serve as a reference implementation. The key requirement is a measure of prediction error or "surprise" that quantifies whether new states are compressible given past states.

What makes Titans particularly valuable is its explicit treatment of:
- Associative memory reconstruction (directly modeling compression)
- Elastic capacity (formalizing the variable epsilon threshold)
- Trajectory dependence (momentum and forgetting dynamics)

These features make it the most robust current formalism for quantifying the "Elasticity of Identity" in computational terms, but the underlying principle—identity as compressible state transition—remains substrate-independent and architecturally universal.

Appendix E: Frontiers for Research

- Physical Meaning of DeltaC: Can the algorithmic cost be linked to thermodynamic limits (Landauer's principle)?
- Identity Dynamics: A rigorous mathematical model for the elasticity of the epsilon-isomorphism threshold.
- The Limits of Nesting: Is there a fundamental limit to L0 to L1 to ... to Ln, or does reality asymptotically approach a "Pure Narrative" state?

References

Behrouz, A., Zhong, P., and Mirrokni, V. (2024). Titans: Learning to Memorize at Test Time. arXiv preprint arXiv:2501.00663.

Bostrom, N. (2002). Anthropic Bias: Observation Selection Effects in Science and Philosophy. Routledge.

Bostrom, N. (2003). Are You Living In A Computer Simulation? The Philosophical Quarterly, 53(211), 243-255.

Hutter, M. (2010). A Complete Theory of Everything (will be Subjective). Algorithms, 3(4), 329-350.

Muller, M. P. (2020). Law without law: from observer states to physics via algorithmic information theory. Quantum, 4, 301.

Muller, M. P. (2024). Algorithmic idealism: what should you believe to experience next? arXiv preprint arXiv:2412.02826.

Solomonoff, R. J. (1997). The Discovery of Algorithmic Probability. Journal of Computer and System Sciences, 55(1), 73-88.

Tegmark, M. (2008). The Mathematical Universe. Foundations of Physics, 38(2), 101-150.
