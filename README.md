# fremtpl2-claim-frequency
# Claim Frequency Modelling with freMTPL2

**Goal:** Predict claim frequency (claims per policy-year) for
French motor third-party liability policies.

**Data:** freMTPL2freq (OpenML), ~678k policies.

**Plan:**
1. Explore data, define target ClaimNb / Exposure
2. Baseline: Poisson GLM
3. Gradient boosting with Poisson loss
4. Compare models (Poisson deviance, calibration)

**Status:** In progress

**Kurzfassung (DE):** Modellierung der Schadenhäufigkeit in der
Kfz-Haftpflicht mit Poisson-GLM und Gradient Boosting.