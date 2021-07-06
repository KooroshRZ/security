This is a repo for Threat modelling cheat sheets:
Visit https://insights.sei.cmu.edu/blog/threat-modeling-12-available-methods/ for Threat Modeling: 12 Available Methods. #Methods

1
STRIDE and Associated Derivations

Invented in 1999 and adopted by Microsoft in 2002, STRIDE is currently the most mature threat-modeling method. STRIDE has evolved over time to include new threat-specific tables and the variants STRIDE-per-Element and STRIDE-per-Interaction.

STRIDE evaluates the system detail design. It models the in-place system. By building data-flow diagrams (DFDs), STRIDE is used to identify system entities, events, and the boundaries of the system. STRIDE applies a general set of known threats based on its name, which is a mnemonic, as shown in the following table:

![Uploading image.png…]()
Table 1: STRIDE Threat Categories

STRIDE has been successfully applied to cyber-only and cyber-physical systems. Although Microsoft no longer maintains STRIDE, it is implemented as part of the Microsoft Security Development Lifecycle (SDL) with the Threat Modeling Tool, which is still available. Microsoft also developed a similar method called DREAD, which is also a mnemonic (damage potential, reproducibility, exploitability, affected users, discoverability) with a different approach for assessing threats.
