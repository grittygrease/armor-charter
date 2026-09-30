# ARMOR Research Group (IRTF) - Proposed Charter v0.2 (draft)

Draft for discussion on armor@irtf.org and at the IETF 127 side meeting. Not
adopted. The changes from v0.1 follow the IETF 124 side meetings in Montreal;
see the README.

## Mission

Advance the end-to-end resilience of Internet protocols against on-path
interference, whether adversarial or unintended.

## Scope

Interference here means disruption of end-to-end communication by something
on the path that is not approved by both endpoints: deep packet inspection,
injection and manipulation, throttling, and forced protocol downgrade. ARMOR
describes interference by its effects and does not judge the intent behind it.

The core of the work is constructive, turning what is known about
interference into protocol and deployment changes:

- Testbeds and tools that reproduce interference and evaluate countermeasures.
- Building blocks that let applications detect interference and switch
  strategies, such as composable networking libraries and cross-platform APIs.
- Datasets on interference and protocol behavior, with their access terms.
- Design, analysis, experimental specification, and evaluation of adaptive
  techniques (e.g., overlay routing, multi-path, polymorphism, traffic
  obfuscation, tunneling).
- Deployment studies for emerging mechanisms (e.g., ECH, MASQUE); theory
  that informs practice.

Empirical measurement of interference and protocol behavior stays in scope as
the input to this work. Evaluations consider what a failure means for the
people using the connection, not only whether it fails, and check that
countermeasures do not add new risks such as a larger denial-of-service
surface.

## Non-Goals

Policy advocacy; standards-track protocol development; product promotion;
real-time incident response; general outages and natural disasters.

## Outputs

IRTF-stream Informational or Experimental documents and shared resources,
starting with three:

1. A short terminology and threat model document, distinguishing for example
   tampering, interference, censorship, and downgrade, and adversarial from
   unintended disruption.
2. A public catalog of datasets and testbeds with their access terms,
   starting from sources already identified (e.g., OONI, Mozilla telemetry).
3. A survey of operators and implementers on what blocks deployment.

## Coordination

ARMOR complements PEARG (privacy), MAPRG (measurement), HRPC (human-rights
considerations), and GAIA (access) rather than duplicating them. It takes
findings to the relevant IETF working groups (e.g., MASQUE, TLS, DNS) as input
to protocol and deployment guidance. A fuller mapping against HRPC, MAPRG,
and PEARG is in progress.

## Participation

Open to researchers, engineers, and operators from academia, industry, and
civil society.

## Meetings

ARMOR meets 1-3 times per year, with at least one meeting co-located with an
IETF meeting; sessions are open, recorded when possible, and support remote
participation.

## Open questions for IETF 127

- Should the constructive work be the core, or is measurement alone the
  clearer focus? The room in Montreal was split.
- Are these the right three outputs to start with?
- How exactly does ARMOR complement HRPC, MAPRG, and PEARG?
