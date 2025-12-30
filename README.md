# Systems That Decide What Matters

This repository is a long-term learning and research log focused on **how modern systems decide what is real, what is reliable, and what humans (or machines) should act on**.

It sits at the intersection of:
- identity & entity resolution
- data representation and embeddings
- AI inference and decision systems
- trust, confidence, and provenance
- human attention and judgment

The goal is not to collect tools or tutorials, but to develop **clear mental models, system primitives, and working prototypes** for building trustworthy decision systems in an increasingly automated world.

---

## Why This Repo Exists

Modern software systems are no longer passive.
They don’t just store data, they **make decisions**:

- which users are the same person
- which signals deserve credit
- which risks should be flagged
- which news matters today
- which entities are trustworthy
- which outputs humans should act on

Yet most systems:
- hide uncertainty
- collapse identity into IDs
- confuse representation with truth
- optimize for speed over understanding

This repository exists to explore a different approach:

> Systems that **form beliefs explicitly**, track evidence, reason over time, and remain accountable to human judgment.

---

## Scope (What Lives Here)

This repo intentionally spans multiple layers of the stack.

### Foundations
- First-principles thinking about identity, trust, and decision-making
- Mathematical representations (probability, similarity, geometry)
- Algorithms and assumptions behind matching, classification, and inference

### Representations
- Entity resolution and identity modeling
- Embeddings and vector spaces
- Hyperdimensional representations
- Spatial data and place identity

### Inference, Reasoning & Memory
- NLP, NER, and semantic extraction
- Structured LLM inference (DSPy, BAML-style contracts)
- Classification and decision logic
- Confidence, evidence, and provenance

### Systems
- Knowledge graphs and multimodal reasoning
- AI inference & serving (e.g. vLLM-style systems)
- Data engineering and storage models
- Distributed systems and software architecture

### Human-Centered Outcomes
- Decision systems and human attention
- When systems should *not* act
- Trust boundaries, escalation, and review
- Data sovereignty and verifiable trust

This is **not** a product repo.
It is a **thinking + building repo**.

---

## Structure (Evolving)

```

/notes/
    identity-entity-resolution.md
    embeddings-and-representation.md
    trust-confidence-provenance.md
    spatial-identity.md
    decision-systems.md

/projects/
    entity-resolution-prototype/
    news-claims-tracking/
    place-reality-profile/

/math/
    similarity-distance.md
    probability-and-belief.md
    geometry-of-embeddings.md

/reading/
    papers.md
    books.md
    talks.md

/design/
    system-diagrams.md
    decision-flows.md
```

The structure will evolve as understanding deepens.

---

## How This Repo Is Used

This repository is updated incrementally, often with:
- short notes after reading or experiments
- sketches of system designs
- small prototypes or proof-of-concepts
- reflections on failures or limitations

Not every commit represents a “finished” idea.
The emphasis is on **learning in public with rigor**.

---

## Guiding Principles

- Identity is a belief, not a fact  
- Representation matters more than models  
- Confidence should be first-class data  
- Decisions are different from predictions  
- Systems shape human attention  
- Automation must remain accountable  

---

## Long-Term Direction

Over time, this work may inform:
- applied research
- infrastructure projects
- open-source tools
- writing and talks
- or production systems


---

## Status

Active, evolving, and intentionally unfinished.

---

## About

Maintained by Dennis Irorere.  
This repository reflects personal learning and experimentation.  
Opinions and mistakes are my own.

If you’re interested in similar problems around identity, trust, and decision systems, feel free to explore, reference, or reach out.
