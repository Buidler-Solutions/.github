![Buidler Solutions](https://raw.githubusercontent.com/Buidler-Solutions/datu-ledger/main/docs/assets/org-hero-v2.png)

### Accountable public infrastructure

We build open protocols for institutions whose records must stay true:
registries, titles, certifications, consents. The guiding rule is simple:
**evidence, not badges** - a record is worth what a verifier can check, not
what a vendor promises.

## What we build

<table>
<tr>
<td width="60%" valign="top">

### DATU: a DAG accountability ledger

[![ci](https://github.com/Buidler-Solutions/datu-ledger/actions/workflows/ci.yml/badge.svg)](https://github.com/Buidler-Solutions/datu-ledger/actions/workflows/ci.yml)
[![GESF](https://raw.githubusercontent.com/Buidler-Solutions/datu-ledger/main/badge.svg)](https://github.com/Buidler-Solutions/datu-ledger/blob/main/compliance/attestations-standards.md)

An offline-first accountability protocol on an **Authorship-Strand DAG
(AS-DAG)** and the **Evidence-Centric Ledger** model: independently authored,
cryptographically signed strands stay causally connected instead of being
forced into one global order. Hybrid post-quantum signatures (Ed25519 +
ML-DSA-65), one static binary per node, a Flutter wallet that holds the
citizen's own keys, and signatures from the people a record is about.

> **Trust is not imposed by consensus. It is established through verifiable
> evidence.**

[Repository](https://github.com/Buidler-Solutions/datu-ledger) ·
[Privacy notice](https://github.com/Buidler-Solutions/datu-ledger/blob/main/PRIVACY.md) ·
[Compliance registers](https://github.com/Buidler-Solutions/datu-ledger/tree/main/compliance) ·
[Security policy](https://github.com/Buidler-Solutions/datu-ledger/blob/main/SECURITY.md)

</td>
<td width="40%" valign="top">

![The DATU explorer](https://raw.githubusercontent.com/Buidler-Solutions/datu-ledger/main/docs/assets/explorer.png)

</td>
</tr>
</table>

## How we work

- **Verifiable over asserted.** Releases are reproducible and Sigstore-signed;
  the compliance score is generated from attestations that cite file paths.
- **The citizen holds the keys.** Identity is a key pair on the person's own
  device; registries attest, they do not own.
- **Offline-first.** A ledger that needs the internet to be useful is a
  ledger that fails exactly when records matter most.
- **Compliance as code.** GDPR, OWASP, CIS, NIST, ISO 27001/27701 and the PH
  Data Privacy Act are attested against the repository, with gates in CI.
- **Say what is not true yet.** Known limits are written down (wire privacy
  triggers, plaintext-at-rest on operator disks, scoping of control packs)
  instead of being rounded up.

