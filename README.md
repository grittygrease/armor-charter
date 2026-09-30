# ARMOR charter

Working text of the charter for ARMOR, a proposed IRTF research group on
protocol resilience against on-path interference. Nothing here is adopted.
Research groups are chartered by the IRTF Chair.

- Current draft: [charter.md](charter.md) (v0.2)
- v0.1, as posted to the list on 19 September 2025:
  [tag v0.1](https://github.com/grittygrease/armor-charter/blob/v0.1/charter.md)
  and the [list archive](https://mailarchive.ietf.org/arch/msg/armor/nQgZ_7tBE4ZnsehQnrKLTb02QW0/)
- What changed:
  [v0.1...main](https://github.com/grittygrease/armor-charter/compare/v0.1...main)

## Where v0.2 comes from

v0.2 applies what the two ARMOR side meetings at IETF 124 in Montreal
(November 2025) pointed to, as summarized in the
[recap to the list](https://mailarchive.ietf.org/arch/msg/armor/Ra3ogsNuAnykRW1axWB2UynRj-E/)
and the
[IETF 127 note](https://mailarchive.ietf.org/arch/msg/armor/OvvT6beTOEUgkkD-QOoHU3-W6_w/):

- The scope narrows to end-to-end resilience against on-path interference,
  adversarial or unintended, described by its effects rather than intent.
  General outages and natural disasters are out.
- Constructive work (testbeds, tools, datasets, experimental specifications)
  becomes the core, with measurement as its input. This isn't settled; it's
  the first open question for San Francisco.
- A few named outputs replace the open-ended list.
- From the first session's talks: building blocks that let applications
  switch strategies under interference, evaluation from the user's side of a
  failed connection, and a view of tampering broader than censorship.

## Discussion

The home for discussion is armor@irtf.org
([archive](https://mailarchive.ietf.org/arch/browse/armor/)). Issues and pull
requests are welcome here too, but please raise anything substantive on the
list. Contributions are subject to the
[IETF Note Well](https://www.ietf.org/about/note-well/).
