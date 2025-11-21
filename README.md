# mlrp: The Workshop Architecture
> Modular Context Stacks for High-Coherence Roleplay

**Current Status:** Production Release (V1)

## The Context
Four months ago, I posted a [Systems Architecture perspective](https://www.reddit.com/r/SillyTavernAI/comments/1lwmadx/character_cards_from_a_systems_architecture/) on r/SillyTavernAI proposing that character consistency is an engineering problem, not a creative writing problem.

At that time, I shared a rough proof-of-concept ("The Coffee Shop") via the `cepunkt/playground` repo. It demonstrated the core idea—separating the *Simulation* from the *Agent*—but lacked the structural rigidity to survive long-context entropy.

**This repository is the answer to that problem.**

I spent the last three months stress-testing this architecture in a "clean room" environment. The result is the **Workshop Architecture**: a modular constraint stack designed to prevent context collapse and "Helpful Assistant" drift in extended roleplay sessions.

## What's Inside

### 1. The Universal Narrator Stacks
Most "Context Dumps" fail because they mix physics, politics, and personal goals into one messy text block. This architecture uses **Modular Constraint Layers**:
* **Layer 1: Universe** (Physics, Magic Systems, Metaphysics)
* **Layer 2: World** (Geography, Geopolitics)
* **Layer 3: Region/Institution** (Local Laws, Social Norms)

These are "drop-in" modules. They handle the environment consequences so your character card doesn't have to.
* *Included Stacks:* Heritalis (Fantasy), Ostria-Thornwick (Political), Ikizen (Cultivation/Fantasy).

### 2. Production-Validated Character Cards
These are not standard "Waifu" cards. They are **System Agents** built using V2/V3 Positioning Specifications.
* **Quantity:** 19 Characters across 5 Scenarios.
* **Optimization:** Tuned to maintain "Kouhai" (Student/Subordinate) or "Expert" constraint topologies, specifically engineered to crush the "As an AI language model" refusal ridge.

### 3. The Methodology
Documentation on how to use **Context Positioning** to carve deep narrative valleys. This isn't just "Lore"; it's drift prevention engineering.

## Related Repositories
This is the **Product** layer. If you want to understand the *Engineering* or *Theory* behind it:

* **[cepunkt/mlcosplay](https://github.com/cepunkt/mlcosplay):** Applying these RP mechanics to serious engineering and chemistry collaboration.
* **[cepunkt/mlpoking](https://github.com/cepunkt/mlpoking):** The mechanical theory. Progressive elimination, constraint topology, and the mathematics of why "System Prompts" actually work.
