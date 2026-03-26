# Graphene Integration Route Verifier

Interactive verification tool accompanying Paper 4:
**"Graphene Integration Route Selection for Ferroelectric Photonic Memory: 
A Bayesian Quality Assessment Across Ten Process Scenarios"**
Solbakken R&D · March 2026

## What this tool does

Enter your process measurements — carrier mobility, carrier density, domain size, 
defect density, and monolayer coverage — and receive a personalised route ranking 
against the paper's literature-anchored baseline priors.

Output includes:
- Route ranking by joint pass probability P(all 5 Goldilocks criteria)
- Binding constraint diagnosis per route
- Comparison against paper baseline (Routes F, I, J Pareto front)
- Plain-language assessment with process development guidance

## How to use

Open the live tool: [link to your GitHub Pages URL once live]

Or download `graphene_route_verifier.html` and open in any modern browser.
No installation required. Runs entirely client-side.

## Methodology

Based on correlated lognormal Monte Carlo simulation (N = 100,000 samples) 
with literature-anchored priors. User measurements update prior means with 
a 60/40 weighting toward measured values. Full methodology in the paper.

## Note on thresholds

Goldilocks window sized for a 64×64 MVM tile with 0.5 dB total insertion 
loss budget. Relaxing to 1.0 dB shifts Route I baseline from 38.6% to ~45.9%.

---
Solbakken R&D · Independent Research · Confidential pre-publication release
