# Pick Value Lab — Marvel Rivals (Patch 8.5)

Interactive draft simulator for *Marvel Rivals*: estimates **adjusted hero pick value** from
high-ladder ranked matches, then lets you build both team drafts and see the model's expected result.

**Live:** https://plivdan.github.io/pick-value-lab/

A single self-contained HTML page (all data and images embedded). The hero, team-up, and role-structure
values come from a ridge-logistic hero-impact model fit on 23,844 Patch 8.5 competitive matches
(mostly Grandmaster/Celestial), controlling for both teams' heroes, team-ups, role structure, map,
mode, and repeated-player effects. Regenerated automatically as new data is crawled.
