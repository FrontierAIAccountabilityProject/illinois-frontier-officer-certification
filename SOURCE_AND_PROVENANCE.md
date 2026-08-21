# Source and provenance

## What this repository is

A public-domain legislative research draft amending an **enacted Illinois statute**: the
Artificial Intelligence Safety Measures Act, **430 ILCS 185**, created by **P.A. 104-0538** and
amended by **P.A. 104-0466**, effective **1 January 2027**.

It is not a standalone regulatory scheme. It adds a natural-person certification layer to duties
Illinois has already enacted, and leaves the compute threshold, the revenue threshold, the covered
class and the technical safety standards exactly as they were passed.

**The official Illinois publication controls wherever it differs from this draft.**

## Its relationship to the wider project

This draft is the **Illinois-specific adaptation** of a proposal published in two other places:

| | |
|---|---|
| **General model legislation**, for adoption by any state — Frontier Artificial Intelligence Responsible Officer Act, draft 0.1 | <https://github.com/FrontierAIAccountabilityProject/frontier-ai-responsible-officer-act> |
| **The research project** behind both — Model Act (Frontier AI Public Welfare Offenses), v3.4, with the drafting record, evidence dossier, errata register and open cure queue | <https://github.com/FrontierAIAccountabilityProject/model-act> · archived at <https://doi.org/10.5281/zenodo.22029795> |

A parallel adaptation exists for **New York's RAISE Act** at
<https://github.com/FrontierAIAccountabilityProject/raise-officer-certification>. The three drafts
share a design and differ in the statute each amends. **They are not interchangeable, and this
repository has previously served the wrong one** — see *Corrections*, below.

## The provision this draft completes

Illinois already requires the annual independent audit report to contain, at
**430 ILCS 185/10(d)(2)(C)**:

> a detailed assessment of the large frontier developer's internal controls, including its
> designation and empowerment of senior personnel responsible for such implementation by the large
> frontier developer, its employees, and its contractors

and, four items later at **430 ILCS 185/10(d)(2)(G)**:

> the signature of the lead auditor certifying the results of the audit

So an independent party must verify that a responsible person has been designated and genuinely
empowered — and the only signature the statute requires is that independent party's. The person
whose authority was just verified signs nothing. **That is the gap this draft closes, and nothing
in it adds any obligation to the auditor.**

## What was and was not carried across

**Carried across** from the general draft: the controlling-person test based on final material
decision authority rather than title; the express exclusions for status, credentials, technical
access, advice and ministerial implementation; the non-delegable duty of reasonable inquiry; the
public signature register; and the bar on indemnification, insurance, reimbursement or
compensation offset of an individual penalty.

**Not carried across:** the general draft's own thresholds and adopting-state nexus, replaced by
Illinois's enacted thresholds; and any criminal provision. **This draft creates no criminal
offense and no private right of action.** Enforcement is by the Attorney General alone, against a
signer for breach of that signer's own duty, and never merely because the company violated
something else.

## Integrity

`SHA256SUMS.txt` lists digests for the files actually present in this repository. It is
regenerated whenever a listed file changes; **a stale manifest is worse than none**, because it is
a claim about verification that fails the moment a reader runs it.

`TABLE_OF_AUTHORITIES.md` is the authority base of the **Model Act v3.4**, from which this draft's
doctrine derives. It was not compiled against this Illinois text, and says so at its head.

## Corrections

This project publishes its own errors rather than quietly patching them; the register lives in the
[model-act repository](https://github.com/FrontierAIAccountabilityProject/model-act/blob/main/ledger/errata.md).

Recorded against this repository:

- **21 August 2026.** For part of one evening this repository served, as `SPONSOR_MEMO.md`, the
  sponsor memorandum for the **New York RAISE** draft, and its `CITATION.cff` described the
  general Responsible Officer Act at the wrong version and URL. Both corrected the same day.
- **21 August 2026.** A wider audit then found that `SOURCE_AND_PROVENANCE.md`, `SHA256SUMS.txt`
  and `TABLE_OF_AUTHORITIES.md` had also been carried over unadapted from the general-act
  repository. The manifest listed **eight files this repository does not contain**. This file is
  the replacement; the manifest was regenerated; the table of authorities was rescoped honestly
  rather than rewritten.

**Cause, stated plainly:** this repository was created by copying a sibling repository, and only
some of the files were adapted. **Nothing in the process required anyone to read the rest.**

## AI assistance

This draft was prepared with AI assistance, disclosed. **AI output is not authority.** Every legal
proposition requires review against primary sources, and no completed professional review is
claimed.

## Attribution and reuse

Dedicated to the public domain under CC0 1.0. **No permission, attribution or acknowledgment is
required for legislative use.** A citation to the version and commit is nevertheless useful, so a
reader can identify the text on which a review or introduction was based.
