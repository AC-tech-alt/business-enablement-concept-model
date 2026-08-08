# Business Enablement Concept Model

A shared, plain-language model of how a strategic priority moves from problem to sustained business impact inside a matrixed operating environment — the kind of environment where a "business enablement" function (Business, Operations, Technology/Data, Domain Specialists, and Field all touching the same initiative) is responsible for turning strategy into adopted, value-producing execution.

**Status: early / pre-alpha.** This is a first pass at defining the concepts, relationships, and rules in plain language, before any of it becomes a formal schema. It is meant to be stress-tested against real initiatives, not treated as finished.

## Why this exists

Most status reports treat "we launched it" and "it's working" as the same fact. They aren't. A workflow can be fully built, trained on, and technically live while nobody is actually using it six months later. That gap — between designed, executed, and adopted — is where a lot of strategic initiatives quietly fail without anyone being able to say exactly where or why.

This project tries to name each stage of that lifecycle precisely enough that a business leader, an operations lead, and an engineer would all recognize the same definition — the same goal as [Evani Govender's CommonGood Atlas](https://www.linkedin.com/pulse/grant-payment-why-grantmaking-systems-need-shared-evani-govender-rn5bc/), which does this for grantmaking. This project applies the same approach to cross-functional business enablement and delivery.

## Structure

- [`concepts/`](./concepts) — one file per core concept: definition, properties, relationships, rules
- [`roles.md`](./roles.md) — how ownership of a concept shifts across a 5-function operating model (Business, Operations, Technology/Data, Domain Specialists, Field), rather than staying fixed to one team
- [`relationships.md`](./relationships.md) — a worked example tracing a business problem through to measured value, and where the handoffs typically break

## Core concepts at a glance

| Concept | One-line definition |
|---|---|
| [Business Problem](./concepts/business-problem.md) | A validated gap between current and desired state, named by a domain leader |
| [Initiative](./concepts/initiative.md) | The chartered effort to close a Business Problem |
| [Workflow](./concepts/workflow.md) | The designed sequence of steps, roles, and systems that operationalizes part of an Initiative |
| [Execution Plan](./concepts/execution-plan.md) | The concrete build-out of a Workflow |
| [Field Readiness](./concepts/field-readiness.md) | The state where people have what they need to run the Workflow |
| [Adoption](./concepts/adoption.md) | Sustained, observed use of the Workflow under normal operating pressure |
| [Value Realization](./concepts/value-realization.md) | The measured outcome the Initiative was chartered to produce |

## What this is not (yet)

This is not a formal ontology — there's no RDF/OWL/SHACL representation, no graph database, no visual explorer. Those are the natural next steps if this holds up under real-world testing, following the same technical pattern CommonGood Atlas uses. Right now it's a plain-language starting point.

## Feedback welcome

Where are the definitions too rigid? Which concept is missing? Where does a stage get skipped in practice? Open an issue or a PR.

## License

MIT — see [LICENSE](./LICENSE).
