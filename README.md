# Evidence to Claim — evidence-to-claim-builder

Turns trial results into audience-specific claims — clinician, patient, payer — and runs them through a transparent rule-based pre-check before Medical, Legal and Regulatory review.

**[Live demo](https://evidence-to-claim-builder.vercel.app)** — works immediately, no API key or setup required.

## Who it's for

Brand, medical affairs, and medical-communications teams preparing claims for MLR review across audiences and product categories.

## Why it matters

Strong evidence still has to be written differently for a clinician, a patient, and a payer, and what a product may legally say depends on what kind of product it is. First drafts that ignore this waste reviewers' time.

## What it does

- Select the endpoints the claim should rest on; non-significant and uncontrolled results are labelled
- Switch audience (clinician, patient & caregiver, payer) and product category (prescription medicine, medical food, digital therapeutic)
- Edit the draft freely — the pre-check re-runs as you type and names the rule behind each flag

## Product decisions that mattered more than the code

1. **One evidence base, several compliant claims** — audience changes the claim, not the evidence
2. **Category sets the rules** — e.g. efficacy statistics routed away from patient materials for a medical food
3. **Every rule is visible** — no model decides what's compliant

## Built with

- HTML, CSS, JavaScript (single-file prototype, no build step)

## Run locally

Open `index.html` in any browser.

## Status

This is a prototype built to explore a problem space, using illustrative/fictional data — not a finished product and not connected to any organization's real systems. Built by [Jane Natividad](https://github.com/jane-natividad) — see more at [jane-natividad.github.io](https://jane-natividad.github.io).
