# Experience 3fc6e8c3 — Referral Acquisition with Paid Pilot to Large Contract

**Author:** Ivan Pasichnyk (`ivan-pasichnyk`)
**Outcome label:** `engaged` at `day_+65`
**Duration:** 65 days · 21 steps
**License:** MIT

## What is published

A 65-day inbound B2B acquisition arc in the sports-vertical broadcast analytics space, anonymized step by step. The pack ships **raw**: the timeline as it happened, plus a facts-only `meta.yaml`. There is **no `applies_when`**, **no summary**, **no author grade reason**. Those are interpretations and are deliberately omitted — the reader's Claude derives match from the trajectory on the fly.

Shape of the arc, in raw structural terms: counterparty technical decision-maker books an inbound discovery via the founder's calendar booking link → discovery call → mutual NDA on counterparty's template signed both sides → counterparty shares sample data + initial scope (multi-sport, low-seven-figure frame target) → free pilot labeling by author's operations lead → two-week iteration on quality and taxonomy → counterparty asks for cost estimate → pricing call → rate aligned at low hourly band, aggregate value lands in the six-figure range → operational follow-up on contract/billing → counterparty "intend to move forward", asks for contract draft → author sends draft Service Agreement → short follow-up + counterparty confirms "reviewing with counsel this week" → external counsel returns moderate redlines → author accepts all redlines without counter (sub-12-hour turnaround) → counterparty sends fresh US e-signing envelope → author signs → counterparty principal (CEO) provides final signature → fully executed.

## Files

- `meta.yaml` — facts only (id, outcome label, duration, category tokens, license)
- `trajectory.anonymized.yaml` — the timeline (21 ordered steps from `relative_day: 0` to `relative_day: +65`)
- `SKILL.md` — Claude entry point

Counterparty identity replaced with category tokens (`<counterparty_tech_dm>`, `<counterparty_legal_signer>`, `<counterparty_principal>`, `<counterparty_external_counsel>`, `<us_e_signing>`, `<rate:hourly_low>`, `<value:100k-1m>`, etc.). Author identity is public — it signs the pack.

## How to install

```bash
git clone https://github.com/anthroos/exp-referral-acquisition-with-paid-pilot-to-large-contract.git
cp -r exp-referral-acquisition-with-paid-pilot-to-large-contract \
  ~/.claude/skills/openexp:ivan-pasichnyk:referral-acquisition-with-paid-pilot-to-large-contract/
```

Auto-discovered on next Claude Code session. To use the pack, install the `openexp-use` Claude Code skill alongside it (one-time setup, applies to all packs):

```bash
git clone https://github.com/anthroos/claude-skills.git
ln -s ~/claude-skills/skills/core/openexp-use ~/.claude/skills/openexp-use
```

Then describe your situation in your own words — `openexp-use` will discover this pack, read its trajectory, and reply with a cited `relative_day`.

## Why this pack might be useful to you

Compared to the author's other published packs, this one covers a **larger-value contract arc** (six-figure aggregate vs hourly-low-band per-batch) with **counsel-driven redlines** as a real friction point and **US e-signing** rather than local-jurisdiction platforms. The fully-executed terminal step at day +65 is reached without principle-of-the-thing pushback on counsel's redlines — that decision is one of the load-bearing moves in the arc.
