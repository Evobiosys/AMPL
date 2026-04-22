# AMPL — Adapted Modular Public License 1.0

The canonical source for **AMPL 1.0**, a copyleft software license that takes
[Mozilla Public License 2.0](https://www.mozilla.org/MPL/2.0/) and adds a
single clause: a **parallel network-use obligation** at the file level.

It does for MPL what AGPL did for GPL — closes the "service over the network"
loophole — but keeps MPL's defining feature, which is *file-level* copyleft
rather than work-level copyleft.

Created under MPL 2.0 Section 10.3, which explicitly authorizes derived
licenses provided they are renamed.

## Quick facts

| | |
|---|---|
| **License name** | Adapted Modular Public License |
| **Version** | 1.0 |
| **Steward** | Jakob Possert-Bienzle (intended to transfer to the EvoBioSys Foundation in AMPL 2.0) |
| **First published** | 2026-04 |
| **Derived from** | [MPL 2.0](https://www.mozilla.org/MPL/2.0/) (under MPL Section 10.3) |
| **Adds** | Section 3.5 — Network Use, scoped to Covered Software |
| **Reusable** | Yes — by anyone, for any project |

## What's different from MPL 2.0

Exactly one substantive addition: **Section 3.5 (Network Use)**.

> If You deploy a modified version of Covered Software to provide a service to
> users interacting with it remotely through a computer network, and that
> version supports such interaction, You must make the Source Code of the
> modified Covered Software available under the terms of this License […].

That's the AGPL-style step. Everything else — patent grants, file-level
copyleft, Larger Work compatibility, secondary-license compatibility with
GPL/LGPL/AGPL, disclaimer of warranty, limitation of liability — comes
verbatim from MPL 2.0.

The only other changes are housekeeping: the original MPL Section 3.5
(Application of Additional Terms) is renumbered to 3.6, and Section 10.1
names the AMPL steward instead of Mozilla.

## Adopting AMPL in your project

1. Copy [`LICENSE`](LICENSE) into the root of your repository.
2. Attach the **Exhibit A** notice (bottom of `LICENSE`) to source files:

   ```
   This Source Code Form is subject to the terms of the Adapted Modular
   Public License, v. 1.0. If a copy of the AMPL was not distributed with
   this file, You can obtain one at https://evobiosys.org/legal/ampl-1.0.
   ```

3. Optionally, point a `LICENSE-NOTICE` or your README at this repo as the
   canonical source: <https://github.com/Evobiosys/AMPL>.

You do **not** need permission from the steward to adopt AMPL for your own
project. AMPL is a public license, freely usable by anyone.

## Canonical URLs

- This repository: <https://github.com/Evobiosys/AMPL>
- Web canonical (Exhibit A points here): <https://evobiosys.org/legal/ampl-1.0>
- Upstream (MPL 2.0): <https://www.mozilla.org/MPL/2.0/>

## Projects that supplement AMPL with their own addenda

- **EvoBiosys License** — AMPL 1.0 + a revenue-threshold commercial-license
  tier: <https://github.com/Evobiosys/license>
