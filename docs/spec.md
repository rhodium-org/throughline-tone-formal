# Tone — Formal register — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates
it in CI. The prose headings are hand-owned — everything between `tl:*` markers is
injected from the YAML items, so the published spec can never drift from the graph.

This source is the **tone / register axis** for one register: **formal**. It governs
how the writing *sounds* relative to the reader relationship — not readability,
spelling, punctuation, genre, medium or brand voice, each of which is its own
throughline source. Register variants are mutually exclusive: **formal**, **neutral**
and **informal** are sibling sources and a consumer composes exactly one under the
`tone` namespace. Every principle is a `user_requirement`; every rule is a
`system_requirement` that `implements` its principle. The throughline UIDs are this
source's own and immutable — a consumer cites a rule as `tone:SR-0001`.

It carries
<!-- tl:count type == 'user_requirement' -->
5
<!-- tl:end --> principles and
<!-- tl:count type == 'system_requirement' -->
10
<!-- tl:end --> rules.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — Text sounds consistently formal and professional** — `intent`, status `approved`

> A formal register signals seriousness, authority and respect for distance. It suits legal, regulatory, financial and official writing, where the reader expects the organisation to sound measured and impersonal. This axis governs register — how the writing sounds relative to the reader relationship — not readability, spelling or punctuation, each of which is a separate source. Register variants are mutually exclusive: a consumer composes exactly one of the formal, neutral or informal sibling sources.

**source_ref**: TBS Tone — Formal register
<!-- tl:end -->

## 1. Use full grammatical forms, not contractions

<!-- tl:item UR-0001 -->
**UR-0001 — Use full grammatical forms, not contractions** — `user_requirement`, status `approved`

> Write auxiliary and negative forms out in full.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Formal register — Contractions
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0001' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | approved | Write auxiliaries and negatives in full, not contracted |
| SR-0002 | system_requirement | approved | Avoid colloquial elisions and clipped words |
<!-- tl:end -->

## 2. Address the reader with professional distance

<!-- tl:item UR-0002 -->
**UR-0002 — Address the reader with professional distance** — `user_requirement`, status `approved`

> Keep salutation and naming impersonal and respectful.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Formal register — Address and greeting
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0002' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0003 | system_requirement | approved | Use a formal salutation, never a casual greeting |
| SR-0004 | system_requirement | approved | Keep address impersonal; avoid the reader's first name in running text |
<!-- tl:end -->

## 3. Choose neutral, professional vocabulary

<!-- tl:item UR-0003 -->
**UR-0003 — Choose neutral, professional vocabulary** — `user_requirement`, status `approved`

> Avoid slang, idiom and emotive colour; state things plainly.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Formal register — Vocabulary register
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0003' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0005 | system_requirement | approved | Avoid slang, idiom and figurative expressions |
| SR-0006 | system_requirement | approved | Avoid emotive intensifiers |
<!-- tl:end -->

## 4. State points with measured assertiveness

<!-- tl:item UR-0004 -->
**UR-0004 — State points with measured assertiveness** — `user_requirement`, status `approved`

> Be plain and precise about obligations; hedge only for genuine uncertainty.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Formal register — Directness
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0004' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0007 | system_requirement | approved | State obligations and decisions plainly, without coaxing |
| SR-0008 | system_requirement | approved | Hedge only for genuine uncertainty |
<!-- tl:end -->

## 5. Keep courtesy restrained and professional

<!-- tl:item UR-0005 -->
**UR-0005 — Keep courtesy restrained and professional** — `user_requirement`, status `approved`

> Offer standard courtesy without warmth-signalling or humour.

*Derives from:* INT-0001

**source_ref**: TBS Tone — Formal register — Warmth and social signals
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0005' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0009 | system_requirement | approved | Keep thanks and courtesies brief and standard |
| SR-0010 | system_requirement | approved | Do not use humour or playful asides |
<!-- tl:end -->
