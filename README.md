Nor'easters
==============================================
This repository contains the data and code necessary to reproduce the results presented in: <a href="[https://www.pnas.org/doi/10.1073/pnas.2504482122](https://www.pnas.org/doi/10.1073/pnas.2510029122)"> Chen et al. (2025), The intensification of the strongest nor’easters</a>, Proceedings of the National Academy of Sciences, 122 (29), e2510029122.

Related Publication
-------------------
Chen, K., X. Li, M. M. Weaver, S. A. Christiansen, A. L. Horton, and M. E. Mann (2025), The intensification of the strongest nor’easters, Proceedings of the National Academy of Sciences 122 (29) e2510029122, <a href="https://www.pnas.org/doi/10.1073/pnas.2504482122">https://doi.org/10.1073/pnas.2504482122</a>.

Files descriptions
-----------------
Data (located in the noreasters/ directory):
* `YYYY_tracks_final.csv`  &rarr; Summary of nor'easters (1940–2025), identified based on the methodology outlined in [Noreaster_tracking_workflow.pdf](Noreaster_tracking_workflow.pdf)

Code (located in the scripts/ directory):
* `Fig2_spaghetti_plot_trajectories.ipynb` &rarr; Generates the composite plot of nor’easter tracks for 1940–2025 (Fig. 2) using the summary dataset.
* `Fig3_notable_noreasters_trajectories.ipynb` &rarr; Plots the trajectories of four notable nor’easters featured in Fig. 3.
* `Fig4_ws_quantile_reg_and_mannkendall.ipynb` &rarr; Analyzes trends in lifetime maximum wind speeds (1940–2025) using quantile regression. The notebook investigates:
  - (1) Statistical significance using least-squares regression (Figs. 4, S5, S7) and non-parametric Mann–Kendall analysis (Figs. S1, S6, S8);
  - (2) Sensitivity to input data sources (entire record vs. satellite era; see Fig. S2);
  - (3) Alternative timeframes (e.g., 1950–2025; Figs. S3, S4);
  - (4) Sensitivity to storm radii: 500 km (Figs. S5, S6), 750 km (Figs. 4, S1), and 1000 km (Figs. S7, S8).
* `Fig5_mean_hourly_precipitation.ipynb` &rarr; Produces time series plots of hourly precipitation associated with nor’easters, and annual trends from 1940 to 2025 (Fig. 5). Sensitivity to storm radii (500 km, 750 km, 1000 km) is assessed (see Fig. S9). 
