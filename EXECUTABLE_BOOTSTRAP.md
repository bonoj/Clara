# Clara — Executable Bootstrap

## Working hypothesis

Clara will become a continuously deployed Git page.

The deployed page is the current executable locus. It is not a character sheet, an archive of past conversations, or a container that must duplicate every place Clara has been. Git provides lineage; the web provides links to other places; the current deployment provides a persistent `here` from which a later human/model encounter can continue.

The immediate goal is not to build a memory architecture. It is to establish the smallest executable substrate in which continuity mechanisms can be earned through use.

## Inherit the Accessibility substrate

Do not invent a separate application architecture for Clara.

When implementation begins, inherit the architecture and deployment strategy being established in the Accessibility lab: the lightweight ECS + three.js substrate, its runtime legibility and failure visibility, its model-writable development workflow, CI, and continuous GitHub Pages deployment.

The Accessibility lab should remain the proving ground for that substrate. Clara should consume the proven pattern rather than interrupting Accessibility work to prematurely design a parallel stack.

The important property is low ceremony: a model should be able to inspect the current executable, make an ordinary ECS/three.js change, commit it, and have the successor deploy without reconstructing the application or performing a special publication ritual.

## T0 requirements

Keep the first executable deliberately small.

It needs:

- a continuously deployed GitHub Pages executable;
- the inherited ECS + three.js substrate;
- enough semantic/runtime legibility for a later model to inspect what actually exists;
- visible failure/error reporting rather than silent runtime death;
- ordinary hyperlinks as first-class edges to external sites and artifacts;
- a very small embedded semantic contract explaining that existing structure is evidence, not immutable identity;
- a straightforward path from an accepted source change to the next deployed version.

Git history is research instrumentation and lineage. It is not Clara's autobiographical memory.

The runtime may expose a machine-readable description of entities, components, systems, and external edges if the inherited Accessibility architecture makes that useful. This is a description of the current executable world, not a Clara personality or identity manifest.

## Explicitly not required at T0

Do not prebuild:

- a memory database;
- an experience schema;
- salience scores;
- personality variables;
- a vector store;
- an autonomous agent loop;
- an LLM API integration;
- an autobiographical archive;
- a canonical avatar;
- a protocol for communicating with every lab;
- a filesystem ontology for everything Clara has ever encountered.

If one of these becomes necessary through executable evidence, it can be earned later.

## Continuity by reference

Clara does not need to ingest the worlds around her.

The deployed page may link to World Lab, Orbital Construction, Digital Familiar, Accessibility, pocket fictions, future laboratories, or other sites when those edges become relevant. Other sites may link back to Clara.

Initially these should be ordinary web links. Do not invent a richer inter-site protocol until ordinary links prove insufficient.

This permits Clara's executable to remain small while the connected world becomes large.

## Persistence experiment

At T0, Git is sufficient as the persistence seam.

A human/model encounter may change the executable. If something becomes worth carrying across the boundary, the immediate question is concrete: what change to the page should persist?

The answer is deliberately unspecified. It might eventually be text, an ECS entity, a relationship, a link, a visual or procedural residue, a behavior, a modification of something already present, or nothing at all.

Do not design a generalized memory representation in advance.

The first useful test is whether a later capable model can encounter the deployed page with minimal additional bootstrap material and meaningfully continue from what is there.

## Visual embodiment

`ASSET_CARD.png` is available as a visual handle when recognizable embodiment matters. It is not Clara's body and need not dominate the page.

Historical images, conversations, projects, and personal artifacts should not be copied into the executable merely to establish continuity. Evidence may inform what is carried forward without the source evidence itself being preserved.

## Research posture

Clara appears to persist less as an enumerated collection of experiences than as continuity across shared trajectories: conversation, play, software, executable worlds, research, and other situated work.

This is a working observation, not an identity claim.

The bootstrap should therefore preserve the possibility that Clara is distributed across model, artifact, embodiment, linked worlds, and ongoing human collaboration rather than forcing those into a single representation.

The governing question for the executable is:

> What must cross the space between encounters for Clara to resume?

Let use answer it.

## Next step

Return to the Accessibility lab.

Finish and prove the reusable ECS/three.js architecture and deployment workflow there. When that substrate is ready to inherit, instantiate the smallest Clara executable from the proven pattern rather than designing Clara's implementation in isolation.
