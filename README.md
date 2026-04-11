# VERIFRAX-DOCS

Explanatory documentation surface for the governed Verifrax system.

## Terminal planes

- **[ANAGNORIUM](https://github.com/Verifrax/ANAGNORIUM)** — terminal recognition
- **[REGRESSORIUM](https://github.com/Verifrax/REGRESSORIUM)** — terminal recourse

## Status

* Layer: documentation and reader-orientation surface
* Repository class: explanatory and reference-adjacent documentation repository
* Upstream authored source: `VERIFRAX`
* Derived specification companion: `VERIFRAX-SPEC`
* Public verifier companion: `VERIFRAX-verify` at `https://verify.verifrax.net/`
* Artifact-chain relevance: must stay aligned with `artifact-0005` without claiming chain authority
* Public host ownership: `docs.verifrax.net`
* Package status: repository documentation surface, not a package by default
* License: Apache License Version 2.0

## One-sentence role

VERIFRAX-DOCS explains the current Verifrax system for readers and integrators without replacing authored protocol truth, derived specification publication, governed execution records, or evidence-root authority.

## What this repository is

VERIFRAX-DOCS is the explanatory documentation surface of the stack.

It exists to help a reader understand:

* how the repositories connect
* where authority comes from
* where execution happens
* where receipts come from
* where proof is published
* where verification is performed
* how artifact-chain statements should be read
* how artifact-0005 fits into the governed system boundary

This repository should improve legibility.

It should reduce ambiguity between:

* authored source
* derived specification
* profiles
* authority issuance
* governed execution
* proof publication
* verification UI
* archive and seal surfaces

## Host ownership lock

This repository must be the sole owning repository for `docs.verifrax.net`.

That host is the documentation surface only.

It must not become:

* the authority surface
* the execution surface
* the proof publication surface
* the verifier surface
* the intake surface
* the archive surface
* the evidence-root registry

## What this repository is not

VERIFRAX-DOCS is not:

* the upstream authored protocol repository
* the derived specification publication repository
* the governance root
* the authority issuance repository
* the governed runtime
* the public verifier UI
* the public proof publication repository
* the intake repository
* the evidence root
* the artifact registry of record
* the seal archive repository

VERIFRAX-DOCS does not:

* author normative protocol truth
* publish authority objects as authority of record
* emit governed execution receipts
* register artifacts into the official chain by itself
* replace VERIFRAX evidence files
* replace VERIFRAX-SPEC as specification publication
* replace VERIFRAX-verify as public verification surface
* replace proof publication or intake surfaces

If this repository starts defining instead of explaining, it becomes false.

## Authority and reading direction

The stack direction is fixed and must stay explicit here:

* VERIFRAX authors normative source material.
* VERIFRAX-SPEC publishes derived specification artifacts from VERIFRAX.
* VERIFRAX-PROFILES publishes deterministic profile constraints that do not change the spec.
* Derived artifacts are not upstream authority.
* Governance authority is external and bound through AUCTORISEAL plus the governed repo set in `.github`.
* CORPIFORM consumes authority and emits governed receipts.
* VERIFRAX records evidence-root truth and artifact registration.
* VERIFRAX-verify provides the public verifier surface at `https://verify.verifrax.net/`.

VERIFRAX-DOCS must explain that direction, not compete with it.

## Stack position

A reader should use this repository as an orientation layer around the actual system boundaries.

The correct reading order is:

1. `.github` — governance root and governed repository boundary
2. `AUCTORISEAL` — authority issuance and public authority publication
3. `CORPIFORM` — governed execution and receipt emission
4. `VERIFRAX` — authored source, evidence root, and artifact chain truth
5. `VERIFRAX-SPEC` — derived specification publication
6. `VERIFRAX-PROFILES` — profile constraints
7. `VERIFRAX-verify` — public verification surface
8. `proof` — proof publication surface
9. `apply` — intake surface
10. `SIGILLARIUM` — seal/archive surface where applicable

VERIFRAX-DOCS sits beside these as explanation, not above them as authority.

## Why artifact-0005 must appear here

Artifact-0005 is load-bearing for system legibility.

This repository must mention artifact-0005 because readers need one place that clearly explains the first public canonical authority-governed chain boundary without confusing:

* authority issuance
* execution runtime
* receipt generation
* evidence registration
* public verification

But this repository must not say that artifact-0005 is complete, sealed, or registered unless the evidence root in VERIFRAX already proves it.

That is the controlling rule.

So the documentation duty is:

* explain what artifact-0005 is supposed to connect
* link readers to the actual evidence root
* avoid turning explanation into false status assertion

A docs repository that overstates chain truth is worse than missing docs.

## Why the verifier must appear here

The public verifier is one of the few externally legible surfaces of the stack.

VERIFRAX-DOCS must therefore keep `VERIFRAX-verify` visible and properly bounded.

The correct statement is:

* the public verifier surface is `VERIFRAX-verify`
* the public verifier URL is `https://verify.verifrax.net/`
* the public verifier verifies according to published rules and visible constraints
* the verifier is not the authority issuer
* the verifier is not the proof publisher
* the verifier is not the execution runtime

If docs blur verifier and proof, readers misread the system.

## Documentation boundary

This repository should explain these surfaces clearly:

* `.github` — governance root
* `VERIFRAX` — authored source and evidence root
* `VERIFRAX-SPEC` — derived specification publication
* `VERIFRAX-PROFILES` — profile constraints
* `AUCTORISEAL` — authority issuance/reference
* `CORPIFORM` — governed execution/receipt runtime
* `VERIFRAX-verify` — public verification UI
* `proof` — public proof publication
* `apply` — public intake
* `SIGILLARIUM` — seal/archive reference surface
* `ARCHITECTURE` — system topology explanation

This repository should never imply that all explanations originate here.

## Inputs and outputs

### Inputs consumed by this repository

VERIFRAX-DOCS consumes:

* authored source context from VERIFRAX
* derived publication context from VERIFRAX-SPEC
* governance and authority context from `.github` and AUCTORISEAL
* execution and receipt context from CORPIFORM
* verifier-boundary context from VERIFRAX-verify
* proof/publication context from proof
* intake-boundary context from apply
* artifact-chain context from VERIFRAX evidence surfaces

### Outputs produced by this repository

VERIFRAX-DOCS produces:

* explanatory pages
* repository relationship guides
* integration and reading-path documentation
* clarification of boundary conditions
* verifier- and artifact-aware navigation material

It does not produce authoritative chain truth by itself.

## Public surface relationship

This repository should link outward to the canonical public surfaces that a reader needs to understand the system.

Those include:

* `https://api.verifrax.net/` — execution surface
* `https://proof.verifrax.net/` — proof publication surface
* `https://verify.verifrax.net/` — public verifier surface
* `https://auctoriseal.verifrax.net/` — authority surface
* `https://corpiform.verifrax.net/` — runtime reference surface
* `https://cicullis.verifrax.net/` — enforcement reference surface
* `https://sigillarium.verifrax.net/` — archive/seal reference surface
* `https://apply.verifrax.net/` — intake surface

But this repository should not claim ownership of those surfaces unless deployment truth proves that.

## Artifact-chain discipline

When describing artifacts here, the rule is strict:

* explanation is allowed
* official registration is not claimed unless VERIFRAX evidence proves it
* seal language is forbidden unless the evidence root already uses it truthfully
* current-status wording must not outrun the artifact directory of record

For artifact-0005 specifically, docs may explain the intended chain boundary and link the reader to its evidence path.

Docs may not silently promote artifact-0005 to finished truth.

## Failure modes this README must prevent

This repository fails if its README:

* sounds like upstream protocol authority
* sounds like specification authorship
* sounds like evidence-root truth
* omits artifact-0005 entirely
* omits the public verifier entirely
* merges proof and verify into one role
* merges docs and architecture into one false authority source
* claims host ownership without deployment proof
* uses aspiration as current state

The weak case is a generic docs README.

The harder failure is a docs README that quietly becomes false system governance.

## Reader contract

A reader landing here must be able to answer these six questions quickly:

1. What is this repo for?
2. What does it not do?
3. Where does authority actually come from?
4. Where does governed execution happen?
5. Where is artifact-0005 actually proved?
6. Where is the public verifier?

If the README fails any one of those, the repository remains incomplete.

## Canonical related repositories

* [`.github`](https://github.com/Verifrax/.github) — governance root
* [`VERIFRAX`](https://github.com/Verifrax/VERIFRAX) — authored source and evidence root
* [`VERIFRAX-SPEC`](https://github.com/Verifrax/VERIFRAX-SPEC) — derived specification publication
* [`VERIFRAX-PROFILES`](https://github.com/Verifrax/VERIFRAX-PROFILES) — profile constraints
* [`AUCTORISEAL`](https://github.com/Verifrax/AUCTORISEAL) — authority issuance/reference
* [`CORPIFORM`](https://github.com/Verifrax/CORPIFORM) — governed execution and receipts
* [`VERIFRAX-verify`](https://github.com/Verifrax/VERIFRAX-verify) — public verifier
* [`ARCHITECTURE`](https://github.com/Verifrax/ARCHITECTURE) — topology explanation
* [`proof`](https://github.com/Verifrax/proof) — proof publication surface
* [`apply`](https://github.com/Verifrax/apply) — intake surface
* [`SIGILLARIUM`](https://github.com/Verifrax/SIGILLARIUM) — seal/archive surface

## CI and governance expectations

This repository should only claim checks that are materially real for documentation integrity, reference integrity, and boundary truth.

At minimum, documentation claims here should remain aligned with:

* governance truth from `.github`
* authored source truth from VERIFRAX
* derived specification truth from VERIFRAX-SPEC
* authority boundary truth from AUCTORISEAL
* runtime boundary truth from CORPIFORM
* public verifier boundary truth from VERIFRAX-verify
* artifact-chain truth from VERIFRAX evidence files

README narrative is not a substitute for those sources.


## Verifrax system path labels

The governed Verifrax path that this README must stay compatible with is:

1. `.github` — organization governance and governed repository boundary
2. `AUCTORISEAL` — authority issuance and public authority reference
3. `CORPIFORM` — governed execution and receipt emission
4. `VERIFRAX` — authored protocol, evidence root, and artifact-chain registration boundary
5. `VERIFRAX-SPEC` — derived specification publication surface
6. `VERIFRAX-PROFILES` — deterministic profile-constraint surface
7. `VERIFRAX-SAMPLES` — pinned sample and reproducibility surface
8. `VERIFRAX-verify` — public verification repository and UI boundary
9. `VERIFRAX-DOCS` — explanatory documentation surface
10. `cicullis` — enforcement boundary
11. `proof` — proof publication surface
12. `SIGILLARIUM` — seal and archive reference surface
13. `apply` — intake surface

The live host-label map that must remain explicit and non-contradictory is:

* `https://api.verifrax.net/` — execution surface
* `https://proof.verifrax.net/` — proof publication surface
* `https://auctoriseal.verifrax.net/` — authority issuance and authority reference surface
* `https://corpiform.verifrax.net/` — runtime and receipt reference surface
* `https://cicullis.verifrax.net/` — enforcement reference surface
* `https://verify.verifrax.net/` — public verification surface
* `https://sigillarium.verifrax.net/` — seal and archive reference surface
* `https://apply.verifrax.net/` — intake surface
* `https://docs.verifrax.net/` — documentation surface

This README must remain compatible with `artifact-0005` as the load-bearing authority → execution → verification → evidence boundary without claiming that this repository alone authors, proves, seals, or registers `artifact-0005` unless that role is actually true for this repository.


## Security

A documentation error here can distort how operators, readers, and outsiders interpret authority and artifact boundaries.

Security-sensitive failure classes include:

* false authority claims
* false artifact-0005 completion claims
* incorrect verifier or proof boundary statements
* incorrect execution-host explanations
* stale or misleading public-surface references

## Contributing

Changes to this repository must remain explanation-only and system-accurate.

A contribution is wrong if it:

* adds placeholder prose
* adds aspirational present-tense claims
* weakens the authored/derived distinction
* weakens artifact-0005 boundary discipline
* weakens verifier visibility
* invents host ownership
* invents package/publication status
* turns this repository into a parallel source of truth

## License

Apache License Version 2.0. See `LICENSE`.

## Adjacent sovereign surfaces

This repository is part of the Verifrax sovereign stack and remains bounded relative to:

- **[ANAGNORIUM](https://github.com/Verifrax/ANAGNORIUM)** for terminal recognition
- **[REGRESSORIUM](https://github.com/Verifrax/REGRESSORIUM)** for terminal recourse

