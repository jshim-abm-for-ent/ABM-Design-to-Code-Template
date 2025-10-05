# Example Canvas (Entrepreneurship Network ABM)

① Research Focus
Simulate how relational embeddedness (RE) and structural embeddedness (SE) affect founders’ resource acquisition probability (P) in an entrepreneurship network.

② Agents
- Types: founders (entrepreneurs), resource owners
- Founder attributes: nq, re, se, resource_gain, strategy
- Owner attributes: resource_level, preference
- Initialization: 80 founders, 40 owners; attributes initialized in [0,1]; random placement in 2D torus

③ Environment
- Space: 2D torus
- Initial links: each founder considers 3 random owners with 10% link formation probability
- Globals: lambda=0.005; alpha=0.5; beta=0.5; gamma=0.5; reinforce_rate=0.05; decay_rate=0.02
- Scenario flags: policy_mode (0/1/2)

④ Behavioral Rules
- Each tick, a founder contacts one owner.
- Success probability: P = 1 - exp( -lambda * nq^alpha * re^beta * (se + 1)^gamma )
- On success: resource_gain +0.1; link strength +0.05
- On failure: link strength -0.02

⑤ Interaction Mechanisms
- Target selection: uniformly random among linked owners
- Interaction type: resource exchange (owner resource_level decreases; founder resource_gain increases)
- Effects: strengthen link on success; drop link if strength<0.01

⑥ Dynamics
- Per tick: founders act → links decay
- Link decay: strength ← strength * (1 - decay_rate)
- Stop after 500 ticks

⑦ Metrics
- Agent‑level: mean resource_gain of founders
- System‑level: avg_P (mean acquisition probability), network_density, sys_performance (sum resource_gain)
- Output: plots + CSV log

⑧ Validation
- Sensitivity on lambda/alpha/beta/gamma
- 20 replications per parameter set

⑨ Scenarios
- policy_mode 0: baseline
- policy_mode 1: networking boost (increase link formation prob by 1.5×)
- policy_mode 2: resource subsidy (owners resource_level +0.1)

⑩ Interpretation
- Nonlinear effects of RE/SE on P
- Policy comparison on performance and structure
