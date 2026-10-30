# Evidence to Claim Builder

Drafts claims for clinicians, patients and payers from trial results, then pre checks them before review.

**[Try the live demo](https://evidence-to-claim-builder.vercel.app)**. It works straight away with no setup, runs entirely in your browser, and stores nothing. All data is fictional or synthetic.

## Why I built it

While mapping a real nutrition therapy evidence base, I kept finding strong results phrased for the wrong reader. A statistic that suits a clinician can be off limits in patient materials. I wanted a tool that gets the first draft right for each audience.

## The problem

Strong evidence still has to be written differently for a clinician, a patient and a payer, and what a product may say depends on what kind of product it is. First drafts that miss this waste reviewers' time.

## What I built

Pick endpoints from two fictional trials, choose an audience and a product category, and get a drafted claim with a transparent pre check covering significance, comparators, study design, population, category rules, citations and overstatement.

## Who it's for

Brand, medical affairs and medical communications teams preparing claims for review.

## What it does

- Select the trial results a claim should rest on, with weak or uncontrolled results clearly labelled
- Switch audience and product category and watch the draft change
- Edit freely while the pre check reruns and names the rule behind each flag

## Decisions that shaped it

1. **One evidence base, several claims:** the audience changes the wording while the evidence stays the same.
2. **The product category sets the rules:** efficacy numbers stay out of patient materials for a medical food, for example.
3. **Every rule is visible:** each flag names the rule behind it.

## Key takeaway

The most honest reading of the evidence is usually narrower and stronger, and the tool shows which results truly support it.

## Built with

- HTML, CSS and JavaScript in a single file

## Run it locally

Open `index.html` in any browser. There's nothing to install.

## About this project

This is a working prototype I built to explore a real problem space. It uses illustrative, fictional data and isn't connected to any organisation's systems. You can find more of my work at [jane-natividad.github.io](https://jane-natividad.github.io).

Built by [Jane Natividad](https://github.com/jane-natividad).
