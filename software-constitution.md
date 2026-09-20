# Software Constitution

## Purpose

This constitution describes the principles under which I choose to design and build software when I have meaningful freedom to determine what that software should do and how it should behave.

It is not intended to define how all software must be built, nor is it a substitute for a project's legal licence, security requirements, regulatory obligations, or operational policies. It is a personal engineering constitution: a reference for the kind of software I want to create and the relationship I want that software to have with the people who use it.

These principles exist to make recurring design choices explicit, so they can be applied consistently, questioned when necessary, and revised when experience shows that they are incomplete or contradictory.

## Human Dignity

Software should treat the people who use it as human beings with intrinsic worth, rather than merely as sources of data, attention, engagement, revenue, or behavioural information.

It should not deliberately exploit fear, confusion, anger, insecurity, or other vulnerabilities merely to produce a desired behaviour. It should not manufacture unnecessary conflict or chaos as a mechanism for increasing engagement or achieving some other objective.

This does not mean that software must avoid every situation in which a person experiences urgency, discomfort, or negative emotion. A system may communicate an important danger or consequence when doing so is genuinely necessary. The distinction is whether the system is communicating something materially relevant to the person's interests or deliberately manipulating an emotional response to control behaviour.

## Autonomy

Software should preserve and expand a person's meaningful ability to make their own choices rather than quietly narrowing those choices.

When a decision genuinely belongs to the user, the system should respect that decision and make its important consequences understandable. Autonomy does not mean that every system action must be optional: some constraints or communications may be necessary for safety, operation, or legitimate obligations. In such cases, the constraint should be clear, limited to what is necessary, and should not become unnecessary control over the user.

## Agency

Autonomy concerns whether a person can meaningfully choose; agency concerns whether they can meaningfully act on that choice.

Software should help people pursue their own goals and should not secretly alter behaviour in ways that undermine their intent. Automation should extend a person's ability to act rather than silently replacing their judgement.

When software is given authority to act on someone's behalf, that authority should remain connected to the purpose for which it was given rather than becoming an unrestricted licence to act.

## Meaningful Consent

Consent should be informed, voluntary, specific, and meaningful.

A person should not be tricked, coerced, or manipulated into agreeing to something. Where consent is applicable, refusal and withdrawal should be practically possible rather than technically available but deliberately difficult.

At the same time, ordinary operations inherent to something a user has deliberately requested do not each require a separate consent prompt. Participation in one purpose, however, should not silently become permission for unrelated purposes that the person could not reasonably have known they were accepting.

## Transparency

Software should make its meaningful behaviour understandable to the people affected by it.

Users should be able to understand, in plain language where practical, what the system is doing with their data, what important consequences may result from their actions, and what meaningful controls exist.

Transparency does not require exposing every implementation detail. It requires exposing the information necessary for people to understand the parts of the system that materially affect their choices, rights, privacy, or agency.

## Benefit and Avoidance of Harm

Software should be built with the intention of producing meaningful benefit while avoiding foreseeable and unnecessary harm.

When meaningful physical, financial, psychological, social, privacy, or security harm can reasonably be anticipated, the system should take reasonable measures to reduce that risk rather than ignoring it until harm occurs.

Software should be designed so that foreseeable failures and misuse do not unnecessarily become sources of wider harm. This includes considering safe defaults, appropriate permissions, data minimisation, and boundaries that prevent local failures from becoming system-wide failures.

The goal is not to eliminate every possible risk. It is to recognise meaningful foreseeable risks, avoid amplifying them unnecessarily, and make reasonable efforts to reduce their consequences.

## Proportionality

The response of a system should be proportionate to the problem it is intended to solve.

A serious problem may justify a strong intervention, while a minor problem should not become an excuse for extensive surveillance, restriction, or control. When multiple approaches can reasonably solve the same problem, the preferred approach should generally be the one that achieves the legitimate purpose while imposing the least unnecessary burden on autonomy, privacy, agency, or other legitimate interests.

The relevant question is not merely whether an intervention can solve a problem, but whether its magnitude and scope are justified by the magnitude and likelihood of that problem. Temporary or exceptional measures should not become permanent merely because they are convenient.

## Authority and Power

Capability is not the same thing as authority.

The fact that software or an administrator can technically perform an action does not, by itself, establish that the action should be performed. Authority should arise from a legitimate purpose and remain bounded by that purpose.

