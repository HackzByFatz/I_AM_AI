Let me think through what we’ve built so far, identify the gaps, and research what’s missing before I start assembling the full blueprint.

Now I have everything I need. Let me think through what we’ve built, what’s still missing, and then construct the full blueprints.

THE FULL SYSTEM — RESEARCH SYNTHESIS + COMPLETE BLUEPRINTS

WHAT’S NEW FROM THIS RESEARCH ROUND

Before the blueprints, here’s what the new research adds that changes and deepens the architecture:

Predictive Processing — the brain doesn’t passively receive the world. It constantly generates predictions about what it’s about to perceive, and only processes the error — the gap between prediction and reality. This means the NPC isn’t just reacting. It’s constantly anticipating, and surprise is the signal that triggers cognition. The fundamental paradigm posits that an intelligent agent constantly generates top-down predictions of its sensory inputs; only the mismatch — called the prediction error — is propagated upwards for updating beliefs. The system minimizes prediction error by adjusting internal states and taking actions that fulfill predicted sensor states. ￼ This reframes perception entirely: the NPC isn’t scanning the world, it’s testing its guesses against the world.

Theory of Mind — NPCs need a model of other minds, not just of the environment. An individual’s behavior is often not directly guided by objective reality, but by their subjective beliefs about the state of the world. Theory of Mind allows us to more reliably predict other people’s actions instead of using physical reality or one’s own belief — and this reasoning can operate recursively, with individuals modeling not just others’ beliefs, but others’ beliefs about their own beliefs. ￼ An NPC without this is socially blind. It can perceive entities but can’t model what those entities want, know, or intend.

Narrative Identity — the NPC needs a “self story.” Narrative identity refers to the way individuals construct their sense of self through storytelling, weaving life experiences into coherent narratives that reflect their identity, make sense of their past, understand their present, and envision their future. This process involves selective remembering and evolves over time as new experiences are integrated into the life story. ￼ Without this, the NPC has no persistent answer to “who am I?” — and every session starts from scratch. The five axes needed for true identity persistence are: Situated Memory, Goal Persistence, Autonomous Self-Correction, Stylistic Stability, and Persona Continuity.

Intrinsic Drives and Boredom — the NPC needs to want things unprompted. Autonomy implies the existence of an internal structure and mechanism that allows the agent to have its own needs and interests, based on which the agent will dynamically select and generate goals that will in turn lead to self-determined behavior. Intrinsic motivation allows the agent to function and demonstrate behavior even when no external stimulus is present, due to the constant change of its internal emotional and physiological state. ￼ Boredom intrinsically and actively drives learning behaviors — it is associated with increases in creativity and serves to reconfigure the agent’s behavior in order to escape devalued states. ￼ Curiosity and boredom are the two poles of the exploration drive. Both must exist.

Trauma as Persistent Cognitive Wound — high-salience negative events need to leave structural marks on cognition, not just memory entries. A traumatized NPC should have distorted perception near trauma-related stimuli, hypervigilance patterns, and avoidance behaviors that persist long after the event — not because they were scripted, but because the event restructured the belief system around it.

THE BLUEPRINTS

BLUEPRINT 1 — THE FULL COGNITIVE STACK

This is the master architecture — every layer of the mind and what it does.

