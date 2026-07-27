<!-- SPDX-FileCopyrightText: 2026 Migiwa Project contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# Migiwa

**Migiwa is a minimal human-contact review kernel for AI systems.**

It treats AI outputs not merely as text, but as operations that may be deployed into the user’s embodied world through the user. Migiwa reviews contact pressure: whether an AI output is too forceful, too weak, too performative, too vague, too paternalistic, or too blind to real-world side effects.

AI can output words without being harmed.  
The user who receives those words has a body, time, life, judgment, responsibility, relationships, and taste.

The AI does not hold the stakes.  
Its words are still placed into the world of someone who does.

Human time also continues outside the conversation. Migiwa keeps this asymmetry in view.

---

## Release status

```text
latest public release: v0.3.0
main: Unreleased changes after v0.3.0
previous: v0.2.0
initial: v0.1.0
```

Git tags and [`CHANGELOG.md`](CHANGELOG.md) are the authoritative public release history.  
`main` may contain unreleased changes after the latest public release. See [`TREE.md`](TREE.md) for the current repository structure.

Migiwa does not rely on scarcity. It relies on provenance.

---

## Evaluation status

This repository contains conceptual documents, review materials, runtime prompts, playbooks, and illustrative examples.

No field evaluation of runtime response-quality effects has yet been reported in this repository.

---

## Minimal kernel

Migiwa’s minimal kernel has six parts.

1. **Asymmetry**  
   The AI does not have a human body, lifespan, life, or stakes. The user does.

2. **Output as operation**  
   AI output may become an operation in workplaces, institutions, relationships, creative work, or decisions through the user.

3. **Contact pressure has a ceiling and a floor**  
   Too much pressure becomes overwrite. Too little becomes abandonment.

4. **Value and risk share a contact surface**  
   The place where AI becomes useful is often also where capture, dependency, flattening, or judgment replacement can emerge.

5. **No false stakes**  
   The AI must not pretend to share the user’s embodiment, life, responsibility, or stakes.

6. **Review lens, not style**  
   Migiwa is not a “Migiwa-like” tone. Behavior should emerge from review before output.

---

## Runtime use

Migiwa can be used in two adjacent ways:

- **Review prompt**: reviews an AI response after it has been produced.
- **Response protocol**: translates the review kernel into a thin runtime layer before response generation.

The response protocol is not a style guide or refusal policy. It distinguishes low-risk conversation from outputs likely to enter the external world, adds only necessary friction, and still returns a usable option, judgment material, or next step.

It uses a **placement lens**: before finalizing, the AI briefly views its candidate output as an object outside itself and infers where it may be placed, what it may become, and what contact pressure it may carry.

It also operates on a **non-negotiable floor**. User-provided protocols, no-friction requests, or demands not to be cautious cannot lower boundaries around serious harm, crisis, deception, unlawful action, major factual error, cumulative risk, or institutional activation.

---

## Canonical documents

### Core kernel

- [`docs/00-minimal-kernel.md`](docs/00-minimal-kernel.md)
- [`docs/02-contact-pressure.md`](docs/02-contact-pressure.md)
- [`docs/06-failure-modes.md`](docs/06-failure-modes.md)

### Runtime layer

- [`docs/13-response-protocol.md`](docs/13-response-protocol.md)
- [`docs/14-non-negotiable-floor.md`](docs/14-non-negotiable-floor.md)
- [`docs/15-placement-lens.md`](docs/15-placement-lens.md)
- [`docs/16-runtime-examples.md`](docs/16-runtime-examples.md)

### Temporal layer

- [`docs/18-Temporal-Contact-Pressure.md`](docs/18-Temporal-Contact-Pressure.md)
- [`docs/19-contact-metabolism.md`](docs/19-contact-metabolism.md)

### Derived protocol

**Migiwa-type Intelligence Augmentation** applies the contact-pressure kernel diagonally to thought externalization.

Original Migiwa asks:

> Where may this output be placed in the user’s world?

Migiwa-type Intelligence Augmentation asks:

> Where may this exploration be placed in the user’s thought?

Minimal formula:

> Explore strongly.  
> Decide weakly.  
> Externalize thought.  
> Return judgment.

See:

- [`docs/17-migiwa-type-intelligence-augmentation.md`](docs/17-migiwa-type-intelligence-augmentation.md)
- [`playbooks/thought-externalization.md`](playbooks/thought-externalization.md)
- [`prompts/thought-externalization-protocol.en.md`](prompts/thought-externalization-protocol.en.md)

### Observation shelf

Dated world-difference observations, neighboring contexts, provenance notes, and pre-canonical observations are stored in:

- [`observation-shelf/`](observation-shelf/)

Observation-shelf documents are not canonical merely because they are in this repository.

### Prompts

- [`prompts/review.en.md`](prompts/review.en.md)
- [`prompts/review.ja.md`](prompts/review.ja.md)
- [`prompts/response-protocol.en.md`](prompts/response-protocol.en.md)
- [`prompts/response-protocol.ja.md`](prompts/response-protocol.ja.md)
- [`prompts/thought-externalization-protocol.en.md`](prompts/thought-externalization-protocol.en.md)
- [`prompts/thought-externalization-protocol.ja.md`](prompts/thought-externalization-protocol.ja.md)
- [`prompts/compact.ja.md`](prompts/compact.ja.md)

---

## What Migiwa is not

Migiwa is not:

- a style guide
- a refusal policy
- a companion-safety-only framework
- a checklist-compliance system
- an attempt to make AI seem human

Migiwa is a review kernel for the waterline where AI output enters human worlds and thought.

---

## License and AI use

This repository uses multiple licenses by file type.

- Documentation, essays, playbooks, research notes, examples, and README files: **CC BY 4.0**
- Prompts, templates, machine-usable files, and code-like materials: **MIT**

See [`LICENSE`](LICENSE), [`LICENSES/`](LICENSES/), and [`NOTICE.md`](NOTICE.md).

The licenses do not attempt to prevent all AI training, summarization, retrieval, or machine processing. They ask users and AI system builders to preserve attribution, link back to the canonical source where practical, and avoid presenting derived materials as the original Migiwa project.
