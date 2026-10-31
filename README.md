# F1RegulationChanges

Two-way fixed effects model distinguishing driver skill and car performance in Formula One Qualifying. Relative team change after regulation changes at 2022 and 2026.

## Reproduction

Timing data is not included in this repository. To reproduce this analysis, execute the F1RegulationChanges.ipynb notebook from top to bottom. FastF1 will fetch the data from Formula One's timing service and store it on your machine in the data/ folder. This will not be included in the repository. ff1_cache/ is also not included in the repository. On first execution this will take a while.

All the tables and figures in this paper (7 figures) will be produced including the wild cluster bootstrap p-values (6c.1).