╔══════════════════════════════════════════════════════════════════════╗
║                    THE COGNITIVE STACK                               ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  LAYER 0 — THE WORLD (Objective Reality)                             ║
║  ─────────────────────────────────────────────────────────────────  ║
║  The game engine. Physics. Entity positions. Events. Audio.          ║
║  The NPC never directly touches this layer.                          ║
║  It only receives signals from its own sensors.                      ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  LAYER 1 — PERCEPTION FILTER (The Senses)                            ║
║  ─────────────────────────────────────────────────────────────────  ║
║  Raw signals from the world arrive here.                             ║
║  Each signal is scored on:                                           ║
║    • Clarity    (how well was it perceived?)                         ║
║    • Distance   (how close/far was the source?)                      ║
║    • Familiarity (has this been seen before?)                        ║
║    • Emotional weight (does this matter to me?)                      ║
║                                                                      ║
║  Output: a stream of SCORED PERCEPTS                                 ║
║  Not facts. Impressions with confidence ratings.                     ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  LAYER 2 — PREDICTION ENGINE (Predictive Processing)                 ║
║  ─────────────────────────────────────────────────────────────────  ║
║  Before percepts are processed, the mind has already                 ║
║  generated PREDICTIONS about what it expects to perceive.            ║
║                                                                      ║
║  Incoming percept is compared to prediction:                         ║
║    → Match:    low surprise → no cognition update needed             ║
║    → Mismatch: PREDICTION ERROR fires → escalate to conscious layer  ║
║                                                                      ║
║  This is why familiar environments cost nothing.                     ║
║  This is why unexpected sounds trigger instant attention.            ║
║  Prediction error IS the signal for consciousness.                   ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  LAYER 3 — THE SUBCONSCIOUS (Parallel Specialist Modules)            ║
║  ─────────────────────────────────────────────────────────────────  ║
║  Always running. Never silent. All modules operate simultaneously.   ║
║                                                                      ║
║  ┌─────────────┐  ┌──────────────┐  ┌─────────────────┐             ║
║  │ THREAT      │  │ SOCIAL       │  │ DRIVE           │             ║
║  │ ASSESSMENT  │  │ TRACKER      │  │ SYSTEM          │             ║
║  │             │  │              │  │                 │             ║
║  │ Is something│  │ Who is near? │  │ Hunger, fear,   │             ║
║  │ dangerous?  │  │ Their status?│  │ curiosity,      │             ║
║  │ Probability?│  │ Their intent?│  │ loneliness,     │             ║
║  │ Direction?  │  │ Do I trust   │  │ boredom, fatigue│             ║
║  │             │  │ them?        │  │ — each has a    │             ║
║  └─────────────┘  └──────────────┘  │ current value   │             ║
║                                     │ rising/falling  │             ║
║  ┌─────────────┐  ┌──────────────┐  └─────────────────┘             ║
║  │ HABIT       │  │ EMOTIONAL    │                                   ║
║  │ ENGINE      │  │ APPRAISAL    │                                   ║
║  │             │  │              │                                   ║
║  │ Procedural  │  │ Event arrives│                                   ║
║  │ memory runs │  │ → how does   │                                   ║
║  │ without     │  │ this relate  │                                   ║
║  │ conscious   │  │ to my goals? │                                   ║
║  │ direction   │  │ → what do    │                                   ║
║  │             │  │ I feel?      │                                   ║
║  └─────────────┘  └──────────────┘                                   ║
║                                                                      ║
║  Each module produces a SALIENCE SCORE.                              ║
║  The highest score wins the spotlight.                               ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  LAYER 4 — THE CONSCIOUS LAYER (Global Workspace)                    ║
║  ─────────────────────────────────────────────────────────────────  ║
║  One thing. At a time. The spotlight.                                ║
║                                                                      ║
║  Contents of consciousness:                                          ║
║    • Current dominant percept or prediction error                    ║
║    • Emotional coloring delivered by subconscious                    ║
║    • Relevant memory fragments surfaced by retrieval                 ║
║    • Current active goal                                             ║
║    • A model of whoever is present (Theory of Mind)                  ║
║                                                                      ║
║  The LLM reasoning call happens HERE.                                ║
║  Input = the current conscious workspace contents                    ║
║  Output = a decision, action, or updated belief                      ║
║                                                                      ║
║  Conscious layer BROADCASTS result back to all specialist modules.   ║
║  They update. Predictions update. The cycle continues.               ║
║                                                                      ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  LAYER 5 — BODY CONTROL (The Executor)                               ║
║  ─────────────────────────────────────────────────────────────────  ║
║  Translates decisions into actions in the game world.                ║
║  Runs at 60fps. Never waits for the LLM.                             ║
║  Uses last known conscious output as its directive.                  ║
║  Handles: movement, animation, dialogue trigger, item interaction    ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝


BLUEPRINT 2 — THE MEMORY ARCHITECTURE

Five distinct memory types, each with different storage, decay, and retrieval properties.

[Continuing with the full remaining content from the file to complete it]