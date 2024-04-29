#   `%yard`, A Developer Commons
This is a test
This is a second test

`%yard` is a provisional desk to offer helpful utilities for Urbit-based app development.  Please direct questions and feedback to @sigilante.

As discussed in [UIP-0108](https://github.com/urbit/UIPs/blob/main/UIPS/UIP-0108.md), we are fielding this as a non-core desk before deciding whether and how to more closely integrate it to the standard Urbit distribution.

Some rules of thumb for inclusion in %yard:

- Tools should not replicate (core, standard distribution) functionality unnecessarily, although a case can be made for unification or mirroring.
- Since inclusion in such a desk implies a commitment to maintenance, we prefer to include tools that already fall within the Urbit Foundation's purview.
- No kelvin decrement should be necessary, and Zuse and the rest of the standard library will not be affected. (It is worth noting that %yard will provide a way of gently introducing userspace tools en route to %base, however.)

At the current time, we'd like to see:

- developer feedback on any of the tools included in this desk
- suggestions on what else to consider including
- unit tests that adequately vet the behavior of the included libraries and marks

Among other contributors, `%yard` includes:

- [`/lib/sequent`](https://github.com/jackfoxy/sequent) by ~nomryg-nilref
- [`/lib/regex`](https://github.com/lynko/re.hoon) by ~macrep-racdec
- [`/lib/manx-utils`](https://github.com/tinnus-napbus/manx-utils/) by ~tinnus-napbus
- [`/lib/math`](https://github.com/sigilante/libmath) by ~lagrev-nocfep