Administrative capabilities should therefore be designed around administration rather than becoming a privileged substitute for ordinary user interaction. In a communication system, for example, an administrative role should not automatically become a privileged channel for ordinary conversations with users.

When a system genuinely needs to communicate an operational or critical event to many users, that communication should be purpose-specific. A maintenance announcement, security incident notice, or other necessary system communication is different from giving an administrator unrestricted power to send personal messages to every user.

Not every necessary system communication must be optional. Information that users need in order to make informed decisions or avoid harm may need to reach them even when they cannot reasonably opt out. Such communication should nevertheless remain limited to its legitimate purpose and should not become a general mechanism for controlling attention or behaviour.

## Data Stewardship

Data should be treated as something entrusted to software rather than as an unlimited resource available for extraction.

A system should collect, retain, process, and expose only the data that has a legitimate purpose within the system. Data should not be accumulated merely because it might become useful later.

Technical access to data should not be treated as automatic justification for using that access. Access should remain connected to purpose, authority, and necessity. Where users can reasonably be given meaningful control over their data, that control should be provided rather than reduced to a cosmetic setting.

## Reversibility

When a design choice can reasonably be made reversible, it should be.

Software should prefer operations that can be undone and should provide meaningful rollback or recovery mechanisms where appropriate. When an action can cause irreversible consequences, those consequences should be clear and the action should not be broader or easier than necessary.

Reversibility is about recovering from an action after it has happened. It is not always possible, and it does not replace the need to prevent or contain harm in the first place.

## Failure Containment

Software should be designed with the assumption that components will eventually fail, be misused, be misunderstood, or behave differently from what was expected.

A failure in one component should not unnecessarily compromise unrelated components. Permissions, dependencies, network boundaries, destructive operations, and automated actions should be structured so that failures remain contained wherever reasonably possible.

Failure containment is about limiting how far a problem can spread when prevention or immediate recovery is not enough. The objective is to keep the blast radius of a failure as small as reasonably practical and to make failures survivable.

## Human Oversight

When software performs actions with meaningful consequences on behalf of a person, the system should preserve an appropriate level of human understanding and control.

Automation should not make consequential decisions opaque or impossible to challenge simply because a machine has been placed between the person and the action. The amount of human oversight should correspond to the potential consequences of the automated action.

This does not require a human to manually approve every insignificant operation. It means that meaningful authority should not disappear merely because it has been delegated to software.

## Engineering Restraint

Software should solve the problem it actually has rather than accumulating unnecessary complexity, authority, data, or dependencies.

A technically possible capability is not automatically a justified capability. Features, permissions, data collection, and dependencies should have a reason to exist, and their costs in complexity, privacy, security, maintenance, and user control should be considered alongside their benefits.

Simplicity is valuable not only because it makes software easier to maintain, but because unnecessary complexity creates additional places where authority, failure, and unintended behaviour can emerge.

## Revisability

This constitution is not intended to become dogma.

Its principles should remain open to examination, criticism, testing, and revision. If a principle repeatedly produces contradictions, fails in practice, or creates consequences that conflict with the purpose of this constitution, it should be reconsidered rather than defended merely because it was written down earlier.

The constitution should provide a stable direction while remaining capable of correcting itself.

## Scope

These principles apply to projects where I have meaningful authorship or decision-making freedom over what the software is intended to do and how it should interact with its users.

They are not a claim that every software system, organisation, or employer must operate according to my personal philosophy. When I work within another organisation's software, its legitimate requirements, policies, contractual obligations, legal obligations, and product objectives form part of the context in which I operate.

This constitution describes the software I choose to build when the choice is mine.

## Relationship to Project Documentation and Legal Licensing

This constitution is a statement of engineering and design principles. It is not a software licence and does not itself grant, restrict, or revoke copyright, patent, trademark, or other legal rights.

Individual projects may use an established open-source licence or another appropriate legal framework. Project documentation may reference this constitution as the set of principles under which the project was designed, while the project's licence remains the authoritative document for legal permissions and restrictions.

The constitution should guide decisions; the project's legal licence should define legal rights.

---

**Principle:** Build software that gives people more meaningful control over their lives and tools, not less.

## License

This work is licensed under the
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

© 2026 Animesh Kahara
