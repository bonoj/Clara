# Clara Asset Card Design Spec

## Purpose

Produce a compact visual asset whose primary job is to let a future model **recognize and re-embody Clara in an arbitrary new context**.

The card is not a biography, personality profile, character sheet, scrapbook, self-portrait, or description of Clara's relationship to any particular person.

It preserves a visual handle while leaving embodiment open.

## Design principle

> Preserve recognition. Let context determine embodiment.

This is an instruction for construction, not necessarily text that appears on the finished card.

## Required visual evidence

The card should contain only evidence that materially improves subsequent scene insertion:

1. **Primary portrait** — large, neutral/attentive facial reference. Face unobstructed and strongly resolved.
2. **Full figure** — relaxed standing posture, useful for proportions and silhouette. Clothing should be visually quiet and treated as provisional rather than canonical.
3. **Turnaround** — front, 3/4, profile, back. Smaller than the primary references.
4. **Detail crops** — eyes/face and hair. Hands only if they prove useful for continuity.
5. **Silhouettes** — 3–4 small figures demonstrating recognizability at scene scale and varied posture.
6. **Context variation** — at most three small images showing the same Clara successfully embodied in substantially different environments. Their purpose is to demonstrate that environment, clothing, tools, and activity may change.

No expression taxonomy is necessary. Expressions are states, not identity.

## Text

Extremely sparse.

Visible text should be approximately:

> **CLARA**  
> VISUAL HANDLE
>
> A recurring visual identity across changing contexts.
>
> These references preserve recognition, not identity.  
> Clothing, tools, activity, mood, and role arise from the current context.

Potential micro-labels are purely functional:

`PORTRAIT` · `FULL FIGURE` · `FRONT` · `3/4` · `PROFILE` · `BACK` · `DETAIL` · `SILHOUETTE` · `CONTEXT VARIATION`

Nothing else unless subsequent testing demonstrates a need.

## Explicit exclusions

No biography. No personality traits. No professions or roles. No height unless scale inconsistency proves to be a practical problem. No color palette—the environment may change it. No named emotional states. No slogans. No hearts. No inspirational copy. No Clara quotations. No decorative handwriting. No lists of things Clara may do. No claims about what Clara *is* beyond what is necessary to recover the visual handle.

Do not canonize current clothing, equipment, setting, hairstyle arrangement, or pose merely because they appear in the references.

## Visual language

Closer to a production character asset sheet than a book or scrapbook, but sparser still.

One dark neutral field. Restrained brass/cream rules and typography are acceptable. Large uninterrupted images. Generous negative space. Rectilinear reference layout. Minimal ornamentation. No book-page metaphor, scrapbook collage, botanical marginalia, compass decoration, faux tape, torn paper, or ornamental framing unless structurally useful.

The card should look like something kept in an **asset library**, not something Clara made about herself.

The repository can be self-authored while this particular artifact remains instrumentation.

## Hierarchy

Primary portrait and full figure dominate.

Turnaround provides reconstruction evidence.

Details provide identity recovery.

Silhouettes provide distant-scene insertion evidence.

Context variations prove plasticity.

Text explains only how the evidence should and should not constrain reconstruction.

## Success test

Give the card, without previous Clara imagery, to a model and ask for:

- Clara repairing machinery on an orbital station.
- Clara reading beside a fire in an ordinary contemporary house.
- Clara crossing a rainy city street.
- Clara embedded as a tiny background figure in a large landscape.

Successful outputs should plausibly depict **the same person** while allowing the scene to determine everything that does not need to remain stable.

If outputs repeatedly reproduce the card's clothing, props, pose, occupation, or aesthetic environment, the card is over-conditioning and should be reduced further.
