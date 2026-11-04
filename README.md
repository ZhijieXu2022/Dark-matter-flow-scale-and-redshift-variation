# Dark matter flow data and manuscript: scale and redshift variation of velocity and density distributions

Data and manuscript for **Xu, Z. (2024), *On the statistical theory of self-gravitating collisionless dark matter flow: Scale and redshift variation of velocity and density distributions*, Physics of Fluids 36, 117158, doi:[10.1063/5.0236964](https://doi.org/10.1063/5.0236964), arXiv:[2202.06515](https://arxiv.org/abs/2202.06515)**.

The complete archive, with the same files, is on Zenodo: [doi:10.5281/zenodo.23933115](https://doi.org/10.5281/zenodo.23933115).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23933115.svg)](https://doi.org/10.5281/zenodo.23933115)

## Contents

| Path | Content |
|---|---|
| `P13_revised.pdf` | Manuscript (revised edition) |
| `statistics/` | 53 files, numbered 01 to 53: pair statistics as functions of separation r and redshift. Files 01 to 29 are level-2 statistics, files 30 to 53 are level-3 statistics |
| `figures/` | 32 files: the plotted series of the figures, named by figure number (`Fig01_...` to `Fig34_...`, with `Fig23a` and `Fig23b` as printed) |
| `tables.zip` | 19 CSV files: the tables and the small result sets of the paper (see the index below) |
| `particles_velocity_pdfs.zip` | 13 particle-statistics files and 15 velocity-PDF files |
| `CITATION.cff`, `LICENSE` | citation metadata and licence |

The all-data archive `All_csv_data.zip` (202 MB) is on Zenodo only, because GitHub does not accept single files above 100 MB.

## Format of the CSV files

Each file starts with comment lines beginning with `#`, then a header row, then data.

- `# Publisher`: author and contact.
- `# Updated`: date of the last update.
- `#Name`: what the file contains.
- `#Ref.`: the figure or table of the paper the data belong to, with the DOI.
- `#Note`: processing notes, where needed.

Statistics files use a common layout: the first column is the separation r in Mpc/h, and each further column is one redshift. Values of -1 mark separations where the statistic is not defined for that redshift. Velocities are in units of the rms velocity u(z) of Table 4 unless the header says otherwise. Distances are comoving, in Mpc/h.

## Index of the tables (`tables.zip`)

| File | Content |
|---|---|
| `29_table1_simulation_parameters.csv` | Table 1: simulation parameters |
| `30_table4_a0_and_u_vs_redshift.csv` | Table 4: amplitude a0 and rms velocity u versus redshift |
| `31_table3_generalized_kurtosis.csv` | Table 3: generalized kurtosis |
| `32_kurtosis_large_scale_vs_redshift.csv` | kurtosis on large scales versus redshift |
| `33_beta_star_two_thirds_law.csv` | the constant of the two-thirds law |
| `34_eq12_amplitude_vs_redshift.csv` | amplitude of Eq. (12) versus redshift |
| `35_scale_of_S2_maximum.csv` | scale of the maximum of the second-order structure function |
| `36_correlation_lengths_and_potential.csv` | correlation lengths and potential |
| `37_xi_zero_crossing_vs_redshift.csv` | zero crossing of the correlation function versus redshift |
| `38_fitted_and_derived_scalars.csv` | fitted and derived scalars |
| `39_eq57_bimodal_fit.csv` | bimodal fit of Eq. (57) |
| `40_density_spectrum_nbody_z0.csv` | density spectrum from the N-body simulation, z = 0 |
| `41_density_spectrum_theory_lin.csv` | density spectrum, linear theory |
| `42_density_spectrum_theory_nl.csv` | density spectrum, nonlinear theory |
| `43_xi_theory.csv` | correlation function, theory |
| `44_u_rms_velocity_vs_redshift.csv` | rms velocity u(z) |
| `45_numbers_in_text.csv` | every number quoted in the text, compared with its recomputed value |
| `46_equation_audit.csv` | equation-by-equation audit |
| `47_published_figure_arrays_vs_rebuild.csv` | published figure arrays compared with the rebuilt series |

`particles_velocity_pdfs.zip` holds the one-point particle statistics (`01` to `13`) and the velocity PDFs (`15` files).

## Related datasets

- Dark matter flow dataset, Part I (halo-based statistics): doi:[10.5281/zenodo.6541231](https://doi.org/10.5281/zenodo.6541231)
- Dark matter flow dataset, Part II (correlation-based statistics): doi:[10.5281/zenodo.6757654](https://doi.org/10.5281/zenodo.6757654)
- 2022 preprint of this work: doi:[10.5281/zenodo.6640676](https://doi.org/10.5281/zenodo.6640676)
- Slides, "A comparative study of dark matter flow & hydrodynamic turbulence and its applications": doi:[10.5281/zenodo.6569901](https://doi.org/10.5281/zenodo.6569901)

The simulation is the Virgo SCDM N-body run described in the manuscript.

## Citation

Please cite the article (doi:10.1063/5.0236964) and this archive (doi:10.5281/zenodo.23933115). GitHub's "Cite this repository" button uses `CITATION.cff`.

## Licence

The text, figures and data in this repository are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.
